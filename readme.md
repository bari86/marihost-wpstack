# MariHost WP Stack (Beta)

MariHost WP Stack is a free LEMP stack automation script written in Bash designed to enhance and simplify WordPress provisioning, performance, and security.



| PageSpeed | GTMetrix | Pingdom | SecHeaders | SSL Labs | WebPageTest | ImmuniWeb |
| :--------------: | :------: | :-----: | :--------------: | :-------------: | :-------------: | :-------------: |
| [**A**](https://developers.google.com/speed/pagespeed/insights/?url=https%3A%2F%2Fslickstack.io%2F) | [**A**](https://gtmetrix.com/reports/slickstack.io/zpLMZ1eb) | [**A**](https://tools.pingdom.com/#5aeba9dea8000000) | [**A**](https://securityheaders.com/?q=https%3A%2F%2Fslickstack.io%2F&followRedirects=on) | [**A**](https://www.ssllabs.com/ssltest/analyze.html?d=slickstack.io&latest) | [**A**](https://www.webpagetest.org/result/190920_68_a4a541db9847ce601ef264b41df9d0f3/) | [**A**](https://www.immuniweb.com/websec/?id=pmqYyXDB) |

## Core Modules

*Last updated: Apr 30, 2022*

| LEMP Module | Mirrors | Version | What does SlickStack optimize? |
| :------------- | :----------: | :----------: | :----------: |
| **Ubuntu LTS** | [mirrors](https://mirrors.slickstack.io/modules/ubuntu/) | 22.04 | `crontab` + `gai.conf` + `sshd_config` + `sudoers` + `sysctl.conf` |
| **Nginx** | [mirrors](https://mirrors.slickstack.io/modules/nginx/) | 1.18.x | `nginx.conf` + server blocks |
| **OpenSSL** | [mirrors](https://mirrors.slickstack.io/modules/openssl/) | 3.0.x | `slickstack.crt` + `slickstack.key` + `dhparam.pem` |
| **Lets Encrypt** | [mirrors](https://mirrors.slickstack.io/modules/letsencrypt/) | 1.21.x | `cert.perm` + `chain.pem` + `fullchain.pem` + `privkey.pem` |
| **MySQL** | [mirrors](https://mirrors.slickstack.io/modules/mysql/) | 8.0.x | `my.cnf` |
| **PHP-FPM** | [mirrors](https://mirrors.slickstack.io/modules/php-fpm/) | 8.1.x | `php.ini` + `php-fpm.conf` + `www.conf` |
| **Redis** | [mirrors](https://mirrors.slickstack.io/modules/redis/) | 6.0.x | `redis.conf` + `object-cache.php` |
| **WordPress** | [mirrors](https://mirrors.slickstack.io/modules/wordpress/) | 5.9.x | some WP Core junk files are removed by `ss-clean` |
| **WP-CLI** | [mirrors](https://mirrors.slickstack.io/modules/wordpress/wp-cli/) | 2.6.0 | some commands are disabled |
| **Adminer** | [mirrors](https://mirrors.slickstack.io/modules/adminer/) | 4.8.1 | default config |
| **Git** | [mirrors](https://mirrors.slickstack.io/modules/git/) | 2.34.x | default config |
| **UFW Firewall** | [mirrors](https://mirrors.slickstack.io/modules/ufw-firewall/) | 0.36.x | `ufw` + `ufw.conf` + `user-rules` |
| **ClamAV** | [mirrors](https://mirrors.slickstack.io/modules/clamav/) | 0.103.x | `freshclam.conf` |
