# **IPSA**
## ***Intranet Scanner Automated*** - is tool to automate process and gathering info a minor part of pentest, trust this is work's

### Features
```
- Auto detect subnetmask and size of it self size
- Detect macinhes alive on the intranet network
- Dectect the operation system's with some packet send to knowledg ports identifing or guessing the OS
- Multitasking methods for scanning and reduce considerable timeout of output
- Run in GPU (just little thing is what changes everything)
- Use can choose number of CUDA cores, srry AMD users I haven't AMD processor to buid for u arch
```

### How works this tool work's
```
- First run a simple TCP/IP SYN ACK connection with alive machines in network
- After user can choose a selection of ports to scan or just scan the fuck*n 65355 ports avaliable, but can use mostly commmon ports by default: **21,22,23,25,53,137,138,139,80,443,445,1050,1080,8080**
- Them just test conneciton with socket as nine percent of scanners
- So using paralelism and verifyfication TCP and UDP at same time in paralelism with CUDA cores <3 this is beatiful guys
- This tools is only for real pentester'rs don't make sh*t with that, are you resposability and I'm not your father or mother so do what want so just not an assh**le u know what I saying
```

### Installing
```bash
- <b>Linux> (Manually) </b>:
-   user@localhost~#: apt install git python3 python3-dev python3-asyncio python3-pip
- <b>Windows (Manually): </b>
-   Install python3 on <a href="www.python.org" target="_blank"><u><i>www.python.org</i></u>
-   WinKey + R type cmd and ENTER
-   C:\Users\user\anypath> python -m pip install asyncio
- #### <b>Universal installing: </b>
-   python -m pip install -r requeriments
```
