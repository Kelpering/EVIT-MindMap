# EVIT-MindMap

Internet Components and Common Internet Protocols

## About

This project is a basic resource page for the mind map for an EVIT classroom. Content will include both the basic ideas behind the project, as well as necessary background info for said project and associated questions.

- Examples:
  - HTTP/HTTPS is used to send and receive both html documents (webpages) and associated files.
  - IPv4/IPv6 are used to identify specific and broad devices in the global internet.

- Interactions:
  - Internet protocols are one of few concepts that are directly related to performance in applications (along with hardware and usage).
  - Internet building blocks are used in similar ways with IoT devices (for compatibility).

## Background knowledge

HTTP (HyperText Transfer Protocol): Used to request and respond to servers and computers where files
or other data is needed.

HTTPS (HTTP Secure): An additional specification of HTTP which implements SSL/TLS security.

SSH (Secure Shell): A protocol to allow shell access to a remote machine. This would imply
full access to the specified security level provided.

FTP (File Transfer Protocol): A protocol to allow file transfers and access from a remote
machine. This does not allow shell access in most/all circumstances.

SFTP (SSH FTP): An additional protocol overlay for SSH to allow file transfers.

FTPS (File Transfer Protocol Secure): An additional protocol overlay for FTP to allow secure
file transfers.

IP addresses (IPv4 Address): A four (4) octet byte string that indicates a specific computer
over a network. Can be used recursively in smaller LAN networks. (A router has an IP, but
internal computers can have their own IP addresses that might already be taken outside of the
inner network).

IPv6: Another address, exactly the same as IPv4 in most practical applications except for the
fact that it has a larger address space. This means it can uniquely identify many more computers
than IPv4.

IMAP (Internet Message Access Protocol): A protocol to allow for the retrieval of email from
a centralized server. Allows for multiple devices to receive the same mail.

Question 1:
What is the difference between HTTP and HTTPS, and why is HTTPS preferred for secure communication?

Answer:
HTTP (HyperText Transfer Protocol) is used to request and respond to servers for files or data. HTTPS (HTTP Secure) is an enhanced version of HTTP that implements SSL/TLS for encryption, ensuring secure communication by protecting data from eavesdropping and tampering.

Question 2:
How do IPv4 and IPv6 differ in addressing devices on the internet?

Answer:
IPv4 addresses are four octet byte strings used to identify devices on a network. IPv6, while functioning similarly in identifying devices, has a much larger address space, allowing for a vastly greater number of unique devices to be addressed compared to IPv4.

Question 3:
What protocol would you use to securely transfer files to a remote machine and why?

Answer:
You would use SFTP (SSH File Transfer Protocol) or FTPS (File Transfer Protocol Secure). SFTP is preferred if SSH access is available since it leverages the security of SSH. FTPS can be used when secure file transfers are required but without SSH access.
