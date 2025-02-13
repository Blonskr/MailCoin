# MailCoin：A Decentralized Cryptocurrency Payment Network Based on Email Protocols (SMTP/IMAP)

Author: Blonskr

Publication Date: February 10, 2025

Email:Blonskr@tutamail.com

www.mailcoin.org

ABSTRACT

This paper proposes MailCoin, a decentralized payment network based on email protocols (SMTP/IMAP). By leveraging the email services that all internet users already use as infrastructure, MailCoin enables a decentralized cryptocurrency payment system that is highly private, tamper-proof, censorship-resistant, easy to use, and free of transaction fees.

Its key innovations include:  
1.	Email Address as Wallet Address: The email address directly serves as the user’s wallet address, eliminating the learning curve.
2.	Email-Based Transactions: Users can complete payments and transactions simply by sending an email.
3.	Email Server Mining: Validators are responsible for parsing emails, verifying transactions, and submitting them to the ledger.
4.	Decentralized Mail Resolution (DMR): A distributed address system built on an improved Kademlia DHT.
5.	Lightweight BFT-PoS Consensus: A dynamically adjustable time window mechanism (Δ=30s±20%).
6.	Transaction Cost Shift Model: Replaces traditional Gas fees with token inflation, achieving zero transaction fees. 

Experiments show that MailCoin outperforms traditional blockchain-based cryptocurrencies in terms of double-spending resistance (success rate <0.01%), transaction throughput (1,218 TPS), and energy efficiency (0.0023 kWh/tx).

1. INTRODUCTION

1.1 Research Background
   
The current cryptocurrency systems based on blockchain technology face several challenges:

1)	High User Entry Barriers: The cost and complexity of using decentralized wallets make cryptocurrency adoption difficult for average users.
2)	Weak Censorship Resistance and Privacy: Major cryptocurrencies have been increasingly subject to transaction tracing, with organizations linking blockchain activity to real-world identities.
3)	Incompatibility with Microtransactions: Ethereum‘s average Gas fee is around $2.1, while Bitcoin transaction fees remain high, making small payments impractical.

The Simple Mail Transfer Protocol (SMTP) and Internet Message Access Protocol (IMAP) are among the most widely used communication protocols on the Internet. They inherently possess decentralized characteristics, aligning with the core principles of Web3.0, where there is no central authority, and anyone can freely set up mail servers that communicate globally.

Additionally, email protocols offer strong censorship resistance since they rely on open standards (SMTP/IMAP) rather than closed APIs, making it difficult for governments or institutions to impose complete restrictions.

Given email’s asynchronous communication, global relay capabilities, and near-zero marginal costs (as per RFC 5321 [2]), it presents an ideal foundation for constructing a decentralized payment network.

1.2 Core Contributions

1)	Protocol-Level Innovations:

a)	Encoding transactions as RFC 5322 standard emails, ensuring multi-platform compatibility.
b)	Developing a Decentralized Mail Resolution (DMR) service to replace centralized DNS services, enabling censorship-resistant address resolution.

2)	Consensus Mechanism Optimization:

a)	Implementing an asynchronous Byzantine Fault Tolerant Proof-of-Stake (BFT-PoS) algorithm based on the Cosmos SDK.
b)	Introducing a dynamic validator election mechanism to enhance network resilience.

3)	Economic Model Design:

a)	Establishing a zero-fee sustainable incentive model.
b)	Implementing a token inflation control strategy to ensure long-term stability.
c)	

1.3 Application Scenarios

With low transaction costs, MailCoin is well-suited for various use cases, including:

1. Content tipping
2. E-commerce transactions
3. IoT-based micro-billing

Download MailCoin Academic Paper
https://www.mailcoin.org/attachment/MailCoin-0.16.6-en.pdf
