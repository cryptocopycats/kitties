# kittyverse.json

Free open public domain data for cryptokitties and copycats in JSON incl. fancies, cattributes, trait types, traits, genes, and more - No API key required ;-)


<!-- add - why? why not?
[traits.json](#traitsjson)  •
[fancies.json](#fanciesjson)  •
[purrstiges.json](#purrstigesjson)
-->


## traits.json

Example - All 12 Trait Types with 32 Traits - [`traits.json`](https://raw.githubusercontent.com/cryptocopycats/kitties/master/kittyverse.json/traits.json):

``` json
{
  "body": {
    "genes": "0-3",
    "name": "Fur",
    "code": "FU",
    "kai": {
      "1": "savannah",
      "2": "selkirk",
      "3": "chantilly",
      "4": "birman",
      "5": "koladiviya",
      "6": "bobtail",
      "7": "manul",
      "8": "pixiebob",
      "9": "siberian",
      "a": "cymric",
      "b": "chartreux",
      "c": "himalayan",
      "d": "munchkin",
      "e": "sphynx",
      "f": "ragamuffin",
      "g": "ragdoll",
      "h": "norwegianforest",
      "i": "mekong",
      "j": "highlander",
      "k": "balinese",
      "m": "lynx",
      "n": "mainecoon",
      "o": "laperm",
      "p": "persian",
      "q": "fox",
      "r": "kurilian",
      "s": "toyger",
      "t": "manx",
      "u": "lykoi",
      "v": "burmilla",
      "w": "liger",
      "x": ""
    }
  },
  ...
 }
```


## fancies.json

Example - All Fancy Cats (Normal, Exclusive, Special Edition) with Trait Recipes, Max Limits, IDs, Time Windows, and More - [`fancies.json`](https://raw.githubusercontent.com/cryptocopycats/kitties/master/kittyverse.json/fancies.json):

``` json
{
  "tallythepurrocious": {
    "name": "Tally the Purrocious",
    "recipe": {
      "time": { "start": "2019-01-10", "end": "2019-01-21" },
      "traits": ["selkirk", "koala", "arcreactor", "sully" ]},
    "desc": "Mystical Cat Talisman - Gods Unchained Promotion"
  },
  "aeoncat": {
    "name": "Aeoncat",
    "specialedition": {
      "time": {"start": "2019-01-17", "end": "2019-01-28"},
      "limit": 380 },
    "desc": "Goddess Aeona - Goddess of Nature - Gods Unchained Promotion"
  },
  "hypurrion": {
    "name": "Hypurrion",
    "date": "2019-01-10",
    "exclusive": {
       "limit": 1, "ids": [269] },
    "desc": "Hyperion - Mythic Titan of Light - Gods Unchained Promotion"
  },
  "catzy": {
    "name": "Catzy",
    "date": "2018-12-31",
    "specialedition": {
      "limit": 10, "ids": [1137653,1137654,1137655,1137656,1137657,
                           1137658,1137659,1137660,1137661,1137662] },
    "desc": "Changpeng \"CZ\" Zhao - CEO of Binance - Top 10 Blockchain Influencer of the Year 2018 by CoinDesk"
  },
  ...
}
```


## purrstiges.json

Example - All Purrstige Cattributes with Trait Recipes, Time Windows, and More - [`purrstiges.json`](https://raw.githubusercontent.com/cryptocopycats/kitties/master/kittyverse.json/purrstiges.json):

``` json
{
  "bionic": {
    "name": "Bionic",
    "recipe": {
      "time": { "start": "2019-05-01", "end": "2019-08-31" },
      "traits": ["ragdoll",
                 "WE05",
                 ["totesbasic 1", "totesbasic 2", "totesbasic 3"],
                 "PU30"]}
  },
  ...
}
```



## How to Use the Public JSON HTTP API (Micro) Web Service - No API Key Required ;-)

Use the "raw" links served by GitHub (otherwise you get the complete "formatted" GitHub web page).
Example:

```
$ curl https://raw.githubusercontent.com/cryptocopycats/kitties/master/kittyverse.json/traits.json
```



## Updates / Contributions Welcome - Please Update the Source Text Files

Note: The JSON files get (auto-)generated using the kittyverse library and datasets, thus, **please do NOT
edit the JSON files but the source text files in the kittyverse repo** e.g.:

- Trait Types and Traits in [`/kittyverse/../traits.rb`](https://github.com/cryptocopycats/kittyverse/blob/master/lib/kittyverse/config/traits.rb)
- Fancy Cats (Exclusives, Special Editions, etc.) in [`/kittyverse/../fancies.rb`](https://github.com/cryptocopycats/kittyverse/blob/master/lib/kittyverse/config/fancies.rb)
- Purrstige Cattributes in [`/kittyverse/../purrstiges.rb`](https://github.com/cryptocopycats/kittyverse/blob/master/lib/kittyverse/config/purrstiges.rb)





## Questions? Comments?

Post them on the [cryptokitties reddit](https://www.reddit.com/r/cryptokitties). Thanks.
