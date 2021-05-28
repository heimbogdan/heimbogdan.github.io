# Introduction

## What is Blockchain?

This is the question may of us ask at the beginning, when we hear others talk about it. Let me give you a short explanation about what Blockchain is and how it can help us.

Well, `blockchain` is, as the name itself states, a chain compose of blocks. These blocks contains data, timestamp and some block header information, where we can find a hash of all the data it contains.

Starting with the first block which is also called `genesis block`, the chain is build up by linking the blocks. The order of the blocks is given by a number… the block number.

By now you are asking yourself:
<i>Ok… So what’s so special about it?</i>

Well… Here comes the part where the block hash comes involved.

<img src="https://miro.medium.com/max/977/1*mNdCyhj2WRSzmgTOVztaUg.png">

In the header data of each block there are two hashes:

-   block hash - witch represents the current block hash (obviously)
-   previous block hash - which is the hash of the block before (this is also obviously).

So far, so good ? Let’s keep going.

Already you might have a question and also as a good reader you do not want to bother me with a question for what you know the answer. <i>Why in the image above the genesis block has 0’s for previous hash?</i> - Well… It might have something to do with the fact that it is the fist block of the chain!? Just saying…
