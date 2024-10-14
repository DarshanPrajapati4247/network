# Notes: UDP sendto and recvfrom (Week 4- UDP sendto recvfrom.pdf)

## UDP Datagrams

- UDP does not maintain a connection (session)

## sendto Function

- Purpose: Send UDP datagrams
- Syntax: `sendto(sockfd, buf, len, flags, *to, tolen)`
- Key points:
  - `to` is a pointer to a struct sockaddr
  - Returns the number of bytes actually sent (might be less than requested)
  - Returns -1 on error

## recvfrom Function

- Purpose: Receive UDP datagrams
- Syntax: `recvfrom(sockfd, buf, len, flags, *from, *fromlen)`
- Key points:
  - `from` is a pointer to a local struct sockaddr_storage
  - Returns the number of bytes received
  - Returns -1 on error

## Reference
- Brian "Beej Jorgensen" Hall. Beej's Guide to Network Programming. 
  https://beej.us/guide/bgnet/html/split/index.html

