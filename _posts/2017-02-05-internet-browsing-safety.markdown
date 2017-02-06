---
layout: post
title: Safe Internet Browsing Tips
category: Tutorial
feature_text: |
  ## Browse Safely
  Take charge of your online security
excerpt: |
  Safely browsing the Internet requires a certain amount of vigilance.
---

In the movies, hackers are often depicted hunched over a glowing green screen, typing furiously as they tear down the defenses of their hapless victims. And it's true, that a hacker at a keyboard could do a lot of damage if they set their time and efforts toward it. The hard truth, though, is that the weakest link on your home computer is probably your Web browser, not some obscure backdoor.

Safely browsing the Internet requires a certain amount of vigilance. In order to land successful attacks, cyber criminals are relying on their victims' ignorance or inattention. It could be something as simple as visiting the wrong site, or clicking on a link that doesn't lead where you think it does. There are, of course, some threats that Internet users can't completely defend against, but knowing how to spot hackers' tricks will go a long way to keeping you safe.

Cyber criminals often utilize a technique called "social engineering" to trick their victims. Social engineering at its most basic is anything that convinces someone to do what the hacker wants. It could be an email that asks for your online banking credentials, a link to what looks like an interesting article, or even a phone call from someone pretending to be tech support. (As an aside, no tech support team in the world is going to cold call you to "fix errors on your computer," so if you get such a call, feel free to hang up on them.) In any case, the goal is to get you to take some action that will help the attacker to gain access to your information or your computer.

### Know where you are

The primary thing you can do to avoid many these attacks is to always know where you are on the Internet. In order to do this, though, you must understand the layout and the basic operation of your Web browser. 

All Web browsers have the same basic components. At the top of the window you will find an address bar that contains the URL (which stands for Uniform Resource Locator, in case you were curious). Below that is the content of the site you are viewing. Understanding how to read a URL is essential to knowing what site you are looking at. All addresses have some common elements. First, you can usually separate out the *domain* from the *path* to determine whether the site you are on is legitimate. The domain tells you which site you are on, while the path refers to the specific page or resource within that site you are viewing.

{% include figure.html image="/assets/safe-browsing/address_bar.PNG" caption="The address bar can usually be found at the top of your browser's window." position="block" %}

Don't be fooled by tricky subdomains. They might make it look like you're where you want to be, when in fact you're somewhere else entirely. To identify the actual domain, find the highest level domain and work backwards. This will likely be .com, .org, .biz, or something similar. Work backwards from that *top level domain* (TLD) and you'll find the name of the actual *domain* you are looking at. Keep going to the left, and you'll see the *subdomain*, if the address has one. 

{% include figure.html image="/assets/safe-browsing/address_bar_diagram.png" caption="The URL consists of a protocol (usually HTTP or HTTPS), subdomains, a domain, and a top level domain." position="left" %}

For example, if you think you're on a Google Website, you should see google.com as the domain. A malicious site may try and trick you with something like google-com.**malicious-site.com**. Don't be fooled by the word "google" in the subdomain there -- the actual domain you are at is malicious-site.com.

Being aware of this one thing will save you from many of the common attack patterns criminals use. Before you do anything sensitive on a Web site, such as enter your username and password to log in or enter your credit card number, make sure you are on the site you think you are by checking the address bar.

### Know where you're going

The next thing to be aware of is where links will take you once you click on them. This is similar to checking the address bar to see what domain you are on; you're going to look at the domain of the URL in the link. In many cases, the link itself will be the address it links to, but you can't necessarily trust that as the text or image displayed for the link can be anything the site designer wishes it to be. Don't worry, though, because there are a few ways to tell the actual destination of a link. 

The simplest might be just hovering your mouse curser over the link. In some browsers, the target URL of the link will appear over your curser after a couple of seconds, or at the bottom of the window. 

{% include figure.html image="/assets/safe-browsing/url_address_hover.PNG" caption="In most modern browsers, the target URL for a link will appear in the bottom left corner of your browser when you hover over a link." position="block" %}

This isn't an option on mobile devices, though, so sometimes you'll need to use another method to view the target link. One quick and easy way to view it is to copy the link location by right-clicking on the link, selecting the option to copy the link location, and then pasting it into a word processor. On mobile devices, you can usually do the same thing by pressing and holding on the link for a few seconds.

{% include figure.html image="/assets/safe-browsing/saving_url_location.PNG" caption="You can right-click on a link to copy its location." position="block" %}

{% include figure.html image="/assets/safe-browsing/pasted_url.PNG" caption="You can then past the copied URL to a word processor such as Notepad." position="block" %}

Or, you can look at the page source code directly by right clicking on the link and selecting "Inspect Element." This will open a window showing the source code for the link you selected. Look for "href=". The target address for the link will be inside quotation marks just after that.

{% include figure.html image="/assets/safe-browsing/inspecting_element.PNG" caption="Again, right-clicking brings up the menu to inspect the link." position="block" %}

{% include figure.html image="/assets/safe-browsing/showing_inspected_element.PNG" caption="A quick peek at the site's source code will show you the link's target." position="block" %}

If the link is pointing to the location you intend to go, you're free to click on it! But, if it leads to a site you weren't expecting or don't trust, you will probably want to avoid it.

### Stay Vigilant

By using these techniques, you will avoid falling victim to some of the more dangerous sites out there. It may take some practice to get into the habit of always checking where you are and where you're going while browsing the Internet, but doing so is essential for safe Web surfing. Stay vigilant, and happy browsing!
