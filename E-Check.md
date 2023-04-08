
[[Chapter 3 - Payment Systems]]

- Suppose the content of a check is 'C'
- Check is signed by computing the message digest of 'C' and encrypting it using a private key
- The E Check along with the signature is then forwarded on to Payee
- The Payee then sends it to the bank to be cleared

**There are FOUR types of E Checks**
1. ***Deposit and Clear***
![[depcle.png]]

- Payer signs an E Check and sends it to the Payee
- Payee deposits the check in his bank
- The Payer's bank and the Payee's bank perform a check clearance to transfer funds

2. ***Cash and Transfer***
![[cashtrans.png]]
- Used when Payee's bank cannot support E Check
- Upon receiving the signed E Check from the Payer the check is forwarded to the Payer's bank directly
- The Payer's bank verifies the E Check and transfers the funds directly

3. ***Lockbox***
![[lockbox.png]]
- The Payee needs a special account with the bank called a lockbox
- With this he can accept E Checks from the Payer
- This is useful for large organizations that handle a large number of checks

4. ***Funds Transfer***
![[fund.png]]
- The Payer sends the E Check to his bank initiating a fund transfer
- The Payer's bank then credits the Payee accordingly via existing funds transfer