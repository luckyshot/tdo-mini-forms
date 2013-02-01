#TDO Mini Forms Wordpress Plugin

## IMPORTANT

> TDO Mini Forms is a Wordpress plugin developed by [Mark Cunningham](http://thedeadone.net/) ( [@thedeadone](https://twitter.com/thedeadone) ) some time ago. It is a fantastic free plugin but a security vulnerability was detected in the Upload File functionality where a user could upload a PHP file with an image extension and then execute this file, more info in (Mark's post)[http://thedeadone.net/blog/where-has-tdo-mini-forms-plugin-gone/]. For this to happen, a server would need to be configured to allow image file types to execute as code, a very bad idea and something usually no one would ever do. 

***

**If you are unsure on the above, do NOT use the plugin.**

***

## Purpose of this repository

The purpose of this repository is to fix the vulnerabilities and keep it as up-to-date as possible. Mark hasn't got time to work on it so I hoped by making a centralized Git project we can all push commits and keep it up to date. 

Feel free to send any push requests with your improvements.

### Changelog
#### 01 Feb 2013
- First commit of the plugin version 0.13.9 (last one I could find)
- Updated reCaptcha library to point to Google's servers
