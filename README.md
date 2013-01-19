Bad Bot Blocker
===============

231 Apache htaccess rules to block bad bots.

Some of the stuff blocked:

- E-mail harvesters
- Content scrapers
- Spam bots
- Aggressive bots that provide little value
- Bots linked to viruses or malware
- Government surveillance bots
- Russian search engine Yandex
- Chinese search engine Baidu

You should disable the rules for Yandex or Baidu if you want
them to index your website. But unless your website is written
in Russian or Chinese, you probably don't get any traffic
from them. They mostly just waste bandwidth and consume resources.

Bots frequently try to make themselves look like other software by
disguising their useragent. Many of the rules look harmless or
perfectly legitimate, such as, "^Java" but it's actually one of the most
potentially dangerous useragents. And it has no known legitimate purpose
that in use today.

If you have a bizarre or complicated setup, be sure to look everything
over before using it. But for everyone else, this should work without
any issues.

