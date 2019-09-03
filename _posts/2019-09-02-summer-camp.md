---
layout: post
title: "[hacker|security] summer camp - observations from @BsidesLV and @defcon 27"
date: 2019-09-02
---

security camp, hacker camp either/and, doesn't matter because it is warm/hot, community of like minded folks, numerous cons with *lot's* of opportunity to explore, engage and learn! a few items of note below and did I mention the heat, ahhhh :D

Curious to learn more about single sign-on, <em>SSO Wars the token menace</em> provided an overview along with two CVEs one of which highlighted how code paths that don't coordinate can lead to "confusion" and exploit. <a href="https://github.com/pwntester/DupeKeyInjector">Slides, code and more</a>


___


Graph theory! Visuals are good(tm). Previous talk(s) including <a href="https://www.youtube.com/watch?v=ZukUmZSKSek">Sacha Faust using graphs to map assets</a>, along with some basic exposure/dabbling with neo4j has me on the lookout for more and @BsidesLV didn't disappoint:

<a href="https://twitter.com/cxosidekick">cxosidekick</a> shared *lots* of great detail about the use of graphs including graphing/mapping an environment (tech, business, risk), automated workflow involving humans to update/improve security posture and accept risk, with tools the org. was already using. <a href="https://youtu.be/LjCtbpXQA9U?t=4153"><em>Building an enterprise security knowledge graph to fuel better decisions, faster.</em></a>

<a href="https://twitter.com/insanitybit">insanitybit</a> focused in on parsing logs to graph, enabling reduction in volume (compared to the logs) and an example identifying exploit flow. <em><a href="https://youtu.be/LjCtbpXQA9U?t=8025">Grapl - a Graph Platform for detection and response</a></em> and <a href="https://github.com/insanitybit/grapl">Grapl on GitHub</a>

During a line discussion <a href="https://github.com/BloodHoundAD/BloodHound">BloodHound</a> was mentioned (new to me!) that maps AD relationships using graph theory so you can identify who is a member of what for example.

___

32 villages at defcon 27! that now includes boats and planes, awesome! options++ including 10th year for the social engineering village where the people skills aspect of several talks around communication were relate-able for me to work/life scenarios:
 - "don't do emotional crazy & don't judge, understand" Robin Drake
 - @ghostie_ loosely don't negate the frame, don't mention negative behavior or what you don't want folks to do.

On the framing theme, a @BlueTeamVillage talk by @investigatory about security education and dropping the sky is falling/fear angle for **healthy skepticism** along with positive security stories. Pondering/looking to see how to incorporate this!

Luckily was able to attend two workshops care of @BSidesLV and @BlueTeamVillage to get hands on with elastic stack/ELK/BELK. The latter involved a CTP to navigate the software to determine aspects of events, managed an 11th place, more importantly a chance to explore Kibana. Suspect there must be some graph theory UI action available out there, could have come in handy, more to learn...

Discussion on medical devices, brought up this scenario: a family member, friend, colleague, ... dies. You know they have one or more electronic health devices - can you request an autoposy of the electronic equipment, does it have appropriate tamper proof logging, ..... Good discussion, food for thought during healthcare fireside chat.

*[Phising in the cloud](https://www.netskope.com/blog/defcon-cloud-village-phishing-in-the-cloud-era)*, explored scenarios whereby the SSL lock is there, so it's all good (tm) and  safe to open right, nope? not to mention the slick software development and marketing of phishing toolkits, to empower you on your "quest".


Automating discovery of exploitable vulns in firmware https://github.com/ChrisTheCoolHut/Firmware_Slap

