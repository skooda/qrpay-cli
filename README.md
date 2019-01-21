# qrpay-cli
Simple cli script for generating QR payment links.

## Notice
This script is intended for Czech market, so it may not work for other countries.

## Installation
- Clone repo with `git clone https://github.com/skooda/qrpay-cli.git`
- Use your favorite editor to edit `# Config` section of `qrpay-cli/qrpay` file:
  - replace `<YOUR_ACCOUNT_NUMBER_HERE>` with your account number
  - replace `<YOUR_BANK_CODE_HERE>` with code of your bank  
- Make script callable `chmod 770 qrpay-cli/qrpay`
- Optionaly you can move it to some executable directory `mv qrpay-cli/qrpay /bin/qrpay`

## Usage
Basic usage is `qrpay <Amount> <Message>`, for example: `qrpay 300 Yesterdays lunch`

You can also copy link into clipboard using `qrpay 300 Yesterdays lunch | pbcopy`

## Thanks
Great thanks to developers or https://qr-platba.cz/ for making this posible.
