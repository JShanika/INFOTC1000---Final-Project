# INFOTC1000-Final-Project
Info. Tech. 1000 Final Project done in Markdown

>Project Details: For this project, I will be transcribing my notes for a [**Dungeons and Dragons**][D&D] campaign that I run with my friends. I have plans to make these notes into a personal web page at some point with [**HTML**][HTML] and [**JavaScript**][JS]. This will allow me to query the notes, as well as perform functions during gameplay that will make my note taking, and running the game, smoother/easier.
>
>There will be pages in this repository dedicated to some of the basic rules I use in **Dungeons and Dragons**, _a.k.a_ "[**D&D5E**][D&D]", as well as pages used to display maps, characters, history, and items relevant to the custom world I have created for my group of players.

![DND5E Logo][Logo]

## Repository Contents
- [**D&D5E Rules**][Rules]
  - Ability Scores
  - Dice Rules
  - Races
  - Classes
  - Conditions
  - Equipment
  - Spells
  - Beastiary
- [**Lore**][Lore]
  - Creation Myth
  - Timeline
  - Planes of Existence
  - Dieties
- [**Maps**][Maps]
  - Tallahs
  - Di'oa
  - Serenis
- [**NPCs**][NPCs]
  - Lawful
  - Chaotic
  - Good
  - Evil
  - Neutral
- [**PCs**][PCs]
  - Griffith Paccino
  - Spike Lee
  - Arpunis "Space Marine"
  - Uther Farsailor
  - Thok
  - Danger _(dead)_
  - Rogar
- [**Items**][Items]
  - Magic Items
  - Quest Items
  - Misc.
- [**Tallahs Campaign Logs**][Logs]
  - Session 01
  - Session 02
  - Session 03
  - Session 04
  - Session 05
  - Session 06
  - Session 07
  - Session 08
  - Session 09
  - Session 10
  - Session 11
  - Session 12
  - Session 13

## The Future of This Repository and Code Application

>My hope is that eventually I will be able to organize these notes with code, like [**JavaScript**][JS] and [**jQuery**][JQuery] on an [**HTML**][HTML] Web Server, so that I may quickly find things I am searching for mid-game session and change them according to my players interactions with my world in real time. A long-term goal of mine is to utilize what I have learned in Software Engineering to design and create an application to run along side these notes on the server that my players can use to keep track of their character information. They should be able to view all of their character information like equipment, stats, and personal notes. Along with this character sheet tracker, I want to be able to display relavant images, and isometric maps for any combat or roleplay situation they may find themselves in. When displaying a combat scenario to the players I want the application to track combat and aid in speeding up players turns. [**This API**][API] is one of many I have found that could aid in quickly requesting specific rulesets and official content from [**D&D5E**][D&D].

#### Example API Data of the Spell [**Acid Arrow**][ExSpell]

```
HTTP 200 OK
Allow: GET, HEAD, OPTIONS
Content-Type: application/json
Vary: Accept

{
    "count": 321,
    "next": "https://api.open5e.com/spells/?format=api&page=2",
    "previous": null,
    "results": [
        {
            "slug": "acid-arrow",
            "name": "Acid Arrow",
            "desc": "A shimmering green arrow streaks toward a target within range and bursts in a spray of acid. Make a ranged spell attack 
            against the target. On a hit, the target takes 4d4 acid damage immediately and 2d4 acid damage at the end of its next turn. On a miss, 
            the arrow splashes the target with acid for half as much of the initial damage and no damage at the end of its next turn.",
            "higher_level": "When you cast this spell using a spell slot of 3rd level or higher, the damage 
            (both initial and later) increases by 1d4 for each slot level above 2nd.",
            "page": "phb 259",
            "range": "90 feet",
            "components": "V, S, M",
            "material": "Powdered rhubarb leaf and an adder's stomach.",
            "ritual": "no",
            "duration": "Instantaneous",
            "concentration": "no",
            "casting_time": "1 action",
            "level": "2nd-level",
            "level_int": 2,
            "school": "Evocation",
            "dnd_class": "Druid, Wizard",
            "archetype": "Druid: Swamp",
            "circles": "Swamp",
            "document__slug": "wotc-srd",
            "document__title": "Systems Reference Document",
            "document__license_url": "http://open5e.com/legal"
        }
}
```




[Rules]: DND5E_Rules.md "D&D 5E Rules"
[Lore]: Lore.md "Lore"
[Maps]: Maps.md "Maps"
[NPCs]: NPCs.md "NPCs"
[PCs]: PCs.md "PCs"
[Items]: Items.md "Items"
[Logs]: SessionLogs.md "Logs"
[Logo]: 5e_backgrounds.png "D&D Logo"
[ExSpell]: https://api.open5e.com/spells/?format=api "Example Spell"
[HTML]: https://en.wikipedia.org/wiki/HTML "HTML Wiki"
[JS]: https://www.javascript.com/ "JavaScript"
[JQuery]: https://jquery.com/ "JQuery Homepage"
[D&D]: https://dnd.wizards.com/ "Dungeons and Dragons"
[API]: https://api.open5e.com/?format=api "D&D 5E API"
