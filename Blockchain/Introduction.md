[< Back](./Blockchain.md) [Home](../README.md)

# Introduction

## What is Blockchain?

This is the question may of us ask at the beginning, when we hear others talk about it. Let me give you a short explanation about what Blockchain is and how it can help us.

Well, `blockchain` is, as the name itself states, a chain compose of blocks. These blocks contains data, timestamp and some block header information, where we can find a hash of all the data it contains.

Starting with the first block which is also called `genesis block`, the chain is build up by linking the blocks. The order of the blocks is given by a number… the block number.

By now you are asking yourself:
<em>Ok… So what’s so special about it?</em>

Well… Here comes the part where the block hash comes involved.

<img src="https://miro.medium.com/max/977/1*mNdCyhj2WRSzmgTOVztaUg.png">

In the header data of each block there are two hashes:

-   block hash - witch represents the current block hash (obviously)
-   previous block hash - which is the hash of the block before (this is also obviously).

So far, so good ? Let’s keep going.

Already you might have a question and also as a good reader you do not want to bother me with a question for what you know the answer. <em>Why in the image above the genesis block has 0’s for previous hash?</em> Well… It might have something to do with the fact that it is the fist block of the chain!? Just saying…

The current block hash is generated based on the information data it holds and previous block hash. This is done to secure the order of the blocks in chain and to add tamper proof on the data it holds.

If someone tries to change something from one block, starting with that block all the hashes must be generated again and updated trough the rest of the blocks. To battle this security problem, blockchain uses the concept of `distributed ledger`, witch means that all nodes in the network hold the same data, that is validated by all nodes and synchronized trough the network. Using a distributed network makes the blockchain technology more secure and harder to tamper with, making the attacker forced to obtain the control of 50% + 1 of the network. Saying this, the more nodes in the network, the more secure the network is.

<img src="https://www.seba.swiss/static/9bf6b53dc571b40802e651d90e64675c/54539/seba-the-bridge-figur-1-attack-on-a-blockchain-24092020_2000px.png">

<br>

---

## Content

[Home](../README.md)

-   [Blockchain](./Blockchain.md)
    -   [Introduction](./Introduction.md)
