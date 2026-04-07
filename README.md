# X-Division for Xenonauts 2

An ambitious project to port the legendary [X-Division](https://www.goldhawkinteractive.com/forums/index.php?/topic/21stranded-x-division/) total conversion mod from Xenonauts 1 into Xenonauts 2.

X-Division was one of the most comprehensive mods for the original Xenonauts, adding dozens of new weapon tech lines, alien species, research projects, and gameplay mechanics. This project aims to bring that depth and content to Xenonauts 2.

> **[ALPHA / PUBLIC TEST]** This project is in early development. Research is instant and manufacturing costs $100 for testing purposes. Values are NOT balanced for normal gameplay. Contributors welcome!

## Project Goals

- **New Weapon Tech Lines** - Multiple new weapon tiers with Mk1/Mk2/Mk3 progression (Plasma, Antimatter, Sonic, Rail, and more)
- **Extended Existing Weapons** - Add Mk3 upgrades to existing Gauss and Laser weapon lines
- **Interrogation System** - Rank-specific alien interrogation research that unlocks advanced technology
- **New Alien Content** - New alien variants, abilities, and encounters (planned)
- **Expanded Tech Tree** - Deep research dependencies requiring specific alien captures
- **Rebalanced Economy** - Adjusted costs, research times, and material requirements (planned)
- **Custom Weapon Icons** - Ported from the original X-Division mod

## Current Content

### Weapons (35 new)

| Tech Line | Weapons | Damage Type | Armour Pen |
|-----------|---------|-------------|------------|
| **Plasma** (Mk1/2/3) | Pistol, Rifle, Shotgun, Sniper, LMG × 3 | Energy | 10-28% |
| **Gauss Mk3** | Pistol, Rifle, Shotgun, Sniper, LMG | Kinetic | 18% |
| **Antimatter** (Mk1/2/3) | Pistol, Rifle, Sniper, Cannon, Minigun × 3 | Kinetic | 90% |

### Interrogations (20 new research projects)

Rank-specific interrogation research for captured aliens:

| Species | Officer | Elite | Leader | Praetorian |
|---------|---------|-------|--------|------------|
| Psyon | ✅ | ✅ | ✅ | ✅ |
| Sebillian | ✅ | ✅ | ✅ | ✅ |
| Wraith | ✅ | ✅ | ✅ | ✅ |
| Secton | — | ✅ | — | ✅ |
| Mantid | ✅ | ✅ | — | — |
| Andron | — | ✅ | — | ✅ |

Plus: Interrogation: Eternal and Interrogation: High Eternal

### Tech Tree

```
=== PLASMA ===
Alien Plasma Weapons + Psyon Officer Interrogation
  -> Basic Plasma (Mk1 × 5)
    + Psyon Leader + Wraith Officer
    -> Advanced Plasma (Mk2 × 5)
      + Psyon Praetorian + Wraith Elite + Wraith Leader
      -> Ultimate Plasma (Mk3 × 5)

=== GAUSS MK3 ===
Gauss Damage upgrade + Sebillian Officer/Elite/Leader
  -> Ultimate Gauss (Mk3 × 5)

=== ANTIMATTER ===
Singularity Core + Ultimate Gauss + Ultimate Plasma
+ Sebillian Praetorian + Wraith Praetorian
  -> Basic Antimatter (Mk1 × 5)
    + Eternal Interrogation
    -> Advanced Antimatter (Mk2 × 5)
      + High Eternal Interrogation
      -> Ultimate Antimatter (Mk3 × 5)
```

## Planned Content

- [ ] **Sonic Weapons** - Mk1/Mk2/Mk3 line
- [ ] **Rail Weapons** - Mk1/Mk2/Mk3 line
- [ ] **Laser Mk2/Mk3** - Extend existing Laser weapons
- [ ] **New Alien Types** - Port X-Division alien variants
- [ ] **New Armour Tiers** - Advanced armour research
- [ ] **Balanced Economy** - Proper costs, research times, material requirements
- [ ] **Xenopedia Entries** - Lore and descriptions for all new content
- [ ] **Localization** - English and Chinese support

## Installation

1. Subscribe on [Steam Workshop](https://steamcommunity.com/app/538030/workshop/), OR
2. Copy the mod folder to `Documents/My Games/Xenonauts 2/Mods/`
3. Enable in the game's Mod Manager
4. Start a new game

## File Structure

```
template/
├── strategy/
│   ├── item/weapon/          (35 weapon definitions)
│   ├── item/corpse/          (11 captured alien items)
│   └── projects/
│       ├── research/         (7 weapon tech + 20 interrogation)
│       └── engineering/      (35 manufacturing projects)
└── groundcombat/
    └── item/weapon/          (35 ground combat weapons)

texture/
└── groundcombat/ui/item/weapon/  (42 weapon icons)
```

## Contributing

This is an open-source community project. We welcome contributions in:

- **Balancing** - Weapon stats, research times, costs
- **New Weapon Lines** - Sonic, Rail, Laser upgrades, etc.
- **New Aliens** - Porting X-Division alien variants
- **Art Assets** - Weapon icons, UI elements
- **Bug Reports** - Testing and reporting issues
- **Localization** - Translations

Please open an issue or submit a pull request!

## Credits

- **Original X-Division mod**: Charon and the X-Division team
- Weapon icons ported from X-Division for Xenonauts 1
- 3D models use existing Xenonauts 2 game assets
- Built with assistance from Claude AI

## Compatibility

- Supported game version: **7.18.4+**
- Does NOT override any base game files
- Compatible with other mods

## License

This is a fan mod for Xenonauts 2. All rights to the original game belong to Goldhawk Interactive.
X-Division assets used with respect to the original mod creators.
