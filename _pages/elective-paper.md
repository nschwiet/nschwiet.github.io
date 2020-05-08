---
layout: archive
title: "Analog Game Metadata Schema: AGMS"
permalink: /elective-paper/
author_profile: true
---

[PDF of elective paper](/files/ElectivePaper.pdf).

### Abstract

Tabletop games have increased in popularity over the last 20 years among hobbyists, collectors, librarians, and scholars. This metadata schema is intended to support cataloging efforts of tabletop games as cultural artifacts for use in libraries and research. While the website BoardGameGeek has served as the defacto metadata source for board gamers, the metadata and vocabulary they collect and make queryable falls short for purposes such as classification, circulation, and tracking trends in design and distribution. Issues include inconsistent and vague use of categories, mechanics, an absence of role playing games which are described on a separate site, RPGGeek, and an absence of most card games. This paper builds on the work done by BoardGameGeek as well as the Video Game Metadata Schema developed by University of Washington Information School Game Research Group.

### Introduction

Tabletop games, especially board and role playing games, have increased in popularity over the last 20 years (Duffy, O. (2014). In gaming literature, board games and RPGs have not enjoyed as much interest and research as video games and sports. However, interesting research is being done around the sociality and aesthetics of board games and RPGs. These advancements in tabletop games preclude a necessary mode in which to engage with them as an information object and cultural artifact. In order to classify and discuss tabletop games in the context of libraries and archives, a metadata schema is proposed which builds off the current leading community around board games, BoardGameGeek (BoardGameGeek, 2019), and parallel work done at the University of Washington and their Video Game Metadata Schema (Video Game Metadata Schema, 2017).

The definition of games used for the purpose of this project is taken from the philosopher Bernard Suits: “the voluntary attempt to overcome unnecessary obstacles” (Suits, 1978, p. 53). According to this definition, they must be engaged in voluntarily and they must contain obstacles, which are imposed by the rules. A key argument for playing a game according to Suits is achieving the lusory attitude, or “To play a game is to attempt to achieve a specific state of affairs [prelusory goal], using only means permitted by rules [lusory means], where the rules prohibit use of more efficient in favour of less efficient means [constitutive rules], and where the rules are accepted just because they make possible such activity [lusory attitude]” (Suits, 1978, pp. 54-55). This has been dubbed “striving play” (Nguyen, forthcoming), where a player takes on the end state of the game and makes it their own end state while they are engaged in this play. Due to recent interests into the aesthetic and practical properties of games and the heightened interests in board games, a method for discussing these complex artifacts as information artifacts is in order.

Tabletop games are largely defined by their physicality (Analog Game Studies, 2014). Typically, players are required to be within physical proximity of each other. Core components of the game that players interact with are also constituted in a physical medium, such as boards, cards, and figurines which largely distinguishes tabletop games from other games, such as sports. Due to the increasing literature around these types of games which refer to them as analog (Analog Game Studies, 2019), this schema follows adopts this terminology and will refer to these games as analog games, with the schema titled Analog games Metadata Schema (AGMS). While there is considerable debate regarding what to call this genre of games, this paper will use the terms analog and tabletop interchangeably, both of which capture the genre of games discussed appropriately.

### Audience

The schema proposed here is intended for librarians, archivists, researchers, and hobbyists for cataloging, recordkeeping, and sharing collections of tabletop games among individuals and institutions. The schema is intended to build off pre existing metadata already captured by BoardgameGeek in order to make possible the extraction of the immense metadata that the community has already contributed to the site while establishing a vocabulary for standardizing descriptions of tabletop, RPG, and card games among the community. The schema aspires to be mappable onto MARC records (Library of Congress, 2019) as well as to the Dublin Core Metadata Schema (DCMI: Dublin Core Metadata Element Set, Version 1.1: Reference Description, 2019) to promote ingestion into other repositories. Finally, certain schemata items aspire to be interchangeable with the VGMS. In order to ensure compatibility with existing metadata schemas and crosswalk tools, the schema will be maintained as XML (XML Introduction, 2019).

Existing search and retrieval systems around tabletop games are distributed among various online communities. BoardgameGeek is the leader in aggregating and making searchable board games. Their sister site, RPGGeek (RPGGeek, 2019), plays the same role in the Role Playing Games (RPG, 2019) community. Pagat (Pagat, 2019) is the leader in games which use the 52 card deck (“French Suited”) popular in the United States and increasingly the world due to popularity of Poker. There is some overlap in each of these communities, and among these communities and the video games communities (e.g. apps that play the same games or apps necessary to play some hybrid analog/digital games). Each of these sites includes their own search criteria and organization of these objects. There is no controlled vocabulary across these sites which makes using them in the information institutions like the library difficult.

### Metadata Creation

This schema aspires to become the authority voice in each of these named communities and hopes that these communities can participate in this project in return. As a way to encourage participation and to acknowledge these communities as authority sources themselves, crowdsourcing is proposed as a method for generating these partnerships and creating metadata, as recent efforts  indicate that engaged communities do actively participate (Deines, Gill, Lincoln, & Clifford, 2018). To this end, data already generated from these sources will be used to populate this initial metadata schema. However, care will be taken to tidy up the conflation of mechanics, themes, and subdomains that already exists in these sources. Input will also be derived from the existing VGMS and from various game communities.

The crowdsourcing discussed here is done by proxy; numerous board game enthusiasts and players have contributed enormous amounts of information to sites like BoardGameGeek. This metadata is already useful and powerful. RPGGeek is operated by a contingent community and follows many of the same metadata practices, allowing for integration of these two authority sources. More difficult to assess is the metadata on Pagat as it is operated by a different community with different metadata practices. While the card games are generally broken into class and type, these elements are not searchable through the site interface. Some work would need to be done in order to more closely align the explicit and implicit information available on that site with more readily available metadata on BoardGameGeek and RPGGeek. It is suggested that once a widely agreed upon schema and vocabulary are developed, crowdsourcing within the game community could assist with this metadata integration.

### Metadata Categories

#### Physical Elements

Tabletop games, being defined by the objects that comprise them, are necessarily physical. They play out in a physical space, have physical components, and require physical interaction among players. There is discussion that computers and the digital are also physical, bits and bytes sitting on magnetic disks or like media. This paper does not enter this debate, but makes the digital/analog distinction for pragmatic purposes, mainly along the dimension of how players engage with the game medium. Due to the physicality of tabletop games, certain metadata elements will be necessary for describing these components. This aspect differentiates analog game metadata schemas from certain video game schemata. Physical schemata include number of players, game pieces and components, box dimensions, and play space requirements.

#### Theme

An aspect that most games, analog and digital, share are themes. Themes are often but not necessarily rooted in history or a fantasy or science fiction narrative. Themes may or may not be intertwined with the mechanics of a game. For example, Twilight Struggle is heavily themed after the Cold War with opposing players taking the side of the US or the USSR. The theme of Twilight Struggle is intimately connected with the mechanics of the game. Lost Cities, a game themed around exploration and discovery of lost monuments, is a game where the theme and the mechanics do not appear codependent but instead largely independent. Games like chess and bridge are considered abstract games as there is largely no narrative surrounding the narrative of the game. Common themes in tabletop games include abstract, war, and economic.

#### Mechanics

Mechanics are another schemata point that is shared between analog and digital games. Mechanics are in short how a game is played. They are the affordances a player has in the gamespace for overcoming the obstacles presented by the game rules. Mechanics are therefore important to most game types: in chess bishops can only be moved diagonally; in basketball the ball needs to be dribbled; in Simcity zones can only be developed so far from roads; and so on. While mechanics are shared across game types, certain types of mechanics are prevalent to certain game mediums. For example, probabilistic outcomes are more readily calculated in video games, though they do occur in boards games and RPGs as well (such as the 20 sided die in Dungeons and Dragons). Common mechanics include deck building and tile placement.

#### Aboutness

The aboutness of a game is also shared between all game types. This description of games is difficult to assess in a systematic way due to the subjective experience of players. It is interested in the question of what it is like to play a particular game, or to make a move within the game rules. Recent scholarly work is currently taking shape to answer these questions (Nguyen, forthcoming), and this research has implications on how games could be described via a metadata schema. This metadata schema does not intend to be an authoritative voice in the present state of the discussion concerning the aboutness of games, though it leaves room for advances in this area.

#### Provenance

Finally there is the game provenance metadata. This category includes rights and intellectual property information such as designer, artist, and publisher information as well as other administrative data such as release date, release version, and rating (e.g crowdsourced ratings from BoardGameGeek). Provenance data provides information about what publishers release games when, giving an overview of the tabletop game market. This metadata section can also be thought of as corollary to technical or administrative metadata.

#### Type and Genre

Genre is a general category that aims to capture what kind of tabletop game is being discussed. There are three types primarily discussed here, organized by their primary medium: board games, card games, and role playing games. Type can be thought of as sub-genre. This schema point vocabulary is contingent on the genre label and specifies more granularly what kind of game is being discussed in a play context. In other words, what is the style of the game. In board games, common styles include family, strategy, abstract, and so on. In card games styles include patience; in role playing games, dice rolling, storytelling.

### The Schema

This is the initial version of the schema, adopted largely from BBG and the VGMS. Metadata elements that align with DCMS are denoted with [DC:] and with VGMS, [VGMS:]. An asterisk indicates whether the element is required for the schema. Due to the limited scope of Dublin Core, multiple elements may be mapped to individual Dublin Core elements. For example, Play Space and Play Time both map to the Dublin Core element coverage.

* Mechanic* - The primary operation the player uses to overcome the obstacle(s) in the game. Multiple values can be recorded.
* Type* (sub-genre) [DC: type] - An attribute of Genre. This is the style of the gaming experience, given the genre designation.
* Genre* [DC: type] [VGMS: Gameplay Genre] - The general category of tabletop game. There are three accepted values: board game, card game, role playing game. These are not mutually exclusive categories and multiple values can be accepted.
* Theme* [DC: subject] [VGMS: Narrative Genre] - The theme of a game. This is the general story the game employs to allow a narrative of mechanics to play out.
* Title* [DC: title] [VGMS: Game Title]- The name of the game.
* Designer* [DC: creator] - The creator(s) of the game.
* Publisher [DC: publisher] - The entity responsible for the production and distribution of the game.
* Date* [DC: date] [VGMS: Retail Release Date] - The date the game was released or date the game was invented.
* Edition [DC: source] [VGMS: Version Information] - The print or version of a game.
* Rating - Crowdsourced from BBG. Scale 1-10. This is a dynamic value, so the rating in the schema may differ from the current BBG rating. Refer to the date of metadata creation.
* Game Rate (Difficulty/Complexity) - Crowdsourced from BBG. Scale 1-5. This is a dynamic value, so the rating in the schema may differ from the current BBG rating. Refer to the date of metadata creation.
* Language* [DC: language] [VGMS: Language] - The language the game components or instructions are written in.
* Intellectual Property* [DC: rights] - Specify whether the game is the intellectual property of the creator, publisher, or combination thereof.
* Community Site* [DC: identifier] - The equivalent of an “authority” site for board, RPG, or card games.
* Expansion [DC: relation] - Specify whether the game is an expansion on, and therefore contingent to, another game.
* Packaging Dimensions [DC: format] [VGMS: Packaging] - The size and weight of the game box or container.
* Number of Players [VGMS: Number of Players]. The number of players the game requires.
* Play Space [DC: coverage] - How much space an instance of playing a game will take, on average.
* Play Time [DC: coverage] - How much time an instance of playing a game will take, on average.
* Components* [DC: format] - The pieces necessary to play the game such as board, cards, dice, chips, etc. This element accepts multiple values.
* Description* [DC: description] [VGMS: Summary] - A description or account of a resource
* Notes [VGMS: Game Note] - Any other feature or characteristic of a game that is notable not covered in the other fields
* Artist [DC: contributor] - The artist of the game components.
* Award - Nominated and/or awards received.

### Controlled Vocabulary

Controlled vocabularies are important for ensuring that metadata contributors use the same language when crediting or editing metadata. The vocabulary in this schema is sourced from various communities as well as metadata schemas such as the VGMS and aspires to be incorporated back into those communities to increase harmony among descriptions of tabletop games. A controlled vocabulary also increases cohesive retrieval when searching and filtering. While the initial draft of this schema does not pretend to cover every possible mechanic or thematic descriptor in use, it does define a few in the hopes of setting a standard for future versions of controlled vocabulary. It is both important and difficult to define these controlled vocabulary: important due to the significant lack of previous scholarship in this domain; difficult due to the expansive vocabulary for describing games in the field as well as difficulties in defining terms of art (Donovan, Cho, Magnifico, & Lee, 2013).

#### Mechanic

* Deck Building - Players have a personal collection of cards or tokens that provide different actions and/or resources which are randomly drawn.
* Tile Placement - Players place pieces or tiles to shape the game board.
* Trick-taking - Commonly used in card games. Each player plays a card from their hand face up and all cards played constitute a trick, which is won by a player or team according to the rules of the game.
* Hand Management - Commonly used in card games. Cards played in a certain order or sequence will benefit the player.

#### Genre

* Board Game - A game that requires space for the components to be situated. Components are requisite for this genre, contrasting it from most RPG that do not require specific components (though they may to increase narrative).
* Card Game - A game that requires the use of the 52 card “French” deck of cards.
* Role Playing Game - A game that is typically played without components, but typically include dice as a decision tool. A persistent performative aspect is typical.

#### Type (Genre prerequisite)

* Strategy (board, card) - A game in which decision making skills have a high significance in determining the outcome; chance is often minimized.
* Party (board) - A game that encourages social interaction, typically by alluding to popular references and requiring lower amounts of skill as chance often plays a significant role. Can accommodate large groups.
* Storytelling (board, role-playing) - A game where the player crafts a story based on prompts or materials provided by the game. 

#### Theme

* Abstract - Typically without a theme, e.g. chess, go, most card games.
* Economic - Players to develop and manage a system of production, distribution, trade, and/or consumption of goods, simulating a market in some way.
* War - Modeled after conflict, simulating military actions.

#### Components

* Die - Object with multiple sides (typically 4-20), often with different values on different sides. Typically rolled for introducing probability as a mechanic.
* Chip - Counters of uniform weight and size but with different colors to represent different values.
* Meeple - Small token used in board games, from Carcassonne. Used to represent player occupation in the board game space.
* Token - Pieces used to designate areas or figures on a board.

### Use Case and Sample Record

As this schema is intended to be used by information professionals, such as catalogers, and researchers, it is important to make these objects searchable by multiple dimensions. For example, if games were to be included in a library’s catalog, a library patron looking for a short game to play with a friend might want to search for games that are two players and take less than 30 minutes to play. Similarly a researcher who is interested in military themed games that are modeled after the cold war released in the 2000s might query a games database for war and/or cold war themed games with a date range between 2000 and 2009. This schema accounts for both of these use cases.

For the following use case, the user was browsing the library for a quick board game for two players. The user could find this game on BoardGameGeek or find it via a library interface that searched Dublin Core:

#### Sample Record

* Mechanic* - Hand Management
* Type* (sub-genre) - Strategy
* Genre* - Board Game
* Theme* - Abstract
* Title* - Battle Line
* Designer* - Reiner Knizia
* Publisher - GMT Games
* Date* - 2000
* Edition - 1
* Rating - 7.4
* Game Rate (Difficulty/Complexity) - 1.91
* Language* - English
* Intellectual Property* - GMT Games
* Community Site* - https://www.boardgamegeek.com/boardgame/760/battle-line
* Expansion - no
* Packaging Dimensions - 
* Number of Players* - 2
* Play Space - 
* Play Time  - 30 minutes
* Components - 70 cards; 9 tokens
vDescription - Two opponents face off across a 'battle line' and attempt to win the battle by taking 5 of 9 flags or 3 adjacent flags. Flags are decided by placing cards into 3 card poker-type hands on either side of the flag (similar to straight flush, 3 of a kind, straight, flush, etc). The side with the highest 'formation' of cards wins the flag.
* Notes - 
* Artist -  Roland MacDonald, Rodger B. MacGowan, Mark Simonitch
* Award - 

### Future Directions

While sites like BoardGameGeek will likely remain the authority source for board games and is likely to field the largest number of queries, even from library users or researchers, this schema is an attempt at refining the search parameters and terms by introducing a schema and controlled vocabulary. The schema will also over time make searching for games in a library catalog possible by mapping onto the Dublin Core Metadata Schema and by extension MARC. Finally, this schema aspires to cover all tabletop games in order to unify the fractured authority sources between board games, card games, and role playing games. By pairing the AGMS with the VGMS, a more cohesive study and exploration of games as cultural artifacts can be explored. There is also an opportunity here for the creation of a Meta Game Metadata Schema in order to capture the unifying features of games.

This report is a preliminary survey of the existing analog game space. It suggests a definition of analog, or tabletop, games; notes which sources are the community authority figures within each defined analog game domain; provides a rudimentary metadata schema combined from Dublin Core, the Video Game Metadata Schema, and existing BoardGameGeek search parameters; and provides some sample controlled vocabulary definitions. Further work needs to be done with this schema including increasing the harmony between board game, card game, and role playing game terms, organization, and search techniques; engaging with analog gaming communities for their feedback and testing of the schema; and contacting the named authorities to see if larger discussions could be initiated around these efforts. Certain local communities could be leveraged for their input and participation including the UCLA Games Lab and the Information Studies Research Lab, as well as game stores local to Los Angeles.

### References

Analog Game Studies. (n.d.). Retrieved June 7, 2019, from Analog Game Studies website: http://analoggamestudies.org/

BoardGameGeek | Gaming Unplugged Since 2000. (n.d.). Retrieved June 7, 2019, from https://www.boardgamegeek.com/

Card Games. (n.d.). Retrieved June 7, 2019, from https://www.pagat.com/

Deines, Gill, Lincoln, & Clifford. (2018, February 7). Six Lessons Learned from Our First Crowdsourcing Project in the Digital Humanities. Retrieved June 7, 2019, from The Getty Iris website: http://blogs.getty.edu/iris/six-lessons-learned-from-our-first-crowdsourcing-project-in-the-digital-humanities/

DCMI: Dublin Core Metadata Element Set, Version 1.1: Reference Description. (n.d.). Retrieved June 7, 2019, from http://www.dublincore.org/specifications/dublin-core/dces/

Donovan, A., Cho, H., Magnifico, C., & Lee, J. H. (2013). Pretty as a pixel: issues and challenges in developing a controlled vocabulary for video game visual styles. Proceedings of the 13th ACM/IEEE-CS Joint Conference on Digital Libraries - JCDL ’13, 413. https://doi.org/10.1145/2467696.2467747Duffy, O. (2014, November 25). Board games’ golden age: sociable, brilliant and driven by the internet. The Guardian. Retrieved from https://www.theguardian.com/technology/2014/nov/25/board-games-internet-playstation-xbox
Nguyen, Christopher Thi. (forthcoming). Games: Agency as Art. Oxford University Press
Office, N. D. and M. S. (n.d.). MARC STANDARDS (Network Development and MARC Standards Office, Library of Congress) [Webpage]. Retrieved June 7, 2019, from https://www.loc.gov/marc/
Our Mission. (2014, October 5). Retrieved June 7, 2019, from Analog Game Studies website: http://analoggamestudies.org/about/our-mission/
Releases – GAMER Group. (n.d.). Retrieved June 7, 2019, from https://gamer.ischool.uw.edu/releases/
RPGGeek. (n.d.). Retrieved June 7, 2019, from https://rpggeek.com/
Suits, B. H. (1978). The grasshopper: games, life, and Utopia (1st ed). Edinburgh: Scottish Academic Press.
Video Game Metadata Schema. (2017). Retrieved from https://gamer.ischool.uw.edu/wp-content/uploads/2018/04/VGMSVersion4.0_20180824.pdf
XML Introduction. (n.d.). Retrieved June 7, 2019, from https://www.w3schools.com/XML/xml_whatis.asp
