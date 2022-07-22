# NewBull Block Explorer

[SpiderByte Block Explorer](https://github.com/typhoonsimon/spiderByteBlockExplorer) is a simple and lightweight block explorer written in PHP(no database required).

SpiderByte Block Explorer work with [SpiderByte](https://spiderbyte.co) fine. It's should work with others pow/pos/hybrid block chain, such as Bitcoin, Litecoin, etc.

## Requirements

-   Linux or Windows server of running SpiderByte Wallet
-   Apache 2.4.x
-   PHP 5.6.x with CURL and JSON support enabled

## Installation

Installation is quite simple, and just complete the following steps:

-   Upload the contents of the archive to your server.
-   Modify the conf/config.php file with your own info and NewBull RPC info.
-   That's it! Open your any Modern Browsers to the install URL, and the block explorer should come up.

Note:

1. If you do not know about apache url_rewrite, please turn off the url_rewrite configuration in conf/config.php file;

## Usage

Below shows the URLs available:

-   / = Home page, showig recent blocks list.
-   /block/HEIGHT = displays all detail and txs within a block.
-   /blockhash/HASH = displays all detail and txs within a block.
-   /tx/TXID = View a single tx

## Theme / Template Modifications

-   Content css, js, img, pages, header and footer files are in /themes/theme1/ directory.
-   CSS uses Bootstrap 3.x as requested.

## Donations

---

NB: NbUSBit9Q8mrDYPMwv6fW17rykThe3X735

ETH: 0xdA667f1921A2e454A1cD3E9D90c75a7c0EE94193

BTC:

LTC:

## License

---

MIT

## Changelog (from NewBull original)

2.0.0 2022-07-22

first release of SpiderByte explorer;

make it work with hybrid pow/pos block generation;

removed all warnings and notices that appear with PHP 7+;

1.7.0 2021-11-27

add stats page;

make the block hash display shorter;

1.6.0 2021-05-31

add chaintips page;

1.5.2 2020-10-06

add retarget_diff_since;

1.5.1 2020-09-30

format weight same as size;

1.5.0 2020-09-25

add: block weight and version hex;

1.4.0 2020-05-18

remove: no longer used code;

fix: bug;

1.3.0 2020-03-28

add: next difficulty estimate;

1.2.0 2019-12-27

add: memory pool list;

1.1.0 2019-12-13

add: root_path in conf/config.php file;

fix: explorer_path in conf/config.php file;

1.0.0 2019-05-09

refactor;

0.9.0 2019-02-21

fix bug;

0.8.0 2018-06-14

refactor;

0.7.0 2018-01-04

fix bug;

0.6.0 2017-11-27

add theme system;

0.5.0 2017-09-06

fix bug;

0.4.0 2017-09-05

add some features;

0.3.0 2017-04-30

fix bug;

0.2.0 2017-04-29

add feature;

0.1.0 2017-04-23

first release;
