# Toilet — TOTO Aquia (dual flush)

**Home:** 1803-8 Smithe Mews, Vancouver, BC V6B 0A5 · Buzzer 6088
**Location:** Bathroom
**Documented:** 2026-09-08 by Young (photos in `../photos/`)
**Status:** ⚠️ Reported broken, Sep 2026 — handyman requested photos. Exact symptom still to be written down (won’t flush / keeps running / weak flush / leaking at base / button stuck).

## Identification

| Field | Value |
|---|---|
| Brand | TOTO |
| Product line | Aquia, Dual-Max flushing system |
| Set model | **CST414M** (two-piece, 12″ rough-in, elongated, skirted bowl, universal height, chrome push-button) |
| Tank model | **ST413M#01** |
| Bowl model | CT414 (expected pairing — not photographed, confirm from the stamp on the bowl) |
| Colour | #01 Cotton White (stamp reads `#01(W)`) |
| Flush rating | 1.6 gpf / 6.0 Lpf full · 0.9 gpf / 3.4 Lpf light |
| Tank stamp | `483 · 080421 · #01(W)` → manufactured 2008-04-21 |
| Parts label | 0EU047 REV 03/06 (covers Aquia ST413M, Drake ST743SB, Drake ST743SBD) |
| Warranty | TOTO 1-year limited on vitreous china — expired 2009-04-21 |
| TOTO technical support | 1-888-295-8134 · totousa.com |

**How it was identified:** the tank exterior is printed with a dual-flush rating (1.6 / 0.9 gpf). Of the three tanks on the in-tank parts label, only the Aquia row (ID mark ST413M) is dual flush; both Drake rows are 1.6 gpf single flush. TOTO’s parts manual PD-00190 lists ST413M as the tank of the CST414M Aquia set. The skirted elongated bowl in the photo matches.

## Replacement parts (Aquia row of the tank label)

| Part | TOTO part # |
|---|---|
| Fill valve | TSU09A.8 |
| Flush valve assembly | THU224 |
| Seal gasket (flush-valve seal) | 9BU064E |
| Push button, chrome | THU221#CP |
| Elongated seat (standard Aquia pairing — confirm hinge spacing) | SS114#01 |

Order colour-matched parts in **#01**. Do **not** use chlorine drop-in tablets in the tank (label warning — degrades the flush-valve seal).

## Observations from the photos

1. Whole unit: elongated, skirted bowl with close-coupled tank; seat and lid stained (seat is a separate part).
2. Tank exterior: dual-flush rating that identifies the Aquia Dual-Max.
3. Parts label inside the tank with the Aquia part numbers above.
4. Same label, second angle.
5. Inside the tank: date/colour stamp and a green-tinted, mineral-scaled fill-valve base — likely culprit if the tank runs or refills slowly.

## Maintenance schedule

| Job | Every | Last done | Next due |
|---|---|---|---|
| Open tank: inspect & photograph internals | 365 d | 2026-09-08 | 2027-09-08 |
| Dye test for silent tank leaks | 180 d | — | 2026-10-01 |
| Clean seat, hinges & rim jets | 90 d | — | 2026-10-08 |
| Check tank-to-bowl bolts & base for seepage | 365 d | — | 2027-03-01 |

## Open tasks

| Task | Due |
|---|---|
| Send toilet photos + model info to handyman | 2026-09-09 |
| Write the exact toilet symptom on its record | 2026-09-09 |
| Handyman visit — fix the toilet | 2026-09-15 |
| Log the repair + parts on the History tab | 2026-09-16 |
| Toilet dye test (silent leak), repeats every 180 d | 2026-10-01 |

## Service log

- **2026-09-08 · Young** — Toilet reported broken. Opened the tank, photographed the parts label, tank stamp and flush rating; identified the model as TOTO Aquia CST414M (tank ST413M). Photos sent to the handyman. Parts: none yet. Cost: $0.

## Copy-paste summary for the handyman

> Toilet: TOTO Aquia two-piece dual flush (1.6 / 0.9 gpf), model CST414M — tank ST413M, colour #01 Cotton White, tank date stamp 08/04/21. TOTO part numbers from the tank label: fill valve TSU09A.8, flush valve THU224, seal gasket 9BU064E, push button THU221#CP. Elongated skirted bowl, 12" rough-in. Address: 1803-8 Smithe Mews, Vancouver BC V6B 0A5, buzzer 6088.

## Importing into the game

`toilet-toto-aquia.json` in this folder is the exact record the game uses. To load it into another Home Base copy, paste the `asset` object into that file’s `STATE.assets` array and the `tasks` entries into `STATE.tasks`, then copy the `photos/` folder alongside the HTML.
