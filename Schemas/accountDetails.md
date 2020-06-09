### accountDetails


| Field             | Rule  | Description                                               |
| ----------------- | ----- | --------------------------------------------------------- |
| resourceId        | M     | The account number                                        |
| iban              | M     | The IBAN account number                                   |
| bban              | O     | The BBAN account number                                   |
| msisdn            | NA    | Not used                                                  |
| currency          | M     | ISO 4217 Alpha 3 currency code                            |
| name              | O     | Name of the account                                       |
| product           | O     | Product name of the bank for this account                 |
| cashAccountType   | NA    | Not used                                                  |
| status            | M     | enabled, deleted, blocked                                 |
| bic               | O     | BICFI                                                     |
| linkedAccounts    | NA    | Not used                                                  |  
| usage             | NA    | Not used                                                  |
| details           | O     | Specifications that might be provided by the ASPSP        |
| overdraftLimit    | M     | Over draft limit rule on the account, in positive numbers |
| balances          | O     | A list of balances regarding this account                 |
| _links            | M     | Links to resources                                        |

Field rules
* M = Mandatory
* O = Optional
* C = Conditional
* NA = Not applicable / Not used
* IS = Icelandic 

### Special cases

1. 