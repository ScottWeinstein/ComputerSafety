---
layout: post
title: Good password management
tags: [DataSafety Security]
last_updated: 2011-12-21
---

### Passwords
Everyone hates them, but for moment, the're what we use to keep our data secure. It's not uncommon to need passwords for well over 20 different sites and accounts. The first step towards good password management is to categorize the sites you use into two categories: **important** and **unimportant**.

The list of important accounts should be short

* your email
* your bank
* brokerage
* possibly facebook (as facebook is being used as sign-in portal for many other sites)

###### 
Passwords for **important** sites must be both strong and unique to each site. Passwords for **unimportant** sites can be relativly weak.


## Examples
Passwords such as `f!rstBorn432` are not very secure and can be cracked relativly quickly.


On the other hand, passwords such as `aae34437edf138d7708fef0b7616e4230dc712ff0ff4af6d9ccac377c3cdf3d7` are quite secure - not only are they hard for computers to crack, 
they are impossible for people to guess, and only rain-man types could even think of memorizing it. Don't worry, you'll never have to _memorize_ or _type_ this kind of password.


## Call to action
1. Use a password manager to store your important passwords.
1. Create secure passwords and change the passwords on your important accounts

### Password manager
I use [KeePass](http://keepass.info/index.html) - it's free, popular, and been around for a while. (here are some other [desktop](http://lifehacker.com/5529133/five-best-password-managers) and [web](http://www.passpack.com/en/professional-password-manager/) based managers)

* Install the software and choose a good passphrase (mine is a 5 word phase of about 40 chars) to protect the KeePass database that is created.
  * A good passphrase could be a sentence (with spaces) and substitute some letters for special characters or the first letters of the words of a long sentence.
  * At minimum it should be over 25 characters and contain upper and lower case, numbers and non-alphanumeric characters.
* Before continuing, familiarize yourself with the use KeePass. This is **important**, as if you loose any of the password database, the keyfile, or forget your passphase you are well fucked.
* Allow KeePass to generate unique and long passwords for each one of your **important** site accounts.
* you'll never have to remember all those passwords ever again - just the one KeePass passphrase

## Typical process using KeePass
1. Open KeePass (enter your passphrase to access the KeePass database)
1. Copy the appropriate long, complex, KeePass-generated password and
1. Paste it into the important site login field. ().


#### Optional
I keep my KeePass password database on [Dropbox](http://db.tt/PnMCV7X), so that it's kept in sync between my work laptop and my home PC. But to make this secure I also use a **key file** in adition to a passphrase. This additional security feature means that to open the KeyPass database, both my master password, **and** the keyfile must be used. To transfter the key file I copy (just once) via USB thumb drive to the two computers (using DropBox or email could render the additional security of the keyfile moot)
