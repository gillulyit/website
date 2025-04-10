+++
date = '2024-05-09T21:53:44-04:00'
draft = false
title = 'Microsoft to enable bitlocker'
+++

One of the major turns Microsoft is making in an upcoming update is to turn Bitlocker on by default. Even if a user has bypassed the requirement for an online account while installing Windows. If Bitlocker doesn't engage correctly with the computer's TPM chip during the enabling and encrypting process, it will very likely result in a prompt for the recovery key, and without it being connected to an online account, it won't be recoverable from there.

Even with the online account, I've seen times where Bitlocker has prompted for recovery keys on boot, and it **wasn't** backed up in the online account. It's very tricky to enable something like disk encryption and **not** lock some users out of their files. Which is why I'm against a corporation like Microsoft, enabling it behind the scenes without prompting or even telling users that they're going to do it. It's not their files they're putting on the line by doing so.

So here's some words of advice:

## Run Backups

Now might be the time to back up all the files you deem important. My general rule of thumb, is if you'll cry when you lose it, back it up.

The best way to back up depends on the use case. The simplist way to back up the majority of the time is to buy a few flash drives which are big enough to hold your files, and somehow copy your files onto them. There's a few ways to do it, one is simply right-clicking the file or folder you want to put onto the flash drive, (typically one's important files are either in Desktop, Documents, or Pictures, unless they were explicitly put elsewhere), and using the "Send To" flyout. 

Watching the sidebar or "This PC" screen while unplugging or plugging in the flash drive can let you know which one it is.

If you're an Office 365 subscriber, synching the Documents, Desktop, and Pictures option can be enabled in its settings under the "Manage Backup" screen if it hasn't notified you to do so. Even though that's technically not a backup, it's better than nothing.

Another option is to install and setup something like [FreeFileSync](https://freefilesync.org/), to backup your files either on a one-time basis or as part of a schedule. While doing a scheduled backup to a live source, I'd recommend rotating different flash drives every week or so, just in case you get hit with ransomware.

## Switching to Linux

One thing I see on the internet is a group of people encouraging the not-so-savvy users to switch to Linux. Which can be a daunting task for the people who don't understand computers on a fundamental level. At the same time I can understand the frustrations which would cause some users to make the switch themselves and encourage others to do so as well. As some of the decisions Microsoft is making has been pretty abrasive to users. But are they so abrasive that backing up everything, then jumping ship to an entirely new system, and restoring everything is the right course of action? Only you can decide for yourself.

If you're comfortable with the truth of having to learn more about your computer than you thought was possible, I'd suggest [Linux Mint](https://linuxmint.com/) for long time Windows users. It is laid out much the same and has a pretty well thought out visual software library (much of the same programs that one would use on Windows, probably won't work on Linux). Looking up what you want to do on the software library will likely show you any software that would do the task.

Also some multimedia providers reduce the video quality of streams and sometimes make videos unavailable for Linux users, due to them not being able to DRM (Digital Rights Management, essentially keeps people from copying or recording some content) it on a level deemed necessary by various licensing organizations.

Then again, it's not something I'd recommend personally for non-savvy users but I can help with a back up and transition process for those in the Belmont area who are just so fed up with these decisions Microsoft is making.