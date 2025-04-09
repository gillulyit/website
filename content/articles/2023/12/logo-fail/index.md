---
title: "LogoFAIL Exploit Details"
date: 2023-12-15T10:39:20-05:00
draft: false
---

One of the major things currently in the media is the discovery of the LogoFAIL vulnerability which was disclosed by a security research firm, Binarly, if you're into technical knowledge you can read the article [here](https://binarly.io/posts/The_Far_Reaching_Consequences_of_LogoFAIL/index.html)

## What it means to users

The TL:DR; of this for users is that there maybe a major bug in their boot firmware which may allow for more persistant malware. And like always, it is a good idea to practice vigilance in downloading and installing software.

Another thing to keep in mind is that for us tech providers, from what I gather, is that reflashing firmware may become a part of malware scrubbing which means extra time and extra risk to the device.

At least until vendors release patches to effected firmware, which may not come to older devices.

## What it means to developers

Software developers, especially those dealing in Open Source projects, should be made very aware of this exploit and the signs to look out for when performing code review from other contributors and pull requests. As personally, if there is a wide exploit on this then I could see a major Open Source project being a primary vessel for this.

Or even on Closed Source software, if a cyber crime ring can bring an inside actor to the development floor of a company and introduce the exploit that way.

So if you are a developer or open source contributor, be sure to review code more vigilantly.

## Future mitigations

As firmware providers start releasing patches to this vulnerability, device vendors should be pushing patches out to the userbase in the (hopefully) near future. If your device starts updating its firmware, don't interrupt it, and make sure you plug it into power if it's a laptop.

Alternatively, you can get your device model and serial number and check against your device manufacturer's website for system firmware updates, which their release notes should state "LogoFAIL" in it somewhere.

* [HP](https://support.hp.com/us-en/drivers)
* [Dell](https://www.dell.com/support/home/en-us?app=drivers)
* [Lenovo](https://pcsupport.lenovo.com/us/en)
* [Framework](https://knowledgebase.frame.work/bios-and-drivers-downloads-rJ3PaCexh)