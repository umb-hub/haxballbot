# Haxball Bot Room Manager
This is a project for Software Engineering Exam about design a bot for manage an Haxball's room.

#Contents
- [Abstract](#abstract)
- [Stakeholders](#stakeholders)
- [Functional and non functional requirements](#functional-and-non-functional-requirements)
	+ [Functional Requirements](#functional-requirements)
	+ [Non functional requirements](#non-functional-requirements)
  
  
# Abstract

Haxball is a physics-based multiplayer soccer game without any login process. To play it's enough insert a nickname and choose a room to play. Anyone can create his room or partecipate to another's one, his architecture is a P2P architecture-based but a server entity is used to prevent attacks. Haxball's community is the core of the game, infact this game is really customizable and his users creates maps and gamemodes.
Cause of p2p architecture room's owner network is not suitable to handle multiple connection, or room's owner abuse their role to get an unfair game. To avoid those problems creator game enable users to make their own automated game rooms through [API](https://github.com/haxball/haxball-issues/wiki/Headless-Host))
Our stakeholder is a haxball player, sick of other game master's abuses, so he asks us a wonderful bot to manage his room.

# Stakeholders
| Stakeholder name  | Description        | 
| :---------------: |:-------------------|
| Users           | They are interested in finding a cool bot, that manage game in a fair and cool mode and can show their achievments. | 
| Owners          | They are interested to improve Haxball Community with an automatized and fair system. |
| Devolpers       | They are interest to do a good platform that can be reused in others project and get their exam with maximum vote. |

# Functional and non functional requirements

## Functional Requirements
| ID       |Description  |
| ---------|:-------------| 
|  REQ1   | Handle automatically game initialization in a specified mode. |
|  REQ2   | Handle registration and authentication and make sure that nickname is unique. |
|  REQ3   | Monitor and save the stats for each game and registered players. |
|  REQ4   | Cool stuff chat with emoji's shurtcut. |
|  REQ5   | Avoid malicious behavior by players. |

## Non-Functional Requirements
| ID        | Type (efficiency, reliability) | Description  | Refers to |
| ------------- |:----------:| :---------------| :-----:|

