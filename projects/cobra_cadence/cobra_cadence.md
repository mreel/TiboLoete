![Cobra Cadence Banner](media/banner.jpg)
---
The Cobra Cadence is a 36-key, handwired split keyboard with a unique layout.

**Key features:**  
- Slightly splayed columnar-staggered layout
- 4×3+2 main cluster
- 2×3 thumb keys
- 2 'mash' keys
- KMK firmware

{pictures}

## Design
### Layout
With this keyboard I wanted to take the principle of 'never more than 1u away from the homerow' very seriously, but also wanted to keep a few easily mashable keys, namely escape and play/pause. It's just fun to mash 'em.  
To that end, there's only two keys on the inner column, I've never liked the inner column while typing so this was my change to make it just a bit smaller and keep those keys within even easier reach.  
On the pinky, I decided to go for an oddly placed upper row as I have very short pinkies. For my next keyboard I would likely go for a slightly more exagerated stagger instead.  

### Build
I went with a more organic shape for case for a few reasons. For one, with this layout, a tighter, more common angular design simply didn't look good. I also felt that ergonomic keyboards in general are meant to line up with our biology more closely, to be more organic. The design should reflect that.  
The logo is based on the key layout, the snake's head is the 'mash' key, with the tail as the thumb cluster.
{logo->key graphic}

The case and plates are 3D-printed and the keyboard uses a [sandwich mount](https://www.keyboard.university/200-courses/keyboard-mounting-styles-4lpp7). The plate features a recepticle for the microcontroller to fit into. The keyboard is completely symmetrical and both halves are connected with a hardwired cable.

> [!TIP]
> All the files for this project can be found in this repo

## Components
### BOM
| Part                              | Quantity |
| --------------------------------- | -------- |
| Diode                             | 36       |
| MX switch (Durock T1)             | 36       |
| Seeed Studio XIAO nRF52840        | 2        |
| M2 threaded inserts               | 48       |
| M2 Nut                            | 2        |
| M2 Screw                          | 26       |
| Keycaps                           | 36       |
| Wire†                             | ~3m?     |
| 3D-printed plate (L+R)            | 1        |
| 3D-printed case (L+R, top+bottom) | 1        |
<!-- to do: add lengths to threaded inserts and screws-->
† I used the conductors from some ethernet cable I had laying around, worked great

<!-- 
- reddit post: summary and pictures
- blog post on website: longer write-up, including a detailed explanation of stuff so it can be replicated
- github page: more firmware, 3d files etc
- BOM
- assembly guide
- firmware
- license (hardware and software)
- marketing?
- credit & attribution
- all project files
-->