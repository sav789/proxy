# proxy
This is a simple proxy written in C
Design of a Daemon Process Acting as a TCP Proxy Server 
We would suggest putting all files on the desktop!!!
This code was compiled on Mac or Linux!!!
1.	How to Compile the program: gcc proxy.c –o proxy
2.	Then the compiler generates an executable file “look on your desktop”
3.	How to run program:  ./proxy <proxy_port_num>  
  a.	An example: ./proxy 6060
  b.	6060 this part of the example is your proxy port which is designated by the proxy server port
  c.	Now the result of this command is to bind the proxy_port port of the proxy server to the service_port port of remote_host. 
  d.	Then we can use the proxy_port port through the proxy server to access the remote_host. 
4.	Ex: Next go to a browser and change the proxy address to: ranger2.cs.mtsu.edu and port to number 6060
5.	Then connection should be established and you will see the GET and Host from http header and the connected IP address.
