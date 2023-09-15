---
icon: home
label: Home
---

![](static/sa-rapid7-hero.webp)

# Welcome to the Docs!

The SA-Rapid7Assets add-on allows Splunk Enterprise Security admins to use [Rapid7 <small>:icon-link-external:</small>][r7]{ target="blank" } asset data with the Asset Database. This documentation will cover the components used in the add-on and advanced configurations. 

!!!danger Important
This Supporting add-on is only intended to work with [Splunk Enterprise Security <small>:icon-link-external:</small>](https://splunkbase.splunk.com/app/263){ target="blank" } deployments.
!!!

> __*Disclaimer*__
> 
> *This Splunk Supporting Add-on is __not__ affiliated with [__Rapid7 LLC__ <small>:icon-link-external:</small>][r7]{ target="blank" } and is not sponsored or sanctioned by the Rapid7 team. Please visit [https://www.rapid7.com/ <small>:icon-link-external:</small>][r7]{ target="blank" } for more information about Rapid7.*

## Assumptions

This documentation assumes the following:

1. You have a working Splunk Enterprise Security environment. __This add-on is not intended to work without Splunk ES.__
2. You already have Rapid7 asset data ingested using the [Rapid7 InsightVM Technology Add-On <small>:icon-link-external:</small>](https://splunkbase.splunk.com/app/5097){ target="blank" }.
3. Familiarity with setting up a new Asset source in Enterprise Security.

## About

Info | Description
------|----------
SA-Rapid7Assets | 1.0.2 - [Splunkbase <small>:icon-link-external:</small>](https://splunkbase.splunk.com/app/7025){ target="blank" } \| [GitHub <small>:icon-link-external:</small>](https://github.com/ZachChristensen28/SA-Rapid7Assets/releases/){ target="blank" }
Splunk Enterprise Security Version <small>(Required)</small> | [7.x \| 6.x <small>:icon-link-external:</small>](https://splunkbase.splunk.com/app/263){ target="blank" }
Rapid7 InsightVM Technology Add-On <small>(Required)</small> | [>=1.3.2 <small>:icon-link-external:</small>](https://splunkbase.splunk.com/app/5097){ target="blank" }
Add-on has a web UI | No, this add-on does not contain views.

[r7]: https://www.rapid7.com/
