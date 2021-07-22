---
layout: post
lang: en
template: English
date: 2021-07-22
timezone: 8
tags: []
ja: []
zh-Hans: []
zh-Hant: []
title: New features of Twidere X 1.4.0
location: Toyama,Japan
type: ''
image: "{{ site.baseurl_root }}/uploads/popover-1.png"

---
![popover.png](https://i.loli.net/2021/07/22/PrcyxGqwSeFHDTk.png)

Since 1.3.0, there have been many improvements and updates made on Twidere X. And now, the latest version 1.4.0 has been released, it can be viewed in the Github and Google Play beta channels.

Github 1.4.0 (https://github.com/TwidereProject/TwidereX-Android/releases/tag/1.4.0)

Now, let’s see the amazing **new features** in this version.

**The updated release format:**

Twidere X has provided the .aab installation package in Google Play and Github starting from version 1.3.0 This new mode can reduce the size of the application, download time, and free up the space the application occupies on the device.

For more introduction and details about the .aab installation package, please refer to this [link](https://medium.com/googleplaydev/what-a-new-publishing-format-means-for-the-future-of-android-2e34981793a).

**Twitter DM (Direct Message) support:**

Now you can send a private message to the person you want directly on his/her profile page.

In the sidebar, you can find the :envelope_with_arrow: Messages button, where you will see the sending history and create a new private message. Once you receive a private message, you will also get a notification .

![208345761.png](https://vip1.loli.io/2021/07/21/xaCO4Db5tZITSUf.png)

**Notification:**

Now you can choose the account you want to receive push notifications in Settings-Notifications and in which messages you want to push.

If there’s a new private message or new mention in Twitter, you will receive a new notification. And it also works if there’s a new content notification in Mastodon (Tips: You can choose to send private messages only).

![20210721164016.png](https://vip1.loli.io/2021/07/21/BNK9rgwm8iMpjQU.png)

**The improvement of Twitter thread :**

Enter the appropriate Nitter Instance in Settings-Misc to enable it, and it is available for private tweets. We also provide UI adjustments for better display.

Here is a page (https://github.com/zedeus/nitter/wiki/Instances) of possible Nitter Instances, choose one of them and paste it to Settings-Misc to have a try.

\*Due to the limitation of Twitter API, some data might not be able to be fetched from Twitter, you can use a third-party data provider to provide this data. Twidere does not take any responsibility for them.

**Twitter trends:**

You can view Twitter trends in the search tab now. We only support Worldwide trends at the moment, and will continue to develop this part of the function in the future.

![20210721171036.png](https://vip2.loli.io/2021/07/21/NMk26GYCIVLoncK.png)

**New options of scrolling timeline:**

Now you can hide the FAB/tab/bottom bar when scrolling the timeline. We have also improved the processing of the timeline interruption area. After refreshing the timeline, it will remain in the original reading position.

![20210721165158.png](https://vip2.loli.io/2021/07/21/LmNxVBo7qgXFJSv.png)

**Sending threads:**

Now you can send threads by enabling thread mode in the compose page.

Enable this button when you want to tweet threads.

![20210721171457.png](https://vip1.loli.io/2021/07/21/boDSkFuHgOtEKU4.png)

**Pure dark mode:**

The dark mode is now available and you can open the AMOLED optimized mod to make the pure dark.

Settings - Appearance - Dark - AMOLED optimized mod to active it.

This theme is very useful for devices using AMOLED screens, I believe you will like this mode.

![20210721165907.png](https://vip1.loli.io/2021/07/21/N2lxFadpf4HQuzB.png)

**The update also includes:**

* Fido key and password manager can be used when you log in
* Fix input cursor color in compose page
* Upgrade Jetpack Compose to RC01

The official version to 1.4.0 is available now, including [F-Droid](https://f-droid.org/zh_Hans/packages/com.twidere.twiderex/), [Github](https://github.com/TwidereProject/TwidereX-Android/releases) and [Google Play](https://play.google.com/store/apps/details?id=com.twidere.twiderex). Enjoy Twidere X 1.4.0 for Android !