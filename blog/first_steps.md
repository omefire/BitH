# Getting started on HaskellBitcoin
There's two technologies I've been interested in for some time now.
I'd like to improve my skills and understanding on bitcoin tech & Haskell tech.
So, I've decided to embark on building a bitcoin wallet written in Haskell.

The intent here is not to have a production ready wallet, but rather teach myself
the intricacies of bitcoin's inner data structures and how it works and what makes it tick.

### First steps
The first thing I did was to install bitcoin on my ubuntu development box:
    ```http://bitzuma.com/posts/compile-bitcoin-core-from-source-on-ubuntu/```

### Stepping through Bitcoin Core code
One of the first things that need to be done first is to find the entry point of the
Bitcoin Core program, and follow how it handles startup.

The main entry point of the graphical version of Bitcoin Core is: 
    ```https://github.com/bitcoin/bitcoin/blob/48b5b84ee511d5ccd0d47bb0018c1b3c9ddebeff/src/qt/bitcoin.cpp#L508```

