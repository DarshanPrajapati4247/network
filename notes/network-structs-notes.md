# Notes: Network Structs (Week 2 - Network Structs.pdf)

## IP Addresses and C Structs

1. **struct addrinfo**
   - Purpose: To prepare socket address structures for subsequent use

2. **struct sockaddr**
   - Purpose: Holds socket address information for many types of sockets

3. **struct sockaddr_in**
   - Purpose: Makes it easy to reference elements of the socket address
   - Specific to IPv4

4. **struct in_addr**
   - Purpose: IPv4 only, for historical compatibility

5. **struct sockaddr_in6**
   - Purpose: Makes it easy to reference elements of the socket address when using IPv6

6. **struct sockaddr_storage**
   - Purpose: Flexibility - holds both IPv4 and IPv6 structures
   - Useful when you don't know in advance which IP version will be used

## Function: inet_pton

- Name stands for: "Presentation to network"
- Purpose: Converts an IP address in numbers-and-dots notation into either a struct in_addr or a struct in6_addr

## Reference
- Brian "Beej Jorgensen" Hall. Beej's Guide to Network Programming. 
  https://beej.us/guide/bgnet/html/split/index.html

