# MariHost WP Stack (Beta)

MariHost WP Stack is a free LEMP stack automation script written in Bash designed to enhance and simplify WordPress provisioning, performance, and security.

## What To Expect

| PageSpeed | GTMetrix | Pingdom | SecHeaders | SSL Labs | WebPageTest | ImmuniWeb |
| :--------------: | :------: | :-----: | :--------------: | :-------------: | :-------------: | :-------------: |
| [**A**](https://developers.google.com/speed/pagespeed/insights/?url=https%3A%2F%2Fslickstack.io%2F) | [**A**](https://gtmetrix.com/reports/slickstack.io/zpLMZ1eb) | [**A**](https://tools.pingdom.com/#5aeba9dea8000000) | [**A**](https://securityheaders.com/?q=https%3A%2F%2Fslickstack.io%2F&followRedirects=on) | [**A**](https://www.ssllabs.com/ssltest/analyze.html?d=slickstack.io&latest) | [**A**](https://www.webpagetest.org/result/190920_68_a4a541db9847ce601ef264b41df9d0f3/) | [**A**](https://www.immuniweb.com/websec/?id=pmqYyXDB) |

## Core Modules

*Last updated: Feb 26, 2022*

| LEMP Module | Mirrors | Version | What does MariHost WP Stack customize? |
| :------------- | :----------: | :----------: | :----------: |
| **Ubuntu LTS** | [mirrors](https://mirrors.slickstack.io/modules/ubuntu/) | 20.04 | `crontab` + `gai.conf` + `sshd_config` + `sudoers` + `sysctl.conf` |
| **Nginx** | [mirrors](https://mirrors.slickstack.io/modules/nginx/) | 1.18.x | `nginx.conf` + server blocks |
| **OpenSSL** | [mirrors](https://mirrors.slickstack.io/modules/openssl/) | 1.1.1x | `slickstack.crt` + `slickstack.key` + `dhparam.pem` |
| **Lets Encrypt** | [mirrors](https://mirrors.slickstack.io/modules/letsencrypt/) | 0.40.x | `cert.perm` + `chain.pem` + `fullchain.pem` + `privkey.pem` |
| **MySQL** | [mirrors](https://mirrors.slickstack.io/modules/mysql/) | 8.0.x | `my.cnf` |
| **PHP-FPM** | [mirrors](https://mirrors.slickstack.io/modules/php-fpm/) | 7.4.x | `php.ini` + `php-fpm.conf` + `www.conf` |
| **Redis** | [mirrors](https://mirrors.slickstack.io/modules/redis/) | 5.0.x | `redis.conf` + `object-cache.php` |
| **WordPress** | [mirrors](https://mirrors.slickstack.io/modules/wordpress/) | 5.9.1 | some WP Core junk files are removed by `ss-clean` |
| **WP-CLI** | [mirrors](https://mirrors.slickstack.io/modules/wordpress/wp-cli/) | 2.6.0 | some commands are disabled |
| **Adminer** | [mirrors](https://mirrors.slickstack.io/modules/adminer/) | 4.8.1 | default config |
| **Git** | [mirrors](https://mirrors.slickstack.io/modules/git/) | 2.25.x | default config |
| **UFW Firewall** | [mirrors](https://mirrors.slickstack.io/modules/ufw-firewall/) | 0.36 | `ufw` + `ufw.conf` + `user-rules` |
| **ClamAV** | [mirrors](https://mirrors.slickstack.io/modules/clamav/) | 0.102.x | `freshclam.conf` |
| **Rclone** | [mirrors](https://mirrors.slickstack.io/modules/rclone/) | 1.50.x | `rclone.conf` |
