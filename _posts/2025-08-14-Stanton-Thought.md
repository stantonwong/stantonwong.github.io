---
layout: post
title: BNB Greenfield and the Evolution of Decentralized Computing Platforms
date: 2023-05-04 23:00:00 +0800
location: Shanghai
categories: [Crypto]
tags: crypto BNB_Chain BNB_Greenfield
---

With the recent launch of BNB Greenfield, there was an invitation to write about it via the [Greenfield Content Writing Contest](https://twitter.com/BNBCHAIN/status/1647193052262309888) (unfortunate that the contest seems to have disappeared, with all the websites supporting the contest having gone down and I have been ghosted as to where I stand, but might as well share here!). 

As decentralized services have always been a big interest of mine, I took the opportunity to practice my writing and do a deep dive into an exploration of the history and evolution of decentralized computing platforms, where it is now, and where they will go in the future.

I've always been fascinated with the decentralization of web services we use daily. The first decentralized service I followed was [Golem](https://www.golem.network/) (GNT), a project that was first launched in 2016 with the goal of providing a decentralized computing platform that allows users to rent out their unused computer power. Essentially, Golem was providing a decentralized marketplace for computing power where anyone can participate.

With the recent launch of [BNB Greenfield](https://greenfield.bnbchain.org/en), we have another entrant into the decentralized computing platform, so it's worth taking a look at where we started and where we are now.

The following is an exploration into the history and evolution of how we got to the decentralized computing platforms of today.

## The first decentralized computing projects
The concept of decentralized computing power has been around for a while. Back in 1999, [Berkeley SETI Research Center](https://en.wikipedia.org/wiki/Berkeley_SETI_Research_Center "Berkeley SETI Research Center") at the University of California, Berkeley started a project called [SETI@home](https://en.wikipedia.org/wiki/SETI@home), where people at home could install the [BOINC](https://en.wikipedia.org/wiki/Berkeley_Open_Infrastructure_for_Network_Computing) software and volunteer their computer's computing power to help do scientific work around detecting intelligent life outside of Earth.

The 3rd of such large-scale volunteer computing projects (the first 2 being [Great Internet Mersenne Prime Search](https://en.wikipedia.org/wiki/Great_Internet_Mersenne_Prime_Search "Great Internet Mersenne Prime Search") (GIMPS) was launched in 1996 and [distributed.net](https://en.wikipedia.org/wiki/Distributed.net "Distributed.net") in 1997), it tested the viability of volunteer computing with over 5.2 million participants worldwide donating their computing power, aggregating a total of 2 million years of aggregate computing time across its 21 years of operation.

The launch of SETI@home was back before cloud computing was widely available. Websites and online services were still hosted in localized data servers and there were no data center services that allowed you to easily spin up an instance like Amazon's EC2 and Microsoft's Azure Virtual Machines. The idea of leveraging unused processing power around the globe to supplement the extensive amount of processing needed for scientific research was a genius idea that came out of necessity and would lead the way to large investments in cloud computing, centralizing service offerings so it made sense from a business perspective.

## The Introduction of On-Demand Cloud Computing
The most well-known cloud computing service in the world today is Amazon's Amazon Web Services (AWS). It started in 2006 as a single product, Amazon Simple Storage Service (S3), and quickly expanded into over 300 services that are used by businesses of all sizes all over the world.

AWS started as an internal project to help launch an e-commerce service called Merchant.com to help third-party merchants like Target or Marks & Spencer build online shopping sites on top of Amazon's e-commerce engine[^1]. Due to poor future planning, the codebase became a jumbled mess, sparking the requirement to untangle the code into a set of well-documented APIs for ease of use.

This first step pushed for a more organized and disciplined approach to developing tools around database, computing, and storage, spreading internally to all of the teams in Amazon as having a common set of infrastructure services made it so that everyone could build without having to reinvent the wheel every time. And thus, AWS was born.

The market exploded as these computing and infrastructure services were not only extremely useful and cost-effective for Amazon's internal teams, but for any companies that required database, compute, and/or storage capabilities for their businesses, which was the majority of companies as we enter the late 2000s. With the successful launch of Amazon S3 in 2006, AWS would then launch Amazon Elastic Compute Cloud (EC2) in 2007, Amazon Relational Database Services (RDS) in 2008, and continue this pattern of launching a new service every year.

Today, the market for cloud computing and infrastructure services is valued at USD 484 billion dollars (as of 2022)[^2] with large, centralized players including Amazon, Microsoft, Google, and a myriad of others all offering similar on-demand cloud computing services.

## The Decentralized Opportunity in Web3
As centralized services continued to develop and innovate, a decentralized software economy was emerging with the start of Bitcoin and Ethereum. Bitcoin introduced the concept of the blockchain and a decentralized currency, while Ethereum added programmable smart contracts on top of that. With these two concepts, we usher in the start of Web3, where services that previously were only possible, from a business perspective, by being centralized, could now be offered in a decentralized way as well.

The big development is the opportunity to now build trustless transactions between mutually-distrusting parties. Using smart contracts, buyers and sellers can transact directly without an intermediary, and a truly trustless cloud storage marketplace is born.

As mentioned earlier, the first project to tackle this idea was [Golem](https://www.golem.network/), quickly followed by [SONM](https://sonm.com/). Both projects focused on distributed compute power, similar to the SETI@home project, and both were made possible by the introduction of smart contracts on the Ethereum blockchain, which is where they both run.

At the same time, distributed storage was being developed. The two first projects to take a stab at this was [Storj](https://www.storj.io/), launched in 2014, and [Sia](https://sia.tech/), launched in 2015. Both Storj and Sia provide a marketplace between a network of decentralized storage providers and users who are looking for storage. Instead of leveraging an existing blockchain, both projects opted to create their own blockchain, Storj on the Storj blockchain and Sia on the Sia blockchain.

In 2017, [Filecoin](https://filecoin.io/) and [Arweave](https://www.arweave.org/) also entered the space. Filecoin provides a similar decentralized service as Storj and Sia, offering a decentralized marketplace. Filecoin, built on top of Ethereum, takes advantage of the [InterPlanetary File System](https://ipfs.tech/) (IPFS), an open-source project building a distributed file system that splits the data and stores it in smaller chunks with a referencable unique fingerprint. Arweave, built on its own stand-alone blockchain, introduces a new idea and is designed as permanent storage as data is written onto the blockchain directly.

In 2020, [Flux](https://runonflux.io/) joins the mix with a focus on replicating AWS in a decentralized manner. Instead of just compute power or data storage, Flux offers instances to run your software in the same way that Amazon AWS, Microsoft Azure, and Google Cloud. This service is slightly more holistic than the previously mentioned projects and will attract a different audience.

In 2022, we have [Züs](https://zus.network/), introducing the idea of zero-knowledge proofs into the decentralized storage space. Züs's pitch leans on privacy and encryption, with the entirety of its stand-alone blockchain, previously known as 0Chain protocol, using zero-knowledge proofs, which allows data to be stored and accessed in a way where the owner does not need to share any details about the file itself for complete privacy (note this is not to say that the previous projects are not using encryption).

A myriad of projects is introducing their own takes on how to approach decentralized computing services. The opportunity lies in the fact that none of the players in this space have established dominance yet, leaving decentralized storage and decentralized computing platforms as a nascent Web3 space that is bound to grow as the technology continues to develop.

## Strengths and Weaknesses of Decentralized Storage
Taking a brief step back, why should we even consider decentralized storage? What are the benefits of decentralizing over the current centralized services?

If we do an initial breakdown, here are some considerations for decentralized storage:
- **Resilience:** Decentralized storage is more resilient to censorship and attack, as it is not stored on a single server.
- **Security:** Decentralized storage is more secure than centralized storage, as it is not controlled by a single entity.
- **Privacy:** Decentralized storage is more private than centralized storage, as users have more control over their data.
- **Cost-effectiveness:** Decentralized storage can be more cost-effective than centralized storage, as it can be shared by multiple users.
- **Scalability:** Decentralized storage can be scaled more easily than centralized storage, as it can be added to as needed.

The strengths are the same as any form of decentralization, where the distribution allows for much better resilience, security, and privacy, especially from global enforcement entities like governments. Decentralization also has the potential for cost-effectiveness, due to the lower overhead, and scalability as it introduces a lot more flexibility by allowing more service providers into the mix without the requirement of establishing formal business structures and large investments.

Of course, we shouldn't discount the weaknesses as well, which include:
- **Complexity:** Decentralized storage is more complex to set up and use than centralized storage.
- **Performance:** Decentralized storage can be slower than centralized storage, as it is distributed across multiple nodes.
- **Availability:** Decentralized storage can be less available than centralized storage, as it is dependent on the availability of multiple nodes.

Again, these weaknesses are applicable to all decentralized projects. Running trustless distributed nodes globally requires new software protocols to handle the complexity, which tends to have a hit on performance. As the projects are still growing, there will be limited availability. The great thing is that none of these weaknesses are unsolvable, with each project team already taking steps towards resolving them in their own way.

Back to the main question of why should we be looking at decentralized storage services at all. In the long term, the biggest reason might be censorship and data security.

Current centralized storage services are established and have a proven track record. Decentralized storage is a newer technology that is designed to be more resistant to censorship and hacking, but will require time to develop its technology and establish itself as a legitimate alternative to centralized services.

## Enter BNB Greenfield
The initial goal of this article was to introduce the new player into this space, so let's explore what kind of new interesting ideas and opportunities BNB Greenfield brings to decentralized storage.

[BNB Greenfield](https://greenfield.bnbchain.org/en) is a decentralized data storage system and economy built on the BNB Chain. Like the previously mentioned decentralized storage projects, BNB Greenfield also aims to provide a more secure, efficient, and cost-effective way to store data than traditional centralized storage solutions.

The most interesting angle that BNB Greenfield is taking advantage of is its ecosystem. BNB Greenfield will use BNB as its token, and although BNB Greenfield will operate on its own blockchain, it is designed to easily cross-chain between itself and the BNB Chain. That means that BNB Greenfield will be one of the go-to decentralized storage options for projects that are already in the BNB Chain ecosystem.

BNB Greenfield is also poised to take large advantage of its marketability as it is supported by BNB Chain's core team and part of Binance's larger plan to build out the different decentralized pieces that are needed for a thriving decentralized ecosystem. 

As it currently stands, BNB Greenfield isn't doing anything particularly unique in comparison to the other decentralized storage projects that are already in the market, but it is filling in an ecosystem void in the BNB Chain and is positioned to greatly take advantage of that synergy as the BNB Chain ecosystem continues to develop with its extensive number of community and educational initiatives.


## Decentralized Storage and the Future
Although there is now healthy competition in the decentralized storage space, competition really isn't between decentralized storage projects, but between decentralized and centralized offerings.

Users of decentralized storage services are typically other decentralized, or Web3, projects. But the real business value becomes apparent if decentralized storage becomes a desired option for traditional businesses. As mentioned previously, the global market for centralized storage services is USD 484 billion dollars. The long-term goal of decentralized storage services is to tap into this market.

But there are a lot of obstacles that still need to be overcome. The instability of cryptocurrencies that are used for payment, the additional computational and energy costs to powering this on a blockchain, the I/O speed of accessing data in storage, and redundancy services that guarantees that there will be no data lost[^3]. 

If these can be resolved, the trend toward decentralization will be inevitable. Decentralization provides individuals with the opportunity to invest in tangible services that they can control. 

Previously, it wasn't possible to individually and directly invest in projects unless you knew the founder of the company was able to IPO. Cryptocurrencies are changing that, providing everyone access to securities from the start.

Previously, it wasn't possible to individually and directly provide liquidity into the traditional financial system. Decentralized finance (DeFi) is changing that, providing decentralized services around borrowing and lending, trading, assets exchange, savings and yield products, synthetic assets, etc., that did not need any human intermediary in between.

Previously, it wasn't possible to individually and directly own game assets. Everything would be hosted in the central servers and if the servers ever shut down, you lost everything. Game finance (GameFi), with the help of NFTs, will offer the ability for games to surpass the value of its game ecosystem.

Previously, it wasn't possible to individually and directly provide compute and data storage services. Decentralized computing platforms are changing that, providing individuals with the opportunity to participate in the marketplace.

In conclusion, the decentralized storage space is still young and there is still a lot of catching up to do, but the potential for the entire space is huge. 

As for BNB Greenfield, it is still in testnet, so there's still a long way to go. In comparison to other decentralized storage projects, it is still not as mature from a product perspective as projects like Sia and Storj have been around for 6-7 years now. What BNB Greenfield brings to the table though is its ecosystem and the enormous support it has. It will be interesting to see how this translates to growth over the next few years.


## Footnotes
[^1]: https://techcrunch.com/2016/07/02/andy-jassys-brief-history-of-the-genesis-of-aws/
[^2]: https://www.grandviewresearch.com/industry-analysis/cloud-computing-industry
[^3]: https://blocksandfiles.com/2022/11/29/web3-storage/