Philwinkle_LinkGuestOrder
=====

**Description**

Associate a guest order to your account as a logged-in customer.

This module was <a href="http://magento.stackexchange.com/questions/6772/if-email-exists-force-customer-to-login-before-ordering">created in response to a thread on Magento StackExchange</a> wherein a question was raised of how to prohibit a guest from continuing in Onepage Checkout if a registered account was already on file for that email address.  This module is, in my opinion, the better UX implementation of the same behavior and gives the power to the customer to associate to their account at a later date if they so choose.

<img src="http://i.imgur.com/PuYFKhb.png"/>

**A note about security**

Only guest orders may be associated, and at least 3 of the following 4 criteria must be known about the order to be associated:

- Billing Lastname
- Order Number
- Zipcode
- Email Address

The order is associated with the currently logged-in account. While more information could always be required, this is based on the Magento Sales Guest Controller and mirrors the criteria to modify/update/issue RMAs.  


**More information**

If you'd like additional features or have a bug request, contact me at philwinkle at gmail dot com or file an issue here on Github.


**License**

NOTICE OF LICENSE

This module is subject to the Open Software License (OSL 3.0)
that is bundled with this package in the file LICENSE.txt.
It is also available through the world-wide-web at this URL:
http://opensource.org/licenses/osl-3.0.php
