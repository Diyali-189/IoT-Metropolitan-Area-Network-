# IoT-Metropolitan-Area-Network-
MAN with a Smart Facility

PROPOSED METHODOLOGY
Metropolitan area network design includes two distinct campuses in a city, which are connected by a router over an ISP (Internet Service Provider).

First Campus Network is comprised of 3 distinct facilities and each facility has different units and requirements. All specification for the first campus is as following:

Facility 1 - 7 workstation PCs and 5 wireless users connected through WRT300N router.
Facility 2 - 11 workstation PCs and a server farm consisting of 1 database server, 2 Web servers, 1 file storage server, 1 mail server and 1 domain name server (DNS).

Second Campus includes 2 distinct facilities and each facility includes different units and requirements. All specifications for the second campus are:
Facility 1 - 8 workstation users and 3 wireless users.
Facility 2 - 8 workstation users. They use database management systems, web browsing applications and transfer files. Additionally,there are 4 IP phones using VoIP service.

At the upper level MAN has connected with two ISP routers with GBIT fibber transmission media. These routers than connects to main campus switch. Then again with GBIT cooper cable it connected to building switches.

PROTOCOLS USED
E-mail service: SMTP (Simple Mail Transfer Protocol) is used in sending and receiving e-mail.

File transfer: When it comes to sending/receiving files between workstations, FTP (File Transfer Protocol) is used. 

Web  browsing: In the both Campus, users need to browse Web. Therefore, HTTP will be used in this project. 

IP phones : In the second facility of the second campus, voice and multimedia communication have to be available. So, VoIP need to be used on that facility.
Wireless  communication: We have used WPA-PSK for wireless network.
