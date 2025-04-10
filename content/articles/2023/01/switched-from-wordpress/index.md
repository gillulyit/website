+++
date = '14 Jan 2023'
draft = false
title = 'Switched this site from WordPress to Hugo'
+++

I had made the plunge into creating this site, custom in HTML using Hugo Static Site generator, mainly for the reasons outlined below.

## Security

No matter how many times I checked my modules to see how many updates they had, and for WordPress itself, my hosting service was always warning me about security vulnerabilities with the installation.

One good thing about creating static pages, including with Hugo, is that the server itself is only hosting raw content, instead of doing server-side scripting. Which means it's only vulnerable if attackers find out my SSH or FTP password.

## Spam

Another thing that swayed me to go this route is the spam I would get from various spammers on Wordpress. In their infinite wisdom, the creators of Wordpress decided to put comment fields on attachment pages, which cannot be turned off, and they're not normally visible unless said content is used in a post. So I had a slew of comments on my site logo images.

The only way I could turn that off was to change the sitewide setting to require logins to post comments. Otherwise, there was no other setting.

