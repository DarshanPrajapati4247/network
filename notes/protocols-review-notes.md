# Notes: Protocols Review (Week 1 - Protocols Review.pdf)

## Internet Overview

- Definition: "Network of networks"
- Components:
  - Billions of connected computing devices (hosts = end systems)
  - Packet switches (routers, switches)
  - Communication links (fiber, copper, radio, satellite)
  - Networks (collections of devices, routers, links managed by organizations)
  - Interconnected ISPs

## Protocols

- Definition: Rules that define the format, order of messages sent and received among network entities, and actions taken on message transmission, receipt
- Examples: HTTP, streaming video, Skype, TCP, IP, WiFi, 4/5G, Ethernet

## Internet Standards

- RFC: Request for Comments
- IETF: Internet Engineering Task Force

## Protocol Layers

1. Application Layer
   - Supports network applications
   - Protocols: HTTP, IMAP, SMTP, DNS

2. Transport Layer
   - Process-to-process data transfer
   - Protocols: TCP, UDP

3. Network Layer
   - Routing of datagrams from source to destination
   - Protocols: IP, routing protocols

4. Link Layer
   - Data transfer between neighboring network elements
   - Protocols: Ethernet, 802.11 (WiFi), PPP

5. Physical Layer
   - Bits "on the wire"

## Encapsulation

- Each layer adds its own header to the data from the layer above
- Process: Message -> Segment -> Datagram -> Frame

## Wireshark

- Purpose: Packet analyzer tool
- Captures and analyzes network traffic at various layers (Ethernet, IP, TCP/UDP, Application)

