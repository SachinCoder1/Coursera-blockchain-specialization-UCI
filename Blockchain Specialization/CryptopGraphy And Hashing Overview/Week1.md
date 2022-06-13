# The Nature of Ownership - Week 1


### 1. In the context of information security in software systems, the term identification refers to:
- [ ] Claiming to be a certain person by name or another unique identifier.
- [ ] Confirming a link of ownership between a person and a specific item.
- [x] Verifying who you are by means of an I.D. card or other form of external evidence.
- [ ] Granting access to specific resources or services according to a set of well-defined criteria.


### 2. The term authorization refers to:
- [ ] Verifying who you are by means of an I.D. card or other form of external evidence.
- [ ] Claiming to be a certain person by name or another unique identifier.
- [x] Granting access to specific resources or services according to a set of well-defined criteria.
- [ ] Confirming a link of ownership between a person and a specific item.


### 3. The term authentication refers to:
- [ ] Claiming to be a certain person by name or another unique identifier.
- [x] Verifying who you are by means of an I.D. card or other form of external evidence.
- [ ] Granting access to specific resources or services according to a set of well-defined criteria.
- [ ] Confirming a link of ownership between a person and a specific item.


### 4. Ideally, a ledger has both public and private functions. Which one of the following actions is the private function?
- [x] Recording a transfer of ownership.
- [ ] Matching owners with their property.
- [ ] Verifying ownership.
- [ ] Determining the identify of owners.


### 5. Both a ledger and a sales receipt can help document ownership. What can the ledger DO that the sales receipt CANNOT?
- [ ] Make publicly viewable in order to confirm ownership.
- [x] Keep track of ownership changes over time.
- [ ] Show the relationship between a person and an item they own.
- [ ] Document the time and date that an ownership change (i.e. a sale) took place.


### 6. What can be done with a ledger in order to eliminate (or at least significantly minimize) the risk of losing the information it contains?
- [x] Install it on multiple nodes in a peer-to-peer network with the understanding that the “correct” version is the one that is most agreed-upon.
- [ ] Make it private so only authorized individuals can view its contents. 
- [ ] Install it on a randomly-selected node within a peer-to-peer system to reduce its exposure to hackers.
- [ ] Encrypt its contents so only authorized persons who have the decryption key can view the information.


### 7. Which one of the following situations is a specific example of the kind of double spending that the blockchain can be used to prevent?
- [x] Tickets for a tourist excursion train are available from five different locations in town. Every hour, the individual ticket sellers use email to keep each other up-to-date on the number of seats sold. One day, the internet service crashes for two hours but the ticket sellers continue selling tickets. Unfortunately, that day’s trip is overbooked and several people holding tickets will need to be refunded. 
- [ ] The local bank’s accounting system is hacked and the software routine that updates the customer account database stops subtracting ATM withdrawals from customers’ accounts. Several customers realize this and begin making multiple withdrawals from different ATMs across town. 
- [ ] ABC Coffee Shop emails a coupon to its customers stating that that they can print it out and use it for a discount on a cup of coffee. One of the customers forwards it to 25 of his friends, who all eagerly descend upon the coffee shop, coupons in hand.
- [ ] The local newspaper emails a PDF version of its print edition to its digital subscribers every day. Some subscribers forward those PDF file to non-subscribers so the newspaper ends up losing revenue (assuming that those freeloaders would otherwise pay for subscriptions).


### 8. One of the functional requirements for the blockchain is the ability to distribute ledgers to nodes in an untrustworthy environment. How can it do this? 
- [ ] Designate a “home node” to maintain the canonical copy of the ledger against which all other distributed ledgers are compared for accuracy.
- [ ] Once a ledger has been updated, prevent further transactions from being registered.
- [x] Design the ledgers so that the transaction history cannot be changed (make it “append-only”).
- [ ] Before disseminating updated ledgers, systematically “ping” each node to verify its trustworthiness.


### 9. Which one of the following statements is correct about how the blockchain handles transaction data?
- [x] The blockchain maintains a historical and unchangeable record of all transactions as a means of verifying ownership.
- [ ] Each time a new transaction is added to the blockchain, the previous transactions are re-sorted in order of transaction size.
- [ ] All transaction data are registered sequentially with a coordinating node before being disseminated to the peer-to-peer network.
- [ ] Unlike money transfers carried out in a traditional bank, a distributed blockchain-based system performs “post facto” authorization.


### 10. ABC Online Bookseller, which accepts bitcoin cash for payment, is limited in its capacity to ship books due to its small warehouses and small fleet of delivery trucks. So, they limit customers to purchasing only five books per day. Which aspect of transaction integrity does this limit represent? 
- [ ] Authorization
- [ ] Informal correctness
- [x] Semantic correctness
- [ ] Formal correctness