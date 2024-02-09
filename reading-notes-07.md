## Reading
## SSH Protocol

1. What is the Secure Shell (SSH) Protocol?
   * Method of secure remote login from one system to another, this is explicitly a text-based terminal connection
3. What are the typical uses of the SSH protocol?
   * Remote commands, managing infrastructure from a distance, and interactive file transfers
5. How does the SSH protocol work?
   * server contact, receive a public key, authentication, login to os
7. How is the data kept safe when transmitted between the SSH client and server?
   * It is encrypted with parameters set during the authentication negotiation
9. What is SFTP?
    * Secure File Transfer Protocol: file transfer over SSH 

    
## What is RDP? And how to use it
1. What is Windows Remote Desktop Connection?
   * A tool that allows a user to remotely connect to a pc or server over the internet or local network
3. What is RDP?
   * This is the actual protocol that the remote desktop connection uses to communicate with the two devices. These two devices are the server and the client
5. What is the RDP port number?
   * 3389
## Things I would like to know more about 

* For SFTP: How can I implement key-based authentication in SFTP to enhance security beyond just password-based authentication?
* For SSH: What are the best practices for hardening an SSH server, particularly in terms of configuring ciphers, MACs, and key exchange algorithms?
* For RDP: What specific measures can I take to secure RDP access against brute force attacks and vulnerabilities, considering both network-level and software configurations?
