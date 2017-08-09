## What's this?

This is a fork of [vanitygen](https://github.com/samr7/vanitygen) by [samr7](https://github.com/samr7) that able to generate valid [Signatum](https://signatum.io/)  Coin addresses.

Didn't here about Signatum? Here some useful links:

* [Signatum Official Site](https://signatum.io/#home) 
* Signatum on [bitcointalk](https://bitcointalk.org/index.php?topic=2030529.665) 
* Signatum on [forum.bits.media ](https://forum.bits.media/index.php?/topic/43549-sigt-signatum-skunkhash-pos/) (russian crypto-currencies related forum)
* [SIGT/BTC Market](https://www.cryptopia.co.nz/Exchange/?market=SIGT_BTC) on Cryptopia

### How to use?

Examples:

	./oclvanitygen -k -B B%your_pattern_for_address%
	./vanitygen -B B%your_pattern_for_address%
	
Than open your signatum-qt wallet, Help -> Debug -> Console and enter generated privkey throught importprivkey command.

	importprivkey <signatumprivkey> [label] [rescan=true]
	Adds a private key (as returned by dumpprivkey) to your wallet.
	
### Donate

If you find this project usefull you can donate some SIGT:

* BDeckerHRgbmfADQd4CY4jv19tTkXXTNPH ([Block Explorer](http://explorer.signatum.io/address/BDeckerHRgbmfADQd4CY4jv19tTkXXTNPH))