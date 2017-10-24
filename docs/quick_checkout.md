# Quick Checkout

* Current Version: 11.0.0
* Last Updated: 30 June 2017
* License: [Commercial License][1]
* Compatibility:
OpenCart 1.5.1.x, 1.5.2.x, 1.5.3.x, 1.5.4.x, 1.5.5.x, 1.5.6.x, 2.x, 3.x

Quick Checkout 10 is the final release for OpenCart 1.5.x. Please upgrade your OpenCart store to have access to Quick Checkout 11.

[1]: https://www.marketinsg.com/usage-license

## Description

Quick Checkout enhances your customer's checkout experience. It allows you to fully customise your the checkout process from adding fields to removing fields! Quick Checkout is the top rated One Page Checkout solution in OpenCart with top-tier support.

## Features

* Customise your checkout experience, enable / disable fields (eg. Telephone, Country, Zone, Company etc)
* Easy to use One Page Checkout
* Compatible with all payment modules
* Compatible with all shipping modules
* Compatible with all themes
* 100% new files, no overwrites
* Multi-language supported
* Multi-store supported
* Multi columns layout
* Set fields sort position
* Set default values for fields
* Set placeholder text for fields
* Set fields required / optional
* Responsive feature to integrate with responsive themes
* Supports postal code based shipping modules
* Enable / Disable cart module
* Enable / Disable voucher / coupon / reward points module
* Enable / Disable login module
* Enable / Disable countdown timer
* Enable / Disable delivery field
* Enable / Disable delivery time field
* Enable / Disable order confirmation page
* Select or Radio choice type for shipping & payment
* Set default payment & shipping method
* Set payment and shipping logo
* Set default newsletter status
* Display loading screen
* Display spinner loading icon or overlay loading design
* Enable / disable drop down survey response
* Highlight error fields
* Add custom HTML header and footer content
* Add custom CSS codes through admin panel
* Easy one click installation

## Installation

### OpenCart Cloud

1. Purchase the extension from your administration panel.
2. Proceed to `Extensions >> Extensions` and select `Modules`. Then, install `Quick Checkout`. Configure extension accordingly.
3. Please view configuration details below.

### OpenCart 3

1. Go to `Admin >> Extensions >> Installer` to upload the extension zip file.
2. Proceed to `Extensions >> Extensions` and select `Modules`. Then, install `Quick Checkout`. Configure extension accordingly.
3. Please view configuration details below.

### OpenCart 2 & 1.5

1. Unzip the files. Ensure that vQmod has been installed.
2. Upload the files WITHIN the upload folder to your OpenCart installation folder with a FTP client. The folders should merge.
3. In your admin panel, proceed to `Extensions >> Modules`. Then, install `Quick Checkout`. Configure extension accordingly.
4. Please view configuration details below.

## Configurations

### General Settings

#### Status

Turn on/off Quick Checkout. Set status to enable to begin using Quick Checkout.

#### Minimum Order Amount

The minimum amount (in system's default currency) the cart total must reach before checkout is enabled.

#### Debug

This function is for developer to debug javascript and checkout errors.

#### Confirmation Page

Turn on/off the order confirmation page. If disabled, customer will not see their order cart for confirmation before payment.

#### Auto Save Data

Allow the customer's information to be saved automatically when the customer starts entering information on your checkout page.

#### Allow Users to Edit Cart Quantities

Allow the customer to change the product quantity on the checkout page. Disable to prevent customer from changing quantity on the checkout page.

#### Highlight Fields with Error

Enable to highlight fields with error when checkout form is submitted.

#### Display Error Below Fields

Enable to display error message below each field when checkout form is submitted.

#### Attempt Auto Submit

Attempt to automatically submit the payment form. This will only work if the payment module you are using does not require additional information (e.g. Bank Transfer, PayPal Standard). Payment modules that require additional information such as credit card fields cannot be automatically submitted.

#### Payment Button Targets

This is used to target the auto submit payment forms. If your payment module uses another button ID, add it to this field to target correctly for auto submit feature to work.

#### Proceed Button Text

Configure the text to be shown to customer to proceed to the next step of the checkout.

### Design

#### Display Load Screen

Display the page loading screen when checkout page is loaded.

#### Loading Display

Configure how the loading icon should be displayed.

#### Layout

Configure the layout of the checkout page.

#### Responsive Quick Checkout

Configure the checkout for a responsive design.

#### Slide Effect

Configure the checkout transition when it proceeds to the order confirmation page.

#### Custom CSS Codes

Add your custom CSS codes here if you wish to further style the checkout page.

### Fields

#### Display

Configure whether the field should be displayed to the customer on the checkout page.

#### Required

Configure whether the field is required to be filled in.

#### Default Value

Configure the default value for the field when it is loaded.

#### Placeholder

Configure the field placeholder.

#### Sort Order

Configure the field position when displayed on the checkout page.

### Modules

#### Display Coupon Module

Toggle on/off the coupon module on the checkout page.

#### Display Voucher Module

Toggle on/off the voucher module on the checkout page.

#### Display Reward Module

Toggle on/off the reward module on the checkout page.

#### Display Cart Module

Toggle on/off the cart module on the checkout page.

#### Display Login Module

Toggle on/off the login module for guest customers on the checkout page.

#### Custom HTML Header

Add custom HTML text to the header of the checkout page.

#### Custom HTML Footer

Add custom HTML text to the footer of the checkout page.

### Payment

#### Display Payment Method Module

Turn on/off the payment method module on the checkout page. The default selected payment module will be used if the payment method module is disabled.

#### Payment Reloads Cart

Turn on/off payment reloads cart feature. This is useful if your payment methods have additional fees.

#### Payment Selection

Configure the payment method selection to be select or radio type display.

#### Default Payment Module

Configure the default payment method for checkout.

#### Payment Logo URL

Configure the payment logo image URL to be loaded on the checkout page.

### Shipping

#### Display Shipping Method Module

Turn on/off the shipping method module on the checkout page. The default selected shipping module will be used if the shipping method module is disabled.

#### Shipping Reloads Payment

Turn on/off shipping reloads payment feature. This is useful if your payment methods are dependent on the selected shipping methods.

#### Shipping Selection

Configure the shipping method selection to be select or radio type display.

#### Default Shipping Module

Configure the default shipping method for checkout.

#### Shipping Logo URL

Configure the shipping logo image URL to be loaded on the checkout page.

### Survey

Survey response will be captured in the order comments section.

#### Display Survey Field

Configure the status of the survey field.

#### Survey Required

Configure if the survey field must be filled up before checkout.

#### Survey Question

Configure the survey question to be displayed to the customer.

#### Survey Type

Configure the type for the survey. Select `text` for an open ended answer, and select `select` for customer to select from a list of answers.

### Delivery

Additional delivery details are stored into the order comments section.

#### Display Delivery Field

Turn on/off the delivery field.

#### Display Delivery Time

Configure whether the delivery time can be chosen by the customer, will only be an estimate, or is from a list of drop down timings.

#### Delivery Date Required

Configure whether delivery date field must be filled in during checkout.

#### Delivery Dates Unavailable

Configure the list of dates unavailable for delivery.

#### Delivery Minimum Days in Advance

Configure the minimum number of days required in advance for delivery date selection.

#### Delivery Maximum Days in Advance

Configure the maximum number of days allowed in advance for delivery selection.

#### Delivery Earliest Hour

Configure the earliest hour the customer can select for delivery.

#### Delivery Latest Hour

Configure the latest hour the customer can select for delivery.

#### Delivery Days of Week to Disable

Configure the days of the week to disable delivery.

### Timer

#### Countdown Timer

Turn on/off the countdown timer.

#### Countdown Starts

Configure how the countdown timer should start.

#### Countdown Text

The text to display for the countdown timer. Use the `{timer}` template code to display the timer on the checkout page.

### Analytics

#### Recover Abandoned Carts

Purchase our Recover Abandoned Carts extension to turn abandoned carts into sales.

## Change Log

### Version 11.0.0 (30/06/2017)
* Fixed compatibility with OpenCart 3.0.0.0
* Fixed minor bugs and improvements
* Removed fax field for OpenCart 3
* Ceased support for OpenCart 1.5

### Version 10.1.0 (13/05/2017)
* Added multi-language placeholder
* Added multi-language default text
* Fixed custom fields not hiding
* Fixed custom fields validation
* Fixed cart total display when login for price is enabled
* Improved email validation when field not required
* Improved shipping reloads payment

### Version 10.0.6 (31/01/2017)
* Fixed missing column language

### Version 10.0.5 (26/01/2017)
* Added ability to remove rewards, coupons and vouchers

### Version 10.0.4 (16/11/2016)
* Fixed minor bugs with OpenCart 1.5 release
* Fixed minor bugs with minimum order feature

### Version 10.0.3 (26/09/2016)
* Fixed minor bugs

### Version 10.0.2 (08/07/2016)
* Fixed compatibility with OpenCart 2.3.0.0

### Version 10.0.1 (20/05/2016)
* Fixed force registration
* Fixed minor bugs

### Version 10.0.0 (03/05/2016)
* Improved feature to disable confirmation page
* Improved speed and performance by reducing ajax requests
* Improved auto submit feature
* Improved loading screen
* Improved auto submit targets
* Improved overlay design 
* Improved delivery field and date picker
* Improved custom fields integration with OpenCart 2
* Added default payment method
* Added default shipping method
* Added payment logos
* Added shipping logos
* Added place holder for fields
* Added configurable proceed button language
* Added minimum and maximum hours for delivery
* Fixed minor bugs
* Fixed minor layout issue
* Removed loading gif from OC 1.5 release

### Version 9.5.0 (08/04/2016)
* Added custom CSS field
* Added analytics tab
* Added feature to remove confirmation page
* Added auto submit target field
* Added new overlay module loading feature
* Fixed blank option for payment method

### Version 9.4.5 (04/03/2016)
* Fixed compatibility with OpenCart 2.2.0.0
* Last release for OpenCart 1.5.1.x and OpenCart 1.5.2.x

### Version 9.4.4 (20/01/2016)
* Fixed minimum order cart validation
* Improved three columns layout design

### Version 9.4.3 (23/12/2015)
* Fixed issue with payment address refreshing shipping methods

### Version 9.4.2 (06/12/2015)
* Fixed order comments tag
* Fixed issue with shipping address not saving on OC 1.5.x

### Version 9.4.1 (04/12/2015)
* Fixed fatal bug on OC 1.5.3.x to OC 1.5.6.x caused by v9.4.0
* Fixed minor bug OC 2.1.0.x