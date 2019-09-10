# Personal hosts files for Samsung Knox-based ad blockers.

## Hosts aggregator script
 * This script aggregates the following hosts files , processes them into a Samsung Knox friendly format, and removes any duplicate and redundant hosts.
   - AdHell original package
   - [Dan Pollock aka someonewhocares](http://someonewhocares.org/hosts/)
   - [Peter Lowe](https://pgl.yoyo.org/as/serverlist.php?showintro=0;hostformat=hosts)
   - [Bjorn Stormberg](https://github.com/bjornstar/hosts)
   - [StevenBlack's ad-hoc list](https://github.com/StevenBlack/hosts)
   - [AdGuard Simplified domain names filter](https://kb.adguard.com/en/general/adguard-ad-filters#domains)
   - [AdGuard Mobile ads filter](https://kb.adguard.com/en/general/adguard-ad-filters#mobile)
   - [Malware Domain List](http://www.malwaredomainlist.com/hostslist/hosts.txt)
   - [hoshsadiq's adblock-nocoin-list](https://github.com/hoshsadiq/adblock-nocoin-list)
   - [280blocker](https://280blocker.net/files/280blocker_domain.txt)
   - [MobileAdTrackers](https://raw.githubusercontent.com/jawz101/MobileAdTrackers/master/hosts)
   - and more...
 * This is a modified version of [mmotti's script](https://github.com/mmotti/mmotti-host-file).

## Main lists
* Link: https://raw.githubusercontent.com/CitizenXVIL/Hosts/master/Optimized_hosts_list.txt
   - Ran hosts_aggregator script to create custom, personal hosts list.
   - There may be false positives. Testing is limited to apps and webpages I browse regularly.
   - Short link: https://bit.ly/2s5KMxC

## Add-on Lists
* Link: https://raw.githubusercontent.com/CitizenXVIL/Hosts/master/Youtube%20hosts.txt
   - Experimental list to attempt to block YouTube video ads. This is based on information from Pi-Hole discussion boards about YouTube ad blocking. This is highly unlikely to work because YouTube uses continuously changing subdomains, and blocking all the subdomains can affect mobile playbcack.
   - Short link: https://bit.ly/2KvfXKS

* Link: https://raw.githubusercontent.com/CitizenXVIL/Hosts/master/mobile%20domains.txt
   - Mobile ad/tracker list based on AdGuard's mobile ad filter.
   - This list is automatically processed and generated by a script.
   - Short link: https://bit.ly/2w2ac4j
