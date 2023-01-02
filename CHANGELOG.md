# Changelog

### 1.7.1
- (Updated to latest Pf2eTools data)

## 1.7.0 _Assisting Bot_ edition
- Added `/lookup creature image`
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