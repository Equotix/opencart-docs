# Two Factor Authentication (SMS)

* Current Version: 2.0.0
* Last Updated: 14 July 2017
* License: [Commercial License][1]
* Compatibility: OpenCart 1.5.1.x, 1.5.2.x, 1.5.3.x, 1.5.4.x, 1.5.5.x, 1.5.6.x, 2.x, 3.x


[1]: https://www.marketinsg.com/usage-license

## Description

Two Factor Authentication (SMS) allows you to setup 2FA security for your customers’ accounts. A OTP SMS will be sent to the customer’s mobile phone number and the customer has to enter the OTP to login to view his account details on your store.

Note: A Logic Message ([https://www.logicmessage.com][2]) account is required to send SMSes.

[2]: https://www.logicmessage.com

## Features

* Send OTP SMS to customer when they login
* Customers with invalid phone number will be allowed to login without verification
* Configurable OTP SMS template

## Installation

### OpenCart Cloud

1. Purchase the extension from your administration panel.
2. Proceed to `Extensions >> Extensions` and select `Modules`. Then, install `Two Factor Authentication (SMS)`. Configure extension accordingly.
3. Please view configuration details below.

### OpenCart 3

1. Go to `Admin >> Extensions >> Installer` to upload the extension zip file.
2. Proceed to `Extensions >> Extensions` and select `Modules`. Then, install `Two Factor Authentication (SMS)`. Configure extension accordingly.
3. Please view configuration details below.

### OpenCart 1.5 & 2

1. Unzip the files. Ensure that vQmod has been installed.
2. Upload the files WITHIN the upload folder to your OpenCart installation folder with a FTP client. The folders should merge.
3. In your admin panel, proceed to `Extensions >> Modules`. Then, install `Two Factor Authentication (SMS)`. Configure extension accordingly.
4. Please view configuration details below.

## Configurations

### OpenCart 1.5, 2, 3 & Cloud

1. Sender

	Enter the purchased phone number or personalised sender ID you have in your Logic Message account.

2. Auth Key & Auth Secret

	Enter the auth key and auth secret you have from the Logic Message API Application you have created.

3. Default Country Prefix

	If the phone number customer is using is not a valid number, the default country prefix will be appended to the customer's phone number before sending an SMS.

## Change Log

### Version 2.0.0 (14/07/2017)
* Fixed compatibility with OpenCart 3.0.0.0
* Minor improvements and updates
* Added ability to remove leading zeroes
### Version 1.0.1 (26/01/2017)
* Fixed minor bugs
### Version 1.0.0 (06/01/2017)
* Module released.