It is named Cyberware Fighters, the [Steam page](https://store.steampowered.com/app/2461910?beta=0) has been created.

## Description

## Background

With the maturity of prosthetic body technology, people have become accustomed to physical transformation. Yes, this is the cyberpunk world that appeared in the novels in the past. Among them is a group of people who are the pioneers of physical transformation. They transform their hands to enhance their attack power, transform their legs to enhance their mobility, and embed artificial brains to enhance their prediction ability. They are fighters, they are called--Cyberware Fighters.

## Overview

The background of the game is a futuristic world of *cyberpunk* and *Chinese KungFu*, and the game type is a *beat-em-up action game* that combines the *roguelike* gameplay.

## Features

## Rogue-like

Arcade beat-em-up action games are still a genre with a relatively long lifespan. Up to now, there are still many game genres with active fans, such as "Dungeons and Dragons", "Knights of Valour" and so on. However, the traditional beat-em-up game has a single process and lacks freshness. If it is combined with rogue-like gameplay, it can make the game process full of freshness. In the game, players can also choose a combination of different prosthetic bodies to create completely different characters to break through the level. This kind of prosthetic body obtained immediately can also give each game process a completely different game experience.

## Action Combo System

The action system is a very important system for beat-em-up game. Now there are still many players who are studying the "Instakill" gameplay in "Knights of Valour" (limited to only one set of combos to kill the boss). The combo system is also the core of this game. Core gameplay. There are many genres of action systems now, but I still prefer the middle hardcore action system of ARC System. The sequence connection is relatively free, but it is not an action system that can form a sequence by pressing the XY keys. It has certain requirements for operation. But it's not too difficult, it needs some practice, and it can generate a lot of positive feedback to the players.

- Scaling: The combo correction system is more friendly to the design of the attack action, and the general attack will be added with a scaling (there will be some penalties for attacks in the same combo later in the attack power and stun time), which can be used in a combo When the same move hits the target, the same skill scaling will give a greater scaling penalty. This system can not only encourage players to use different skills, different players choose different variants, but also make the design of attack skills more free and less prone to "one move" In the case of "one-trick pony", the player's combos will also be more diverse.

https://github.com/Boros-Tech/CyberwareFighters-Docs/assets/125040847/b1b26520-0ef0-42e3-9062-b8c125eb8b8a

- Elite Shield: For bosses or elite enemies, adopt the design of elite shields. Before the enemy's shield is exhausted, it will only cause a small amount of damage and pause to the enemy, and will not cause effects such as stun or launch. After the shield is broken, the combo can be started, and the elite shield will be restored after the combo ends and the normal state is restored. This is not an innovative design, but this design does solve the following problems:

    1, There is no need to design a boss with a full endure. In order to prevent the boss from falling down at the first touch, the boss must be given a certain body setting, or the boss is endowed with a strong dodge ability. The dodge ability is divided into two types: soft dodge and passive dodge. Among them, soft dodge will cause difficulties in AI design, and if passive dodge is too frequent, it will conflict with the core gameplay combo system (but it can also be used as a feature of some few bosses. Design), and the full-scale Boss will conflict with the game's core action combo gameplay.

    2, Make Boss battles pay more attention to the quality of combos. Every time a combo is brought in, some pre-attacks are required to reduce the elite shields, which will make it appear that offensive opportunities are relatively scarce. Players must seize this fleeting opportunity. I have observed that there is also a design that restores elite shields according to time. I personally don't like this design and weakens the role of combos in Boss battles.

- Energy system: Refer to the energy system of "Denjin Makai II", which is my favorite energy system in the beat-em-up game, which makes the game process very refreshing. The character can consume energy to perform the special moves. After the energy is exhausted, using the special moves again will consume one bar of blood to restore the full energy bar so that the character can successfully perform the special move. The way to restore energy is also very simple, you can restore energy by stopping the action for a period of time or attacking the enemy can also restore a small amount of energy.


https://github.com/Boros-Tech/CyberwareFighters-Docs/assets/125040847/bbf0d284-6695-4847-bef0-423bd91473ac

- Move method: Personally, I prefer the traditional rubbing method, but other moves can be realized through the difference of the prosthetic body. Here is a well-designed drill weapon. All of its moves do not need to be rubbed, but the concept of "action cancellation" is also used. This example is intended to illustrate that different styles of actions can be realized by designing different variants. For example, in "Vanillaware", it is also possible to derive different action modes by using the direction keys and light and heavy attacks in the combo.

https://github.com/Boros-Tech/CyberwareFighters-Docs/assets/125040847/afe24f04-93d7-4936-9aad-89d06d3e37ea

## Item System

The item system is very similar to the item system in "Dungeon and Dragons" and "Knights of Valour". Players can pick up different items in the game. These items are divided into three categories:

- Immediate effect item: It takes effect immediately after picking it up. For example, food immediately restores stamina, and gold increases some gold coins.
- Usable item: Pick it up and put it in the item bag, then you can select it at any time and release it manually.
- Cyberware item: Similar to the equipment system, you can replace it directly after picking it up, and the old cyberware will fall to the ground. Please refer to [Cyberware System](#Cyberware System).

https://github.com/Boros-Tech/CyberwareFighters-Docs/assets/125040847/e569332c-dc5a-4028-bea1-fce1632b022c

## Cyberware System

The cyberware system allows players to customize their own characters. Players' characters can pick up cyberware from different parts during the game process to replace their own cyberware to create completely different characters. Through the cyberware, you can get different attack actions, arts and moving and jumping abilities. During the game process, you can also spend gold coins to enhance your cyberware to obtain stronger arts.

Cyberwares are divided into 5 different slots：

- Cyber body: Determine the character's image, attack and attack scaling, as well as basic physical strength and attack power. Generally, the selection in the preparation interface will not change during the game.
- Main Weapon: Usually manifested as the main hand of the character or the prosthetic body of both hands. It can provide attack actions and some arts for the character, and more arts can be unlocked through upgrading, usually designed as an attack action triggered by pressing the X button.
- SubWeapons: Usually appear as additional equipable weapons. It can provide the arts of using weapons (such as the shooting attack in "Dian Jing 2" and "Heterosexual vs. Predator"). The actions provided by the secondary weapon will consume stamina, and more arts can be unlocked by upgrading. Usually designed as an attack action triggered by pressing the Y key.
- Brain Chip: In the background story, fighters will use different internal functions by installing artificial brain chips. It will not be shown in the character image, but its unique energy bar will be added to the character UI. The accumulation method of the energy bar is completely designed by the chip designer. The artificial brain chip will also provide some attack actions and arts, but they will all consume artificial brain energy bars, and their status is equivalent to that of super arts in traditional clearance games. More super arts can be unlocked by upgrading, usually designed as an action triggered by pressing the B button.
* Foot: The character's legs are transformed into a cyberware, which defines the character's movement ability. Upgrades can unlock special movement abilities (such as double jump, dash, etc.).

https://github.com/Boros-Tech/CyberwareFighters-Docs/assets/125040847/c23a6b10-6809-4fda-b746-9ac1319379c0

https://github.com/Boros-Tech/CyberwareFighters-Docs/assets/125040847/0b2971fb-03c6-47eb-9c8a-866af30befe2

## Workshop Support

The action design of action games is usually very difficult. Compared with games that are purely numerical, it is more necessary to consider the balance of actions. If a certain attack action is very powerful, it is likely that there will be a "one trick" situation (some The game will add a cooling mechanism to limit the use frequency of a single move, but I don't like this design greatly weakening the refreshing feeling of action games). So I added the same skill correction, elite shield, and energy system design, just to make the design of attack actions more free.

When the game is released, a custom Godot development engine will also be released, allowing the development of custom prosthetics. Because the Godot engine is cross-platform, customizable, small in size, visual operation, open source and free, and script code, it is very suitable for use as a tool for content creation.

## Multiplayer

The game provides local multiplayer and online multiplayer functions, and players can cooperate with multiple players to break through and fight against each other.

## Development Status

Now the action system, prosthesis system and props system have been developed. The EA version is expected to be released in August, in which the following content is planned:

- Arcade mode: Rogue-like mode with about 5 levels.
- Online mode: Rogue-like mode where you create a room online and play with online players.
- Preparation interface: After selecting the arcade or entering the room, the player will first enter the preparation interface, where the player can change the body, and the host can also choose additional content that can appear during the game process.
- Enemies: At least 6 types of miscellaneous soldiers and 5 types of bosses.
- Custom content: Open content development tools, you can develop custom prosthetics and enemies, and upload them to the creative workshop and share them with other players.

## At Last

## Project Approval

I'm a retro gamer and I love beat-em-up games. The beat-em-up game is very suitable for multiplayer games to break through the level with friends. It is very easy to get started. Even a novice in the arcade hall can get through the first level. I want to develop such a clearance game. At the same time, I also observed some problems of this game type, so I hope to solve these problems by adding meat pigeon gameplay. So I thought of changing the prosthetic body under the cyber world view to conform to the setting of this drastically changed action, so I thought of the background stories of "Denjin Makai II" and "The Cyber Slayer", which finally determined the development direction of the game.

## Problems

The advantages and disadvantages of some beat-em-up games I have observed, I hope to keep the advantages and solve their weaknesses.

Advantages：

- Party games, anyone can join the game at any time at any time, easy to play, even novice players on the arcade can pass the first level, and there is no need to develop characters for a long time.
- Excellent gameplay, I have observed that many webpages now wear the skin of clearing the game but the core is an online game that focuses on RPG gameplay (such as: DNF, Naruto, Captor Clash, etc.), and the action part is used for quick capture. It also shows the role of the player's attractiveness, which also shows that the beat-em-up game is easy to pick up and has excellent gameplay.

Disadvantages：

- The workload of adding art is huge, and the workload will increase exponentially as the number of cyberwares increases.
- The duration of the game is short, because this type is designed for arcades, generally the duration of arcade games is about half an hour, which is really too little for home console games.
- It is more difficult to add actions. It is very difficult to design actions for this kind of strong action game. It is necessary to maintain the uniqueness of actions and prevent loops from appearing. Therefore, there are not many actions except for fighting games.

Solutions：

- For the art solution, using 3D characters does not need to be pinched by hand, you can use MagcaVoxel to make a voxel model, and then import mixamo to install the skeleton model.
- For the problem of game duration, add rogue-like gameplay and support for custom content.
* For the problem of action design, add serial correction and cyberware system to reduce the difficulty of design. "Scaling" can effectively prevent the occurrence of loops, and the cyberware system can reduce the number of actions that need to be designed at one time.

## Others

To make some digressions, because I haven’t considered the main story yet, I didn’t design the characters at all. The bodies in the demo video are the recent favorite virtual characters Zundamon and NeuroSama, both of which are the products of recent machine learning, and they will not appear in In the official game, it should be placed in the sample of the development tool. The current development of AI is really fast, and new technologies are becoming more and more open. After the emergence of ChatGPT, I used to think that it was difficult to get started. I only need to keep asking ChatGPT questions to easily enter new fields. I want to say that I have managed open source projects, and as a developer, I also understand what support content developers need, so I want to make such a game that emphasizes the creative mode. I believe that as long as the tools are convenient and open enough, there should be many players who want to add all kinds of unconstrained content in action games.