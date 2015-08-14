NSABlocklist© file original created under the MITM license 2015 by CHEF-KOCH.


Description:
------------
This isn't yet another [hosts file](https://en.wikipedia.org/wiki/Hosts_(file)) or [DNSBL](https://en.wikipedia.org/wiki/DNSBL) that claims to secure the web, it's specially designed to _stop_ known NSA / GCHQ / C.I.A. or F.B.I. servers from beeing connecting to you without permission. The list is not designed to block common malware, spyware or anything that is already avaible on the net via a proper designed hosts for such case. This hosts or the super ranges lists could block some of your sites/servers you may need, so you'll be warned!


My list is original based on 2007 published Wikileaks documents and includes my own modifications.


This project includes
------------
* An '[HOSTS.txt](https://github.com/CHEF-KOCH/NSABlocklist/blob/master/HOSTS.txt)' file that includes all Servers/DNS domains that are known to be NSA or GCHQ involved. The confirmation is given on the _Research_ link at the bottom.
* An '[Super Ranges.txt](https://github.com/CHEF-KOCH/NSABlocklist/blob/master/Super%20Ranges.txt)' file which includes a list of known IP ranges that are compromised (be careful with that!).
* An '[LICENSE](https://github.com/CHEF-KOCH/NSABlocklist/blob/master/LICENSE)' File to shows the MITM license.
* The '[README](https://github.com/CHEF-KOCH/NSABlocklist/blob/master/README.md)' (this) file that includes the latest news, updates and explanations,...
* An '[problematic.txt](https://github.com/CHEF-KOCH/NSABlocklist/blob/master/problematic.txt)' file wich includes DNS/PTRs that are possible problematic for you. 


Important Notice
------------
* A true list of compromised IPs would list the entire Internet, then on to the fuller range open mouth blabbering of blogs, email, chat rooms, texting, aided and abetted by the world's telecoms, postal services, and, most reliably, bedroom  murmurings.
* I do not accept donations, I'm not doing this because I want $$money or hype I'm doing this because I didn't found a proper list on the whole internet and of course I want to share my knowledge for free. I always think that such information should be available for everyone on the world.


Do you hate the NSA or other agencies?
------------
* I do not _hate_ the NSA or other agencies but I really don't like that everyone is automatically under the microscope and of course that there is no opt-out or transparency excpect lies and more lies (and some excuses ...yeah, we are doing this because terrorism, go f$ck yourself with such statements!)
* Everyone have something to hide, passwords, privat data, accounts, ....


Known problems hosts file can't fix
------------
* An hosts file is no guarantee, if the NSA is already in your system it's already to late.
* HOSTS files are no guarantee that the NSA or any other attacker/organization could simply bypass it via 0day or other vulnerabilitys on your system/router.
* HOSTS files can't protect against attacks directly on/in the hardware, e.g. if the router is already compromised or comes with backdoors this list will be easily bypassed anyway.
* Due the complex of the entire file I can't explain every single IP or PTR record.
* The hosts file may present an attack vector for malicious software because the file could be modified to redirect the entire traffic e.g. adware or trojans can do this. Ensure that the file was marked as read-only and you're not logged in as adminstrator. 


ToDo:
------------

- [ ] Fix Readme.md, typos, grammar,...
  - [ ] Maybe sort the hosts list alphabetically
  - [ ] Maybe add an seperate hosts file for MS, Apple, Google (if someone ask for it) 
  - [ ] Maybe monthly updates?
- [ ] Find invalid entries or domains that aren't online anymore (high-prio)
- [ ] Fix/merge all reported [issues](https://github.com/CHEF-KOCH/NSABlocklist/issues)
    - [ ] Add explanation how to identify compromised domains/DNS
	- [ ] Add solutions to e.g. secure DNS via DNSCrypt/DANE


Project History
------------

- [x] 14.08.2015 initial upload of the entire project and small Readme.md corrections



Research
------------

* [Cryptome](http://cryptome.info/0001/ip-tla.htm)
* [33bits](http://33bits.org/)
* [Randomtalker web-privacy](http://randomwalker.info/web-privacy/)
* [Free Haven's Selected Papers in Anonymity](http://freehaven.net/anonbib/)
* [NSA Spying | Electronic Frontier Foundation](https://www.eff.org/de/nsa-spying)
* [Mobile Security Wiki | mobilesecuritywiki.com](https://mobilesecuritywiki.com/)
* [Researcher at Kaspersky Labs have discovered a list of domains used by the NSA to install malware on victim's PC around the world.](https://www.hackread.com/here-is-a-list-of-urls-used-by-the-nsa-to-install-malware-on-pcs-worldwide/)
* [NSA PRISM Keywords For Domestic Spying - Business Insider](http://www.businessinsider.com/nsa-prism-keywords-for-domestic-spying-2013-6?IR=T)
* [Hardened user.js for Firefox to stop data leackage](https://github.com/pyllyukko/user.js)


**Thanks goes to everyone which fights for www security! Give spying no chance!**
