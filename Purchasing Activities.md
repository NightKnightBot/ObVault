
[[Chapter 4 - E Commerce strategies]]

- Purchasing activities include ***identifying and evaluating vendors, selecting specific products, placing orders, and resolving any issues that arise after receiving the ordered goods or services.***
- These issues might include *late deliveries, incorrect quantities, incorrect items, and defective items*
- By monitoring all relevant elements of purchase  transactions, purchasing managers can play an important role in maintaining and improving product quality and reducing cost
- A company’s supply chain includes **design, produce, promote, market, deliver, and support each individual component of that product or service**
- This Department is charged with buying all components at the lowest price possible
- They do this by **identifying** qualified vendors and asking them to prepare **bids** that described what they would supply and how much they would **charge**
- Then **select the lowest bid** that still **met the quality standards** for the component

```mermaid
graph TD
id(Identify needs)
rev(Review vendor catalogs, web pages or databases)
defreq(Define requirements)
rfq(Send requests for quotes)
rq(review quotes and selct vendor)
ap(Approve purchase)
cpo(Create Purchase Order)
ecwv(Establish credit with vendor)
spotv(Send purchase order to vendor)
cacpo(Check availability and confirm purchase order)
as(Arrange shipping)
pi(Perform inspections)
fso(Fulfill and ship order)
isprd(Inspect shipment and process receiving documents)
crdaipo(Check recieving documents against invoice and purchase order)
tfrdms(Transfer from recieving department to material storage)
rtar(Record transaction in accounting records)
psp(Process and send payment)


id <--> rev
id & rev --> defreq --> rfq & rq
rfq --> rq
rq --> ap & cpo
ap --> cpo & ecwv
cpo --> spotv --> cacpo
cacpo --> as & pi & fso
pi <--> fso
fso --> isprd
isprd --> crdaipo --> psp & tfrdms 
tfrdms --> rtar --> psp
```

There are two types of purchasing
1. Direct Materials Purchasing
2. Indirect Materials Purchasing

[[Direct vs. Indirect Materials Purchasing]]