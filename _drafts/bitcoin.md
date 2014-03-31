---
layout: post
title:  "The Three Phases of Changing Someone's Mind"
date:   2014-03-29 01:56:00AM

quote: | 
  I journeyed to the East <br/>
  And I struggled to stay afloat<br/>
  A solitary Buddhist Monk threw me a rope<br/>
  Looked me in the eye<br/>
  And said, "Don't make me say this twice<br/>
  You want to be a monk, you got to cook a lot of rice<br/>
linktext: Stay Frosty
linkurl: https://www.youtube.com/watch?v=7Mk1uifmAEw
---

--How miners make money
--What a wallet is (how you can find bitcoins)

After a conversation with my roommate, a smart but not overly technological guy,I realized that most people could understand bitcoin fairly easily with the explanation of a few underlying technologies and a few metaphors.

<h4>The Financial Network</h4>

First off, Bitcoin is a distributed system. Bitcoin "miners" are actually doing the math to verify transactions are legit. The decentralized network of miners is what accepts or rejects a transaction, and for their trouble, they get to mine bitcoins. They do this by, every time they successfully verify a group of transactions (a block), they add a transaction to it that says that the miner gets a certain number of bitcoin out of thin air. The system is set up so that this only happens every 10 minutes or so, giving the money supply a predictable growth, which is important for economic predictions. It also explains why bitcoin mining is a numbers game and unlikely to pay off these days, since there are so many other people out there trying to get that batch of free coins first.

At any rate, every time a block (group of transactions) is validated, it's added to the "blockchain", which is the giant ledger of every bitcoin transaction ever done, including the balances of every account in the system.

<h4>Not having two Bitcoin to rub together</h4>

These accounts, or what are called "wallets," are really the building block of the whole system. You don't have individual bitcoins floating around, what you have a zillions of accounts, each with some balance of bitcoins in them. A transaction subracts from one account's number and adds to another account's number. No "coin" per se are actually exchanged. 

Part of the way that bitcoin is so anonymous is that a wallet is a trivial thing and you can make them up at will. It would be just as easy to store 100 BTC in one wallet as to store 1 BTC in a hundred wallets. They are just logical groupings.

<h4>Cryptography Detour: Symmetric and Asymmetric</h4>
The underly technology of bitcoin is a concept called asymmetric encryption. Now, most the encryption we use today and what most people think of is symmetric encryption. You take your message, encrypt it with a given key, and then at the destination decrypt it with the same key and get the same message out. That's one way to do it, but it requires making sure the encryption key is an absolute secret.

On the other hand, there is a form of encryption where you don't have just one key, but two, and they are a pair. Encrypt a message with one and you need the other key to decrypt it; there's no way to find out one key if you know the other. This leands to what is also known as "public-key cryptography", named after the practice of publishing one key in the pair and keeping the other as a closley guarded secret.

If you encrypt an email with my public key and then send it to me, only somebody who can decrypt it with my private key can read it. And hopefully that's only me
