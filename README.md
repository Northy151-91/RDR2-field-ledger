# RDR2 Field Ledger

RDR2 Field Ledger is a mobile-first companion app for **Red Dead Redemption 2 Story Mode**.

It is designed to make hunting, crafting, recipe tracking, camp upgrades, Trapper progress, Talismans, animal locations, and horse hunting easier to manage from a phone while playing.

The app is intentionally lightweight, offline-friendly, and does not require an account or backend server.

## Features

### Dashboard
Quick overview of:

- Trapper progress
- Camp upgrade progress
- Talismans and Trinkets
- Recipes learned
- Active Hunt List
- Pinned objectives

Dashboard cards link directly to their relevant sections.

### Hunt List
Build a custom hunting checklist by selecting:

- an animal
- a crafting category

For example:

**Beaver → Camp**

will add only Beaver-related materials required for Pearson/Camp crafting.

Hunt List quantities can be updated as materials are collected, and completed requirements automatically disappear from the active list.

Tapping a material shows the crafts that require it and whether those crafts are complete.

### Trapper
Track Trapper clothing, saddles, accessories, and garment requirements.

Features include:

- material requirement popups
- individual material checklists
- completion tracking
- garment-set filtering
- story progression filtering
- favourites / pinned items

### Camp / Pearson
Track:

- Satchel upgrades
- Camp cosmetic upgrades
- Pearson crafting requirements

Each craft has an expandable material checklist.

### Talismans & Trinkets
Track Fence-crafted Talismans and Trinkets including:

- required legendary animal parts
- jewellery and special items
- crafting costs
- permanent bonuses
- completion status

### Recipe Guide
Recipes are treated as reusable reference information rather than single-use objectives.

Categories include:

- Cooking
- Tonics
- Ammo & Weapons
- Hunting
- Horse Care

Recipes can be marked as **Learned** to track recipe/pamphlet progression without treating the recipe itself as completed.

### Animal Guide
Animal entries include practical hunting information such as:

- best hunting locations
- region
- useful time of day
- habitat
- behaviour
- bait usefulness
- recommended clean-kill weapon
- spawn-reset advice
- warnings and hunting tips
- related Trapper, Camp and Talisman requirements

The goal is to provide useful hunting routes rather than list every possible random spawn.

### Horse Finder
Includes wild, encounter-based, and stable-only horses.

Horse entries can include:

- breed and coat
- acquisition type
- best wild spawn location
- stable location
- story progression requirement
- useful time-of-day information
- purchase price
- base Health
- base Stamina
- base Speed
- base Acceleration
- Handling type

Horse stats are intended to represent base horse stats before bonding, saddle, and stirrup bonuses.

### Favourites
Crafts, recipes, and horses can be pinned for quick reference.

### Progress Storage
Progress is stored locally in the browser.

No account or online database is required.

This includes:

- craft completion
- recipe learned status
- Hunt List progress
- favourites
- collected material quantities

## Backup

The app includes:

- Export progress
- Import progress
- Copy progress summary

Because progress is stored locally, exporting a backup is recommended before:

- changing phones
- clearing browser data
- changing browsers
- reinstalling the app

## Mobile First

The interface is designed primarily for phone use.

Features include:

- large touch targets
- thumb-friendly bottom navigation
- full-width mobile cards
- large slide-up detail panels
- safe-area support for modern phones
- extra bottom scrolling clearance above navigation buttons
- responsive tablet/desktop layout

## Design

The visual style is inspired by the feel of Red Dead Redemption 2 without copying game artwork.

The interface uses:

- parchment tones
- leather browns
- muted brass
- restrained burgundy accents

The goal is to feel like a field ledger or hunting journal rather than a modern spreadsheet.

## Offline Use

RDR2 Field Ledger is built as a lightweight Progressive Web App (PWA).

Once hosted over HTTPS, it can be installed on supported phones and used like a standalone app.

The core tracker can work offline after the application has been cached.

## Installation

Once the app is hosted:

### Android / Chrome

1. Open the app website.
2. Open the browser menu.
3. Select **Install app** or **Add to Home screen**.

### iPhone / Safari

1. Open the app website.
2. Tap **Share**.
3. Select **Add to Home Screen**.

## Data Privacy

RDR2 Field Ledger does not require:

- user accounts
- analytics
- advertisements
- cloud storage
- tracking services

Checklist and progress data remains in the browser's local storage unless the user exports it manually.

## Planned Development

Planned improvements include:

- Full RDR2 Story Mode animal compendium
- Zoologist / Skin Deep tracking
- Expanded animal species filters
- Birds, reptiles, amphibians and fish
- Legendary animal entries
- Guarma animals
- More detailed horse coat information
- Additional progression filters
- Improved global search
- Further mobile interface refinements

## Scope

This project is focused on **Red Dead Redemption 2 Story Mode**.

Red Dead Online content is not currently part of the tracker.

## Disclaimer

RDR2 Field Ledger is an unofficial fan-made companion project.

Red Dead Redemption, Red Dead Redemption 2, Rockstar Games, and associated names and trademarks are property of their respective owners.

This project is not affiliated with or endorsed by Rockstar Games or Take-Two Interactive.
