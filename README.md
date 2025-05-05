# Giovanni's Mansion

A first attempt at a Pokemon Red Romhack

## Changelog

- Added movement speed QoL improvements from Pret's [Running Shoes tutorial](https://github.com/pret/pokered/wiki/Running-Shoes)
- Changed starter pokemon 
- Added Red debug version from [Pret's tutorial](https://github.com/pret/pokered/wiki/Add-debug-mode-to-red). i.e. Blue debug but just on Red version


data/text.asm -> changed oak speech
changed oak_speech ProfOakPic to GiovanniPic


## Proposal
- Small game
- Giovanni tasks Rocket (or just Red) to find something in a city
- Mother held hostage by Rockets or something
- You are given one pokemon (something like Ghastly or Porygon for fun)
    - Stretch goal -> Recreate Baloonda
- Go around city trying to find the thing/defeat the guy
- Doors link to new map areas full of trainers
- Kind of a Kaizo survival hack
- Some mechanic where trainers either chase you or suddenly run at you
- Mario Has Logged On inspiration
- At the end you fight your way to Giovanni and then fight him or something
- Like 1-2 hour game tops, delete all other areas
- Maybe like 1 building with 4 rooms or something
- 1 room puts you in the centre with a load of non-skippable trainer fights
- 1 room is Misty Has Logged On and she sprints at you




Original readme:
## Pokémon Red and Blue [![Build Status][ci-badge]][ci]

This is a disassembly of Pokémon Red and Blue.

It builds the following ROMs:

- Pokemon Red (UE) [S][!].gb `sha1: ea9bcae617fdf159b045185467ae58b2e4a48b9a`
- Pokemon Blue (UE) [S][!].gb `sha1: d7037c83e1ae5b39bde3c30787637ba1d4c48ce2`
- BLUEMONS.GB (debug build) `sha1: 5b1456177671b79b263c614ea0e7cc9ac542e9c4`
- dmgapae0.e69.patch `sha1: 0fb5f743696adfe1dbb2e062111f08f9bc5a293a`
- dmgapee0.e68.patch `sha1: ed4be94dc29c64271942c87f2157bca9ca1019c7`

To set up the repository, see [**INSTALL.md**](INSTALL.md).


## See also

- [**Wiki**][wiki] (includes [tutorials][tutorials])
- [**Symbols**][symbols]
- [**Tools**][tools]

You can find us on [Discord (pret, #pokered)](https://discord.gg/d5dubZ3).

For other pret projects, see [pret.github.io](https://pret.github.io/).

[wiki]: https://github.com/pret/pokered/wiki
[tutorials]: https://github.com/pret/pokered/wiki/Tutorials
[symbols]: https://github.com/pret/pokered/tree/symbols
[tools]: https://github.com/pret/gb-asm-tools
[ci]: https://github.com/pret/pokered/actions
[ci-badge]: https://github.com/pret/pokered/actions/workflows/main.yml/badge.svg
