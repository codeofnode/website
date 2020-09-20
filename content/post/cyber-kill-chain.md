+++
author = "Ramesh Kumar"
title = "Using cyber kill chain to build strategy for cyber security"
date = "2020-06-25"
description = "This will help simplify the strategy for cyber security practices."
tags = [
    "cybersecurity",
    "killchain",
]
+++

*Enforcing security is open ended, and hence very difficult* .. This is what I usually hear.  

But we all know security is not something which we have recently started enforcing, it has been there from times of wars. How would they have planned for the same?

The strategy and hence the enforcing pattern becomes very clear, when we think from attackers point of view.

Here are the five stages an attacker plans to breach a protected area.

1. Finding weak points:  
Finding open ports on a machine, or finding the email address of an employee.

2. Gaining access:  
Use of social engineering toolkit to get access to credentials, or using metasploit to find vulnerability in a machine.

3. Internal movement access:  
Now after getting access, the attacker will try to get access to other machines of protected premises, via eg remotely logging in.

4. Setting up backdoor in internal systems:  
Now that attacker is able to access internal machines, they would like to setup a direct and silent access (backdoor) to these compromised internal assets

5. Taking actions:  
Here is when an attacker will try to steal something or do some harm.


#### The solution
If we counter protect each layer then, can’t we say security is enforced?

1. Educate and use firewalls:  
Educate employees not to disclose their information. Blocking unused ports. And also setting up honeypots and firewalls after that.

2. Extra layer of authentication:  
Use MFA, or security keys. Define source IPs or org managed systems for further access into protected premises.

3. Apply Network ACLs:  
Use subnetting, routing rules. Authenticated one should access only a specific minimal part of premises.

4. Microsegmentation:  
Protect east west movement and other similar mechanisms like instance whitelisting to ensure who can access what even within premises. In nutshell, enforce, zero trust.

5. Authorization and Encryption:  
Enforce Resource based and Role based access controls for least privileged access to various assets. Data encryption (in rest and in fly) is a must to enforce. Monitoring and detecting anomalies is a good add on.


If you want to get more clarity, please [google kill chain](https://www.google.com/search?q=kill+chain) that has been used in historical wars. Some says its 7 stages, but i thought to make it 5 to make it more generic. It doesn't really matter.

Thank you.
