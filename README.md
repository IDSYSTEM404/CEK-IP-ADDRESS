# CEK-IP-ADDRESS


Why do you need geolocation?

Pairing of IP address to a geographical location is called geolocation. There are times when you need to identify where your web visitors are coming from. You might have an ecommerce website, and would like to know where your potential customers are, pre-populate country code on forms, display different language and reduce credit card fraud based on geographic location. Or, you might want to fight against illegal spammers and hackers, and would like to locate source of a problem.

Although it would be nice to be able to find precise location of a visitor, it is almost impossible to find exact location of a host given its IP address. However, there are tools available to help identify approximate location of the host. ARIN Whois database provides a mechanism for finding contact and registration information for IP resources registered with ARIN.

You may also use 3rd party websites such as Geobytes or Dnsstuff to lookup the IP address. The whois lookup will reveal name of the ISP who owns that IP address, and the country where it is originated from. If you're lucky, you might also find the city of orgin. You may also use products developed by 3rd party companies like Ip2location. Our sister website, findmyip.org also provides a geographic information of your IP address.

You may also use reverse DNS to find out the hostname of the IP address, which might give you some clues. Many ISPs, Corporations and Academic institutions use location as a qualified hostname, although this is not always true. A couple of things to note here: (1) Reverse DNS translation does not always work. It depends on the correct configuration of the ISP's DNS server. (2) The US domain names such as .com, .net and .org does not always imply that the host is located in the United States.

You may use 'traceroute' command to find clues to the location of the IP address. The names of the routers through which packets flow from your host to the destination host might hint at the geographical path of the final location.

IP-based Geolocation FAQ
1. What is IP-based Geolocation?

IP-based Geolocation is mapping of an IP address or MAC address to the real-world geographic location of an Internet-connected computing or a mobile device. Geolocation involves in mapping IP address to the country, region (city), latitude/longitude, ISP and domain name among other useful things.
2. Where can I get a IP-based Geolocation database?

There are a number of commercially available geolocation databases, and their pricing and accuracy may vary. Ip2location, MaxMind, Tamo Soft, DB-IP, Ipinfo and IPligence offer a fee-based databases that can be easily integrated into an web application. Most geolocation database vendors offers APIs and example codes (in ASP, PHP, .NET and Java programming languages) that can be used to retrieve geolocation data from the database. We use a number of commercial databases to offer a free geolocation data on our website.

There are also freely available geolocation databases. Vendors offering commercial geolocation database also offer a Lite or Community edition that provides IP-to-Country mappings. Ip2Country.net and Webhosting.info (Directi) offer free IP-to-Country database that can be also integrated into your web application. There are companies also offering free web services that can be used to show geolocation of an IP address on your website.
3. How accurate is IP-based Geolocation?

Accuracy of geolocation database varies depending on which database you use. For IP-to-country database, some vendors claim to offer 98% to 99% accuracy although typical Ip2Country database accuracy is more like 95%. For IP-to-Region (or City), accracy range anywhere from 50% to 75% if neighboring cities are treated as correct. Considering that there is no official source of IP-to-Region information, 50+% accuracy is pretty good.
4. How does IP-based geolocation work?

ARIN Whois database provides a mechanism for finding contact and registration information for IP resources registered with ARIN. The IP whois information is available for free, and determining the country from this database is relatively easy. When an organization requires a block of IP addresses, a request is submitted and allocated IP addresses are assigned to a requested ISP.

# For Windows
- Install XAMPP
- Download https://github.com/IDSYSTEM404/CEK-IP-ADDRESS
- usage : php cekip.php

# For Termux or Linux
- pkg install php
- git clone https://github.com/IDSYSTEM404/CEK-IP-ADDRESS
- cd CEK-IP-ADDRESS
- php cekip.php
