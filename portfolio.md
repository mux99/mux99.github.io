---
layout: home
title: portfolio
nav_order: 2
nav_titles: true
titles_max_depth: 3
---
## Hours recap

| activity | theme | real hours | validated | start | end |
| --- | --- | ---:| ---:| --- | --- |
| Catch the flag | ctf | 12h | 10h | ? | ? |
| Hackaton 20225 | hachaton | 48h | 10h | 2022/10/28 | 2022/10/30 | 
| Discord Bot | personnal | 25~30h | 10h | 2021/12/? | 2023/02/16 |
| Lab power supply | personnal | 12h | 10h | 2020/?/? | 2024/04/7 |
| Nuke plugin | for a friend | 6h | 6h | 2024/04/9 | 2024/04/9 |
| Pc upgrade |
<!--| TETRIS project |-->
| Raspberry pi Minecraft server |
||

## Details

### Catch the flag

### Hackaton
In october of 2022 I participated in an Hackaton at EPHEC-LLN on the subject of green developement. The objective was to come up with and idea of app/website that would help solve an issue liked with sustainable developement. The idea we came up with was a wesite that would be a News source but only chowing positive articles. To reduce the need for administrators and content managers, we planned the site to work colaboratively. A bit like wikipedia.

It was really interesting to have the perspective of a marketing student while discussing features and the idea itself. Their insight was enlightening.

<details markdown="block">
<summary>proof</summary>

![](/assets/hackaton.jpg)
</details>

### Discord bot
Initially developed during the revisions of the January exams. The idea was to create a bot that could be customized to recognize multiple commands. The one I was most iterested in was a command that would allow people se see what multiplayer games they had in common. To do that Everyone on the server votes to tell the bot what games they have (and are willing to play with other). The vote uses the reactions to messages that are maintained and updated by the bot.

<details markdown="block">
<summary>It looks like this</summary>

![](https://cdn.discordapp.com/attachments/566710939760721933/1226506006981247036/image.png?ex=662503bb&is=66128ebb&hm=be425f0d64b9dff752236f6c25aa798d1de6b708424bf1fc7d0e6c7e850f1234&)
![](https://cdn.discordapp.com/attachments/566710939760721933/1226506221972881469/image.png?ex=662503ee&is=66128eee&hm=1a2430b4751bf6d44faebea2362ce34e113e2353306ec041735f95fb3bf9af84&)
![](https://cdn.discordapp.com/attachments/566710939760721933/1226506334426501262/image.png?ex=66250409&is=66128f09&hm=f9a1c185d2c4bddc05961fa4ac1d6a745403f55e78ec275653ff39353e0861c8&)
</details>

When users vote, the bot keeps track internally of who plays what in memory. From then on, when two or more users want to play together, they can call `*wtp <@user1> <@user2>` and the bot will list all games in common:

![](https://cdn.discordapp.com/attachments/566710939760721933/1226508677624627200/image.png?ex=66250638&is=66129138&hm=ccf2214e79095ca07775982f2a78f92c2332652baf295fd87003bd8c1d01ba55&)

to keep the chat neat, the message conaining the command is deleted by the bot, and the response given will be removed after 5 minutes.

When embarking on this project, I was not familiar with API work. It was really intertesting to navigate the existing data structures and hooks of discord to create this bot. It was also a good oportunity to better my python, wich was not amazing at the time.

[git repository](https://github.com/mux99/Nawak-Bot)

*note: Reader, I would be delighted to discuss it further with you if you are interested ^^*

### Lab power supply
This is a short project for which adencements where made verry slowly over time, one hour here, half an hour there. The goal was to convert an old PC power supply I had lying around, and convert it to a lab power supply that could output, 12 and 5 volts. It was not a difficult project by any stretch of imagination, but it was one of the more pleasant ones.

### Pc upgrade

<!--### TETRIS project-->