# Dragon's Dogma 2 — Collection & Pawn Tracker

An unofficial, browser-based checklist and reference tracker, with a pawn/fruit counter.

**[Open the tracker](https://rooneysimpson.github.io/dragons-dogma-2-tracker/)**

- Search and filter quests, weapons, armor, rings and skills.
- Track obtained items, quantities, quest completion and personal notes.
- Use **Spoilers: hidden / shown** at the top. Quest names always stay visible and searchable for tracking. Protection starts on: story/route details, NPC/location filters, full records and source links require explicit reveal. Equipment names/pictures stay browsable unless you enable the stricter option; that option never hides quest names. Your choice persists; importing a backup does not silently turn protection off.
- Accepted, unfinished quests are amber; completed quests are green in every view.
- Quests explicitly marked timed in the reference have an orange **Timed** label beside their type, including when spoilers are hidden. An absent label does not establish that a quest has no deadline.
- Click a dropdown or quantity button again to close it without changing your selection. Vocation choices scroll in short windows so the button stays accessible.
- Switch between image cards, detailed cards and text rows using the fixed three-icon View control.
- Use **Columns** to choose how many cards appear across the list. Card size follows the available width; there is no separate scale slider.
- Equipment card names wrap in a separate row above the artwork, preserving the picture area. Detailed cards label hidden spoilers and offer an explicit per-record reveal.
- Vocation emblems sit in the existing single-line strip below each picture. A **+N** button opens the full list when the emblems do not fit.
- Use the A–Z side index with Name A–Z sorting. With grouping enabled, letters navigate within the current group. Rings sort and index by the words after “Ring of”; full item names remain visible.
- Find all shields under **Weapons → Shields**. Armor lists head, body, legs, cloaks and outfit sets.
- Quest text rows show the name, type and objective without empty equipment columns. Full quest names wrap without a line limit: the row grows downward while its horizontal width stays fixed. Quest-only lists fit the available width.
- Switch to **[FIGS™ Tracker](https://rooneysimpson.github.io/dragons-dogma-2-tracker/#figs)** for pawn and fig counters, a saved pawn roster and dated hire/reward history. Its neon button glows with animated colors and sparkles; reduced-motion settings keep it still.
- Add a pawn once, then mark hires by date. Store the list/rank seen on that date, offered rewards and quantities, and whether you collected them. **History** opens previous records; **Same as last reward** copies the previous offer. Favorite, search, filter, archive and Undo help manage regular hires. Pawn IDs are optional unless same-named pawns need distinguishing.
- Marking a dated hire adjusts the existing manual hire counter once. Counter adjustments/resets do not erase records. Offered/collected rewards do not add figs to storage automatically; use the separate +99 storage control after depositing them. Previous dates are editable; an empty date means no record, not a confirmed missed hire.
- Open **Sources** for recorded references, image credits and where each source is used.
- Find the two **Delicious in Dungeon** outfit-set entries under Armor → Outfit set, including claim instructions and Official Pawn information. Their exact inventory names, stats and equipment restrictions remain explicitly unverified.

## Your progress

New visitors start with an empty checklist, empty pawn roster and zero counters. Progress is saved in this browser's local storage, separately for each visitor. It does not automatically sync between devices or browsers. Export **Backup all** regularly and use **Import backup** to restore or move your progress, including pawn profiles and daily history. Older count-only backups preserve your existing roster. Existing v1/v2/v3 collection backups remain supported.

A local HTML copy and the hosted page use different browser storage. To move progress from your downloaded copy, export its backup and import that file into the hosted tracker. Clearing browser/site data can remove local progress.

## Offline copy

Download `index.html` and open it in a current browser. The app, reference data and images are embedded; source links need an internet connection. The downloaded copy stores its own progress.

## References and credits

The **Sources** button lists references and artwork credits recorded in the supplied catalog. Individual item details retain source links, confidence labels and research gaps. Listing a source does not mean every claim or link has been independently checked. This publication preserves the supplied reference catalog; it is not a new factual audit.

Dragon's Dogma 2 and its game artwork belong to CAPCOM. Additional source/credit information is preserved in the tracker. This repository does not claim ownership of third-party material or grant a blanket license for it. This is an unofficial fan tool with no CAPCOM affiliation.

## Hosting

This is a static HTML application, published from the `main` branch root through GitHub Pages. `.nojekyll` keeps the generated HTML unchanged. There is no app account, backend or analytics code. The app does not send your checklist or notes to an application server.
