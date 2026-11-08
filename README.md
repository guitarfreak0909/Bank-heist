# Night Shift Heist

A small roguelite stealth bank-robbery game that runs in the browser. It's one HTML file with no dependencies.

**Play:** open `index.html` in a browser. It works on desktop (keyboard) and on phones and tablets (touch controls, portrait or landscape).

## How to play
**Touch:** the left stick moves you, and pushing it all the way to the edge sprints. Hold ACT to crack the vault or pick a lock, and tap it at the van to escape. SMOKE, DECOY, DISG and EMP use your items, and II pauses.

**Keyboard:**
- **WASD / arrows**: move. **Shift**: sprint, which makes noise guards can hear.
- **E / Space**: hold next to the vault to crack it (drilling is loud) or next to a locked door to pick it. Tap at the van to escape.
- **Q**: smoke bomb. **R**: throw a decoy. **C**: guard uniform (disguise). **F**: EMP that disables cameras and lasers.
- **Esc**: pause. **M**: sound on/off.

Pick up cash, crack the vault, and get back to the van. The more you carry, the slower you move. Guards and cameras fill
the detection meter. When it fills, the alarm goes off and a police countdown starts. Getting caught costs a
life and half your bag. Escape without setting off the alarm for a +25% ghost bonus.

There are 5 banks per run, and each one gets a new random layout with more guards and cameras. Between jobs you
spend your take on upgrades at the safehouse. Your best total haul is saved in the browser.

## What you'll run into
- **Locked glass doors** from job 2 on. Guards have keys; you have to pick them. Guards can see through the glass.
- **Laser grids** that pulse on and off across a room. Touching a live beam sets off the alarm. An EMP turns them off.
- **Guard dogs** from job 3 on. They smell you at short range, see through your disguise, and bark loudly enough to bring guards running.
- **The Federal Vault** (job 5) has a two-stage vault. Cracking the outer door brings in two more guards.

## Crew
You unlock new crew members by setting a new best haul: The Ghost ($15k), The Muscle ($35k), The Techie ($60k) and The Mastermind ($100k).
Each one starts with a different loadout.

All sound effects are generated in the browser, so there are no audio files.
