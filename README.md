# Credit Card Validation

Verify the correctness of the entered card number and the type of card used

# Installation

`npm i credit-card-validation --save`

Then...

```
import { cardNumberValidation, getCardType } from 'credit-card-validation';

cardNumberValidation(CARD_NUMBER);  // false or true
getCardType(CARD_NUMBER);   //Mastercard, AMEX, Discover, Diners, Diners-Carte Blanche, JCB, Visa Electron or nothing

```
