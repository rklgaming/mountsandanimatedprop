# Mounts and Animated Props: Player and Admin Guide

How to ride mounts, wear animated props and ride your pet, everything admins can set in game, and every command.
Keys can be changed in game: **Settings > Key Bindings > FiveM**.

Versions this guide is for: **rklmounts 3.74.0**, model packs **rklflyingmounts 1.0.0**, **rklmountninja 1.0.18**,
**rklmountfantasyland 1.0.6**, **rklpet_ninjakirin**, and **rklanimatedprop 1.17.1**.

An interactive version with a searchable command table is in [`docs/index.html`](docs/index.html).

---

## What's new

### Admin, all in game
- `/mountadmin` has four tabs: **Players**, **Who rides what**, **Mounts** and **Shops**. Everything saves at once and stays after a restart.
- Give or take **VIP**, lock a whole mount or **single colours** to a player.
- Set each mount **Free**, **Item**, **VIP or item**, **VIP only** or **Off**, plus one "Mounts need their item" switch.
- **Mounts** tab: rename, turn on / off, set prices and ride numbers, add a new mount from a copy, with no config edits.
- **Shops** tab: place a mount shop where you stand; players walk up and press **E**.
- The prop Ledger (`/apadmin`) and Mount Admin are linked: a player's page shows their mounts, with "Open in /mountadmin".

### Mounts
- New prop mounts: the **Gale Fan** (a giant flying war fan) and the **Dune Disc** (a floating disc of sand). The broomstick, cloud and hoverboard were remade.
- The land horses and the donkey were remade and renamed: Ironclad Destrier, Elven Palfrey, Wayfarer Courser, Peddler's Donkey.
- The **Ninja Tortoise** swims, dives and surfaces in deep water and walks out in the shallows; on land SHIFT runs on its legs.
- The **Ninja Kirin** is the summoned Kirin itself (same model, same colours), rider on its saddle.
- No height limit when flying. Wings come off when you land. No particles on mounts.
- Smoother moves: gaits change without a snap, beasts back up and turn on the spot with their own steps, dragons keep their own wing beat, jumping beasts gather their legs, crouching riders sit right on heads and shells.
- Fixed: a rider who sometimes went invisible to other players.
- Taken off the mount list (nothing deleted, each can be turned back on): the bear, armored wolf, donkeyboost, the ten tailed beasts, the Spider, the Ants and the Frost Wolf, and the ped copies of the Amethyst Wolf / Void Kitsune / Starforged Golem.

### Pets and props
- **Riding your pet is one animal**: press **J** on your summoned pet and its mount stands on its spot; get off and the pet is right there, following you.
- `/petsummon` also calls back a pet mount you left far away.
- Every pet's mount is ridden through its pet (unless an admin sets "Normal mount too").
- The pet follows better: it stays on the ground on jumps and flights, joins you on a High Jump, really stays on Stay.
- Ten props are free for everyone. Shops and the Hall of Wonders show only what is for sale.

---

## For players

### Getting a mount
1. **Get it**: buy it at a mount shop (walk up and press **E**), use its item `mount_…`, or have it given by an admin. Some mounts are free for everyone. A mount's colours come with it, unless an admin gave you only some colours.
2. **Call it**: press **F6** (`/mountvip`) to open **My Mounts**: it lists every mount you can ride right now. Pick a colour, then **Ride**. You can also use the item. **Send back** in F6, or using the item again, puts it away.
3. **VIP keeps it**: a VIP player can press **Lock** in F6 to bind a mount from the bag to the character for good. A locked mount needs no item.
4. **Your pet's mount**: the ninja pets, dragons, gryphon, phoenix, wolf, kitsune and golem are ridden through their pet: summon the pet, then press **J**.

### Riding keys

| On land | | In the air | | In the water | |
|---|---|---|---|---|---|
| W A S D | move (the mount runs where the camera looks) | W / S | forward, back | W A D | swim, turn |
| tap Shift | trot (on / off) | A / D | turn | Left Ctrl | dive |
| hold Shift | run | Shift | climb (no height limit) | Shift | come up |
| Space | jump | Left Ctrl | go down | Space | boost |
| S | back up | mouse | look around | | |
| H | roar (dragons, beasts) | G | hover in place | | |
| E or F | get off | E | land | | |
| F on foot | send the mount away | | | | |

Mount screens: **F6** My Mounts, **J** ride your summoned pet, **F7** move / colour / hide the mount UI, **F9** hide or show all mount UI.

### Every mount
- **Land**: Ironclad Destrier, Elven Palfrey, Wayfarer Courser, Peddler's Donkey, Cougar, Panther, Stag, Ox, War Boar.
- **Beasts and ninja pets** (most ridden through their pet): Amethyst Wolf, Void Kitsune, Starforged Golem, Ninja Dog, Ninja Dog Scout, Ninja Cat, Ninja Ape, Ninja Toad, Ninja Serpent, Ninja Slug, Ninja Kirin, Ninja Tortoise (land and water).
- **Flying**: Blood Dragon (12 colours), Fantasy Dragon, Chinese Fantasy Dragon, Celestial Dragon, Gryphon Boss, Fantasy Phoenix, Ninja Falcon, Broomstick, Cloud, Gale Fan, Dune Disc.
- **Wings**: Angelic, Celestial, Demon, Fairy and Vampire wings.
- **Water**: Dolphin, Orca, Manta, Hammerhead, Tiger Shark.
- **Ground glide**: Hoverboard.

### Animated props and pets
1. **Wear props**: `/animatedprop` opens your **Regalia**: tails, wings, horns, pets and more. Equip, pick a colour, take it off. Using a prop item equips it; it stays safe in your Regalia while worn.
2. **Your pet**: `/petmenu` shows your pet's moves, **Stay**, **Roam** and **Stop**. `/petsummon` calls your pet out at full size or sends it back to your shoulder.
3. **Ride your pet**: summon it, press **J**: its mount stands where the pet stood. Get off and your pet is right there again, following you. Left its mount far away? `/petsummon` calls it back.
4. **Prop moves**: `/apflare`, `/apswish`, `/apshake`, `/apflick` play a move on the prop you wear, when it has that move.

---

## For admins

### `/mountadmin`
- **Players**: search a player online by name or #id. Give or take **VIP Stable**; for every mount, **Lock to them** (every colour) or **Take back**; **Colours** gives single colours. "In their bag" and "Locked to them" show what they already have.
- **Who rides what**: each mount gets a mode. One switch for "Mounts need their item". A pet's mount has **Normal mount too** (on = it can also be ridden without its pet). Search, then "Set every mount shown to…" changes many at once.

  | Mode | Who rides it |
  |---|---|
  | Free | everyone |
  | Item | needs its item (default) |
  | VIP or item | VIP without the item, others with it |
  | VIP only | VIP only; the item alone is not enough |
  | Off | nobody; the item is kept |

  A mount locked to a player always works for them, unless it is Off.
- **Mounts**: every mount on one list: On / Off, its name, shop price and its ride numbers (speed, boost, climb, walk / run, top speed, stamina, jump). **Back to config** undoes a row. **Add a mount** makes a copy under a new name with an existing model.
- **Shops**: **Add a shop where you stand** and name it. Per shop: On / Off, Move here, Go there, Delete (click twice), the stable hand, the map icon, and what it sells (every mount on sale, or chosen mounts).

Every change is logged in the server console, and the player is told.

### Props: `/apadmin`
The **Steward's Ledger**: give a prop (as an item or as access, for a time), activate a pet's mount, **Holders** (who has what, offline too), VIP tiers, permissions, shops, the Showroom and the log. `/apfit` opens the Fitting Bench.

### Tuning
`/mountdev` is the full live editor for a mount (speeds, jump height, seats, camera), saved for every player. `/mountfit` measures a mount's height on the ground again.

**Who counts as an admin**: for mounts, the ACE `rklmounts.admin` or the groups admin, superadmin, god, owner. For props, the roles in the Ledger's Permissions tab.

---

## Server setup

Everything starts with `ensure [rkl]`. Keep these folders together:

```
resources/[rkl]/[mounts models]/rklmounts            the mount script (land + prop mounts inside)
resources/[rkl]/[mounts models]/rklflyingmounts      dragons, gryphon, phoenix, wings
resources/[rkl]/[mounts models]/rklmountninja        the ninja pet mounts
resources/[rkl]/[mounts models]/rklmountfantasyland  wolf, kitsune, golem
rklpet_ninjakirin  (with the pet packs)              the Kirin: pet, summon and mount
resources/[rkl]/[animatedprops]/rklanimatedprop      props + pets, with its addon packs
```

- If a model pack is missing, the server says so at start and those mounts cannot be called.
- Do not run the old `rklmountdragons`, `rklmountfantasyfly` or `rklmountwings` next to `rklflyingmounts` (the same models twice).
- What admins set in game lives in `rklmounts/data/`: `mounts.json`, `mount_rules.json`, `shops.json`, `mount_overrides.json`. Back these up with the server.
- VIP and mount locks are in the database table `awaken_vip_perks` (oxmysql).
- After an update, restart the changed resources (or the server).

---

## All commands

| Command | Who | What it does | Script |
|---|---|---|---|
| F6 · `/mountvip` | Player | My Mounts: every mount you can ride now, colour, ride, send back, VIP lock | Mounts |
| E at a mount shop | Player | Open that shop's window and buy a mount | Mounts |
| J · `/ridepet` | Player | Ride your summoned pet | Mounts |
| F7 · `/rklmountsui` | Player | Mount UI settings | Mounts |
| F9 · `/rklmountshide` | Player | Hide or show all mount UI | Mounts |
| `/animatedprop` | Player | Regalia: wear tails, wings, horns, pets | Props |
| `/petmenu` | Player | Your pet: moves, Stay, Roam, Stop | Props |
| `/petsummon` | Player | Summon your pet, send it back, or call back a pet mount left far away | Props |
| `/apflare` `/apswish` `/apshake` `/apflick` | Player | Play that move on the prop you wear | Props |
| `/mountadmin` | Admin | Mount Admin: Players, Who rides what, Mounts, Shops | Mounts |
| `/mountgrant <id> <mount \| colour \| vip> [off]` | Admin | Lock a mount, one colour or VIP to a player (console too) | Mounts |
| `/mountdev` | Admin | Live mount editor | Mounts |
| `/mountfit [reset \| off \| on]` | Admin | Measure a mount's height on the ground again | Mounts |
| `/mountdebug` · `/findanims [dict]` | Admin | Debug | Mounts |
| `/apadmin` | Admin | Steward's Ledger | Props |
| `/apfit` | Admin | Fitting Bench | Props |
| `/apdebug` | Admin | List every spawned prop in F8 | Props |
| `apgive <id> <prop> [colour \| all]` | Console / ACE | Give a prop item | Props |
| `apgiveall <id> [category \| all]` | Console / ACE | Give every design of a category | Props |
| `apgrant <player> <scope> [minutes] [colour]` | Console / ACE | Give access to a prop without an item | Props |
| `aprevoke <player> <scope>` | Console / ACE | Take that access back | Props |
| `apvip <player> <tier \| remove> [days]` | Console / ACE | Prop VIP tier | Props |
| `apaccess [scope] [preset]` | Console / ACE | Who may wear a prop, family or category | Props |
| `aproles [reset]` · `aplog [count]` · `apshop [reset]` | Console / ACE | Roles, log, prop shops | Props |
| `apitems [json]` · `apaddons` · `apfitexport` | Console / ACE | Item list, found addons, fit export | Props |

Console commands are typed in the server console (txAdmin) without the slash, or in game by staff with the ACE `command.<name>`.
