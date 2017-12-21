# eNETS Integration

* Current Version: 3.0.0
* Last Updated: 18 December 2017
* License: [Commercial License][1]
* Compatibility: OpenCart 1.5.1.x, 1.5.2.x, 1.5.3.x, 1.5.4.x, 1.5.5.x, 1.5.6.x, 2.x, 3.x


[1]: https://www.marketinsg.com/usage-license

## Description

OpenCart Singapore eNETS payment integration. Supports eNETS & eNETS QR. UMAPI Lite Integration no longer supported.

## Features

* eNETS payment gateway integration
* eNETS Credit, Debit & QR payment gateway
* Activate payment module only when reaches the specific order total
* Captures call back notification to automatically update order status
* Sandbox mode for testing

## Installation

### OpenCart Cloud

1. Purchase the extension from your administration panel.
2. Proceed to `Extensions >> Extensions` and select `Payments`. Then, install `eNETS Credit / Debit / QR`. Configure extensions accordingly.

### OpenCart 2 & 3

1. Go to `Admin >> Extensions >> Installer` to upload the extension zip file.
2. Proceed to `Extensions >> Extensions` and select `Payments`. Then, install `eNETS Credit / Debit / QR`. Configure extension accordingly.

### OpenCart 1.5

1. Unzip the files.
2. Upload the files WITHIN the upload folder to your OpenCart installation folder with a FTP client. The folders should merge.
3. In your admin panel, proceed to `Extensions >> Payments`. Then, install `eNETS Credit / Debit / QR`. Configure extension accordingly.

## Configurations

### OpenCart 1.5, 2, 3 & Cloud

Upon installing the respective payment modules you need, you will have to fill up your API details you have from eNETS. No additional configuration is required.

## Change Log

### Version 3.0.0 (18/12/2017)
* Added support for new eNETS API
* Added QR payment support
* Added API upgrade for OpenCart 1.5
* Removed UMAPI Lite support
### Version 2.0.0 (28/06/2017)
* Fixed compatibility with OpenCart 3.0.0.0
* Minor improvements and updates
* Ceased support for OpenCart 1.5
### Version 1.0.3 (10/07/2016)
* Fixed compatibility with OpenCart 2.3.0.0
### Version 1.0.2 (10/03/2016)
* Fixed wrong path
### Version 1.0.1 (07/03/2016)
* Fixed compatibility with OpenCart 2.2.0.0
* Removed redundant codes
### Version 1.0.0 (30/06/2015)
* Payment module created