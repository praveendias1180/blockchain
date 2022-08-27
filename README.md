# SHA 256

## Fact: SHA 256 of Empty String

```
e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855
```

SHA 256 of empty string will be always the above string.


## SHA 256 of Praveen

```
a95a2ca6166bcb55a969401a63e960ada7295a27183500b321ac3f7c4cc6e681
```

https://emn178.github.io/online-tools/sha256.html

![](sha-meter.png)

# SHA-2

SHA-2 (Secure Hash Algorithm 2) is a set of cryptographic hash functions designed by the United States National Security Agency (NSA) and first published in 2001.[3][4] They are built using the Merkle–Damgård construction, from a one-way compression function itself built using the Davies–Meyer structure from a specialized block cipher.

https://en.wikipedia.org/wiki/SHA-2

# Blocks

## Original Block

![](original.png)

Now let's enter 'Data'. Data = 'hi'. Immediately the Hash will be changed. And try to find a Nonce such that Hash starts with '0000' again. Put 1 in the Nonce. Then 2, 3, 4, etc.

NO! don't do it manually. Click the 'Mine' button.

## Mined!

![](mined.png)

# Blockchain

We can chain the above described blocks to create a blockchain.

![](blockchain.png)

And if change the data in a block all blocks after that block will be invalid (Will not start the hash with '0000')

![](broken.png)

You will have to remine all the successive blocks after change.

