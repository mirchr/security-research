# Security Research
A collection of files related to my personal security research. Additional content will be posted on my blog https://blog.mirch.io.


### Exploits
* CVE-2018-19788 - PolicyKit (aka polkit) 0.115 that allows a user with a uid greater than INT_MAX to successfully execute any systemctl command. [CVE-2018-19788.sh](vulnerabilities/CVE-2018-19788.sh). The Hacker News article: [Warning! Unprivileged Linux Users With UID > INT_MAX Can Execute Any Command](https://thehackernews.com/2018/12/linux-user-privilege-policykit.html)
* CVE-2018-18556 - VyOS Privilege escalation via sudo pppd for operator users. [CVE-2018-18556.sh](vulnerabilities/VyOS/CVE-2018-18556.sh). Detailed write-up: https://blog.mirch.io/2018/11/05/cve-2018-18556-vyos-privilege-escalation-via-sudo-pppd-for-operator-users.


