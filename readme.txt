=== wpRTC - WebRTC for WordPress ===
Contributors: guavaworks, michalbluma, michaelbeil
Donate link: http://www.codingofficehours.com/coh/#/teacher/23
Tags: webrtc, video, video chat, webcam
Requires at least: 4.0
Tested up to: 4.3.1
Stable tag: 2.0.1
License: GPLv3 or later
License URI: http://www.gnu.org/licenses/gpl-3.0.html

WebRTC for WordPress allows you to easily create a video chat room utilizing webRTC, which is supported by most of the latest versions of modern browsers.

== Description ==
  
WebRTC or Web Real Time Communication is an open project that enables browsers with RTC capabilities to connect with video, audio, and screen sharing.  
  
Install the plugin and use the simple shortcode `[wpRTC room_name="room"]` to create multiple rooms for users to interact with each other using video.

[Documentation](http://roysivan.com/wp-webrtc) available, please check it for shortcode use, and wpRTC Pro version tips.
  
[IceComm.io](http://icecomm.io/) is a free (up to 50 unique concurrent visitors) library which powers wpRTC. It is free to sign up and is required as of v2.0

== Installation ==

1. Download zipped archive of plugin
1. Log into your WordPress dashboard and add the new plugin via upload
1. Activate the plugin
1. Click on wpRTC in your menu (below "Settings") to see shortcode settings and styling options
1. You will need an icecomm.io account.


== Frequently Asked Questions ==

= What is WebRTC? =
[WebRTC](http://www.webrtc.org) WebRTC is a free, open project that enables web browsers with Real-Time Communication (RTC) capabilities via simple JavaScript APIs. The WebRTC components have been optimized to best serve this purpose.

= I installed it, but only see a black screen =
If you have the plugin installed and tried using the shortcode and only see a black screen, make sure you remember to give your browser permission. Here's a [screenshot of permissions on Chrome](http://roysivan.com/wp-webrtc/videoPermission.png).

= What is IceComm.io, why do I need it? =
IceComm is the cross-browser library that supports the in-browser video chatroom. WPRTC required IceComm as of v2 due to problems with TURN servers not being configured properly creating a cross between users. If you have your own TURN servers you can modify the IceComm global settings to include your TURN server. IceComm is 100% free up to 50 concurrent unique visitors, or 50 active video chatroom participants at the same time.


== Screenshots ==
  
1. Make sure to check the newly added menu for updates, tips, and settings.
2. Styling options are still being added, style the video player any way you want it!

== Changelog ==

= 2.0 =
* New webRTC library

= 1.1 =
* Added Video Mute
  
= 1.0.1 =
* Upgrade to version 1
* Documentation update
* Settings updates

= 0.1 =
* Shortcode and initial build
