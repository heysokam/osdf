# Open Source defrag's mod code

## Goals:
### Code & License:
- Respect FOSS philosophy. Open source and community focus.
- Eliminate all traces of q3a-sdk licensing constraints.
- Either reverse-engineer or rewrite the code.
- Community based, where anyone can become a contributor.

### Gameplay:
- Maintain gameplay 1:1. The code is not accessible, but can be reverse-engineered.
- Achieve compatibility with existing maps. Avoid requiring any form of map porting as much as possible.
- Community collaboration in bug-fixing and further development of the mod.

## Base repositories:
- ioquake3: 
Base development starting point (q3e has no gpl qvm creation utilities)

- Q3Arena 1.32b GPL release: 
Base Gameplay code (ioq3 has gameplay modifications)

- Lumia's Momentum Mod GPL codebase: https://github.com/chovelyoukai/defragmmod 
Most accurate non-id3-engine implementation to date

## Helper repositories:
Repositories that can aid in the success of this project:
- Existing reverse engineering effort: https://github.com/krsh732/DF_Reverse_Stuff
- Q3vm disassembler: https://github.com/brugal/q3vm 
- Existing OpenDF attempt, based on OpenArena: https://github.com/oitzujoey/opendf
