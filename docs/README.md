# Haskell and Cryptocurrencies

![Haskell Logo](https://upload.wikimedia.org/wikipedia/commons/1/1c/Haskell-Logo.svg)

- Lectures: TODO: Insert lecture days
- **Instructors:**
  - [Lars Brünjes](https://iohk.io/en/team/lars-brunjes)
  - [Andres Löh](http://www.well-typed.com/people/andres/)
- **TA**
  - [Alejandro García](https://iohk.io/en/team/alejandro-garcia)

## Course Description

Haskell is a high-level, purely functional programming language with a
strong static type system and elegant mathematical underpinnings. It is
being increasingly used in industry by organizations such as Facebook,
AT\&T, and NASA, along with several financial firms. We will explore the
joys of functional programming, using Haskell as a vehicle. In the first
part of the course, you will learn to use Haskell to easily and
conveniently write practical programs. The last couple of weeks will
consist of several special topics that explore advanced features of
Haskell. Evaluation will be based on class participation, weekly
programming assignments, and an open-ended final project.

## Getting the Software

You will need `ghc` (the Haskell compiler; at least version 8.6.5, preferably
version 8.10.1), `cabal` (a build tool for Haskell; at least version 2.4.1,
preferably version 3.2), and a suitable development editor to edit source files
with (e.g. Visual Studio Code, or (neo)vim).

Instructions on how to install the necessary software are available [here](https://github.com/zfoh/haskell-simple-install/blob/master/README.md),
separated by platform (Linux, MacOS, Windows).

These instructions also include information on how to set up more advanced IDE-like
editor support for Visual Studio Code, in the form of `ghcide`. While this will be
helpful in the long run, it is not mandatory, and if you experience problems setting
this up, don't worry for now.

## How to get help

- Discord TODO: Insert link to the discord chat for the class
- Forum TODO: Insert link to the forum for the class
- [Haskell tag stackoverflow.com](https://stackoverflow.com/questions/tagged/haskell)
- How do I install Haskell on Windows? [video](https://drive.google.com/file/d/1vxSk3Qeb_SyCNuwvs6jpQRmM2BNrVRro/view?usp=sharing)

### Defects

If you find a defect in one of the sample programs.
Or maybe a typo in one of the slides we will really appreciate it
if you could post it as an issue on GitHub Itself.
Report defecs in: [issues](TODO Insert link to issues for this class)

## Class

|             | Lecture and slides                       | Edited Video with Captions                                                                              | Original Video |
|-------------|------------------------------------------|---------------------------------------------------------------------------------------------------------|----------------|
| Lecture 010 | [Welcome][1]                             | [youtube](https://www.youtube.com/watch?v=EoO76YCSTLo&list=PLJ3w5xyG4JWmBVIigNBytJhvSSfZZzfTm&index=1)  | [video][2]     |
|             | [Introduction to Cryptocurrencies][4]    |                                                                                                         |                |
|             | [An Overview of Haskell][5]              |                                                                                                         |                |
| Lecture 020 | [Datatypes & Functions][7]               | [youtube](https://www.youtube.com/watch?v=OnuYmTbj9pk&list=PLJ3w5xyG4JWmBVIigNBytJhvSSfZZzfTm&index=4)  | [video][8]     |
| Lecture 030 | [Polymorphism & Type Classes][11]        | [youtube](https://www.youtube.com/watch?v=GHM0OmJG7bo&list=PLJ3w5xyG4JWmBVIigNBytJhvSSfZZzfTm&index=10) | [video][12]    |
| Lecture 040 | [Higher-Order Functions][14]             | [youtube](https://www.youtube.com/watch?v=4wJ7DzOEDRY&list=PLJ3w5xyG4JWmBVIigNBytJhvSSfZZzfTm&index=12) | [video][15]    |
|             | [Packaging & Tools][18]                  |                                                                                                         |                |
| Lecture 050 | [IO][19]                                 | [youtube](https://www.youtube.com/watch?v=rCbF8nXVLlg&list=PLJ3w5xyG4JWmBVIigNBytJhvSSfZZzfTm&index=15) | [video][20]    |
| Lecture 060 | [Testing][23]                            |                                                                                                         | [video][24]    |
| Lecture 070 | [Abstraction Patterns][26]               | [youtube](https://www.youtube.com/watch?v=ykQ2KX2bDLo&list=PLJ3w5xyG4JWmBVIigNBytJhvSSfZZzfTm&index=17) | [video][27]    |
| Lecture 080 | [Concurrency][29]                        |                                                                                                         | [video][30]    |
| Lecture 090 | [Network Servers][32]                    |                                                                                                         | [video][33]    |
| Lecture 100 | [Parser Combinators][35]                 |                                                                                                         | [video][36]    |
| Lecture 110 | [More on Parsing][38]                    |                                                                                                         | [video][39]    |
| Lecture 120 | [Data Structures][41]                    |                                                                                                         | [video][42]    |
| Lecture 130 | [More on Data Structures][44]            |                                                                                                         | [video][45]    |
| Lecture 140 | [Optics][47]                             |                                                                                                         | [video][48]    |
| Lecture 150 | [More Optics][50]                        |                                                                                                         | [video][51]    |
| Lecture 160 | [More on Monads][53]                     | [youtube](https://www.youtube.com/watch?v=g0KIpgHGaEU&list=PLJ3w5xyG4JWmBVIigNBytJhvSSfZZzfTm&index=21) | [video][54]    |
| Lecture 170 | [Free Monads][56]                        |                                                                                                         | [video][57]    |
| Lecture 180 | [Streaming][59]                          |                                                                                                         | [video][60]    |
| Lecture 190 | [Embedded Domain-Specific Languages][62] |                                                                                                         | [video][63]    |
| Lecture 200 | Marlowe I                                |                                                                                                         | [video][65]    |
| Lecture 210 | Marlowe II                               |                                                                                                         | [video][67]    |
| Lecture 220 | Marlowe III                              |                                                                                                         | [video][69]    |
| Lecture 230 | Marlowe: Static Analysis & Simulator     |                                                                                                         | [video][71]    |
| Lecture 240 | Marlowe: Commodities                     |                                                                                                         | [video][73]    |
| Lecture 250 | Plutus I                                 |                                                                                                         | [video][75]    |
| Lecture 260 | Plutus II                                |                                                                                                         | [video][77]    |
| Lecture 270 | Plutus: State Machines                   |                                                                                                         | [video][79]    |
| Lecture 280 | [Template Haskell][81]                   |                                                                                                         | [video][82]    |
| Lecture 290 | Liquid Haskell & Propositions as Types   |                                                                                                         | [video][84]    |
| Lecture 300 | Servant & Persistent                     |                                                                                                         | [video][86]    |

[1]:   ../lectures/00-welcome.pdf
[2]:   https://drive.google.com/file/d/1u0xNcuoi9cLTFMenfEbNRXqe0S5sI-nj/view?usp=sharing
[3]:   https://drive.google.com/file/d/1OVoowel76o5tedNLYxxCyPN6qopGD6wK/view?usp=sharing
[4]:   ../lectures/01-intro-cryptocurrencies.pdf
[5]:   ../lectures/02-overview-haskell.pdf
[6]:   https://classroom.github.com/a/ZFu9YQF5
[7]:  ../lectures/03-datatypes-functions.pdf
[8]:   https://drive.google.com/file/d/127LklblBCX-2VsHKy3cHWeXWyhFr5lma/view?usp=sharing
[9]:   https://drive.google.com/file/d/127LklblBCX-2VsHKy3cHWeXWyhFr5lma/view?usp=sharing
[10]:  https://classroom.github.com/a/YjmNAnkP
[11]:  ../lectures/04-polymorphism-type-classes.pdf
[12]:  https://drive.google.com/file/d/11MVm_fiqpaEFavEOSXKQ6zBuSRRp5MCE/view?usp=sharing
[13]:  https://drive.google.com/file/d/1E3fRkTX5-NhUHP1YFC01Dtt2s8AYCrjL/view?usp=sharing
[14]:  ../lectures/05-higher-order-functions.pdf
[15]:  https://drive.google.com/file/d/1CzKVzIwuNVvtbZk30VOKaEb2paCxAD_r/view?usp=sharing
[16]:  https://drive.google.com/file/d/1KaWzbrCgNBXL9gUGsgYO198orrHhYtUN/view?usp=sharing
[17]:  https://classroom.github.com/a/8_VyrI5G
[18]:  ../lectures/06-packaging-and-tools.pdf
[19]:  ../lectures/07-io.pdf
[20]:  https://drive.google.com/file/d/1WuTl_Z_xvmZJv0AD0vlQYs63ja68gFfz/view?usp=sharing
[21]:  https://drive.google.com/file/d/11H2lVjCV60GXJVSt3zl5XX66QXDGHIhc/view?usp=sharing
[22]:  https://classroom.github.com/a/_eDITQUZ
[23]:  ../lectures/08-testing.pdf
[24]:  https://drive.google.com/file/d/1UXqmBjNMPuJxHbsAMTDnihdnw6IZRt73/view?usp=sharing
[25]:  https://drive.google.com/file/d/1ueiGfD0fjbLJh6nHcg33Rtb_zLAZsRyV/view?usp=sharing
[26]:  ../lectures/09-abstraction-patterns.pdf
[27]:  https://drive.google.com/file/d/1pfgRzEeioNNWM__AvQ_FPczdy08-ON0W/view?usp=sharing
[28]:  https://drive.google.com/file/d/1NS35BfBXdpFv1MSW6sP1lWPOMEqafeUr/view?usp=sharing
[29]:  ../lectures/10-concurrency.pdf
[30]:  https://drive.google.com/file/d/1r36dUeCLBZdU69CoM-OFIggicXVMEcwk/view?usp=sharing
[31]:  https://drive.google.com/file/d/1tj4964piFXiNVhFvAhJEt8VmksFKH7VR/view?usp=sharing
[32]:  ../lectures/11-servers.pdf
[33]:  https://drive.google.com/file/d/1_Po9UjEOO9TW0VUjxXgQNd1R9x-TtjB8/view?usp=sharing
[34]:  https://drive.google.com/file/d/1didVeqSJ9Z_UeX-mCvV8RS4FYsFQTRQu/view?usp=sharing
[35]:  ../lectures/12-parser-combinators.pdf
[36]:  https://drive.google.com/file/d/14PIL_2ZhROoR1QBkH5851FEP7tv0UG_z/view?usp=sharing
[37]:  https://drive.google.com/file/d/14FTpgRSN5Y5qqPXekADKG1eWGv31P7hZ/view?usp=sharing
[38]:  ../lectures/13-more-parsing.pdf
[39]:  https://drive.google.com/file/d/1dZoaL0NQHpvNqni27kD4o0cW_uUMnumK/view?usp=sharing
[40]:  https://drive.google.com/file/d/1Rm6gx2qCCTXZMKNqEtXhWnfPhsUYUXSw/view?usp=sharing
[41]:  ../lectures/14-data-structures.pdf
[42]:  https://drive.google.com/file/d/1yfLx1ZZax_2ftcDJSrUnqHJavFaVmKDW/view?usp=sharing
[43]:  https://drive.google.com/file/d/1GUkcECr4NIXuLE8JC78bMABDvlxhjBJU/view?usp=sharing
[44]:  ../lectures/15-more-data-structures.pdf
[45]:  https://drive.google.com/file/d/18jm_OhzdcBFNtdtZPqMNKOPJG8Licl6H/view?usp=sharing
[46]:  https://drive.google.com/file/d/1-uUgA2bwLHf2Xg3ekGFgE5ITFaHN8ce0/view?usp=sharing
[47]:  ../lectures/16-optics.pdf
[48]:  https://drive.google.com/file/d/17zdvG7jZGhUdS3jJYcAeOwmaVucGcIUq/view?usp=sharing
[49]:  https://drive.google.com/file/d/1pVBmKqLSbmXDh0kwyqpPnQY9W9s9eFMQ/view?usp=sharing
[50]:  ../lectures/17-more-optics.pdf
[51]:  https://drive.google.com/file/d/1diCeBDVNCxl97kFAF7S8V4jhqLHucLB0/view?usp=sharing
[52]:  https://drive.google.com/file/d/1gbVNoOFhuQCUtDr79gswScrYNjiONUpb/view?usp=sharing
[53]:  ../lectures/18-more-monads.pdf
[54]:  https://drive.google.com/file/d/1WEbuxxFYZvThn5TOSaIgvfT7peSwBa6k/view?usp=sharing
[55]:  https://drive.google.com/file/d/1hR91DeUj9FYqhFDZvko9nclWEgDVqr4O/view?usp=sharing
[56]:  ../lectures/19-free-monads.pdf
[57]:  https://drive.google.com/file/d/1hOEQu8l-3Lv4vr1sTv3gvJBUpumQEu5Y/view?usp=sharing
[58]:  https://drive.google.com/file/d/1HUy0_jwxDmo_iueRoB3gKzmNf82-ckxh/view?usp=sharing
[59]:  ../lectures/20-streaming.pdf
[60]:  https://drive.google.com/file/d/1TO0TVHJZWrwMvzGCRagE7STB3WsJniuD/view?usp=sharing
[61]:  https://drive.google.com/file/d/1yVpAiy4jQ6F7ZfiDPPG5LDrZWHMui-Oq/view?usp=sharing
[62]:  ../lectures/21-dsls.pdf
[63]:  https://drive.google.com/file/d/1VeBZum65R3R0BWSMaG8VS8yUW3epge9u/view?usp=sharing
[64]:  https://drive.google.com/file/d/17wJGLVhkVDR3FXP0Vc4TL07e_yjdQtLs/view?usp=sharing
[65]:  https://drive.google.com/file/d/1sAGeMxvz8u73gZ0IEznRnfMF1pTiv82Y/view?usp=sharing
[66]:  https://drive.google.com/file/d/1lpUHD1DNIXt9Y2FNl3OLKjRQ1JMbvSTF/view?usp=sharing
[67]:  https://drive.google.com/file/d/1DK2k23rlQ-Y_Lc-AGqu1tkvMELSX_R3T/view?usp=sharing
[68]:  https://drive.google.com/file/d/1z4JDttyvrTPHC2M7LPUemcXItJAhPLOf/view?usp=sharing
[69]:  https://drive.google.com/file/d/1wFjlLNJ14h6my8-1kw2sThmHMGJfN2Ef/view?usp=sharing
[70]:  https://drive.google.com/file/d/17H6-LQElMJstZQp3wM998Zz1ckMoxdm4/view?usp=sharing
[71]:  https://drive.google.com/file/d/16-wypdPzH0gQWH5V39fIni3AVNR1cu97/view?usp=sharing
[72]:  https://drive.google.com/file/d/1AVtx_RV55Wn0mj_2k7jnS7mkCa6rNesI/view?usp=sharing
[73]:  https://drive.google.com/file/d/1cdY_RfuKNCRxXDiZeQ59_qZX-P_J8UAi/view?usp=sharing
[74]:  https://drive.google.com/file/d/1LvTGGZBX27ZXqxIIKGjgDS0DVhXUXAY8/view?usp=sharing
[75]:  https://drive.google.com/file/d/1OVNlhRT1SiFGVyEjlLx1Uw-0TZmOqxsn/view?usp=sharing
[76]:  https://drive.google.com/file/d/1btfOCt3g_bKqyYTnwdEOivke9ofp4Op9/view?usp=sharing
[77]:  https://drive.google.com/file/d/1PoT0FGsX_9E0zesdaMNcUzlV64B-91Tf/view?usp=sharing
[78]:  https://drive.google.com/file/d/1gm2gtp4_95tP0zn59Gt48Zk2xaqcc03s/view?usp=sharing
[79]:  https://drive.google.com/file/d/1QvGbbaGSUzr5jbtcRNjXabpipE-z6uib/view?usp=sharing
[80]:  https://drive.google.com/file/d/13vIEnie4Cjbc41TX4t6KNt4h5dVHBQi4/view?usp=sharing
[81]:  ../lectures/22-template-haskell.pdf
[82]:  https://drive.google.com/file/d/1kmeVAqn0tugQ53DFW_ylro7pDoCQhsED/view?usp=sharing
[83]:  https://drive.google.com/file/d/1lvR2rupIgA-KeddDWIIuOyBdJLYO1onk/view?usp=sharing
[84]:  https://drive.google.com/file/d/11cpYOPx-MuNjFo1Ia_DuH1DiTqMidpsP/view?usp=sharing
[85]:  https://drive.google.com/file/d/1IHccsUdYivX1GOn_vDz9E4zn_T21596-/view?usp=sharing
[86]:  https://drive.google.com/file/d/1t5j5Rcdmq300lkQ8T4MH5ZRq8OAhcLnB/view?usp=sharing
[87]:  https://drive.google.com/file/d/1QXVpG1-UcSDco0jAhrHuYwU9s3kCXV5J/view?usp=sharing

### Assignments

Homework are due on Fridays before the lecture, one week after they have been handed out.
All homework submission is via GitHub classroom.
If you have questions, check this video:

- [Introduction](https://github.com/iohkedu/02-Introduction)
- [Datatypes & Functions](https://github.com/iohkedu/03-datatypes)
- [Higher-Order Functions](https://github.com/iohkedu/05-higher-order)
- [IO](https://github.com/iohkedu/io)
- [w01](https://github.com/iohkedu/w01)
- [w02](https://github.com/iohkedu/w02)
- [w03](https://github.com/iohkedu/w03)
- [w04](https://github.com/iohkedu/w04)
- [w05](https://github.com/iohkedu/w05)
- [w06](https://github.com/iohkedu/w06)
- [w07](https://github.com/iohkedu/w07)
- [p1](https://github.com/iohkedu/p1)


[200]: https://drive.google.com/file/d/1_dVRHFZgZhQE27HhDVRLq_QdvJAP1yK0/view?usp=sharing
[201]: https://drive.google.com/file/d/1Wx-vzhmE4XiaocV2FrV5VtloG8xniDP8/view?usp=sharing
[202]: https://drive.google.com/file/d/1TAWPyPOLN1AdOQggiCzbyCQYnrOswrhD/view?usp=sharing
[203]: https://drive.google.com/file/d/1rDZmNo0wcnys_kljQYMb_ObNzP_R9wXo/view?usp=sharing
[204]: https://drive.google.com/file/d/1B3A_HhnJ7YsooKq5dcbdqm7n6QbO4myY/view?usp=sharing
[205]: https://drive.google.com/file/d/1Vlc5BbO92EjNqvWmpMviZL5ARVI8kSu_/view?usp=sharing
[206]: https://drive.google.com/file/d/1t7sMpQsnId7eY_4Bvdg664Zh-9me9Xli/view?usp=sharing
[207]: https://drive.google.com/file/d/1NB6CmN6zVAlOI1XBtmUbxM3mc1GC83pT/view?usp=sharing
[208]: https://drive.google.com/file/d/1ABo-iMUsXeMXS9fRzCyAlGkgoAvapSDK/view?usp=sharing
[209]: https://drive.google.com/file/d/1YtJsnBTEYxWRwQ9LRLOkVg5VfbgM6Cl5/view?usp=sharing
[210]: https://drive.google.com/file/d/14j7Z1QraMofS4IzX-X9a7a7J-KliHaRx/view?usp=sharing
[211]: https://drive.google.com/file/d/1nJMgP3m8cP1pwCWgx1-C_jnPFYxJlsvh/view?usp=sharing
[212]: https://drive.google.com/file/d/1W7odvqAiYLkbaz8fyrnl1BRTRjVrsJ3V/view?usp=sharing
[213]: https://drive.google.com/file/d/1HlP3uZ-hEp9z6X6DT2YgOzCKwo370yHu/view?usp=sharing
[214]: https://drive.google.com/file/d/1WRw73J8SvKJ-mEJGFLJV82JecjMmSB3r/view?usp=sharing
[215]: https://drive.google.com/file/d/1-nUmXDYojurK2mBp0LkN-shMRa_fjGAo/view?usp=sharing
[216]: https://drive.google.com/file/d/13k2QdK1HJbON_YwUqQJzf2G1iJz5vToN/view?usp=sharing
[217]: https://drive.google.com/file/d/12OiMSmoA6yItBWZZj-M2V4CE1ZD7eRyq/view?usp=sharing
[218]: https://drive.google.com/file/d/18Szu5rqzGkD87xLXE21ZOrcwKhaQj0Jv/view?usp=sharing
[219]: https://drive.google.com/file/d/1TtCgsQC19QaIpItaeLTGuY1f4iih_cAt/view?usp=sharing
[220]: https://drive.google.com/file/d/1PeN0Q-GygHITA-sh5RdrlLBkmITny6N1/view?usp=sharing
[221]: https://drive.google.com/file/d/1Atov2UfZeXk2uWO1f1vQjxWPh4gThPe2/view?usp=sharing
[222]: https://drive.google.com/file/d/1b2qjN09AVDZ1hxIWpC5Og5stYbeib4-M/view?usp=sharing
[223]: https://drive.google.com/file/d/1iHwKy_fOBxuriyDVrIGT2Sduv_vW7ajJ/view?usp=sharing

### Bibliography

We have read most of these books and they provide good information for beginners.

1. Lipovača M. [Learn You A Haskell For Great Good!](http://learnyouahaskell.com/). San Francisco: No Starch Press; 2012.

>Beginner Friendly book with lots of examples.

2. O'Sullivan B, Stewart D, Goerzen J. [Real World Haskell](http://book.realworldhaskell.org/). Farnham: O'Reilly; 2009.

>A lot of real world techniques, just a little bit outdated at this point.

3. Bird R. [Algorithm Design With Haskell](https://www.amazon.com/Algorithm-Design-Haskell-Richard-Bird-ebook/dp/B08BKXJ1N3/ref=tmm_kin_swatch_0?_encoding=UTF8&qid=1597814133&sr=8-1). Cambridge University Press; 2020.

>Learn how far you can get with immutable data, to implement almost all standard algorithms.

4. Thibaut C. [Texas Hold'em: The Little Haskeller](https://leanpub.com/texasholdem-tlh).leanpub.com; 2019.

>A long article, written in the Quesntion and Answer format. Like the Little Schemer.

5. Penner C. [Optics By Example: Functional Lenses In Haskell](https://leanpub.com/optics-by-example). leanpub.com; 2020.

>The only book on optics.
