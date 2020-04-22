# SSCP_System
All Attacks for System (Monitor)

http://www.wildlist.org/user_reports.htm (frequently asked virus)

------------------------------------------------------------

# Digital Signature (a.k.a Code Sign)

# Sandbox

# VM

------------------------------------------------------------

# Checklist for System

1. Port

2. Libs (injection)

3. Drivers (loaded payload)

4. Key Register (Change)

5. Target Process (call API)

6. File Modify

7. Http Traffic

# Protection for System

1. Libs (injection)

2. Drivers (loaded payload)

3. Key Register (Change)

4. File Modify

5. Target Process (call API)

6. Http Traffic --- SSL & using Encrpto 加密 (Layer5)

7. Port --- SNORT/Open Port Scanner/ use nonstandard port to avoid brute-force attacks

8. virus --- Pestudio

9. running program --- Process Explorer

# Vulnerability Mgmt Process

https://community.synopsys.com/s/topic/0TO34000000LiuoGAC/codenomicon

-[x] Analysis on Attack Surface

-[x] Test (identify) the Attack Vectors

-[x] Report

-[x] Mitigate

# Attack Protection Tool

(1) Recognition/Reconnaissance (attack area and target)

(2) Incursion to Network, and place the Malware to System

(3) Discovery from Fingerprint to reveal the flaws and drawback of sys

(4) Capture Information from flaws of sys

(5) Exfiltration (send back info to Hacker)

# Suspicious Packer Detection

...

------------------------------------------------------------

# Brute-Force Attacks:

Hacker can manifest(show) config values, and make request to Server, then get response, and analysis the response 

-[x] Dictionary Attack

   to guess username & password from a dictionary file using script.

-[x] Search Attack

   to guess username & password from a set of given conditions, such as
   a given password length and a character set. (this attack will be slow due to  big possible candidates)

-[x] Rule-based Attack

   to guess username & password from a guessed space coverage, like "John the Ripper" can generate password variation from part of username or modify them thru a preconfig mask words in the input.

------------------------------------------------------------

# Attack in Sys Level:

* P2P Network

* Anonymous IP by Proxy tool, 使用代理工具製造偽造IP位址

* Rootkit, 管理員權限的攻擊

* Code Detection, 系統指紋辨識->系統漏洞

* Mobile Malcode, 手機病毒

* Deobfuscation of Srcipt, 防止腳本混淆技術

* Backdoor, 後門程式

* Log File Attack, 偷看紀錄（揭露重要訊息）

* Malicious File by DiskMount, 虛擬記憶體放置惡意文件

* Memory Dump, 記憶體溢

http://www.rekall-forensic.com (鑑識檢測工具)

* Buffer overflaw, 緩衝區溢位

* Pointer overflow, 指標溢位

* Diretory Traversal (a.k.a Filepath Traversal), 路徑跨域

* Convert Channel, 秘密通道

* Passive DNS Query by "fast flux botnets", 反向主機名稱查詢

* Reverse IP/ WHOIS by Robtex/DomainCrawler/SpamHaus/DNSstuff/DomaimTool

https://ithelp.ithome.com.tw/articles/10190057

# Attacked Apps:

* Adware

* Spyware

* Rogue

# Melicious Code, 惡意病毒：

* Logic Bomb

* Trojan

* Dropper

* Bot

* File Infector

* Macro Virus

* Boot Sector Virus

* Worm


