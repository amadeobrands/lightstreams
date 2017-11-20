<h1 align="center"><a href="http://www.lightstreams.network">Lightstreams</a> White Paper</h1>
<p align="center">
By <a href="https://mikesmo.github.io/">Michael Smolenski</a>
</p>

## Introduction

This white paper outlines plans by Autonomous Contracts[[1]](http://autocontracts.io/) to develop the [Lightstreams network](http://lightstreams.network)[[2]](http://lightstreams.io/), a peer-to-peer digital publishing network for content ranging from books, magazines, music, TV to movies and more.

The Lightstreams network will be an independent blockchain that is an Ethereum hybrid enabling any individual or business to publish digital content directly to consumers, replacing traditional online intermediaries such as Amazon, Spotify or Netflix.

[Lightstreams](http://lightstreams.network) is made possible through the new generation of Web 3.0 technology[[3]](https://nextconf.eu/2016/09/next16-blockchain-will-build-web-3-0-says-jamie-burke/) built upon blockchain and smart contract technology[[4]](https://bitsonblocks.net/2016/02/01/a-gentle-introduction-to-smart-contracts/). Blockchain technology that includes the award winning [Permissioned Blocks](https://github.com/autocontracts/permissioned-blocks/blob/master/whitepaper.md) protocol developed by Autonomous Contracts. [[5]](https://mikesmo.github.io/blog/2017/06/09/Consensus-hackathon.html) [[6]](https://github.com/autocontracts/permissioned-blocks) 

Today, traditional online intermediaries provide the distribution channel to deliver content to a global audience via the internet. To reach this scale, intermediaries own and maintain a large centralised computer infrastructure in order to handle the loading requirements of such audiences.

<p align="center">
<img src="/images/centralised-distribution.png">
<br>
<b>Traditional Model</b> - Distribution of digital content to consumers globally via centralised intermediaries.
</p>
<br>

Lightstream's disruptive technology makes such centralised infrastructure for distributing digital content obsolete. Instead, by using a peer-to-peer file sharing model[[7]](https://en.wikipedia.org/wiki/Peer-to-peer_file_sharing), network participants will provide the necessary infrastructure in order for the network to scale globally.

Consider the following example, using only a laptop, an author publishes a title of an e-book to the Lightstreams network. A customer who purchases the book downloads a copy directly from the author's laptop to their tablet. When a second customer purchases the e-book, they download parts of the e-book simultaneously from the author and the first customer. The author could disconnect his laptop from the network, and the e-book would continue to sell, as a third customer could download content from the first and second customers and so forth. Since the payments are executed using blockchain technology, the author will continue to be paid even though they are offline. This demonstrates how the Lightstreams uses the participant's devices in the network as the infrastructure to scale and provide the bandwidth as demand increases.

<p align="center">
<img src="/images/peer-to-peer-distribution.png">
<br>
<b>Lightstreams Model</b> - Distribution of digital content directly to consumers via a peer-to-peer network that dynamically scales as demand increases.
</p>

The current state of digital distribution is that of an oligopoly marketplace where only a few internet firms have the majority of the market share. As such, the incumbents tightly control the distribution channel and charge high fees while providing a less than ideal service for artists. By artists, we refer to authors, musicians, composers, songwriters, online course producers,  directors of self-made videos and any other creator of digital content.

By using a peer-to-peer distribution model, Lightstreams will create a network with the following principles:
- A revenue model that gives a fair share to the artist.
- A network the incentivises participants for being good stewards and building the community.
- Promotes an ever-expanding set of applications and services by allowing open access for anyone to use and build upon infrastructure. 

The scope of this paper describes a publishing channel for digital books, however the scope of the Lightstreams project extends to all forms of digital content such as music and video streaming.

The discussion of this paper is limited to creating a publishing channel for the distribution of digital books for the purpose of illustrating the use and benefits of the Lightstreams network. However, the scope of Lightstreams is not limited to digital books as the technology has been designed with audio and video streaming capabilities in mind using an IPFS[[8]](https://ipfs.io/) protocol layer. Therefore topics discussed in this paper are applicable to all forms of digital content inclusive of audio and video streaming.

Lightstreams will be an Ethereum-hybrid network inheriting many of the features of the Ethereum network by keeping feature releases synchronised with the main Ethereum code base. A digital token known as a Photon (PHT) token will be the cryptocurrency of the network. The primary utility value of the Photon will be in the facilitation of purchasing digital content.

## Problems with Content Publishing

Authors currently face today the following pain-points when using traditional publishing houses and online bookstores for distributing their ebooks.

### An Unfair Sales Model

The high fees for using an online sales channel means that authors receive 50% less revenue than if they were able to sell directly to the customer.

For example, a book valued at $9.99 sold on Amazon, has the following fees[[9]](https://kdp.amazon.com/en_US/help/topic/A29FL26OKE7R7B):

1. For a standard sale, an approximate 48% fee is charged; this comprises a 30% platform fee plus and an electronic delivery fee of $2.58. [[10]](http://andrewhy.de/amazons-markup-of-digital-delivery-to-indie-authors-is-129000/)

2. For a subscription sale, an approximate 50% fee is charged. This is calculated using a fee structure, where the author receives $0.00496 per page read, with a max payout of $5.00 for a 1000 page book.

### A Lack of Trust in Reporting Sales

Online bookstores control the ownership, custody and storage of customer information and sales data. Only a small subset of this data is shared with authors and they have no ability to trace and verify the validity of the data. This lack of transparent data provenance creates mistrust in the accuracy of sales. Adding to this is a complicated revenue-sharing model that is not standardised across bookstores and causes further frustration and confusion.

Incorrect sales reporting is not limited to online bookstores, too often many internet intermediaries receive complaints and in certain cases, legal action has been taken as shown in these examples: 

- Amazon apologizes for concerns raised about Kindle Edition Normalized Page Count (KENPC)[[11]](https://kdp.amazon.com/en_US/help/topic/AI3QMVN4FMTXJ) anomalies. [[12]](https://teleread.org/2016/10/08/amazon-kdp-select-authors-are-losing-page-reads-apparently-due-to-software-glitches/) 
- AgeView Press filed a complaint about incorrect sales reporting for an ebook published titled "Flying Solo" on Amazon's Kindle Direct via the Createspace e-store. [[13]]( https://jeanettevaughan.wordpress.com/2012/09/28/do-amazon-and-createspace-rip-off-indie-publishers-with-failure-to-correctly-report-sales/)
- Spotify settled a $20 million dispute with music publishers for the failure to report and pay licensing fees for distribution of copyrighted material. [[14]](https://www.nytimes.com/2016/03/18/business/media/spotify-reaches-settlement-with-publishers-in-licensing-dispute.html)
- RootZoo sues Facebook for overcharging of advertising fees by incorrectly reporting on advertisement clicks. [[15]](http://www.campaignlive.co.uk/article/rootzoo-sues-facebook-ad-click-dispute/920220)

### A closed communication channel

Online bookstores control the distribution channel and so are selective in the data shared with authors. There is no way for the author to connect directly with their readers. Readers who may want the option to have an open communication channel to the author of the book that they have purchased.

This hampers the author's ability to gain insights into the interests and receive direct feedback from their readership.

This control of the channel means that authors are unable to seek feedback, make announcements and to easily release early drafts and rough cuts.

### Fake Reviews that Impact Sales

Most online bookstores provide a review section for posting comments about books. Being open to anyone to write a review mean that it is open to abuse by fake reviewers. There have been known cases of fake reviews by those that have not purchased or read the material. In fact, there are third-party services that can be hired to write positive endorsements about books in order to progress them further up best selling lists. In some cases, it has been known that authors themselves have written favourably about their books and negative of others to create an unfair advantage.

- Orlando Figes, a respected history professor at Birkbeck, University of London was discovered to have posted fake reviews on Amazon lavishing high praise on his own book whilst posting critical reviews of others. [[16]](https://www.theguardian.com/books/2010/jul/16/orlando-figes-fake-amazon-reviews)

## Mission Statement

Lightstreams mission is to create a publishing network for all things digital. A network that is owned and regulated by the community, where artists and fans can connect at a low cost, fair and open marketplace.

## Features

### The Photon Token

The Lightstreams network will consist of an independent blockchain that is Ethereum based and compliant. Rather than Ether (ETH) as the native network cryptocurrency, the Lightstreams network will facilitate payments via a cryptocurrency that will have a unit value called a Photon (PHT).

The utility of the PHT token is for:

1. Purchasing digital content.
2. Rewarding participants for actions that encourage the growth of the network.
3. Rewarding validators for creating blocks.
4. Governance of the network, where voting power is based upon sales.

A token sale event will determine the initial allocation of PHT tokens between accounts describe in a genesis block.

### Disintermediation of Traditional Intermediaries

The value chain for digital books from the author to readers is via publishing houses and online bookstores, where currently Amazon Bookstore has the greatest market share.

By using the Lightstream peer-to-peer network, authors will be able to publish books directly to their readers, disintermediate both the traditional publishing houses and online bookstores.

This will result in the redistribution of sales revenue significantly in the favour of authors. It will also mean, there is no delay in receiving payments, as authors will receive PHT coins directly from readers into their digital wallets.

Note: In order to protect consumers from situations of fraud, new authors without a reputation, may be required to have the revenue they earn on sales held in the smart contract for a short period of time. This will be in order to ensure that if the content being sold infringes upon any copyright or is not as advertised then consumers will have the ability to report such abuse. If complaints reach certain levels then consumers will be refunded and the smart contract related to the content destroyed.

### Detailed Customer and Sales Data

Customer information and sales history will be recorded by smart contracts that execute on the Lightstreams network. This data will be confidentially and available only to the author and those that have been granted permission. This feature will be based upon a distributed secure vault that is part of the Permissioned Blocks protocol.

All sales activity of a book will only be available to authors. Customer information such as gender, location and reading preferences will be opt-in by readers that wish to share this information.

Data that is recorded by smart contracts will be immediately available to authors in real time. Since Lightstreams will be an open protocol, any third party can create analytical tools and services for authors to interpret this raw data.

### An Open Communication Channel

Users of the Lightstreams network will have the ability to follow authors and themes. This will serve as a twitter-like communication channel where users will be able to follow authors and subjects matters of their interest.

Authors will also be able to opt-in to a service where customers who have purchased content will be able to send their feedback. Authors can choose feedback to be either a private or public channel.

### Credible Customer Reviews

Authors will have the option to have their books reviewed by users of the system. Users will receive karma point similar to Reddit based on their activity. This grading system will form part of a credibility rating score for reviews. Those that do not have enough karma point will not be able to post reviews. Users will have the ability to upvote and downvote reviews.

Reviewers will be incentivised by receiving PHT tokens that are awarded to them for upvotes.

## Blockchain Architecture

The Lightstreams blockchain will be an independent Ethereum-based blockchain with the following features:

- It will be an open public network such that any user can connect and transmit transactions on the network.
- It will have an Ethereum compliant API that will be kept synchronised with the latest version of Ethereum.
- It will use the Permissioned Blocks protocol for the privacy and confidentiality of customer information.
- It will use a Proof of Authority (PoA) consensus algorithm.

<p align="center">
<img src="/images/lightstreams-architecture.png">
<br>
<b>Lightstreams Architecture</b> - A high level architecture overview.
</p>

## Scaling for Global Demand

The Lightstreams network will dynamically scale for distributing content via a private peer-to-peer file-sharing protocol known as Permissioned Blocks. The benefit of using a peer-to-peer file sharing protocol it that this eliminates the need for any intermediary to provide the distribution infrastructure. Instead, the network participants provide the infrastructure via their own devices. This means that as demand increases so does bandwidth increase for distributing content.

Each node in the network will store content on a modified version of IPFS, a file sharing layer that is part of the Permissioned Blocks protocol. The protocol will operate such that content is only shared with those that have been authorised, that is, they purchased the content.

## Seeding Services

Authors that do not wish to keep their node connected to the network can choose a seeding service for their books available to readers to download. These seeding nodes will provide this service for a fee that will host their books in a temporary cache until the content reaches a level of demand that it can be self-sustaining in the network.

The fee will be a scaling price structure based on the size of the content. This will avoid scenarios where the seeding services could be maliciously attacked with large files.

## Smart Contract Sales

The network will initially have two different models for selling content that will be controlled by smart contracts.

- A direct sale between author and reader.
- A subscription sale where a subscriber pays a monthly fee to read content from a subject category.

A benefit of using a smart contract is that the allocation of sales revenue is completely transparent and traceable to all network. 

### Direct Sales

In a direct sale, the author sets the price of their book as an amount of PHT tokens. At any time the author can choose to adjust the price of their book and the version of a published book. Readers who have purchased the book will be able to view the most up to date version, or any previous version.

Consuming content will be governed by a smart contract such that only that have purchased the content are granted access to the content in order to download to their network node.

The process of a direct sale is as follows:

1. The author creates a smart contract with the price of the book and an IPFS address of the product details. 
2. The author then uploads a version of the book which is stored in their local IPFS data store and linked to the smart contract.
3. The smart contract is published the Lightstreams network.

<p align="center">
<img src="/images/smart-contract-publishing-content.png">
<br>
<b>Publishing of Content</b> - Producer adds content, set price and publishes smart contract.
</p>

4. A user then purchases a copy of the book by paying the price in LST tokens set in the smart contract. This purchase is recorded in the smart contract, and a Lightstreams service fee is deducted.
5. The transaction for purchasing a copy of the book is broadcast to the Lightstreams network.
6. To retrieve a copy of the book, a request is made via the IPFS bit swap protocol for the content specified at the IPFS address stored in the smart contract. 
7. The smart contract on the author's node (or any node that has the content), verifies that the user has purchased the book. 
8. An encrypted copy of the book is sent to the user via the IPFS bit swap protocol.
9. The copy of the book is decrypted and is received by the user for reading.

<p align="center">
<img src="/images/smart-contract-consuming-content.png">
<br>
<b>Consuming of Content</b> - Consumer pays the price and retrieves a copy of the content.
</p>

### Subscription Sales

In a subscription sales model, an author will earn revenue based upon a normalised price per page accessed by readers. 
Access to each page of the book will be controlled by a smart contract that only permits readers that are subscribers to a book subject category.

Readers will pay a monthly fee in PHT tokens for each subject category they subscribe to. At any time the reader can decide to discontinue paying the subscription fee, upon which they will be unable to download content.

At the end of each month, the total PHT tokens collected for a subject category will be distributed to the authors less a service fee. The tokens will be divided and distributed by the ratio of pages accessed per book. If a book has more than 1000 pages, then the total number of pages is capped at 1000 pages.

Authors are rewarded for adding content to new subject categories such that they will take a greater proportion of the funds than authors who join once the subject category becomes popular.

<p align="center">
<img src="/images/subscription-contract.png">
<br>
<b>Subscription Contract</b> 
</p>

## Lightstreams Discovery Service

The Lightstreams network will provide a discovery service for readers to search and browse for books and content available for sale. Readers will be able to search via book subject, author, popularity or promoted works. Upon selection of a book, the reader can choose to view the content based on a direct or subscription based purchase depending upon the sales model.

Just as any online bookstore, the discovery service will provide information about books to aid readers in their purchasing decision:

- Author details
- Front and back cover
- Contents and index pages
- Product details: Published year, ISBN, ASIN... 
- A short blurb
- Reader reviews

A listing fee will be charged for publishing the book on the marketplace. The fee will be paid out to reviewers to cover the costs of reviewing content to ensure the quality of the marketplace is maintained.

## Network Consensus

A blockchain is distributed network that requires consensus between nodes in order to determine the valid state of the network at any given point in time. 

The Ethereum network uses a Proof of Work (PoW) consensus[[17]](https://github.com/ethereum/wiki/wiki/Mining) model where validator nodes known as miners validate transactions. Validators are incentivised to validate transactions by being rewarded with tokens if they can solve a complicated algorithm before the other validators in the network.

However, PoW does not scale well, with an overall network throughput of ~10 transactions per second. Lightstreams will instead use a Proof-of-Authority (PoA)[[18]](https://cointelegraph.com/news/why-blockchain-needs-proof-of-authority-instead-of-proof-of-stake) consensus algorithm where a set of "validator" nodes that are explicitly allowed to create new blocks and secure the blockchain. Using a PoA algorithm such as Tendermint[[19]](https://tendermint.com/) will allow for an order of magnitude increase in scalability ~10,000 transactions per second while also allowing for a governance model for chain maintenance and keep the block issuers accountable.

Lightstreams validators will earn a fee for validating transactions. Nodes that achieve a certain level of sales on the network will have the option to become validators. Validators will be required to pass a  
Validators are incentivised by having a stake in the successful operation of the network. Therefore validators will be selected by those participants that maintain the highest sales volumes.

In order to protect the network from malicious smart contracts being published, validators will only permit contracts that have been certified by Lightstreams Foundation to become part of the blockchain. In order to permit this behaviour smart contracts will be multi-signature where both the artist and an account operated by the Lightstreams Foundation will need to have signed for a validator to accept the transaction.  

## Governance

Authors with the high sales per year and per subject category will be invited to become network validators.

Note: Authors may outsource the operational aspects of being a validator whilst retaining control and oversight. 

Network validators will have the responsibility to:

1. To inspect network transactions to ensure that they are valid, and then broadcast these valid transactions as blocks to the rest of the network.
2. Propose new resolutions to be voted by the community via smart contracts.
3. Propose and decide by majority vote, an arbitrator for resolving any transaction disputes.

In order to host a validator node, validators will need to ensure that they build their node to a specified standard to ensure a minimum level of security and transaction throughput.

## The Lightstreams Client

The Lightstreams client software will be open sourced licenced software. Key functional improvements will be specified via community proposals that are also voted on by the community. The Lightstreams Foundation will, however, reserve the right to veto specific proposals.

Development of client features will be undertaken by both open source development and core developers of the Lightstream Foundation. The Lightstream client will be initially developed for two target categories; desktop and mobile devices.

Desktop clients will contain the full feature set of the Lightstreams client. It is envisioned that the primary use of the desktop client will be for content producers to add and manage their digital content. However, consumers may also prefer to use this client to access content.

The mobile version will be a light client version that will be optimised for tablet and mobile phone devices. Due to network bandwidth and processing constraints, not all features will be available in this version.

## Go to Market Plan

The initial goal of the Lightstreams network and the scope of this paper is the development of a publishing channel for digital books, with the particular focus on the academic and technical books. By selecting this niche market category, we believe that this will give the greatest opportunity to maximise market traction by targeting the most likely early adopters, IT and technical professionals.

Once traction has been established and the network hardened to servce this niche market, horizontal expansion into other book categories will occur. Following this, Lightstreams will expand to other forms of digital content such as music and video streaming.

## The Lightstreams Foundation

The Lightstreams Foundation primary purpose will be to maintain a core team of developers that will build new features and fix bugs to maintain the competitive edge of the Lightstream client.

It is envisioned that the Lightstreams Foundation will be domiciled in Switzerland with development teams located primarily in Germany and Spain.

## Roadmap

Lightstreams has already finished its prototyping phase and plans to launch the network in Q1 2018. The following roadmap outlines the project's planned timeline.

| Project Phase / Milestone | Date      | Comments                                                                                                                                                                                                                                                                                                                                                  |
|---------------------------|-----------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Prototype                 | Completed | The prototype of using the Permissions Blocks protocol for content publishing has already been completed and demonstrated and won an award in May 2017 at the Consensus Hackathon 2017.                                                                                                                                                                                                                                                                                                                                                                                                              |
| Network launch            | Q1 2018   | It is planned that the network will launch in early 2018 where the first token of the platform will be available for sale. A major fundraising event will occur upon launch of the platform with the sale of LST tokens will occur, and customers will be immediately able to purchase digital content that is added to the network by content producers.  |
| Desktop client MVP        | Q2 2018   | The Minimal Viable Product version of the Lightstreams Desktop Client will be available for download. This will have a minimum function set for selling and purchasing of digital content.                                                                                                                                                                |
| Desktop client v1         | Q3 2018   | Version 1 of the Lightstreams Desktop Client will be available for download, which will have a more comprehensive function set.                                                                                                                                                                                                                           |
| Discovery Service         | Q3 2018   | The Lightstreams Discovery Service will be launched which will better assist users to search and browse for content.                                                                                                                                                                                                                                      |
| Mobile client MVP         | Q4 2018   | MVP Mobile Client will be launched where customers will be able to test the minimum functionalities for read and discover content.        
| Mobile client v1          | Q1 2019   | The Lightstream Mobile Client will be launched where customers can install an app on their tablet or mobile for reading or uploading content.        
| API/SDK                   | Q2 2019   | Release of an API / SDK to allow third parties to build on top of Lightstreams Network.        

## More resources
- [Lighstreams website](http://lightstreams.network)
- [Telegram group](https://t.me/joinchat/DZfAhw2IZSYcQchG3DPWaQ)
- [Twitter](https://twitter.com/lightstreams_io)
- [Blog](https://medium.com/lightstreams)

## Citations

- [[1]](http://autocontracts.io/) Autonomous Contracts http://autocontracts.io/
- [[2]](http://lightstreams.io/) The Lightstream Network http://lightstreams.io/
- [[3]](https://nextconf.eu/2016/09/next16-blockchain-will-build-web-3-0-says-jamie-burke/) Blockchain wil Build Wedb 3.0, Jamie Burke https://nextconf.eu/2016/09/next16-blockchain-will-build-web-3-0-says-jamie-burke/
- [[4]](https://bitsonblocks.net/2016/02/01/a-gentle-introduction-to-smart-contracts/) "A Gentle Introduction to Smart Contracts" by Antony Lewis https://bitsonblocks.net/2016/02/01/a-gentle-introduction-to-smart-contracts
- [[5]](https://mikesmo.github.io/blog/2017/06/09/Consensus-hackathon.html) Permissioned Blocks - Hackathon Win! Consensus 2017 https://mikesmo.github.io/blog/2017/06/09/Consensus-hackathon.html
- [[6]](https://github.com/autocontracts/permissioned-blocks) Permissioned Blocks White Paper https://github.com/autocontracts/permissioned-blocks
- [[7]](https://en.wikipedia.org/wiki/Peer-to-peer_file_sharing) Wikipedia: Peer-to-peer file sharing https://en.wikipedia.org/wiki/Peer-to-peer_file_sharing
- [[8]](https://ipfs.io/) IPFS - A peer-to-peer hypermedia protocol https://ipfs.io/
- [[9]](https://kdp.amazon.com/en_US/help/topic/A29FL26OKE7R7B) Amazon Kindle Direct Publishing Fees https://kdp.amazon.com/en_US/help/topic/A29FL26OKE7R7B
- [[10]](http://andrewhy.de/amazons-markup-of-digital-delivery-to-indie-authors-is-129000/) Amazon’s markup of digital delivery to indie authors is ~129,000% by Andrew Hyde http://andrewhy.de/amazons-markup-of-digital-delivery-to-indie-authors-is-129000/
- [[11]](https://kdp.amazon.com/en_US/help/topic/AI3QMVN4FMTXJ) Royalties in Kindle Unlimited and Kindle Owners' Lending Library https://kdp.amazon.com/en_US/help/topic/AI3QMVN4FMTXJ
- [[12]](https://teleread.org/2016/10/08/amazon-kdp-select-authors-are-losing-page-reads-apparently-due-to-software-glitches/) Amazon KDP Select authors are losing page reads, apparently due to software glitches by David VanDyke https://teleread.org/2016/10/08/amazon-kdp-select-authors-are-losing-page-reads-apparently-due-to-software-glitches/
- [[13]](https://jeanettevaughan.wordpress.com/2012/09/28/do-amazon-and-createspace-rip-off-indie-publishers-with-failure-to-correctly-report-sales/) Do Amazon and Createspace rip off Indie publishers with failure to correctly report sales? https://jeanettevaughan.wordpress.com/2012/09/28/do-amazon-and-createspace-rip-off-indie-publishers-with-failure-to-correctly-report-sales/
- [[14]](https://www.nytimes.com/2016/03/18/business/media/spotify-reaches-settlement-with-publishers-in-licensing-dispute.html) Spotify Reaches Settlement With Publishers in Licensing Dispute, New York Time March 17, 2016 https://www.nytimes.com/2016/03/18/business/media/spotify-reaches-settlement-with-publishers-in-licensing-dispute.html
- [[15]](http://www.campaignlive.co.uk/article/rootzoo-sues-facebook-ad-click-dispute/920220) RootZoo sues Facebook over ad click dispute http://www.campaignlive.co.uk/article/rootzoo-sues-facebook-ad-click-dispute/920220
- [[16]](https://www.theguardian.com/books/2010/jul/16/orlando-figes-fake-amazon-reviews) Historian Orlando Figes agrees to pay damages for fake reviews https://www.theguardian.com/books/2010/jul/16/orlando-figes-fake-amazon-reviews
- [[17]](https://github.com/ethereum/wiki/wiki/Mining) Ethereum Mining https://github.com/ethereum/wiki/wiki/Mining
- [[18]](https://cointelegraph.com/news/why-blockchain-needs-proof-of-authority-instead-of-proof-of-stake) Why Blockchain Needs ‘Proof of Authority’ Instead of ‘Proof of Stake’ https://cointelegraph.com/news/why-blockchain-needs-proof-of-authority-instead-of-proof-of-stake 
- [[19]](https://tendermint.com/) Tendermint - Byzantine fault-tolerant replicated state machines in any programming language https://tendermint.com/

