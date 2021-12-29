# Summary
0. A couple of words on analysis and multiaccounting
1. **kava1uh8h4m0cqq6tnyj255mkj0s8s9vfe2kq6a2s8u** - received funds from 2 accounts from the start of the competition
2. **kava1pwhuq02sfnan3z5w4cayqd6smd2957mgd6hpj4** - received funds from 4 accounts from the start of the competition
3. **kava1fskeptst975wj8s2epraq9u89cznlrj04dwc0g** - received funds from 21 accounts
4. **kava1j7run79ex2dd5k78pk07865d4srj3gt9wly4sp** - received funds from 23 accounts
5. **kava1z6udp0degrp3fzwcn4sx4fu3su64lskcf3jhcm** (main) - cheat with swaps: pumps the price from addtional accounts, instantly profits from swap with the main account
   - **kava1h5g50w6xeej7yrynjz2z54px2cpxdqysupdw4w** (secondary)
   - **kava1t5jgg4u4jk2cqwsyt9jj353epq5wlzt9z0deks** (secondary)
   - **kava1h8yhg2q6j0x7r03ly3u9fh7j22d3q36u9rwv25** (secondary)
6. **kava17x3e8z9rra5a7zve52rffyex5u63rmeh649gf6** (main) - cheat with swaps: pumps the price from addtional accounts, instantly profits from swap with the main account
   - **kava1h5g50w6xeej7yrynjz2z54px2cpxdqysupdw4w** (secondary) - same as the one above
   - **kava1wlvsxhj4aeujwpgr9j6szygu0xk4kgj03s9cs8** (secondary)
7. **kava1vtcpusw3fkzvhxmnuztjdan5v93tw558pp4y47** (main) - multiaccounts for 1 player, probably fair play on all accounts
   - **kava1xcwvw6jxxgx3vppzcrdmemjll7vt9t5aw57065** (secondary)
   - **kava1uj8cpjujypa0wrj7k8fp2jpkp4f5euml8wykhx** (secondary)
   - **kava1d08eh22xr2txmt3m404vp66fhvw79m8jt8x06l** (secondary)
   - **kava19lnrq2n5crme7cptageamnyzkk97lcc8632h4k** (secondary)
8. **kava1gfdkdeyvamglk2tc8quqtddjksmnr7eya7uh3k** - top auction liquidator; bought collateral at almost 0 cost most of the time
   - **kava1svtehhtemmuk5hl9qxydhswdhqcfjxvrphws65** - competing top auction liquidator
9. **kava1ueu592zmh5aqmnt9aqddglvwuvwg0krjml0r2n** - multiaccounts for 1 player
   - **kava1lueh9u37pcjktccg7kd3yj5jl2vwqax4565w67**
   - **kava1dl6pgkgp0849863zu86jldhm3fe37ut299k4ga**
   - **kava15vkstzpueykxaprm84sra7ejtp6g6ep58z6dpt**
   - **kava1a4aap0glvcww5fw4ypfvsd80ta0cksl0vu9qkl**


# Report
logs date: 28 Dec ~23:00 UTC

analysis date: 26-28 Dec

### Txs correlation

There is an interesting correlation between the account activity and cheating; not true for all accounts, but helped to identify the main cheaters.

This is the top 30 leaderboard with correlation noted
```
1. kava1gfdkdeyvamglk2tc8quqtddjksmnr7eya7uh3k in process <- auction bidder
total tx: 4183
2. kava1ngd60qqsuhr3ky9fqsn443pkzwwugn40t4afty in process <- system account
total tx: 39
3. kava1svtehhtemmuk5hl9qxydhswdhqcfjxvrphws65 in process <- auction bidder
total tx: 4633
4. kava1eufgf0w9d7hf5mgtek4zr2upkxag9stmzx6unl in process
total tx: 2481
5. kava17x3e8z9rra5a7zve52rffyex5u63rmeh649gf6 in process <- identified cheater
total tx: 892
6. kava1vtcpusw3fkzvhxmnuztjdan5v93tw558pp4y47 in process
total tx: 2287
7. kava13qeen0h97lz7p8na0kqvvw4ekg0qtj8sertepe in process
total tx: 1858
8. kava1qx3nua3t62kyk6gztv0ghwnadukut38cl68q2s in process
total tx: 2346
9. kava1sdttm0h4ez8lr9qk8h5r3jjxhaf3qq5gk0ft0x in process
total tx: 1279
10. kava1fskeptst975wj8s2epraq9u89cznlrj04dwc0g in process <- identified cheater
total tx: 52
11. kava1j7run79ex2dd5k78pk07865d4srj3gt9wly4sp in process <- identified cheater
total tx: 31
12. kava1pwhuq02sfnan3z5w4cayqd6smd2957mgd6hpj4 in process <- identified cheater
total tx: 329
13. kava1r62909r0dnj2xyqf0qrnrxc58s362jr9xgk6mt in process
total tx: 1173
14. kava1dr5at8u3f20p4kpu34knmdp8k8rd53er9jpaat in process
total tx: 1790
15. kava1z6udp0degrp3fzwcn4sx4fu3su64lskcf3jhcm in process <- identified cheater
total tx: 548
16. kava1yqvnnnr7zq5g0v4xetp9amnlrkfqwcj95t7sv0 in process
total tx: 2216
17. kava1xgjhyfxgzy0je4r8fwuskphhhrlm0jrjuhh47f in process
total tx: 4347
18. kava1uh8h4m0cqq6tnyj255mkj0s8s9vfe2kq6a2s8u in process <- identified cheater
total tx: 549
19. kava1xcwvw6jxxgx3vppzcrdmemjll7vt9t5aw57065 in process <- multiaccount for 4y47 (top 6)
total tx: 295
20. kava1cvqzhnld6qtlsz7jy0f5n2k3aqfpts6uyzstld in process <- trading bot
total tx: 9671
21. kava1mzakmr5yjcftx4xgcvu9dptmsty7mkjdsys74g in process
total tx: 1328
22. kava1uj8cpjujypa0wrj7k8fp2jpkp4f5euml8wykhx in process <- multiaccount for 4y47 (top 6)
total tx: 366
23. kava1nq3kdc22z8u0rs80ed5lua6jsuaj7a50vj84sy in process
total tx: 1233
24. kava18sf2nxqt2633x3f7udjkcqkz3lzdgpsms4ddtd in process
total tx: 698
25. kava129mx925h3937xg66dzhqe8pfwemxvhanzf8wxp in process
total tx: 798
26. kava1fkzwehrhhuqegqgyccsqz2r42csw8qkh8lmcjn in process
total tx: 2099
27. kava1d08eh22xr2txmt3m404vp66fhvw79m8jt8x06l in process <- multiaccount for 4y47 (top 6)
total tx: 306
28. kava1tdyty4rs4vfynktdzh2s2sf6as0v0c8tcae2g4 in process
total tx: 149
29. kava1zfgmdes6rmq6ynrrml9fpxmtrfds5k3vvwkkh2 in process
total tx: 177
30. kava16p6p8yy8amradz97nkqagqpzdc90pekwv9uuht in process
total tx: 229
```

### Multiaccounting

Similar TX patterns are also true for multiaccounts which is described in section 9.

It's difficult to find multiaccounting with logs only. Some accounts raise questions with similar activites, but it's not easy to identify their relation from first view: you start doubting if it's a normal behaviour for multiple players or if there is one person to whom this behaviour is typical. In the section 9 I provide an example of several accounts that might belong (or might not) to one person and explain why I find these accounts suspicous.

While I am completly sure about the multiaccount player in section 6, my observations in section 9 make me wonder if there are indeed that many multiaccounts or I have a wrong perception of the human behaviour. I find the activity of the observed players very confusing.

It's hard to believe that such big prizes attracted only a couple multiaccount users: getting $1000 per account for 2 weeks of low time consuming labor every day is very attrective to cheaters. I strongly encourage to investigate multiaccounting as I tend to belive there might be a lot of them among top 61 at least.

## 1. kava1uh8h4m0cqq6tnyj255mkj0s8s9vfe2kq6a2s8u
multiple assets received from 2 accounts from the start

low activity compared to fair players
```
height: 5048 - time: 2021-12-16T06:27:17Z - to: kava1uh8h4m0cqq6tnyj255mkj0s8s9vfe2kq6a2s8u - from: kava1nxpfyzdzw0u2smv6myh58d44cxlu6fllen608w - what: 10.0swp
height: 5080 - time: 2021-12-16T06:29:57Z - to: kava1uh8h4m0cqq6tnyj255mkj0s8s9vfe2kq6a2s8u - from: kava1nxpfyzdzw0u2smv6myh58d44cxlu6fllen608w - what: 39990.0swp
height: 5159 - time: 2021-12-16T06:36:34Z - to: kava1uh8h4m0cqq6tnyj255mkj0s8s9vfe2kq6a2s8u - from: kava1nxpfyzdzw0u2smv6myh58d44cxlu6fllen608w - what: 16667.0kava
height: 5212 - time: 2021-12-16T06:41:00Z - to: kava1uh8h4m0cqq6tnyj255mkj0s8s9vfe2kq6a2s8u - from: kava1nxpfyzdzw0u2smv6myh58d44cxlu6fllen608w - what: 32587.624767swp
height: 5544 - time: 2021-12-16T07:08:46Z - to: kava1uh8h4m0cqq6tnyj255mkj0s8s9vfe2kq6a2s8u - from: kava1l7p5sqczzzwyetray93g47xfwzzmex6peejh2f - what: 40000.0swp
height: 5550 - time: 2021-12-16T07:09:16Z - to: kava1uh8h4m0cqq6tnyj255mkj0s8s9vfe2kq6a2s8u - from: kava1l7p5sqczzzwyetray93g47xfwzzmex6peejh2f - what: 14049.168086kava
height: 5555 - time: 2021-12-16T07:09:41Z - to: kava1uh8h4m0cqq6tnyj255mkj0s8s9vfe2kq6a2s8u - from: kava1l7p5sqczzzwyetray93g47xfwzzmex6peejh2f - what: 72992.12577usdx
height: 5572 - time: 2021-12-16T07:11:07Z - to: kava1uh8h4m0cqq6tnyj255mkj0s8s9vfe2kq6a2s8u - from: kava1l7p5sqczzzwyetray93g47xfwzzmex6peejh2f - what: 29917.34031usdx
```

## 2. kava1pwhuq02sfnan3z5w4cayqd6smd2957mgd6hpj4
multiple assets received from 4 accounts from the start

low activity compared to fair players
```
height: 2148 - time: 2021-12-16T02:24:40Z - to: kava1pwhuq02sfnan3z5w4cayqd6smd2957mgd6hpj4 - from: kava1xclqexg8qsmsv2rjxa9pkehxqjde2vkzuza3wm - what: 16666.99992kava
height: 2156 - time: 2021-12-16T02:25:20Z - to: kava1pwhuq02sfnan3z5w4cayqd6smd2957mgd6hpj4 - from: kava1xclqexg8qsmsv2rjxa9pkehxqjde2vkzuza3wm - what: 40000.0swp
height: 2170 - time: 2021-12-16T02:26:30Z - to: kava1pwhuq02sfnan3z5w4cayqd6smd2957mgd6hpj4 - from: kava103pf2l3g5zxvah2xf55hgrzfy3d0k8npa37lve - what: 40000.0swp
height: 2187 - time: 2021-12-16T02:27:55Z - to: kava1pwhuq02sfnan3z5w4cayqd6smd2957mgd6hpj4 - from: kava103pf2l3g5zxvah2xf55hgrzfy3d0k8npa37lve - what: 16666.8364kava
height: 2199 - time: 2021-12-16T02:28:56Z - to: kava1pwhuq02sfnan3z5w4cayqd6smd2957mgd6hpj4 - from: kava1qrxq3ujh2t9j3gurmuxujs4jtfmppjlsv77zzl - what: 16666.99992kava
height: 2343 - time: 2021-12-16T02:40:59Z - to: kava1pwhuq02sfnan3z5w4cayqd6smd2957mgd6hpj4 - from: kava1qrxq3ujh2t9j3gurmuxujs4jtfmppjlsv77zzl - what: 40000.0swp
height: 2347 - time: 2021-12-16T02:41:19Z - to: kava1pwhuq02sfnan3z5w4cayqd6smd2957mgd6hpj4 - from: kava146nma6qd652hhyzsvszfj6ued5pqht8srwg9ev - what: 40000.0swp
height: 2351 - time: 2021-12-16T02:41:39Z - to: kava1pwhuq02sfnan3z5w4cayqd6smd2957mgd6hpj4 - from: kava146nma6qd652hhyzsvszfj6ued5pqht8srwg9ev - what: 16666.9968kava
```

## 3. kava1fskeptst975wj8s2epraq9u89cznlrj04dwc0g
multiple assets received from 21 accounts

low activity compared to fair players
```
height: 103374 - time: 2021-12-21T23:31:57Z - to: kava1fskeptst975wj8s2epraq9u89cznlrj04dwc0g - from: kava193c7pdy0tj0nn5nryc4xkaras29kmq9mawer86 - what: 40000.0swp
height: 103383 - time: 2021-12-21T23:32:43Z - to: kava1fskeptst975wj8s2epraq9u89cznlrj04dwc0g - from: kava193c7pdy0tj0nn5nryc4xkaras29kmq9mawer86 - what: 16666.99kava
height: 103438 - time: 2021-12-21T23:37:19Z - to: kava1fskeptst975wj8s2epraq9u89cznlrj04dwc0g - from: kava1g7khvcz9rt3cms4jzus78eqx5q82l9r075muv7 - what: 40000.0swp
height: 103449 - time: 2021-12-21T23:38:14Z - to: kava1fskeptst975wj8s2epraq9u89cznlrj04dwc0g - from: kava1g7khvcz9rt3cms4jzus78eqx5q82l9r075muv7 - what: 16666.99kava
height: 103498 - time: 2021-12-21T23:42:20Z - to: kava1fskeptst975wj8s2epraq9u89cznlrj04dwc0g - from: kava1rffszt5090jlpj0fhwap2zcwune6gg30nzxyv9 - what: 40000.0swp
height: 103508 - time: 2021-12-21T23:43:10Z - to: kava1fskeptst975wj8s2epraq9u89cznlrj04dwc0g - from: kava1rffszt5090jlpj0fhwap2zcwune6gg30nzxyv9 - what: 16666.99kava
height: 103550 - time: 2021-12-21T23:46:41Z - to: kava1fskeptst975wj8s2epraq9u89cznlrj04dwc0g - from: kava1pcf4l90sz3r2ae25q5c7qwg4lkd92s6qq5eu25 - what: 40000.0swp
height: 103559 - time: 2021-12-21T23:47:26Z - to: kava1fskeptst975wj8s2epraq9u89cznlrj04dwc0g - from: kava1pcf4l90sz3r2ae25q5c7qwg4lkd92s6qq5eu25 - what: 16666.99kava
height: 103603 - time: 2021-12-21T23:51:07Z - to: kava1fskeptst975wj8s2epraq9u89cznlrj04dwc0g - from: kava1n2al3zh752wzc7mgfdtnrw52xrhthnw26ea8t3 - what: 40000.0swp
height: 103615 - time: 2021-12-21T23:52:07Z - to: kava1fskeptst975wj8s2epraq9u89cznlrj04dwc0g - from: kava1n2al3zh752wzc7mgfdtnrw52xrhthnw26ea8t3 - what: 16666.99kava
height: 103666 - time: 2021-12-21T23:56:23Z - to: kava1fskeptst975wj8s2epraq9u89cznlrj04dwc0g - from: kava1flps09nf3dzlcmsv7hryme56r6yljny9e59ysu - what: 40000.0swp
height: 103679 - time: 2021-12-21T23:57:28Z - to: kava1fskeptst975wj8s2epraq9u89cznlrj04dwc0g - from: kava1flps09nf3dzlcmsv7hryme56r6yljny9e59ysu - what: 16666.99kava
height: 103730 - time: 2021-12-22T00:01:44Z - to: kava1fskeptst975wj8s2epraq9u89cznlrj04dwc0g - from: kava1dcr7remwraqplc6ycexepegtc8eg7xn6xat5ht - what: 40000.0swp
height: 103750 - time: 2021-12-22T00:03:25Z - to: kava1fskeptst975wj8s2epraq9u89cznlrj04dwc0g - from: kava1dcr7remwraqplc6ycexepegtc8eg7xn6xat5ht - what: 16666.99kava
height: 103796 - time: 2021-12-22T00:07:15Z - to: kava1fskeptst975wj8s2epraq9u89cznlrj04dwc0g - from: kava1f6e7gj0cy4x4xnfnf4je2g99sahuqepvcsm3vd - what: 40000.0swp
height: 103810 - time: 2021-12-22T00:08:26Z - to: kava1fskeptst975wj8s2epraq9u89cznlrj04dwc0g - from: kava1f6e7gj0cy4x4xnfnf4je2g99sahuqepvcsm3vd - what: 16666.99kava
height: 103867 - time: 2021-12-22T00:13:12Z - to: kava1fskeptst975wj8s2epraq9u89cznlrj04dwc0g - from: kava122qh2xxmkr0f5vrdszdllenm96x966ck4gr8qf - what: 40000.0swp
height: 103878 - time: 2021-12-22T00:14:07Z - to: kava1fskeptst975wj8s2epraq9u89cznlrj04dwc0g - from: kava122qh2xxmkr0f5vrdszdllenm96x966ck4gr8qf - what: 16666.99kava
height: 103927 - time: 2021-12-22T00:18:13Z - to: kava1fskeptst975wj8s2epraq9u89cznlrj04dwc0g - from: kava1sxfgynwnm8g74tm0u77qzdxkp3qqksk8eajwkt - what: 40000.0swp
height: 103938 - time: 2021-12-22T00:19:08Z - to: kava1fskeptst975wj8s2epraq9u89cznlrj04dwc0g - from: kava1sxfgynwnm8g74tm0u77qzdxkp3qqksk8eajwkt - what: 16666.99kava
height: 103975 - time: 2021-12-22T00:22:14Z - to: kava1fskeptst975wj8s2epraq9u89cznlrj04dwc0g - from: kava12se7un450gk4c6ze4rkau302r6hq76htkuwp55 - what: 40000.0swp
height: 103989 - time: 2021-12-22T00:23:24Z - to: kava1fskeptst975wj8s2epraq9u89cznlrj04dwc0g - from: kava12se7un450gk4c6ze4rkau302r6hq76htkuwp55 - what: 16666.99kava
height: 104031 - time: 2021-12-22T00:26:55Z - to: kava1fskeptst975wj8s2epraq9u89cznlrj04dwc0g - from: kava1jf5p2tx4s748admx9vjl5vk49clpffpyh6a6zh - what: 40000.0swp
height: 104042 - time: 2021-12-22T00:27:50Z - to: kava1fskeptst975wj8s2epraq9u89cznlrj04dwc0g - from: kava1jf5p2tx4s748admx9vjl5vk49clpffpyh6a6zh - what: 16666.99kava
height: 104090 - time: 2021-12-22T00:31:51Z - to: kava1fskeptst975wj8s2epraq9u89cznlrj04dwc0g - from: kava1jkcqeqxxvvkyycsmmmpasz6sqm0dtqlxkjh66n - what: 40000.0swp
height: 104103 - time: 2021-12-22T00:32:56Z - to: kava1fskeptst975wj8s2epraq9u89cznlrj04dwc0g - from: kava1jkcqeqxxvvkyycsmmmpasz6sqm0dtqlxkjh66n - what: 16666.99kava
height: 104174 - time: 2021-12-22T00:38:53Z - to: kava1fskeptst975wj8s2epraq9u89cznlrj04dwc0g - from: kava1aezevw97d6jfakr45d7j0lxvufzrt57uz07zq9 - what: 40000.0swp
height: 104186 - time: 2021-12-22T00:39:53Z - to: kava1fskeptst975wj8s2epraq9u89cznlrj04dwc0g - from: kava1aezevw97d6jfakr45d7j0lxvufzrt57uz07zq9 - what: 16666.99kava
height: 104231 - time: 2021-12-22T00:43:39Z - to: kava1fskeptst975wj8s2epraq9u89cznlrj04dwc0g - from: kava1cdp4ky8pzjgqga7rc8q4kawhcd6uu82k6gu9a3 - what: 40000.0swp
height: 104245 - time: 2021-12-22T00:44:49Z - to: kava1fskeptst975wj8s2epraq9u89cznlrj04dwc0g - from: kava1cdp4ky8pzjgqga7rc8q4kawhcd6uu82k6gu9a3 - what: 16666.99kava
height: 104278 - time: 2021-12-22T00:47:34Z - to: kava1fskeptst975wj8s2epraq9u89cznlrj04dwc0g - from: kava1zeq62p3esg9fvadujt6utqv4pdk6sd3hzlncyw - what: 40000.0swp
height: 104288 - time: 2021-12-22T00:48:25Z - to: kava1fskeptst975wj8s2epraq9u89cznlrj04dwc0g - from: kava1zeq62p3esg9fvadujt6utqv4pdk6sd3hzlncyw - what: 16666.99kava
height: 104344 - time: 2021-12-22T00:53:06Z - to: kava1fskeptst975wj8s2epraq9u89cznlrj04dwc0g - from: kava1urpr4a6phsn036ey23csdj2zg9qrspg69s4lap - what: 40000.0swp
height: 104353 - time: 2021-12-22T00:53:51Z - to: kava1fskeptst975wj8s2epraq9u89cznlrj04dwc0g - from: kava1urpr4a6phsn036ey23csdj2zg9qrspg69s4lap - what: 16666.99kava
height: 104395 - time: 2021-12-22T00:57:22Z - to: kava1fskeptst975wj8s2epraq9u89cznlrj04dwc0g - from: kava1ax6xl8nh8dm0tl4cvzganag6qcegy5tsn3n0hh - what: 40000.0swp
height: 104406 - time: 2021-12-22T00:58:17Z - to: kava1fskeptst975wj8s2epraq9u89cznlrj04dwc0g - from: kava1ax6xl8nh8dm0tl4cvzganag6qcegy5tsn3n0hh - what: 16666.99kava
height: 104459 - time: 2021-12-22T01:02:43Z - to: kava1fskeptst975wj8s2epraq9u89cznlrj04dwc0g - from: kava1feqrwg0q2jw0w5tumcr5vtas4ktdes2px5m74t - what: 40000.0swp
height: 104470 - time: 2021-12-22T01:03:38Z - to: kava1fskeptst975wj8s2epraq9u89cznlrj04dwc0g - from: kava1feqrwg0q2jw0w5tumcr5vtas4ktdes2px5m74t - what: 16666.99kava
height: 105055 - time: 2021-12-22T01:52:34Z - to: kava1fskeptst975wj8s2epraq9u89cznlrj04dwc0g - from: kava15050lp86lte7p54dv6resvrxaz0cqpmd7rqmrv - what: 40000.0swp
height: 105068 - time: 2021-12-22T01:53:39Z - to: kava1fskeptst975wj8s2epraq9u89cznlrj04dwc0g - from: kava15050lp86lte7p54dv6resvrxaz0cqpmd7rqmrv - what: 16666.99kava
height: 105259 - time: 2021-12-22T02:09:38Z - to: kava1fskeptst975wj8s2epraq9u89cznlrj04dwc0g - from: kava1cv4edj2nqh0y3909efxpsvpu5j6get4fre6u4n - what: 40000.0swp
height: 105268 - time: 2021-12-22T02:10:23Z - to: kava1fskeptst975wj8s2epraq9u89cznlrj04dwc0g - from: kava1cv4edj2nqh0y3909efxpsvpu5j6get4fre6u4n - what: 16666.99kava
```

## 4. kava1j7run79ex2dd5k78pk07865d4srj3gt9wly4sp
multiple assets received from 23 accounts

low activity compared to fair players
```
height: 86134 - time: 2021-12-20T23:29:54Z - to: kava1j7run79ex2dd5k78pk07865d4srj3gt9wly4sp - from: kava1cvrjmnu4xpzak6qhu035pekh5h45vprejnzx8j - what: 40000.0swp - 
height: 86171 - time: 2021-12-20T23:33:00Z - to: kava1j7run79ex2dd5k78pk07865d4srj3gt9wly4sp - from: kava1cvrjmnu4xpzak6qhu035pekh5h45vprejnzx8j - what: 16666.99kava - 
height: 86212 - time: 2021-12-20T23:36:26Z - to: kava1j7run79ex2dd5k78pk07865d4srj3gt9wly4sp - from: kava1e69q8vgkncaxyxuaandpwnkc7uvw788wn87cs5 - what: 40000.0swp - 
height: 86254 - time: 2021-12-20T23:39:56Z - to: kava1j7run79ex2dd5k78pk07865d4srj3gt9wly4sp - from: kava1e69q8vgkncaxyxuaandpwnkc7uvw788wn87cs5 - what: 16666.99kava - 
height: 86311 - time: 2021-12-20T23:44:42Z - to: kava1j7run79ex2dd5k78pk07865d4srj3gt9wly4sp - from: kava1en5smenwwqxjtdunrpejlqhsagf6e2m5227qwl - what: 40000.0swp - 
height: 86317 - time: 2021-12-20T23:45:13Z - to: kava1j7run79ex2dd5k78pk07865d4srj3gt9wly4sp - from: kava1en5smenwwqxjtdunrpejlqhsagf6e2m5227qwl - what: 16666.99kava - 
height: 86360 - time: 2021-12-20T23:48:48Z - to: kava1j7run79ex2dd5k78pk07865d4srj3gt9wly4sp - from: kava1l0dug58r4224rfdj8kmwu3ahwa53qq00sr7zfy - what: 40000.0swp - 
height: 86397 - time: 2021-12-20T23:51:54Z - to: kava1j7run79ex2dd5k78pk07865d4srj3gt9wly4sp - from: kava1l0dug58r4224rfdj8kmwu3ahwa53qq00sr7zfy - what: 16666.99kava - 
height: 86474 - time: 2021-12-20T23:58:20Z - to: kava1j7run79ex2dd5k78pk07865d4srj3gt9wly4sp - from: kava1qxr72tjtxzl73g6hxjgz9l0ysl86xfrym4s58m - what: 40000.0swp - 
height: 86479 - time: 2021-12-20T23:58:46Z - to: kava1j7run79ex2dd5k78pk07865d4srj3gt9wly4sp - from: kava1qxr72tjtxzl73g6hxjgz9l0ysl86xfrym4s58m - what: 16.66699kava - 
height: 86490 - time: 2021-12-20T23:59:41Z - to: kava1j7run79ex2dd5k78pk07865d4srj3gt9wly4sp - from: kava1qxr72tjtxzl73g6hxjgz9l0ysl86xfrym4s58m - what: 16.650328kava - 
height: 86499 - time: 2021-12-21T00:00:26Z - to: kava1j7run79ex2dd5k78pk07865d4srj3gt9wly4sp - from: kava1qxr72tjtxzl73g6hxjgz9l0ysl86xfrym4s58m - what: 16633.0kava - 
height: 86522 - time: 2021-12-21T00:02:21Z - to: kava1j7run79ex2dd5k78pk07865d4srj3gt9wly4sp - from: kava14k2wh6gpdv48tzm60lvz9hzjfqmd2ryklhtqdn - what: 40000.0swp - 
height: 86528 - time: 2021-12-21T00:02:51Z - to: kava1j7run79ex2dd5k78pk07865d4srj3gt9wly4sp - from: kava14k2wh6gpdv48tzm60lvz9hzjfqmd2ryklhtqdn - what: 16666.99kava - 
height: 86575 - time: 2021-12-21T00:06:47Z - to: kava1j7run79ex2dd5k78pk07865d4srj3gt9wly4sp - from: kava104fxnc63rq68mgf6vakfmvlvlyqud26g84gvaf - what: 40000.0swp - 
height: 86580 - time: 2021-12-21T00:07:12Z - to: kava1j7run79ex2dd5k78pk07865d4srj3gt9wly4sp - from: kava104fxnc63rq68mgf6vakfmvlvlyqud26g84gvaf - what: 16666.99kava - 
height: 86622 - time: 2021-12-21T00:10:43Z - to: kava1j7run79ex2dd5k78pk07865d4srj3gt9wly4sp - from: kava1m5fqcsuwtaeaaseu9xyxxw9vvqm32stn423d32 - what: 40000.0swp - 
height: 86633 - time: 2021-12-21T00:11:38Z - to: kava1j7run79ex2dd5k78pk07865d4srj3gt9wly4sp - from: kava1m5fqcsuwtaeaaseu9xyxxw9vvqm32stn423d32 - what: 16666.99kava - 
height: 86670 - time: 2021-12-21T00:14:44Z - to: kava1j7run79ex2dd5k78pk07865d4srj3gt9wly4sp - from: kava1r54smaudr5hq6s5yaqnhahmd8gr27zkkrqvs62 - what: 40000.0swp - 
height: 86682 - time: 2021-12-21T00:15:44Z - to: kava1j7run79ex2dd5k78pk07865d4srj3gt9wly4sp - from: kava1r54smaudr5hq6s5yaqnhahmd8gr27zkkrqvs62 - what: 16666.99kava - 
height: 86726 - time: 2021-12-21T00:19:25Z - to: kava1j7run79ex2dd5k78pk07865d4srj3gt9wly4sp - from: kava128sqvxfpkk8z8rnka6v69ze7euxwegcsevnkfk - what: 40000.0swp - 
height: 86736 - time: 2021-12-21T00:20:15Z - to: kava1j7run79ex2dd5k78pk07865d4srj3gt9wly4sp - from: kava128sqvxfpkk8z8rnka6v69ze7euxwegcsevnkfk - what: 16666.99kava - 
height: 86780 - time: 2021-12-21T00:23:56Z - to: kava1j7run79ex2dd5k78pk07865d4srj3gt9wly4sp - from: kava1m4gqy9az69xq6d2zxrlyf6m8wv40y653tdl6fa - what: 40000.0swp - 
height: 86790 - time: 2021-12-21T00:24:46Z - to: kava1j7run79ex2dd5k78pk07865d4srj3gt9wly4sp - from: kava1m4gqy9az69xq6d2zxrlyf6m8wv40y653tdl6fa - what: 16666.99kava - 
height: 86832 - time: 2021-12-21T00:28:17Z - to: kava1j7run79ex2dd5k78pk07865d4srj3gt9wly4sp - from: kava19q9722h0px3g3pqrsem7wzqa7vqjsqtkvne49l - what: 40000.0swp - 
height: 86846 - time: 2021-12-21T00:29:27Z - to: kava1j7run79ex2dd5k78pk07865d4srj3gt9wly4sp - from: kava19q9722h0px3g3pqrsem7wzqa7vqjsqtkvne49l - what: 16666.99kava - 
height: 86943 - time: 2021-12-21T00:37:34Z - to: kava1j7run79ex2dd5k78pk07865d4srj3gt9wly4sp - from: kava1gpswhuhumrg9xjdurr6t94t8lsa9g70qphcjfu - what: 40000.0swp - 
height: 86956 - time: 2021-12-21T00:38:39Z - to: kava1j7run79ex2dd5k78pk07865d4srj3gt9wly4sp - from: kava1gpswhuhumrg9xjdurr6t94t8lsa9g70qphcjfu - what: 16666.99kava - 
height: 86999 - time: 2021-12-21T00:42:15Z - to: kava1j7run79ex2dd5k78pk07865d4srj3gt9wly4sp - from: kava1kegjjwtv6988r062qf2emh9djserc26jvv7zme - what: 40000.0swp - 
height: 87009 - time: 2021-12-21T00:43:05Z - to: kava1j7run79ex2dd5k78pk07865d4srj3gt9wly4sp - from: kava1kegjjwtv6988r062qf2emh9djserc26jvv7zme - what: 16666.99kava - 
height: 87086 - time: 2021-12-21T00:49:32Z - to: kava1j7run79ex2dd5k78pk07865d4srj3gt9wly4sp - from: kava1tgckc9ekhz6ssaafp52s8azvc4an5eeef773qn - what: 40000.0swp - 
height: 87097 - time: 2021-12-21T00:50:27Z - to: kava1j7run79ex2dd5k78pk07865d4srj3gt9wly4sp - from: kava1tgckc9ekhz6ssaafp52s8azvc4an5eeef773qn - what: 16666.99kava - 
height: 87137 - time: 2021-12-21T00:53:48Z - to: kava1j7run79ex2dd5k78pk07865d4srj3gt9wly4sp - from: kava1uev86hfk22z7f3lzw7s2s04h6c47wdzxvpjzkw - what: 40000.0swp - 
height: 87149 - time: 2021-12-21T00:54:48Z - to: kava1j7run79ex2dd5k78pk07865d4srj3gt9wly4sp - from: kava1uev86hfk22z7f3lzw7s2s04h6c47wdzxvpjzkw - what: 16666.99kava - 
height: 87190 - time: 2021-12-21T00:58:14Z - to: kava1j7run79ex2dd5k78pk07865d4srj3gt9wly4sp - from: kava1cgy7prfvhv44n79zr83vvh28zs6jknhmqmsrl0 - what: 40000.0swp - 
height: 87233 - time: 2021-12-21T01:01:49Z - to: kava1j7run79ex2dd5k78pk07865d4srj3gt9wly4sp - from: kava1mxqn6n38n3uuwtxf7w386jpdmqpkyp9aamazgr - what: 40000.0swp - 
height: 87242 - time: 2021-12-21T01:02:35Z - to: kava1j7run79ex2dd5k78pk07865d4srj3gt9wly4sp - from: kava1mxqn6n38n3uuwtxf7w386jpdmqpkyp9aamazgr - what: 16666.99kava - 
height: 87282 - time: 2021-12-21T01:05:55Z - to: kava1j7run79ex2dd5k78pk07865d4srj3gt9wly4sp - from: kava1mz89a5ugmdf9jtc09l0p20pgje0mdc4cr96qh3 - what: 40000.0swp - 
height: 87291 - time: 2021-12-21T01:06:40Z - to: kava1j7run79ex2dd5k78pk07865d4srj3gt9wly4sp - from: kava1mz89a5ugmdf9jtc09l0p20pgje0mdc4cr96qh3 - what: 16666.99kava - 
height: 87419 - time: 2021-12-21T01:17:23Z - to: kava1j7run79ex2dd5k78pk07865d4srj3gt9wly4sp - from: kava1va8k5jqm6sal8namyr9r5l2upnkgltdll9dcqv - what: 40000.0swp - 
height: 87427 - time: 2021-12-21T01:18:03Z - to: kava1j7run79ex2dd5k78pk07865d4srj3gt9wly4sp - from: kava1va8k5jqm6sal8namyr9r5l2upnkgltdll9dcqv - what: 16666.9968kava - 
height: 87466 - time: 2021-12-21T01:21:19Z - to: kava1j7run79ex2dd5k78pk07865d4srj3gt9wly4sp - from: kava15u8zlyl8669p6vk74vmuw5hclfz324drk9408a - what: 40000.0swp - 
height: 87483 - time: 2021-12-21T01:22:44Z - to: kava1j7run79ex2dd5k78pk07865d4srj3gt9wly4sp - from: kava15u8zlyl8669p6vk74vmuw5hclfz324drk9408a - what: 16666.99kava - 
height: 87519 - time: 2021-12-21T01:25:45Z - to: kava1j7run79ex2dd5k78pk07865d4srj3gt9wly4sp - from: kava1v7l09pk9qjgl8fu7yvlcxk3479kl9f2slyh0rm - what: 40000.0swp - 
height: 87527 - time: 2021-12-21T01:26:25Z - to: kava1j7run79ex2dd5k78pk07865d4srj3gt9wly4sp - from: kava1v7l09pk9qjgl8fu7yvlcxk3479kl9f2slyh0rm - what: 16666.99kava - 
height: 87561 - time: 2021-12-21T01:29:15Z - to: kava1j7run79ex2dd5k78pk07865d4srj3gt9wly4sp - from: kava1u4ezzqfkff9yzcyfjperfg2e6m6phy5dgsezn2 - what: 40000.0swp - 
height: 87573 - time: 2021-12-21T01:30:16Z - to: kava1j7run79ex2dd5k78pk07865d4srj3gt9wly4sp - from: kava1u4ezzqfkff9yzcyfjperfg2e6m6phy5dgsezn2 - what: 16666.99kava - 
```

## 5. kava1z6udp0degrp3fzwcn4sx4fu3su64lskcf3jhcm (main)
+ kava1h5g50w6xeej7yrynjz2z54px2cpxdqysupdw4w (secondary)
+ kava1t5jgg4u4jk2cqwsyt9jj353epq5wlzt9z0deks (secondary)
+ kava1h8yhg2q6j0x7r03ly3u9fh7j22d3q36u9rwv25 (secondary)

hidden transfer of capital from 1 account to the other; pumps or dumps the price with second account, profits with main account
multiple swap exampls with 2 secondary accounts identified (might be more)

### Example 1:

timing: 02:43 - 02:46

preparation: secondary account sells assets for USDX
```
height: 174526 - time: 2021-12-26T02:43:16Z - kava1h5g50w6xeej7yrynjz2z54px2cpxdqysupdw4w - what: 6500.0akt - for: 19072.873804usdx - 
height: 174530 - time: 2021-12-26T02:43:36Z - kava1h5g50w6xeej7yrynjz2z54px2cpxdqysupdw4w - what: 200.0luna - for: 6048.561706usdx - 
height: 174533 - time: 2021-12-26T02:43:51Z - kava1h5g50w6xeej7yrynjz2z54px2cpxdqysupdw4w - what: 2400.0osmo - for: 11914.755405usdx - 
```
main account buys ATOM
```
height: 174553 - time: 2021-12-26T02:45:32Z - kava1z6udp0degrp3fzwcn4sx4fu3su64lskcf3jhcm - what: 292000.0usdx - for: 11350.156692atom - 
```
secondary account buys a lot of ATOM (price goes up a lot)
```
height: 174558 - time: 2021-12-26T02:45:57Z - kava1h5g50w6xeej7yrynjz2z54px2cpxdqysupdw4w - what: 519708.618488usdx - for: 16735.728052atom - 
```
main account sells ATOM (gained 70k+ usdx)
```
height: 174567 - time: 2021-12-26T02:46:42Z - kava1z6udp0degrp3fzwcn4sx4fu3su64lskcf3jhcm - what: 11350.156692atom - for: 364380.434562usdx - 
```
second account sells ATOM (lost 70k usdx)

### Example 2:

timing:  02:47 - 02:58

all actions are done in the same low time frame

secondary account finishes preparations to get more USDX
```
height: 174572 - time: 2021-12-26T02:47:07Z - kava1h5g50w6xeej7yrynjz2z54px2cpxdqysupdw4w - what: 16735.728052atom - for: 445123.871108usdx - 
```
main account buys ATOM
```
height: 174582 - time: 2021-12-26T02:47:57Z - kava1z6udp0degrp3fzwcn4sx4fu3su64lskcf3jhcm - what: 364380.434562usdx - for: 13923.730501atom - 
```
second account buys a lot of ATOM
```
height: 174587 - time: 2021-12-26T02:48:22Z - kava1h5g50w6xeej7yrynjz2z54px2cpxdqysupdw4w - what: 445123.871108usdx - for: 14098.155666atom - 
```
main account sells ATOM (gained 70k+ usdx)
```
height: 174592 - time: 2021-12-26T02:48:47Z - kava1z6udp0degrp3fzwcn4sx4fu3su64lskcf3jhcm - what: 13923.730501atom - for: 438933.806652usdx - 
```
second account sells ATOM (lost 70k usdx)
```
height: 174597 - time: 2021-12-26T02:49:12Z - kava1h5g50w6xeej7yrynjz2z54px2cpxdqysupdw4w - what: 14098.114333atom - for: 368463.427711usdx - 
```
actions repeat
```
height: 174606 - time: 2021-12-26T02:49:58Z - kava1z6udp0degrp3fzwcn4sx4fu3su64lskcf3jhcm - what: 438933.806652usdx - for: 203701.993921swp - 
height: 174611 - time: 2021-12-26T02:50:23Z - kava1h5g50w6xeej7yrynjz2z54px2cpxdqysupdw4w - what: 368463.427711usdx - for: 146751.948766swp - 
height: 174617 - time: 2021-12-26T02:50:53Z - kava1z6udp0degrp3fzwcn4sx4fu3su64lskcf3jhcm - what: 203701.993921swp - for: 497552.497878usdx - 
height: 174622 - time: 2021-12-26T02:51:18Z - kava1h5g50w6xeej7yrynjz2z54px2cpxdqysupdw4w - what: 146751.948766swp - for: 301128.986254usdx - 
height: 174633 - time: 2021-12-26T02:52:13Z - kava1z6udp0degrp3fzwcn4sx4fu3su64lskcf3jhcm - what: 149999.93549usdx - for: 50023.914627akt - 
height: 174659 - time: 2021-12-26T02:54:23Z - kava1z6udp0degrp3fzwcn4sx4fu3su64lskcf3jhcm - what: 347552.562388usdx - for: 13329.74388atom - 
height: 174664 - time: 2021-12-26T02:54:49Z - kava1z6udp0degrp3fzwcn4sx4fu3su64lskcf3jhcm - what: 347552.562388usdx - for: 12913.568661atom - 
height: 174670 - time: 2021-12-26T02:55:19Z - kava1h5g50w6xeej7yrynjz2z54px2cpxdqysupdw4w - what: 301128.986254usdx - for: 9622.984231atom - 
height: 174675 - time: 2021-12-26T02:55:44Z - kava1z6udp0degrp3fzwcn4sx4fu3su64lskcf3jhcm - what: 12913.568661atom - for: 394229.571803usdx - 
height: 174680 - time: 2021-12-26T02:56:09Z - kava1h5g50w6xeej7yrynjz2z54px2cpxdqysupdw4w - what: 9622.984231atom - for: 252717.487988usdx - 
height: 174689 - time: 2021-12-26T02:56:54Z - kava1z6udp0degrp3fzwcn4sx4fu3su64lskcf3jhcm - what: 99999.064815usdx - for: 32177.330781akt - 
height: 174712 - time: 2021-12-26T02:58:49Z - kava1z6udp0degrp3fzwcn4sx4fu3su64lskcf3jhcm - what: 5400.0akt - for: 16914.786298usdx - 
```

### Example 3:
buy ATOM with main account
```
height: 175347 - time: 2021-12-26T03:51:56Z - kava1z6udp0degrp3fzwcn4sx4fu3su64lskcf3jhcm - what: 300000.0usdx - for: 11349.864775atom - 
```
buy ATOM with secondary account
```
height: 175352 - time: 2021-12-26T03:52:21Z - kava1h5g50w6xeej7yrynjz2z54px2cpxdqysupdw4w - what: 465120.099298usdx - for: 14756.039494atom - 
```
sell ATOM with main account (+65k usdx gains)
```
height: 175357 - time: 2021-12-26T03:52:46Z - kava1z6udp0degrp3fzwcn4sx4fu3su64lskcf3jhcm - what: 11349.864775atom - for: 365041.271129usdx - 
```
sell ATOM with secondary account (~65k usdx loss)
```
height: 175362 - time: 2021-12-26T03:53:11Z - kava1h5g50w6xeej7yrynjz2z54px2cpxdqysupdw4w - what: 14756.039494atom - for: 398071.915856usdx - 
```
repeat
```
height: 175369 - time: 2021-12-26T03:53:47Z - kava1z6udp0degrp3fzwcn4sx4fu3su64lskcf3jhcm - what: 365041.271129usdx - for: 199221.946667swp - 
height: 175378 - time: 2021-12-26T03:54:32Z - kava1h5g50w6xeej7yrynjz2z54px2cpxdqysupdw4w - what: 398071.915856usdx - for: 185913.740493swp - 
```

### Example 4:
buy OSMO with main account
```
height: 75677 - time: 2021-12-20T08:55:13Z - kava1z6udp0degrp3fzwcn4sx4fu3su64lskcf3jhcm - what: 127731.397082usdx - for: 28665.744032osmo - 
```
buy OSMO with secondary account
```
height: 75683 - time: 2021-12-20T08:55:44Z - kava1t5jgg4u4jk2cqwsyt9jj353epq5wlzt9z0deks - what: 399999.0usdx - for: 71618.989335osmo - 
```
sell OSMO with main account (50k+ usdx profit)
```
height: 75687 - time: 2021-12-20T08:56:04Z - kava1z6udp0degrp3fzwcn4sx4fu3su64lskcf3jhcm - what: 28665.744032osmo - for: 175828.224413usdx - 
```
sell OSMO with secondary account (50k usdx loss)
```
height: 75693 - time: 2021-12-20T08:56:34Z - kava1t5jgg4u4jk2cqwsyt9jj353epq5wlzt9z0deks - what: 71618.989335osmo - for: 350581.517181usdx - 
```
repeat
```
height: 75714 - time: 2021-12-20T08:58:19Z - kava1z6udp0degrp3fzwcn4sx4fu3su64lskcf3jhcm - what: 175828.224413usdx - for: 38708.021142osmo - 
height: 75720 - time: 2021-12-20T08:58:49Z - kava1t5jgg4u4jk2cqwsyt9jj353epq5wlzt9z0deks - what: 299999.0usdx - for: 54214.812067osmo - 
height: 75733 - time: 2021-12-20T08:59:54Z - kava1z6udp0degrp3fzwcn4sx4fu3su64lskcf3jhcm - what: 38708.021142osmo - for: 221309.107915usdx - 
height: 75744 - time: 2021-12-20T09:00:50Z - kava1t5jgg4u4jk2cqwsyt9jj353epq5wlzt9z0deks - what: 54214.812067osmo - for: 250721.487045usdx - 
height: 75759 - time: 2021-12-20T09:02:05Z - kava1z6udp0degrp3fzwcn4sx4fu3su64lskcf3jhcm - what: 221309.107915usdx - for: 48365.553426osmo - 
height: 75765 - time: 2021-12-20T09:02:35Z - kava1t5jgg4u4jk2cqwsyt9jj353epq5wlzt9z0deks - what: 429854.873684usdx - for: 70901.344823osmo - 
height: 75769 - time: 2021-12-20T09:02:55Z - kava1z6udp0degrp3fzwcn4sx4fu3su64lskcf3jhcm - what: 48365.553426osmo - for: 308328.754681usdx - 
height: 75775 - time: 2021-12-20T09:03:25Z - kava1t5jgg4u4jk2cqwsyt9jj353epq5wlzt9z0deks - what: 70901.344823osmo - for: 341261.965257usdx - 
```

### Example 5:
```
height: 225704 - time: 2021-12-29T02:03:46Z - kava1z6udp0degrp3fzwcn4sx4fu3su64lskcf3jhcm - what: 671332.104092usdx - for: 370480.321872swp
height: 225710 - time: 2021-12-29T02:04:16Z - kava1h8yhg2q6j0x7r03ly3u9fh7j22d3q36u9rwv25 - what: 442696.033857usdx - for: 196112.813166swp
height: 225716 - time: 2021-12-29T02:04:46Z - kava1z6udp0degrp3fzwcn4sx4fu3su64lskcf3jhcm - what: 370480.321872swp - for: 779770.417356usdx
height: 225721 - time: 2021-12-29T02:05:11Z - kava1h8yhg2q6j0x7r03ly3u9fh7j22d3q36u9rwv25 - what: 196112.813166swp - for: 331442.895134usdx
```

## 6. kava17x3e8z9rra5a7zve52rffyex5u63rmeh649gf6 (main)
+ kava1h5g50w6xeej7yrynjz2z54px2cpxdqysupdw4w (secondary) - same secondary account as the cheater above; same person operating both main accounts
+ kava1wlvsxhj4aeujwpgr9j6szygu0xk4kgj03s9cs8 (secondary)

hidden transfer of capital from 1 account to the other; pumps or dumps the price with second account, profits with main account
multiple swap exampls with 2 secondary accounts identified (might be more)

### Example 1:
buy ATOM with main account
```
height: 165603 - time: 2021-12-25T14:16:58Z - kava17x3e8z9rra5a7zve52rffyex5u63rmeh649gf6 - what: 268000.0usdx - for: 10694.066687atom - 
```
buy ATOM with secondary account
```
height: 165608 - time: 2021-12-25T14:17:23Z - kava1h5g50w6xeej7yrynjz2z54px2cpxdqysupdw4w - what: 427706.812142usdx - for: 14452.049528atom - 
```
sell ATOM with main account (60k usdx profit)
```
height: 165613 - time: 2021-12-25T14:17:48Z - kava17x3e8z9rra5a7zve52rffyex5u63rmeh649gf6 - what: 10694.066687atom - for: 323539.136022usdx - 
```
sell ATOM with secondary account
```
height: 165617 - time: 2021-12-25T14:18:08Z - kava1h5g50w6xeej7yrynjz2z54px2cpxdqysupdw4w - what: 14452.049528atom - for: 370329.555742usdx - 
```
repeat
```
height: 165622 - time: 2021-12-25T14:18:34Z - kava1nsh262f50musa6vr4a03ft0xq0ar86aln4udsy - what: 4525.0usdx - for: 5409.476711hard - 
height: 165622 - time: 2021-12-25T14:18:34Z - kava17x3e8z9rra5a7zve52rffyex5u63rmeh649gf6 - what: 323539.136022usdx - for: 12732.762316atom - 
height: 165626 - time: 2021-12-25T14:18:54Z - kava1h5g50w6xeej7yrynjz2z54px2cpxdqysupdw4w - what: 370328.561387usdx - for: 12346.83374atom - 
height: 165631 - time: 2021-12-25T14:19:19Z - kava17x3e8z9rra5a7zve52rffyex5u63rmeh649gf6 - what: 12732.762316atom - for: 379885.846021usdx - 
height: 165636 - time: 2021-12-25T14:19:44Z - kava1h5g50w6xeej7yrynjz2z54px2cpxdqysupdw4w - what: 12346.83374atom - for: 312146.32819usdx - 
height: 165642 - time: 2021-12-25T14:20:14Z - kava17x3e8z9rra5a7zve52rffyex5u63rmeh649gf6 - what: 379885.846021usdx - for: 210186.791616swp - 
height: 165647 - time: 2021-12-25T14:20:39Z - kava1h5g50w6xeej7yrynjz2z54px2cpxdqysupdw4w - what: 312146.32819usdx - for: 149836.925813swp - 
height: 165652 - time: 2021-12-25T14:21:04Z - kava17x3e8z9rra5a7zve52rffyex5u63rmeh649gf6 - what: 210186.791616swp - for: 426311.5008usdx - 
height: 165657 - time: 2021-12-25T14:21:29Z - kava1h5g50w6xeej7yrynjz2z54px2cpxdqysupdw4w - what: 149836.925813swp - for: 263718.920771usdx -
```

### Example 2:
buy ATOM with main account
```
height: 157144 - time: 2021-12-25T02:29:29Z - kava17x3e8z9rra5a7zve52rffyex5u63rmeh649gf6 - what: 286000.0usdx - for: 10801.193292atom - 
```
buy ATOM with secondary account
```
height: 157149 - time: 2021-12-25T02:29:54Z - kava1wlvsxhj4aeujwpgr9j6szygu0xk4kgj03s9cs8 - what: 437837.987831usdx - for: 13892.867097atom - 
```
sell ATOM with main account (+140k USDX profit)
```
height: 157155 - time: 2021-12-25T02:30:24Z - kava17x3e8z9rra5a7zve52rffyex5u63rmeh649gf6 - what: 10801.193292atom - for: 346929.94864usdx - 
```
sell ATOM with secondary account (140k USDX loss)
```
height: 157161 - time: 2021-12-25T02:30:54Z - kava1wlvsxhj4aeujwpgr9j6szygu0xk4kgj03s9cs8 - what: 13892.867097atom - for: 375006.50163usdx - 
```
repeat
```
height: 157167 - time: 2021-12-25T02:31:24Z - kava17x3e8z9rra5a7zve52rffyex5u63rmeh649gf6 - what: 346929.94864usdx - for: 65715.417012osmo - 
height: 157171 - time: 2021-12-25T02:31:44Z - kava1ylsrlsw4mx9zp7nhe5pk65d5fa2xjp3s5lcg6f - what: 700.0kava - for: 3269.181444usdx - 
height: 157172 - time: 2021-12-25T02:31:49Z - kava1wlvsxhj4aeujwpgr9j6szygu0xk4kgj03s9cs8 - what: 375006.50163usdx - for: 64281.416823osmo - 
height: 157178 - time: 2021-12-25T02:32:19Z - kava17x3e8z9rra5a7zve52rffyex5u63rmeh649gf6 - what: 65718.417012osmo - for: 381876.413711usdx - 
height: 157183 - time: 2021-12-25T02:32:44Z - kava1wlvsxhj4aeujwpgr9j6szygu0xk4kgj03s9cs8 - what: 64281.416823osmo - for: 338067.424656usdx - 
```

## 7. kava1vtcpusw3fkzvhxmnuztjdan5v93tw558pp4y47 (main)
+ kava1xcwvw6jxxgx3vppzcrdmemjll7vt9t5aw57065 (secondary)
+ kava1uj8cpjujypa0wrj7k8fp2jpkp4f5euml8wykhx (secondary)
+ kava1d08eh22xr2txmt3m404vp66fhvw79m8jt8x06l (secondary)
+ kava19lnrq2n5crme7cptageamnyzkk97lcc8632h4k (secondary)

Operates multiple accounts, but seems to be playing fair with all; wants to get more prizes

No evidence was found that any of the accounts separately are violating any rules. Secondary accounts are used to win more prizes in the competition which is however the violation itself.

### Point 1: 
Swapping style is the same for all accounts and that is not how the normal player performs swaps with numbers like 44444 or 33333;

**4y47**
```
height: 4930 - time: 2021-12-16T06:17:24Z - kava1vtcpusw3fkzvhxmnuztjdan5v93tw558pp4y47 - what: 44444.0usdx - for: 28206.200315swp - log: 
height: 4934 - time: 2021-12-16T06:17:44Z - kava1vtcpusw3fkzvhxmnuztjdan5v93tw558pp4y47 - what: 35555.0usdx - for: 9204.890269kava - log: 
height: 4940 - time: 2021-12-16T06:18:15Z - kava1vtcpusw3fkzvhxmnuztjdan5v93tw558pp4y47 - what: 11110.0usdx - for: 7061.865749swp - log: 
height: 4944 - time: 2021-12-16T06:18:35Z - kava1vtcpusw3fkzvhxmnuztjdan5v93tw558pp4y47 - what: 22222.0usdx - for: 13980.710914swp - log: 
height: 4949 - time: 2021-12-16T06:19:00Z - kava1vtcpusw3fkzvhxmnuztjdan5v93tw558pp4y47 - what: 35553.0usdx - for: 45117.325052hard - log: 
height: 4956 - time: 2021-12-16T06:19:35Z - kava1vtcpusw3fkzvhxmnuztjdan5v93tw558pp4y47 - what: 14444.0usdx - for: 3680.11184kava - log: 
height: 4968 - time: 2021-12-16T06:20:35Z - kava1vtcpusw3fkzvhxmnuztjdan5v93tw558pp4y47 - what: 15554.0usdx - for: 3925.330708kava - log: 
```
**ykhx**
```
height: 5176 - time: 2021-12-16T06:37:59Z - kava1uj8cpjujypa0wrj7k8fp2jpkp4f5euml8wykhx - what: 41333.019563usdx - for: 26155.45021swp - log: 
height: 5197 - time: 2021-12-16T06:39:44Z - kava1uj8cpjujypa0wrj7k8fp2jpkp4f5euml8wykhx - what: 44444.0usdx - for: 67630.771116hard - log: 
height: 5201 - time: 2021-12-16T06:40:05Z - kava1uj8cpjujypa0wrj7k8fp2jpkp4f5euml8wykhx - what: 33333.0usdx - for: 47926.553182hard - log: 
height: 5205 - time: 2021-12-16T06:40:25Z - kava1uj8cpjujypa0wrj7k8fp2jpkp4f5euml8wykhx - what: 55554.0usdx - for: 80793.300147hard - log: 
```
**7065**
```
height: 4205 - time: 2021-12-16T05:16:45Z - kava1xcwvw6jxxgx3vppzcrdmemjll7vt9t5aw57065 - what: 55553.838158usdx - for: 84543.159017hard - log: 
height: 4209 - time: 2021-12-16T05:17:05Z - kava1xcwvw6jxxgx3vppzcrdmemjll7vt9t5aw57065 - what: 45227.0usdx - for: 63976.033921hard - log: 
height: 4234 - time: 2021-12-16T05:19:11Z - kava1xcwvw6jxxgx3vppzcrdmemjll7vt9t5aw57065 - what: 55555.0usdx - for: 14598.041408kava - log: 
height: 4240 - time: 2021-12-16T05:19:41Z - kava1xcwvw6jxxgx3vppzcrdmemjll7vt9t5aw57065 - what: 55554.0usdx - for: 14761.312342kava - log: 
height: 4248 - time: 2021-12-16T05:20:21Z - kava1xcwvw6jxxgx3vppzcrdmemjll7vt9t5aw57065 - what: 36666.0usdx - for: 51989.572134hard - log: 
```
**x06l**
```
height: 4091 - time: 2021-12-16T05:07:13Z - kava1d08eh22xr2txmt3m404vp66fhvw79m8jt8x06l - what: 15555.0usdx - for: 20202.104044hard - log: 
height: 4100 - time: 2021-12-16T05:07:58Z - kava1d08eh22xr2txmt3m404vp66fhvw79m8jt8x06l - what: 11332.0usdx - for: 14564.327238hard - log: 
height: 4105 - time: 2021-12-16T05:08:23Z - kava1d08eh22xr2txmt3m404vp66fhvw79m8jt8x06l - what: 11111.0usdx - for: 13992.190069hard - log: 
```
**2h4k**
```
height: 2805 - time: 2021-12-16T03:19:38Z - kava19lnrq2n5crme7cptageamnyzkk97lcc8632h4k - what: 44444.0usdx - for: 23893.610316swp - log: 
height: 2809 - time: 2021-12-16T03:19:58Z - kava19lnrq2n5crme7cptageamnyzkk97lcc8632h4k - what: 55555.0usdx - for: 29005.82126swp - log: 
height: 2813 - time: 2021-12-16T03:20:18Z - kava19lnrq2n5crme7cptageamnyzkk97lcc8632h4k - what: 55554.0usdx - for: 27892.169122swp - log: 
height: 2818 - time: 2021-12-16T03:20:43Z - kava19lnrq2n5crme7cptageamnyzkk97lcc8632h4k - what: 27447.0usdx - for: 14139.274909swp - log: 
height: 3636 - time: 2021-12-16T04:29:09Z - kava19lnrq2n5crme7cptageamnyzkk97lcc8632h4k - what: 55555.0usdx - for: 13913.785521kava - log: 
height: 3641 - time: 2021-12-16T04:29:34Z - kava19lnrq2n5crme7cptageamnyzkk97lcc8632h4k - what: 44443.0usdx - for: 27097.231166swp - log: 
```

### Point 2:
Perfect timing. When one account starts activity, the other account stops its activity
None of the accounts overlap each other and operate at the same time. In example 3 the accounts start and finish their activity in a row one after the other on the same day

It's better to compare the full logs of all 5 accounts swap transactions however the following examples are illustrative

#### Example 1: accounts 4y47 vs x06l vs 7065
- 4y47 ~ xx - 04:55 
- x06l ~ 04:57 - 05:08
- 7065 ~ 05:09 - 05:23
- 4y47 ~ 05:26 - xx

4y47 does a lot of transactions before ~04:55 and then stops; continues at ~05:26 and does a lot of transactions
```
... many txs
height: 3948 - time: 2021-12-16T04:55:15Z - kava1vtcpusw3fkzvhxmnuztjdan5v93tw558pp4y47 - what: 55555.0usdx - for: 73794.323729hard - log: 
... 0 txs
height: 4322 - time: 2021-12-16T05:26:32Z - kava1vtcpusw3fkzvhxmnuztjdan5v93tw558pp4y47 - what: 55554.0usdx - for: 14714.424186kava - log: 
... many txs
```

x06l was silent until ~04:57, stopped at ~05:08; the next txs are only in the morning
```
... no txs
height: 3969 - time: 2021-12-16T04:57:01Z - kava1d08eh22xr2txmt3m404vp66fhvw79m8jt8x06l - what: 6500.0akt - for: 36947.602299usdx - log: 
... performs 7 more txs
height: 4105 - time: 2021-12-16T05:08:23Z - kava1d08eh22xr2txmt3m404vp66fhvw79m8jt8x06l - what: 11111.0usdx - for: 13992.190069hard - log: 
... no txs
```

7065 was silent until ~05:09, stopped at ~05:23
```
... no txs
height: 4122 - time: 2021-12-16T05:09:49Z - kava1xcwvw6jxxgx3vppzcrdmemjll7vt9t5aw57065 - what: 6500.0akt - for: 39000.050293usdx - log: 
... perfoms 14 txs
height: 4290 - time: 2021-12-16T05:23:52Z - kava1xcwvw6jxxgx3vppzcrdmemjll7vt9t5aw57065 - what: 35000.000002usdx - for: 9011.852664kava - log: 
... nomore txs until morning
height: 8093 - time: 2021-12-16T10:42:01Z - kava1xcwvw6jxxgx3vppzcrdmemjll7vt9t5aw57065 - what: 27444.406896usdx - for: 34786.048211hard - log: 
```

#### Example 2: 4y47 vs ykhx
- 4y47 ~ xx - 06:29
- ykhx ~ 06:30 - 07:04
- 4y47 ~ 07:16 - xx

4y47 does a lot of transactions before ~06:29 and then stops; continues transactions at ~07:16 and does a lot of transactions after
```
height: 5060 - time: 2021-12-16T06:28:17Z - kava1vtcpusw3fkzvhxmnuztjdan5v93tw558pp4y47 - what: 14725.231811usdx - for: 19464.301137hard - log: 
height: 5070 - time: 2021-12-16T06:29:07Z - kava1vtcpusw3fkzvhxmnuztjdan5v93tw558pp4y47 - what: 3333.0usdx - for: 841.091125kava - log: 
... no txs here
height: 5639 - time: 2021-12-16T07:16:43Z - kava1vtcpusw3fkzvhxmnuztjdan5v93tw558pp4y47 - what: 1211.0usdx - for: 89.91302atom - log: 
height: 5646 - time: 2021-12-16T07:17:18Z - kava1vtcpusw3fkzvhxmnuztjdan5v93tw558pp4y47 - what: 75456.0usdx - for: 19893.94129kava - log: 
```

ykhx was silent until ~06:30, stopped at ~07:04
```
... no txs
height: 5092 - time: 2021-12-16T06:30:57Z - kava1uj8cpjujypa0wrj7k8fp2jpkp4f5euml8wykhx - what: 6500.0akt - for: 40398.696591usdx - log: 
... performs 20+ txs
height: 5487 - time: 2021-12-16T07:04:00Z - kava1uj8cpjujypa0wrj7k8fp2jpkp4f5euml8wykhx - what: 1999.765796kava - for: 8722.738599usdx - log: 
... nomore txs on this day
```

#### Example 3: 4y47 vs 2h4k
- 4y47 ~ xx - 02:58
- 2h4k ~ 03:04 - 03:20
- 4y47 ~ 03:22 - xx

```
... many transactions before
height: 2543 - time: 2021-12-16T02:57:43Z - kava1vtcpusw3fkzvhxmnuztjdan5v93tw558pp4y47 - what: 44434.0usdx - for: 10027.097523kava - log: 
height: 2551 - time: 2021-12-16T02:58:23Z - kava1vtcpusw3fkzvhxmnuztjdan5v93tw558pp4y47 - what: 14443.0usdx - for: 17326.86167hard - log: 
... stops here
height: 2835 - time: 2021-12-16T03:22:08Z - kava1vtcpusw3fkzvhxmnuztjdan5v93tw558pp4y47 - what: 44444.0usdx - for: 11046.609693kava - log: 
height: 2839 - time: 2021-12-16T03:22:29Z - kava1vtcpusw3fkzvhxmnuztjdan5v93tw558pp4y47 - what: 4442.0usdx - for: 2262.665093swp - log: 
... continues a lot of transactions
```

2h4k starts activity right in this time gap
```
... no txs
height: 2624 - time: 2021-12-16T03:04:29Z - kava19lnrq2n5crme7cptageamnyzkk97lcc8632h4k - what: 6500.0akt - for: 35460.713357usdx - log: 
... performs 10 txs
height: 2818 - time: 2021-12-16T03:20:43Z - kava19lnrq2n5crme7cptageamnyzkk97lcc8632h4k - what: 27447.0usdx - for: 14139.274909swp - log: 
... stops activity
```

1 hour later the same situation:
- 4y47 ~ xx - 04:26
- 2h4k ~ 04:29 - 04:38
- 4y47 ~ 04:39 - xx

4y47 is doing different transactions; stops 04:26 - 04:39; continues
```
... many txs
height: 3599 - time: 2021-12-16T04:26:03Z - kava1vtcpusw3fkzvhxmnuztjdan5v93tw558pp4y47 - what: 14444.0usdx - for: 17957.311061hard - log: 
height: 3606 - time: 2021-12-16T04:26:39Z - kava1vtcpusw3fkzvhxmnuztjdan5v93tw558pp4y47 - what: 55554.0usdx - for: 14121.554763kava - log: 
... no txs
height: 3758 - time: 2021-12-16T04:39:21Z - kava1vtcpusw3fkzvhxmnuztjdan5v93tw558pp4y47 - what: 55555.0usdx - for: 82047.947178hard - log: 
height: 3762 - time: 2021-12-16T04:39:42Z - kava1vtcpusw3fkzvhxmnuztjdan5v93tw558pp4y47 - what: 43333.0usdx - for: 57042.597164hard - log: 
... continues with many transactions
```

2h4k starts activity
```
... no txs
height: 3636 - time: 2021-12-16T04:29:09Z - kava19lnrq2n5crme7cptageamnyzkk97lcc8632h4k - what: 55555.0usdx - for: 13913.785521kava - log: 
... performs 10 txs
height: 3749 - time: 2021-12-16T04:38:36Z - kava19lnrq2n5crme7cptageamnyzkk97lcc8632h4k - what: 49856.202331usdx - for: 74561.876048hard - log: 
... no activity afterwards
```

#### Example 4: 4y47 vs x06l vs 7065 vs ykhx vs 2h4k
All accounts appear in a row with the following timing on Dec 21:

- y47 ~ 04:07 - 04:16
- 2h4k ~ 04:23 - 04:25
- ykhx ~ 04:33 - 04:43
- x06l ~ 04:51 - 05:01
- 7065 ~ 05:15 - 05:24

04:07 - 04:16 4y47 started activity
```
... no TXs before
height: 89458 - time: 2021-12-21T04:07:57Z - kava1vtcpusw3fkzvhxmnuztjdan5v93tw558pp4y47 - what: 763.602866luna - for: 30728.796367usdx - log: 
height: 89469 - time: 2021-12-21T04:08:52Z - kava1vtcpusw3fkzvhxmnuztjdan5v93tw558pp4y47 - what: 19000.0swp - for: 31547.989055usdx - log: 
height: 89481 - time: 2021-12-21T04:09:52Z - kava1vtcpusw3fkzvhxmnuztjdan5v93tw558pp4y47 - what: 18666.0swp - for: 30550.977727usdx - log: 
height: 89497 - time: 2021-12-21T04:11:13Z - kava1vtcpusw3fkzvhxmnuztjdan5v93tw558pp4y47 - what: 686.172956luna - for: 27215.791282usdx - log: 
height: 89521 - time: 2021-12-21T04:13:13Z - kava1vtcpusw3fkzvhxmnuztjdan5v93tw558pp4y47 - what: 650.676857luna - for: 25467.888709usdx - log: height: 89534 - time: 2021-12-21T04:14:18Z - cdp-withdraw - kava1vtcpusw3fkzvhxmnuztjdan5v93tw558pp4y47 - what: 30400.0hard 
height: 89553 - time: 2021-12-21T04:15:54Z - hard-borrow - kava1vtcpusw3fkzvhxmnuztjdan5v93tw558pp4y47 - what: 26666.0hard 
height: 89558 - time: 2021-12-21T04:16:19Z - hard-borrow - kava1vtcpusw3fkzvhxmnuztjdan5v93tw558pp4y47 - what: 1000.0hard 
height: 89564 - time: 2021-12-21T04:16:49Z - hard-borrow - kava1vtcpusw3fkzvhxmnuztjdan5v93tw558pp4y47 - what: 13333.0hard 
... no TXs after
```

04:23 - 04:25 2h4k started activity
```
height: 89647 - time: 2021-12-21T04:23:45Z - kava19lnrq2n5crme7cptageamnyzkk97lcc8632h4k - what: 286.0luna - for: 11607.810239usdx - log: 
height: 89663 - time: 2021-12-21T04:25:06Z - kava19lnrq2n5crme7cptageamnyzkk97lcc8632h4k - what: 92.205525luna - for: 3728.045115usdx - log: 
... no TXs after
```

04:33 - 04:43 x06l started activity right after the first one
```
... no TXs before
height: 89762 - time: 2021-12-21T04:33:23Z - hard-withdraw - kava1uj8cpjujypa0wrj7k8fp2jpkp4f5euml8wykhx - what: 189.278863luna 
height: 89767 - time: 2021-12-21T04:33:48Z - kava1uj8cpjujypa0wrj7k8fp2jpkp4f5euml8wykhx - what: 189.278863luna - for: 7793.651227usdx - log: 
height: 89780 - time: 2021-12-21T04:34:53Z - kava1uj8cpjujypa0wrj7k8fp2jpkp4f5euml8wykhx - what: 1901.621907kava - for: 9303.737776usdx - log: 
height: 89792 - time: 2021-12-21T04:35:53Z - kava1uj8cpjujypa0wrj7k8fp2jpkp4f5euml8wykhx - what: 2300.0kava - for: 11222.386449usdx - log: 
height: 89801 - time: 2021-12-21T04:36:38Z - kava1uj8cpjujypa0wrj7k8fp2jpkp4f5euml8wykhx - what: 2844.0kava - for: 13830.871234usdx - log: 
height: 89809 - time: 2021-12-21T04:37:19Z - kava1uj8cpjujypa0wrj7k8fp2jpkp4f5euml8wykhx - what: 3455.0kava - for: 16734.434839usdx - log: 
height: 89818 - time: 2021-12-21T04:38:04Z - kava1uj8cpjujypa0wrj7k8fp2jpkp4f5euml8wykhx - what: 4200.0kava - for: 20243.329289usdx - log: 
height: 89828 - time: 2021-12-21T04:38:54Z - kava1uj8cpjujypa0wrj7k8fp2jpkp4f5euml8wykhx - what: 5000.0kava - for: 23957.927067usdx - log: 
height: 89837 - time: 2021-12-21T04:39:39Z - kava1uj8cpjujypa0wrj7k8fp2jpkp4f5euml8wykhx - what: 6000.0kava - for: 28548.771092usdx - log: 
height: 89850 - time: 2021-12-21T04:40:44Z - kava1uj8cpjujypa0wrj7k8fp2jpkp4f5euml8wykhx - what: 7100.0kava - for: 33503.05411usdx - log: 
height: 89857 - time: 2021-12-21T04:41:20Z - cdp-withdraw - kava1uj8cpjujypa0wrj7k8fp2jpkp4f5euml8wykhx - what: 40000.0hard 
height: 89866 - time: 2021-12-21T04:42:05Z - hard-borrow - kava1uj8cpjujypa0wrj7k8fp2jpkp4f5euml8wykhx - what: 21111.0hard 
height: 89871 - time: 2021-12-21T04:42:30Z - hard-borrow - kava1uj8cpjujypa0wrj7k8fp2jpkp4f5euml8wykhx - what: 11111.0hard 
height: 89875 - time: 2021-12-21T04:42:50Z - hard-borrow - kava1uj8cpjujypa0wrj7k8fp2jpkp4f5euml8wykhx - what: 5555.0hard 
height: 89880 - time: 2021-12-21T04:43:15Z - hard-borrow - kava1uj8cpjujypa0wrj7k8fp2jpkp4f5euml8wykhx - what: 2222.0hard 
... no TXs after
```

04:51 - 05:01 7065 started activity; no overlapping
```
... no TXs before
height: 89975 - time: 2021-12-21T04:51:12Z - hard-withdraw - kava1d08eh22xr2txmt3m404vp66fhvw79m8jt8x06l - what: 888.0usdx 
height: 89986 - time: 2021-12-21T04:52:07Z - hard-withdraw - kava1d08eh22xr2txmt3m404vp66fhvw79m8jt8x06l - what: 1111.0usdx 
height: 89992 - time: 2021-12-21T04:52:37Z - hard-withdraw - kava1d08eh22xr2txmt3m404vp66fhvw79m8jt8x06l - what: 1333.0usdx 
height: 90003 - time: 2021-12-21T04:53:32Z - hard-withdraw - kava1d08eh22xr2txmt3m404vp66fhvw79m8jt8x06l - what: 55.0luna 
height: 90032 - time: 2021-12-21T04:55:58Z - kava1d08eh22xr2txmt3m404vp66fhvw79m8jt8x06l - what: 55.0luna - for: 2270.253153usdx - log: 
height: 90041 - time: 2021-12-21T04:56:43Z - cdp-withdraw - kava1d08eh22xr2txmt3m404vp66fhvw79m8jt8x06l - what: 2600.0hard 
height: 90047 - time: 2021-12-21T04:57:13Z - hard-withdraw - kava1d08eh22xr2txmt3m404vp66fhvw79m8jt8x06l - what: 77.0luna 
height: 90051 - time: 2021-12-21T04:57:33Z - kava1d08eh22xr2txmt3m404vp66fhvw79m8jt8x06l - what: 77.0luna - for: 3174.108482usdx - log: 
height: 90058 - time: 2021-12-21T04:58:08Z - cdp-withdraw - kava1d08eh22xr2txmt3m404vp66fhvw79m8jt8x06l - what: 3888.0hard 
height: 90063 - time: 2021-12-21T04:58:33Z - hard-withdraw - kava1d08eh22xr2txmt3m404vp66fhvw79m8jt8x06l - what: 105.0luna 
height: 90066 - time: 2021-12-21T04:58:49Z - kava1d08eh22xr2txmt3m404vp66fhvw79m8jt8x06l - what: 105.0luna - for: 4320.365748usdx - log: 
height: 90072 - time: 2021-12-21T04:59:19Z - cdp-withdraw - kava1d08eh22xr2txmt3m404vp66fhvw79m8jt8x06l - what: 5120.0hard 
height: 90077 - time: 2021-12-21T04:59:44Z - hard-withdraw - kava1d08eh22xr2txmt3m404vp66fhvw79m8jt8x06l - what: 128.255984luna 
height: 90080 - time: 2021-12-21T04:59:59Z - kava1d08eh22xr2txmt3m404vp66fhvw79m8jt8x06l - what: 128.255984luna - for: 5264.835395usdx - log: 
height: 90087 - time: 2021-12-21T05:00:34Z - cdp-withdraw - kava1d08eh22xr2txmt3m404vp66fhvw79m8jt8x06l - what: 6400.0hard 
height: 90094 - time: 2021-12-21T05:01:09Z - hard-borrow - kava1d08eh22xr2txmt3m404vp66fhvw79m8jt8x06l - what: 111.0atom 
height: 90100 - time: 2021-12-21T05:01:39Z - hard-borrow - kava1d08eh22xr2txmt3m404vp66fhvw79m8jt8x06l - what: 66.0atom 
... no TXs after
```

05:15 - 05:24 ykhx account started
```
... no TXs before
height: 90266 - time: 2021-12-21T05:15:32Z - hard-withdraw - kava1xcwvw6jxxgx3vppzcrdmemjll7vt9t5aw57065 - what: 66.0luna 
height: 90272 - time: 2021-12-21T05:16:02Z - hard-withdraw - kava1xcwvw6jxxgx3vppzcrdmemjll7vt9t5aw57065 - what: 113.0luna 
height: 90277 - time: 2021-12-21T05:16:28Z - hard-withdraw - kava1xcwvw6jxxgx3vppzcrdmemjll7vt9t5aw57065 - what: 255.0luna 
height: 90281 - time: 2021-12-21T05:16:48Z - hard-withdraw - kava1xcwvw6jxxgx3vppzcrdmemjll7vt9t5aw57065 - what: 555.0luna 
height: 90285 - time: 2021-12-21T05:17:08Z - hard-withdraw - kava1xcwvw6jxxgx3vppzcrdmemjll7vt9t5aw57065 - what: 531.540225luna 
height: 90290 - time: 2021-12-21T05:17:33Z - kava1xcwvw6jxxgx3vppzcrdmemjll7vt9t5aw57065 - what: 518.639115luna - for: 21715.712283usdx - log: 
height: 90297 - time: 2021-12-21T05:18:08Z - cdp-withdraw - kava1xcwvw6jxxgx3vppzcrdmemjll7vt9t5aw57065 - what: 26111.0hard 
height: 90300 - time: 2021-12-21T05:18:23Z - kava1xcwvw6jxxgx3vppzcrdmemjll7vt9t5aw57065 - what: 26111.0hard - for: 23847.573476usdx - log: 
height: 90314 - time: 2021-12-21T05:19:33Z - cdp-withdraw - kava1xcwvw6jxxgx3vppzcrdmemjll7vt9t5aw57065 - what: 28888.0hard 
height: 90317 - time: 2021-12-21T05:19:48Z - kava1xcwvw6jxxgx3vppzcrdmemjll7vt9t5aw57065 - what: 28888.0hard - for: 26154.135683usdx - log: 
height: 90324 - time: 2021-12-21T05:20:23Z - cdp-withdraw - kava1xcwvw6jxxgx3vppzcrdmemjll7vt9t5aw57065 - what: 31111.0hard 
height: 90334 - time: 2021-12-21T05:21:14Z - kava1xcwvw6jxxgx3vppzcrdmemjll7vt9t5aw57065 - what: 31111.0hard - for: 27900.535758usdx - log: 
height: 90342 - time: 2021-12-21T05:21:54Z - cdp-withdraw - kava1xcwvw6jxxgx3vppzcrdmemjll7vt9t5aw57065 - what: 33500.0hard 
height: 90352 - time: 2021-12-21T05:22:44Z - hard-borrow - kava1xcwvw6jxxgx3vppzcrdmemjll7vt9t5aw57065 - what: 27800.0hard 
height: 90357 - time: 2021-12-21T05:23:09Z - hard-borrow - kava1xcwvw6jxxgx3vppzcrdmemjll7vt9t5aw57065 - what: 13666.0hard 
height: 90364 - time: 2021-12-21T05:23:44Z - hard-borrow - kava1xcwvw6jxxgx3vppzcrdmemjll7vt9t5aw57065 - what: 6111.0hard 
height: 90371 - time: 2021-12-21T05:24:19Z - hard-borrow - kava1xcwvw6jxxgx3vppzcrdmemjll7vt9t5aw57065 - what: 3333.0hard 
height: 90375 - time: 2021-12-21T05:24:39Z - hard-borrow - kava1xcwvw6jxxgx3vppzcrdmemjll7vt9t5aw57065 - what: 2222.0hard 
... no TXs after
```
#### Possbile relations
I have identified accounts with similar behaviour, but it's time consuming to compare everything. I provide suspicious accounts below

**kava1ng9306lcttrr2p0zn8sw66kq59j6yh80ju2wqn**
+ same pattern
```
height: 10375 - time: 2021-12-16T13:52:55Z - kava1ng9306lcttrr2p0zn8sw66kq59j6yh80ju2wqn - what: 126768.931842usdx - for: 79541.467298swp - log: 
height: 10392 - time: 2021-12-16T13:54:20Z - kava1ng9306lcttrr2p0zn8sw66kq59j6yh80ju2wqn - what: 11111.0usdx - for: 6843.808624swp - log: 
height: 10409 - time: 2021-12-16T13:55:46Z - kava1ng9306lcttrr2p0zn8sw66kq59j6yh80ju2wqn - what: 58111.0usdx - for: 35818.266347swp - log: 

height: 59820 - time: 2021-12-19T10:48:56Z - hard-borrow - kava1ng9306lcttrr2p0zn8sw66kq59j6yh80ju2wqn - what: 61111.0hard 
height: 59822 - time: 2021-12-19T10:49:06Z - hard-deposit - kava1ng9306lcttrr2p0zn8sw66kq59j6yh80ju2wqn - what: 61111.0hard 
height: 59825 - time: 2021-12-19T10:49:21Z - hard-borrow - kava1ng9306lcttrr2p0zn8sw66kq59j6yh80ju2wqn - what: 31111.0hard 
height: 59827 - time: 2021-12-19T10:49:31Z - hard-deposit - kava1ng9306lcttrr2p0zn8sw66kq59j6yh80ju2wqn - what: 31111.0hard 
height: 59829 - time: 2021-12-19T10:49:41Z - hard-borrow - kava1ng9306lcttrr2p0zn8sw66kq59j6yh80ju2wqn - what: 14444.0hard 
height: 59831 - time: 2021-12-19T10:49:51Z - hard-deposit - kava1ng9306lcttrr2p0zn8sw66kq59j6yh80ju2wqn - what: 14444.0hard 
height: 59833 - time: 2021-12-19T10:50:01Z - hard-borrow - kava1ng9306lcttrr2p0zn8sw66kq59j6yh80ju2wqn - what: 6666.0hard 
height: 59835 - time: 2021-12-19T10:50:11Z - hard-deposit - kava1ng9306lcttrr2p0zn8sw66kq59j6yh80ju2wqn - what: 6666.0hard 
```

## 8. kava1gfdkdeyvamglk2tc8quqtddjksmnr7eya7uh3k - liquidators
- kava1svtehhtemmuk5hl9qxydhswdhqcfjxvrphws65

kava1gfdkdeyvamglk2tc8quqtddjksmnr7eya7uh3k - top auction liquidator; bought collateral at almost 0 cost most of the time

kava1svtehhtemmuk5hl9qxydhswdhqcfjxvrphws65 - competing top auction liquidator

While auctions are technicaly an important part of the platform and must be tested thoroughly too, such huge advantage makes the technicaly skilled player instant winner. It should be clearly stated in the rules how the auctions must be treated otherwise some people think auctions are forbidden while the others profit from them. It was mentioned in the blog that auctions won't be conducted, yet we have 2 liquidators who buy most of the collateral at very low cost like 50$ for 50000$

I have no information how much each of the accounts gained total from the auctions, but their rewards rate is way ahead of the other players; I leave this to the Team

uh3k has very low swap activity which was the key to success in the competition which tells he benefited solely from auctions

By the time this report is created:

**uh3k** performed total 3562 bids - operates a liquidation bot that outbids other players which make liquidations not interesting for the other players and allows to bid cheap for most auctions

**ws65** performed total 2964 bids

These 2 players are the most profitable players (top 2) in the game with no special tactics but buying collateral cheap

### Example:
The price for the auctions is very low
```
height: 33016 - time: 2021-12-17T21:27:02Z - last_bidder: kava1svtehhtemmuk5hl9qxydhswdhqcfjxvrphws65 - id: 284 - what: 437.500001usdx
height: 33017 - time: 2021-12-17T21:27:07Z - last_bidder: kava1svtehhtemmuk5hl9qxydhswdhqcfjxvrphws65 - id: 285 - what: 57.776251usdx
height: 33019 - time: 2021-12-17T21:27:17Z - last_bidder: kava1svtehhtemmuk5hl9qxydhswdhqcfjxvrphws65 - id: 286 - what: 397.07501usdx
height: 33024 - time: 2021-12-17T21:27:42Z - last_bidder: kava1svtehhtemmuk5hl9qxydhswdhqcfjxvrphws65 - id: 297 - what: 1228.485663usdx
height: 33026 - time: 2021-12-17T21:27:52Z - last_bidder: kava1svtehhtemmuk5hl9qxydhswdhqcfjxvrphws65 - id: 299 - what: 143.850001usdx
height: 33028 - time: 2021-12-17T21:28:02Z - last_bidder: kava1svtehhtemmuk5hl9qxydhswdhqcfjxvrphws65 - id: 300 - what: 0.3675usdx
height: 34564 - time: 2021-12-17T23:36:31Z - last_bidder: kava1svtehhtemmuk5hl9qxydhswdhqcfjxvrphws65 - id: 287 - what: 23.283388hard
height: 34566 - time: 2021-12-17T23:36:41Z - last_bidder: kava1svtehhtemmuk5hl9qxydhswdhqcfjxvrphws65 - id: 288 - what: 0.006378atom
height: 34568 - time: 2021-12-17T23:36:51Z - last_bidder: kava1svtehhtemmuk5hl9qxydhswdhqcfjxvrphws65 - id: 289 - what: 0.038643atom
height: 34570 - time: 2021-12-17T23:37:01Z - last_bidder: kava1svtehhtemmuk5hl9qxydhswdhqcfjxvrphws65 - id: 290 - what: 0.101101akt
height: 34572 - time: 2021-12-17T23:37:11Z - last_bidder: kava1svtehhtemmuk5hl9qxydhswdhqcfjxvrphws65 - id: 291 - what: 0.005003luna
height: 34573 - time: 2021-12-17T23:37:16Z - last_bidder: kava1svtehhtemmuk5hl9qxydhswdhqcfjxvrphws65 - id: 292 - what: 0.044986osmo
height: 34575 - time: 2021-12-17T23:37:26Z - last_bidder: kava1svtehhtemmuk5hl9qxydhswdhqcfjxvrphws65 - id: 293 - what: 0.175159osmo
```

### Example 2:
Outbidding by liquidation bot
```
height: 100942 - time: 2021-12-21T20:08:32Z - last_bidder: kava1gfdkdeyvamglk2tc8quqtddjksmnr7eya7uh3k - id: 538 - what: 50.55usdx
height: 100951 - time: 2021-12-21T20:09:17Z - last_bidder: kava1gfdkdeyvamglk2tc8quqtddjksmnr7eya7uh3k - id: 538 - what: 101.1usdx
height: 100986 - time: 2021-12-21T20:12:12Z - last_bidder: kava1gfdkdeyvamglk2tc8quqtddjksmnr7eya7uh3k - id: 538 - what: 10110.0usdx
height: 100991 - time: 2021-12-21T20:12:37Z - last_bidder: kava1gfdkdeyvamglk2tc8quqtddjksmnr7eya7uh3k - id: 538 - what: 20220.0usdx
height: 101025 - time: 2021-12-21T20:15:28Z - last_bidder: kava1gfdkdeyvamglk2tc8quqtddjksmnr7eya7uh3k - id: 538 - what: 30330.0usdx
height: 101035 - time: 2021-12-21T20:16:18Z - last_bidder: kava1gfdkdeyvamglk2tc8quqtddjksmnr7eya7uh3k - id: 538 - what: 40440.0usdx
height: 101042 - time: 2021-12-21T20:16:53Z - last_bidder: kava1gfdkdeyvamglk2tc8quqtddjksmnr7eya7uh3k - id: 538 - what: 42462.0usdx
```

## 9. **kava1ueu592zmh5aqmnt9aqddglvwuvwg0krjml0r2n** - probable multiaccounts
   - **kava1lueh9u37pcjktccg7kd3yj5jl2vwqax4565w67**
   - **kava1dl6pgkgp0849863zu86jldhm3fe37ut299k4ga**
   - **kava15vkstzpueykxaprm84sra7ejtp6g6ep58z6dpt**
   - **kava1a4aap0glvcww5fw4ypfvsd80ta0cksl0vu9qkl**

The most suspicious part here is similarity 4 (timing) and similarity 5 (pattern). This example might be false-positive, but it's fine to illustrate the idea and strategy.

##### 1 similarity: close number of transactions
player 33 5w67: 126 txs, 12 swap txs

player 37 k4ga: 108 txs, 11 swap txs

player 39 9qkl: 106 txs, 7 swap txs

player 46 6dpt: 120 txs, 11 swap txs

player 47 0r2n: 104 txs, 9 swap txs

##### 2 similarity: same starting strategy
All sharing the same swaping strategy at the start of the game (or close to the start like with k4ga): sell everything for usdx
```
height: 5956 - time: 2021-12-16T07:43:14Z - kava1ueu592zmh5aqmnt9aqddglvwuvwg0krjml0r2n - what: 80000.0hard - for: 60923.772927usdx - log: 
height: 5977 - time: 2021-12-16T07:45:00Z - kava1ueu592zmh5aqmnt9aqddglvwuvwg0krjml0r2n - what: 450.0atom - for: 6998.705691usdx - log: 
height: 5984 - time: 2021-12-16T07:45:35Z - kava1ueu592zmh5aqmnt9aqddglvwuvwg0krjml0r2n - what: 180.0luna - for: 8484.809991usdx - log: 
height: 5991 - time: 2021-12-16T07:46:10Z - kava1ueu592zmh5aqmnt9aqddglvwuvwg0krjml0r2n - what: 2200.0osmo - for: 11880.983103usdx - log: 
height: 6051 - time: 2021-12-16T07:51:11Z - kava1ueu592zmh5aqmnt9aqddglvwuvwg0krjml0r2n - what: 40000.0swp - for: 63080.949083usdx - log: 

height: 5700 - time: 2021-12-16T07:21:49Z - kava1lueh9u37pcjktccg7kd3yj5jl2vwqax4565w67 - what: 80000.0hard - for: 64468.538806usdx - log: 
height: 5709 - time: 2021-12-16T07:22:34Z - kava1lueh9u37pcjktccg7kd3yj5jl2vwqax4565w67 - what: 6500.0akt - for: 43077.640756usdx - log: 
height: 5739 - time: 2021-12-16T07:25:05Z - kava1lueh9u37pcjktccg7kd3yj5jl2vwqax4565w67 - what: 15500.0swp - for: 24655.263883usdx - log: 
height: 5747 - time: 2021-12-16T07:25:45Z - kava1lueh9u37pcjktccg7kd3yj5jl2vwqax4565w67 - what: 257.929541swp - for: 409.335251usdx - log: 
height: 5773 - time: 2021-12-16T07:27:56Z - kava1lueh9u37pcjktccg7kd3yj5jl2vwqax4565w67 - what: 200.0usdx - for: 39.326146osmo - log: 
height: 5801 - time: 2021-12-16T07:30:16Z - kava1lueh9u37pcjktccg7kd3yj5jl2vwqax4565w67 - what: 499.999999atom - for: 7224.19307usdx - log: 
height: 5808 - time: 2021-12-16T07:30:51Z - kava1lueh9u37pcjktccg7kd3yj5jl2vwqax4565w67 - what: 190.0luna - for: 7618.828422usdx - log: 
height: 5813 - time: 2021-12-16T07:31:16Z - kava1lueh9u37pcjktccg7kd3yj5jl2vwqax4565w67 - what: 2000.0osmo - for: 9239.949016usdx - log: 
height: 5873 - time: 2021-12-16T07:36:17Z - kava1lueh9u37pcjktccg7kd3yj5jl2vwqax4565w67 - what: 24999.0usdx - for: 6247.773646kava - log: 

height: 22897 - time: 2021-12-17T07:20:31Z - kava1dl6pgkgp0849863zu86jldhm3fe37ut299k4ga - what: 8569.394671akt - for: 22806.227655usdx - log: 
height: 22901 - time: 2021-12-17T07:20:52Z - kava1dl6pgkgp0849863zu86jldhm3fe37ut299k4ga - what: 2400.0osmo - for: 9862.615565usdx - log: 
height: 22904 - time: 2021-12-17T07:21:07Z - kava1dl6pgkgp0849863zu86jldhm3fe37ut299k4ga - what: 42835.858898swp - for: 58664.44727usdx - log: 
height: 22908 - time: 2021-12-17T07:21:27Z - kava1dl6pgkgp0849863zu86jldhm3fe37ut299k4ga - what: 16660.0kava - for: 75908.723914usdx - log: 
height: 22959 - time: 2021-12-17T07:25:43Z - kava1dl6pgkgp0849863zu86jldhm3fe37ut299k4ga - what: 80000.0hard - for: 70548.838846usdx - log: 

height: 21003 - time: 2021-12-17T04:42:05Z - kava1a4aap0glvcww5fw4ypfvsd80ta0cksl0vu9qkl - what: 80002.281196hard - for: 62078.442001usdx - log: 
height: 21007 - time: 2021-12-17T04:42:25Z - kava1a4aap0glvcww5fw4ypfvsd80ta0cksl0vu9qkl - what: 6504.745722akt - for: 20134.568868usdx - log: 
height: 21012 - time: 2021-12-17T04:42:50Z - kava1a4aap0glvcww5fw4ypfvsd80ta0cksl0vu9qkl - what: 16600.0kava - for: 74076.316271usdx - log: 
height: 21039 - time: 2021-12-17T04:45:06Z - kava1a4aap0glvcww5fw4ypfvsd80ta0cksl0vu9qkl - what: 2400.0osmo - for: 10264.131012usdx - log: 
height: 21052 - time: 2021-12-17T04:46:11Z - kava1a4aap0glvcww5fw4ypfvsd80ta0cksl0vu9qkl - what: 40000.0swp - for: 63358.136624usdx - log: 

height: 23449 - time: 2021-12-17T08:06:42Z - kava15vkstzpueykxaprm84sra7ejtp6g6ep58z6dpt - what: 8106.11419akt - for: 20097.228927usdx - log: 
height: 23453 - time: 2021-12-17T08:07:02Z - kava15vkstzpueykxaprm84sra7ejtp6g6ep58z6dpt - what: 2400.0osmo - for: 9110.439167usdx - log: 
height: 23458 - time: 2021-12-17T08:07:27Z - kava15vkstzpueykxaprm84sra7ejtp6g6ep58z6dpt - what: 43361.556477swp - for: 59392.206427usdx - log: 
height: 23462 - time: 2021-12-17T08:07:48Z - kava15vkstzpueykxaprm84sra7ejtp6g6ep58z6dpt - what: 16660.0kava - for: 72688.2599usdx - log: 
height: 23468 - time: 2021-12-17T08:08:18Z - kava15vkstzpueykxaprm84sra7ejtp6g6ep58z6dpt - what: 80000.0hard - for: 65107.604248usdx - log: 
```
##### 3 similarity: same game strategy
```
height: 21084 - time: 2021-12-17T04:48:52Z - hard-borrow - kava1a4aap0glvcww5fw4ypfvsd80ta0cksl0vu9qkl - what: 150000.0usdx 
height: 21089 - time: 2021-12-17T04:49:17Z - hard-deposit - kava1a4aap0glvcww5fw4ypfvsd80ta0cksl0vu9qkl - what: 150000.0usdx 
height: 21094 - time: 2021-12-17T04:49:42Z - hard-borrow - kava1a4aap0glvcww5fw4ypfvsd80ta0cksl0vu9qkl - what: 150000.0usdx 
height: 21097 - time: 2021-12-17T04:49:57Z - hard-deposit - kava1a4aap0glvcww5fw4ypfvsd80ta0cksl0vu9qkl - what: 150000.0usdx 
height: 21108 - time: 2021-12-17T04:50:52Z - hard-borrow - kava1a4aap0glvcww5fw4ypfvsd80ta0cksl0vu9qkl - what: 50000.0usdx 
height: 21112 - time: 2021-12-17T04:51:12Z - hard-deposit - kava1a4aap0glvcww5fw4ypfvsd80ta0cksl0vu9qkl - what: 50000.0usdx 
height: 21119 - time: 2021-12-17T04:51:47Z - hard-borrow - kava1a4aap0glvcww5fw4ypfvsd80ta0cksl0vu9qkl - what: 100000.0usdx 
height: 21122 - time: 2021-12-17T04:52:03Z - hard-deposit - kava1a4aap0glvcww5fw4ypfvsd80ta0cksl0vu9qkl - what: 100000.0usdx 
height: 21127 - time: 2021-12-17T04:52:28Z - hard-borrow - kava1a4aap0glvcww5fw4ypfvsd80ta0cksl0vu9qkl - what: 100000.0usdx 
height: 21130 - time: 2021-12-17T04:52:43Z - hard-deposit - kava1a4aap0glvcww5fw4ypfvsd80ta0cksl0vu9qkl - what: 100000.0usdx 
height: 21141 - time: 2021-12-17T04:53:38Z - hard-borrow - kava1a4aap0glvcww5fw4ypfvsd80ta0cksl0vu9qkl - what: 80000.0usdx 

height: 22988 - time: 2021-12-17T07:28:08Z - hard-borrow - kava1dl6pgkgp0849863zu86jldhm3fe37ut299k4ga - what: 193552.0usdx 
height: 22991 - time: 2021-12-17T07:28:23Z - hard-deposit - kava1dl6pgkgp0849863zu86jldhm3fe37ut299k4ga - what: 193552.0usdx 
height: 22995 - time: 2021-12-17T07:28:43Z - hard-borrow - kava1dl6pgkgp0849863zu86jldhm3fe37ut299k4ga - what: 154842.0usdx 
height: 22998 - time: 2021-12-17T07:28:58Z - hard-deposit - kava1dl6pgkgp0849863zu86jldhm3fe37ut299k4ga - what: 154842.0usdx 
height: 23002 - time: 2021-12-17T07:29:18Z - hard-borrow - kava1dl6pgkgp0849863zu86jldhm3fe37ut299k4ga - what: 123873.0usdx 
height: 23005 - time: 2021-12-17T07:29:33Z - hard-deposit - kava1dl6pgkgp0849863zu86jldhm3fe37ut299k4ga - what: 123873.0usdx 

height: 23591 - time: 2021-12-17T08:18:35Z - hard-borrow - kava15vkstzpueykxaprm84sra7ejtp6g6ep58z6dpt - what: 185000.0usdx 
height: 23598 - time: 2021-12-17T08:19:10Z - hard-deposit - kava15vkstzpueykxaprm84sra7ejtp6g6ep58z6dpt - what: 185000.0usdx 
height: 23607 - time: 2021-12-17T08:19:55Z - hard-borrow - kava15vkstzpueykxaprm84sra7ejtp6g6ep58z6dpt - what: 148779.0usdx 
height: 23615 - time: 2021-12-17T08:20:35Z - hard-deposit - kava15vkstzpueykxaprm84sra7ejtp6g6ep58z6dpt - what: 148779.0usdx 
height: 23620 - time: 2021-12-17T08:21:01Z - hard-borrow - kava15vkstzpueykxaprm84sra7ejtp6g6ep58z6dpt - what: 119023.0usdx 
height: 23624 - time: 2021-12-17T08:21:21Z - hard-deposit - kava15vkstzpueykxaprm84sra7ejtp6g6ep58z6dpt - what: 119023.0usdx 
height: 23637 - time: 2021-12-17T08:22:26Z - hard-borrow - kava15vkstzpueykxaprm84sra7ejtp6g6ep58z6dpt - what: 95218.0usdx 

height: 24748 - time: 2021-12-17T09:55:22Z - hard-borrow - kava1ueu592zmh5aqmnt9aqddglvwuvwg0krjml0r2n - what: 194314.0usdx 
height: 24751 - time: 2021-12-17T09:55:37Z - hard-deposit - kava1ueu592zmh5aqmnt9aqddglvwuvwg0krjml0r2n - what: 194314.0usdx 
height: 24754 - time: 2021-12-17T09:55:52Z - hard-borrow - kava1ueu592zmh5aqmnt9aqddglvwuvwg0krjml0r2n - what: 155451.0usdx 
height: 24757 - time: 2021-12-17T09:56:07Z - hard-deposit - kava1ueu592zmh5aqmnt9aqddglvwuvwg0krjml0r2n - what: 155451.0usdx 
height: 24762 - time: 2021-12-17T09:56:32Z - hard-borrow - kava1ueu592zmh5aqmnt9aqddglvwuvwg0krjml0r2n - what: 124361.0usdx 
height: 24766 - time: 2021-12-17T09:56:52Z - hard-deposit - kava1ueu592zmh5aqmnt9aqddglvwuvwg0krjml0r2n - what: 124361.0usdx 

height: 24401 - time: 2021-12-17T09:26:20Z - hard-deposit - kava1lueh9u37pcjktccg7kd3yj5jl2vwqax4565w67 - what: 262868.831581usdx 
height: 24404 - time: 2021-12-17T09:26:35Z - hard-borrow - kava1lueh9u37pcjktccg7kd3yj5jl2vwqax4565w67 - what: 212561.0usdx 
height: 24407 - time: 2021-12-17T09:26:51Z - hard-deposit - kava1lueh9u37pcjktccg7kd3yj5jl2vwqax4565w67 - what: 212561.0usdx 
height: 24412 - time: 2021-12-17T09:27:16Z - hard-borrow - kava1lueh9u37pcjktccg7kd3yj5jl2vwqax4565w67 - what: 377.88739luna 
height: 24415 - time: 2021-12-17T09:27:31Z - hard-deposit - kava1lueh9u37pcjktccg7kd3yj5jl2vwqax4565w67 - what: 377.88739luna 
height: 24419 - time: 2021-12-17T09:27:51Z - hard-borrow - kava1lueh9u37pcjktccg7kd3yj5jl2vwqax4565w67 - what: 161546.0usdx 
height: 24422 - time: 2021-12-17T09:28:06Z - hard-deposit - kava1lueh9u37pcjktccg7kd3yj5jl2vwqax4565w67 - what: 161546.0usdx 
height: 24426 - time: 2021-12-17T09:28:26Z - hard-borrow - kava1lueh9u37pcjktccg7kd3yj5jl2vwqax4565w67 - what: 129237.0usdx 
height: 24430 - time: 2021-12-17T09:28:46Z - hard-deposit - kava1lueh9u37pcjktccg7kd3yj5jl2vwqax4565w67 - what: 129237.0usdx 
height: 24436 - time: 2021-12-17T09:29:16Z - hard-borrow - kava1lueh9u37pcjktccg7kd3yj5jl2vwqax4565w67 - what: 103389.0usdx 
height: 24439 - time: 2021-12-17T09:29:31Z - hard-deposit - kava1lueh9u37pcjktccg7kd3yj5jl2vwqax4565w67 - what: 103389.0usdx 
```
##### 4 similarity: no overlapping, close timing
9qkl ~ 02:06 - 02:09

k4ga ~ 02:35 - 02:37

6dpt ~ 02:53 - 02:55

5w67 ~ 03:30 - 03:33

0r2n ~ 03:42 - 03:43

The only txs for this day
```
height: 156867 - time: 2021-12-25T02:06:19Z - swap-withdraw - kava1a4aap0glvcww5fw4ypfvsd80ta0cksl0vu9qkl - what: 223.486271hard 201.456225usdx 
height: 156875 - time: 2021-12-25T02:06:59Z - hard-borrow - kava1a4aap0glvcww5fw4ypfvsd80ta0cksl0vu9qkl - what: 1511.0usdx 
height: 156880 - time: 2021-12-25T02:07:24Z - hard-deposit - kava1a4aap0glvcww5fw4ypfvsd80ta0cksl0vu9qkl - what: 1714.0usdx 
height: 156886 - time: 2021-12-25T02:07:54Z - hard-borrow - kava1a4aap0glvcww5fw4ypfvsd80ta0cksl0vu9qkl - what: 39.0atom 
height: 156889 - time: 2021-12-25T02:08:09Z - hard-deposit - kava1a4aap0glvcww5fw4ypfvsd80ta0cksl0vu9qkl - what: 46.0atom 
height: 156909 - time: 2021-12-25T02:09:50Z - cdp-withdraw - kava1a4aap0glvcww5fw4ypfvsd80ta0cksl0vu9qkl - what: 9.0atom 

height: 157220 - time: 2021-12-25T02:35:50Z - swap-withdraw - kava1dl6pgkgp0849863zu86jldhm3fe37ut299k4ga - what: 23.619014swp 39.365973usdx 
height: 157235 - time: 2021-12-25T02:37:05Z - cdp-withdraw - kava1dl6pgkgp0849863zu86jldhm3fe37ut299k4ga - what: 40.0hard 

height: 157431 - time: 2021-12-25T02:53:29Z - cdp-withdraw - kava15vkstzpueykxaprm84sra7ejtp6g6ep58z6dpt - what: 9.0akt 
height: 157437 - time: 2021-12-25T02:53:59Z - hard-deposit - kava15vkstzpueykxaprm84sra7ejtp6g6ep58z6dpt - what: 117.818182usdx 
height: 157440 - time: 2021-12-25T02:54:14Z - hard-borrow - kava15vkstzpueykxaprm84sra7ejtp6g6ep58z6dpt - what: 8.0atom 
height: 157444 - time: 2021-12-25T02:54:34Z - hard-borrow - kava15vkstzpueykxaprm84sra7ejtp6g6ep58z6dpt - what: 10.0akt 
height: 157452 - time: 2021-12-25T02:55:14Z - swap-withdraw - kava15vkstzpueykxaprm84sra7ejtp6g6ep58z6dpt - what: 0.903514kava 4.21991usdx 

height: 157877 - time: 2021-12-25T03:30:47Z - swap-withdraw - kava1lueh9u37pcjktccg7kd3yj5jl2vwqax4565w67 - what: 0.297995kava 1.42182usdx 
height: 157884 - time: 2021-12-25T03:31:23Z - hard-deposit - kava1lueh9u37pcjktccg7kd3yj5jl2vwqax4565w67 - what: 1.436183usdx 
height: 157891 - time: 2021-12-25T03:31:58Z - hard-borrow - kava1lueh9u37pcjktccg7kd3yj5jl2vwqax4565w67 - what: 460.0usdx 
height: 157910 - time: 2021-12-25T03:33:33Z - cdp-withdraw - kava1lueh9u37pcjktccg7kd3yj5jl2vwqax4565w67 - what: 5.0hard 

height: 158013 - time: 2021-12-25T03:42:10Z - swap-withdraw - kava1ueu592zmh5aqmnt9aqddglvwuvwg0krjml0r2n - what: 199.398941swp 332.314844usdx 
height: 158024 - time: 2021-12-25T03:43:05Z - hard-borrow - kava1ueu592zmh5aqmnt9aqddglvwuvwg0krjml0r2n - what: 3499.0usdx 
height: 158032 - time: 2021-12-25T03:43:45Z - hard-deposit - kava1ueu592zmh5aqmnt9aqddglvwuvwg0krjml0r2n - what: 3834.67156usdx 
```
9qkl ~ 02:39 - 02:39

k4ga ~ 02:59 - 02:59

6dpt ~ 03:15 - 03:16

5w67 ~ 03:39 - 03:40

0r2n ~ 03:49 - 03:52

The only txs for this day
```
height: 174475 - time: 2021-12-26T02:39:00Z - swap-withdraw - kava1a4aap0glvcww5fw4ypfvsd80ta0cksl0vu9qkl - what: 40.201662hard 36.311837usdx 
height: 174479 - time: 2021-12-26T02:39:20Z - hard-borrow - kava1a4aap0glvcww5fw4ypfvsd80ta0cksl0vu9qkl - what: 700.0usdx 
height: 174483 - time: 2021-12-26T02:39:40Z - cdp-withdraw - kava1a4aap0glvcww5fw4ypfvsd80ta0cksl0vu9qkl - what: 10.0atom 

height: 174716 - time: 2021-12-26T02:59:09Z - swap-withdraw - kava1dl6pgkgp0849863zu86jldhm3fe37ut299k4ga - what: 1.95734swp 3.855099usdx 
height: 174723 - time: 2021-12-26T02:59:45Z - cdp-withdraw - kava1dl6pgkgp0849863zu86jldhm3fe37ut299k4ga - what: 1.0hard 

height: 174916 - time: 2021-12-26T03:15:53Z - swap-withdraw - kava15vkstzpueykxaprm84sra7ejtp6g6ep58z6dpt - what: 0.159873kava 0.77314usdx 
height: 174924 - time: 2021-12-26T03:16:33Z - cdp-withdraw - kava15vkstzpueykxaprm84sra7ejtp6g6ep58z6dpt - what: 5.0akt 

height: 175200 - time: 2021-12-26T03:39:38Z - swap-withdraw - kava1lueh9u37pcjktccg7kd3yj5jl2vwqax4565w67 - what: 0.053294kava 0.257728usdx 
height: 175204 - time: 2021-12-26T03:39:58Z - hard-deposit - kava1lueh9u37pcjktccg7kd3yj5jl2vwqax4565w67 - what: 460.260333usdx 
height: 175212 - time: 2021-12-26T03:40:39Z - cdp-withdraw - kava1lueh9u37pcjktccg7kd3yj5jl2vwqax4565w67 - what: 5.0hard 

height: 175314 - time: 2021-12-26T03:49:10Z - swap-withdraw - kava1ueu592zmh5aqmnt9aqddglvwuvwg0krjml0r2n - what: 34.985747swp 61.497257usdx 
height: 175336 - time: 2021-12-26T03:51:01Z - hard-deposit - kava1ueu592zmh5aqmnt9aqddglvwuvwg0krjml0r2n - what: 62.118442usdx 
height: 175352 - time: 2021-12-26T03:52:21Z - cdp-withdraw - kava1ueu592zmh5aqmnt9aqddglvwuvwg0krjml0r2n - what: 5.0hard 
```
9qkl ~ 02:16 - 02:17

k4ga ~ 02:36 - 02:37

6dpt ~ 02:52 - 02:53

5w67 ~ 03:09 - 03:10

0r2n ~ 03:17 - 03:18

The only txs for this day
```
height: 191425 - time: 2021-12-27T02:16:40Z - swap-withdraw - kava1a4aap0glvcww5fw4ypfvsd80ta0cksl0vu9qkl - what: 40.385888hard 34.731003usdx 
height: 191430 - time: 2021-12-27T02:17:05Z - hard-deposit - kava1a4aap0glvcww5fw4ypfvsd80ta0cksl0vu9qkl - what: 772.251583usdx 
height: 191434 - time: 2021-12-27T02:17:25Z - cdp-withdraw - kava1a4aap0glvcww5fw4ypfvsd80ta0cksl0vu9qkl - what: 5.0atom 

height: 191664 - time: 2021-12-27T02:36:39Z - swap-withdraw - kava1dl6pgkgp0849863zu86jldhm3fe37ut299k4ga - what: 4.271341swp 6.933969usdx 
height: 191671 - time: 2021-12-27T02:37:14Z - cdp-withdraw - kava1dl6pgkgp0849863zu86jldhm3fe37ut299k4ga - what: 4.0hard 

height: 191845 - time: 2021-12-27T02:51:48Z - swap-withdraw - kava15vkstzpueykxaprm84sra7ejtp6g6ep58z6dpt - what: 0.158649kava 0.748302usdx 
height: 191861 - time: 2021-12-27T02:53:08Z - cdp-withdraw - kava15vkstzpueykxaprm84sra7ejtp6g6ep58z6dpt - what: 2.0akt 

height: 192058 - time: 2021-12-27T03:09:36Z - swap-withdraw - kava1lueh9u37pcjktccg7kd3yj5jl2vwqax4565w67 - what: 0.052803kava 0.249839usdx 
height: 192064 - time: 2021-12-27T03:10:07Z - hard-borrow - kava1lueh9u37pcjktccg7kd3yj5jl2vwqax4565w67 - what: 161.0usdx 
height: 192069 - time: 2021-12-27T03:10:32Z - cdp-withdraw - kava1lueh9u37pcjktccg7kd3yj5jl2vwqax4565w67 - what: 5.0hard 

height: 192153 - time: 2021-12-27T03:17:33Z - swap-withdraw - kava1ueu592zmh5aqmnt9aqddglvwuvwg0krjml0r2n - what: 35.270154swp 58.643358usdx 
height: 192157 - time: 2021-12-27T03:17:53Z - hard-deposit - kava1ueu592zmh5aqmnt9aqddglvwuvwg0krjml0r2n - what: 59.235715usdx 
height: 192161 - time: 2021-12-27T03:18:13Z - cdp-withdraw - kava1ueu592zmh5aqmnt9aqddglvwuvwg0krjml0r2n - what: 4.0hard 
height: 192168 - time: 2021-12-27T03:18:48Z - hard-borrow - kava1ueu592zmh5aqmnt9aqddglvwuvwg0krjml0r2n - what: 2977.0usdx 
```
9qkl ~ 03:05 - 03:08

k4ga ~ 03:20 - 03:20

6dpt ~ 03:20 - 03:24

5w67 ~ 03:36 - 03:43

0r2n ~ 03:44 - 03:46

The only txs for this day
```
height: 209225 - time: 2021-12-28T03:05:27Z - hard-borrow - kava1a4aap0glvcww5fw4ypfvsd80ta0cksl0vu9qkl - what: 250.0usdx 
height: 209237 - time: 2021-12-28T03:06:27Z - cdp-repay - kava1a4aap0glvcww5fw4ypfvsd80ta0cksl0vu9qkl - atom-a - what: 50.0usdx 
height: 209241 - time: 2021-12-28T03:06:48Z - hard-deposit - kava1a4aap0glvcww5fw4ypfvsd80ta0cksl0vu9qkl - what: 50.0usdx 
height: 209247 - time: 2021-12-28T03:07:18Z - swap-withdraw - kava1a4aap0glvcww5fw4ypfvsd80ta0cksl0vu9qkl - what: 396.130238hard 340.199332usdx 
height: 209253 - time: 2021-12-28T03:07:48Z - swap-deposit - kava1a4aap0glvcww5fw4ypfvsd80ta0cksl0vu9qkl - what: 100.0hard 85.880678usdx
height: 209261 - time: 2021-12-28T03:08:28Z - hard-deposit - kava1a4aap0glvcww5fw4ypfvsd80ta0cksl0vu9qkl - what: 607.276829hard 

# this is the only case of overlapping I've came across with these accounts: k4ga completes the transaction later than 6dpt
# I admit that this example breaks the logic, yet this is the only tx for k4ga on that day and there is a possibility it was initiated earlier and took longer to process
height: 209404 - time: 2021-12-28T03:20:25Z - swap-withdraw - kava1dl6pgkgp0849863zu86jldhm3fe37ut299k4ga - what: 184.186772swp 313.063488usdx 

height: 209399 - time: 2021-12-28T03:20:00Z - swap-withdraw - kava15vkstzpueykxaprm84sra7ejtp6g6ep58z6dpt - what: 6.915753kava 33.401472usdx 
height: 209410 - time: 2021-12-28T03:20:56Z - kava15vkstzpueykxaprm84sra7ejtp6g6ep58z6dpt - what: 3.0kava - for: 14.467535usdx - log: 
height: 209419 - time: 2021-12-28T03:21:41Z - cdp-borrow - kava15vkstzpueykxaprm84sra7ejtp6g6ep58z6dpt - what: 65.0usdx 
height: 209438 - time: 2021-12-28T03:23:16Z - kava15vkstzpueykxaprm84sra7ejtp6g6ep58z6dpt - what: 5.0atom - for: 117.759969usdx - log: 
height: 209447 - time: 2021-12-28T03:24:01Z - hard-deposit - kava15vkstzpueykxaprm84sra7ejtp6g6ep58z6dpt - what: 20.0usdx 

height: 209599 - time: 2021-12-28T03:36:44Z - cdp-borrow - kava1lueh9u37pcjktccg7kd3yj5jl2vwqax4565w67 - what: 15.0usdx 
height: 209605 - time: 2021-12-28T03:37:14Z - swap-deposit - kava1lueh9u37pcjktccg7kd3yj5jl2vwqax4565w67 - what: 15.0hard 12.88484usdx
height: 209682 - time: 2021-12-28T03:43:41Z - hard-deposit - kava1lueh9u37pcjktccg7kd3yj5jl2vwqax4565w67 - what: 11.0usdx 

height: 209697 - time: 2021-12-28T03:44:56Z - hard-deposit - kava1ueu592zmh5aqmnt9aqddglvwuvwg0krjml0r2n - what: 2000.0usdx 
height: 209700 - time: 2021-12-28T03:45:11Z - hard-deposit - kava1ueu592zmh5aqmnt9aqddglvwuvwg0krjml0r2n - what: 10.0hard 
height: 209704 - time: 2021-12-28T03:45:31Z - hard-borrow - kava1ueu592zmh5aqmnt9aqddglvwuvwg0krjml0r2n - what: 1000.0hard 
height: 209715 - time: 2021-12-28T03:46:26Z - swap-deposit - kava1ueu592zmh5aqmnt9aqddglvwuvwg0krjml0r2n - what: 777.0hard 667.434688usdx
```
##### 5 similarity: pattern

###### point 1: all accounts follow each other in the same order every day starting from Dec 24 (or even earlier), see the order in the examples above

###### point 2: 
If we look closely at the players' activity from the last days (check all in similarity 4), they have the same weird pattern

I'd say there is close to 0 possibility that 2 players among 700 would be following this strange pattern of withdrawing from swap and cdp at almost the same time without doing anything specific, but these strange transactions

What makes me believe they are all interconnected is this pattern of 0 sense transactions which look more like simulating some activity. While I understand that akt\atom might be used for IBC transactions, there's no logic to withdraw 5 hard or playing with small amounts. It's better to compare the logs 1-to-1 to get this sense that something is wrong about these accounts
```
height: 174716 - time: 2021-12-26T02:59:09Z - swap-withdraw - kava1dl6pgkgp0849863zu86jldhm3fe37ut299k4ga - what: 1.95734swp 3.855099usdx 
height: 174723 - time: 2021-12-26T02:59:45Z - cdp-withdraw - kava1dl6pgkgp0849863zu86jldhm3fe37ut299k4ga - what: 1.0hard 

height: 191425 - time: 2021-12-27T02:16:40Z - swap-withdraw - kava1a4aap0glvcww5fw4ypfvsd80ta0cksl0vu9qkl - what: 40.385888hard 34.731003usdx 
height: 191430 - time: 2021-12-27T02:17:05Z - hard-deposit - kava1a4aap0glvcww5fw4ypfvsd80ta0cksl0vu9qkl - what: 772.251583usdx 
height: 191434 - time: 2021-12-27T02:17:25Z - cdp-withdraw - kava1a4aap0glvcww5fw4ypfvsd80ta0cksl0vu9qkl - what: 5.0atom 

height: 174916 - time: 2021-12-26T03:15:53Z - swap-withdraw - kava15vkstzpueykxaprm84sra7ejtp6g6ep58z6dpt - what: 0.159873kava 0.77314usdx 
height: 174924 - time: 2021-12-26T03:16:33Z - cdp-withdraw - kava15vkstzpueykxaprm84sra7ejtp6g6ep58z6dpt - what: 5.0akt 

height: 175200 - time: 2021-12-26T03:39:38Z - swap-withdraw - kava1lueh9u37pcjktccg7kd3yj5jl2vwqax4565w67 - what: 0.053294kava 0.257728usdx 
height: 175204 - time: 2021-12-26T03:39:58Z - hard-deposit - kava1lueh9u37pcjktccg7kd3yj5jl2vwqax4565w67 - what: 460.260333usdx 
height: 175212 - time: 2021-12-26T03:40:39Z - cdp-withdraw - kava1lueh9u37pcjktccg7kd3yj5jl2vwqax4565w67 - what: 5.0hard 

height: 175314 - time: 2021-12-26T03:49:10Z - swap-withdraw - kava1ueu592zmh5aqmnt9aqddglvwuvwg0krjml0r2n - what: 34.985747swp 61.497257usdx 
height: 175336 - time: 2021-12-26T03:51:01Z - hard-deposit - kava1ueu592zmh5aqmnt9aqddglvwuvwg0krjml0r2n - what: 62.118442usdx 
height: 175352 - time: 2021-12-26T03:52:21Z - cdp-withdraw - kava1ueu592zmh5aqmnt9aqddglvwuvwg0krjml0r2n - what: 5.0hard 
```

##### Possible relations
I have identified many accounts with similar behaviour, but it's time consuming to compare everything. I provide suspicious accounts below for additional investigation

What all those accounts share in common:
- low tx count, low swap tx count
- selling all for usdx from the start
- doing sensless transactions as if they are simulating activity

**kava1tjrhqzsanpmqvkvxrlevt9esee4xw2w6j98vt4 (pos 31)**
+ 193 txs, 24 swap txs
```
height: 193366 - time: 2021-12-27T04:59:00Z - swap-withdraw - kava1tjrhqzsanpmqvkvxrlevt9esee4xw2w6j98vt4 - what: 0.287878hard 0.241043usdx 
height: 193372 - time: 2021-12-27T04:59:31Z - hard-deposit - kava1tjrhqzsanpmqvkvxrlevt9esee4xw2w6j98vt4 - what: 198.896426usdx 
height: 208006 - time: 2021-12-28T01:23:30Z - swap-withdraw - kava1tjrhqzsanpmqvkvxrlevt9esee4xw2w6j98vt4 - what: 1.380594hard 1.2072usdx 
height: 208022 - time: 2021-12-28T01:24:50Z - swap-deposit - kava1tjrhqzsanpmqvkvxrlevt9esee4xw2w6j98vt4 - what: 0.966292kava 4.711757usdx
height: 208036 - time: 2021-12-28T01:26:00Z - cdp-withdraw - kava1tjrhqzsanpmqvkvxrlevt9esee4xw2w6j98vt4 - what: 1.0kava 
```
**kava1zfgmdes6rmq6ynrrml9fpxmtrfds5k3vvwkkh2 (pos 29)**
+ 177 txs, 24 swap txs
```
height: 194790 - time: 2021-12-27T06:58:07Z - swap-withdraw - kava1zfgmdes6rmq6ynrrml9fpxmtrfds5k3vvwkkh2 - what: 0.019686akt 0.060209usdx 
height: 194795 - time: 2021-12-27T06:58:32Z - hard-deposit - kava1zfgmdes6rmq6ynrrml9fpxmtrfds5k3vvwkkh2 - what: 68.556518usdx 
height: 194800 - time: 2021-12-27T06:58:57Z - cdp-withdraw - kava1zfgmdes6rmq6ynrrml9fpxmtrfds5k3vvwkkh2 - what: 0.4swp 
height: 208478 - time: 2021-12-28T02:02:58Z - cdp-withdraw - kava1zfgmdes6rmq6ynrrml9fpxmtrfds5k3vvwkkh2 - what: 3.0swp 
height: 208490 - time: 2021-12-28T02:03:59Z - swap-withdraw - kava1zfgmdes6rmq6ynrrml9fpxmtrfds5k3vvwkkh2 - what: 203.748963hard 178.076433usdx 
height: 208499 - time: 2021-12-28T02:04:44Z - swap-deposit - kava1zfgmdes6rmq6ynrrml9fpxmtrfds5k3vvwkkh2 - what: 1.0akt 2.982069usdx
height: 208515 - time: 2021-12-28T02:06:04Z - cdp-repay - kava1zfgmdes6rmq6ynrrml9fpxmtrfds5k3vvwkkh2 - swp-a - what: 1.0usdx 
height: 208519 - time: 2021-12-28T02:06:24Z - hard-withdraw - kava1zfgmdes6rmq6ynrrml9fpxmtrfds5k3vvwkkh2 - what: 26.0kava 
height: 208529 - time: 2021-12-28T02:07:14Z - hard-deposit - kava1zfgmdes6rmq6ynrrml9fpxmtrfds5k3vvwkkh2 - what: 481.91371usdx 
height: 208533 - time: 2021-12-28T02:07:34Z - hard-borrow - kava1zfgmdes6rmq6ynrrml9fpxmtrfds5k3vvwkkh2 - what: 17.0luna 
height: 208543 - time: 2021-12-28T02:08:25Z - hard-deposit - kava1zfgmdes6rmq6ynrrml9fpxmtrfds5k3vvwkkh2 - what: 658.635602usdx 
height: 208553 - time: 2021-12-28T02:09:15Z - hard-borrow - kava1zfgmdes6rmq6ynrrml9fpxmtrfds5k3vvwkkh2 - what: 12.0luna 
height: 208562 - time: 2021-12-28T02:10:00Z - hard-deposit - kava1zfgmdes6rmq6ynrrml9fpxmtrfds5k3vvwkkh2 - what: 329.18295usdx 
height: 208567 - time: 2021-12-28T02:10:25Z - hard-borrow - kava1zfgmdes6rmq6ynrrml9fpxmtrfds5k3vvwkkh2 - what: 6.0luna 
height: 208585 - time: 2021-12-28T02:11:55Z - swap-deposit - kava1zfgmdes6rmq6ynrrml9fpxmtrfds5k3vvwkkh2 - what: 9.0osmo 45.671735usdx
height: 208594 - time: 2021-12-28T02:12:41Z - swap-deposit - kava1zfgmdes6rmq6ynrrml9fpxmtrfds5k3vvwkkh2 - what: 6.000001akt 17.892404usdx
```
**kava18jnqe0r25utgqjwapwaydzr7wddeta6j9322pt (pos 34)**
+ 126 txs, 12 swap txs
```
height: 192992 - time: 2021-12-27T04:27:44Z - swap-withdraw - kava18jnqe0r25utgqjwapwaydzr7wddeta6j9322pt - what: 46.804714hard 39.141978usdx 
height: 192996 - time: 2021-12-27T04:28:04Z - hard-deposit - kava18jnqe0r25utgqjwapwaydzr7wddeta6j9322pt - what: 284.285015usdx 
height: 193000 - time: 2021-12-27T04:28:24Z - cdp-withdraw - kava18jnqe0r25utgqjwapwaydzr7wddeta6j9322pt - what: 0.7kava 
height: 193104 - time: 2021-12-27T04:37:06Z - swap-withdraw - kava18jnqe0r25utgqjwapwaydzr7wddeta6j9322pt - what: 45.86862hard 38.359138usdx 
height: 193107 - time: 2021-12-27T04:37:21Z - hard-deposit - kava18jnqe0r25utgqjwapwaydzr7wddeta6j9322pt - what: 38.746605usdx 
height: 193110 - time: 2021-12-27T04:37:36Z - cdp-withdraw - kava18jnqe0r25utgqjwapwaydzr7wddeta6j9322pt - what: 0.5kava 
# what for does he need 0.7 kava and 10 minutes later 0.5 kava? what will it change for a normal player?
```
**kava1kdnvc2dmeqatv4fmemfy8q7whl9vjta68fkr8m (pos 36)**
+ 172 txs, 14 swap txs
```
height: 192693 - time: 2021-12-27T04:02:43Z - swap-withdraw - kava1kdnvc2dmeqatv4fmemfy8q7whl9vjta68fkr8m - what: 0.103014kava 0.494153usdx 
height: 192699 - time: 2021-12-27T04:03:13Z - cdp-withdraw - kava1kdnvc2dmeqatv4fmemfy8q7whl9vjta68fkr8m - what: 0.01kava 
height: 208211 - time: 2021-12-28T01:40:38Z - swap-withdraw - kava1kdnvc2dmeqatv4fmemfy8q7whl9vjta68fkr8m - what: 278.013302hard 243.06839usdx 
height: 225433 - time: 2021-12-29T01:41:06Z - hard-deposit - kava1kdnvc2dmeqatv4fmemfy8q7whl9vjta68fkr8m - what: 50.0hard 
height: 225438 - time: 2021-12-29T01:41:31Z - swap-deposit - kava1kdnvc2dmeqatv4fmemfy8q7whl9vjta68fkr8m - what: 50.821518hard 42.310284usdx
# why does he withdraw low amounts?
```
**kava14mysv209yv0gcvu0dmth98uq04zzy7c0j0k5nv (pos 40)**
+ 125 txs, 16 swap txs
```
height: 192814 - time: 2021-12-27T04:12:50Z - swap-withdraw - kava14mysv209yv0gcvu0dmth98uq04zzy7c0j0k5nv - what: 11.216193hard 9.379578usdx 
height: 192817 - time: 2021-12-27T04:13:05Z - hard-deposit - kava14mysv209yv0gcvu0dmth98uq04zzy7c0j0k5nv - what: 78.633131usdx 
height: 192824 - time: 2021-12-27T04:13:40Z - cdp-withdraw - kava14mysv209yv0gcvu0dmth98uq04zzy7c0j0k5nv - what: 0.3hard 
height: 208216 - time: 2021-12-28T01:41:04Z - swap-withdraw - kava14mysv209yv0gcvu0dmth98uq04zzy7c0j0k5nv - what: 96.766875hard 84.603752usdx 
height: 208250 - time: 2021-12-28T01:43:54Z - hard-deposit - kava14mysv209yv0gcvu0dmth98uq04zzy7c0j0k5nv - what: 30.268054hard 
height: 225530 - time: 2021-12-29T01:49:12Z - hard-deposit - kava14mysv209yv0gcvu0dmth98uq04zzy7c0j0k5nv - what: 22.0usdx 
height: 225539 - time: 2021-12-29T01:49:58Z - cdp-repay - kava14mysv209yv0gcvu0dmth98uq04zzy7c0j0k5nv - hard-a - what: 30.0usdx 
height: 225543 - time: 2021-12-29T01:50:18Z - swap-withdraw - kava14mysv209yv0gcvu0dmth98uq04zzy7c0j0k5nv - what: 45.474815hard 37.452339usdx 
```
**kava19wugvjdd6nl767y4vvqpv2wrtf0uhrmk4uqlmm (pos 51)**
+ 165 txs, 18 swap txs
```
height: 194279 - time: 2021-12-27T06:15:22Z - swap-withdraw - kava19wugvjdd6nl767y4vvqpv2wrtf0uhrmk4uqlmm - what: 2.157227hard 1.793475usdx 
height: 194282 - time: 2021-12-27T06:15:37Z - hard-deposit - kava19wugvjdd6nl767y4vvqpv2wrtf0uhrmk4uqlmm - what: 102.450264usdx 
height: 194286 - time: 2021-12-27T06:15:57Z - cdp-withdraw - kava19wugvjdd6nl767y4vvqpv2wrtf0uhrmk4uqlmm - what: 2.0hard 
height: 208300 - time: 2021-12-28T01:48:05Z - cdp-withdraw - kava19wugvjdd6nl767y4vvqpv2wrtf0uhrmk4uqlmm - what: 8.0hard 
height: 208314 - time: 2021-12-28T01:49:15Z - cdp-withdraw - kava19wugvjdd6nl767y4vvqpv2wrtf0uhrmk4uqlmm - what: 10.0hard 
height: 208317 - time: 2021-12-28T01:49:30Z - cdp-repay - kava19wugvjdd6nl767y4vvqpv2wrtf0uhrmk4uqlmm - hard-a - what: 1.0usdx 
height: 208326 - time: 2021-12-28T01:50:16Z - hard-borrow - kava19wugvjdd6nl767y4vvqpv2wrtf0uhrmk4uqlmm - what: 8.0luna 
height: 208334 - time: 2021-12-28T01:50:56Z - hard-deposit - kava19wugvjdd6nl767y4vvqpv2wrtf0uhrmk4uqlmm - what: 339.904594usdx 
height: 208341 - time: 2021-12-28T01:51:31Z - hard-borrow - kava19wugvjdd6nl767y4vvqpv2wrtf0uhrmk4uqlmm - what: 6.0luna 
height: 208352 - time: 2021-12-28T01:52:26Z - swap-deposit - kava19wugvjdd6nl767y4vvqpv2wrtf0uhrmk4uqlmm - what: 10.0hard 8.741547usdx
height: 208359 - time: 2021-12-28T01:53:01Z - hard-deposit - kava19wugvjdd6nl767y4vvqpv2wrtf0uhrmk4uqlmm - what: 170.914554usdx 
height: 208363 - time: 2021-12-28T01:53:21Z - hard-borrow - kava19wugvjdd6nl767y4vvqpv2wrtf0uhrmk4uqlmm - what: 3.0luna 
# why did he borrow 6 luna and then again 3 luna?
```
