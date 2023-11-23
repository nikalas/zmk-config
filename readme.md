# ZMK configuration for Kyria

This is my ZMK configuration for the Kyria keyboard. It's a work in progress.

## TODO

[ ] Make proper windows layer

## Features:

### Vim-key

No useless caps lock key here. Instead it's a vim-key, pulling double duty as both escape (when tapped) and control when held down.

### Combos

[Combos](https://zmk.dev/docs/features/combos/)

I have set up the following combos, for both my mac and win layers:

- redo : `shift+z`
- undo : `z+x`
- cut : `x+c`
- copy : `c+v`
- paste : `v+b`

### Tap Dance

[Tap Dance](https://zmk.dev/docs/behaviors/tap-dance/)

On the left shift key, I have set up tap dance to toggle sticky shift on single press, regular shift for hold, and caps word for double tap.

### Home Row Mods

[Home Row Mods](https://zmk.dev/docs/behaviors/hold-tap#example-use-cases)

Essentially this allows me to use the home row keys as modifiers when held, and as regular keys when tapped.
