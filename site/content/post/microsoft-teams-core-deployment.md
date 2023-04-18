---
title: Microsoft Teams - Core deployment
date: 2023-04-18T19:07:41.586Z
description: >-
  Teams provides a set of custom administrator roles that can be used to manage
  Teams for your organization. The roles provide various capabilities to
  administrators.

  A small change...
image: https://www.computerworld.ch/img/1/6/7/8/6/8/3/Swisscom_Gebaeude_Logo_auschnitt_bild-pd_w960_h721.jpg
---
### 7.1.1	Administrators

Teams provides a set of custom administrator roles that can be used to manage Teams for your organization. The roles provide various capabilities to administrators.

### 7.1.2	Office 365 URL’s and IP address ranges

Before scaling your voice deployment across your organization, take time to review and confirm that your environment is ready to provide users with the best possible experience.
To get the best experience on Teams, your organization must have deployed Exchange Online and SharePoint Online, and you must have a verified domain for O365 such as contoso.com.
To scale calls and meetings across your organization you should ensure that all user locations have internet access to connect to the Office 365 Services. At a minimum you should make sure that the following common ports are open to the internet from your user's locations:-

* TCP ports 80 and 443 outgoing from clients that will use Teams
* UDP ports 3478 through 3481 outgoing from clients that will use Teams

Microsoft 365 and Office 365 URLs and IP address ranges

### 7.2	Chat, teams and channels

Teams provides a great out-of-the-box collaboration experience for your organization, and most organizations find that the default settings work for them. This chapter helps you decide whether to change any of the default settings, based on your organization's profile and business requirements, then it walks you through each change.
Chat, teams, channels, & apps in Microsoft Teams - Microsoft Teams | Microsoft Docs