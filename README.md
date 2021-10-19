![GitHub last commit](https://img.shields.io/github/last-commit/zelo72/adguard)![GitHub commit activity](https://img.shields.io/github/commit-activity/m/zelo72/adguard)![GitHub issues](https://img.shields.io/github/issues/zelo72/adguard)![GitHub closed issues](https://img.shields.io/github/issues-closed/zelo72/adguard)![visitors](https://visitor-badge.glitch.me/badge?page_id=zelo72.adguard&left_color=grey&right_color=blue)

## AdBlock filterlists for AdGuard Home/DNS, AdBlock, uBlock & Co.
***Other formats: [Hosts](https://github.com/Zelo72/hosts) | [Domains](https://github.com/Zelo72/rpi)***

### ***DNS blacklists*** (Black-/Blocklists)

**Overview:**
| List | Big | Multi | Light | Fake | Personal | [OISD full](https://oisd.nl/downloads) | [OISD basic](https://oisd.nl/downloads) |
|:-----|:---:|:-----:|:-----:|:----:|:--------:|:--------------------------------------:|:---------------------------------------:|
| [Big](https://raw.githubusercontent.com/Zelo72/adguard/main/big.adblock)                                       |   | X | X | X | X | X |   |
| [Multi](https://raw.githubusercontent.com/Zelo72/adguard/main/multi.adblock)                                   |   |   | X |   | X |   | X |
| [Light](https://raw.githubusercontent.com/Zelo72/adguard/main/light.adblock)                                   |   |   |   |   | X |   |   |
| [Fake](https://raw.githubusercontent.com/Zelo72/adguard/main/fake.adblock)                                     |   | + | + |   | + |   |   |
| [Personal](https://raw.githubusercontent.com/Zelo72/adguard/main/personal.adblock)                             |   |   |   |   |   |   |   |
| [Affiliate & Tracking](https://raw.githubusercontent.com/Zelo72/adguard/main/affiliatetracking.adblock)        | + | + | + |   | + |   |   |
| [Threat Intelligence Feeds](https://raw.githubusercontent.com/Zelo72/adguard/main/threat-intelligence.adblock) | + | + | + |   | + |   |   |

*X= contains the named list in the column header    
+= expands the named list in the column header*
         
#### Totallist ***(recommendation)***

[**Big**](https://raw.githubusercontent.com/Zelo72/adguard/main/big.adblock) - Zelo's "Big" Blocklist: Blocks ads, tracking, metrics, telemetry, fake, phishing, malware, coins, crypto and other "crap". An all-in-one blocklist that does not block any mandatory "functions" - no strict blocking. Dead hosts (hosts addresses that no longer exist) have been removed from this list. It can be used as a standalone blocklist. The prerequisite is that the ad blocker can handle large lists. With Pihole, for example, this is no problem. The list contains about 1.300.000 domains (570.000 AdBlock optimized).

> ***Link:***
> https://raw.githubusercontent.com/Zelo72/adguard/main/big.adblock
> 
> ***Sources:*** [Stats](https://github.com/Zelo72/rpi/blob/master/pihole/blocklists/big.stats)

#### Basiclists (included in Big blocklist)

[**Multi**](https://raw.githubusercontent.com/Zelo72/adguard/main/multi.adblock) - Zelo's "Multi" blocklist: Blocks ads, tracking, metrics, telemetry, phishing, malware, coins, crypto and other "crap". The "light" version of the big list. A light all-in-one blocklist that does not block any mandatory "functions" - no strict blocking. Dead hosts (hosts addresses that no longer exist) have been removed from this list. It can be used as a standalone blocklist. The list contains about 430.000 domains (250.000 AdBlock optimized).

> ***Link:***
> https://raw.githubusercontent.com/Zelo72/adguard/main/multi.adblock
> 
> ***Sources:*** [Stats](https://github.com/Zelo72/rpi/blob/master/pihole/blocklists/multi.stats)

[**Light**](https://raw.githubusercontent.com/Zelo72/adguard/main/light.adblock) - Zelo's "Light" blocklist: Blocks ads, tracking, metrics, telemetry. The "very light" version of the multi list. A lightweight blocklist for ad blockers who have problems with large lists that does not block any mandatory "functions" - no strict blocking. Dead hosts (hosts addresses that no longer exist) have been removed from this list. The list contains about 100.000 domains (60.000 AdBlock optimized).

> ***Link:***
> https://raw.githubusercontent.com/Zelo72/adguard/main/light.adblock
> 
> ***Sources:*** [Stats](https://github.com/Zelo72/rpi/blob/master/pihole/blocklists/light.stats)

[**Fake**](https://raw.githubusercontent.com/Zelo72/adguard/main/fake.adblock) - Zelo's "Fake" blocklist: Blocks fake stores, -news, -science, -streaming, rip-offs, cost traps and co. Based on various consumer sites, warnings and other fake lists. As a recommended addition to the multi or light blocklist, the domains from the fake blocklist are included in the big blocklist. The list contains about 15.000 domains (7.500 AdBlock optimized).

> ***Link:*** https://raw.githubusercontent.com/Zelo72/adguard/main/fake.adblock
> 
> ***Sources:*** *Consumer Sites, Trusted Shops, Watchlist Internet, zelo72* - [Stats](https://github.com/Zelo72/rpi/blob/master/pihole/blocklists/fake.stats)

#### Personallists (included in Light/Multi/Big blocklist)

[**Personal**](https://raw.githubusercontent.com/Zelo72/adguard/main/personal.adblock) - Zelo's "Personal" blocklist: Blocks ads, tracking, metrics, telemetry and  other "crap". As an extension for other blocklists. The personal blocklist is already included in my light/multi/big blocklist! The list contains about 23.000 domains (13.000 AdBlock optimized).

> ***Link:*** https://raw.githubusercontent.com/Zelo72/adguard/main/personal.adblock
> 
> ***Sources:*** [Stats](https://github.com/Zelo72/rpi/blob/master/pihole/blocklists/personal.stats)

#### Extensionlists (if required - as an extension to the big, multi or light blocklist)

[**Affiliate&Tracking**](https://raw.githubusercontent.com/Zelo72/adguard/main/affiliatetracking.adblock) - Zelo's "Affiliate & Tracking Plus" Blocklist: Blocks additional ads, ad links, tracking, metrics and telemetry. An extension to the light/multi/big blocklist. Note: This blocklist also blocks e.g. links marked as ads in Google search or affiliate links in mail offers. The list contains about 170.000 domains (142.000 AdBlock optimized). ***(Optional)***

> ***Link:*** https://raw.githubusercontent.com/Zelo72/adguard/main/affiliatetracking.adblock
> 
> ***Sources:*** [Stats](https://github.com/Zelo72/rpi/blob/master/pihole/blocklists/affiliatetracking.stats)

[**ThreatIntelligenceFeeds**](https://raw.githubusercontent.com/Zelo72/adguard/main/threat-intelligence.adblock)- Zelo's "Threat Intelligence Feeds": Blocks Malware, Crypto, Coins, Spam, Scam and Pishing - domains known to spread malware, launch phishing attacks, host command-and-control servers and more. Increases secutity significantly. The list contains about 320.000 domains (280.000 AdBlock optimized). ***(Optional)***

*An attempt has been made to avoid false positive domains, but still this list may contain false positive domains. Therefore, an admin should be available to allow falsely blocked domains when you use this list. Please report false positive domains.*

> ***Link:*** https://raw.githubusercontent.com/Zelo72/adguard/main/threat-intelligence.adblock
> 
> ***Sources:*** [Stats](https://github.com/Zelo72/rpi/blob/master/pihole/blocklists/threat-intelligence.stats)

---

### ***Note***

***The blocklists were created for purely personal, private use. They were designed to avoid false positive domains as much as possible and not to block any needed features. Maximum blocking with full functionality. They were [compiled](https://github.com/Zelo72/rpi/tree/master/pihole/blocklists/build) from [numerous sources](https://github.com/Zelo72/adguard/blob/main/SOURCES.md), my own [blacklists](https://github.com/Zelo72/rpi/tree/master/pihole/blocklists/data) and various [whitelists](https://github.com/Zelo72/adguard/blob/main/SOURCES.md#white--dead-list). To keep the lists as small as possible, [dead domains](https://github.com/Zelo72/adguard/blob/main/SOURCES.md#white--dead-list) are removed regularly.***

**The blocklists are updated daily.**

---

### ***Credits***

**A huge thank you to the following list maintainers of the [sources used](https://github.com/Zelo72/rpi/blob/master/SOURCES.md):**

*ABPindo, abpvn, AdAway, adblock.gardar.net, AdguardTeam, AdroitAdorKhan, AhaDNS, alphasoc.net, AmnestyTech, anudeepND, azorult-tracker.net, badmojr, blokadaorg, bongochong, botvrij.eu, boutetnico, cbuijs, cert-pa.it, chrisjudk, common-lisp.net, curbengh, cyberthreatcoalition.org, d3ward, Dan Pollock (someonewhocares.org), DandelionSprout, davidonzo, DRSDavidSoft, durablenapkin, easylist, EasyList-Lithuania, easylist-thailand, EnergizedProtection, guardicore, hole.cert.pl, hoshsadiq, hostfiles.frogeye.fr, hpthreatresearch, iam-py-test, infinitytec, jdlingyu, jkrejcha, joewein.net, JoseGalRe, kargig, Kees1958, KevinThomas0, kriskintel.com, Laicure, latvian-list, matomo-org, metamask, mitchellkrogza, mkb2091, Natizyskunk, nextdns, notracking, ookangzheng, orca.pet, osint.digitalside.it, paulgb, Peter Lowe (pgl.yoyo.org), phishing.army, piperun, PolishFiltersTeam, prodaft, quidsup, raghavdua1995, rescure.me, RPiList, rspamd, scafroglia93, ShadowWhisperer, shreyasminocha, socram8888, Spam404, stamparm, stanev.org, Stephan (sjhgvr - oisd.nl), StevenBlack, stonecrusher, stopforumspam.com, T145, tiuxo, tomasko126, uBlockOrigin, Ultimate-Hosts-Blacklist, URLhaus, usom.gov.tr, velesila, WaLLy3K, What-Zit-Tooya, windscribe.com, winhelp2002.mvps.org, yecarrillo, Yhonay, zebpalmer, ZeroDot1, zoso.ro*

---

*For a better internet - keep the internet clean!*

---

Test results of around 6000 website views from [WhoTracks.Me website list](https://whotracks.me/websites.html) with active big and affiliate & tracking block list:

![grafik](https://user-images.githubusercontent.com/62211544/137098766-08427ada-623c-4590-a689-03a4c1159cd4.png)

