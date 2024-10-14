[Note: The previous 100 questions remain unchanged. I'm adding the following 30 questions to the end of the existing set.]

101. What is the purpose of the epoll() system call in Linux?
    a) To handle multiple network connections efficiently
    b) To encrypt network traffic
    c) To compress data before transmission
    d) To resolve domain names

102. In C, what is the difference between calloc() and malloc()?
    a) calloc() initializes the allocated memory to zero, malloc() does not
    b) malloc() can allocate more memory than calloc()
    c) calloc() is faster than malloc()
    d) There is no difference

103. Which protocol is used for secure file transfer?
    a) FTP
    b) HTTP
    c) SFTP
    d) SMTP

104. What is the purpose of the SO_KEEPALIVE socket option?
    a) To keep the connection alive by sending periodic packets
    b) To keep the socket open even after the process terminates
    c) To keep the data in the socket buffer after closing
    d) To keep the IP address assigned to the socket

105. In C, what does the volatile keyword indicate?
    a) The variable can be changed by hardware
    b) The variable should be stored in RAM
    c) The variable is constant
    d) The variable is thread-safe

106. What is the main purpose of the Nagle algorithm in TCP?
    a) To reduce the number of small packets sent over the network
    b) To increase the speed of large file transfers
    c) To encrypt network traffic
    d) To compress data before transmission

107. Which of the following is NOT a valid errno value in network programming?
    a) EAGAIN
    b) EWOULDBLOCK
    c) EINPROGRESS
    d) ENOTNETWORK

108. What is the purpose of the fcntl() function when used with F_SETFL and O_NONBLOCK flags?
    a) To set a socket to non-blocking mode
    b) To set a file descriptor to blocking mode
    c) To set a socket to UDP mode
    d) To set a file descriptor to read-only mode

109. In C, what is the purpose of the restrict keyword?
    a) To indicate that a pointer doesn't alias with any other pointer
    b) To make a variable constant
    c) To allocate memory on the stack
    d) To prevent a variable from being optimized by the compiler

110. What is the primary purpose of the ARP protocol?
    a) To resolve IP addresses to MAC addresses
    b) To assign IP addresses dynamically
    c) To route packets between networks
    d) To encrypt network traffic

111. Which system call is used to wait for I/O events on multiple file descriptors?
    a) wait()
    b) select()
    c) poll()
    d) Both b and c

112. In C, what is a union?
    a) A data type that can hold different types of data at different times
    b) A combination of multiple structures
    c) A special kind of array
    d) A type of network connection

113. What is the purpose of the MSG_PEEK flag in the recv() function?
    a) To view incoming data without removing it from the queue
    b) To prioritize the received message
    c) To check if the connection is still alive
    d) To receive out-of-band data

114. Which of the following is NOT a valid IP address?
    a) 192.168.0.1
    b) 10.0.0.1
    c) 172.16.0.1
    d) 256.0.0.1

115. What is the main difference between big-endian and little-endian byte order?
    a) The order in which bytes are stored in memory
    b) The size of the memory allocation
    c) The speed of memory access
    d) The way memory is freed

116. In C, what does the static keyword do when used with a global variable?
    a) Makes the variable accessible only within the file it's declared in
    b) Allocates the variable on the heap
    c) Makes the variable constant
    d) Increases the variable's scope to all linked files

117. What is the purpose of the getpeername() function?
    a) To get the name of the local host
    b) To get the name of the remote peer connected to a socket
    c) To get the IP address of a hostname
    d) To get the port number of a service

118. Which protocol operates at the Network layer of the OSI model?
    a) TCP
    b) UDP
    c) IP
    d) HTTP

119. What is the main purpose of the htons() function?
    a) To convert a short integer from host byte order to network byte order
    b) To convert a long integer from host byte order to network byte order
    c) To convert an IP address from host format to network format
    d) To convert a hostname to an IP address

120. In C, what is the purpose of the extern keyword?
    a) To declare a variable or function that is defined in another file
    b) To create a new variable
    c) To allocate memory dynamically
    d) To make a variable constant

121. What is the primary function of ICMP (Internet Control Message Protocol)?
    a) To provide error reporting and diagnostic information
    b) To establish reliable connections
    c) To assign IP addresses dynamically
    d) To encrypt network traffic

122. Which system call is used to change the owner of a file?
    a) chmod()
    b) chown()
    c) fchown()
    d) Both b and c

123. In C, what does the sizeof operator return?
    a) The number of elements in an array
    b) The memory address of a variable
    c) The size in bytes of a data type or variable
    d) The length of a string

124. What is the purpose of the SO_REUSEADDR socket option?
    a) To allow multiple sockets to bind to the same port
    b) To reuse the same memory address for multiple sockets
    c) To enable address resolution for the socket
    d) To allow the socket to use reserved ports

125. Which of the following is NOT a valid socket domain?
    a) PF_INET
    b) PF_INET6
    c) PF_UNIX
    d) PF_HTTP

126. What is the main purpose of the struct sockaddr_storage?
    a) To store both IPv4 and IPv6 addresses
    b) To store multiple socket addresses
    c) To provide temporary storage for socket operations
    d) To manage socket options

127. In C, what is a void pointer?
    a) A pointer that can point to any data type
    b) A pointer that points to nothing
    c) A pointer to a void function
    d) A pointer that cannot be dereferenced

128. What is the purpose of the listen() system call?
    a) To accept incoming connections
    b) To mark a socket as passive, ready to accept incoming connections
    c) To connect to a remote server
    d) To start listening for incoming data

129. Which protocol is used for secure email transmission?
    a) SMTP
    b) POP3
    c) IMAP
    d) SMTPS

130. In C, what is the difference between a structure and a union?
    a) A structure can hold multiple members simultaneously, a union can hold only one
    b) A union can hold multiple members simultaneously, a structure can hold only one
    c) A structure is for network programming, a union is for file I/O
    d) There is no difference

Answers:
101. a, 102. a, 103. c, 104. a, 105. a, 106. a, 107. d, 108. a, 109. a, 110. a,
111. d, 112. a, 113. a, 114. d, 115. a, 116. a, 117. b, 118. c, 119. a, 120. a,
121. a, 122. d, 123. c, 124. a, 125. d, 126. a, 127. a, 128. b, 129. d, 130. a

