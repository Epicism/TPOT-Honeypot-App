The T-Pot Honeypot is a virtual machine with multiple Honeypots created by T-Mobile, combining existing honeypots (glastopf, kippo, honeytrap and dionaea) with the network IDS/IPS suricata, and T-Mobile's own data submission ewsposter which now also supports hpfeeds honeypot data sharing. For more information on T-Pot please see http://dtag-dev-sec.github.io/mediator/feature/2015/03/17/concept.html. 

The T-Mobile T-Pot Honeypot App contains dashboard visualizations for the T-Mobile T-Pot Honeypot Technical Add-on located here: https://splunkbase.splunk.com/app/4339/

Install this app on your Splunk Search Heads and change the "tpotindex" macro to point to the proper index that your T-Pot Honeypot data is saved if changed from the tpot index.
