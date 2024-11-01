=== WordUP-Login ===
Contributors: Luksoverse
Donate link: https://luksoverse.io/donations/
Tags: LUKSO, Luksoverse, Metaverse, Universal Profiles, Web3
Requires at least: 4.7
Tested up to: 6.0
Stable tag: 1.0
Requires PHP: 7.0
License: GPLv3
License URI: https://www.gnu.org/licenses/gpl-3.0.en.html

Here is a short description of the plugin.  This should be no more than 150 characters.  No markup here.

== Description ==
Bringing the possibility to login with Universal Profiles to the mass.

Around 40% of all websites worldwide are powered by the WordPress system and it is the most popular Content Management System (CMS) in the world with 63% of all CMS websites. We did built a free plugin for in the WordPress appstore what makes it possible for all those websites to implement Universal Profiles in about 3 clicks.

In future releases we want to work on:

- Have a better and smoother flow
- Implement more functions
- Have the option to make login with UP the only possible login method

== Frequently Asked Questions ==

== Screenshots ==

1. [https://github.com/JordyDutch/Luksoverse-picture-hosting/blob/main/Screen%20Shot%202022-10-06%20at%2016.26.16.png?raw=true  This is how your login screen will look like.]


[youtube https://youtu.be/ZeLROKA9RJc]

== Changelog ==

= 1.0 =
First version of our plugin.


== Upgrade Notice ==


== How does it work ==

Note: We only support Google Chrome for now.

- We created a WordPress login plugin for Universal Profiles, it will be available soon in the WordPress appstore and free to download and use on all WordPress based websites.

- The plugin asks you to connect your Universal Profiles account to the WordPress website and let you sign a random nonce.

- The plugin takes your username, profile picture and UP address to your WordPress account.

- You can register a new account by only using Universal Profiles or you can connect your Universal Profile to your existing account in the `Connect UP` menu on the WordPress dashboard.

- In the `Connect UP` menu on the WordPress dashboard you can also discconect your Universal Profile from your account.

- You can only register your Universal Profile on 1 WordPress account on the same website.


## User-manual

### New user

1. Make sure you have installed the [Universal Profiles web-extension](https://docs.lukso.tech/guides/browser-extension/install-browser-extension/)

2. Are you a new user of https://luksoverse.io/, go to the homepage and click `register`

3. You wil now register a new account with your Universal Profile

4. From now on you can use the `login` button to login to the website

For any other WordPress website it will be the same, but you have to go to websitedomain.com/wp-login.php (For example: https://luksoverse.io/wp-login.php)

Or

Ask the WordPress website owner to implement our HTML shortcode in his login system.

### Existing user

1. Make sure you have installed the [Universal Profiles web-extension](https://docs.lukso.tech/guides/browser-extension/install-browser-extension/)
2. Go to https://luksoverse.io/wp-login.php
3. Login with your username and password
4. Go to the `Connect UP` menu on the WordPress dashboard
5. Connect your Universal Profile to your account
6. Now you can use the login button on the homepage or on https://luksoverse.io/wp-login.php

For any other WordPress website it will be the same, but you have to go to websitedomain.com/wp-login.php (For example: https://luksoverse.io/wp-login.php)

Or

Ask the WordPress website owner to implement our HTML shortcode in his login system.

### WordPress website

Do you own a WordPress and do you want to replace your website login system with Universal profiles? Follow the next steps:

1. Download the WordUP! Login plugin from the WordPress appstore and activate it on your website.

Your login system on /wp-login.php has now changed to a system where you can choose to do a normal login or login with Universal Profiles

2. Provide the steps above to your users to let them login with Universal Profiles to your website.

3. Optionally you can add our HTML shortcode `[lukso_wp_login]` to your homepage to create a UP login there.
