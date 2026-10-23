# Trade License Fee Calculator (DNCC)

A simple web calculator that estimates the trade license payment.

## Inputs
- License fee
- Signboard fee
- Month of payment

## How it works
- Paid in July to September: no surcharge.
- Paid from October: surcharge months are counted from July
  (October = 3, November = 4, and so on).
- Surcharge per month: the larger of 10% of the license fee or 100 taka.
- VAT: 15% of license fee + signboard fee + surcharge.
- Fixed fees added at the end: Income tax 3000, Book fee 270,
  Other fee 500, Bank fee 50.

## Changing rates
Open index.html and edit the numbers under "Settings".

## Note
This is an estimate. Check the current official rules before
quoting a client. No client data is stored in this project.
