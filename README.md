# iperf-pods

This project demonstrates the deployment of two pods using iperf3 image. One pod is considered as server and other is considered as a client. 
On pod-1: iperf3 -s -p 3000 -f M 
On pod-2: iperf3 -c pod-1-IP-adddress -p 3000 -f M

Output: 
The bandwith between 2 pods is displayed as output
