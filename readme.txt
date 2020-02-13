=== Plugin Name ===
Contributors: Josh Daniel
Company link: https://www.coriunder.com
Tags: Coriunder, direct, redirect, form, woocommerce, woothemes
Requires at least: 3.5.1
Tested up to: 3.9.0
Stable tag: 0.1.7.1

WooCommerce PSP Direct Payment Gateway

== Description ==

PSP Direct payment gateway for Woocommerce.  Once installed, you can configure this through Woocommerce Payment Gateways tab.

Enable the payment gateway and apply your unique Merchant Number provided by PSP.


For direct (and not redirect) process method:
As with all direct payment gateways where your customer doesn't leave your website, 
you will need a valid SSL certificate and PCI DSS certification.


Tested with WooCommerce version 2.0.20 and compatible with version 2.1

== Installation ==
Installation :

1. Download.

2. Upload to your /wp-contents/plugins/ directory.

3. Activate the plugin through the 'Plugins' menu in WordPress.

4. Goto Woocommerce -> Settings and select the Payment Gateways tab and click on PSP Direct just below the tabs.

Configure Gateway:

1. Add your 'Merchant Number ' which would have been supplied by PSP.

2. configure other processing options on this page

== Frequently Asked Questions ==
= Does it support 3D Secure =
Yes it does, to enable it you first need to contact PSP and then set Process method to "Use PaymentPage Redirection".

== Screenshots ==
1. PSP Direct settings screen
2. Customer payment page

== Changelog ==
= Version 0.9.0.0 - 25042014 =
* Feature - Initial release
= Version 0.9.0.5 - 04022016 =
* Feature - small updates