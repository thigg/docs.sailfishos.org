---
title: HowTo
permalink: HowTo/
nav_exclude: true
layout: default
---

This contains how to documentation about checking features or information from Sailfish OS.

## Check Open Source Licenses

Easiest way to check licenses is to go to **Settings > About product** and scroll a bit down and click "see information about packages" which takes you to the list of packages with licenses and shows you all the open source licenses.

If you have AppSupport installed you can check open source licenses related to AppSupport at **Settings > Android<sup>TM</sup> App Support > Show licences**

You can also use following command in terminal in case you have developer mode installed:
```
rpm -qa --queryformat '%{license}\t%{name}-%{version}-%{release}\n'
```

