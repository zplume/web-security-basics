# Web browsing security basics

## About

**This article provides some basic tips on how to reduce the risk of being hacked while using the internet.**

This article is not intended to be an exhaustive list of risks and mitigations, but to give an introduction to the topic and cover some tools/techniques for avoiding the most common risks. Links to more comprehensive resources will be included where relevant for those who want to dig deeper.

This article does not go into detail on the topic of **privacy** as this is a big topic and it deserves proper explanation, which is beyond the scope of this article. See the resources at the end of the article for information on this topic.

This article does not go into great detail on device security (another big topic, given the range of devices and operating systems), but some high-level tips are included.

## Why should I care

TODO
* Explain context, risks
* Reference haveibeenpwned.com

## Multi-factor authentication / two-factor authentication

### What is multi-factor / two-factor authentication?

* 1st factor: password (something you know)
* 2nd factor: phone (something you have)
* Additional factors: ?

### When should I use multi-factor or two-factor authentication?

Enabling two-factor or multi-factor authentication for your account means that even if a hacker gains access to your email address and password for a website, they shouldn't be able to access your account.

As a minimum security measure (if you do nothing else), you should enable two-factor/multi-factor authentication wherever and whenever possible, **especially** for email accounts.

If someone can get access to your email account, they can potentially get access to other websites you use that use that email address, by resetting your password via the 'forgot my password' functionality. Not good!

### Two-factor authentication mobile apps

* Microsoft Authenticator
* Google Authenticator
* TODO

## Use a modern web browser and update it as soon as updates are available

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

* LastPass
* 1Password
* TODO

## Disable in-built browser password manager

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

* uBlock Origin
* TODO


## Device security basics

TODO

Be careful about which software you download and install.

### Desktop

* Firewall
* Anti-virus

### Mobile

* DNS / VPN apps

## References

* [HowTo: Privacy & Security Conscious Browsing](https://gist.github.com/atcuno/3425484ac5cce5298932)
* TODO