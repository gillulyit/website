+++
title = "Web Design"
date = "2025-05-09T17:45:46-04:00"
draft = false
weight = 3
description = "Our website design services including custom Hugo sites."
[params]
image = "web-design.webp"
+++

For small businesses in and around Allegany County, NY, we can provide website design services such as:

## Custom websites in Hugo

Our custom websites using Hugo static site generators are secure because they don't expose a login screen to the internet. All of the files needed to make and push edits, can be secured onto a local computer. Either from one of ours or a specific one in your office (if you want to be able to make your own changes). How the process works:

- As part of the job, we create Hugo project files which are used as templates to build your site using one simple command
- Content is written in markdown, which is a simple language which can translate to a markup language like HTML, for the site
- A keypair is generated for a specific user on a specific computer using its ssh-keygen command
- The contents of the id*.pub file from the .ssh directory it creates is appended to .ssh/authorized_keys on the webserver
  - Multiple ones can be appended on their own lines in the authorized_keys file if you need to be able to post changes from multiple computers
- We can help create an automatic script to build the site with Hugo and upload it to your webserver
- Then to post changes you or we could make the changes to the markdown files in the content folder. Then with one simple command and the passphrase of the keypair, the changes get uploaded immediately.

## Wordpress Block themes

We can help you setup a Wordpress installation on your webserver and also in creating a theme in Wordpress blocks.

For things that are over our head on the Wordpress side of things, there are two or three other local businesses we can work with to work on said websites.

## Simple React Apps

If you need a simple React JS app built into your website, like a price calculator; we can help you create it and integrate it into your own website.