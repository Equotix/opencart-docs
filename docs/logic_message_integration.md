# Logic Message Integration

* Current Version: 2.0.1
* Last Updated: 19 December 2017
* License: [Commercial License][1]
* Compatibility: OpenCart 1.5.1.x, 1.5.2.x, 1.5.3.x, 1.5.4.x, 1.5.5.x, 1.5.6.x, 2.x, 3.x


[1]: https://www.marketinsg.com/usage-license

## Description

Logic Message integration allows you to send SMS messages from your OpenCart store using Logic Message. Notify your customers of their order status update, welcome them to your store, or send them an order confirmation SMS. 

Note: A Logic Message ([https://www.logicmessage.com][2]) account is required to send SMS messages.

## Features

* Integration with Logic Message
* Setup different SMS notification templates
* Setup different templates depending on the country of the receiving number
* Setup different sender number for the templates

## Installation

### OpenCart Cloud

1. Purchase the extension from your administration panel.
2. Proceed to `Extensions >> Extensions` and select `Modules`. Then, install `Logic Message Integration`. Configure extension accordingly.
3. Proceed to `Extensions >> Modifications` and click the blue refresh button.
4. The prices on the product page should now automatically update.

### OpenCart 3

1. Go to `Admin >> Extensions >> Installer` to upload the extension zip file.
2. Proceed to `Extensions >> Extensions` and select `Modules`. Then, install `Logic Message Integration`. Configure extension accordingly.
3. Proceed to `Extensions >> Modifications` and click the blue refresh button.
4. If you do not have a Logic Message account, you can sign up at [https://www.logicmessage.com][2].

### OpenCart 1.5 & 2

1. Unzip the files. Ensure that vQmod has been installed.
2. Upload the files WITHIN the upload folder to your OpenCart installation folder with a FTP client. The folders should merge.
3. In your admin panel, proceed to `Extensions >> Modules`. Then, install `Logic Message Integration`. Configure extension accordingly.
4. If you do not have a Logic Message account, you can sign up at [https://www.logicmessage.com][2].

[2]: https://www.logicmessage.com

## Configurations

### OpenCart 1.5, 2, 3 & Cloud

1. Auth Key

	You can retrieve your auth key from your Logic Message account (API Applications).

2. Auth Secret

	You can retrieve your auth secret from your Logic Message account (API Applications).

3. Default Country Prefix

	Enter the default country code for telephone numbers that do not have a country code entered. Numbers without a matching country code will have this country prefix added.

4. Debug

	Log API integration message sent from Logic Message into the OpenCart error logs.

5. Sender

	Sender ID entered must be a number / ID already linked to your Logic Message account.


## Change Log

### Version 2.0.1 (19/12/2017)
* Fixed minor bugs
### Version 2.0.0 (14/07/2017)
* Fixed compatibility with OpenCart 3.0.0.0
* Minor improvements and updates
### Version 1.0.4 (10/10/2016)
* Fixed missing auto increment for database table
### Version 1.0.3 (29/09/2016)
* Rebranded to Logic Message
### Version 1.0.2 (18/08/2016)
* Fixed critical bugs