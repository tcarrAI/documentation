---
title: Session and Cookie Handling
description: Details about configuring settings for session expiration and cookies.
categories: [developing]
tags: [code, debug]
keywords: drupal, session expiration, cookie lifetime, session,
---
Pantheon allows developers to control the length of sessions. There are two pieces; the lifetime of the cookie and the lifetime of the session itself.  

The cookie lifetime is configured using the PHP setting [session.cookie\_lifetime](http://www.php.net/manual/en/session.configuration.php#ini.session.cookie-lifetime). If set to 0, the cookie is deleted when the user closes their browser. Set to 2,000,000 seconds in Drupal's default.settings.php and in Pantheon's PHP configuration.  

