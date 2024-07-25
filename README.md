# newt196-projects
SSH setup includes the following within 4 points
-Encryption in use
-SSH tarpit put on a more approchable vlan vs the actual ssh server, (need to be descriptive in this expliantaion)
-SSH log monitoring and solutions to do so
-SSH ensure downgrade exploits are not in use with the actual ssh server
-SSH real host set on a port that is not 22

https://github.com/ytisf/theZoo/tree/master

Sandbox_in_a_box (adv)
Setup a Sandbox enviroment within 2 virtual enviroments for malware analysis.
Security: Made sure that VM Escape could not occur by properly isolating as musgh as possible
-including: network isolation(confirmed the vm and the host are not talking with eachother | monitring network activity and system calls oir any other file changes| 
Some malware analysed: AsyncRAT | Dexter | Rubilyn |

Firewall implmentation through Snort
Deny all my default and whitelist what is needed, AKA SSH and Apache server for tight now
Snort logs for Linux and Windows server. 
Setup a virtual lan, verified the vlan within the manager appliance and checked the connections within wireshark and port scanning.

Wireshark
analysis of wireless packets captured on an ESP32. 
Implmented my own router and configured it to be somewhat verlnerabul to deathenti ation attacks.
Captured the M1 & M3 of a vulnerable connected device to that network.
Was able to crack the default wifi password of 7 charecters after a two days 
The dictionary included combined password from 3 of the major password lists found online. (Including my own password rules containied within python)

Familiar with capturing pcaps over a lan and wireless card.
-Familiar with how to filter packets and siff through each protocol layer.
-Familiar with capturing http and https request to better recognize web responses and call backs. 
-Exploring FTP and SSH traffic specific to server setup.

Programming
Python
Code for encrpyting my own file with assymertric cryptoogprphy. 

Secure and unsecure chat setup between two computers on my netwrok
-Authentication was based on an TCP connection
-verified in wireshark, unsecure communication could be viewed in wireshard | secure communciation was left encrpyted and encrypted with CeaserCipher(for beginners, looking to upgrade the encyption if ever where to be hosted over the internet)

Possible ARP defense and attakcs 

Man in the middle attacks where possible. 




