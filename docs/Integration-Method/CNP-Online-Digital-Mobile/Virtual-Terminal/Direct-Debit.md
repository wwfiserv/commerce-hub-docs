# Enter payment data for Direct Debit transactions


## Overview

The Payment Details section for Direct Debit transactions shows fields for the customer’s IBAN (International Bank Account Number), the BIC (Business Identifier Code - which is required in case of transactions with a foreign IBAN), the Account Holder, an optional field for the Mandate Reference and a drop-down menu for the Mandate type.

If you do not enter a Mandate Reference, a mandate reference starting with the prefix ‘IPG’, a time stamp and a random value will automatically be assigned.

If you set the Mandate type to Recurring, an additional mandatory field appears where the Mandate Date needs to be entered.

![image](../../../assets/images/Direct-Debit-screenshot.png)

If you are using the First Data Local Payments solution for SEPA Direct Debit you will be provided with a couple of additional fields which are mandatory to support retrieving the relevant mandate:

- Mandate Date – To be populated with the initial mandate signature date
- Mandate URL – To be populated with the valid URL of the SEPA mandate to enable the Risk and Compliance department to access the details.

## See Also

[API Explorer](url)
[Card Transaction](Card-Transaction.md)
[Complete Transaction](Complete-Transaction.md)
[Transaction Result](Transaction-Result.md)