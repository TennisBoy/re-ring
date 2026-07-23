# SHAD 2026 DE — Sound-Awareness Device

The team's project site for **SHAD 2026 — Design & Entrepreneurship** at TMU.

**How might we reimagine the life cycle of everyday goods to minimize waste and drive sustainable innovation?**

## The concept

Harvest the **piezoelectric crystal** out of discarded disposable lighters and turn it into a
**contact microphone**. A small node sticks to the object that makes a sound — a door, a smoke
alarm, a washing machine — classifies what it hears **on the device itself**, and sends a short
message to a phone or smartwatch. Deaf and hard-of-hearing users get a wrist tap telling them
what their home is doing.

**The everyday good whose life cycle is reimagined is the lighter, not the device.** Disposable
lighters are household hazardous waste and a fire risk in waste facilities. We take one out of
that stream and it comes back as a sensor.

## What's here

| File | What it is |
|---|---|
| `index.html` | The full business case — **generated, not hand-written** (see below) |
| `rering-deck.html` | The superseded Re:Ring pitch deck, kept for reference |

Open either in any browser — self-contained, no build step, no dependencies.

## This site is generated

`index.html` is rendered from a source document by a build script that lives in a separate
repository. **Do not hand-edit it** — the next build silently overwrites your changes. Edit the
source, re-run the build, commit the result here.

## Reading the claims

Every figure on the page is labelled, and the labels are colour-coded so they survive a skim:

- `[est]` — **our own estimate**, invented for the business case. Defensible as an estimate,
  not a fact. There are 23.
- `[verify]` — believed true, **not yet checked against a source**. There are 16.

Nothing on the page is bench-tested, and no cost figure comes from a supplier quote.

**The load-bearing untested assumption:** nobody has yet confirmed that a reclaimed lighter
piezo can resolve a knock into a usable signal. The whole concept rests on it.

## Known limitation, stated up front

A piezo is a *contact* microphone — it reads vibration through solids far better than sound
through air. Knocking, doorbells, and smoke alarms are strong cases. **Baby crying and dog
barking are airborne, and are the weak cases.** The page says so rather than burying it.

## Superseded — Re:Ring

The team's earlier concept: jewelry that keeps the metal *look* and drops the metal *bulk* — a
3D-printed plant-based PLA core electroplated with a micron-thin skin of real metal, designed to
be taken back, re-plated, and composted. Preserved at `rering-deck.html`.

Two claims from it worth keeping straight: PLA does **not** biodegrade in nature (it needs
industrial composting), and the "less mined metal" figure was always a design-stage estimate.
