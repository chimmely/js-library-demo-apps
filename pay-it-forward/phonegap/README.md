# PhoneGap & Kinvey
## Cross platform frontend + Scalable cloud backend

This repository contains the Pay It Forward sample application, which uses PhoneGap and Kinvey. The Pay It Forward application is a simplified version of the [#RubyRiot](http://www.kinvey.com/blog/itemlist/tag/Ruby%20Riot) app built by Kinvey in January 2012. The goal of the app is to make it very easy for conference attendees to connect, and to introduce each other to new people.

### Kinvey features in this app
* Facebook integration
* caching, offline usage and data syncing
* push notifications
* data [persistence](http://docs.kinvey.com/js-developers-guide.html#appdata)

### Set up
In `assets/www/scripts/app.js`, replace `<your-app-key>` and `<your-app-secret>` (lines 9–10) with your application credentials. On line 13, enter your Facebook App Id. For Push Notifications to work, [enable push](http://docs.kinvey.com/service-overview.html#push) for your app through the console. In `assets/airshipconfig.properties`, replace `<your-push-key>` and `<your-push-secret>` with your push credentials.

### What’s next?
* Download the [Kinvey JavaScript Library](https://console.kinvey.com/#downloads).
* Follow the [PhoneGap tutorial](http://docs.kinvey.com/js-phonegap-tutorial.html) for using Kinvey with PhoneGap.
* Learn more about our APIs in the [JavaScript Developer’s Guide](http://docs.kinvey.com/js-developers-guide.html).