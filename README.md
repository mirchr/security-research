# Security Research
A collection of files related to my personal security research. Additional content will be posted on my blog https://blog.mirch.io.

## Tools
* [openssldir_check](https://github.com/mirchr/openssldir_check/) - A Windows utility to check for potential insecure paths used by the OPENSSLDIR build parameter in OpenSSL libraries
* [ssscache2john](https://github.com/mirchr/ssscache2john/) - Convert SSSD LDAP cache files to John The Ripper format
* [DumpTompcatSessions](https://github.com/mirchr/DumpTomcatSessions/) - Dump Tomcat sessions using JMX


| Tool | Description |
| :---: |-------------|
|[openssldir_check](https://github.com/mirchr/openssldir_check/)| Windows utility to check for potential insecure paths used by the OPENSSLDIR build parameter in OpenSSL libraries|
|[ssscache2john](https://github.com/mirchr/ssscache2john/)|Convert SSSD LDAP cache files to John The Ripper format|
|[DumpTompcatSessions](https://github.com/mirchr/DumpTomcatSessions/)|Dump Tomcat sessions using JMX|

## Vulnerabilities

* CVE-2019-12571 - PIA macOS Arbitrary File Overwrite. [CVE-2019-12571.txt](vulnerabilities/PIA/CVE-2019-12571.txt).

* CVE-2019-12572 - PIA Windows Privilege Escalation: Malicious OpenSSL engine. [CVE-2019-12572.txt](vulnerabilities/PIA/CVE-2019-12572.txt). Walk through https://blog.mirch.io/2019/06/10/cve-2019-12572-pia-windows-privilege-escalation-malicious-openssl-engine/

* CVE-2019-12573 - PIA Linux, macOS Arbitrary File Overwrite. [CVE-2019-12573.txt](vulnerabilities/PIA/CVE-2019-12573.txt).

* CVE-2019-12574 - PIA Windows Privilege Escalation: DLL Injection. Detailed write-up: [CVE-2019-12574.txt](vulnerabilities/PIA/CVE-2019-12574.txt).

* CVE-2019-12575 - PIA Linux, macOS Privilege Escalation: Shared Object Injection. [CVE-2019-12575.txt](vulnerabilities/PIA/CVE-2019-12575.txt).

* CVE-2019-12576 - PIA macOS Privilege Escalation: Untrusted Search Path. [CVE-2019-12576.txt](vulnerabilities/PIA/CVE-2019-12576.txt).

* CVE-2019-12577 - PIA macOS Privilege Escalation: Insecure umask. [CVE-2019-12577.txt](vulnerabilities/PIA/CVE-2019-12577.txt).

* CVE-2019-12578 - PIA Linux Privilege Escalation: Argument Injection. [CVE-2019-12578.txt](vulnerabilities/PIA/CVE-2019-12578.txt).

* CVE-2019-12579 - PIA Linux, macOS Privilege Escalation: Command Injection. [CVE-2019-12579.txt](vulnerabilities/PIA/CVE-2019-12579.txt).

* CVE-2019-6617 - F5 BIG-IP Resource Administrator Privilege Escalation. [CVE-2019-6617.txt](vulnerabilities/F5/CVE-2019-6617.txt). F5 Advisory: https://support.f5.com/csp/article/K38941195

* CVE-2019-6724 - Barracuda VPN Client Privilege Escalation on Linux and macOS. PoC: [CVE-2019-6724.sh](vulnerabilities/CVE-2019-6724.sh). Detailed write-up: [CVE-2019-6724: Barracuda VPN Client Privilege Escalation on Linux and macOS](https://blog.mirch.io/2019/02/14/cve-2019-6724-barracuda-vpn-client-privilege-escalation-on-linux-and-macos/). Barracuda VPN Client [Release Notes](http://campus.barracuda.com/product/networkaccessclient/doc/78154149/release-notes-barracuda-vpn-client-for-linux/)

* CVE-2018-15332 - F5 BIG-IP APM client for Linux and macOS arbitrary file takeover vulnerability. Detailed write-up: [CVE-2018-15332.txt](vulnerabilities/F5/CVE-2018-15332.txt). F5 Advisory: [K12130880](https://support.f5.com/csp/article/K12130880)

* CVE-2018-5529, CVE-2018-5546 - F5 BIG-IP APM client for Linux and macOS vulnerability. Detailed write-up: [CVE-2018-5529.txt](vulnerabilities/F5/CVE-2018-5529.txt). F5 Advisories: [K52171282](https://support.f5.com/csp/article/K52171282), [K54431371](https://support.f5.com/csp/article/K54431371)

* CVE-2018-18629 - Privilege Escalation on Linux via keybase-redirector . PoC: [CVE-2018-18629.sh](vulnerabilities/CVE-2018-18629.sh). Detailed write-up: [CVE-2018-18629: Keybase Linux privilege escalation](https://blog.mirch.io/2018/12/21/cve-2018-18629-keybase-linux-privilege-escalation/). Keybase Advisory: [Local Privilege Escalation on Linux via keybase-redirector (KB002)](https://keybase.io/docs/secadv/kb002)

* CVE-2018-19788 - PolicyKit (aka polkit) 0.115 that allows a user with a uid greater than INT_MAX to successfully execute any systemctl command. PoC: [CVE-2018-19788.sh](vulnerabilities/CVE-2018-19788.sh). Detailed write-up: [CVE-2018-19788 PoC – polkit: Improper handling of user with uid > INT_MAX leading to authentication bypass](https://blog.mirch.io/2018/12/09/cve-2018-19788-poc-polkit-improper-handling-of-user-with-uid-int_max-leading-to-authentication-bypass/). The Hacker News article: [Warning! Unprivileged Linux Users With UID > INT_MAX Can Execute Any Command](https://thehackernews.com/2018/12/linux-user-privilege-policykit.html)
* CVE-2018-18556 - VyOS Privilege escalation via sudo pppd for operator users. PoC: [CVE-2018-18556.sh](vulnerabilities/VyOS/CVE-2018-18556.sh). Detailed write-up: [CVE-2018-18556 – VyOS Privilege escalation via sudo pppd for operator users](https://blog.mirch.io/2018/11/05/cve-2018-18556-vyos-privilege-escalation-via-sudo-pppd-for-operator-users). Advisory: [The "operator" level is proved insecure and will be removed in the next releases](https://blog.vyos.net/the-operator-level-is-proved-insecure-and-will-be-removed-in-the-next-releases)


