
[[Chapter 3 - Payment Systems]]

## There are Three main parts of SET Protocol
1. **Confidentiality** 
	- Sensitive data  is kept secured and confidential through encryption
2. **Integrity** 
	- All content is digitally signed to keep content integrity
3. **Authentication**
	- Authentication preformed through public key infrastructure

### The Easy way to remember this is C.I.A.

![[Pasted image 20230224210504.png]]
**Merchant** This refers to a seller, which is connected to an acquirer.
**Cardholder** This refers to a registered holder of the credit card who is a buyer.
**Issuer** This refers to the bank that issues the credit card to a cardholder
**Acquirer** This refers to the bank that serves as an “agent” to link a merchant to multiple issuers.
**Payment gateway** The payment gateway is situated between the SET system and the financial network of the current credit card system for processing the credit card payment.

### SET Protocol has 4 phases:
1. *Initiation*: Cardholder sends a purchase initiation request to the merchant
2. *Purchase*: Then the merchant returns a response message to the cardholder. The cardholder sends the purchase order together with the payment instruction to the merchant
3. *Authorization*: Merchant obtains the authorization from the issuer via the payment gateway
4. *Capture*: Merchant requests a money transfer to its account

![[Pasted image 20230224211326.png]]