<div align="center">

# ✦ Mounts & Props ✦
### *A rider's codex*

How to ride mounts, wear animated props and ride your pet, all that admins can set in game, and every command.

**[Open the illustrated guide](https://rklgaming.github.io/mountsandanimatedprop/)** &nbsp;·&nbsp; every key can be changed in *Settings › Key Bindings › FiveM*

</div>

---

## I · What's new

**Admin, all in game**
- `/mountadmin` has four tabs: **Players**, **Who rides what**, **Mounts** and **Shops**. Saved at once, kept after a restart.
- Pick a player and give them exactly the mounts (or single colours) they may ride.
- **Assigned only** *(new)*: a mount only for the players it was given to. VIP alone is not enough.
- Rename mounts, turn them on or off, set prices and speeds, add a new mount from a copy.
- Place mount shops where you stand; players walk up and press **E**.

**Mounts**
- New: the **Gale Fan**, a giant flying war fan, and the **Dune Disc**, a floating disc of sand. The broomstick, cloud and hoverboard were remade.
- The horses and the donkey remade: Ironclad Destrier, Elven Palfrey, Wayfarer Courser, Peddler's Donkey.
- The **Ninja Tortoise** swims, dives and runs on its legs; the **Ninja Kirin** is the summoned Kirin itself.
- No height limit in the sky. Wings come off when you land.
- Smoother moves everywhere; a rider no longer goes invisible to others.

**Pets & props**
- Your pet and its mount are one animal: **J** on your summoned pet, and when you get off it is right there.
- `/petsummon` calls back a pet mount left far away.
- The pet follows better on jumps, flights and Stay.
- Ten props are free for everyone. Shops show only what is for sale.

---

## II · Getting a mount

1. **Earn it**: buy it at a mount shop (walk up, press **E**), use its item, or receive it from an admin. Some mounts are free for all. Its colours come with it, unless you were given only some.
2. **Call it**: press **F6** (`/mountvip`) for **My Mounts**: every mount you may ride right now. Pick a colour, then **Ride**. **Send back** puts it away.
3. **Keep it**: a VIP can press **Lock** in F6 to bind a mount from the bag to the character for good.
4. **Your pet's mount**: the ninja pets, dragons, gryphon, phoenix, wolf, kitsune and golem are ridden through their pet: summon it, then press **J**.

---

## III · Riding keys

| On land | | In the sky | | In the water | |
|---|---|---|---|---|---|
| W A S D | ride where the camera looks | W / S | forward, back | W A D | swim, turn |
| tap Shift | trot | A / D | turn | Left Ctrl | dive |
| hold Shift | gallop | Shift | climb, no limit | Shift | surface |
| Space | leap | Left Ctrl | descend | Space | surge |
| S | step back | mouse | look around | | |
| H | roar | G | hover in place | | |
| E / F | dismount | E | land | | |
| F on foot | send it away | | | | |

Screens: **F6** My Mounts · **J** ride your pet · **F7** arrange the mount UI · **F9** hide the mount UI

---

## IV · Every mount

- **Steeds of the land**: Ironclad Destrier, Elven Palfrey, Wayfarer Courser, Peddler's Donkey, Cougar, Panther, Stag, Ox, War Boar
- **Beasts & ninja pets**: Amethyst Wolf, Void Kitsune, Starforged Golem, Ninja Dog, Dog Scout, Cat, Ape, Toad, Serpent, Slug, Kirin, and the Ninja Tortoise (land and sea)
- **Wings of the sky**: Blood Dragon in twelve colours, the Fantasy, Chinese Fantasy and Celestial Dragons, Gryphon Boss, Fantasy Phoenix, Ninja Falcon, Broomstick, Cloud, Gale Fan, Dune Disc
- **Wings, tides & glide**: Angelic, Celestial, Demon, Fairy and Vampire wings · Dolphin, Orca, Manta, Hammerhead, Tiger Shark · Hoverboard

---

## V · Props & pets

1. **Wear props**: `/animatedprop` opens your **Regalia**: tails, wings, horns, pets and more. Equip, pick a colour, take it off.
2. **Your pet**: `/petmenu` for its moves, **Stay**, **Roam**, **Stop**. `/petsummon` calls it out at full size or sends it back to your shoulder.
3. **Ride your pet**: summon it and press **J**: its mount stands where it stood. Dismount and your pet is there again.
4. **Prop moves**: `/apflare`, `/apswish`, `/apshake`, `/apflick` play a move on the prop you wear.

---

## VI · For admins

**`/mountadmin`**
- **Players**: find a player online. Give or take **VIP**. For each mount: **Lock to them** (every colour), **Take back**, or **Colours** to give single colours. This is how you choose exactly what each player may ride.
- **Who rides what**: each mount gets a mode, plus one switch for "Mounts need their item". A pet's mount can also be a *Normal mount too*.

  | Mode | Who rides it |
  |---|---|
  | 🟢 Free | everyone |
  | 🟠 Item | needs its item |
  | 🟣 VIP or item | VIP free, others need the item |
  | 🟡 VIP only | every VIP |
  | 🔵 **Assigned only** | only the players you gave it to |
  | 🔴 Off | nobody |

  *To give a player only certain mounts: set those mounts to Assigned only, then in Players lock to each player what they may ride.*
- **Mounts**: every mount on one list: on or off, its name, price and riding numbers; **Back to config** undoes a row; **Add a mount** copies one under a new name.
- **Shops**: add a shop where you stand; move it, give it a stable hand and a map mark, choose what it sells.

**`/apadmin`**: the Steward's Ledger for props and pets: give a prop (as an item or as access, for a time), turn on a pet's mount, see who holds what, VIP tiers, roles, shops, the Showroom and the log. `/apfit` opens the Fitting Bench.

**Tuning**: `/mountdev` edits a mount live for everyone; `/mountfit` measures a mount's height on the ground again.

---

## VII · Every command

| Command | For | What it does |
|---|---|---|
| F6 · `/mountvip` | Player | My Mounts: every mount you may ride now |
| E at a mount shop | Player | Open that shop and buy a mount |
| J · `/ridepet` | Player | Ride your summoned pet |
| F7 · `/rklmountsui` | Player | Arrange, colour or hide the mount UI |
| F9 · `/rklmountshide` | Player | Hide or show all mount UI |
| `/animatedprop` | Player | Your Regalia |
| `/petmenu` | Player | Your pet: moves, Stay, Roam, Stop |
| `/petsummon` | Player | Summon your pet, send it back, or call back a pet mount |
| `/apflare` `/apswish` `/apshake` `/apflick` | Player | A move on the prop you wear |
| `/mountadmin` | Admin | Players, Who rides what, Mounts, Shops |
| `/mountgrant <id> <mount \| colour \| vip> [off]` | Admin | Lock a mount, a colour or VIP to a player |
| `/mountdev` | Admin | Edit a mount live |
| `/mountfit [reset \| off \| on]` | Admin | Measure a mount's height again |
| `/mountdebug` · `/findanims [dict]` | Admin | Debug tools |
| `/apadmin` | Admin | The Steward's Ledger |
| `/apfit` | Admin | The Fitting Bench |
| `/apdebug` | Admin | List every spawned prop in F8 |
| `apgive <id> <prop> [colour \| all]` | Admin | Give a prop item |
| `apgiveall <id> [category \| all]` | Admin | Give every design of a category |
| `apgrant <player> <scope> [minutes] [colour]` | Admin | Access to a prop without an item |
| `aprevoke <player> <scope>` | Admin | Take that access back |
| `apvip <player> <tier \| remove> [days]` | Admin | A player's prop VIP tier |
| `apaccess [scope] [preset]` | Admin | Who may wear a prop |
| `aproles` · `aplog` · `apshop` | Admin | Roles, the log, the prop shops |
| `apitems` · `apaddons` · `apfitexport` | Admin | Item list, found addons, fit export |

*Console commands are typed in the server console without the slash, or in game by staff allowed to use them.*

<div align="center">

✦ *Ride well, and may your mount never tire.* ✦

</div>
