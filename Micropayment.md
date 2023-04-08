
[[Chapter 3 - Payment Systems]]

## ***Why Micropayment?***
- There are situations where macro-payment may be unjustified as the size of the payment is too small
- Millicent With the aim of providing a lightweight and secure payment method, Millicent introduces a digital currency known as scrip, which is accepted only by its respective vendor

## ***Millicent Micropayment***
![[Pasted image 20230226165907.png]]
- This system involves three parties
	1. Customer
	2. Broker
	3. Vendor
- Vendors sell scrips through Brokers to Customers in aggregate fashion
- The vendor scrips are sent to the customer and the purchase is settled by a macro-payment method
- To ensure that the content of a scrip cannot be modified, each scrip comes with a certificate produced by hashing the content of the scrip with a scrip-specific secret.
- According to the scrip ID, the vendor can identify the secret from a database and hence reproduce the certificate.
- By comparing the reproduced certificate with the one sent by the customer, the validity of the scrip can be verified.

## How does payment with scrips work?
- When a customer wants to purchase something from a vendor, he sends the scrips summing up the total payment amount to the vendor.
- Before accepting a scrip, the vendor verifies that the scrip is valid by checking the associated certificate and that it has not been spent before.
- Each vendor uses a database to record all the used scrips.