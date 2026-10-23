# Logic Lab

A playful logic gates game for kids. It runs in the browser as one self-contained page (`index.html`), with no build step and no dependencies. Open the file and play. The only outside request is the Google Fonts stylesheet, and the page works without it using fallback fonts.

Kids flip switches, light lamps, and drag gates and NOTs into circuits. It teaches AND, OR, NOT, NAND, NOR and XOR, then De Morgan's laws, a half adder, and building every gate from NAND alone.

## Levels (22)

| World | Levels |
| --- | --- |
| 1. Meet the gates | Switch and lamp, NOT, AND, OR |
| 2. NOT tricks | Spy gate, NAND, NOR, XOR |
| 3. De Morgan's mirror | Twin of NAND, twin of NOR, AND from an OR, OR from an AND, A but not B |
| 4. Real-life logic | Door alarm, sprinkler, pet shop door |
| 5. Computer parts | Adding with gates, build the adder, NOT / AND / OR from NAND |
| 6. Free play | Playground that names what you build and lists its twins |

## How to play

- Drag a gate piece onto the gate spot, and drag a NOT onto a dotted circle. Drag a NOT away to remove it.
- On the NAND plug board, drag plugs (switch A or B, or the output of another NAND) into the sockets.
- Slide the switch knobs, or tap anything. Tapping works everywhere as a fallback.
- Tap a row of the truth table to set the switches for you.

## Notation

A small circle on a gate's input or output means "invert this signal", as in standard logic diagrams (ANSI/IEEE Std 91). The game calls that circle a NOT. De Morgan's trick in the game is: flip every NOT (add it or remove it), then swap AND and OR.

## Notes

- Progress is saved in the browser's local storage.
- Works with mouse, touch and keyboard, in light and dark mode.
