# IT-Security

## Introduction

Huge shoutout to [xapax](https://github.com/xapax) and [sushant747](https://github.com/sushant747) for the base repo for this note collection.

My notepad about stuff related to IT-security, and specifically penetration testing. Stuff I have come across that I don't feel like googeling again.

I have used this book to try to write down how some things work, but at the same time I want to use it as a reference book to find commands and things I just can't remember. Therefore I have tried to create a TLDR section in the beginning of some chapters where I have copy-paste ready commands that are useful. And if you want to know more you can continue to read the rest of the chapter. This is my way of making the book a hybrid between the Red Team Field Manual and a standard introduction book to pentesting.

Also, this book is just a collection of stuff that is available on the interwebz. I am just a simple collector. I have tried to include a reference section to show where I found the technique. This book is my way of trying to give something back to the infosec community and I hope it can be useful to someone.

You can read this book on [https://xapax.gitbooks.io/security/content/](https://xapax.gitbooks.io/security/content/). If you feel like contributing, or just forking it, you can do that from its github repo here: [https://github.com/xapax/security](https://github.com/xapax/security). If you feel like this is a good start, but you want to add and remove things and just make it yours you can just fork it and do whatever you want with it.

## Summary

* [Introduction](README.md)
* [The Basics](the_basics.md)
  * [Linux](linux.md)
    * [Basics of Linux](basics_of_linux.md)
    * [Bash-scripting](bash-scripting.md)
    * [Vim](vim.md)
  * [Windows](windows.md)
    * [Basics of Windows](basics_of_windows.md)
    * [PowerShell](powershell.md)
    * [PowerShell Scripting](powershell_scripting2.md)
    * [CMD](cmd.md)
  * [Scripting With Python](scripting_with_python.md)
    * [Python Fundamentals](python_fundamentals.md)
    * [Useful Scripts](connections.md)
  * [Transferring Files](transfering_files2.md)
    * [Transfering Files on Linux](transfering_files.md)
    * [Transfering files on Windows](transfering_files_to_windows.md)
  * [Firewalls](firewalls.md)
  * [General tips and tricks](general_tips.md)
* [Recon and Information Gathering Phase](scanning.md)
  * [Passive Information Gatherig](passive_information_gatherig.md)
    * [TODO] Identify IP-addresses and Subdomains
      * [TODO] Identify IP-addresses
      * [Find Subdomains](find_subdomains.md)
        * [DNS Basics](dns_basics.md)
        * [Finding subdomains](finding_subdomains.md)
        * [DNS Zone Transfer Attack](dns_zone_transfer_attack.md)
    * [Identifying People](email_harvesting.md)
    * [Search Engine Discovery](google_hacking.md)
    * [Identifying Technology Stack](identifying-technology-stack.md)
  * [Active Information Gathering](active_information_gathering.md)
    * [Port Scanning](port_scanning.md)
* [Vulnerability analysis](vulnerability_analysi1s.md)
  * [Server-side Vulnerabilities](server-side-vulnerabilities.md)
    * [Common ports\/services and how to use them](list_of_common_ports.md)
    * [Port Knocking](port_knocking.md)
  * [HTTP - Web Vulnerabilities](web-services.md)
    * [Common Web-services](common_web-services.md)
    * [WAF - Web Application Firewall](waf_-_web_application_firewall.md)
    * [Attacking the System](lead_to_compromise.md)
      * [Local File Inclusion](local_file_inclusion.md)
      * [Remote File Inclusion](remote_file_inclusion.md)
      * [Hidden Files and Directories](web-scanning.md)
      * [SQL-Injections](sql-injections.md)
      * [Nosql-Injections](nosql-injections.md)
      * [XML External Entity Attack](xml_external_entity_attack.md)
      * [Bypass File Upload Filtering](bypass_image_upload.md)
      * [Exposed Version Control](exposed_version_control.md)
      * [Failure to Restrict URL Access](failure-to-restrict-url-access.md)
    * [Attacking the User](attacking_the_user.md)
      * [Clickjacking](clickjacking.md)
      * [Broken Authentication or Session Management](broken_authentication_or_session_management.md)
      * [Text\/content-injection](text-injection.md)
      * [Subdomain Takeover](subdomain_takeover.md)
      * [Cross Site Request Forgery](cross_site_request_forgery.md)
      * [Cross-site-scripting](cross-site-scripting.md)
        * [Examples](examplesXSS.md)
      * [Browser Vulnerabilities](browser_vulnerabilities.md)
      * [Java Applet](java_applet.md)
  * [Automated Vulnerability Scanners](automated_vulnerability_scanners.md)
* [Exploiting](exploiting.md)
  * [Social Engineering - Phishing](social_engineering_-_phishing.md)
  * [Default Layout of Apache on Different Versions](default_layout_apache_on_different_versiont.md)
  * [Shells](reverse-shell.md)
  * [Webshell](webshell.md)
  * [Generate Shellcode](create_shellcode.md)
  * [Editing Exploits](editing-exploits.md)
  * [Compiling windows exploits](compiling-windows-exploits.md)
* [Post Exploitation](post_exploitation.md)
  * [Spawning Shells](spawning_shells.md)
  * [Meterpreter for Post-Exploitation](getting_meterpreter_shell.md)
  * [Privilege Escalation - Linux](privilege_escalation_-_linux.md)
  * [Privilege Escalation - Windows](privilege_escalation_windows.md)
  * [Escaping Restricted Shell](escaping_restricted_shell.md)
  * [Bypassing antivirus](bypassing_antivirus.md)
  * [Loot and Enumerate](loot.md)
    * [Loot Windows](loot_windows_-_for_credentials_and_other_stuff.md)
    * [Loot Linux](tcp-dumps_on_pwnd_machines.md)
  * [Persistence](persistence.md)
  * [Cover your tracks](clean_up.md)
* [Password Cracking](password-cracking.md)
  * [Generate Custom Wordlist](generate_custom_wordlist.md)
  * [Offline Password Cracking](identify_hash_and_crack_it.md)
  * [Online Password Cracking](online_password_cracking.md)
  * [Pass the Hash - Reusing Hashes](pass_the_hash_-_reusing_hashes.md)
* [Pivoting - Port forwarding - Tunneling](port_forwarding_and_tunneling.md)
* [Network traffic analysis](network_traffic.md)
  * [Arp-spoofing](arp-spoofing.md)
    * [SSL-strip](ssl-strip.md)
  * [DNS-spoofing](dns-spoofing.md)
  * [Wireshark](wireshark.md)
* [Wifi](wifi.md)
  * [WEP](wep.md)
  * [WPS](wps.md)
* [Physical access to machine](physical_access_to_machine.md)
* [Literature](littearature.md)

## Find practical examples

If you read about a vulnerability that you want to know more about I can really recommend searching for in on HackerOne via google. It is a good way to find real life examples of vulnerabilities.

Here is an example of such a search:

```
site:hackerone.com sql-injection
```

## Disclaimers

Sometimes the line isn't very clear between the chapters. Some actions might be considered part of the vulnerability analysis-phase, but it could also but considered part of the recon-phase. It is what it is.

These chapters are written sporadically with a lot of stuff missing. I just add stuff wherever whenever. Also, things might not be accurate, I might have misunderstood something or misused a tool. So don't trust me or this book for any accuracy.

