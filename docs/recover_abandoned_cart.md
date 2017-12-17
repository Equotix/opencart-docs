# Recover Abanadoned Cart

* Current Version: 2.1.0
* Last Updated: 17 December 2017
* License: [Commercial License][1]
* Compatibility: OpenCart 1.5.1.x, 1.5.2.x, 1.5.3.x, 1.5.4.x, 1.5.5.x, 1.5.6.x, 2.x, 3.x


[1]: https://www.marketinsg.com/usage-license

## Description

Many of our customers leave before completing their orders due to various reasons. Recover Abandoned Carts is here to assist you in contacting your customers that left after adding items to their shopping cart without completing the order.

## Features

* Track abandoned carts on your website for both guest and registered customers
* Track customer’s duration on your website with items in cart
* Track customer’s last visited page
* Track customer’s IP address
* Capture customer’s information if available
* View abandoned carts from one single page
* Automatically send reminder emails to customer
* Multi-language support
* Multi-store support
* Set up multiple email templates to remind customers
* Generate unique coupon for customer along with the email
* Set coupon validity duration
* Rich text editor for writing email template
* Automatically delete stored abandoned cart after reminding customer
* Allow customers to unsubscribe from your reminder emails
* View statistics and report
* Allow customer to restore their cart items with a single click


## Installation

### OpenCart Cloud

1. Purchase the extension from your administration panel.
2. Proceed to `Extensions >> Extensions` and select `Modules`. Then, install `Recover Abandoned Cart`. Configure extension accordingly.
3. Proceed to `Extensions >> Modifications` and click the blue refresh button.

### OpenCart 3

1. Go to `Admin >> Extensions >> Installer` to upload the extension zip file.
2. Proceed to `Extensions >> Extensions` and select `Modules`. Then, install `Recover Abandoned Cart`. Configure extension accordingly.
3. Proceed to `Extensions >> Modifications` and click the blue refresh button.

### OpenCart 1.5 & 2

1. Unzip the files. Ensure that vQmod has been installed.
2. Upload the files WITHIN the upload folder to your OpenCart installation folder with a FTP client. The folders should merge.
3. In your admin panel, proceed to `Extensions >> Modules`. Then, install `Recover Abandoned Cart`. Configure extension accordingly.

## Configurations

### OpenCart 1.5, 2, 3 & Cloud

1. Setting Up Cron Job

	Please choose an option from the below to setup the automation of sending emails.

	a. My server supports cron job

	Use the cron job command provided in the module for your convenience. Add it to your server to run daily.

	b. My server does not support cron job

	Use an external service like EasyCron or SetCronJob to trigger the cron job URL. Cron job URL has been provided in the module for your convenience.

2. Setting Up Email Template

	You can setup up various email templates in the Email Templates tab. The email templates will be sent upon reaching the condition you have configured.

3. Purging Useless Cart

	Useless carts are those abandoned carts recorded without email addresses. Those carts are from guests that have yet to even visit your checkout page or enter any information on your website for us to track. You can click the purge useless cart button to remove those abandoned carts.

4. Purging Reminded Cart

	Reminded carts are those that have already been sent an email reminder. If you no longer wish to track them, you can delete those carts by pressing the purge reminded carts button. Alternatively, you can let the system handle it automatically by enabling the ‘delete’ function in the email template. Once carts have been deleted, the one click restore cart feature will not work for deleted carts.

5. Unsubscribed Customers

	The system will no longer send an email to the customer that has unsubscribed. However, it will still mark the cart as ‘reminded’ without sending the email, so you can easily delete off their carts by purging the reminded carts.

## Change Log

### Version 2.1.0 (17/12/2017)
* Added single click cart restore feature
* Minor bug fixes
### Version 2.0.1 (29/08/2017)
* Fixed token issue for OpenCart 2.0 to 2.2 release
### Version 2.0.0 (11/07/2017)
* Fixed compatibility with OpenCart 3.0.0.0
* Minor improvements and updates
* Ceased support for OpenCart 1.5
### Version 1.2.1 (17/05/2017)
* Fixed multi-store URL for unsubscribe link
* Fixed wrongly loaded template for OpenCart 2.3.0.2
### Version 1.2.0 (29/11/2016)
* Fixed minor bugs
* Added send individual mail feature for each abandoned cart
### Version 1.1.6 (28/10/2016)
* Fixed incorrect pagination
### Version 1.1.5 (26/09/2016)
* Fixed minor bugs for OpenCart 1.5 release
### Version 1.1.4 (14/08/2016)
* Fixed minor bugs
### Version 1.1.3 (12/07/2016)
* Fixed compatibility with OpenCart 2.3.0.0
### Version 1.1.2 (13/06/2016)
* Fixed auto cleanup feature cleaning incorrectly
### Version 1.1.1 (21/04/2016)
* Fixed template unable to be edited
* Fixed email template text editor issue
* Fixed OC 1.5 email not sending issue
* Fixed undefined coupon expiry issue
* Fixed reminded report calculations
### Version 1.1.0 (07/04/2016)
* Added chart report for reminded carts
* Fixed minor bugs with email sending multiple times
* Fixed compatibility with OpenCart 2.2.0.0
### Version 1.0.5 (01/04/2016)
* Fixed compatibility with OpenCart 2.2.0.0
### Version 1.0.4 (27/03/2016)
* Fixed wrong URL for viewing customer details
* Fixed wrong SQL for updating reminded cart
### Version 1.0.3 (07/03/2016)
* Fixed compatibility with OpenCart 2.2.0.0
### Version 1.0.2 (25/02/2016)
* Improved automated cleanup
* Added shortcut to page on menu
### Version 1.0.1 (09/02/2016)
* Fixed minor bugs
* Improved cron job handling