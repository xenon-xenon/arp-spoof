## ARP Cache Poisoning
Script for MITM attack 

Usage
--
- How to use:

    sudo python3 arp-cache-poisoning.py -i `<interface>` -t1 `<target1>` -t2 `<target2>`
- To get help use:

    sudo python3 arp-cache-poisoning.py -h
    
Example 
--
    sudo python3 arp-cache-poisoning.py -i eth0 -t1 192.168.1.1 -t2 192.168.1.50

Note
--
- You have to run this script with `root` privileges !
- You should have enabled `ip forwarding` on your machine !
