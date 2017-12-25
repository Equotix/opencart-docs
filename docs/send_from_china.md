# Send From China

* Current Version: 3.0.0
* Last Updated: 11 July 2017
* License: [Commercial License][1]
* Compatibility: OpenCart 1.5.1.x, 1.5.2.x, 1.5.3.x, 1.5.4.x, 1.5.5.x, 1.5.6.x, 2.x, 3.x


[1]: https://www.marketinsg.com/usage-license

## Description

This extension integrates Send From China (http://www.sendfromchina.com/) mailing services with your website. Give your customers an estimated shipping fee based on the services and the location right away.

This extension will work as long as Send From China supports your country as the mailing origin and it covers all locations that Send From China supports. Contact their sales representative for up to date information. (Send From China only returns currency value in Chinese Yuan [CNY].)

Do note that warehouse and dropshipping is not supported with this API at the moment. Only retreiving of shipping rates is supported.

## Features

* Rates are always up to date and live from Send From China
* You select which services to offer
* Option to display delivery time
* Option to display delivery class
* Option to display delivery weight
* Supports tax class
* Supports geo zones
* Uses Send From China API Integration

## Installation

### OpenCart Cloud

1. Purchase the extension from your administration panel.
2. Proceed to `Extensions >> Extensions` and select `Shipping`. Then, install `Send From China`. Configure extension accordingly.
3. Please view configuration details below.

### OpenCart 2 & 3

1. Go to `Admin >> Extensions >> Installer` to upload the extension zip file.
2. Proceed to `Extensions >> Extensions` and select `Shipping`. Then, install `Send From China`. Configure extension accordingly.
3. Please view configuration details below.

### OpenCart 1.5

1. Unzip the files.
2. Upload the files WITHIN the upload folder to your OpenCart installation folder with a FTP client. The folders should merge.
3. In your admin panel, proceed to `Extensions >> Shipping`. Then, install `Send From China`. Configure extension accordingly.
4. Please view configuration details below.

## Configurations

### OpenCart 1.5, 2, 3 & Cloud

1. Weight Class

	Send From China only accepts Kilogram as the weight class. Please select that for the configuration.

2. CNY Currency

	Send From China returns currency value in Chinese Yuan (CNY). Please ensure you have added the currency into your store in `System >> Localisation >> Currencies` with the currency code `CNY`. You may leave the currency disabled if you do not want to use it at the store front.

3. SOAP and API Details

	Please ensure that your server has SOAP installed to use Send From China API. You will need an account with Send From China if you wish to enter the API details into the configurations.

## Change Log

### Version 3.0.0 (11/07/2017)
* Fixed compatibility with OpenCart 3.0.0.0
* Fixed minor bugs and improvements
* Ceased support for OpenCart 1.5
### Version 2.2.4 (25/04/2017)
* Fixed issue with incorrect price display
* Fixed issue with licensing system (OpenCart 2.3)
### Version 2.2.3 (12/07/2016)
* Fixed compatibility with OpenCart 2.3.0.0
### Version 2.2.2 (10/03/2016)
* Fixed wrong path
### Version 2.2.1 (07/03/2016)
* Fixed compatibility with OpenCart 2.2.0.0
### Version 2.2.0 (19/06/2015)
* Improved administration interface
### Version 2.1.3 (23/04/2015)
* Fixed mail compatibility with OpenCart 2.0.2.0
### Version 2.1.2 (03/02/2015)
* Fixed issue to improve support for smaller weights
### Version 2.1.1 (23/12/2014)
* Update support Facebook link
### Version 2.1.0 (20/10/2014)
* OC 2 compatibility
### Version 2.0.0 (05/04/2013)
* Enable version 2.0 of Send From China API using SOAP
* Allow selection between SOAP and XML version
### Version 1.0 (03/04/2013)
* Shipping module created