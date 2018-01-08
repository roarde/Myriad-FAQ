**Myriad FAQ**

u/Mynaeradicator - MTeYZ6SQEKBCysTSf9LdW8rAxaahWSSvPd

u/Keepmyshirt - MSKeep4t24cJXMcZmCHFH84Hhw8QzvbzQY

Sections

General Information

Goals/Direction

Software/Development Information

Coin Acquisition

1. General Information

    1. What is Myriadcoin?

        1. Myriadcoin (or "Myriad") was launched in February 2014 by 8bitcoder, forked from Zetacoin. It was the first cryptocurrency to use five proof-of-work algorithms in an effort to increase security as well as broaden the base of people who could mine it - SHA256d and Scrypt for ASIC miners, Skein and Myr-Groestl for GPU miners, and Qubit for GPU and CPU miners. Qubit has since been replaced with Yescrypt. Huntercoin, launched in late 2013, was actually the first coin to use multiple PoW algorithms (SHA256d and Scrypt), but its focus was not on mining, rather on a blockchain-based game that produced the large majority of new coins. (NOTE:  www.myriadcoin.org
)

    2. What makes Myriadcoin different from other coins? 

        2. Unlike most digital currencies, such as Bitcoin, Dogecoin, or Litecoin, Myriadcoin does not use a single hashing algorithm. It is even different from Darkcoin, and the other X algorithm based cryptocurrencies, as Myriad not only uses 5 different algorithms, but they are all mining concurrently. This feature gives Myriadcoin incredible resilience, and is one of the core features highlighted by its proponents.  (NOTE:  What is Myriadcoin and Multi-Algorithm Mining? - Coin Brief https://99bitcoins.com/what_is_myriadcoin) It also makes for exception resistance to 51% attacks. It is also not pre-mined, unlike other currencies, so there are no hidden fortunes by insiders.

 

    3. Who is the creator of Myriadcoin?

        3. 8bitcoder created Myriadcoin. (NOTE:  https://github.com/myriadcoin/myriadcoin/commit/f1a9ebbdc886b15b372d6ea3a98ecd196b2fe007 )  (NOTE:  https://bitcointalk.org/index.php?topic=483515.0
)

    4. Who comprises the "Core/Dev Team"

        4. A lot of people have contributed to Myriad over the years and most of them have been anonymous. As of 12/31/2017, u/cryptapus completed a port to .14.2.3, building from work by u/nzsquirrel on the Unitus coin. u/8bitcoder also assisted in porting Myriadcoin to .14.2.3. Development of and for Myriad is occurring daily.

    5. How much control does the "Core/Dev Team" have over my money? 

        5. The devs don't really have the power to change anything, beyond using their knowledge and community influence. All they can do is publish new wallets that would change the PoW as you say. But the community could choose not to download them. As well, anyone could choose to be a dev and try to fork the network. In fact there is a bounty of 1.5 million XMY to anyone who successfully produces a PoW hard fork on XMY under sane conditions. (NOTE:  https://docs.google.com/document/d/1Mm7RxqVrVFkrsGVcEfhkX6hsVInTAvxaDAYd63xD-fA/edit) 

    6. Can the Devs potentially change all algorithms? 

        6. In order to change the PoW, it's a complicated matter. First you need a dev to make the new wallet. Then you need everyone to download the new wallet, including pools, exchanges, block explorers, other services. Then you need miners to connect to pools using the new wallet and mine the new version blocks. And if you don't have a great supermajority of hash power behind your fork, you might end up with a "Myriad Fork" and "Myriad Classic" situation, which would be very confusing for investors.  (NOTE:  https://www.reddit.com/r/myriadcoin/comments/6k2n8g/how_much_power_do_the_myriadcoin_devs_have_over/djjczaz/)

        7. Think of the wallets as just being a book of rules on what to accept - if  the devs change the rules, only those miners who update to the new rule book (i.e. wallet) will accept those new changes. this is where the miners hold the power - not the devs. the miners secure the network, but also hold very strong influence over what changes are accepted. devs can attempt to introduce changes - but miners decide which ones are accepted. Changes have to be accepted by the group at large cause the group could all choose not to move over. Essentially everyone who is mining is voting for/against changes. those who have the biggest support (i.e. hashrate) behind them win.

    7. What is Proof of Work and what is its advantage over Proof of Stake?

        8. In essence, proof of stake is a greener and cheaper form of consensus. "Proof of work is maybe the biggest idea behind the Nakamoto’s Bitcoin white paper – published back in 2008 – because it allows trustless and distributed consensus. Going deeper, proof of work is a requirement to define an expensive computer calculation, also called mining, that needs to be performed in order to create a new group of trustless transactions (the so-called block) on a[ ](http://blockgeeks.com/guides/what-is-blockchain-technology/)distrubuted ledger called a blockchain." ”In proof of stake, unlike proof-of-work, the creator of a new block is chosen in a deterministic way, depending on its wealth, also defined as stake. There is no block reward, so, the miners take the transaction fees.This is why in the PoS system miners are called forgers, instead (NOTE:  https://blockgeeks.com/guides/proof-of-work-vs-proof-of-stake/).

    8. Could the Devs take all the Myriadcoins?

        9. No. Only YOU have control of your wallet. 

    9. What happens at a fork? 

        10. A fork results in two (or more) new future histories, whilst keeping the same past history (transactions that happened before remain in both blockchains). if you have XMY at the time of the fork occurring, you have XMY in both chains going forward, until you spend them in either one. you could keep an old version wallet running on the old blockchain, rejecting stuff from the new one... think of it as an alternate universe with slightly different rules from the real one. you may start with the same conditions (i.e. the same set of transactions on the blockchain at time of fork), but the two new universes will diverge from one another. Newer wallets stop accepting blocks for the replaced algorithm, and instead only accept the new one. older wallets will do the reverse - reject the new algorithm, and still accept the old one - and then a blockchain fork is born.

    10. Do the 5 different algorithms need 5 different wallets in the backend?

        11. No. One wallet that accepts blocks hashed with any of the 5 current algorithms, according to the rules built into them.

    11. Where’s Qubit? 

        12. When we replaced Qubit with Yescrypt, it was something that many people had discussed on the subreddit, and then u/Myriad_Angel offered a small bounty for some devs to implement the change. A number of people worked on it. According to u/Myriad_Angel, nzsquirrell, 8bitcoder, cryptapus, hash_engineering. The reason why we replaced Qubit is because it's kind of similar to X11 in the way that it works.  (NOTE:  https://redd.it/6k2n8g)

    12. Is there a rich list? 

        13. You can find a rich list on the [cryptap.us website](https://cryptap.us/myr/richlist/) and the [cryptoid.info website](https://chainz.cryptoid.info/xmy/#!rich).  

    13. When is the block halving? 

        14. The last halving was on Wed, 18 Jan 2017 22:00:43 GMT - and was mined by a myr-groestl miner on block 1935360 . The next one will be approximately 96 weeks from the last halving. 

    14. Are you on X Social Media Platform? 

        15. Here is a list of all the official Myriad social media accounts:

            1. [Official Twitter Account](http://www.twitter.com/myriadcoin) 

            2. [Official Subreddit](http://www.reddit.com/r/myriadcoin) 

            3. [Official Facebook Page](https://www.facebook.com/themyriadplatform/)

            4. [Official Chat](https://redd.it/6h15hc)

            5. [Bitcointalk.org](https://bitcointalk.org/index.php?topic=483515.0)

            6. [Official Myriad YouTube Channel ](https://www.youtube.com/channel/UCh_wXelOZJWh6A2zkkcym1g)

            7. [Official Myriad Instagram ](https://www.instagram.com/myriadcoin/)

            8. [Stocktwits Stream](https://stocktwits.com/symbol/XMY.X) and [Stocktwits Account](https://stocktwits.com/myriadcoin) 

            9. [Wikipedia Page](https://en.wikipedia.org/wiki/Myriadcoin)

            10. [Myriad bitcoinwiki.org page](https://en.bitcoinwiki.org/wiki/MyriadCoin) 

    15. Where can I buy Myriad? 

        16. See Coin Acquisition section below. 

    16. When are we getting on the moon? 

        17. Speculation and prediction requests are referred to [www.reddit.com/r/MyriadTrader](http://www.reddit.com/r/MyriadTrader) or a magic 8 ball near you.

    17. What can I buy with Myriad?

        18. Please see [MYRket](http://www.reddit.com/r/MYRket). Everyone is encouraged to post ads and accept payments in XMY 

2. Goals/Direction

    18. Community focus

        19. The development goals of the project are community driven. Major decisions have been made using community input. For example, in August 2016, Myriad developers used mining consensus to replace the Qubit algorithm aimed at CPU miners with the Yescrypt algorithm when the former was no longer viable for CPU miners. The mining consensus method activated the replacement algorithm when a sufficient percentage of the community signaled their support of the change through a version upgrade.

        20. In line with keeping a culture of decentralization, there is no one that will make a claim of being the "boss" of anyone. We are a collection of people who are interested in this project, and we put our skills to use for the good of Myriad and the community. We are beholden to no one but our love for Myriad. 

    19. "Coin for Everyone"

        21. This is a reference to inclusion of a wider range of people and machines who can mine the coin, as opposed to bitcoin, which is SHA-256d specific. It's simply more accessible to more hardware choices. Someone in Zimbabwe can mine it with a Windows Laptop, or even an Android device. More hardware accessibility = a more global cryptocurrency that isn't limited to deep pockets and mining infrastructures.

        22. What can I do to help?

            11. Our first suggestion is always to get as well informed about the project as possible. This is the single most important act of service to the community, as being well versed in the project will enable to you speak positively about it to others. 

            12. The community is fortunate that it is composed of dedicated people with a wide variety of skill sets. The short version is "do the things you are good at doing". Game designer? Make games. Artist? Make art, volunteer your design services to the community, or start projects yourself. Coder? Code. 

            13. Social Media

                1. Follow, like and retweet posts from the official Twitter account. Try to include #xmy $xmy #myriadcoin and mention @myriadcoin.

                2. Upvote, comment and post on r/myriadcoin. Use the [tip bot](https://www.reddit.com/r/myrbot/wiki/index). 

                3. Follow, like, and share posts from the [Facebook Page](https://www.facebook.com/themyriadplatform/)

                4. Join the [Official Chat](https://redd.it/6h15hc), engage others and answer questions from newcomers.

                5. Engage others in the [Bitcointalk.org](https://bitcointalk.org/index.php?topic=483515.0) page

                6. Subscribe to the [Official Myriad YouTube Channel ](https://www.youtube.com/channel/UCh_wXelOZJWh6A2zkkcym1g)

                7. Follow the [Official Myriad Instagram ](https://www.instagram.com/myriadcoin/)

                8. Follow the Official Myriad Stocktwits [Stream](https://stocktwits.com/symbol/XMY.X) and [Account](https://stocktwits.com/myriadcoin) 

                9. Add and update information on Myriadcoin entries for [Wikipedia](https://en.wikipedia.org/wiki/Myriadcoin) and [bitcoinwiki.org](https://en.bitcoinwiki.org/wiki/MyriadCoin) 

                    1. Information needs to be put in, the easiest one to update will be occasional market update information. Bitcoinwiki.org especially needs attention.

                10. Ask cryptocurrency blogs and cryptocurrency youtube channels to review Myriad. Better yet, create your own content!

                11. look for all articles posted about Myriad and consolidate into [one google doc](https://docs.google.com/document/d/1nS7gOlpPohD_vDXg0UoxEbTh4_TVIiGVPMVxK_zfEWs/edit?usp=sharing) . Titles, dates, authors and links. Thank you. Suggest using google scholar too. We have a few scholarly articles in which we are mentioned.

                12. Participating in the SubReddit

                    2. Myriadcoin has always been a pioneer of tipping. There was a Sunday tipping thread years ago, and now, an occasional tipping thread. Nowadays, meaningful participation in the subreddit gets rewarded by other community members through tips. The reddit tipbot is synced with the irc tipbot. Instructions [here.](https://www.reddit.com/r/myrbot/wiki/index)

                13. [Ask Apple to put us in their Approved Cryptocurrencies List](https://redd.it/78pkdh) 

            14. Lobby for Myriad

                14. Exchanges

                    3. Everyone needs to actively ask exchanges to list XMY. A handy list is provided [here](https://redd.it/7hi3j5) but more can be added. 

                    4. Mention to them (and everyone) that a new, improved, Core Wallet has been released. The .14 wallet is very fast and reliable. 

                15. Mining Pools

                    5. Pools currently mining Myriad

                        1. Identify pools where XMY can be mined. Add to list by commenting [here](https://redd.it/7j807w) : 

                        2. Make sure that the pool is using the latest .14 wallet. All pools except hongico.com have been confirmed to use .14. Need to do this for future releases. 

                    6. Pools not currently mining Myriad

                        3. Mining

                            1. Ask popular mining pools to include a Myriad pool. Post relevant updates on reddit.

                        4. Merge Mining

                            2. Let SHA256 and Scrypt pools know they can merge mine Myriad using those algorithms Post relevant updates on reddit. 

                16. "Real" World

                    7. Merchants

                        5. Ask business owners to consider taking XMY as payment. 

                            3. Low transaction fees vs credit card and even bitcoin

                            4. If you work for a service oriented business, ask if you can receive tips in XMY. 

                            5. If you are a business owner, post on [r/MYRket](http://www.reddit.com/r/MYRket) 

                    8. Friends and Family

                        6. Talk to your friends and family about Myriad and why it’s technically superior to Bitcoin and other cryptocurrencies.

                    9. Stickers

                        7. Ask for free stickers from u/keepmyshirt either through pm-ing your address or using this [form ](https://redd.it/6o8zi8) 

                            6. Put them on your laptops, cars, bikes. Etc. 

                            7. Ask businesses if you can place the stickers on their community wall.

                            8. Update the [Presence Map](https://goo.gl/LZ5Pji) 

            15. Myriad in different languages

                17. Currently looking for liaisons to interact with non-english speaking pools and exchanges. Non-english social media too. Specifically, Chinese, Japanese, Korean, and Russian. There could be more. Send a pm to u/keepmyshirt

                18. Currently looking for people to go through the new website to translate to new languages, and correct current translations. Create a pull request [here](https://github.com/myriadteam/website/blob/master/web/include/translations.php) or send a spreadsheet and the completed english text and translation to [me@braydonb.com](mailto:me@braydonb.com) 

                19. Currently looking for translators for the infographic. Please let u/keepmyshirt know when you’ve completed a translation. You can edit the text [here](https://goo.gl/sbVXUU) 

            16. Current and Future Projects

                20. We are using [Trello](https://trello.com/b/BCamm97g/myriad-roadmap) to keep track of past, current, and future projects. It does not include all ongoing projects. If you would like to be a member of the Trello board, send a moderator message on reddit mentioning your Trello username.

    20. Security

    21. Algorithm information

Currently, it uses five different hashing algorithms as proof of work, with each algorithm aimed to support a different segment of miners:[[2]](https://en.wikipedia.org/wiki/Myriadcoin#cite_note-myriadwebsite-2)

* SHA256d and Scrypt for ASIC miners (merge minable)

* Skein and Myr-Groestl for GPU miners

* Yescrypt for GPU and CPU miners

3. Software/Development Information

    22. Wallets

        23. What’s the best wallet to use? 

            17. Having a wallet that *YOU* control is key. Please do not leave more coins than is necessary in the exchanges. 

                21. The [Core Wallet](https://github.com/myriadteam/myriadcoin/releases) is still recommended for those who do not mind having their wallet in a computer. 

                22. For those who do not want to download the whole blockchain, download the [Electrum Wallet ](https://cryptap.us/myr/electrum/). 

                23. For mobile applications, there is an [iOS JSWallet](https://redd.it/78q1n5), an [Android Wallet](https://play.google.com/store/apps/details?id=com.myralicious.wlc.myriadjs&hl=en), and the [browser-based JSWallet](http://cryptap.us/myr/jswallet). 

        24. What’s the difference between the Core Wallet and the Electrum Wallet (NOTE:  https://www.reddit.com/r/myriadcoin/comments/7o50kc/question_regarding_wallets/)?

            18. Myriad-core (or QT) is the reference client and node. It is the safest way to use Myriad and follows all network rules. If all else fails in Myriad this will be the wallet that survives. The down side is that it will take some time to sync and startup. Most of that has vastly improved with the latest release (v0.14), so it's hard to not recommend this option. Additionally, running this and opening your ports to relay blocks helps the network in general.

            19. Electrum-myr is a fork of Electrum for Myriad. It is faster to startup and use quickly, and has most of the functionality of Electrum like offline cold storage, seed words, etc. However, it is NOT fully SPV like upstream Electrum (see https://github.com/cryptapus/electrum-myr/issues/1 currently only block sequence is obeyed and algo difficulty checks are missing) and relies on the small network of electrum servers out there. It is safest if used with your own electrum-server which is not necessarily an easy task for most folks.

        25. How do I store my coins securely?

            20. The most secure way is to have a paper wallet, and to keep it in a secure location. Download the paper wallet generator [here](https://cryptap.us/myr/paperwallet.html). Graphics for the paper wallet are available [here](https://redd.it/6l21sx) and [here](https://t.me/Myriadcoinofficial/39972).

    23. Auxiliary Software

        26. Detailed ticker data on Chrome and Firefox [browser extensions.](https://redd.it/72weht)

4. Coin Acquisition

    24. Trading Information/Exchanges

        27. List of Exchanges

            21. [Bittrex](https://www.bittrex.com/Market/Index?MarketName=BTC-xmy) (BTC/XMY)

            22. [Litebit.eu](http://litebit.eu/en/buy/myriadcoin) (BTC/XMY, EUR/XMY)

            23. [Cryptopia.nz](https://www.cryptopia.co.nz/Exchange/?market=XMY_BTC) (BTC/XMY, DOGE/XMY, LTC/XMY)

            24. [NLEXCH](https://www.nlexch.com/markets/xmybtc) (XMY/BTC, XMY/BCH, XMY/LTC, XMY/NLG, and XMY/EMC)

        28. Applying to exchanges

            25. The most recent exchange that we have come across that supports Myriadcoin is nlexch.com. We are always on the lookout for new exchange listing. The community is encouraged to actively lobby for their favorite exchanges to support the coin. A handy list can be found [here](https://redd.it/7hi3j5).

    25. Faucets/Games Giving Free XMY

        29. [Transparent Ponzi](https://cryptap.us/myr/dice/#ponzi)

        30. [Coinbomb](https://cryptap.us/myr/dice/#coinbomb)

        31. [Dice](https://cryptap.us/myr/dice/#dice)

        32. [Trivia Game (IRC)](http://webchat.freenode.net?channels=%23myrbot&uio=OT10cnVlJjExPTEyMyYxMj10cnVl38) 

    26. Mining Information

        33. Guides

            26. [Comprehensive Mining Guide](https://www.reddit.com/r/myriadcoin/comments/7omwpv/comprehensive_mining_guides_for_amd_nvidia_or_cpu/)

            27. [CPU Mining for beginners(Yescrypt)](https://redd.it/6jj5z5/)

            28. [GPU Mining for beginners (Myr-groestl) ](https://redd.it/6jobfa)

            29. [GPU Mining for beginners (Skein) ](https://redd.it/6lsic9)

            30. [Raspberry Pi mining (Yescrypt - Linux)](https://redd.it/6uh0aw)

            31. Android Mining (Yescrypt)  [Link 1](https://redd.it/7kc3vj) or [Link 2](https://redd.it/52yzcx)

            32. [Mining on a Mac](https://redd.it/6kczk1)

        34. Important information for all holders/miners

            33. Make sure you have the most current wallet version. Latest versions of the Core Wallet are available on the [Github Page](https://github.com/myriadteam/myriadcoin/releases/) 

            34. The [latest version](https://github.com/cryptapus/electrum-myr/releases/) of the Myriad Electrum Wallet. 

        35. Pool Info

[https://www.miners-pool.eu/](https://www.miners-pool.eu/)

Algorithms: Myriad-Groestl and yescrypt. 

Contact: twitter @MinersPoolEU IRC: #minerspool @ freenode - Email: support@miners-pool.eu or u/minerspooleu

all their mining fees are donated to Sea Shepherd, an international direct-action ocean conservation movement.

[http://zpool.ca/](http://zpool.ca/) 

Algorithms: yescrypt, Myriad-Groestl, sha256, skein, scrypt 

Contact: them through Twitter: @_zpool_ [Discord](https://discord.gg/n45n6Jj) 

[https://www.multipool.us](https://www.multipool.us) 

Algorithms: sha256 (merge mined)

[https://miningpoolhub.com/](https://miningpoolhub.com/) 

Algorithms: yescrypt and Myriad-Groestl. 

Contact: twitter @miningpoolhub reddit.com[/r/miningpoolhub](https://www.reddit.com/r/miningpoolhub)[ u/miningpoolhub](https://www.reddit.com/u/miningpoolhub) .

[http://pokemongomongo.tk/stats](http://pokemongomongo.tk/stats) 

Algorithm: yescrypt. 

Contact: post@pokemongomongo.tk for feedback. They are also parked in our IRC Channels.

[http://pool.hashrefinery.com/site/mining](http://pool.hashrefinery.com/site/mining)

Algorithms: skein, yescrypt, and Myriad-Groestl. 

Contact: bitcointalk: hashrefinery

[http://p2pool.e-pool.net:5857/static/](http://p2pool.e-pool.net:5857/static/) - 

Algorithm: yescrypt. 

[http://pool.hongico.com:5534/static/](http://pool.hongico.com:5534/static/) 

Algorithm: yescrypt. 

[https://www.mining-dutch.nl/](https://www.mining-dutch.nl/) 

Algorithm: Myriad-Groestl. 

[Prohashing.com](https://prohashing.com/help.html?topic=explorer-general) 

Algorithm: Scrypt. 



        36. Mining Software

        37. Further Reading

            35. Insert articles found in reddit article project above here. 

