---
layout: post
title: A WiFi overhaul
---

A friend of mine recently asked me how he can get better WiFi. I can understand it's probably pretty difficult for some to understand the idea of how WiFi in fact works. This article will hopefully help him and you make some educated decisions on how to best accomplish your goals, mainly, good WiFi coverage and speed in your home.

==WiFi basics==
WiFi basics are essential to this topic. There are a few different hardware items required for WiFi to work properly and we'll explain what each is. Before, we go down that rabbit hole, first here are the basics of how WiFi works.

WiFi is basically a radio. Many people forget this when they get into security configurations or dense neighborhoods. WiFi is a radio and it's a radio signal. Radio signals are affected by a lot of different things. Interference from objects, other devices, or just distance.

==Devices==

There are several devices that go into a Wireless network. Most home users are accustomed to just 1 box provided by their ISP. If you've ever heard the term Jack of all trades, you'll know the second line to that is master of none. In many cases your ISP provided modem our router as they may call it, is not particularly good at any one thing. Today we'll be breaking this equipment up into dedicated devices for each purpose, improving speed, reliability, and even lower costs. Yes, that's right, you can lower costs by rolling your own WiFi at home. There are upfront costs to contend with, but, some ISPs charge up to $12 a month for that modem you rent. It doesn't work very well at anything but cost you $144 a year! Depending on the size of your home you can get everything you need for $158. Pays for itself in less than a year!

===Modem===
Generally internet is fed to your home via a coaxial cable. Take note that even fiber delivery is delivered to homes this way. For instance, in my areas, fiber is delivered to the neighborhood and coax is used from there to the house. From there it can sometimes be delivered to an outside box called an ONT. The ONT is managed by the company providing your internet access and generally you don't need to do anything in or with this box. You do however need the ONT, if your ISP provides it. If not, your internet will be fed directly to a modem.

A modem is a device that converts data for transmission from one medium to another. In our case that's ethernet to coaxial cable. In general that single box you get from your provider has a modem, router, switch, and access point, all in one. Again, these devices don't really do any one thing very well. You can in fact purchase a modem for use with most cable providers, but since there are several, I won't mention any makes or models, just know that you can buy one separately. With fios, the ONT actually has an ethernet port and a quick call to customer service gets this turned on.

I will say this, be sure you're prepared before you make that call and expect a little pushback. They're really not interested in you giving up their modem, be nice and you'll usually get what you want.

In my friend's case, and mine, we have fios and don't actually need the modem. So in our case, we'll skip to the next deivice, if you have cable though, you'll need to work out a modem for your service provider.

A quick note with cable providers and modems. In many cases your phone and internet packages now use the same boxes. There are some weird rules around this and you might be stuck with their box, check for your provider but be warned it'll be a challenge to get them to help you at all.

===Router===
A router's purpose is to route traffic from one network, like our home network, to another like the internet. Again, the devices provided by cable and phone providers that offer internet are not very good. A very important function of a router is a firewall. The firewall's job is to prevent access to the network, except for authorized traffic. Known threats exist and have existed for many years for these routers provided by the larger ISPs. They probably won't fix them anytime soon, if at all.

===Access Point===
The access point is the radio that gives us WiFi. Packing in a radio with all of the above and putting it under your desk doesn't give us a very good signal and that should be expected. The security of these devices is also pretty bad. Some ISPs are now turning these into hotspots. So you're paying for the equipment, the power, and the service and they're offering it up to other users via a hotspot. You'll be able to see this when you go to a friends house and can login to their WiFi without asking them for the password.

==The plan==
My friend has I'd say about a moderately sized home. Probably larger than most suburban homes, but by no means a mansion. The truth is, I spec'd this out for him and believed he might be able to pull it off with one access point, but we're working with an addition, and most of his access is spread from one end of the building to the other.

What we're going to do is get our dedicated router setup for internet access, get our access point in a high place for good coverage, and create a good grid of the home with a little overlap.

==The hardware==

Okay, here come the affiliate links. If you're going this route, here is what I purchased, feel free to use this links. It helps me out a bit, but doesn't cost you a penny.













So this site is up! That really didn't take long. Before going any further I really must tell you, if you don't know, this site is hosted by Github. No sponsorship or anything, they actually provide a way for you to build a blog using a static site generator called [Jekyll](https://jekyllrb.com/). and yes it is Free, not sort of free, actually free.

Just a bit more about Jekyll. Jekyll is a static site generator. Getting into the details is for another post but suffice to say it allows you to make or more importantly support a blog without any specific CMS crazy hosting environment built for NASA (talking about you WordPress). Don't get me wrong, I love WordPress but for a lot of things, it really is like taking a Boeing 777 to the grocery store, it's just overkill. Again, details in a later post. It's really easy to get setup, checkout [Github Pages Here](https://pages.github.com/) for more info, we'll do a post on that in the future. Oh, [checkout this handy markdown cheat sheet too!](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

So I'm up and running! Part of me feels like I've met my quota for the day with the above, but that'd be pretty boring for anyone out there so here is a brief intro to what I'm up to.

I finally bought an Arduino! Better late than never, I guess. I'm still making the LED blink for fun but I'm really looking forward to a project I have coming up soon to put the Arduino to work, I've got a bit of reading to do before I get into that though.

The Arduino sparked another idea but never really stayed with the Arduino. I've always wanted one of those whole home audio system, where you can listen to music in pretty much any room of the house, but I didn't wanted to be limited to just one audio source. I'd like to be able to pipe all sorts of different things into it. Of most interest was being able to have multiple different sources going to different zones/rooms all at once. So my wife could be listening to one thing in one room and me another. Ditto to my daughter. Anyway, I was thinking of using the Arduino as a controlling mechanism but later settled on a different path. The Arduino might still be used for some I/O though going forward. Still working out the cracks and pops as I just got the speakers in today.

In coding I'm really trying to sit down and solidly learn a language for  once. I took to PHP years ago but never stuck with it. I learned enough and was able to do some cool stuff but got away from it and now I'm back looking for more. I think Python will be the next one I learn. I've got way too many project ideas and think Pyhton might be good for them there.

In Radio, I haven't done much aside from get a 40 meter dipole in the air, FINALLY. I've only been in our new home since March. And I managed to get a Arrow J Pole on the chimney at the same time, but I haven't even transmitted from it yet... that was like 3 weeks ago too.

For SDR, I've actually just started playing with ADSB again. I lived in an apartment that felt like it was in an RF hole for several years before buying our home so I might be running a little crazy with the projects now that I've got room to do what I want. Right now I'm just playing around with SDR and looking into building another antenna and maybe picking up a different SDR receiver here soon.

Well, that turned into a crazy list. We'll see how far along I get. I think I might make it a point to start posting these ideas/brainstorms going forward and see how far down the list I might get.

Hopefully you're not completely bored by this point and look forward to seeing you all when the next one comes out!
