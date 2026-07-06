<div align="center">

# Hi!

</div>

I'm a SOC analyst at [Seamless Intelligence](https://seamlessintelligence.com.au/) in Perth, Western Australia and graduate from [Edith Cowan University](https://www.ecu.edu.au/). I have a strong interest for cybersecurity and software development, I enjoy CTFs and HackTheBox in my spare time, plus researching and experimenting with new exploits. If you have any questions or comments on what I do, feel free to [contact](#Contact) me. I also have a [blog](https://aurillium.space) where I intend to write up some of my more interesting projects.

# Projects

## PublicPasswd (CVE-2026-46333 and CVE-2026-31431)

<a href="https://github.com/st4rburn/public-passwd"><img src="https://github-stats-extended.vercel.app/api/pin/?username=st4rburn&repo=public-passwd&bg_color=1c1324&title_color=ffa8e4&text_color=ffe0f5&icon_color=ffa8e4&border_color=d980ff" alt="PublicPasswd README card" align="right"></a>

PublicPasswd is an exploit chain which uses CVE-2026-46333 to get a read-only file descriptor for `/etc/shadow`, and then CVE-2026-31431 (CopyFail) to write to it. The tool dumps the hashes of all users who have a password on the system, and allows changing any other user's password without authentication or elevation to root. Can be run as any user and requires no special permissions.

<br clear="right">

## RootRemover (CVE-2026-31431)

<a href="https://github.com/st4rburn/RootRemover"><img src="https://github-stats-extended.vercel.app/api/pin/?username=st4rburn&repo=RootRemover&bg_color=1c1324&title_color=ffa8e4&text_color=ffe0f5&icon_color=ffa8e4&border_color=d980ff" alt="RootRemover README card" align="right"></a>

RootRemover is a method of using CVE-2026-31431 (CopyFail) to temporarily remove the root password of a host, allowing for easy passwordless elevation. It's a modification of [rootsecdev's version](https://github.com/rootsecdev/cve_2026_31431) which sets your UID to 0 upon a fresh login (requiring the current user's password). Both of these differ to the original PoC in that they should work on any architecture and aren't dependent on modifying SUID binaries.

<br clear="right">

## Roku TV ECP2

<a href="https://github.com/st4rburn/ECP2"><img src="https://github-stats-extended.vercel.app/api/pin/?username=st4rburn&repo=ECP2&bg_color=1c1324&title_color=ffa8e4&text_color=ffe0f5&icon_color=ffa8e4&border_color=d980ff" alt="ECP2 README card" align="right"></a>

A Python library to for controlling Roku TV devices on the same network as you, regardless whether the regular ECP API is enabled in settings. This was developed by reverse engineering ECP2, the protocol Roku TVs use to communicate with the mobile app and can search the network for TVs to interface with.

<br clear="right">

## Invisirun

<a href="https://github.com/st4rburn/invisirun"><img src="https://github-stats-extended.vercel.app/api/pin/?username=st4rburn&repo=invisirun&bg_color=1c1324&title_color=ffa8e4&text_color=ffe0f5&icon_color=ffa8e4&border_color=d980ff" alt="Invisirun README card" align="right"></a>

An alternative commandline spoofing proof-of-concept. Invisirun uses NtCreateUserProcess to pad the `Commandline` property of the PEB with null characters, aiming to avoid detection by trailing spaces/other characters.

<br clear="right">

## LunaJuice

<a href="https://github.com/st4rburn/LunaJuice"><img src="https://github-stats-extended.vercel.app/api/pin/?username=st4rburn&repo=LunaJuice&bg_color=1c1324&title_color=ffa8e4&text_color=ffe0f5&icon_color=ffa8e4&border_color=d980ff" alt="LunaJuice README card" align="right"></a>

LunaJuice is an experimental tool created during an internship to monitor and log the activities of suspicious Windows processes. It can be injected by normal users or administrators (to work on any non-protected process) and hosts a local RPC server to query and change configuration. Its goal is to be easily integrated into defensive workflows and be highly customisable to the user's needs.

<br clear="right">

<div align="center">
  
# GitHub Stats

<img src="https://github-stats-extended.vercel.app/api?username=st4rburn&bg_color=2c1e38&title_color=ffa8e4&text_color=ffe0f5&icon_color=ffa8e4&border_color=d980ff" height="165" alt="My GitHub stats">
<img src="https://github-stats-extended.vercel.app/api/top-langs/?username=st4rburn&layout=compact&&bg_color=1c1324&title_color=ffa8e4&text_color=ffe0f5&icon_color=ffa8e4&border_color=d980ff" height="165" alt="My top languages">

###### [github-stats-extended](https://github.com/stats-organization/github-stats-extended) by [stats-organization](https://github.com/stats-organization), originally by [anuraghazra](https://github.com/anuraghazra).

# Contact<a name="Contact"></a>

If it's about a specific project, there's probably a place for it in the README, but otherwise you can [email me](mailto:memphism2003@gmail.com) or contact me on Discord **@aurillium**. While you're here, you should [check out my blog!](https://aurillium.space)

</div>
