<div align="center">

# Hello!

</div>

I'm Memphis Marshall, a SOC analyst at [Seamless Intelligence](https://seamlessintelligence.com.au/) in Perth, Western Australia and graduate from [Edith Cowan University](https://www.ecu.edu.au/). I have a strong interest for cybersecurity and software development, I enjoy CTFs and HackTheBox in my spare time, plus researching and experimenting with new exploits. If you have any questions or comments on what I do, feel free to [contact](#Contact) me. I also have a [blog](https://aurillium.space) where I intend to write up some of the more interesting stuff I do.

# Projects

## RootRemover (CVE-2026-31431)

<img src="https://github-stats-extended.vercel.app/api/pin/?username=aurillium&repo=RootRemover&theme=algolia" alt="RootRemover README card" align="right">

RootRemover is a method of using CVE-2026-31431 (CopyFail) to temporarily remove the root password of a host, allowing for easy passwordless elevation. It's a modification of [rootsecdev's version](https://github.com/rootsecdev/cve_2026_31431) which sets your UID to 0 upon a fresh login (requiring the current user's password). Both of these differ to the original PoC in that they should work on any architecture and aren't dependent on modifying SUID binaries.

<br clear="right">

## Roku TV ECP2

<img src="https://github-stats-extended.vercel.app/api/pin/?username=aurillium&repo=ECP2&theme=algolia" alt="ECP2 README card" align="right">

A Python library to for controlling Roku TV devices on the same network as you, regardless whether the regular ECP API is enabled in settings. This was developed by reverse engineering ECP2, the protocol Roku TVs use to communicate with the mobile app and can search the network for TVs to interface with.

<br clear="right">

## Invisirun

<img src="https://github-stats-extended.vercel.app/api/pin/?username=aurillium&repo=invisirun&theme=algolia" alt="Invisirun README card" align="right">

An alternative commandline spoofing proof-of-concept. Invisirun uses NtCreateUserProcess to pad the `Commandline` property of the PEB with null characters, aiming to avoid detection by trailing spaces/other characters.

<br clear="right">

## LunaJuice

<img src="https://github-stats-extended.vercel.app/api/pin/?username=aurillium&repo=LunaJuice&theme=algolia" alt="LunaJuice README card" align="right">

LunaJuice is an experimental tool created during an internship to monitor and log the activities of suspicious Windows processes. It can be injected by normal users or administrators (to work on any non-protected process) and hosts a local RPC server to query and change configuration. Its goal is to be easily integrated into defensive workflows and be highly customisable to the user's needs.

<br clear="right">

## MCServerGenerator

<img src="https://github-stats-extended.vercel.app/api/pin/?username=aurillium&repo=MCServerGenerator&theme=algolia" alt="MCServerGenerator README card" align="right">

A Python script to generate Minecraft servers using various server software. Very useful for testing plugins and mods on different versions; supports Paper, Spigot, Fabric, and vanilla.

<br clear="right">

<div align="center">
  
# GitHub Stats

[![My GitHub stats](https://github-stats-extended.vercel.app/api?username=aurillium&theme=algolia)](https://github.com/anuraghazra/github-readme-stats) [![My top languages](https://github-stats-extended.vercel.app/api/top-langs/?username=aurillium&theme=algolia&layout=compact)](https://github.com/anuraghazra/github-readme-stats)

###### [github-stats-extended](https://github.com/stats-organization/github-stats-extended) by [stats-organization](https://github.com/stats-organization), originally by [anuraghazra](https://github.com/anuraghazra).

# Contact<a name="Contact"></a>

If it's about a specific project, there's probably a place for it in the README, but otherwise you can [email me](mailto:memphism2003@gmail.com). While you're here, you should [check out my blog!](https://aurillium.space)

</div>
