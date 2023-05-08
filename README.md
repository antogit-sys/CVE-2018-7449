<h1 align = "center"> CVE-2018-7449</h1>
<img src="img/banner.png" >



## 1. Introduction

My tool is written in Python and exploits the CVE-2018-7449 vulnerability to execute a series of commands that will crash the ftp daemon.
<pre>
	<b> *** DISCLAIMER!!! ***</b>
	Please note that the use of hacking tools without authorization is illegal and 
	could result in legal problems. Therefore, it is important to use this tool
	only for testing purposes on systems where you have permission to act.
</pre>
## 2. conditions to exploit this vulnerability

- firewall disabled or compromised

- the attacker must know the username and password of an ftp account

- ftp passwords travel unencrypted and could be sniffed
  
## 3. help use
<img src="img/screenHelper.png" >  

## 4. source from which I took inspiration:

[SEGGER embOS/IP FTP Server 3.22 - Denial of Service - Windows dos Exploit](https://www.exploit-db.com/exploits/44221)
