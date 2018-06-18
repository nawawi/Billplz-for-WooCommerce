=== Billplz for WooCommerce ===
Contributors: wanzulnet
Tags: billplz,paymentgateway,fpx,malaysia
Tested up to: 4.9.6
Stable tag: 3.19.0
Donate link: http://billplz.com/join/lz7pmrxa45tiihvqdydxqq/
Requires at least: 4.3
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html
Requires PHP: 5.6

Accept Internet Banking Payment by using Billplz. 

== Description ==
Install this plugin to accept payment using Billplz (Maybank2u, CIMB Clicks, Bank Islam, FPX). 

== Upgrade Notice == 

WARNING! THIS UPDATE MAY BREAK YOUR SITE!

Please re-configure the plugin if you upgrading from version 3.14 or ealier
1. Make sure your PHP Version is : 5.6/7.0/7.1
2. Set X Signature Key

== Screenshots ==
* Installing Billplz for WooCommerce
* Activate plugin after installation
* Set API Secret Key and X Signature Key
* Enable X Signature Key at [Billplz Account Settings](https://www.billplz.com/enterprise/setting)

== Changelog ==

= 3.19.0 =

* NEW: Added warning for update to the next major release 3.20.x

= 3.18 =

* IMPROVED: Bills will not be created twice in some circumstances

== Installation ==

**Step 1:**

- Login to your *WordPress Dashboard*
- Navigate to **Plugins >> Add New**
- Search **Billplz for WooCommerce >> Install Now**

**Step 2:**

- Activate Plugin

**Step 3:**

- Navigate to **WooCommerce >> Settings >> Checkout >> Billplz**
- Insert your **API Secret Key** and **X Signature Key**
- Save changes

== Frequently Asked Questions ==


= Where can I get API Secret Key? =

You can the API Secret Key at your Billplz Account Settings. [Get it here](https://www.billplz.com/enterprise/setting)

= Where can I get X Signature Key? =

You can the X Signature Key at your Billplz Account Settings. [Get it here](https://www.billplz.com/enterprise/setting)

= Troubleshooting =

1. If you are not getting a **Callback/Redirect** response from Billplz:

	Please make sure you have **Tick "Enable XSignature Payment Completion"** on Billplz Account Settings and make sure you have set your **X Signature Key**.
	
2. If you want both Email & Phone Number to be captured on Bills:

	Set Notification settings to **No Notification** or **Both**	

== Links ==
[Sign Up](http://billplz.com/join/lz7pmrxa45tiihvqdydxqq/) for Billplz account to accept payment using Billplz now!
