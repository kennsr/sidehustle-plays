# Sidehustle Plays

A slot machine that picks your next side hustle. Grab the lever, drag it down, and the
reel lands on a play — or hit **Spin**, or press space.

**Live:** https://kennsr.github.io/sidehustle-plays/

## What's in the service panel (the gear)

- **Next result** — pick any play and the reel lands on it. Nothing on the machine face
  gives it away; the cabinet reads `READY → SPINNING → LOCKED IN` either way.
- **Keep the rig** — off, the fix fires once and the machine goes back to random;
  on, every spin lands there.
- **Show prices** — hides every price: the readout, the outcome picker, the editor,
  and the price sentence in the footer.
- **Machine size** — 70–200%, or **Fit** to scale the whole thing to your screen.
- **Sound** and **spin length**.
- **The plays** — rename, reprice, add, delete, or reset to the original eight.

Settings persist in `localStorage`.

## Running it

One file, no build step, no dependencies:

    open index.html

Prices are typical market rates, not guarantees.
