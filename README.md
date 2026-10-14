# Sunset Soul — PSP homebrew (PSPSDK)

Original mini RPG prototype: explore 3 rooms, talk to the guide,
dodge sparks in short encounters. Art is drawn with rectangles — no assets.

## Build
Requires PSPSDK (`psp-config` in PATH), or use Docker:

```sh
docker run --rm -v "$PWD":/src -w /src pspdev/pspdev make
```

Output: `EBOOT.PBP`. Copy it to `ms0:/PSP/GAME/SunsetSoul/EBOOT.PBP`
(CFW or PPSSPP).

## Controls
- D-pad: move / dodge
- R: run
- X: talk / strike
- O: continue / spare
- START: help
- HOME: exit
