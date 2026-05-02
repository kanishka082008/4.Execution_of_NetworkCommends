# 4.Execution_of_NetworkCommands
## AIM :Use of Network commands in Real Time environment
## Software : Command Prompt And Network Protocol Analyzer
## Procedure: To do this EXPERIMENT- follows these steps:
<BR>
In this EXPERIMENT- students have to understand basic networking commands e.g cpdump, netstat, ifconfig, nslookup ,traceroute and also Capture ping and traceroute PDUs using a network protocol analyzer 
<BR>
All commands related to Network configuration which includes how to switch to privilege mode
<BR>
and normal mode and how to configure router interface and how to save this configuration to
<BR>
flash memory or permanent memory.
<BR>
This commands includes
<BR>
• Configuring the Router commands
<BR>
• General Commands to configure network
<BR>
• Privileged Mode commands of a router 
<BR>
• Router Processes & Statistics
<BR>
• IP Commands
<BR>
• Other IP Commands e.g. show ip route etc.
<BR>

## Output
Microsoft Windows [Version 10.0.26200.8246]
(c) Microsoft Corporation. All rights reserved.

C:\Users\Subash>ipconfig

Windows IP Configuration


Wireless LAN adapter Local Area Connection* 1:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Wireless LAN adapter Local Area Connection* 2:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Wireless LAN adapter Wi-Fi:

   Connection-specific DNS Suffix  . :
   IPv6 Address. . . . . . . . . . . : 2403:8600:c090:51:4e7e:eba4:aa23:e071
   Temporary IPv6 Address. . . . . . : 2403:8600:c090:51:d1b2:4724:1dd3:394f
   Link-local IPv6 Address . . . . . : fe80::aa2c:c60d:144a:a686%15
   Autoconfiguration IPv4 Address. . : 169.254.224.220
   Subnet Mask . . . . . . . . . . . : 255.255.0.0
   Default Gateway . . . . . . . . . : fe80::eedd:24ff:fe3d:ced5%15

Ethernet adapter Ethernet:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

C:\Users\Subash>getmac

Physical Address    Transport Name
=================== ==========================================================
74-D4-DD-CC-33-CC   Media disconnected
F8-3D-C6-6D-AF-5B   \Device\Tcpip_{DC5335DE-D9A8-414B-A96F-1A83D182FC02}

C:\Users\Subash>hostname
LAPTOP-8A9CI14S

C:\Users\Subash>ping google.com

Pinging google.com [2404:6800:4007:81b::200e] with 32 bytes of data:
Reply from 2404:6800:4007:81b::200e: time=10ms
Reply from 2404:6800:4007:81b::200e: time=8ms
Reply from 2404:6800:4007:81b::200e: time=12ms
Reply from 2404:6800:4007:81b::200e: time=10ms

Ping statistics for 2404:6800:4007:81b::200e:
    Packets: Sent = 4, Received = 4, Lost = 0 (0% loss),
Approximate round trip times in milli-seconds:
    Minimum = 8ms, Maximum = 12ms, Average = 10ms

C:\Users\Subash>tracert google.com

Tracing route to google.com [2404:6800:4007:81b::200e]
over a maximum of 30 hops:

  1     5 ms     7 ms     5 ms  2403:8600:c090:51::1
  2     *        *        *     Request timed out.
  3     *        *        *     Request timed out.
  4     *        *       73 ms  maa05s20-in-x0e.1e100.net [2404:6800:4007:81b::200e]

Trace complete.

C:\Users\Subash>dir
 Volume in drive C is Acer
 Volume Serial Number is C448-2713

 Directory of C:\Users\Subash

30-04-2026  11:03    <DIR>          .
31-07-2025  01:00    <DIR>          ..
13-12-2025  10:24    <DIR>          .arduinoIDE
05-11-2025  23:12    <DIR>          .cache
24-02-2026  11:34    <DIR>          .copilot
03-02-2026  10:36    <DIR>          .ipython
10-02-2026  10:58    <DIR>          .matplotlib
03-11-2025  10:34    <DIR>          .vscode
30-07-2025  21:08    <DIR>          Contacts
10-02-2026  10:37    <DIR>          Desktop
20-03-2026  11:09    <DIR>          Documents
02-05-2026  11:33    <DIR>          Downloads
30-07-2025  21:08    <DIR>          Favorites
30-07-2025  21:08    <DIR>          Links
30-07-2025  21:08    <DIR>          Music
25-12-2025  18:17    <DIR>          OneDrive
23-12-2025  23:47    <DIR>          Pictures
29-12-2025  10:02                 0 qms-bmh1.bmp
29-12-2025  10:02                 0 qms-bmh2.bmp
29-12-2025  10:02                 0 qms-bmh3.bmp
29-12-2025  10:03                 0 quartus2.ini
29-12-2025  10:49            30,569 quartus2.qreg
29-12-2025  10:02                 0 quartus_web_rules_file.txt
30-07-2025  21:08    <DIR>          Saved Games
31-07-2025  01:00    <DIR>          Searches
30-04-2026  10:14    <DIR>          Subash
15-11-2025  20:58    <DIR>          Videos
30-04-2026  11:07    <DIR>          web
               6 File(s)         30,569 bytes
              22 Dir(s)  242,995,826,688 bytes free

C:\Users\Subash>cd
C:\Users\Subash

C:\Users\Subash>echo hi
hi

C:\Users\Subash>ver

Microsoft Windows [Version 10.0.26200.8246]

C:\Users\Subash>time
The current time is: 11:42:34.51
Enter the new time:

C:\Users\Subash>date
The current date is: 02-05-2026
Enter the new date: (dd-mm-yy)

## Result
Thus Execution of Network commands Performed 
