# Welcome to Commerce Hub

## Overview

The Commerce Hub provides a simple way to integrate payment acceptance functionality and gives you access to a comprehensive suite of global commerce assets. We Offers a variety of payment options ranging from debit cards, credit cards and eChecks to digital payments like Apple Pay, PayPal, and Google Pay.

See below for the most popular options;

![Payment Methods](../../../assets/images/card-types.png)

Beyond accepting customer payments, our services include Tokenization, 3-D Secure, account verification, creating and managing Recurring Payments, Installments, Deferred Payments, Split Shipment, AVS and Payment URLs.

---

## Online/Digital/Mobile Payments

Card Not Present (CNP) transactions are initiated when a customer does not physically present their payment source at the time of the transaction. Examples of CNP transactions include; online payments, in-app payments, and MOTO transactions.

<!-- theme: warning -->
> CNP transactions are at a higher risk for fraud, due to the inability to verify the account holder is making the purchase. To reduce the risk of card fraud it is recommended to use [3D Secure](../../CNP-Online-Digital-Mobile/3DSecure-Wallets/3D-Secure/3DSecure.md) along with [AVS](../Fraud/Address-Verification.md) and [Security Code](../Fraud/Security-Code.md) verification.

#### [RESTful API](../REST-API/Use-Our-APIs.md)

Allows a merchants to build their own UI and manage customer checkout within their website or software using the Commerce Hub RESTful APIs.

#### [Hosted Payment Page](../../Card-Not-Present/Hosted-Payment-Page/Hosted-Payment-Page.md)

Commerce Hub Hosted Payment Page allows merchants to redirect their customer to our secure payment page when they are checking out.

#### [Payment URL](../../Card-Not-Present/Payment-URL/Payment-URL.md)

Generate an invoice and share with customer for payment.

#### [Payment.js](../../Card-Not-Present/Payment-JS/Payment-JS.md)

Commerce Hub's Payment.js allows merchants working with various Fiserv APIs and gateways to tokenize payment credentials for later transactions.

#### [Virtual POS/ MOTO](../../Card-Not-Present/Virtual-Terminal/Virtual-Terminal.md)

Take orders via phone or to run a Void or Return, our Virtual Terminal is the ideal solution.


---

## In Person Payment

Card Present (CP) transactions are initiated when a customer physically presents their payment source at the time of the transaction. Examples of CP transactions include; manual entry, track data and EMV.

#### [RESTful API](../REST-API/Use-Our-APIs.md)

Allows a merchants to build their own [terminal](../../CP-In-Person/Terminal/Getting-started-Terminal.md) or [software](../../CNP-CP-Common/Software/Software.md) and manage customer checkout within their store, using the Commerce Hub RESTful APIs.


---

<!-- ## Integrate to Commerce Hub

### Transaction Origin

- [Card Not Present](Getting-Started/Getting-Started-CNP.md)
- [Card Present](Getting-Started/Getting-Started-CP.md)
- [Wallets](Getting-Started/Getting-Started-Wallets.md)

### Transaction Type

- [Charge](../Transactions/Charges.md)
- [Capture](../Transactions/Capture.md)
- [Cancel](../Transactions/Cancel.md)
- [Refund](../Transactions/Refund.md)
- [Credit](../Transactions/Credit.md)
- [Inquiry](../Transactions/Inquiry.md)

### Vertical/Industry Type

- Airline
- Lodging
- Mobile/Wallet
- Online/Website
- Petro
- Rental Car
- Quick Service Restaurant

### Value Added Services

- [Acount Verification](../Transactions/Verification.md)
- [Payment Token](../Transactions/Payment-Token.md)
- [Stored Credentials](../Transactions/Stored-Credentials.md)

-->

