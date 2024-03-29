If this helped you, consider [![](https://img.shields.io/static/v1?label=Sponsor&message=%E2%9D%A4&logo=GitHub&color=%23fe8e86)](https://github.com/sponsors/reportsmishing)
[![twitter](https://img.shields.io/twitter/follow/reportsmishing?style=social)](https://twitter.com/reportsmishing)

# Knowledgebase

## Contents

- [Check redirection of various shortened URLs without clicking on the URL](#check-redirection-of-various-shortened-urls-without-clicking-on-the-url-credits-aware-online)
   - [Manually](#manually)
   - [Free Website to unshorten URL](#free-website-to-unshorten-url-unshortenit)
   - [Using commandline](#fancy-command-line-use-curl)
- [Investigating URL Shorteners](#investigating-url-shorteners)  
   - [shrtco.de shortened URLs](#shrtcode-shortened-urls)
   - [rb.gy shortened URLs](#rbgy-shortened-urls)
   - [cutt.ly shortened URLs](#cuttly-shortened-urls)
   - [is.gd/v.gd shortened URLs](#isgdvgd-shortened-urls)
   - [t.ly shortened URLs](#tly-shortened-urls)
- [Various investigations for smishing URLs](#investigations-for-smishing-urls-credits-maltego)
   - [Blogs on SMS Phishing Investigation](#blogs-on-sms-phishing-investigation)
   - [Scripts to investigate smishing URLs](#public-codebase-to-investigate-smishing-urls)
   - [Inspecting sourcecode for URLs opening only on mobile](#inspecting-source-code-for-urls-opening-only-on-mobile)
- [Smishing URL and malware APK collection](#collection-of-some-malicious-urls-and-apks-spread-by-smishing)
- [SMS Phishing campaigns Collection](#sms-phishing-campaigns-collection)
- [Phishing Kit Dissection](#phishing-kit-dissection)

## Check redirection of various shortened URLs without clicking on the URL (credits: [aware-online](https://www.aware-online.com/en/investigate-shortened-urls/))

### Manually 

<img src="https://github.com/reportsmishing/knowledgebase/blob/main/images/shortenedurls.png" width="400"/>

### Free Website to unshorten URL: [unshorten.it](https://unshorten.it)

<img src="https://github.com/reportsmishing/knowledgebase/blob/main/images/unshorten.png" width="400"/>

### Fancy command line? Use cURL:

```
curl -i <shortened URL>
```

## Investigating URL Shorteners

A fantastic resource on URL shorteners is created by [URLTeam](https://wiki.archiveteam.org/index.php/URLTeam).

### [shrtco.de](https://shrtco.de/) shortened URLs

```
https://api.shrtco.de/v2/info?code=<enter code>
```

### [rb.gy](https://rebrandly.com/) shortened URLs

```
https://app.rebrandly.com/public/links/share?href=<enter rb.gy link with code>
```

### [cutt.ly](https://cutt.ly) shortened URLs

```
https://cutt.ly/<short code>-stats
```

### [is.gd/v.gd](https://is.gd/developers.php) shortened URLs

```
https://is.gd/forward.php?format=json&callback=myfunction&shorturl=<short-code or shortened URL>
```

### [t.ly](https://t.ly/) shortened URLs

```
https://t.ly/stats?url=<shortened URL>
```

## Investigations for smishing URLs (credits: [maltego](https://www.maltego.com/blog/phishing-attacks-part-2-investigating-phishing-domains/))

<img src="https://github.com/reportsmishing/knowledgebase/blob/main/images/infographic-phishing.png" width="400"/>

### Blogs on SMS Phishing investigation

* [Investigating SMS phishing](https://blog.bushidotoken.net/2023/07/investigating-sms-phishing-text.html) by [@BushidoToken](https://twitter.com/BushidoToken)

### Public Codebase to investigate smishing URLs

[Scripts to investigate smishing URLs](https://github.com/reportsmishing/public_code)

### Inspecting source code for URLs opening only on mobile

[Using safari and physical iPhone](https://appletoolbox.com/use-web-inspector-debug-mobile-safari/#Use_Web_Inspector_to_debug_mobile_Safari)

One can also simply use an iPhone simulator through Xcode and use the web inspector debug using safari.

<img src="https://github.com/reportsmishing/knowledgebase/blob/main/images/xcode_simulator.png" width="300"/> <img src="https://github.com/reportsmishing/knowledgebase/blob/main/images/develop_simulator.png" width="500"/>

## Collection of some malicious URLs and APKs spread by Smishing

[Virustotal collection of smishing URLs and malware APKs spread through smishing](https://www.virustotal.com/gui/user/cybergeekop/collections)

### Phishing kit dissection

[NHS Monkeypox phishing kit](https://twitter.com/i/events/1568165527406649344) by [@jcybersec](https://twitter.com/JCyberSec_)

### SMS Phishing campaigns collection

[SMS Phishing Campaigns](https://twitter.com/i/events/1567921325720670209) by [@jcybersec](https://twitter.com/JCyberSec_)


## 🙏 Support

![Twitter URL](https://img.shields.io/twitter/url?style=social&url=https%3A%2F%2Fgithub.com%2Freportsmishing%2Fknowledgebase)
<br>
[![](https://img.shields.io/static/v1?label=Sponsor&message=%E2%9D%A4&logo=GitHub&color=%23fe8e86)](https://github.com/sponsors/reportsmishing)

<hr>
<p align="center">
Developed with ❤️
</p>
