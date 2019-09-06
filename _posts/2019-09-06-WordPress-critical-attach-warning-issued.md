—-
layout: post
title: Critical WordPress backdrop warning issued
—-
A [warning has been posted by WordFence](https://www.wordfence.com/blog/2019/08/ongoing-malvertising-campaign-continues-exploiting-new-vulnerabilities/) regarding attacks targeted at WordPress websites. 

## The details
In the short version, plugins always need to be maintained. If they’re out of date, they can be extreamly vulnerable. I’be repaired countless sites, and am currently working to bring up a new site that has outdated plugin. 

In this case, the attacks have been utilizing vulnerables in plugins to inject code and create new administrator accounts. Once they have an administrator account, they can gain full control of your site and it’s content. 

## What should you do
Ensure all of your plugins and WordPress core are the latest version. Contact your web developer if you don’t know how to do this or if you’re not sure. 
Check for new user accounts you’re not familiar with. There shouldn’t be any new user accounts and this script is known to create usernames such `wpservices`.

WordFence noted that the attacks mostly originate from a specific IP address, 104.130.139.134. You may choose to block this IP via firewall rules, if you so choose. I don’t see it having many negative affects as the IP is a server IP and not client IP addresses. I’m sure soon the host of that IP will be investigating, however, I wouldn’t count on this being a full proof plan as the attack can be launched from near any IP address.

## Prevention is key
Keep you’re site updated, keep your plugins updated. If you’ve got a site that never really changes, maybe it’s time to go to a static site. If you’re just in need of a basic blog, maybe a static site generator, like Jekyll. 

I’m not anti-WordPress, in fact, I think it’s an amazing platform but sometimes, it’s really not needed. I also operate a multi-site server with a group of like minded business owners. I help them have a server that’s fast, reliable, and secure. I also maintain their website’s WordPress installation with updates and ensure it’s security. The biggest danger to any computer security is it’s administrators. Limit the plugins you use, not just for security but also for speed. We don’t allow any installation of plugins, unless they are known to be safe. That said, sometimes things come up, which is why backups are always important to.


