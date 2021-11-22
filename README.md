This tests connecting to WalletConnect, and sending a very large transaction - the
constructor for an ERC721 Token.

You must have Rinkeby on your wallet account to create the constructor.

TODO: Add minting using 'mintUsingSequentialTokenId()'

The code uses simple unprocessed in-browser JavaScript.
Dependencies, like the Web3Modal library itself,
are loaded over Unpkg CDN. The code is extensively
commented and short.

Originally sourced from:

[Web3modal](https://github.com/web3modal/web3modal))

# Web3 wallets and HTTPS hosting limitations

Because of limitations how wallet operate within a web browser
and web security,
you should not run this example, or any Web3modal code,
out of your file system or insecure HTTP protocol
(even using localhost).

Setup on Windows:

```
npm i -g --only=prod https-localhost
serve
```

UNIX style:

```sh
npm i -g --only=prod https-localhost
sudo serve .
```

... in the folder of index.html file.

Then you can visit https://localhost to open the example.

# Publishing example on Github

To republish the example:

```sh
git push origin master:gh-pages
```

