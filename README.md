# Purpose of this repository
YARA is a powerful piece of Software. It is called "The pattern matching swiss
knife for malware researchers (and everyone else)". More information about YARA
can be found here: [http://virustotal.github.io/yara/](http://virustotal.github.io/yara/)

Besides looking for malware there are other possible types of usage for this
great tool. So I decided to collect YARA-rules in this repository, that I wrote
myself for different purposes.


## Table of Contents
- [1. Cryptocurrencies](##1.cryptocurrencies)
    - [1.1 Seeds](###1.1seeds)


## 1. Cryptocurrencies
### 1.1 Seeds
When conducting IT-forensic analysis of computers concerning the usage of
cryptocurrencies, you might think about using YARA for scanning the files
in order to find documents that likely contain a seed.

Seeds are randomly chosen words from a dictionary. The number of words used
is more or less standardized. In detail it depends on the cryptocurrency at
focus.

- `wordlist_btc_eng.yar` is a simple YARA-rule for the cryptocurrency
Bitcoin (BTC)
- `wordlist_xmr_ger.yar` and `wordlist_xmr_eng.yar`
are simple YARA-rules for Monero (XMR) concerning the German respectively English
dictionaries.
