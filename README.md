# X-Division Weapon Pack for Xenonauts 2

A mod that ports weapon tech lines and adds new interrogation research from the original Xenonauts 1 [X-Division](https://www.goldhawkinteractive.com/forums/index.php?/topic/21stranded-x-division/) mod into Xenonauts 2.

> **[ALPHA / PUBLIC TEST]** Research is instant and manufacturing costs $100 for testing purposes. Values are NOT balanced for normal gameplay. Contributors welcome!

## Features

### Weapons (35 new weapons)

#### Plasma Weapons (15)
- Pistol, Rifle, Shotgun, Sniper, LMG × Mk1/Mk2/Mk3
- Damage type: Energy | Armour Penetration: 10-28%
- New weapon line separate from game's Fusion weapons
- 3D models: Fusion weapon models | Icons: X-Division

#### Gauss Mk3 (5)
- Pistol, Rifle, Shotgun, Sniper, LMG Mk3
- Damage type: Kinetic | Armour Penetration: 18%
- Extends the existing Gauss weapon line with a 3rd tier

#### Antimatter Weapons (15)
- Pistol, Rifle, Sniper, Cannon, Minigun × Mk1/Mk2/Mk3
- Damage type: Kinetic | Armour Penetration: 90% | Armour Destruction: 10-20%
- Endgame weapon line with extreme armour penetration

### Interrogations (20 new research projects)

Adds rank-specific interrogation research for captured aliens:

| Species | Officer | Elite | Leader | Praetorian |
|---------|---------|-------|--------|------------|
| Psyon | ✅ | ✅ | ✅ | ✅ |
| Sebillian | ✅ | ✅ | ✅ | ✅ |
| Wraith | ✅ | ✅ | ✅ | ✅ |
| Secton | — | ✅ | — | ✅ |
| Mantid | ✅ | ✅ | — | — |
| Andron | — | ✅ | — | ✅ |

Plus: Interrogation: Eternal and Interrogation: High Eternal

## Tech Tree

```
=== PLASMA ===
Alien Plasma Weapons + Psyon Officer Interrogation
  -> Basic Plasma Weapon Technology (Mk1 × 5)
    + Psyon Leader + Wraith Officer Interrogation
    -> Advanced Plasma Weapon Technology (Mk2 × 5)
      + Psyon Praetorian + Wraith Elite + Wraith Leader Interrogation
      -> Ultimate Plasma Weapon Technology (Mk3 × 5)

=== GAUSS MK3 ===
Gauss: Damage upgrade + Sebillian Officer/Elite/Leader Interrogation
  -> Ultimate Gauss Weapon Technology (Mk3 × 5)

=== ANTIMATTER ===
Singularity Core + Ultimate Gauss + Ultimate Plasma
+ Sebillian Praetorian + Wraith Praetorian Interrogation
  -> Basic Antimatter Weapon Technology (Mk1 × 5)
    + Eternal Interrogation
    -> Advanced Antimatter Weapon Technology (Mk2 × 5)
      + High Eternal Interrogation
      -> Ultimate Antimatter Weapon Technology (Mk3 × 5)
```

## Installation

1. Subscribe on Steam Workshop, OR
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
└── groundcombat/ui/item/weapon/  (42 weapon icons from X-Division)
```

## Credits

- **Original X-Division mod**: Charon and the X-Division team
- Weapon icons from X-Division for Xenonauts 1
- 3D models use existing Xenonauts 2 game assets

## Compatibility

- Supported game version: **7.18.4+**
- Does NOT override any base game files
- Compatible with other mods

## Contributing

This mod is in early development. If you're interested in:
- Balancing weapon stats
- Adding new weapon lines (Sonic, Rail, etc.)
- Adding new alien types
- Bug fixes

Please open an issue or submit a pull request!

## License

This is a fan mod for Xenonauts 2. All rights to the original game belong to Goldhawk Interactive.
X-Division assets used with respect to the original mod creators.
