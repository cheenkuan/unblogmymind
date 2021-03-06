---
template: index-page
slug: /
date: 2021-02-02
title: "What will Distributed Ledger Technology and Cryptocurrencies do for Cross Border Payments?"
featuredImage: /assets/PaymentSystemDiagram.png
---
In order to understand what Distributed Ledger Technology (DLT) and Cryptocurrencies brings to cross border payments, we must first consider the typical current state of cross border payments without such technologies.

![Cross Border Payment Diagram for Mobile Display](/assets/PaymentSystemDiagram.png)

### Typical Current State of Cross Border Payments

The diagram above illustrates a typical current state for cross border payments. The Sender who holds Currency A in his bank account with Bank A would like to pay the Recipient in Currency B to the Recipient’s bank account with Bank B. Such payment will typically involve the following sequence of events:

#### Step 1

Sender instructs Bank A to transfer x amount of Currency B (B$x) to Recipient’s bank account with Bank B. Instructions will typically be transmitted via the [SWIFT]( https://www.swift.com/) network, which provides an inter-bank messaging system and network. Bank A debits y amount of Currency A (A$y) from the Sender’s account with the bank, which represents the amount of Currency A that is required to exchange for B$x plus all the fees required to carry out the transfer to the Recipient.

If Bank A and Bank B have a direct bank-to-bank relationship in the form of Bank A holding a Currency B nostro bank account with Bank B, then the transfer will be simpler, as Bank B can debit B$x from such nostro account of Bank A and we can skip to Step 4. Alternatively, the bank-to-bank relationship can be established via membership and multi-currency account held with [Continuous Linked Settlement (CLS)]( https://www.cls-group.com/), a specialist US financial institution that provides foreign exchange settlement services to its members. As this point, CLS has 75 members and provides settlement services for 18 currencies. 

However, this is not the typical case because holding nostro bank accounts in foreign currencies or a CLS multi-currency account is costly. The balance in such accounts represents capital or liquidity that is trapped and cannot be deployed by the bank towards more profitable use. As Bank A will typically not have any bank-to-bank relationship with Bank B, the transfer will have to be made via Correspondent Banks following the next few steps.

#### Step 2

Bank A instructs Bank A1 to transfer B$x to Recipient’s bank account with Bank B. Bank A1 is a bank in the same country as Bank A which holds a nostro bank account with a bank within the country of Bank B or a multi-currency account with CLS. Such banks are commonly referred to as Correspondent Banks. Bank A1 will charge a fee for this service, which is borne by the Sender and calculated into the fees in Step 1. In addition to this fee, there will also be forex charges in the form of fees and forex buy-sell price spread.

The transfer of A$y from Bank A to Bank A1 will typically be carried out under the central bank payment or clearing system of the country of Bank A and Bank A1, Central Bank A Payment System. Banks operating within a country are usually required to maintain accounts with the country’s central bank, and transfers of $A between banks within the system will be carried out via debit and credit entries in such accounts.

#### Step 3

Bank A1 instructs Bank B1 to transfer B$x to the Recipient’s bank account with Bank B. The nostro account of Bank A1 with Bank B1 will be debited B$x. Alternatively, if CLS is used for forex settlement, appropriate entries will be made to the multi-currency accounts of Bank A1 and Bank B1 to ensure that Bank B1 is paid for the B$x it will be sending to the Recipient. Bank B1 will transfer B$x to Bank B, which will be cleared under the payment or clearing system of the country of Bank B and Bank B1, Central Bank B Payment System. Bank B1 will also charge a fee for this service, which is borne by the Sender and calculated into the fees in Step 1.

If Bank B is a Correspondent Bank having a bank-to-bank relationship with Bank A1 or both Bank B and Bank A1 are members of CLS, then Bank A1 can directly instruct Bank B to transfer B$x to the Recipient’s bank account.

#### Step 4

Bank B credits B$x into the account of the Recipient held with Bank B.

### Typical Complaints of Cross Border Payments Users

As a result of the typical current state for cross border payments, users will commonly have the following complaints.

1.	Cross border payments are expensive. Each bank in the payment process levy their own charges, which increases the cost of transaction for the user. The average cost for executing a cross border payment via correspondent bank network is in the range of US$25 to US$35.
<p>
2.	Cross border payments are slow. Multiple banks will process the payment in sequence. Each bank in the payment process will have their own regulatory compliance process, which will include domestic and international regulations for combating financing of terrorism, money-laundering, as well as for maintaining sanctions. Each bank will require some processing time. Further, the time taken may be lengthened by the limited time window for the banks in different time zones to communicate with each other during their operating hours. If clarifications are required or requested, the process may be further delayed. Depending on the time when a transaction is initiated and the mismatch in operating hours of the various banks and intermediaries in the transaction chain, the entire transaction could take between 2 to 5 days.
<p>
3.	Users are unable to track the status of their payment from bank-to-bank in the payment process sequence. SWIFT has a global payment initiative (gpi) that enables such tracking for participating member banks. However, this is not available for all cross border payments.
<p>
4.	There has been a decrease in availability of cross border payments due to decline in the number of active correspondent banks globally. Between 2011 to 2017 there was a 8% decline in the number of active correspondent banks. This is primarily due to a drive towards capital efficiency (via reduction of trapped capital in nostro accounts) as well as a desire to reduce regulatory risks arising from greater focus on anti-money laundering, counter terrorist financing, and sanctions regulations, which had led to substantial fines being imposed on banks found to have breached the regulations. The net result is that currencies that have less cross border payment demand will be under-serviced as more and more correspondent banks stop servicing cross border payments for those currencies. Much of the world’s trade is settled in a few major currencies, in particular US dollars, instead of in the native currencies of the trading partners.

### Developments in Cross Border Payments with DLT and Cryptocurrencies	

[RippleNet]( https://ripple.com/ripplenet) is an example of a working cross border payment system designed to work with DLT and cryptocurrency.  RippleNet payment transactions can be completed in around 3 seconds. RippleNet’s distributed infrastructure is continuously available, and its messaging system and protocol incorporates standardized bi-directional messaging, rich data attachments, pre-validation of transactions, pre-disclosure of information prior to settlement, and atomic settlement, which means that the entire transaction settles instantly or not at all.

Without a cryptocurrency acting as a bridge asset for cross border payments, RippleNet is just an improved DLT based replacement for the SWIFT messaging system that is dominant for conventional cross border payments. Settlement of transactions continues to rely on the network of nostro accounts or credit arrangements between banks, having the disadvantages of trapped capital in nostro accounts and the corresponding counter-party risk.
 
However, when used together with [XRP]( https://ripple.com/xrp), RippleNet’s cryptocurrency, acting as a bridge asset between parties, RippleNet can overcome the disadvantages of trapped capital and counter-party risk inherent in nostro accounts. A transfer of XRP can be completed in around 3 seconds. Therefore, if a Sender’s bank can obtain XRP through a crypto-exchange using the Sender’s local currency, and the Recipient’s bank can obtain Recipient’s local currency through a crypto-exchange using the XRP it receives from Sender’s bank, then the RippleNet transfer can be completed in seconds without the disadvantages inherent in nostro accounts.

### Further Developments for Cross Border Payments Required

RippleNet’s relevance as a global cross border payments network will grow as its network of crypto-exchanges that facilitate payment transaction grows. Growth in the number of XRP to fiat currency pairing traded in these exchanges will also lead to growth in the number of payment corridors supported by RippleNet as well as in transactions using XRP as bridge asset for transfer, which does not require inter-bank nostro or credit arrangements.

### Can RippleNet with XRP be the Killer Solution that takes over Global Cross Border Payments?

RippleNet without any bridge asset can already be considered to be a successful solution for global cross border payments because of the speed and traceability of its payments. The further development of XRP as a viable bridge asset to facilitate value transfers without trapped capital or counter-party risk will further enhance RippleNet. 

However, many have questioned whether XRP or any cryptocurrency or crypto-asset can be a viable bridge asset because of the volatility in their value. With respect to XRP, it must be pointed out that the speed of XRP transfers may minimize and even negate the effects of volatility. It should also be noted that even if the effects of volatility can be negated by speed of transfers, XRP will not work well as a stable store of value until its volatility is fixed. This means that the payment intermediaries using XRP as a bridge asset with RippleNet will have to optimize their strategy for holding the minimum amount of XRP as their money transfer business will require.

There are also concerns that cryptocurrencies or crypto-assets may be subject to arbitrage differences between crypto-exchanges. This may make a cryptocurrency or crypto-asset unsuitable as a medium of transfer when there is a wide price difference for a cryptocurrency or crypto-asset between the send-side exchange and the receiving-side exchange. There are studies demonstrating that during the period between 2017 and 2018 significant price differences can exist between exchanges for the top 3 traded cryptocurrencies, BTC, ETH & XRP, especially if they are in different countries. However, arbitrage opportunities tend to fade into insignificance the more they are exploited and the more mature the market becomes. I suspect that the impact of arbitrage on cross-border payments will become less significant as the market becomes more mature. 

The development of more nostro-free local currency to local currency payment channels using XRP on RippleNet will also require the development of more under-served currency to XRP pair trading in crypto-exchanges and improved accessibility to crypto-exchanges by payment agents.

In my opinion, the development of more cross border payment networks like RippleNet will serve to reduce the friction for cross border payments. The use of DLT to anchor such payment networks will make such networks less vulnerable to manipulative attacks and at the same time provide assurance for the integrity of transactions being executed over the network. Competition in the payment network markets will drive innovation and further development of technologies, and also has the effect the reducing the overall impact of an interruption in any one payment network. Further development of use of crypto-assets as a medium for speedy transfer of value will reduce the costs for payments by eliminating the high costs of maintaining nostro accounts. Over time, as crypto-exchanges and trading of crypto-assets in such exchanges matures, it will even lead to cheaper cross border payments for under-served currencies, when crypto-assets can be immediately traded into the local currency of the receiving party without the need for a foreign exchange intermediary or correspondent bank.

### Project Ubin

Singapore’s [Project Ubin](https://www.mas.gov.sg/schemes-and-initiatives/project-ubin) has demonstrated the viability and efficiencies of the use of DLT and central bank digital currencies in a payment network.

However, I am certain there is room left for private enterprises to build alternative payment networks to compete with RippleNet as stitching a network of private commercial enterprises together into a payment network via B2B agreements seems somewhat less complicated and more nimble than a central bank driven initiative. 

With Singapore’s enterprises being trusted trading partners and investors in ASEAN, accessibility of Singapore’s financial institutions to traditional payment networks which provides connections with the West, and the anticipation of greater regional cooperation, collaboration and trade between the members of the Regional Comprehensive Economic Partnership (RCEP), Singapore may be a very good base location for the establishment of an alternative DLT payment network which focuses on solving the cross border payment problems for the over 2.2B population of RCEP members, and especially for the many ASEAN currencies which are under-served in existing cross border payment networks.

### The Most Important Thing, Compliance

There are actually many important things to address in the course of building a successful alternative DLT payment network. Speed, accessibility, affordability, integrity, security, are all important and necessary features of a payment network. However, the payment network will fail if it does not comprehensively and successfully resolve the problems related to regulatory compliance relevant to the parties in a transaction concerning Anti-Money Laundering, Counter-Terrorism Financing, Economic Sanctions, Personal Data Protection as well as the information requirements of monetary authorities. Only a payment network that is capable of helping the parties to a payment transaction comply with the regulations relevant to them, is deserving of success and support. Although incumbent payment networks are not always successful with their execution of regulatory compliance, the focus on new payment networks will unfairly exaggerate the egregiousness of any regulatory non-compliance from payment upstarts, especially when this is one of the areas where the incumbent may compare favourably with the upstart.

### A Future with more Alternative Payment Networks

I will be looking forward to and cheering the appearance of new payment upstarts who can give incumbent payment networks as well as RippleNet a good run for their money. Competition encourages innovation and efficiencies, and increases the coverage of the entire payment universe. An increase in the number of alternative payment networks serves to improve the resilience of the whole cross border payment universe by ensuring that the catastrophe of disruption of any one network will be mitigated by the availability of alternatives. And nothing stops traditional banks from leveraging their existing network with new technologies to invent new methods for payment in the form of banking as a service to support new payment networks. The competition in recent years have indeed galvanized the global payment landscape. Interesting times lie ahead for cross border payments.

