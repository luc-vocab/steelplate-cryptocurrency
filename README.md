After following Bitcoin and Cryptocurrencies for a few years, one thing became very obvious to me. The number one risk when investing is not hacking or security flaws, it's **user error**. It's so incredibly easy to lose access to your private keys.
* [Hard Drive lost with 7,500 bitcoins](https://www.theguardian.com/technology/2013/nov/27/hard-drive-bitcoin-landfill-site)
* [Lost 900 Ether due to incorrect use of password manager](https://www.reddit.com/r/ethtrader/comments/4wpn3v/how_i_just_lost_900_eth_a_cautionary_tale/)
* [I Forgot My PIN: An Epic Tale of Losing $30,000 in Bitcoin](https://www.wired.com/story/i-forgot-my-pin-an-epic-tale-of-losing-dollar30000-in-bitcoin/)

This page is meant to list conventional best practices on hold to hold crypto-currency in an ultra-secure manner. I'm open to feedback on this, please email [contact@bulletproofbitcoin.com](mailto:contact@bulletproofbitcoin.com)

# Good practices
* Holding your coins on an exchange, even a reputable one, even with 2FA enabled, is risky. Someone could impersonate you and steal your funds within minutes, while you are sleeping. The exchange could get hacked. You will not get your coins back if that happens.
* The only sane way to store bitcoin / other crypto currencies is using a hardware wallet. Get yourself a [Trezor](https://trezor.io/) or [Nano Ledger S](https://www.ledgerwallet.com/)
* During the setup of your hardware wallet, you'll be asked to write down a 24 word (BIP39) passphrase (the "recovery seed"). Properly securing that passphrase is the most important step of the setup. This is the passphrase that you will stamp onto a plate of metal to preserve it for decades to come. Losing or destroying your hardware wallet would not affect you in any way, as long as you safeguard that recovery seed, you will still have access to your funds.
* You must be the only person to see your recovery seed. Do not ask someone else to stamp it into metal for you.
* **NEVER** enter your recovery seed into any electronic device, file, even a password manager. The recovery seed will be shown to you ONCE on the screen of your hardware wallet. It should never be typed onto a desktop computer / smartphone as those environments are vulnerable to hacking by malware. You may write it down on paper temporarily in a private location, until you have a chance to secure the materials for stamping on metal.

# Steel Plates

These steel plates are designed to have a BIP39 24 (or 25) word passphrase stamped onto them, using a letter punch kit, to allow recovery of crypto currency private keys. Whether for use with a software wallet, or a hardware wallet like the Trezor, having the recovery passphrase stamped onto corrosion-proof and fire-proof metal plates minimizes the risk of loss of private keys.

The plates can be ordered from [Lasergist](http://lasergist.com) using instructions below. They are laser-cut from 3mm stainless steel or any other thickness available on lasergist. Technically, the middle plate is the only one required and has laser markings indicating passphrase word ordering. By having additional plates cut, the passphrase can be hidden from sight and zipties can be added to prevent tampering. It also increases the weight of the whole assembly (close to 1kg with 3x 3mm plates) which helps prevent accidental misplacement.

![](http://res.cloudinary.com/photozzap/image/upload/c_scale,w_1024/v1507346680/steelplates-crytocurrency/P1130023.jpg)

![](http://res.cloudinary.com/photozzap/image/upload/c_scale,w_1024/v1507346679/steelplates-crytocurrency/P1130020.jpg)

![](http://res.cloudinary.com/photozzap/image/upload/c_scale,w_1024/v1507346650/steelplates-crytocurrency/P1130018.jpg)

[More Photos](https://imgur.com/a/aznE4)

## Build Instructions

### Design Files 

Below is a description of the Adobe Illustrator files used to place the order from Lasergist.

If you just want the passphrase plate with the 25 locations to stamp words, the two files below are all you need.
* [numbers_plate_shape.ai](https://github.com/lucwastiaux/steelplate-cryptocurrency/raw/master/plates/numbers_plate_shape.ai)
* [numbers_plate_laser.ai](https://github.com/lucwastiaux/steelplate-cryptocurrency/raw/master/plates/numbers_plate_laser.ai)

If you want the front plate with your name on it, you need to submit these two as well (modify  	**frontplate_laser.ai** to include whatever text you want)
* [frontplate_shape.ai](https://github.com/lucwastiaux/steelplate-cryptocurrency/raw/master/plates/frontplate_shape.ai)
* [frontplate_laser.ai](https://github.com/lucwastiaux/steelplate-cryptocurrency/raw/master/plates/frontplate_laser.ai)

This plate is just an empty plate with the cutouts for screws, but no laser engravings:
* [backplate.ai](https://github.com/lucwastiaux/steelplate-cryptocurrency/raw/master/plates/backplate.ai)

And finally this files contains all above designs on different layers, which may be useful if you wish to customize the design further.
* [template_1.ai](https://github.com/lucwastiaux/steelplate-cryptocurrency/raw/master/plates/template_1.ai)

### How to order from Lasergist.com

Head over to [lasergist](http://lasergist.com), start a new design

You will want to submit **numbers_plate_shape.ai** and **numbers_plate_laser.ai**, with the following options:
* Material: AISI 316 - Brushed
* Thickness: 3.0 mm
* Height: 134mm
* Width: 111mm
* Path Length: 2967mm
* Extras: Laser Engraving, Sandblasting

You may change the thickness and material used, and uncheck sandblasting if you wish (selecting different options may change the price). But with the above settings, the price for that plate comes out to **USD $85.53**.

Then depending on whether you want the other plates, repeat the process for **frontplate_shape.ai**, **frontplate_laser.ai** (of course you'll want to modify them first before submitting). With similar settings to above, it came out to **USD $59.57**

The backplate, **backplate.ai** doesn't require any laser engraving and cost **$49.10** with the following settings:
* Material: AISI 316 - Brushed
* Thickness: 3.0 mm
* Height: 134mm
* Width: 111mm
* Path Length: 730mm
* Extras: Sandblasting

### Additional Hardware

If you ordered seperate plates and want to fasten them together, you may order the following screws:
* [M4 x 0.7 mm Thread, 12 mm Long](https://www.mcmaster.com/#93070A103)
* [M4 x 0.7 mm Thread Hex Nut](https://www.mcmaster.com/#98676A200)

The 12mm screws are sufficient to hold 3x 3mm plates. If you have less plates, less thick, or more (perhaps you have different seeds for different coins), then you'll need to get different screws.

Then additionally, you'll want the letter punch kit. I ordered this one from ebay: [letter punch kit](http://www.ebay.com/itm/36pcs-4mm-New-Stamps-Letters-Alphabet-Numbers-Set-Punch-Steel-Metal-Tool-Craft/142456142451?ssPageName=STRK%3AMEBIDX%3AIT&_trksid=p2060353.m2749.l2649). The design on the plate is designed to accomodate words at least 8 characters long, with each letter 4mm x 4mm.

Finally, you can order zip ties to prevent tampering with the seed.

### Any Questions ?
Feel free to ask those on the [Reddit Thread](https://www.reddit.com/r/Bitcoin/comments/72zj1y/bip39_recovery_seed_stamped_on_stainless_steel/)

Also if you like this design, feel free to send me a tip !
* **BTC: 39YGSE5M9b9ch4Xe4WHKRxyXVSm1cXmXZW**
* **Litecoin: MFzrhQuRMz7KL9kj8VVVVSMPcs17Yn7YFD**

# Alternatives
## Cryptosteel
[cryptosteel.com](https://cryptosteel.com/)
## ColdTI
[coldti.com](https://coldti.com/)
## Simple Metal plate
Order a simple stainless steel or titanium plate from Ebay and punch it. It may be difficult to find the right size, but this is the cheapest option of them all.
## Piece of Paper
You could just write your seed on a piece of paper, but a piece of paper is easy to misplace, the ink may fade, flood and fire are a concern. Hard to protect against tampering.

[![Analytics](https://ga-beacon.appspot.com/UA-107710882-1/home)](http://steelplate.cc)
