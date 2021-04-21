

---

**A message from the CryptoKitties makers:**

**You've been permanently banned from participating in r/CryptoKitties. You won't be able to post or comment. Reason: Self-promotion.**

Yes, Dapper Labs - the $7.5 billion dollar CryptoKitties gambling operator & promotor - falesly (or is that fraudulently?) 
claiming it's a "video game with cute-little cartoon cats that you own 100%" - 
censors this author's public service message. Remember - I do not get paid for updating the datasets here.
In response to continue posting I've opened-up a new dev channel **[r/CryptoKittiesDev](https://old.reddit.com/r/CryptoKittiesDev/)**. Join us.

---


# (Crypto) Kitties on the Blockchain



## Datasets

### cryptokitties.csv  - Kitties by ID with Gen(eration), Matron & Sire IDs, Birthdate, Genes, & More

(Crypto) kitties dataset in comma-separated values (CSV) format
in blocks of a thousand kitties each
(e.g.
[`000.csv`](1-99_999/000.csv) incl. 1-999,
[`001.csv`](1-99_999/001.csv) incl. 1000-1999,
[`002.csv`](1-99_999/002.csv) incl. 2000-2999, and so on).
The data records for kitties
incl. id, gen(eration), matron+sire ids, birthdate,
48 (12x4) genes in kai (base32) notation, and more.
Example - [`1-99_999/000.csv`](1-99_999/000.csv):

```
id,gen,matron_id,sire_id,birthdate,genes,name
1,0,,,2017-11-23 06:19:59,ccac 7787 fa7f afaa 1646 7755 f9ee 4444 6766 7366 cccc eede,
2,0,,,2017-11-23 06:19:59,ca9c 7575 f442 af9g 6664 5557 7777 4444 6686 8667 cccc ffec,
3,0,,,2017-11-23 06:19:59,ac9a 6686 ff7f 99aa 6666 5575 779f 4444 6786 7748 cccc dcfc,
4,0,,,2017-11-23 06:19:59,ccac 5686 22ff f99g 1616 7555 ffed 4444 8668 4687 cccc dcff,
5,0,,,2017-11-23 06:19:59,ca9c 8777 747f g99g 4411 7775 f77d 4444 7788 6377 cccc ffef,
...
```

### cattributes.csv  - All Cattributes (Incl. Purrstige) by Rarity & Popularity

Cattributes dataset in comma-separated values (CSV) format.
Example:

```
Total,  Description,  Type
   120, purrior,      prestige
   140, scout,        prestige
   141, dominator,    prestige
   144, centurion,    prestige
   162, explorer,     prestige
...
255855, kittencream , colortertiary
263531, happygokitty, mouth
287510, pouty,        mouth
309267, thicccbrowz,  eyes
408249, totesbasic,   pattern
```

For more see [**cattributes.csv »**](cattributes.csv)



### kittyverse.json  - All Traits and Trait Types, All Fancy Cats (Normal, Exclusive, Special Edition), All Purrstige Cattributes, & More

Datasets include:

- [`traits.json`](https://raw.githubusercontent.com/cryptocopycats/kitties/master/kittyverse.json/traits.json) - all 12 trait types with 32 traits
- [`fancies.json`](https://raw.githubusercontent.com/cryptocopycats/kitties/master/kittyverse.json/fancies.json), [`exclusives.json`](https://raw.githubusercontent.com/cryptocopycats/kitties/master/kittyverse.json/exclusives.json), [`special-editions.json`](https://raw.githubusercontent.com/cryptocopycats/kitties/master/kittyverse.json/special-editions.json) - all fancy cats (normal, exclusive, special edition) with trait recipes, max limits, IDs, time windows, and more
- [`purrstiges.json`](https://raw.githubusercontent.com/cryptocopycats/kitties/master/kittyverse.json/purrstiges.json) - all purrstige cattributes with trait recipes, time windows, and more


For more see [**kittyverse.json »**](kittyverse.json)




## Tools for Imports, Queries, Reports and More


### Copycats

Use the kitty command line tool from the free, open source copycats suite to
read in all datafiles (`**/*.csv`) into an SQL database (e.g. `kitties.db` using SQLite).
Example:

```
$ kitty setup
```

That's it. Note: The kitty command line tool defaults to `kitties.db`
for your local single-file SQLite database
and `./` for the data directory. To query use:

```
$ kitty 1          # print kitty report (traits etc.) for kitty with id 1
```

For more see the [**copycats page »**](https://github.com/cryptocopycats/copycats#database-setup)



### Your Tool Here

Do you have a tool for the kitties dataset? Let us know! Add your tool here.





## License

![](https://publicdomainworks.github.io/buttons/zero88x31.png)

The (crypto) kitties on the blockchain dataset
is dedicated to the public domain.
Use it as you please with no restrictions whatsoever.



## Questions? Comments?

Post them on the [CryptoKittiesDev reddit](https://old.reddit.com/r/CryptoKittiesDev). Thanks.
