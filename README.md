# Rana Moth WASD

A foldable low-profile WASD keyboard with a hinge design inspired by moth wings. Features a "prism" fold, neodymium magnet closure, and Raspberry Pi Pico controller.

![Moth open](Images/Moth.jpg)

![Moth folded](Images/Folded%20Moth.jpg)

---

## Shell Printing

Print the shell, hinges, and all other parts in **Bambu Lab PETG** (any PETG should work). Print the **hinge pin in PLA+** — PETG will warp without supports.

---

## Components

- **Controller:** Standard Raspberry Pi Pico — screws in with M2 screws (4mm length, shorter will also work)
- **Switches:** Must be **low-profile**. Tested with Cosmox Wind Engines and KS33 Silvers
- **USB-C connector:** Model UD (superglued in). The **Model BirdD** is recommended instead — it mounts with screws. You'll need to modify the shell model slightly to fit the BirdD

---

## Assembly

1. Get the Pico side fully wired before touching the other half
2. **Fold the Moth before running cross-body wires** — if you solder in the open position, wires will pull too tight when folded
3. Leave plenty of slack in cross-body wiring
4. Route wires behind the hinge pin for a cleaner build — this is much easier while folded
5. Install the hinge pin **after** routing wires. Getting the pin through with wires already crossing is very difficult

---

## Magnets

The magnets need to be strong — they're working against all the switch springs.

- **Size:** 6×2mm Neodymium, stacked 3 high per hole
- **Count:** 10 holes × 3 magnets = **30 magnets total**

The snap when closing is very satisfying and holds the Moth securely shut.

> [Amazon link to magnets used](https://a.co/d/aDkEUHX)

---

## Prism Fold Design

The top hinge piece has a **lip** that stops the wings from overfolding, giving the prism position a clean stopping point. The rounded hinge backs create friction for rigidity.

**Recommendation:** Put the lip on the **bottom hinge piece** instead of the top.

- The top hinge cannot be removed without fully rewiring the Moth
- The bottom hinge pin can be pulled and the piece replaced if you want to adjust your prism angle later

You can edit the lip width to change the folded angle — shallower or steeper depending on preference.

---

## Misc Notes

- Buttons must be **flush with the face surface** when depressed, or the halves won't meet cleanly when closed. Strong magnets may compensate for minor protrusion
- The hinge pin slots are left open — the friction fit holds without caps, and leaving them open makes intentional removal easier

---

## Files

| Folder | Contents |
|--------|----------|
| `Shell/` | 3D printable shell top panels and backplates (STEP) |
| `Hinge and Buttons/` | Hinge upper/lower, hinge pin, and keycap models (STEP) |
| `Moth PCB/` | KiCad PCB project, schematics, and fabrication files |
| `DXF/` | PCB outlines and hole patterns for reference |
| `Images/` | Build photos |
