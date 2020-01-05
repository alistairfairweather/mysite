---
title: Why FNB's new password policy makes its customers less, not more, secure
date: 2019-08-19T12:30:05+00:00
author: Alistair Fairweather
layout: post
permalink: /2019-08-19-why-FNBs-new-password-policy-makes-its-customers-less-secure
categories:
  - Technology
---

This morning FNB customers around South Africa woke up to a huge inconvenience: the online banking system now requires you to manually type your password into the field. If this doesn't sound like a big deal, it's worth learning about a whole generation of users who rely on password managers to securely store, update and auto-fill their passwords.

Technology and knowledge workers (including me) will often have dozens or hundreds of different accounts with different combinations of usernames, email addresses, passwords and second-factor systems (also known as OTPs). Managing account credentials manually quickly leads to huge headaches such as getting locked out of vital systems (sometimes permanently). Try explaining to a client that you have permanently locked the Gmail account that owns their website's sales data. 

The only way to stay sane in this environment is to use a password manager. I use 1Password (one of the best pieces of software I've ever owned), but there are plenty of others - LastPass is also excellent, and there at least a dozen others (some free, some paid).

But these password managers also have a second important function: they make passwords more secure because they remove the need to remember them. My passwords are typically 30 - 40 characters long with an eye-watering assortment of symbols, digits and letters. They are generated automatically (and randomly) by my password manager. 

As such I literally don't know any of my important passwords - they are too long and complex. I have outsourced that function to a piece of software that is much better at handling this task than me. Literally the only password I have to remember is the one that gives me access to my password manager (hence the name "1Password"). 

So, by essentially forbidding me to paste my own password into my own browser, FNB has forced me to make a ridiculous choice: either stop using internet banking (not happening) or change my password to something I can actually remember and type out (in other words something much less secure). And never mind the fact that my password manager is a password protected, military-grade encrypted vault which is arguably more secure than most of FNB's own servers.

If this sounds like whining from a tiny minority of tech geeks, you're missing the bigger picture. Many, many people store their passwords in less sophisticated digital forms like Word documents or online notes. Many also use a browser that stores their passwords for them. FNB's site has long blocked that auto-fill feature but the implementation depends on browsers, so there are probably tens of thousands of users who unconsciously rely on one of these rudimentary password managers.

It's these people that FNB is concerned about. If someone were to steal the laptop of such a user, the logic goes, they would have de-facto access to their online banking account.

However, FNB's solution will actually make this problem worse not better. This is not a matter for debate - far smarter people than me [have shown](https://xkcd.com/936/) that these kinds of passwords are orders of magnitude easier to crack (i.e. to guess using brute computational force) than the kinds of passwords that a password manager will produce. 

So, by forcing all users to manually type in their passwords, FNB is achieving three unintended things:

1. They are reducing the average complexity of passwords for their entire customer base
2. They are ensuring that more people will store their passwords in insecure formats - including writing them down, or storing them on the desktop of their computer. 
3. They are dramatically increasing password churn and password reset requests via their systems. This will create more noise in their system and make it harder to distinguish between valid and fake reset requests. 

The community managers running [@Rbjacobs](https://twitter.com/Rbjacobs/status/1163373881564049408?s=20) are doing their best to explain and molify grumpy users. The party line, it seems, is that storing your passwords on a device is inherently insecure and remembering your password is better.

There are two big problems with that argument: firstly, stopping people from copying and pasting won't stop them storing their passwords on a device. If your passwords are all in a text note called "Passwords.txt" then all this change is going to do is make your life slightly more annoying. You're not going to change your behaviour. People are bad at remembering passwords, so they record them. Blocking the copy-and-paste feature won't make people better at remembering their passwords! That's just not how humans work.

Secondly, any significant changes to your FNB bank account require a form of second factor authentication - typically this is via an SMS or a notification via the app. So in order to do anything, including changing a password, you need access to both a phone and a computer. I respectfully submit that, if a thief has access to both your laptop and your phone, you're in pretty big trouble and copying and pasting is the least of your problems.

There's another, deeper, issue with this approach. Hackers have now stolen (and distributed) literally billions of user passwords in multiple high-profile attacks and leaks from the likes of Yahoo and LinkedIn. If you think your own passwords are safe, [check your email address](https://haveibeenpwned.com/) at HaveIBeenPwned. Odds are that your details have leaked somewhere at some point.

Apart from the obvious problem of a hacker using one of these lists to guess your specific personal password, these huge databases have done something much more frightening - they have taught hackers what human-generated passwords look like. Or, more specifically, they have provided billions of data points that hackers can use to train their artificial intelligence systems to make them better at guessing passwords. This can make guessing a password - a job that would normally take a computer (literally) thousands or even millions of years to do randomly - into a ten minute job. 

The answer to the above problem is actually pretty simple: use a password manager with long, highly random passwords, together with two-factor authentication. Until today FNB did a brilliant job of supporting that method. Today's change is a big step backward. 

I recognise that this change comes out of a genuine concern for the safety of customers' accounts. This isn't some arrogant corporate dictatorship - this is obviously the recommendation of a well-meaning security team. But the problem with every corporate security team I've ever encountered is, ironically, they don't understand how to change people's behaviour. 

They rely, instead, on brute force. Anyone who works at a bank has suffered from their maddening password policies - "[All passwords must now include gang signs and squirrel noises](https://dilbert.com/strip/2005-09-10)". But while that approach may scale inside a corporation where you pay everyone's salaries, it's not going to wash with customers. 

Something that's maybe not clear from my rantings above: I love my bank. FNB is one of the most innovative and forward-thinking banks in the world. I am proud to be a customer and I have been delighted by FNB's service many, many times. This polemic comes out of a place of love. So, FNB, we implore you, don't be kak, be lekker. 



