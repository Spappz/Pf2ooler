# Changelog

## 1.13.0 _Big Data_ edition
- Allow `/lookup` commands to return *even more* results, offering a random selection (exact matches prioritised) unless there's a truly staggering number
- Update `/view help` and `/view licenses` text
- (Pf2eTools) Added *Curtain Call Player's Guide*
- (Pf2eTools) Added *Lost Omens: Highhelm*
- (Pf2eTools) Added *Wardens of Wildwood* #1–2
- (Pf2eTools) Typos

### 1.12.1
- (Pf2eTools) Added *A Few Flowers More*
- (Pf2eTools) Added *Absalom: City of Lost Omens*
- (Pf2eTools) Added *Blood Lords Player's Guide*
- (Pf2eTools) Added *Dinner at Lionlodge*
- (Pf2eTools) Added *Gatewalkers #2: They Watched the Stars*
- (Pf2eTools) Added *Malevolence*
- (Pf2eTools) Added *Mark of the Mantis*
- (Pf2eTools) Added *Quest for the Frozen Flame Player's Guide*
- (Pf2eTools) Added *Rusthenge*
- (Pf2eTools) Added *Season of Ghosts #4: To Bloom Below the Web*
- (Pf2eTools) Added *Shadows at Sundown*
- (Pf2eTools) Added *Stolen Fate Player's Guide*
- (Pf2eTools) Added *The Enmity Cycle*
- (Pf2eTools) Typos

## 1.12.0 _Length Contraction_ edition
- Allow the bot to display at least _some_ of a statblock, even if the whole thing's too long for Discord's API
- Make `/lookup` commands always show all matches, even if the results are identically named
- (Pf2eTools) Added *Lost Omens: Tian Xia World Guide*
- (Pf2eTools) Added *Season of Ghosts #3: No Breath to Cry* 
- (Pf2eTools) Added *Wake the Dead* comics #1–5
- (Pf2eTools) Typos

### 1.11.1 _Snake Eyes_ edition
- Fix rendering of creatures' context-specific skill modifiers
- Some more improvements behind the scenes on the dice-interpreter
- (Pf2eTools) Lots of new content added!
  - *Season of Ghosts Player's Guide*
  - *Season of Ghosts #1: The Summer That Never Was*
  - *Season of Ghosts #2: Let the Leaves Fall*
  - *Seven Dooms for Sandpoint Player's Guide*
  - *Wardens of Wildwood Player's Guide*
- (Pf2eTools) Typos

## 1.11.0 _Getting Dicey_ edition
- `/roll` commands made with the `secret:Spoilered` option are now *even more* secret, as die-rolls are now padded to fill the same space (caveats for expressions with 'die-replacing' modifiers, such as `1d6rr<3` and `1d20min10`)
- `/roll check`'s `modifiers` option now supports comma-separated lists (e.g. `/roll check modifiers:10,-3,2d4+1`)
- Fix rare bug where `/roll` responses with high `count`s would get cut-off half-way through
- (Pf2eTools) Typos

### 1.10.3
- Display an error message when dice-group notation (e.g. `{1d4,2d6}`) is attempted, rather than just crashing (support coming Soon™)

### 1.10.2
- Make the `/roll table` command actually work as expected rather than just picking a random row (a bit experimental—please tell me if there's bugs!)

### 1.10.1
- (Pf2eTools) More *Rage of Elements* content
- (Pf2eTools) *Player Core* spells and rituals
- (Pf2eTools) Typos

## 1.10.0 _Still Alive_ edition
- Datatype and level, where pertinent, has been moved to the top of the `/lookup` embed
- Fixed a variety of minor display issues
- Improved a variety of internal processing workflows
- (Pf2eTools) Lots more content! *Treasure Vault*, *Rage of Elements* (feats only), *Gatewalkers*, various modules and one-shots...
- (Pf2eTools) Many, many typos

### 1.9.2
- Fixed an extremely minor 'code' injection exploit

### 1.9.1
- Stop the update script from overwriting the new v1.9.0 emojis so you can actually see them 🥲
- (Pf2eTools) Typos

## 1.9.0 _All Spruced Up_ edition
- Add `/lookup creature summary` command, which shows a summary (wow!) of the creature's statblock. *Note:* This command will be superseded by `/lookup creature statblock`, once it's ready, and its current function will change to fill a new niche.
- Split out `/lookup` commands' "!random" option into their own `/random` commands (warned you!)
- Fixed 'Amp' text not appearing on psychic spells
- Fixed 'Duration' text on rituals sometimes not rendering properly
- Improved action emojis (no more squished-up 3-action symbol!)
- Started copying specifically relevant Pf2eTools changelog entries into the Pf2ooler changelog (for people that follow Pf2ooler but not Pf2eTools)
- (Pf2eTools) Added missing creature images for converted sources
- (Pf2eTools) Typos

### 1.8.1
- Fixed Range entries reporting in units of "feets"
- (Updated to latest Pf2eTools data)

## 1.8.0 _All Kitted Out_ edition
- Added `/lookup item statblock` command (only for 'base' weapons, armour, and shields so far; adventuring gear and magic items coming Soon™)
- Added new `secret` option value to certain `/roll` commands to allow the result to be posted publicly, but with all dice and totals spoilered
- Hid some entity-counts from `/view stats` because we've run out of space in the embed!
- Improved error messages
- (Updated to latest Pf2eTools data)

### 1.7.3
- Fixed incorrectly rendering variable tags

### 1.7.2
- Fixed `successDegree` rendering bug

### 1.7.1
- (Updated to latest Pf2eTools data)

## 1.7.0 _Assisting Bot_ edition
- Added `/lookup creature image` command
- Afflictions now show 'Tempted Curse' text
- Fixed some miscellaneous rendering bugs
- (Updated to latest Pf2eTools data)

## 1.6.0 _Lucky Dip_ edition
- Moved `/lookup weapon group` command to `/lookup item group` because I only just realised that armour groups also exist (the command always let you do this but I was simply too :galaxyBrain: to notice)
- Moved `/roll critical` command group to `/draw critical` because I can't just decide things just once
- Added `/draw hero point` command
- Added `/lookup relic gift` command
- Added the ability to 'roll' for a random entity by using the name "!random" on any `/lookup` command (will this morph into its own command one day? Who knows!)
- Expanded the `/lookup` embed footers to list source's full name, rather than just abbreviation
- The bot's activity (the "Playing ..." line on its profile) now slowly cycles around random Paizo adventure paths and modules and whatnot
- Added Skill text on `/lookup action` embeds
- Made it onto Discord's app directory 🥳
- (Updated to latest Pf2eTools data)

### 1.5.1
- Fixed spell duration rendering

## 1.5.0 _Critical Maintenance_ edition
- Added some [documentation](https://github.com/Spappz/Pf2ooler/wiki/List-of-commands)!
- Added `/lookup event` command
- Added `/lookup familiar ability` command
- Added basic `/roll table` command while I figure out how to handle weird tables
- Added `/roll critical hit` and `/roll critical fumble` commands
- Got verified by Discord 🥳
- (Updated to latest Pf2eTools data)

## 1.4.0 _Command Structure_ edition
- Added `/lookup deity statblock` and `/lookup deity intercession`
- Moved `/lookup avatar` to `/lookup deity avatar` (trio complete!)
- Moved `/lookup ability` to `/lookup creature ability` (`/lookup creature statblock` coming Soon™)
- Moved `/lookup group` to `/lookup weapon group` (`/lookup weapon anything_else` coming never)

### 1.3.3 _Sod's_ edition
- Fixed count option not working in the `/roll commands`
- (Updated to latest Pf2eTools data)

### 1.3.2 _RIP Eris_ edition
- Fixed rendering bug where lists and new paragraphs weren't indented properly in especially long embeds
- Fixed rendering bug with `/lookup spell` heightened blocks having inconsistent indentation
- Improved `/lookup` formatting when multiple matches are found to also show source when relevant
- Fixed rare `/lookup` error when multiple partial matches have identical names
- Boolean options (e.g. the ubiquitous `secret`) now show 'Yes' as a choice instead of 'True' (more fitting given the description is posed as a question)

### 1.3.1 _@​Surge Protection_ Edition
- Fixed render typo in `/lookup action` (spurious activity insertion)
- Fixed render typo in `/lookup affliction` (improper bolding)
- Fixed render typo in `/lookup avatar` (missing speed text)

## 1.3.0
- Add /lookup ancestry command (😮)
- Add /lookup heritage command (😱)
- Add /lookup avatar command (🤯)

### 1.2.1
- Fixed extremely rare formatting error

## 1.2.0
- Remove the ability to select false in a command's `secret` option: if you want to show the result publicly, just leave the option blank
- Add `/lookup affliction` command to look up afflictions (gasp! 😱)
- Add rudimentary `/lookup class` command to look up basic class data (sidebar stuff; nothing yet from the feature table)
- Add `/lookup subclass` command to look up the class options you choose at level 1 (the longer ones, like oracles' mysteries, look pretty bad so suggestions welcome!)
- Added note to `/help` about `/lookup commands` not needing full names
- Make `/stats` look a little nicer and respond minutely quicker
- (Updated to latest Pf2eTools version)

## 1.1.0
- Added `/lookup ritual`
- Fixed bug that prevented the bot from responding to commands fired in DMs

## 1.0.0
- i exist lmao
