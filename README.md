<div align="center">

# BackFlash

<img width="600" alt="backflash" src="https://github.com/user-attachments/assets/2536b380-6852-4c55-8250-b81e33dcff67" />

### You know *what* happened. But do you know *when*?

**iPhones, moon landings, Pac-Man, the French Revolution -- one timeline, no mercy.**

**[Play now -- no install, no account, no excuses](https://lukeswitz.github.io/BackFlash/)**

</div>

---

## What is BackFlash?

The game starts immediately. One event is already on the timeline. Cards appear one at a time -- each from a different category -- and you drag them into the right spot. That's it.

The trick: you never know what's next. A video game console, then a war, then a TV show premiere. You're inferring dates from context clues in the event description alone.

---

## How to Play

1. Game starts instantly -- no menus, no setup
2. One anchor event is pre-placed on the timeline
3. A new event card appears at the top -- drag it to where it belongs
4. Green pulse = correct. Red shake = it snaps to the right spot
5. 8 cards to place. Try to get them all right
6. Hit **New game** anytime for a fresh set

---

## What Kind of Events?

Every game pulls from a massive pool of 4,700+ events across dozens of categories:

**Tech** -- iPhone, Google, ChatGPT, Bitcoin, Wi-Fi, Windows 95, World Wide Web

**Gaming** -- Atari 2600, Game Boy, PlayStation, Minecraft, Pac-Man, Fortnite

**Movies** -- Star Wars, Jurassic Park, The Matrix, Frozen, The Godfather

**TV** -- Seinfeld, Breaking Bad, Game of Thrones, Sesame Street, Squid Game

**History** -- Moon landing, Berlin Wall falls, D-Day, Declaration of Independence

**Science** -- Penicillin, DNA double helix, CRISPR, Higgs boson, Theory of Relativity

**Sports** -- First Super Bowl, FIFA World Cup, Miracle on Ice, Wimbledon

**Brands** -- Coca-Cola, McDonald's, LEGO, Nike, Starbucks, Tesla, SpaceX

**Music** -- Woodstock, MTV, Thriller, Coachella, Beastie Boys, Pink Floyd

**Landmarks** -- Statue of Liberty, Golden Gate Bridge, Sydney Opera House

Events are dynamically generated with proper phrasing -- "**Seinfeld** premieres on television", "**LEGO** is founded", "**Berlin Wall falls**" -- not just flat labels.

No two consecutive cards share a category. Items spread across eras. No repeats across games.

---

## Under the Hood

One HTML file. No frameworks. No build step. No backend. No telemetry. No accounts.

Event data sourced from [WikiTrivia](https://github.com/tom-james-watson/wikitrivia) (MIT licensed, Wikidata-derived) plus 220+ hand-curated bonus events. Event descriptions are dynamically generated from category and date-property metadata. All years are regex-stripped from descriptions so you can't cheat.

---

## Run it Locally

```bash
open index.html
```

Needs internet for the initial data fetch from GitHub. After that, games are instant.

---

<div align="center">

*You know the names. Now prove you know the order.*

**[Play BackFlash](https://lukeswitz.github.io/BackFlash/)**

</div>
