---
page_ref: /community/rules/hacking.html
---

# Hacking

<!-- @DOCS__HEADER_PLACEHOLDER@ -->

**tl;dr: Termux official communities neither provide support nor allow others to post or comment about hacking ([blackhat](#blackhat-hacking-not-allowed), [whitehat](#whitehat-hacking-not-allowed) or any other colour) or [hacking packages](#hacking-packages-not-allowed), other than some [exceptions](#exceptions). Related topics like [spamming](#spamming-not-allowed), [DOS/DDOS](#dos-and-ddos-not-allowed), [OSINT](#osint-not-allowed) are not allowed either. Asking and posting more than once is one of the fastest paths to a ban.** If you were sent this link in response to a question and think it may not apply to you, read the rest before posting anything else.

**Termux is not just a hacking tool, contrary to what you may have heard on some random YouTube video.** Termux is a general-purpose linux environment meant for wide range of use cases. People often use it for task automation via shell scripting, SSH client, file synchronization and backup, running web servers, or for programming and developing software. Hacking is just only one of the many possible use cases.

- [Rules](#rules)
  - [Blackhat hacking (not allowed)](#blackhat-hacking-not-allowed)
  - [Whitehat hacking (not allowed)](#whitehat-hacking-not-allowed)
  - [Spamming (not allowed)](#spamming-not-allowed)
  - [DOS and DDOS (not allowed)](#dos-and-ddos-not-allowed)
  - [OSINT (not allowed)](#osint-not-allowed)
  - [Hacking Packages (not allowed)](#hacking-packages-not-allowed)
  - [Exceptions](#exceptions)
- [Terminology](#terminology)

---

&nbsp;





## Rules

### Blackhat hacking (not allowed)

**[Hacking](#blackhat) which violates laws or typical ethical standards for nefarious purposes, such as account hacking, privacy violation, spying, stalking, fraud, cybercrime, cyberwarfare, trolling or malice is not allowed.** This may include following.

- Access someone else's data, computers, network, or accounts without their consent to violate their privacy and steal data. For example:
  - How to hack Wi-Fi, Facebook, Instagram, etc?
  - How to view private photos of a specific Instagram account?
  - How to track someone knowing phone number or IP address?
  - How to create a web site clone for phishing?
  - How to spy on someone's phone?
  - How to bruteforce into password protected accounts or files?
- Send ransomeware to others.
- Posting about how to install, use or fix problems of tools that are dominantly for hacking, such as Kali Linux, Metasploit, Hashcat, Hydra, SQLMAP, etc.

You may say **Someone is doing something evil and I need to hack them back**, but if you need help just installing hacking tools, you do not have the skills to get into a computer fight with bad guys. Contact the humans responsible for abuse reports on the sites or domains they're using, or local law enforcement.

### &nbsp;

&nbsp;



### Whitehat hacking (not allowed)

**[Ethical hacking](#whitehat) that is done with the owner's permission to improve security of computer systems is also not allowed.** This may be surprising to some people or security researchers, but while we *theoretically* support ethical use of hacking and would encourage people to go into such fields, we do not have the time, resources or patience to *practically* investigate whether a user's intentions are ethical or not, even if they claim or actually are getting a degree in the field or are a security researcher. We do not want to support bad use cases of hacking, which brings in bad publicity to the Termux project. Moreover, any such hacking discussion will just attract more users with nefarious purposes and script-kiddies as well, and we do not want to deal with them or be a part of such discussions.

However, any community members who want to support the ethical use of hacking in Termux, they are welcome to host hacking related packages in their own repositories and create and moderate their own unofficial Termux communities.

<!-- FIXME: Fix link: `../../projects/termux/termux-packages/docs/latest/get-started/infosec/index.html` -->

If you are actually studying computer security or are interested in it, then you need to learn how to make things first before learning how to break them and you need to understand the ethical implications of your work and that illegal activities may result you in getting into serious legal trouble, including huge fines or jail time. Check our [how to get into infosec](https://github.com/termux/termux-packages/blob/site/site/pages/en/projects/docs/get-started/infosec/index.md) docs for more info on how to get into this field.

<!-- FIXME: Fix link: `../../projects/termux/termux-packages/docs/latest/get-started/how-to-use-termux-safely/index.html` -->

Moreover, do not trust random YouTube videos or GitHub repositories for hacking with Termux, they are mostly scams, which may result you getting hacked instead or you losing all your data on your device, check [how to use termux safely](https://github.com/termux/termux-packages/blob/site/site/pages/en/projects/docs/get-started/how-to-use-termux-safely/index.md) docs for more info.

### &nbsp;

&nbsp;



### Spamming (not allowed)

**[Spamming](#spamming) others by sending them messages or posts if they didn't ask for it is not allowed.** This may include following.

- How to spam with SMS? Which SMS bomber is the best?
- How to send bulk messages in WhatsApp (for business)?

### &nbsp;

&nbsp;



### DOS and DDOS (not allowed)

**[DoS](#denial-of-service-attack-dos) and [DDOS](#distributed-denial-of-service-attack-ddos) attacks by sending excessive traffic to temporarily or indefinitely disrupting services is not allowed.** This may include following.

- How to send DOS or DDOS to a website? Which DOS tools is best?

### &nbsp;

&nbsp;



### OSINT (not allowed)

**[OSINT](#open-source-intelligence-osint) is not allowed.** This may include following.

- Posting about how to install, use or fix problems of tools that are dominantly for OSINT.

### &nbsp;

&nbsp;



### Hacking Packages (not allowed)

Requesting packages to be provided in our official repositories which serve solely destructive or privacy violation purposes is not allowed, including but not limited to pentesting, phishing, bruteforce, sms/call bombing, DDoS attacks, OSINT. Check our [packing policy](https://github.com/termux/termux-packages/blob/master/CONTRIBUTING.md#packaging-policy) for more info.

You may ask **"... Then why is `$HACKING_TOOL` in the repos?"**, and it is because Termux maintainers make case-by-case decisions about whether to accept packages based on the balance of their usefulness. For example, we package `nmap`, which can be used unethically but is a core tool for network diagnostics, but don't package `metasploit`, which is accurately characterized as an engine for breaking into other people's computers.

However, we do not block in any way the usage of any tools meant for any kind of hacking. Users or security researchers who want to use specific packages not provided by us are free to compile them themselves. Check [building packages](https://github.com/termux/termux-packages/wiki/Building-packages) docs for more info.

#### &nbsp;

&nbsp;



### Exceptions

Not everything security related is hacking related too. **Discussing or posting about vulnerabilities in packages, apps or operating systems with a defensive intent for users to protect themselves and not getting hacked is allowed. However, attackive intents are not allowed.** Moderation will be done on a case to case basis.

You may ask **"... Then why was `$DISCUSSION` allowed?"**, and it is because Termux moderators have discretion to allow or disallow individual discussions based on the context of the question or familiarity with the user asking. There is no definitive way to find the real intent of the user, but it is still easier to find it for a well known user, than a random user, so a user may be asked to stop discussing or may have their post locked even if their intentions are good.

---

&nbsp;





## Terminology

##### Hacker

A hacker is a computer expert who uses their technical knowledge to achieve a goal or overcome an obstacle, within a computerized system by non-standard means - often referred as "power" or "advanced" users. Hackers are not necessarily persons who uses their skills to breach computer system security. [1](https://en.wikipedia.org/wiki/Hacker).


##### Security Hacker

A security hacker is someone who explores methods for breaching defenses and exploiting weaknesses in a computer system or network. [1](https://en.wikipedia.org/wiki/Security_hacker).


##### Blackhat

Hacking which violates laws or typical ethical standards for nefarious purposes, such as account hacking, privacy violation, spying, stalking, fraud, cybercrime, cyberwarfare, trolling or malice. [1](https://en.wikipedia.org/wiki/Black_hat_(computer_security)).


##### Whitehat

Ethical hacking that is done with the owner's permission to improve security of computer systems. [1](https://en.wikipedia.org/wiki/White_hat_(computer_security)).


##### Script kiddie

An unskilled individual who has poor knowledge in computer systems and programming and uses scripts or programs developed by others, primarily for malicious purposes. Script kiddes are known to often reject educational resources and other kind of help on improving their skills, especially if learning path takes much time. They need everything and now, claiming themselves as "newbies". [1](https://en.wikipedia.org/wiki/Script_kiddie)


##### Phishing

A form of social engineering and scam where attackers deceive people into revealing sensitive information or installing malware such as ransomware. [1](https://en.wikipedia.org/wiki/Phishing)


##### Exploit

An exploit is a piece of software, a chunk of data, or a sequence of commands that takes advantage of a bug or vulnerability to cause unintended or unanticipated behavior to occur on computer software, hardware, or something electronic (usually computerized). Such behavior frequently includes things like gaining control of a computer system, allowing privilege escalation, or a denial-of-service (DoS or related DDoS) attack. [1](https://en.wikipedia.org/wiki/Exploit_(computer_security))


##### Denial-of-service attack (DoS)

A cyber-attack in which the perpetrator seeks to make a machine or network resource unavailable to its intended users by temporarily or indefinitely disrupting services of a host connected to a network. Denial of service is typically accomplished by flooding the targeted machine or resource with superfluous requests in an attempt to overload systems and prevent some or all legitimate requests from being fulfilled. [1](https://en.wikipedia.org/wiki/Denial-of-service_attack)


##### Distributed Denial-of-service attack (DDoS)

A [DoS attack](#denial-of-service-attack-dos) where the incoming traffic flooding the victim originates from many different distributed sources, usually by thousands of infected computer systems. [1](https://en.wikipedia.org/wiki/Denial-of-service_attack)


##### Spamming

Sending unsolicited content to messaging systems and social media for the purpose of commercial advertisement, phishing, or repeatedly sending the same message to the same user to annoy or disrupt them, etc. [1](https://en.wikipedia.org/wiki/Spamming)


##### Email or SMS bombing

A form of [spamming](#spamming) that sends large volumes of emails or SMS to an address in a short time to overflow the inbox. [1](https://en.wikipedia.org/wiki/Email_bomb)


##### Open-source intelligence (OSINT)

Collection and analysis of data gathered from open sources (covert sources and publicly available information (PAI)) to produce actionable intelligence. OSINT is primarily used in national security, law enforcement, business intelligence functions and as a precursor to hacking. [1](https://en.wikipedia.org/wiki/Open-source_intelligence)


##### Brute force

An attack which consists of an attacker submitting many passwords or passphrases with the hope of eventually guessing correctly. Under perfect conditions and without time constraints or max submission limits, this attack is almost always successful. In reality, it is the most expensive way of gaining unauthorized access as require trade off between consumed computing resources (energy) and time. [1](https://en.wikipedia.org/wiki/Brute-force_attack)


##### Root

Also known as Superuser - a special user account that normally has all the permissions required for full control over the operating system. On modern Linux-based systems its privileges are defined through [capabilities](https://man7.org/linux/man-pages/man7/capabilities.7.html), which can be revoked or selectively granted to non-root users. More fine-grained root user permissions control can be achieved through implementing mandatory access control policies, e.g. via SELinux. [1](https://en.wikipedia.org/wiki/Superuser)


##### Rooting

An activity aiming to gain root privileges on the device. For Android, this is normally done by unlocking the bootloader if your device vendor allows it and then installing a root manager like [Magisk](https://github.com/topjohnwu/Magisk) or [SuperSU](https://su.chainfire.eu/), but may be done by using an [exploit](#exploit). [1](https://topjohnwu.github.io/Magisk/install.html)


##### Custom kernel

An operating system kernel with extra features besides bare minimum functionality. As Android typically uses a very minimal Linux kernel build, in order to add support for additional features or custom hardware, you will need to compile it yourself and flash it on your device which will require [rooting](#rooting) your device. [1](https://source.android.com/docs/core/architecture/kernel), [2](https://source.android.com/docs/setup/build/building-kernels)


##### Monitor mode

Also known as RFMON (Radio Frequency MONitor) - a functionality of wireless network interface adapter allowing to capture radio frames. It is known to be either disabled or not implemented at firmware level for the Wi-Fi adapters built into Android devices. Capturing using a wireless adapter with [USB OTG](https://en.wikipedia.org/wiki/USB_On-The-Go) is possible, but will normally require a [custom kernel](#custom-kernel) to work. [1](https://en.wikipedia.org/wiki/Monitor_mode)

## &nbsp;

&nbsp;
