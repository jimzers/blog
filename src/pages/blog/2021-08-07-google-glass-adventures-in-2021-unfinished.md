---
templateKey: blog-post
title: Google Glass Adventures in 2021 <Unfinished>
date: 2021-08-07T08:35:16.169Z
description: Debugging and the state of Google Glass in 2021
featuredpost: false
featuredimage: /img/products-grid2.jpg
tags:
  - tech
  - debugging
  - google glass
  - pain
---
Hi internet!

Recently I got a Google Glass. A professor of mine had a few Glasses lying around their lab, and was kind enough to give one to me.

It's been something I wanted to try when I was younger, so it was pretty cool wearing one.

Here's a picture of the Google Glass (Explorer Edition). The case is pretty nice: The bottom of the bag is a hard shell, so the glasses don't get crushed when storing the bag in a crammed backpack.

![Picture of a Google Glass and case](/img/20210807_170801.jpg "Picture of a Google Glass and case")

There's a camera on the outside, and on the top is a button you can press to take photos.

![](/img/20210807_170824.jpg)

There's also a camera on the inside. There's a neat "wink" feature that detects when you wink your eyes and takes a photo. The inner camera helps detect this. The power button is on the far right of the picture.

![](/img/20210807_170912.jpg)





So the first thing I did was to factory reset the sucker. Biggest mistake ever. Turns out you need to login with your Google account in order to use the Glass. Problem is, you gotta go through Google's Glass-specific servers. Unfortunately, these were discontinued after Google decided to focus solely on enterprise usage for the Glass (see "Enterprise" edition).

Luckily, Google does provide a wifi-free method to use your Glass - and it involves a bit of elbow grease. Google's final update to the Glass gets rid of all the Google services, and basically turns the Glass into an Android machine with a nice screen and camera.

In order to update the device to this version without wifi, I had to "flash" my Glass. As a technical reference to anyone stuck on this step:

Note: Before starting, make sure you have the Android tools `adb` and `fastboot` installed. You can find some pretty good guides online. Also install Android Studio if you want to do any development work.

1. Press and hold the power button until your Glass turns off.

2. Press and hold both the power button and camera button. Keep holding onto the camera button until you reach a blue screen with a caution triangle (pictured below)

TODO: Finish steps...

3. Plug in your Glass to your computer. Run `fastboot `

4. Go to the fastboot option and select it.





As a quick warning to anyone looking to get a Glass off eBay, the Google Glass won't work with iPhones anymore. The connection app isn't listed on the App Store anymore.



I first learned about the 



Outline:

1. Background story
2. Specs and pictures of the Google Glass
3. Factory reset
4. Software
5. Future plans
6. Helpful links