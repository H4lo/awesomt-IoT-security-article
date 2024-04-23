- [Introduction](#introduction)
- [安全教程](#安全教程)
- [安全论坛|博客](#安全论坛博客)
- [漏洞分析](#漏洞分析)
  - [网络设备漏洞分析](#网络设备漏洞分析)
  - [摄像头漏洞分析](#摄像头漏洞分析)
  - [智能家居漏洞分析](#智能家居漏洞分析)
  - [嵌入式/物联网设备漏洞分析](#嵌入式物联网设备漏洞分析)
- [固件分析](#固件分析)
- [无线电安全](#无线电安全)
- [硬件安全](#硬件安全)
- [模糊测试](#模糊测试)
- [工具使用](#工具使用)
- [安全论文](#安全论文)
- [会议](#会议)
  - [国内会议](#国内会议)
  - [国外会议](#国外会议)
- [CTF](#ctf)
- [安全报道](#安全报道)
- [开源安全项目](#开源安全项目)
- [车联网安全](#车联网安全)
- [漏洞情报库](#漏洞情报库)
- [其他](#其他)


# Introduction

收集一些与IoT安全有关的安全文章、教程、资料等url资源，供大家一起学习!

- 旧的文章项目地址：https://github.com/H4lo/IOT_Articles_Collection

# 安全教程
[分类 Learning 下的文章 - 赤道企鹅的博客 | Eqqie's Blog](https://eqqie.cn/index.php/category/Learning)
- 摘要: 根据新的上下文，我们可以对原始摘要进行一些修改。

[Preface - heap-exploitation](https://heap-exploitation.dhavalkapil.com/)
- 摘要: 这本书的第一部分详细描述了堆内部的情况，简洁明了。第二部分涵盖了一些最著名的攻击。假设读者对这个主题不熟悉。对于有经验的读者来说，这本书可能适合快速复习。

https://mp.weixin.qq.com/s/L3bkD7nuZdDdBQ7DJ4Q-ew

https://mp.weixin.qq.com/s/jZd5BpAmwFZOZuNjc4-oqA

https://mp.weixin.qq.com/s/jZd5BpAmwFZOZuNjc4-oqA

[About the book - A Noob's Guide To ARM Exploitation](https://ad2001.gitbook.io/a-noobs-guide-to-arm-exploitation/)

[Introduction · Reverse Engineering](https://0xinfection.github.io/reversing/)

[使用Binary Ninja进行IoT设备漏洞挖掘](https://dawnslab.jd.com/binaryninja1-zh-cn/)

https://forum.defcon.org/node/241835, https://github.com/infobyte/cve-2022-27255

https://mp.weixin.qq.com/s/JT_HCfSS7bpgutk3v2ApNQ

https://mp.weixin.qq.com/s/7cdt5lCmU5ufucUasaKVZA

https://www.s3.eurecom.fr/docs/usenixsec22_arbiter.pdf

[Parsing JSON is a Minefield](https://seriot.ch/projects/parsing_json.html)

https://www.4hou.com/search-post?keywords=深入考察JSON在互操作性方面的安全漏洞，

https://github.com/KathanP19/HowToHunt

# 安全论坛|博客
[Security Research & Insights](https://binarly-io.webflow.io/articles)
- 摘要: 1、2023年3月3日，Alex Matrosov揭示了Black Lotus UEFI Bootkit的秘密。
2、探讨了检测和分析rootkits和bootkits的历史和挑战。
3、深入研究了高级威胁分析的世界。

https://blog.attify.com/
- 摘要: 摘要为空

[Shielder](https://www.shielder.com/blog/)
- 摘要: 1. 近期公开的针对Orthanc DICOM服务器的CVE-2023-33466可以被用来实现远程代码执行。
2. 由于没有可用的概念验证，我们编写了一个。
3. 这个漏洞可以利用多语言文件来攻击医疗服务器。

[Aleph Research](https://alephsecurity.com/)
- 摘要: 摘要为空

[Defense.One](https://defense.one/)
- 摘要: 请使用现代浏览器并启用JavaScript以获得最佳浏览体验。

[Research Notes](https://www.assetnote.io/resources/research)
- 摘要: 请与我们的团队通话，了解Assetnote如何改变您保护攻击面的方式。我们将为您设置一个试用实例，让您亲自体验其影响。

[Quarkslab's blog](https://blog.quarkslab.com/index.html)

[CTF导航 | 分享CTF、IOT、ICS、Car相关内容](https://www.ctfiot.com/)

https://xz.aliyun.com/

[unSafe.sh - 不安全](https://unsafe.sh/)

[talos](https://blog.talosintelligence.com/)

[ssd-disclosure](https://ssd-disclosure.com/advisories-archive/)

[nccgroup](https://research.nccgroup.com/)

[UFA-通用固件分析
[Zyxel firmware extraction and password analysis - hn security](https://security.humanativaspa.it/zyxel-firmware-extraction-and-password-analysis/)
系统](https://ufa.360.net/home)

[unblob - extract everything!](https://unblob.org/)

[2022看雪安全开发者峰会 - Hack Inn](https://www.hackinn.com/index.php/archives/808/)

[IOTsec-Zone 安全社区](https://iotsec-zone.com/article?id=314)

[CYS4 | Blog](https://blog.cys4.com/)

[Cymetrics Tech Blog](https://tech-blog.cymetrics.io/en/)

[Page non trouvÃ©e](https://www.synacktiv.com/publications%3Ffield_tags_target_id%3D3.html)

[James Kettle Research Overview](https://skeletonscribe.net/)

[Flatt Security Blog](https://blog.flatt.tech/)

[安全客 - 安全资讯平台](http://anquanke.com)

# 漏洞分析
## 网络设备漏洞分析
[Palo Alto - Putting The Protecc In GlobalProtect (CVE-2024-3400)](https://labs.watchtowr.com/palo-alto-putting-the-protecc-in-globalprotect-cve-2024-3400/)
- 摘要: 原文摘要已经非常详尽，新的上下文并未提供额外的信息，因此无需修改原有摘要。

[Uniview IPC2322LB Auth Bypass and CLI escape](https://ssd-disclosure.com/ssd-advisory-uniview-ipc2322lb-auth-bypass-and-cli-escape/)
- 摘要: 1. Uniview IPC2322LB的身份验证请求处理存在漏洞，远程攻击者可以绕过身份验证过程并获得未经授权的访问权限。
2. 如果这个漏洞与CLI逃逸结合，Uniview设备的安全性可能会被完全破坏。
3. 供应商已经发布了一个解决这个问题的建议。
4. 所有与密码更改相关的Uniview IPC2322LB的Javascript代码都可以在没有身份验证的情况下访问，因此可以绕过身份验证要求并更改密码。
5. 通过绕过身份验证和uvsh（受限制的shell）获取root权限，可以启用telnet。

[Hunting for <del>Un</del>authenticated n-days in Asus Routers](https://www.shielder.com/blog/2024/01/hunting-for-~~un~~authenticated-n-days-in-asus-routers/)
- 摘要: 原始摘要的细化版：1. 在阅读了一些关于影响ASUS路由器的关键CVE的在线详细信息后，我们决定分析易受攻击的固件并可能编写一个n-day漏洞利用程序。
2. 我们发现了易受攻击的代码片段，并成功编写了一个漏洞利用程序以获得RCE，但我们也发现，在现实世界的设备中，报告的漏洞的“未经认证的远程”属性并不总是成立，这取决于设备的当前配置。
3. 我们选择了影响各种Asus SOHO路由器的以下CVE进行研究，并从CVE的详细信息中推断出一些有趣的信息，例如受影响的设备和版本。
4. 我们下载了易受攻击和修复的固件版本，并使用BinDiff进行补丁差异分析，发现了一些变化，但没有一个对我们的目的有趣。
5. 我们使用Qiling模拟固件并在其中复现漏洞，然后购买了目标设备（Asus RT-AX55），并开始分析漏洞以理解其根本原因和如何控制它。
6. 我们发现了一种利用格式字符串漏洞来覆盖SystemCmd内容并触发sys_script("syscmd.sh")函数的方法，但在没有任何cookie的情况下发送我们的有效载荷会导致重定向到登录页面。
7. 我们发现，路由器的配置状态（由NVRAM中的x_Setting键决定）会影响到大部分CGI端点的访问权限。在我们的实际设备中，x_Setting被设置为1，而在我们用Qiling模拟的设备中，x_Setting被设置为0。
8. 我们尝试了其他人报告的影响其他端点的格式字符串CVE，但在NVRAM中x_Setting=1的环境下，它们都无法工作。
9. 我们的研究结果表明，可能存在额外的身份验证绕过漏洞，或者CVE中提到的“未经认证的远程攻击者”是指CSRF类似的场景，或者是前面的研究者在模拟固件时没有考虑到NVRAM的内容。

[Palo Alto CVE-2024-3400 漏洞分析](https://mp.weixin.qq.com/s/D17gGbLJFvWxSO0buyjAxg)
- 摘要: 全球知名防火墙公司Palo Alto Networks近日公布了一个存在于部分PAN-OS系统的GlobalProtect功能中的漏洞CVE-2024-3400。该漏洞允许攻击者在某些配置打开的情况下，对运行该系统的设备进行未授权的远程代码执行，并获取系统的root权限。漏洞利用分析显示，攻击者可以在系统任何目录创建一个文件名可控的文件，然后通过命令注入进行攻击。目前，官方已经发布了更新版本以修复这个漏洞。

[MicroSocks: Convenient access through a compromised SonicWall SMA | dfir.ch](https://dfir.ch/posts/microsocks_sonicwall/)
- 摘要: 最近的调查发现，导致Abyss勒索软件部署的初始入口是一个受损的SonicWall Secure Mobile Access (SonicWall SMA)设备。攻击者利用CVE-2021-20039漏洞获取了访问权限。进一步分析发现，攻击者在设备上放置了两个文件，其中一个是名为wafxSummary的Web Shell。此外，还发现了一个名为wafySummary的文件，它是一个代理服务器。攻击者利用这些漏洞和代理服务器成功地渗透了网络，并在接近11个月的时间内进行了勒索软件分发。这个案例再次强调了及时打补丁、主动扫描漏洞和监控设备的重要性。

[Draytek Vigor 3910 | CataLpa's Site](https://wzt.ac.cn/2024/02/19/vigor_3910/)
- 摘要: 这段代码是一个用于解密和解压缩固件文件的程序。它使用ChaCha20加密算法对文件进行解密，并使用lz4算法对解密后的数据进行解压缩。程序接受一个固件文件作为输入，并将解压缩后的文件保存在rootfs.cpio中。

https://mp.weixin.qq.com/s/FFjIMzbLBxwO7hHZJF6Zuw
- 摘要: 摘要为空

[High Signal Detection and Exploitation of Ivanti's Pulse Connect Secure Auth Bypass & RCE](https://www.assetnote.io/resources/research/high-signal-detection-and-exploitation-of-ivantis-pulse-connect-secure-auth-bypass-rce)
- 摘要: 根据提供的新背景信息，我们可以对原始摘要进行完善。

Ivanti Pulse Connect Secure披露了两个关键漏洞 - CVE-2023-46805（身份验证绕过）和CVE-2024-21887（远程命令执行）。现有的身份验证绕过的利用载荷在旧版本的软件上无法使用。已经发现了一种新的载荷，用于滥用旧版本的身份验证绕过。这些漏洞正在被积极利用，安全研究团队正在努力通知受影响的客户。博客文章记录了逆向工程过程，并确定了检测机制和利用载荷中的潜在漏洞。这些漏洞影响了各个版本的Ivanti Pulse Connect Secure，并且团队已经测试了多个版本以确保准确检测。博客文章还讨论了软件中的文件系统访问和LUKS卷的加密。研究团队在软件的REST API中发现了一系列API端点，并发现了两个无需身份验证即可访问的端点。他们还在API中发现了一个命令注入漏洞。博客文章提供了使用"os.system"和"Popen"调用的"restservice/api"目录中的易受攻击的代码片段的详细信息。这些漏洞允许执行任意命令。博客文章建议采取临时缓解措施和设备完整性检查，因为尚未发布完整的补丁。

[Ivanti's Pulse Connect Secure Auth Bypass Round Two](https://www.assetnote.io/resources/research/ivantis-pulse-connect-secure-auth-bypass-round-two)
- 摘要: Ivanti发布了一份公告，描述了Ivanti Connect Secure中的两个新漏洞：CVE-2024-21888（特权提升）和CVE-2024-21893（身份验证绕过）。安全研究团队在尝试配置其ICS虚拟机以使用SAML身份验证时，发现了SAML组件中的服务器端请求伪造（SSRF）漏洞。他们还发现了一个错误消息，表明可能存在SSRF漏洞。团队进一步调查了SSRF漏洞，并发现DSAuth perl模块是C和C++库的包装器。他们发现了一个名为libxmltooling.so.3的开源软件包中的漏洞，该漏洞允许进行SSRF攻击。通过利用这个漏洞，他们能够通过修改SAML负载并直接调用Web代理后面的Python服务器来实现远程代码执行（RCE）。研究人员还发现了一个更可靠的攻击目标，适用于那些似乎没有配置SAML身份验证的目标。Ivanti已发布了修补程序来解决这些漏洞，并建议用户对其设备进行恢复出厂设置并应用修补程序。

https://ssd-disclosure.com/ssd-advisory-zyxel-vpn-series-pre-auth-remote-command-execution/
- 摘要: 鉴于新的背景信息，我们可以对原始摘要进行完善。

新的摘要：Zyxel VPN防火墙存在三个漏洞链，使得未经身份验证的攻击者可以以root权限执行任意命令。受影响的型号包括VPN50、VPN100、VPN300、VPN500和VPN1000，固件版本为5.21至5.36。这些漏洞允许攻击者覆盖产品配置并触发进程间通信中的注入点，从而实现远程代码执行。sdwan_interface进程以root权限运行，无需额外的特权升级漏洞。这些漏洞还允许攻击者绕过长度限制，在文件中编写任意命令，使其能够执行超出长度限制的命令。通过将这些漏洞链接在一起，攻击者可以实现root预认证远程代码执行。

[Remote Code Execution on Cisco Access Point WAP371 firmware â¤ 1.3.0.7](https://www.synacktiv.com/advisories/remote-code-execution-on-cisco-access-point-wap371-firmware-1307)
- 摘要: 管理员成功登录后，可以在管理部分找到数据包捕获功能。捕获成功后，管理员可以选择直接下载pcap文件，或者通过指定IPv4地址将其发送到远程服务器。然而，服务器上的一个漏洞允许攻击者注入额外的命令，从而创建一个恶意进程。

[CVE-2023-46805 | AttackerKB](https://attackerkb.com/topics/AdUh6by52K/cve-2023-46805/rapid7-analysis)
- 摘要: 多个方面披露了影响Ivanti Connect Secure和Ivanti Policy Secure网关的零日漏洞链。该漏洞链包括绕过身份验证的漏洞和命令注入漏洞，允许远程攻击者以root权限执行任意操作系统命令。这些漏洞影响产品的所有支持版本。调查还发现，包括"/api/v1/totp/user-backup-code"在内的某些终端不需要身份验证。这使得攻击者可以访问内部的Python REST服务，并有可能利用命令注入漏洞。在文件restservice\api\resources\awsazuretestconnection.py中还发现了第二个经过身份验证的命令注入漏洞。供应商已提供了漏洞的缓解措施，并已验证可以阻止利用漏洞。供应商已披露这些漏洞，并计划于2024年1月22日发布官方补丁。与此同时，可以使用临时的XML缓解文件阻止对某些URL的访问，以防止漏洞链的利用。强烈建议立即应用这个临时解决方案。

https://github.com/ea/lytro_unlock
- 摘要: 根据新的背景信息，我们可以对原始摘要进行完善。

这个项目涉及到对Lytro光场相机进行逆向工程，并创建一个Python库，以解锁官方软件中不可用的额外功能。这些功能包括远程相机控制、实时视图流传输、调试控制台和自定义代码执行。Lytro相机虽然作为商业产品不成功，但其具有高倍数光学变焦等有趣的技术。目标是为潜在的创新用途提供对相机的完全软件控制。相机可以在eBay上以折扣价购买，并且使用该库不需要进行任何物理修改。然而，这样做有砖机和失去保修的风险。该项目受到了一个关于技术项目缺陷和失败的Twitter讨论串的启发。作者的目标是为Lytro相机实现类似网络摄像头的功能，如软件控制的变焦和对焦、按需拍照，以及可能的固件修改和实时视图/视频流传输。摘要还提供了相机硬件和固件分析的概述，包括发现了一个命令解释器代码，通过USB或WiFi可以访问广泛的命令和功能。此外，作者成功解锁了被锁定的串行控制台，通过计算并发送基于相机序列号的预期哈希值。作者进一步探索了相机的功能，包括WiFi设置、实时视图参数、手动控制和通过固件的命令shell执行命令。该项目提供了一个全面的命令列表及其描述，其中一些命令尚未完全实现。通过WiFi解锁相机的能力消除了对物理修改的需求，并允许探索内置shell。新的背景提供了一个可以通过Python库访问的其他命令和功能的列表，例如涂抹控制、减少暗斑点、ANR配置、播放命令以及不同相机功能的各种测试和配置。该项目还包括一个连接到相机的WiFi的shell脚本，解锁相机，并允许发送命令和接收输出。该项目展示了不同的功能，如镜头控制、变焦控制和拍照。它还提供了启用实时视图流传输的示例。相机的固件似乎支持Lua脚本，这是该项目的未来目标。总的来说，这个项目提供了一种经济实惠的方式来尝试光场相机，并欢迎他人的贡献和想法。


[Cisco IOS XE CVE-2023-20198: Deep Dive and POC – Horizon3.ai](https://www.horizon3.ai/cisco-ios-xe-cve-2023-20198-deep-dive-and-poc/)
- 摘要: 这篇文章是对之前一篇文章的跟进，探讨了影响思科IOS XE的CVE-2023-20273和CVE-2023-20198的补丁，并确定了攻击者可能利用这些漏洞的一些途径。通过SECUINFRA FALCON TEAM的蜜罐，我们对这些漏洞有了更深入的了解。文章介绍了一个绕过认证的示例请求，以及如何利用该漏洞创建一个具有最高权限的用户。文章指出思科修复这个漏洞的方法有些不寻常，他们本应该修复路径解析漏洞，而不是添加一个新的头部。这让我们怀疑是否还有其他可以通过这种方法访问的隐藏端点。

https://mp.weixin.qq.com/s/zJJHFjmLqCtcbahJYfoyaw

[Rooting Xiaomi WiFi Routers](https://blog.thalium.re/posts/rooting-xiaomi-wifi-routers/)

[Yet More Unauth Remote Command Execution Vulns in Firewalls - Sangfor Edition](https://labs.watchtowr.com/yet-more-unauth-remote-command-execution-vulns-in-firewalls-sangfor-edition/)

[记一次全设备通杀未授权 RCE 的挖掘经历](https://paper.seebug.org/2071/#poc)

[NETGEAR Routers: A Playground for Hackers? | NCC Group Research Blog | Making the world safer and more secure](https://research.nccgroup.com/2023/05/15/netgear-routers-a-playground-for-hackers/)

[Analysis of Pre-Auth RCE in Sophos Web Appliance (CVE-2023-1671) - Blog - VulnCheck](https://vulncheck.com/blog/cve-2023-1671-analysis)

[Zero Day Initiative — CVE-2022-29844: A Classic Buffer Overflow on the Western Digital My Cloud Pro Series PR4100](https://www.zerodayinitiative.com/blog/2023/4/19/cve-2022-29844-a-classic-buffer-overflow-on-the-western-digital-my-cloud-pro-series-pr4100)

[奇安信攻防社区-CVE-2023-25690 Apache HTTP Server 请求走私漏洞 分析与利用](https://forum.butian.net/share/2180)

[奇安信攻防社区-CVE-2023-25690 Apache HTTP Server 请求走私漏洞 分析与利用](https://forum.butian.net/share/2180)

[Vulnerability Spotlight: Netgear Orbi router vulnerable to arbitrary command execution](https://blog.talosintelligence.com/vulnerability-spotlight-netgear-orbi-router-vulnerable-to-arbitrary-command-execution/)

[Debugging D-Link: Emulating firmware and hacking hardware](https://www.greynoise.io/blog/debugging-d-link-emulating-firmware-and-hacking-hardware)

https://mp.weixin.qq.com/s/Hayfe1gxRl_Clk7L8DIEZg

https://mp.weixin.qq.com/s/2joZwexIdVdgc5NL8W3J-A

[Puckungfu: A NETGEAR WAN Command Injection – NCC Group Research](https://research.nccgroup.com/2022/12/22/puckungfu-a-netgear-wan-command-injection/)

https://mp.weixin.qq.com/s/_CQ9jp6-a7wAcImjg8SouQ

https://mp.weixin.qq.com/s/_CQ9jp6-a7wAcImjg8SouQ

[Citrix CVE-2022-27518 漏洞分析](https://paper.seebug.org/2049/)

[Analyzing an Old Netatalk dsi_writeinit Buffer Overflow Vulnerability in NETGEAR Router | cq674350529's blog](https://cq674350529.github.io/2023/02/10/Analyzing-an-Old-Netatalk-dsi-writeinit-Buffer-Overflow-Vulnerability-in-NETGEAR-Router/)

[Patch diff an old vulnerability in Synology NAS | cq674350529's blog](https://cq674350529.github.io/2023/01/06/Patch-diff-an-old-vulnerability-in-Synology-NAS)

[Patch diff an old vulnerability in Synology NAS | cq674350529's blog](https://cq674350529.github.io/2023/01/06/Patch-diff-an-old-vulnerability-in-Synology-NAS)

[Analyzing an Old Netatalk dsi_writeinit Buffer Overflow Vulnerability in NETGEAR Router | cq674350529's blog](https://cq674350529.github.io/2023/02/10/Analyzing-an-Old-Netatalk-dsi-writeinit-Buffer-Overflow-Vulnerability-in-NETGEAR-Router/)

[Analyzing an Old Netatalk dsi_writeinit Buffer Overflow Vulnerability in NETGEAR Router | cq674350529's blog](https://cq674350529.github.io/2023/02/10/Analyzing-an-Old-Netatalk-dsi-writeinit-Buffer-Overflow-Vulnerability-in-NETGEAR-Router/)

[Netgear Nighthawk r7000p upnpd Buffer Overflow Remote Code Execution Vulnerability](https://hdwsec.fr/blog/20230201-netgear/)

[RCE in Avaya Aura Device Services – Assetnote](https://blog.assetnote.io/2023/02/01/rce-in-avaya-aura/)

[CVE-2023-22374: F5 BIG-IP Format String Vulnerability | Rapid7 Blog](https://www.rapid7.com/blog/post/2023/02/01/cve-2023-22374-f5-big-ip-format-string-vulnerability/)

https://mp.weixin.qq.com/s/ie6ydNvxkFjJxmrpOTkcUA

[CVE-2023-0669 | AttackerKB](https://attackerkb.com/topics/mg883Nbeva/cve-2023-0669)

[Vulnerability Spotlight: Asus router access, information disclosure, denial of service vulnerabilities discovered](https://blog.talosintelligence.com/vulnerability-spotlight-asus-router-access-information-disclosure-denial-of-service-vulnerabilities-discovered)

https://mp.weixin.qq.com/s/js8Pg9xmkqRm0A0TF7pVXQ

https://github.com/scarvell/advisories/blob/main/2022_netcomm_nf20mesh_unauth_rce.md

https://github.com/scarvell/advisories/blob/main/2022_netcomm_nf20mesh_unauth_rce.md

[directory-ttraversal-vulnerability-in-huawei-hg255s-products](https://infosecwriteups.com/directory-ttraversal-vulnerability-in-huawei-hg255s-products-dce941a1d015)

[CVE-2022-45313: Mikrotik RouterOs flaw can lead to execute arbitrary code](https://securityonline.info/cve-2022-45313-mikrotik-routeros-flaw-can-lead-to-execute-arbitrary-code/)

[Cool vulns don't live long - Netgear and Pwn2Own](https://www.synacktiv.com/publications/cool-vulns-dont-live-long-netgear-and-pwn2own.html)

[The Last Breath of Our Netgear RAX30 Bugs - A Tragic Tale before Pwn2Own Toronto 2022 | STAR Labs](https://starlabs.sg/blog/2022/12-the-last-breath-of-our-netgear-rax30-bugs-a-tragic-tale-before-pwn2own-toronto-2022/)

[Horde Webmail - Remote Code Execution via Email](https://blog.sonarsource.com/horde-webmail-rce-via-email/)

[Unauthenticated Remote Code Execution in a Wide Range of DrayTek Vigor Routers](https://www.trellix.com/en-us/about/newsroom/stories/threat-labs/rce-in-dratyek-routers.html)

https://mp.weixin.qq.com/s/p5JH8elwd0ze4f8h8xTgiA

[Blind exploits to rule WatchGuard firewalls](https://www.ambionics.io/blog/hacking-watchguard-firewalls)

[pfBlockerNG Unauth RCE Vulnerability - IHTeam Security Blog](https://www.ihteam.net/advisory/pfblockerng-unauth-rce-vulnerability/)

https://infosecwriteups.com/complete-take-over-of-cisco-unified-communications-manager-due-consecutively-misconfigurations-2a1b5ce8bd9a

https://mp.weixin.qq.com/s/efrcXS_uiXp0LzUaaEJ-MA

[Netgear Nighthawk r7000p aws_json Unauthenticated Double Stack Overflow Vulnerability](https://hdwsec.fr/blog/20221109-netgear/)

[Relyze Software Limited - Advanced Software Analysis: CVE-2022-27643 - NETGEAR R6700v3 upnpd Buffer Overflow Remote Code Execution Vulnerability](https://blog.relyze.com/2022/03/cve-2022-27643-netgear-r6700v3-upnpd.html)

[From Patch To Exploit: CVE-2021-35029](https://blog.cys4.com/exploit/reverse-engineering/2022/04/18/From-Patch-To-Exploit_CVE-2021-35029.html)


[SSD Advisory – NETGEAR DGND3700v2 PreAuth Root Access - SSD Secure Disclosure](https://ssd-disclosure.com/ssd-advisory-netgear-dgnd3700v2-preauth-root-access/)

[Reverse Engineering a Netgear Nday | StarkeBlog](https://nstarke.github.io/netgear/nday/2022/03/13/reverse-engineering-a-netgear-nday.html)

https://mp.weixin.qq.com/s/tUikU0U-FCo33kWsmHTCIQ

## 摄像头漏洞分析
[Exploiting: Buffer overflow in Xiongmai DVRs | ret2.me](https://blog.ret2.me/post/2022-01-26-exploiting-xiongmai-dvrs/)

https://mp.weixin.qq.com/s/K-Zu1M5JVhzT_xb7rb1l0Q

[A journey into IoT - Unknown Chinese alarm - Part 1 - Discover components and ports - hn security](https://security.humanativaspa.it/a-journey-into-iot-unknown-chinese-alarm-part-1-discover-components-and-ports/)

## 智能家居漏洞分析
[Say Friend and Enter: Digitally lockpicking an advanced smart lock (Part 2: discovered vulnerabilities)](https://alephsecurity.com/2024/03/07/kontrol-lux-lock-2/)
- 摘要: 如果上下文没有用处，返回原始摘要。

[Say Friend and Enter: Digitally lockpicking an advanced smart lock (Part 1: functional analysis)](https://alephsecurity.com/2024/02/20/kontrol-lux-lock-1/)
- 摘要: 这篇博文分析了Sciener开发并由Kontrol在以色列市场推广的先进智能锁Kontrol Lux Lock。研究的重点是控制该锁的TTLock应用程序中存在的漏洞。分析揭示了锁的通信协议结构和使用的加密方法。博文讨论了使用ESP32 MCU模拟锁的过程以及使用Ghidra分析锁的固件。还分析了固件中使用的加密机制，包括与TTLock应用程序、网关和无线键盘通信的密钥。博文探讨了蓝牙低功耗（BLE）功能和处理传入BLE消息的处理程序，以及无线键盘功能和网关固件分析。此外，博文还提到了使用Telink的调试设备和专用软件套件BDT来调试锁和网关设备。博文还提到了使用socat记录网关与TTLock服务器之间实际流量以进行进一步分析。对网关协议进行了分析，并使用Python实现了网关和TTLock服务器的代码仿真，用于测试和攻击目的。在新的上下文中，还讨论了模拟重置并与新用户配对的网关，包括登录序列、密钥生成、报告附近的锁以及响应服务器命令的过程。

[Rooting Xiaomi WiFi Routers](https://blog.thalium.re/posts/rooting-xiaomi-wifi-routers/)
- 摘要: 研究人员在MI AIoT Router AC2350中发现了多个漏洞，允许攻击者获得root访问权限。这些漏洞在最新的固件更新中没有修复，并且之前在其他小米路由器中也被发现过。局域网漏洞包括命令注入漏洞（CVE-2020-14100）和重复命令注入漏洞（CVE-2023-26319），允许任意命令执行。广域网漏洞包括smartcontroller二进制文件中的堆栈缓冲区溢出漏洞（CVE-2023-26318），允许远程代码执行，以及messagingagent二进制文件中的命令注入漏洞（CVE-2023-26317），允许远程命令执行。此外，messagingagent二进制文件中还发现了堆栈缓冲区溢出漏洞（CVE-2023-26320），导致拒绝服务。这些漏洞对MI AIoT Router AC2350的用户构成重大安全风险。研究人员还发现了messagingagent二进制文件中的堆栈缓冲区溢出漏洞，通过崩溃/usr/bin/messagingagent引起拒绝服务。崩溃会影响路由器的功能，需要重新启动才能恢复正常操作。这些漏洞在其他小米固件中得到了验证，并且研究人员已经确定了四个新的CVE。尽管研究人员希望他们的发现能够加强小米产品的安全性，但他们认为可能还有更多的漏洞有待发现。

[Pulling MikroTik into the Limelight — Margin Research](https://margin.re/2022/06/pulling-mikrotik-into-the-limelight/)
- 摘要: 这篇博客提供了关于逆向工程MikroTik路由器的概述，并介绍了研究过程中创建的工具。它涵盖了RouterOS操作系统、绕过签名验证、MikroTik的专有消息协议和认证过程等主题。该文章旨在更新关于MikroTik的公开可用知识，并提供有关其内部工作原理的速成课程，包括消息路由和多播和广播功能的使用。文章还讨论了使用工具跟踪内部RouterOS消息并可视化它们的方法。此外，文章还深入探讨了MikroTik路由器的认证方案，探索了椭圆曲线Diffie-Hellman（ECDH）和椭圆曲线安全远程协议（EC-SRP）等加密协议。分析了MikroTik对EC-SRP的IEEE提交草案的实现的差异，突出了MikroTik所做的修改。文章最后提到了实现Winbox和MAC Telnet协议的工具的可用性，并提供了有关EC-SRP协议和MikroTik的投影空间计算的进一步细节。文章还讨论了使用精心制作的消息和ROP链在RouterOS v6设备上实现权限提升到超级管理员和远程代码执行（RCE）的过程。文章最后强调了记录和分享关于MikroTik和RouterOS的知识的重要性，以鼓励进一步的研究和探索。

https://downrightnifty.me/blog/2022/12/26/hacking-google-home.html

https://mp.weixin.qq.com/s/WkXbI5lHM2LYnSCMuQAdbA

https://mp.weixin.qq.com/s/4fdD3eEg7aql6_cY81hHOA

[nday exploit: netgear orbi unauthenticated command injection (CVE-2020-27861) | hyprblog](https://blog.coffinsec.com//research/2022/07/02/orbi-nday-exploit-cve-2020-27861.html)

## 嵌入式/物联网设备漏洞分析
[Intel BMC firmware lighttpd vulnerability](https://binarly-io.webflow.io/advisories/brly-2024-002)
- 摘要: 原文摘要已经非常详细和准确，新的上下文并未提供额外的信息，因此无需修改原文摘要。以下是原文摘要：

1. Binarly REsearch团队发现了Intel BMC固件的web服务器组件中存在堆越界读取漏洞，可能使攻击者从Lighttpd进程内存中窃取敏感信息。
2. 该漏洞影响了Intel固件，Binarly团队已确认其影响。
3. 攻击者可以利用这个漏洞读取Lighttpd Web服务器进程的内存，可能导致敏感数据泄露，如内存地址，这可以用来绕过如ASLR等安全机制。
4. Lighttpd 1.4.45在HTTP请求解析逻辑中存在缺陷，如果收到的请求包含多个If-Modified-Since头，web服务器会比较它们的值是否相等，响应状态码取决于此检查的结果。
5. 攻击者可以通过发送大量请求来利用这个漏洞，如果返回的响应状态码不等于400，就意味着从Lighttpd进程内存中窃取了值0x00216a38。
6. 这个漏洞在Lighttpd 1.4.51中已经修复，建议使用最新的稳定版本。

[Your printer is not your printer ! - Hacking Printers at Pwn2Own Part II | DEVCORE](https://devco.re/blog/2023/11/06/your-printer-is-not-your-printer-hacking-printers-pwn2own-part2-en/)
- 摘要: 根据提供的新背景信息，我们可以对原始摘要进行完善。

研究人员在Pwn2Own Toronto 2022比赛中发现了佳能打印机的Pre-auth RCE漏洞，并与另一个团队发生了关于惠普漏洞的冲突。佳能漏洞涉及mDNS协议中的堆栈溢出，而惠普漏洞则是NetBIOS中的堆溢出。研究人员成功利用这些漏洞运行了shellcode，并控制了打印机。在佳能打印机漏洞中，研究人员发现佳能实现的NetBIOS守护程序在解析NetBIOS数据包时存在堆溢出，使他们能够覆盖nb_info结构并控制打印机。此外，研究人员还发现了惠普Color LaserJet Pro M479fdw打印机的slangapp组件中的堆栈溢出漏洞。通过利用这个漏洞，他们能够覆盖函数指针并执行任意代码，最终控制了打印机。佳能打印机的漏洞是通过解析未检查长度的pathinfo触发的，导致堆栈溢出。研究人员通过构造一个请求到/Scan/Jobs/并覆盖返回地址来利用这个漏洞。然而，这个漏洞与另一个团队的发现发生了冲突。打印机安全问题仍然容易被忽视，正如在Pwn2Own比赛中能够入侵打印机的团队数量不断增加所证明的那样。建议物联网设备的用户禁用不必要的服务，正确设置防火墙，并实施适当的访问控制以减轻攻击风险。

[Your printer is not your printer ! - Hacking Printers at Pwn2Own Part I | DEVCORE 戴夫寇爾](https://devco.re/blog/2023/10/05/your-printer-is-not-your-printer-hacking-printers-pwn2own-part1/)

[chonked pt.1: MiniDLNA 1.3.2 HTTP Chunk Parsing Heap Overflow (CVE-2023-33476) Root Cause Analysis | hyprblog](https://blog.coffinsec.com/0day/2023/05/31/minidlna-heap-overflow-rca.html)

[chonked pt.1: MiniDLNA 1.3.2 HTTP Chunk Parsing Heap Overflow (CVE-2023-33476) Root Cause Analysis | hyprblog](https://blog.coffinsec.com/0day/2023/05/31/minidlna-heap-overflow-rca.html)

[chonked pt.1: MiniDLNA 1.3.2 HTTP Chunk Parsing Heap Overflow (CVE-2023-33476) Root Cause Analysis | hyprblog](https://blog.coffinsec.com/0day/2023/05/31/minidlna-heap-overflow-rca.html)

[The printer goes brrrrr, again!](https://www.synacktiv.com/publications/the-printer-goes-brrrrr-again)

https://mp.weixin.qq.com/s/UwsQH9nr1D4FzK2lhy_W2A

https://mp.weixin.qq.com/s/W2yAcmXh4vrE9pOh02H9Gg

[IOTsec-Zoneç©èç½å®å¨ç¤¾åº](https://iotsec-zone.com/article?id=362)

[CVE-2022-24942 Heap-based buffer overflow in Silicon Labs Gecko SDK](https://bugprove.com/knowledge-hub/cve-2022-24942-heap-based-buffer-overflow-in-silicon-labs-gecko-sdk/)

[Researcher drops Lexmark RCE zero-day rather than sell vuln ‘for peanuts’ | The Daily Swig](https://portswigger.net/daily-swig/researcher-drops-lexmark-rce-zero-day-rather-than-sell-vuln-for-peanuts)

[考勤机安全分析报告 - FreeBuf网络安全行业门户](https://www.freebuf.com/articles/paper/354674.html)

https://github.com/blasty/lexmark

https://mp.weixin.qq.com/s/emvk8liLb4MmWpE9L_MkZA

[KUKA KR C4 | CISA](https://www.cisa.gov/uscert/ics/advisories/icsa-21-208-01)

[Technical Advisory – Multiple Vulnerabilities in U-Boot (CVE-2022-30790, CVE-2022-30552) – NCC Group Research](https://research.nccgroup.com/2022/06/03/technical-advisory-multiple-vulnerabilities-in-u-boot-cve-2022-30790-cve-2022-30552/)

https://mp.weixin.qq.com/s/n_HBOWlHtS9sE7shGpDwxw

[Zero Day Initiative — Announcing Pwn2Own Toronto 2022 and Introducing the SOHO Smashup!](https://www.zerodayinitiative.com/blog/2022/8/29/announcing-pwn2own-toronto-2022-and-introducing-the-soho-smashup)

https://mp.weixin.qq.com/s/xVU8o5NcbFYmy0yPJfiwVQ


# 固件分析
[搭建 FortiGate 调试环境 (二)](https://wzt.ac.cn/2024/04/02/fortigate_debug_env2/)
- 摘要: 这段文字是一段关于处理许可证的编程代码。主要步骤包括：1. 初始化许可证结构；2. 检查许可证数据是否存在；3. 在存在的情况下，找到许可证的开始和结束部分；4. 对许可证主体进行处理，包括解码和检查；5. 对解码后的许可证进行进一步处理，包括公钥解密和许可证结构的填充；6. 最后，根据处理结果返回相应的值。

[某路由器串口破解新思路](https://mp.weixin.qq.com/s/EPcqFkzmZs8-Sk5iHFHHPA)
- 摘要: 1. CTF组正在招募re、crypto、pwn、misc、合约方向的专家，同时也在长期招募IOT+Car+工控+样本分析等多个组的人员，有意向的可以通过邮箱admin@chamd5.org联系。
2. 文章介绍了一种新的获取路由器权限的方式，即通过串口获取敏感数据。
3. 通过实验发现，当串口的TX线连接到主控芯片的BOOT相关引脚时，会导致主控芯片无法启动。因此，需要先让设备启动，然后再连接串口。
4. 文章还发现，串口的RX引脚旁边有一个下拉电阻，会屏蔽所有从外部输入的数据，导致无法打断uboot，也无法在系统启动完成后输入用户和密码。
5. 文章最后指出，这个路由器在硬件层面对串口做了两层防护，但在系统层面的鉴权却是空白的，这验证了信息安全的木桶理论，即一个产品的信息安全水平取决于最短的那块木板。

[原创 Paper | 从 0 开始学习 VxWorks](https://mp.weixin.qq.com/s/GC2zwT9SNs2PGLBvQhiN8w)
- 摘要: 本文由wh0am1i@知道创宇404实验室的作者在2024年2月1日撰写，主要介绍了实时操作系统和分时操作系统的定义和区别，以及嵌入式实时操作系统VxWorks的应用领域和特点。文章还详细介绍了如何搭建VxWorks环境，编译VxWorks，启动VxWorks，创建VxWorks应用，并复现VxWorks漏洞。作者表示，虽然VxWorks环境搭建过程较为曲折，但作为业界领先的实时操作系统，VxWorks仍有很多内容值得深入研究。


https://paper.seebug.org/3129/
- 摘要: 摘要为空

[Arlo: I'm watching you](https://www.synacktiv.com/publications/arlo-im-watching-you)
- 摘要：在多伦多举行的Pwn2Own竞赛中，新增了一个“监控系统”类别，本篇博客文章重点关注Arlo摄像头的漏洞研究。对摄像头固件的分析揭示了更新文件是从特定URL下载并遵循特定格式。固件包括不同的操作模式和用于简化模式切换的shell。发现了与版本1的固件格式相关联的RSA私钥，可以解密各种Arlo摄像头型号的固件更新。然而，由于密钥和格式的差异，某些更新无法解密。研究期间开发的工具可在GitHub上获取，以供进一步研究使用。需要注意的是，不应公开发布RSA私钥，并且必须执行中间人攻击来利用较小的攻击面进行TLS连接。

请注意，如果新的背景信息对原始摘要没有帮助，则返回原始摘要。

https://mp.weixin.qq.com/s/jw_APyy6SKo9nMcjqOW1EA
- 摘要: 这篇文章是关于华硕路由器堆溢出漏洞的分析和利用。文章介绍了漏洞的原理和利用方法，并提供了一个示例的exploit。同时，文章还提到了对漏洞进行修复的补丁分析。

https://mp.weixin.qq.com/s/GT0k-rPwahlzqz7Ru2XnUg
- 摘要: 本文介绍了获取虚拟机shell的方法，包括挂载磁盘和修改启动逻辑等。对于未加密的磁盘，可以直接挂载并修改启动脚本；对于加密的磁盘，可以通过调试获取密钥并解密磁盘。此外，还介绍了通过内存patch的方式获取虚拟机shell的方法。

https://ssd-disclosure.com/ssd-advisory-qnap-qts5-usr-lib-libqcloud-so-json-parsing-leads-to-rce/
- 摘要: QTS的JSON解析功能存在类型混淆漏洞，由于未正确检查json-object->data字段的类型。该漏洞允许攻击者劫持控制流，并可通过/cgi-bin/qid/qidRequestV2.cgi二进制文件进行访问。成功利用该漏洞的攻击者可以以管理员用户（相当于QTS操作系统中的root）的身份执行任意代码。该漏洞存在于运行QTS操作系统的QNAP NAS设备中，至少从5.1.0.2348版本开始存在。供应商已发布了修复该漏洞的补丁。

https://mp.weixin.qq.com/s/CfflBzV0a9Glf96JkgbBmg
- 摘要: 这篇文章主要讲述了作者尝试刷机摄像头的经历。作者首先尝试使用32G的SD卡刷机，但失败了。然后作者尝试使用TFTP服务器来拯救摄像头，成功了。最后作者介绍了如何修改固件并重新刷入设备。

https://voidstarsec.com/blog/uart-uboot-and-usb
- 摘要: This post is part of the Intro to Embedded RE series and focuses on UART, UBoot, and USB using the Arcade 1UP Marvel countertop cabinet as a target. The post explores the hardware of the cabinet and identifies the main components. It also discusses the connectors on the motherboard and examines unused test pads and vias on the PCB. The post provides an overview of UART and its protocol, and demonstrates how to decode UART traffic using Pulseview. It then explains how to configure the Raspberry Pi to interface with the UART on the cabinet. The post also covers the process of imaging the partitions and investigating the bootloader. Additionally, it discusses the UBoot console and its commands, as well as the environment variables that can be configured in UBoot. The post further delves into the rksfc commands, which are RockChip's SPI SFC (serial flash controller) interface tool, and provides information about the SPI flash and its partitions. It also explores the USB commands and how they can be used to read and write data from the SPI flash. The post concludes by introducing the Depthcharge utility, which can be used to automate UBoot interactions and perform flash reads and writes. The post then goes on to explain how to implement flash reads and writes using UBoot commands and how to enumerate and set up the USB port. It also demonstrates how to dump the flash using the Depthcharge utility. Finally, the post discusses the contents of the extracted flash and the next steps in the reverse engineering process. The post also covers how to analyze unknown UART traffic and connect to a serial port using screen with a Raspberry Pi. After connecting to the serial port, the UBoot console could be accessed by pressing Ctrl-C. The post includes information on writing a depthcharge script to extract each SPI flash partition to an external flash drive. The next post will focus on an in-depth look at the UBoot binary, creating and modifying memory maps using Ghidra, and attempting to flash a custom kernel to the device. The post provides links to the scripts and tools used and invites readers to reach out with questions or comments.

[Hacking Brightway scooters: A case study – RoboCoffee](https://robocoffee.de/?p=436)

[RTSP协议分析 - IOTsec-Zone](https://www.iotsec-zone.com/article/418)

[Rooting Xiaomi WiFi Routers](https://blog.thalium.re/posts/rooting-xiaomi-wifi-routers/)

https://mp.weixin.qq.com/s/X6l_OfFZM6gPoZgL9n2QgA

https://mp.weixin.qq.com/s/BwQ7Ld7cxF9gxxnzxpp6xg

[DJI Mavic 3 Drone Firmware Analysis](https://www.nozominetworks.com/blog/dji-mavic-3-drone-research-part-1-firmware-analysis/)

https://mp.weixin.qq.com/s/RUQKvzoWPks5Y2x6Ou7jCw

[2020补天杯复盘：小米小爱音箱 后渗透利用公开 | Clang裁缝店](https://xuanxuanblingbling.github.io/iot/2022/09/16/mi/)

[一种获取 FortiOS 权限的方法 | CataLpa's Home](https://wzt.ac.cn/2023/02/23/fortios_padding/)

[Firmware key extraction by gaining EL3 - The Cave](https://blog.xilokar.info/firmware-key-extraction-by-gaining-el3.html?s=09)

[ Zeus WPI | Reverse engineering an e-ink display ](https://zeus.ugent.be/blog/22-23/reverse_engineering_epaper/)

[Analyzing an Old Netatalk dsi_writeinit Buffer Overflow Vulnerability in NETGEAR Router | cq674350529's blog](https://cq674350529.github.io/2023/02/10/Analyzing-an-Old-Netatalk-dsi-writeinit-Buffer-Overflow-Vulnerability-in-NETGEAR-Router)

[Dmitry.GR: Projects](https://dmitry.gr/?r=05.Projects)

[Reverse Engineering BLE Devices — Reverse Engineering BLE Devices  documentation](https://reverse-engineering-ble-devices.readthedocs.io/en/latest/)

https://mp.weixin.qq.com/s/16V1JLcLaakCcMHjzOBbRA

[LinkSys EA6100 AC1200 - Part 1 - PCB reversing](https://0x434b.dev/linksys-ea6100_pt1/)

[DualShock4 Reverse Engineering - Part 1](https://blog.the.al/2023/01/01/ds4-reverse-engineering.html)

https://www.shielder.com/blog/2022/03/reversing-embedded-device-bootloader-u-boot-p.2/

[Shielder - Reversing embedded device bootloader (U-Boot) - p.1](https://www.shielder.com/blog/2022/03/reversing-embedded-device-bootloader-u-boot-p.1/)

[Zyxel firmware extraction and password analysis - hn security](https://security.humanativaspa.it/zyxel-firmware-extraction-and-password-analysis/)

https://mp.weixin.qq.com/s/HwU7rgjhoCsJR0XQAoyHvw

[对某webvpn系统加解密分析 - 先知社区](https://xz.aliyun.com/t/11007)

http://xdxd.love/2015/08/24/逆向路由器固件之解包/

# 无线电安全
[技术前瞻｜mqtt攻击面和挖掘思路浅析](https://mp.weixin.qq.com/s/16V1JLcLaakCcMHjzOBbRA)
- 摘要: 本文主要分析了物联网设备中常见的MQTT协议及其潜在的安全风险。MQTT是一种基于TCP/IP协议栈构建的异步通信消息协议，广泛应用于物联网设备中。文章首先介绍了MQTT协议的基本构成和工作原理，然后分析了开源项目Mosquitto的实现方式和可能存在的安全漏洞。文章还提到了MQTT协议的两大版本v3和v5的特点，以及一些历史上的漏洞案例。最后，文章提出了一些挖掘MQTT协议攻击面的思路和方法，包括代码审计和Fuzz测试等。

[BleedingTooth: Linux Bluetooth Zero-Click Remote Code Execution | security-research](https://google.github.io/security-research/pocs/linux/bleedingtooth/writeup.html)
- 摘要: BleedingTooth是Linux蓝牙子系统中的一组零点击漏洞，可以允许未经身份验证的远程攻击者在短距离内以内核特权执行任意代码。这些漏洞包括一个基于堆的缓冲区溢出漏洞（CVE-2020-24490），可以通过向蓝牙5芯片发送大型广告报告来触发。此漏洞仅在具有蓝牙5芯片的设备上触发，并且只有在受害者正在主动扫描广告数据时才能触发。此外，还存在另外两个漏洞：BadChoice涉及基于堆栈的信息泄漏（CVE-2020-12352），BadKarma是基于堆的类型混淆漏洞（CVE-2020-12351）。这些漏洞构成了严重的安全风险，并可被利用以控制受害者的设备。BadKarma漏洞可以与BadVibes和BadChoice漏洞链接，以实现远程代码执行。用于通信的A2MP通道可以重新配置以绕过BadKarma漏洞并直接调用A2MP接收处理程序。通过将所需的通道模式封装在L2CAP_CONF_UNACCEPT配置响应中，可以实现此重新配置。可以通过操纵struct sock对象和sk_filter()子程序进一步利用漏洞，以控制struct amp_mgr对象并最终执行任意代码。可以使用堆喷射技术来塑造堆并实现受控的越界读取，从而允许对内存地址进行操纵。BadChoice漏洞可用于泄漏内存布局并帮助控制具有已知地址的内存块。通过在之前发送L2CAP_CONF_RSP并尝试将A2MP通道重新配置为L2CAP_MODE_ERTM，可以泄漏偏移量为0x110的struct l2cap_chan对象的地址。该对象的大小为792字节，并在kmalloc-1024 slab中分配。可以通过销毁A2MP通道来释放struct l2cap_chan对象，从而允许与Use-After-Free攻击相同的策略。该技术涉及泄漏struct l2cap_chan对象的地址，通过销毁A2MP通道释放对象，重新连接A2MP通道，并使用堆原语向kmalloc-1024 slab喷射，以可能重新获取以前的struct l2cap_chan对象的地址。该技术可用于控制struct l2cap_chan对象。可以进一步利用这些漏洞来通过控制内存块、泄漏.text段指针和构建ROP链来实现远程代码执行。可以利用对sk_filter字段的控制来将其指向有效载荷并实现RIP控制。该利用还可以执行代码重用攻击，如ROP/JOP，以实现内核堆栈枢轴和执行任意命令。该漏洞的利用的概念验证可在GitHub上找到。漏洞的发现和披露时间表以及研究人员对改进Linux内核安全性的贡献也提供了。

https://www.nozominetworks.com/downloads/US/Nozomi-Networks-WP-UWB-Real-Time-Locating-Systems.pdf

[Hacking Bluetooth to Brew Coffee from GitHub Actions: Part 1 - Bluetooth Investigation | grack](https://grack.com/blog/2022/12/01/hacking-bluetooth-to-brew-coffee-on-github-actions-part-1)

# 硬件安全
[Intro to Embedded RE Part 1: Tools and Series Overview](https://voidstarsec.com/blog/intro-to-embedded-part-1)
- 摘要: 这篇博客提供了逆向工程嵌入式系统所需的工具概述。它涵盖了硬件和软件工具，包括树莓派、逻辑分析仪、万用表、电源、面包板和焊接铁。文章还提到了其他工具，如硅垫、显微镜、FTDI扩展板、示波器、ChipWhisperer、Ghidra、Binwalk、Kaitai Struct和Pulseview/SigRok。该系列将涵盖构建Ghidra开发环境、UART发现和固件提取、理解Ghidra中的内存映射和地址空间、通过SPI和USB进行固件提取、用于固件分析的Kaitai Struct、I2C和并行闪存提取、PCode仿真以及JTAG概述和应用等主题。系列中的每篇文章都有特定的重点，并提供概述、目标、工具、硬件/软件拆解、结论和资源。文章还包含一个指向GitHub存储库的链接，用于访问与每个目标相关的材料。该系列旨在为对学习逆向工程嵌入式系统感兴趣的硬件和软件工程师提供一条路线图。

https://mp.weixin.qq.com/s/HMMa44u-FtSRPxQ1R-73jw

https://mp.weixin.qq.com/s/TsDWgCABWGCUMVUUK3f05A

[Reverse engineering an EV charger](https://www.mnemonic.io/no/resources/blog/reverse-engineering-an-ev-charger/)

[I'm Building a Self-Destructing USB Drive - Interrupt Labs Blog](https://interruptlabs.ca/2022/07/29/I-m-Building-a-Self-Destructing-USB-Drive/)

https://martinschwarzl.at/media/files/thesis_main.pdf

[PCIe DMA Attack against a secured Jetson Nano (CVE-2022-21819) – The Good Penguin](https://www.thegoodpenguin.co.uk/blog/pcie-dma-attack-against-a-secured-jetson-nano-cve-2022-21819/)

https://raelize.com/upload/research/2017/2017_BlueHat-v17_KERNELFAULT-R00ting-the-Unexploitable-using-Hardware-Fault-Injection_CM_NT.pdf

[PS5 Hack: Keys incoming for the mysterious CP Box? - Wololo.net](https://wololo.net/2023/01/29/ps5-hack-keys-incoming-for-the-mysterious-cp-box/)

[A journey into IoT – Chip identification, BUSSide, and I2C - hn security](https://security.humanativaspa.it/a-journey-into-iot-chip-identification-busside-and-i2c/)

https://mp.weixin.qq.com/s/XxzANNCKwvVmrq2eOihyTw

[Data exfiltration using a COVID-bit attack | Kaspersky official blog](https://www.kaspersky.co.uk/blog/covid-bit-attack/25340/?reseller=gb_kdaily-social_acq_ona_smm__all_b2c_some_sma_______)

https://mp.weixin.qq.com/s/oDMF3uVyJ_XR8h2rPakU3Q

[pfBlockerNG Unauth RCE Vulnerability - IHTeam Security Blog](https://www.ihteam.net/advisory/pfblockerng-unauth-rce-vulnerability/)

https://mp.weixin.qq.com/s/K0SXMVVdmkAdZyrNnCorBw

https://ryancor.medium.com/hardware-trojans-under-a-microscope-bf542acbcc29

https://mp.weixin.qq.com/s/G-Aas9ZFjEfUN6gj2hwusw

# 模糊测试
https://github.com/otsmr/blackbox-fuzzing
- 摘要: 这篇学期论文主要讨论了在物联网设备中使用模糊测试来发现与内存相关的漏洞。论文探讨了模糊测试物联网设备所面临的挑战，例如专有源代码和不兼容的CPU架构。论文介绍了IoTFuzzer，这是一个自动化的模糊测试框架，旨在在没有访问固件映像的情况下发现物联网设备中的内存损坏漏洞。论文解释了模糊测试中的harness和corpus的概念，以及在固件中识别潜在易受攻击函数的过程。以二进制文件"wscd"为例，演示了模糊测试的一般过程。此外，还讨论了其他不同二进制文件中的潜在易受攻击函数，如"httpd"和"tmpd"。论文还探讨了使用自定义二进制协议及其潜在漏洞。作者开发了一个harness，并使用AFL++模糊器和QEMU模拟器来对目标函数进行模糊测试。论文还描述了使用Docker创建可重现的模糊测试环境的过程。作者讨论了开发和调试harness的过程，并使用Wireshark生成了一个种子corpus。使用AFL++状态屏幕来监视模糊测试过程，并使用循环计数器和总崩溃数等指标来确定何时停止模糊测试。论文得出结论，虽然模糊测试可能是发现安全漏洞的有效方法，但开发一个可工作的harness并识别出潜在目标可能是耗时且复杂的。

[How I fuzz and hack APIs?](https://rashahacks.com/how-i-fuzz-and-hack-api/)


# 工具使用
https://chat.openai.com/chat

https://mp.weixin.qq.com/s/DZ2Nd5sIjWOuAGwLzBEQGQ

https://mp.weixin.qq.com/s/sBM-I6-ojYuJ9KyfXl87hg
# 安全论文
https://mp.weixin.qq.com/s/Q2OfKSDsv3-4zdlW3tkgxg

https://mp.weixin.qq.com/s/orbT6HuK6cLN3A2-gcA0Ng
# 会议
## 国内会议
## 国外会议
[WordPress › Error](https://conference.hitb.org/hitbsecconf2022sin/materials/D2 COMMSEC - Cracking Kyocera Printers - Yue Liu, Minghang Shen )

[Page not found - HITBSecConf2023 - Amsterdam](https://conference.hitb.org/hitbsecconf2023ams/materials/D1T1 - Your Not So Home Office - Soho Hacking at Pwn2Own - McCaulay Hudson )

[The DEF CON® Media Server - Archives of the conferences](https://media.defcon.org/?C=N)

https://i.blackhat.com/USA-22/Thursday/US-22-Baines-Do-Not-Trust-The-ASA-Trojans.pdf

https://github.com/binarly-io/Research_Publications/blob/main/OffensiveCon_2022/UEFI Firmware Vulns Past, Present and Future.pdf


# CTF
https://www.reddit.com/r/ReverseEngineering/comments/101iozj/reverse_engineering_and_exploiting_an_iot_bug/

# 安全报道
[Ping bug potentially allows remote hack of FreeBSD systemsSecurity Affairs](https://securityaffairs.co/wordpress/139300/hacking/cve-2022-23093-freebsd-systems-flaw.html)

https://mp.weixin.qq.com/s/Y-_1SEHSDBgWEEOD0dJu6g

https://mp.weixin.qq.com/s/GoYc5SA7cbNIrf2iRMKKSw

https://mp.weixin.qq.com/s/tUikU0U-FCo33kWsmHTCIQ

# 开源安全项目
https://github.com/romainthomas/reverse-engineering-workshop

https://github.com/Accenture/VulFi

https://github.com/shijin0925/IOT/blob/master/TOTOLINK A3100R/8.md

https://github.com/aaronsvk/CVE-2022-30075

https://github.com/airbus-seclab/AutoResolv

https://github.com/PortSwigger/http-request-smuggler

https://github.com/Le0nsec/SecCrawler

https://github.com/pedrib/PoC/blob/master/advisories/Cisco/DCNMPwn.md

https://github.com/wudipjq/my_vuln/tree/main/ARRIS

https://github.com/Cossack9989/Vulns/tree/master/IoT

# 车联网安全
[IOTsec-Zoneç©èç½å®å¨ç¤¾åº](https://iotsec-zone.com/article?id=369)

[IOTsec-Zoneç©èç½å®å¨ç¤¾åº](https://iotsec-zone.com/article?id=369)

https://mp.weixin.qq.com/s/LzrqCOq6BjPC6s3SjNvXcw

[Web Hackers vs. The Auto Industry: Critical Vulnerabilities in Ferrari, BMW, Rolls Royce, Porsche, and More | Sam Curry](https://samcurry.net/web-hackers-vs-the-auto-industry/)

https://mp.weixin.qq.com/s/O1EfTtvmAc0e2H6DFlElYA

https://mp.weixin.qq.com/s/pFf7hvan2Z9VOxGyuwIvmg

[Bug in Honda, Nissan, Toyota Cars App Let Hackers Start The Car Remotely](https://cybersecuritynews.com/vulnerability-in-honda-nissan-toyota-cars-app/)

https://mp.weixin.qq.com/s/bx-Rtw1kkSb56iiaUpcqNQ

https://mp.weixin.qq.com/s/0grR0FRCMoWvsGJAGLTfUg


# 漏洞情报库
[💀 Sploitus | Exploit  漏洞情报库 Hacktool Search Engine](https://sploitus.com/)


National Vulnerability Database（NVD）：https://nvd.nist.gov/

Symantec：https://www.symantec.com/security-center/vulnerability-management

Microsoft：https://technet.microsoft.com/en-us/security/

Tenable：https://www.tenable.com/

Rapid7：https://www.rapid7.com/

Zerodium：https://zerodium.com/

Bugtraq：https://www.securityfocus.com/vulnerabilities

vulmon: https://vulmon.com/vulnerabilitydetails?qid=CVE-2022-1040

synk vulndb：https://snyk.io/vuln/search?q=log4j&type=any

# 其他
[Millions of Routers at Risk: CVE-2024-21833 Threatens TP-Link Devices](https://securityonline.info/millions-of-routers-at-risk-cve-2024-21833-threatens-tp-link-devices/)
- 摘要: 最近，CYFIRMA的研究团队对一种名为CVE-2024-21833的安全漏洞进行了详尽分析，该漏洞对TP-Link路由器构成重大风险。该漏洞于2024年1月10日被JPCERT/CC发现，被赋予了8.8的CVSS评分，表示其严重性。该漏洞影响了Archer AX3000、AX5400、AXE75、Deco X50和XE200等型号的路由器，允许未经身份验证的攻击者在附近网络中执行任意操作系统命令。用户应及时更新固件以解决这些安全问题。此外，近年来网络基础设施漏洞的攻击趋势日益增长，TP-Link漏洞并非孤立事件。此漏洞的利用可能导致各个行业的供应链攻击机会，包括金融、教育、政府、医疗、保险和法律实体。用户和网络管理员应采取相应的缓解措施，包括及时更新固件和实施网络分割和防火墙规则。

https://media.defcon.org/DEF CON 30/DEF CON 30 presentations/Daniel (dozer) Jensen - Hunting Bugs in The Tropics V1.0.pdf

https://github.com/horizon3ai/CVE-2022-39952

https://mp.weixin.qq.com/s/ZpIreydFhKbaGtWjKK6wog

https://github.com/infobyte/cve-2022-27255/blob/main/DEFCON/slides.pdf

https://mp.weixin.qq.com/s/xVU8o5NcbFYmy0yPJfiwVQ

[Hardware 其他
https://media.defcon.org/DEF CON 30/DEF CON 30 presentations/Daniel (dozer) Jensen - Hunting Bugs in The Tropics V1.0.pdf

https://github.com/horizon3ai/CVE-2022-39952

https://mp.weixin.qq.com/s/ZpIreydFhKbaGtWjKK6wog

https://github.com/infobyte/cve-2022-27255/blob/main/DEFCON/slides.pdf

https://mp.weixin.qq.com/s/xVU8o5NcbFYmy0yPJfiwVQ
 Embedded Systems: A little early effort in security can return a huge payoff – NCC Group Research](https://research.nccgroup.com/2022/02/22/hardware-embedded-systems-a-little-early-effort-in-security-can-return-a-huge-payoff/)

https://mp.weixin.qq.com/s/5LHUJjp2uceVFcX_RuxeSQ

