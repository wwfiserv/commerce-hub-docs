# Hosted Payment Page Integration

## Overview

Allows a merchant to redirect their customer to a secure Commerce Hub Hosted Payment Page to process a transaction. The Commmerce Hub Hosted Payment Page manages the customer interactions that are required in the checkout process based on payment method, or authentication mechanisms (3-D Secure).

Using secure hosted pages can reduce the burden of compliance with the Data Security Standard of the Payment Card Industry (PCI DSS).

For more information, refer to the [constructing a Hosted Payment Page](url) article for information on how to use our Hosted Payment Page integration.

<!-- theme: info -->
>A merchant can lessen the PCI DSS load by using Hosted Payment Pages, and still make use of our extended capabilities using our RESTful APIs to access features where no direct consumer interaction is required and no sensitive data is being processed.

## Additional Security Settings

The following recommendations are to limit potential for fraudulent activity on your hosted payment page.

**Recommendations**

- Enable Re-Captcha
- Authentication/Login requirement to access the payment page
- Limit response back to the browser/customer
- Follow [fraud best practices](../../Guides-Info/Fraud/Fraud-Settings.md) for the business type or payment flow

## Next Steps

- [Taking Payments](Taking-Payments.md)
- [Completing Transactions](Completing-Transaction.md)
- [Online Wallets](../../Guides-Info/Getting-Started/Getting-Started-Wallets.md)