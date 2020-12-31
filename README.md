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
* Hackers gain access to your private personal/business data
* Hackers gain access to accounts with saved credit card details and purchase goods using those accounts / details

## Data breaches
### What is a data breach?

TODO 

### What happens after a data breach?

TODO

* User account details, such as login information, personal private data and credit card information can be purchased or downloaded from the 'dark web'...
* Hackers may attempt access to other websites using username/password combinations they've gained access to from the data breach, or they may cross-reference that information with information on the same user from other data breaches - perhaps to build a list of known passwords for that email address against common websites, or just to combine data from multiple websites to be used in identity theft.

### Why is reusing the same password on multiple websites a bad idea

TODO

* Breach + reused user/password combination = hackers gaining access to your account for other websites that weren't breached.
* [xkcd - Password Reuse](https://xkcd.com/792/)

### Which companies are at risk of data breach?

TODO

* Examples
* Even websites run by large brands with large budgets) are at risk of data breaches.

### Have my details been exposed by a breach?

TODO

* Reference haveibeenpwned.com

### Password strength and password cracking

TODO

* Most common passwords (ref)
* [xkcd - Password Strength](https://xkcd.com/936/)

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

## Use a modern web browser and update it as soon as updates are available

TODO

* Chrome
* Edge (Chrome based version)
* Firefox

## Avoid clicking links in emails/texts where possible
### About phishing

TODO

### Don't click or tap on links!

Lots of phishing emails will try and persuade you that some urgent action is required, e.g. to prevent a fraudulent payment, confirm a transaction or prevent deletion of your account.

Rather than clicking (or tapping) links from emails or text messages - even if they **look** legitimate - navigate to the website yourself, ideally using your password manager, browser favourites or Google, and log-in to the website to see if any action really is required.

Password managers can help you being tricked by phishing sites as they won't autofill your details for the fake site.

## Use a password manager

TODO

* LastPass
* 1Password
* ...

## Disable your web browser's in-built password manager

TODO

### Benefits of using a password manager

* Unique, strong passwords
* Uniqueness means that when one site gets hacked, anyone who gains access to that username and password won't automatically be able to access other sites that use the same combination of username and password
* Multi-factor/two-factor authentication also helps prevent you getting hacked across multiple services when one gets hacked
* Auto-fill on many sites
* Passwords available across multiple devices (e.g. laptop, desktop, phone, tablet)
* Passwords can be securely shared with family members / colleagues where appropriate.

## HTTP vs HTTPS
TODO


## HTTPS Everywhere
TODO

## Ad-blockers

TODO

* uBlock Origin
* ...

## Device security basics

TODO

* Be careful about which software you download and install and especially **where** you download it from.
* ...

### Desktop

TODO

* Browser updates
* OS updates
* Firewall
* Anti-virus

### Mobile

TODO

* App updates
* OS updates
* DNS / VPN apps

## References

TODO

* [HowTo: Privacy & Security Conscious Browsing](https://gist.github.com/atcuno/3425484ac5cce5298932)
* ...