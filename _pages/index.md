---
layout: page
title: Home
id: home
permalink: /
---



<p style="padding: 3em 1em; background: #505050; border-radius: 4px;">
  Welcome to Cloudspire.
</p>

![whisper.jpg](/assets/whisper.jpg)


<strong>Recently updated notes</strong>

<ul>
  {% assign recent_notes = site.notes | sort: "last_modified_at_timestamp" | reverse %}
  {% for note in recent_notes limit: 5 %}
    <li>
      {{ note.last_modified_at | date: "%Y-%m-%d" }} — <a class="internal-link" href="{{ note.url }}">{{ note.title }}</a>
    </li>
  {% endfor %}
</ul>

# Table of Contents:


## Characters
### PCs
- [[Marcel Bellinar (Carillon) - Erin]]
- [[Markus Euler (Bookmark) - Nick]]
- [[Marlo Savrim (Mist) - Carly]]
### NPCs
- [[Antony Murano]]
- [[Caz Mallock]]
- [[Declan Scheer]]
- [[Esme]]
- [[Flint]]
- [[Gina Batello]]
- [[Kira]]
- [[Passh Velkin]]
- [[Quellyn]]
- [[Teclum Forrester]]
- [[Three Clovers]]
- [[Tia Balsam]]

## Districts
- [[Bedrock]]
- [[Centre City]]
- [[Coinpurse Alley]]
- [[Glitterpeak]]
- [[Mendar Lake]]
- [[Raptor’s Talon]]
- [[Sparrow’s Landing]]
- [[The Basin]]
- [[The Roost]]
- [[The Summit]]

## Locations
- [[Crow's Nest]]
- [[Emberglow Station]]
- [[Factotum Institute]]
- [[Talon Hotel]]
- [[The College]]
- [[The Mines]]
- [[The Press]]

## Factions

### Institution
- [[Blood Imports]]
- [[City Council]]
- [[College of Lightning]]
- [[Dagger Isles Consulate]]
- [[Firelight Brigade]]
- [[Imperial Military]]
- [[Iruvian Consulate]]
- [[Lesser Nobility]]
- [[Ministry of Preservation]]
- [[Severosi Consulate]]
- [[Skovlan Consulate]]
- [[The Diamond Dogs]]
- [[The Island]]
- [[The Vultures]]
### Labor & Trade
- [[Bargers]]
- [[Cabbies]]
- [[Ink Rakes]]
- [[Local 251]]
- [[Rail Jacks]]
- [[The City Planners]]
- [[The Marketiers]]
- [[The Merchant’s Guild]]
- [[The Mesmer Institute]]
- [[The Refinery]]
### The Fringe
- [[Company of the Diving Bell]]
- [[Cult of the Rising Sun]]
- [[Doppelgängers]]
- [[The Rapturous Chord]]
- [[Rent-a-Haunt]]
- [[Spelunkers United]]
- [[The Drowned]]
- [[The Great Hunt]]
- [[The Unseen]]
- [[The Waking Dream]]
### Underworld
- [[Arbuckle & Associates]]
- [[Factum Factotum]]
- [[Lock & Key]]
- [[Lone Star Brigade]]
- [[Pigeon]]
- [[Rogue’s Gallery]]
- [[The Dregs]]
- [[The Fortune Tellers]]
- [[The Red Sashes]]
- [[The Vault]]
- [[The Wing Shades]]
- [[Tycherosi Consulate]]



<style>
  .wrapper {
    max-width: 46em;
  }
</style>
