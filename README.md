# Zimbra
In this Repository you will find different Zimbra Scripts for install Zimbra Collaboration on an automated way

# ZimbraEasyInstall
##What is the ZimbraEasyInstall
This Script install and configures bind9 with the domain and IP that is defined while invoke the command. After that the Scripts prepare the keystroke script with a default installation of Zimbra Collaboration 8.6 (without dnscache) and the config.defaults script, using the domain, IP and password that is defined while invoke the command. Once everything is ready the Script download the latest version of Zimbra Collaboration 8.6, uncompress it and install it using the keystrokes script and the config script.

##Advantages of use the Script
 * Time saving
 * Fully automated
 * Easy to use
 * Good for a quick Zimbra Preview

##Usage and Example
The ZimbraEasyInstall Script is an easy way to install Zimbra Collaboration, without be worry of the DNS configuration, OS depencies, etc. Just execute it and after a few minutes have Zimbra up and running.

Just run the Script adding the TLD domain for your Zimbra Collaboration server, the IP of the DNS server (usually will be the same of the server, but instead you are using different eth interfaces), and add the password for the Zimbra Collaboration server.
```bash
./ZimbraEasyInstall-8.8.15 zimbra.io 192.168.211.40 Zimbra2020
```
##Access to the Web Client and Admin Console
The Script will take care of everything and after a few minutes you can go to the IP of your server and use the next URL:
 * Web Client - https://YOURIP
 * Admin Console - https://YOURIP:7071

## ZimbraEasyInstall-8.8.15
If you want to deploy the latest version of Zimbra, ZCS 8.8.15, now you can, with the new Script ready for ZCS 8.8.15
##Usage and Example
The ZimbraEasyInstall Script is an easy way to install Zimbra Collaboration, without be worry of the DNS configuration, OS depencies, etc. Just execute it and after a few minutes have Zimbra up and running.

Just run the Script adding the TLD domain for your Zimbra Collaboration server, the IP of the DNS server (usually will be the same of the server, but instead you are using different eth interfaces), and add the password for the Zimbra Collaboration server.
```bash
./ZimbraEasyInstall-8.8.15 zimbra.io 192.168.211.40 Zimbra2017
```
##Access to the Web Client and Admin Console
The Script will take care of everything and after a few minutes you can go to the IP of your server and use the next URL:
 * Web Client - https://YOURIP
 * Admin Console - https://YOURIP:7071

## Distributed under MIT license
Copyright (c) 2017 Jorge de la Cruz

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
