#Authentication System: 
2FA should be enforced and password security Wifi Security: Wifi Secured by Certificates and on WPA2 or WPA3 if possible 
# External website security
* Code should be audited by a third party on occasion 
* Fraud alerts should be logged and accounts flagged if suspicious login attempts occur 
# Internal Website Security
* Only allow access via a company VPN 
* Log all attempts and ask for email verification for new ips Remote access solution: 
* RDP through VPN solution described above 
# Firewall: 
* Disallow all services except vpn (on a seperate ip endpoint) and external web server from accessing the internet VLAN configuration: * Have local domains that map to different servers 
* Different departments different networks Laptop security: 
* Lock down BIOS and enable Secure Boot 
* Impliment barcode scanning and tracking of Machine IDs Application policy: 
* No apps can be installed without approval of the IT administrator 
# Privacy Policy: 
* Look into EULA regulations and have a clear and consist page that explains the privacy policy 
# Intrusion Detection and Prevention: 
* Install an IDS and keep central logs 
* Only allow certain vetted services to access customer data, and keep logs of sql queries as well as highlights for suspicious ones or frequent database reads. 