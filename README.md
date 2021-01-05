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

## Common risks

* Data breaches
* Common, weak or reused passwords
* Phishing
* Software security vulnerabilities

Read on for more information each of these risks and for techniques to avoid them.

## Data breaches
### What is a data breach?

A data breach occurs when private/confidential data is leaked or stolen from a company's computer systems and copied or transmitted elsewhere, enabling others to access it who would otherwise be unauthorised to do so.

### What data can be leaked during a breach?

The type of data that is leaked in a breach depends on the nature of the breach, what data the associated systems contained and how effectively those systems were secured.

For example, the following types of information may be included in a breach:

* Your username and password for the website
* Credit card / payment details (if these were collected and stored by the website)
* Personal / sensitive data (if this was collected and stored by the website)

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

### How can I find out if my account(s) were included in a data breach?

Check out Troy Hunt's [Have I Been Pwned](https://haveibeenpwned.com) website.

By simply entering your email address, you can find out (for FREE) if any accounts associated with that email address have been included in a data breach, which companies were breached and when, and what information was leaked in each breach.

### What to do if your account(s) are included in a breach

* Change your password on the affected accounts - use a strong, unique password for each account.
* If the affected account(s) used a password that you also used on other websites, make sure to change your password on each of those websites to a unique, strong password.
* Enable multi-factor authentication on the affected accounts.
* If the breach may have contained credit card / payment information, keep an eye on your financial accounts for transactions you did not make and consider contacting your bank's fraud department.

See below for more details on using strong, unique passwords and multi-factor authentication.

## Passwords

Hackers may attempt to gain access to your online accounts by trying commonly used passwords, trying passwords retrieved from a data breach or by 'brute force': trying many possible passwords by randomly combining letters, numbers and special characters.

### Password tips

To make your passwords more secure:

* Don't use [simple or common passwords](https://nordpass.com/most-common-passwords-list/) that are easy to guess
* Don't use the same password on multiple websites
* Create a strong, unique password for each website account you use

A strong password is long and hard to guess.
One technique for creating hard to guess passwords is to use a mix of letters (upper and lower case), numbers and other characters.

### Don't use the same password on multiple websites

If your username/email and password for a website is leaked during a data breach, hackers may attempt to access other websites with that username/password combination, in the hopes that you have used the same password there too.

Use a unique password for each website to avoid this risk.

### Use a password manager

To create a strong, unique password for each website you use, it is recommended to use a password manager. 

Password managers help you generate strong, unique passwords for each website you use and keep a record of each of your passwords so you don't have to remember them yourself.

Other useful features of password managers include:

* Auto-fill of your username and password on websites you have used previously when you need to login
* Passwords available across multiple devices (e.g. laptop, desktop, phone, tablet)
* Passwords can be securely shared with family members / colleagues if appropriate.

Here are some popular password managers:

* [LastPass](https://www.lastpass.com/)
* [1Password](https://1password.com/)
* [Dashlane](https://www.dashlane.com/)

### Disable your web browser's in-built password manager

TODO

* Why
* How

## Phishing

TODO

### Avoid clicking links in emails/texts where possible

Lots of phishing emails will try and persuade you that some urgent action is required, e.g. to prevent a fraudulent payment, confirm a transaction or prevent deletion of your account.

Rather than clicking (or tapping) links from emails or text messages - even if they **look** legitimate - navigate to the website yourself, ideally using your password manager, browser favourites or Google, and log-in to the website to see if any action really is required.

Password managers can help prevent you from being tricked by phishing sites as they won't autofill your details for fake sites.

### Social engineering

TODO

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

### Malicious software (malware)

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

### Security features and updates

* Enable automatic updates for your computer's operating system
* Update your web browser as soon as updates are available

#### Windows

* Enable Windows Firewall
* Enable Microsoft Defender Anti-Virus

#### MacOS (Apple)

**Application firewall**

Enable [application firewall](https://support.apple.com/en-gb/HT201642)
* Security & Privacy > Firewall
* Click the lock to make changes
* Enter your mac password
* Firewall Options
* Untick **Automatically allow...** options
* Tick **Enable stealth mode**
* Consider enabling **Block all incoming connections**.
* Alternatively, remove or set to **Block incoming connections** any listed applications that do not require incoming connections

**Anti-virus**

While MacOS does include some great features to prevent installation or execution of malware (e.g. Gatekeeper, XProtect) you may also want to use a 3rd party anti-virus application to catch anything that could bypass the MacOS security features.

[The best Mac antivirus for 2020](https://www.macworld.co.uk/feature/mac-antivirus-3672182/)

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