# cve2020-0796
It's name is forecasted as SMBGHOST

Microsoft SMV3.1.1 wormable Exploit

Info and Update:-

https://twitter.com/malwrhunterteam/status/1237480108568477697

Microsoft Info:-

                  https://portal.msrc.microsoft.com/en-US/security-guidance/advisory/CVE-2020-0796

How to patch the bug:

Go and download kb4551762 from link below

 https://www.catalog.update.microsoft.com/Search.aspx?q=KB4551762


More Info:-
                https://support.microsoft.com/en-us/help/4551762/windows-10-update-kb4551762


Some of the already available Github Repositories

https://github.com/cve-2020-0796/cve-2020-0796
https://github.com/Aekras1a/CVE-2020-0796-PoC
https://github.com/ollypwn/SMBGhost
https://github.com/0xtobu/CVE-2020-0796



How to disable microsoft new smb compression functionality to prevent this wormable vulnerability in windows 10 1909 and 1903

    Set-ItemProperty -Path "HKLM:\SYSTEM\CurrentControlSet\Services\LanmanServer\Parameters" DisableCompression -Type DWORD -Value 1 -Force



   ==========*Remember It is wormable so it has the potential to travel from one node to other automatically in a network like wannacry*===

!!!!!!!!!!!*****************Waiting for the Exploit code to be released************** !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

