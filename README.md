# Home Base

A single-file, gamified home-maintenance board. Each home gets its own copy so its records, tasks and saved progress stay separate (each copy uses its own browser-storage key).

| Home | Open | Notes |
|---|---|---|
| The Kim Home (house) | `index.html` | Original demo-seeded board. |
| 1803 – 8 Smithe Mews, Vancouver (condo) | `smithe-mews/index.html` | Real records only. First asset: the TOTO Aquia toilet (photos in `smithe-mews/photos/`). |

## Adding a real item to the condo board

Assets live in the `STATE.assets` array near the top of the `<script>` in `smithe-mews/index.html`. Copy the toilet entry as a template. Useful optional fields it supports beyond the original game:

- `location`, `purchaseNote`, `issue` (shows a red "Current issue" block)
- `notes` (list of identification notes)
- `photos` (`{src, cap}` — put the files in `smithe-mews/photos/`) and `handymanSummary` (copy/email button on the Photos tab)
- `price: 0` hides the price; `lastDone: null` on a schedule job shows "Not done yet"
