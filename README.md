# Web browsing security basics

## About

This document provides information and guidance to help you reduce your risk of being hacked while using the internet.

This document **does not** intend to be an exhaustive list of risks and mitigations, but gives an introduction to the topic and highlights some tools and techniques which can be used to avoid the most common risks.

Links to more comprehensive resources will be included where relevant for those who want to dig deeper.

This document does not go into detail on the topic of **privacy** as this is a big topic and it deserves proper explanation, which is beyond the scope of this document. See the resources at the end of the document for information on this topic.

This document does not go into great detail on **device security** (another big topic, given the range of devices and operating systems), but some high-level tips are included.

## Why should I care?

What is potentially at stake if you get hacked?

* Identity theft
* Hackers gain access to your credit card details and purchase goods using those accounts / details
* Hackers gain access to your private personal/business data

## Common threats

* Data breaches
* Password guessing/cracking
* Software security vulnerabilities
* Phishing

Read on for more information on these threats and techniques to avoid them.

## Data breaches
### What is a data breach?

A data breach occurs when private/confidential data is stolen from a company's computer systems and copied or transmitted elsewhere, enabling others to access it who would otherwise be unable and unauthorised to do so.

### What data can be leaked during a breach?

If you have an account with a company whose systems have been breached, it's possible that your private data has been accessed in the breach and shared with others, who may attempt to use that information for personal/financial gain.

This could include your account username and password, your credit card information or other personal/sensitive data, depending on what information the company had about you and how securely it was stored.

### Can any company be affected by a data breach?

Yes - companies large or small can be the target of a data breach.

Here are some recent examples:

* Adobe
* Avast
* BitTorrent
* Bitly
* Dailymotion
* Disqus
* Domino's
* Dropbox
* Epic Games
* Experian
* Kickstarter
* LinkedIn
* Patreon
* Snapchat
* Sony
* Tesco
* Vodafone
* Yahoo

See [Have I Been Pwned - Pwned Websites](https://haveibeenpwned.com/PwnedWebsites) for a more examples of companies who've suffered a data breach.

### How can I find out if my data was included in a data breach?

Check out Troy Hunt's [Have I Been Pwned](https://haveibeenpwned.com) website.

By simply entering your email address, you can find out (for FREE) if any accounts associated with that email address have been included in a data breach, which companies were breached and when, and what information was leaked in each breach.

### Password reuse - don't do it

If your username and password for a website is leaked during a data breach, hackers may attempt to access other websites with that username/password combination, in the hopes that you have used the same password for multiple websites.

For this reason it is recommended to use unique, strong passwords for each website account you use.

[xkcd - Password Reuse](https://xkcd.com/792/)

## Password guessing/cracking

Another way hackers may attempt to gain access to your online accounts is by guessing your password from a list of commonly used passwords or by combining common words and phrases.

* Most common passwords (ref)

### Strong passwords

* [xkcd - Password Strength](https://xkcd.com/936/)

## Software security vulnerabilities

TODO

* OS
* Software
* Vulnerability
* Exploit

## Multi-factor authentication
### What is authentication

TODO

### Authentication factors

* 1st factor: something you know (password)
* 2nd factor: something you have (e.g. phone)
* 3rd factor: something you are

### Two-factor authentication

TODO

### When should I use multi-factor authentication?

Enabling multi-factor authentication for your account means that even if a hacker gains access to your email address and password combination for a website, they still shouldn't be able to access your account.

As a minimum security measure (if you do nothing else), you should enable multi-factor authentication wherever and whenever possible, **especially** for email accounts.

If someone can get access to your email account, they can potentially get access to other websites you use that use that email address, by resetting your password via the 'forgot my password' functionality. Not good!

### Two-factor authentication mobile apps

TODO

* Microsoft Authenticator
* Google Authenticator
* ...

## Use a modern web browser

TODO

### Modern web browsers

* Chrome / Chromium
* Edge (Chromium version)
* Firefox

TODO - A note about browsers on iOS (these all use iOS Safari browser engine)

### Not modern web browsers

* Internet Explorer
* Safari

## Avoid clicking links in emails/texts where possible
### About phishing

TODO

### Don't click or tap on links!

Lots of phishing emails will try and persuade you that some urgent action is required, e.g. to prevent a fraudulent payment, confirm a transaction or prevent deletion of your account.

Rather than clicking (or tapping) links from emails or text messages - even if they **look** legitimate - navigate to the website yourself, ideally using your password manager, browser favourites or Google, and log-in to the website to see if any action really is required.

Password managers can help prevent you from being tricked by phishing sites as they won't autofill your details for fake sites.

## Use a password manager

TODO

* LastPass
* 1Password
* Dashlane

## Disable your web browser's in-built password manager

TODO

* Why
* How

### Benefits of using a password manager

* Unique, strong passwords
* Uniqueness means that when one site gets hacked, anyone who gains access to that username and password won't automatically be able to access other sites that use the same combination of username and password
* Multi-factor/two-factor authentication also helps prevent you getting hacked across multiple services when one gets hacked
* Auto-fill on many sites
* Passwords available across multiple devices (e.g. laptop, desktop, phone, tablet)
* Passwords can be securely shared with family members / colleagues where appropriate.

## HTTP vs HTTPS

TODO

* What is HTTPS and why is it important?
* Why is HTTP dangerous, even on static sites like blogs?

### HTTPS Everywhere

TODO

## Ad-blockers

TODO

* uBlock Origin
* ...

## Desktop security basics

### Security features and updates

* OS updates
* Browser updates
* Enable OS firewall
* Enable OS anti-virus
* Mac/Linux firewall/anti-virus?

### Malicious software

TODO

Always be careful when downloading software from the internet. Try to only download software from reputable sources.

Hackers may attempt to trick you into downloading malicious software (viruses/trojans/ransomware/keyloggers etc).

TODO - examples:

* Sites that host downloads for software they don't own - these can show up along side genuine search results and are probably best avoided
* Fake websites that mimic their real counterparts and include software download links
* Adverts in search results for fake sites
* Torrent sites and pirated software / key-generators etc

Once malicious software is installed on your computer, it can be difficult to detect or remove (see **rootkits**) and can allow hackers to take control of your computer remotely, steal your account login details / credit card details, install 'ransomware', which prevents you from accessing files on your computer until you pay them a ransom or add your computer to a botnet.

TODO - tidy up, botnet reference.

### Mobile security basics

TODO

* OS updates
* App updates
* App permissions

## VPNs

TODO

* Who to trust? ISP vs VPN provider
* VPN + unsecured public WiFi
* Not a silver bullet for security or privacy

## References

TODO

* For a more in-depth guide on web browsing security and privacy considerations, I highly recommend [HowTo: Privacy & Security Conscious Browsing](https://gist.github.com/atcuno/3425484ac5cce5298932)
* ...