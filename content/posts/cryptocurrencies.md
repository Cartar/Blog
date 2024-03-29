---
title: "The value of Cryptocurrencies"
subtitle: "How much is good to have?"
date: 2022-07-23T00:24:08-04:00
categories: ["Posts"]
draft: true
---

I recall back in 2015 learning about Bitcoin, and thinking the idea was pretty cool. Problem was, I had very little time, and no money to invest, so the idea of buying Bitcoin remained on the todo list for an older me. In 2017, I revisited the idea, this time with a bit of money, but as I started to look into how to actually make a purchase, the market suddenly caught fire, and I felt I’d missed whatever opportunity had been present. Once again, buying crypto was put in the backseat for another day.

Fast forward to 2022, and I’ve finally figured out how to purchase crypto currencies, but I’m now convinced their value is 100% sentimental. Largely thanks to the financial education Rational Reminder has provided, it is clear that blockchains are a terrible form of currency. As I’ve learnt more about the technology, I still think it’s cool, but it isn’t all that innovative. The main innovation was how the software promised to revolutionize our financial system - which now feels like a debunked idea. It’s too slow at processing transactions, has no (reasonable) method of disputing fraud or mistakes of any kind, is rife with illegal activity (i.e., lots of fraud, money laundering, and ransoms), terrible for the environment, and isn’t actually cheaper than alternatives (i.e., PayPal) [1-3]. Not to mention the insane volatility in your purchasing power!

Adding insult to injury, crypto currencies are not actually decentralized. There is a small handful of miners with 51% stake majorities in every major algorithm, and most people purchasing crypto or NFT’s do so via centralized platforms that do not always complete your purchase “on-chain”, and often lend out holdings creating complicated financial structures that look somewhat circular and dangerously close to ponzi schemes. Therefore, it comes as no surprise when exchanges are forced into bankruptcy, at the cost of their patrons [4]. Crypto bubbles like this are similar to the 2008 financial crisis, except the US gov isn't bailing anyone out.

If using exchanges scares you (which it should), then you’re stuck with 2 options to complete a crypto currency transaction: i) barter with another person, and trust the blockchain transaction will post after the money has swapped hands (either in person with cash, or via global payment systems - like PayPal), or ii) trust an online peer-to-peer intermediary (who’s charging 1-2% on the trade) along with the anonymous peer you've been chatting with over some webforum, or exchange marketplace. None of this is regulated, and it is very time consuming. Not to mention inconvenient, and a costly way to move money around. Not just for the environment, but your wallet too.

Oh, and unless you use a central platform, you'll have to submit the transaction authorization to the ledger yourself. Without going into any details, let's just say this isn't something you can do over your phone.

Sure, in a world where your company is paying you in Bitcoin, it’s not too bad. Most people are fine with the banks charging us a 2.5% markup when we move CAD to USD (although there are ways around this [5]). But the truth is, crypto currencies do not purchase any goods you actually need to live. Housing, food, utilities, etc. Sure, it provides you with some entertainment. But it’s the same entertainment you could have at an online casino.

One more thing. People don’t realize the power these central platforms have. Take for instance non-fungible tokens (NFTs). They've gained notoriety as a method for displaying ownership of digital art. Pretty neat idea, a permanent record on the internet of digital art ownership forever. So how does it work? I'll let Moxie Marlinspike explain [6]:

> "NFTs generally do not store [images] on-chain. For most NFTs of most images, that would be much too expensive.

> Instead of storing the data on-chain, NFTs instead contain a URL that points to the data. What surprised me about the standards was that there’s no hash commitment for the data located at the URL. Looking at many of the NFTs on popular marketplaces being sold for tens, hundreds, or millions of dollars, that URL often just points to some virtual private server running Apache somewhere. Anyone with access to that machine, anyone who buys that domain name in the future, or anyone who compromises that machine can change the image, title, description, etc for the NFT to whatever they’d like at any time (regardless of whether or not they “own” the token). There’s nothing in the NFT spec that tells you what the image “should” be, or even allows you to confirm whether something is the 'correct' image."

Not so great if your art's URL is outside of some central crypto platform. You'd have no certainty that the art would last. But, how much certainty do you have when uploading to a platform instead? Let's look at the dominant marketplace for NFT's, OpenSea. Last I checked, OpenSea does something like 90+% of all NFT transactions [7], making them your most likely choice to get started. So suppose you upload some digital art to OpenSea, to sell as an NFT. Is it possible for them to alter it, or take it down? Turns out, the answer is yes! Moxie was experimenting with this exact question, and had his art delisted from their marketplace, without reason, and without having broken their terms of service [6]. He then continues to explain:

> “What I found most interesting, though, is that after OpenSea removed my NFT, it also no longer appeared in any crypto wallet on my device. This is web3, though, how is that possible?"

Skipping over the interesting details (worth a full read at ref. 6), the short answer is because OpenSea is so dominant, digital wallets just request to view NFT's through their API. Moxie again:

> "if your NFT is removed from OpenSea, it also disappears from your [digital] wallet. It doesn’t functionally matter that my NFT is indelibly on the blockchain somewhere, because the wallet (and increasingly everything else in the ecosystem) is just using the OpenSea API to display NFTs, which began returning 304 No Content for the query of NFTs owned by my address!” [6]

So in short, having your NFT removed from OpenSea is essentially the same thing as having it removed from the blockchain. So much for decentralization. But yay for VC backed central platforms?

And if you want to do all the work yourself, purchasing NFTs without an exchange, good luck to you. Not only do you need to be highly proficient in computer science, but you’ll need to be good at interpreting law now too. And if you make a mistake in the code? You could lose everything, with absolutely zero recourse.

So, most likely, you’ll trust the central exchange to do the coding for you instead. After all, they’ve had their code audited! It couldn’t possibly have bugs in it. Well, you’d be surprised to find that indeed, these platforms do make errors, and indeed it does lead to theft. Even after audits [8] (FYI reference 8 demonstrates some of the code you'll be working with in this brave new world).

This isn’t to say there isn’t value here. Crypto currencies and NFT’s have a massive influence on people, and that influence can keep the value moving up. Beyond influence, crypto provides people a convenient way to feel like they’re going to become rich. After all, they’ve seen it happen to other people, and the technology is supposed to be the internet 2.0! Or was that 3.0? The banks are corrupt, and we need DeFi tools to build the future! Just don’t think too hard about how these algorithms are not made to be viewable from your web-browser, or viewed on your smartphone (which is to say nothing about writing to the blockchain from those locations). So what if you need to spin up your own server to participate without a VC backed central platform? It can’t be that hard, can it? (rhetorical question, for those actually wondering, the answer is a resounding yes [6]).

At last, you almost give up. But quickly remember that private blockchains will prevail if nothing else! They’ll be more efficient, and save companies and customers money. Blockchain technology has been saved. I even heard about how Walmart is using it, and they’re basically a tech company, right? Well, all a private blockchains is, is an immutable write only data storage ledger, which has been around since the 60’s [2]. That’s right, the 60s. The only real innovation here is creating a new way for software and PR departments to spend more time together.

So next time you hear about how NFT’s are going to the moon [9], or how each bitcoin could one day be worth $10 million [10], remember that the only thing keeping these dreams alive are the hype themselves. 


### References:
1. https://rationalreminder.ca/podcast/crypto5
2. https://rationalreminder.ca/podcast/crypto6 
3. https://rationalreminder.ca/podcast/crypto7
4. https://web3isgoinggreat.com/?id=celsius-customers-send-letters-to-the-judge-in-the-bankruptcy-case
5. https://wealthsavvy.ca/norberts-gambit-questrade/
6. https://moxie.org/2022/01/07/web3-first-impressions.html 
7. https://etherscan.io/nfttracker
8. https://www.youtube.com/watch?v=sMANc7K4lHk 
9. https://future.com/podcasts/nfts-explainer/
10. https://coinmarketcap.com/alexandria/article/bitcoin-price-history-and-events-timeline 
