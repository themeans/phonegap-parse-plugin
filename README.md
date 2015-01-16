Phonegap Parse.com Plugin
=========================

Phonegap 3.0.0 plugin for Parse.com push service with Parse.framework updated to Version 1.6.1.

** Fixes issues with FBTokenInformationTokenKey & ACAccountTypeIdentifierTwitter.

Using [Parse.com's](http://parse.com) REST API for push requires the installation id, which isn't available in JS

This plugin exposes the four native Android API push services to JS:
* <a href="https://www.parse.com/docs/android/api/com/parse/ParseInstallation.html#getInstallationId()">getInstallationId</a>
* <a href="https://www.parse.com/docs/android/api/com/parse/PushService.html#getSubscriptions(android.content.Context)">getSubscriptions</a>
* <a href="https://www.parse.com/docs/android/api/com/parse/PushService.html#subscribe(android.content.Context, java.lang.String, java.lang.Class, int)">subscribe</a>
* <a href="https://www.parse.com/docs/android/api/com/parse/PushService.html#unsubscribe(android.content.Context, java.lang.String)">unsubscribe</a>

Installation
------------

Pick one of these two commands:

```
phonegap local plugin add https://github.com/xaun/phonegap-parse-plugin.git
cordova plugin add https://github.com/xaun/phonegap-parse-plugin.git
grunt plugin:add:https://github.com/xaun/phonegap-parse-plugin.git
```

