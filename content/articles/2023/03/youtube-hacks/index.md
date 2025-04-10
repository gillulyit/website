+++
date = '25 Mar 2023'
draft = false
title = 'LTT Channel Hacked: Details'
+++

## Session Hijacking Details

When you login to a website, it will generate a session or a token, depending on how the server is setup. If you check the "Remember me" box on the login form, it will keep the session or token in as persistent, and your browser will download it. After that, you can then go to said website, and the server will request from your computer the session, or will verify the token that your web browser has on file, then log you in if that's valid.

Where session hijacking comes into play is when said session ID or token is copied to another endpoint via malware (malicious software or firmware) typically. There are other means of copying said session ID's or tokens, including manually, but a major channel on Youtube got hijacked with the malware method as it is the most common currently.

So, what can you do to protect yourself?

## How to protect yourself

Although most of the burden of protection lays on the webadmin of the service, there is one thing you can do on your end to mitigate the consequences of said attack.

If at all possible, you want to be very aware of what you are downloading and installing on your computer. As this can be the stereotypical email attachment, this also extends to things downloaded from websites, and also flash drives your friends might let you borrow.  Only open things that you absolutely need to open. If it's something you absolutely have to open, wait a few days if you can. That may give your in-the-background antimalware to catch up its signatures to any potential threats.

First thing to do is to verify that your computer doesn't have any malware on it before you proceed (The malware will just grab the new sessions if it persists). You can follow the [instructions here](https://www.howtogeek.com/679263/how-to-scan-with-microsoft-defender-antivirus-on-windows-10/) to run a scan using Windows' built-in defender which is about middle of the pack among third party antimalware vendors.

If you have a third party antimalware installed that you trust more, open it, and follow its steps to scan your computer.

The scanning it does while it's running in the background can sometimes be incomplete because it may have not been discovered or its signature captured while the malware was downloaded and scanned.

A good second-opinion scanner can be [Malwarebytes Free Edition](https://www.malwarebytes.com), followed up by the [ADWCleaner](https://www.malwarebytes.com/adwcleaner) tool they have acquired.

Consult a local and honest computer repair company if this confuses you.

After that is done, you'll want to get back into said service or website, and invalidate all of your login sessions. Including the legitimate ones. This is typically under the security settings of your account titled something along the lines of "Sessions."

## How services can protect you

A few of the actions services can do to protect you are below:

1. Invalidate sessions if they suddenly appear outside of a reasonable scope of IP geolocation.
2. Require passwords for all administrative tasks including changing or recovering Youtube stream keys (in major Youtube channels instances of this happening, the cybercriminal used their access to stream a scam deep-fake of Elon Musk being interviewed about cryptocurrency)
3. Create instructions on their help centers about how to deal with a session hijacking attack.

Even though this list might be in vain, users have some power in not using services until the providers implement these key security features.