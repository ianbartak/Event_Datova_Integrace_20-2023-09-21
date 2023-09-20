1. **ID** (INT): id of the record
2. **POS_ID** (VARCHAR(9)): id of the POS device
3. **POS_TYPE** (VARCHAR(255)): type of the POS device
4. **ADDRESS** (VARCHAR(255)): address of the POS device
5. **CITY** (VARCHAR(255)): city where POS device is located
6. **BBAN** (VARCHAR(255)): Basic Bank Account number of the POS device
7. **IBAN** (VARCHAR(255)): International Bank account number of the POS device
8. **MERCHANT_ID** (VARCHAR(9)): id of the Merchant which POS device is registered to
9. **MERCHANT_NAME** (VARCHAR(255)): name of the merchant which POS device is registered to
10. **MERCHANT_FEE** (FLOAT): fee that merchant pays for every payment done via POS device
11. **REGISTERED_DATE** (DATE): date when POS device was registered
12. **LAST_UPDATE_DATE** (DATE): date of last update of the record

Each attribute in the table is described in detail below:

- **ID**: This attribute represents the unique identifier of the record in the POS_DEVICE table. It is of INT data type.

- **POS_ID**: This attribute represents the unique identifier of the POS device. It is of VARCHAR(9) data type.

- **POS_TYPE**: This attribute represents the type of the POS device. It is of VARCHAR(255) data type.

- **ADDRESS**: This attribute represents the address where the POS device is located. It is of VARCHAR(255) data type.

- **CITY**: This attribute represents the city where the POS device is located. It is of VARCHAR(255) data type.

- **BBAN**: This attribute represents the Basic Bank Account Number of the POS device. It is of VARCHAR(255) data type.

- **IBAN**: This attribute represents the International Bank Account Number of the POS device. It is of VARCHAR(255) data type.

- **MERCHANT_ID**: This attribute represents the unique identifier of the Merchant to which the POS device is registered. It is of VARCHAR(9) data type.

- **MERCHANT_NAME**: This attribute represents the name of the Merchant to which the POS device is registered. It is of VARCHAR(255) data type.

- **MERCHANT_FEE**: This attribute represents the fee that the merchant pays for every payment done via the POS device. It is of FLOAT data type.

- **REGISTERED_DATE**: This attribute represents the date when the POS device was registered. It is of DATE data type.

- **LAST_UPDATE_DATE**: This attribute represents the date of the last update of the record in the POS_DEVICE table. It is of DATE data type.