Andrew Brieff

1.  How many packets are there in this set?
a) 1503 packets
1. How many packets are there in this set?
    1503 packets
2. What protocol was used to transfer files from PC to server?
    FTP
3. Briefly describe why the protocol used to transfer the files is insecure?
    The server in an FTP protocol transfer can only handle usernames and passwords in plaintext, exposing them to anyone listening in on the data stream.
4. What is the secure alternative to the protocol used to transfer files?
    SFTP
5. What is the IP address of the server?
    67.23.79.113
6. What was the username and password used to access the server?
    Username: ihackpineapples
    Password: rockyou1
7. How many files were transferred from PC to server?
    4
8. What are the names of the files transferred from PC to server?
    BjN-01hCAAZbig.jpg
    BvgT9p2IQAEEoHu.jpg
    BvzjaN-IQAA3XG7.jpg
    smash.txt
9. Extract all the files that were transferred from PC to server. These files must be part of your submission!
set2.pcap

10. How many packets are there in this set?
    77882
11. How many plaintext username-password pairs are there in this packet set?
1
12. Briefly describe how you found the username-password pairs.
By using ettercap + grep/ by filtering by POP protocol in wireshark
13. For each of the plaintext username-password pair that you found, identify the protocol used, server IP, the corresponding domain name (e.g., google.com), and port number.
IMPORTANT NOTE: PLEASE DO NOT LOG ON TO THE WEBSITE OR SERVICE ASSOCIATED WITH THE USERNAME-PASSWORD THAT YOU FOUND!

chris@digitalinterlude.com Volrathw69 POP 75.126.75.131 email , digitalinterlude.com, port 110
14. Of all the plaintext username-password pairs that you found, how many of them are legitimate? That is, the username-password was valid, access successfully granted?
The username and password was legitimate
15. How did you verify the successful username-password pairs?
THe password was sent to the server and received a response  200: OK
16. What advice would you give to the owners of the username-password pairs that you found so their account information would not be revealed "in-the-clear" in the future?
Use a more secure protocol so that the username and password are not displayed in plaintext.
