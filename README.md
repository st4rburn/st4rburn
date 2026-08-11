<div align="center">

# Hi!

</div>

I'm a SOC analyst from Perth, Western Australia and graduate from [Edith Cowan University](https://www.ecu.edu.au/). I love cybersecurity and software development, both interests I channel for reverse engineering and exploit development. I'm a big supporter of open source software, so most of my projects outside of work are available here. I believe software and cybersecurity should be accessible to all, I enjoy the opportunity to educate and learn from others in the field and I'm always down for a CTF, so I'm an active participant in the community here in Perth. If you see me around say hi!

I also have a [blog](https://st4rburn.dev) where you can see writeups of the stuff I do.

# Projects

## PublicPasswd (CVE-2026-46333 and CVE-2026-31431)

<a href="https://github.com/st4rburn/public-passwd">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-stats-extended.vercel.app/api/pin/?username=st4rburn&repo=public-passwd&bg_color=1c1324&title_color=ffa8e4&text_color=ffe0f5&icon_color=ffa8e4&border_color=8b53a3">
  <source media="(prefers-color-scheme: light)" srcset="https://github-stats-extended.vercel.app/api/pin/?username=st4rburn&repo=public-passwd&bg_color=fffbfe&title_color=e051b5&text_color=ad769c&icon_color=e051b5&border_color=ffa8e4">
  <img alt="PublicPasswd README card" align="right">
</picture>
</a>

PublicPasswd is an exploit chain which uses CVE-2026-46333 to get a read-only file descriptor for `/etc/shadow`, and then CVE-2026-31431 (CopyFail) to write to it. The tool dumps the hashes of all users who have a password on the system, and allows changing any other user's password without authentication or elevation to root. Can be run as any user and requires no special permissions.

<br clear="right">

## RootRemover (CVE-2026-31431)

<a href="https://github.com/st4rburn/RootRemover">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-stats-extended.vercel.app/api/pin/?username=st4rburn&repo=RootRemover&bg_color=1c1324&title_color=ffa8e4&text_color=ffe0f5&icon_color=ffa8e4&border_color=8b53a3">
  <source media="(prefers-color-scheme: light)" srcset="https://github-stats-extended.vercel.app/api/pin/?username=st4rburn&repo=RootRemover&bg_color=fffbfe&title_color=e051b5&text_color=ad769c&icon_color=e051b5&border_color=ffa8e4">
  <img alt="RootRemover README card" align="right">
</picture>
</a>

RootRemover is a method of using CVE-2026-31431 (CopyFail) to temporarily remove the root password of a host, allowing for easy passwordless elevation. It's a modification of [rootsecdev's version](https://github.com/rootsecdev/cve_2026_31431) which sets your UID to 0 upon a fresh login (requiring the current user's password). Both of these differ to the original PoC in that they should work on any architecture and aren't dependent on modifying SUID binaries.

<br clear="right">

## Roku TV ECP2

<a href="https://github.com/st4rburn/ECP2">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-stats-extended.vercel.app/api/pin/?username=st4rburn&repo=ECP2&bg_color=1c1324&title_color=ffa8e4&text_color=ffe0f5&icon_color=ffa8e4&border_color=8b53a3">
  <source media="(prefers-color-scheme: light)" srcset="https://github-stats-extended.vercel.app/api/pin/?username=st4rburn&repo=ECP2&bg_color=fffbfe&title_color=e051b5&text_color=ad769c&icon_color=e051b5&border_color=ffa8e4">
  <img alt="ECP2 README card" align="right">
</picture>
</a>

A Python library to for controlling Roku TV devices on the same network as you, regardless whether the regular ECP API is enabled in settings. This was developed by reverse engineering ECP2, the protocol Roku TVs use to communicate with the mobile app and can search the network for TVs to interface with.

<br clear="right">

## Invisirun

<a href="https://github.com/st4rburn/invisirun">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-stats-extended.vercel.app/api/pin/?username=st4rburn&repo=invisirun&bg_color=1c1324&title_color=ffa8e4&text_color=ffe0f5&icon_color=ffa8e4&border_color=8b53a3">
  <source media="(prefers-color-scheme: light)" srcset="https://github-stats-extended.vercel.app/api/pin/?username=st4rburn&repo=invisirun&bg_color=fffbfe&title_color=e051b5&text_color=ad769c&icon_color=e051b5&border_color=ffa8e4">
  <img alt="Invisirun README card" align="right">
</picture>
</a>

An alternative commandline spoofing proof-of-concept. Invisirun uses NtCreateUserProcess to pad the `Commandline` property of the PEB with null characters, aiming to avoid detection by trailing spaces/other characters.

<br clear="right">

## LunaJuice

<a href="https://github.com/st4rburn/LunaJuice">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-stats-extended.vercel.app/api/pin/?username=st4rburn&repo=LunaJuice&bg_color=1c1324&title_color=ffa8e4&text_color=ffe0f5&icon_color=ffa8e4&border_color=8b53a3">
  <source media="(prefers-color-scheme: light)" srcset="https://github-stats-extended.vercel.app/api/pin/?username=st4rburn&repo=LunaJuice&bg_color=fffbfe&title_color=e051b5&text_color=ad769c&icon_color=e051b5&border_color=ffa8e4">
  <img alt="LunaJuice README card" align="right">
</picture>
</a>

LunaJuice is an experimental tool created during an internship to monitor and log the activities of suspicious Windows processes. It can be injected by normal users or administrators (to work on any non-protected process) and hosts a local RPC server to query and change configuration. Its goal is to be easily integrated into defensive workflows and be highly customisable to the user's needs.

<br clear="right">

<div align="center">
  
# GitHub Stats

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-stats-extended.vercel.app/api?username=st4rburn&bg_color=1c1324&title_color=ffa8e4&text_color=ffe0f5&icon_color=ffa8e4&border_color=8b53a3">
  <source media="(prefers-color-scheme: light)" srcset="https://github-stats-extended.vercel.app/api?username=st4rburn&bg_color=fffbfe&title_color=e051b5&text_color=ad769c&icon_color=e051b5&border_color=ffa8e4">
  <img alt="My GitHub stats" height="165">
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-stats-extended.vercel.app/api/top-langs/?username=st4rburn&layout=compact&bg_color=1c1324&title_color=ffa8e4&text_color=ffe0f5&icon_color=ffa8e4&border_color=8b53a3">
  <source media="(prefers-color-scheme: light)" srcset="https://github-stats-extended.vercel.app/api/top-langs/?username=st4rburn&layout=compact&bg_color=fffbfe&title_color=e051b5&text_color=ad769c&icon_color=e051b5&border_color=ffa8e4">
  <img alt="My top languages" height="165">
</picture>

###### [github-stats-extended](https://github.com/stats-organization/github-stats-extended) by [stats-organization](https://github.com/stats-organization), originally by [anuraghazra](https://github.com/anuraghazra).

# Contact<a name="Contact"></a>

If it's about a specific project, there's probably a place for it in the README, but otherwise you can email me at **m<span>e&#x40;mi<span>ela&period;</span>&#100;&#101;</span>&#118;** or contact me on Discord `@st4rburn.`. While you're here, you should [check out my blog!](https://st4rburn.dev)

</div>
