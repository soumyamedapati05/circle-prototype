# Circle. prototype roadmap

Three iterations, each with a theme. v1 and v2 are complete and frozen for screenshots. v3 is the current build.

## Sprint 1 — MVP core flow (v1), done

Renter only, deliberately scrappy. Search by category and date, results sorted by distance, item detail with specs, condition record and ID-verified badge, request with dates and lender-set pickup slots, simulated payment with fee and deposit, confirmation.

Cut: map, chat, lender side, multi-item, reviews, insurance, cancellation, brand colors.

## Sprint 2 — Complete the MVP (v2), done

Map view with lender pins, multi-item request from one lender, all-in price on every result, pickup address and instructions on confirmation, brand palette from the team deck.

Bugs found in testing: overlapping map labels; pin tap broke on lender names containing quotes.

## Sprint 3 — Trust and Release 2 (v3), current

**Design.** Minimal redesign, phone frame, Inter, bottom tabs, real product photos, real Lower Manhattan map tiles with Apple-style pins.

**Renter trust.** Sign up, sign in, ID verification with live camera capture, renter profile showing what lenders see, reviews on items and lenders, leave a review after return.

**Release 2 renter features.** Damage protection opt-in at checkout, cancel with fee rules, report a problem with deposit freeze, per-rental chat and inbox, My Rentals with status.

**Lender side.** Added after review flagged that supply was missing from the prototype. Role switch on profile, list an item in under five minutes, requests inbox with renter trust summary and one-tap approve or decline, block dates and remove listings, earnings and upcoming payouts.

Bugs found in testing: lender review count overwrote item reviews; toast covered the Verify button; lender payout included the renter's service fee.

## Still deferred

- Curated bundles and collections (Release 2 story map).
- Push notifications for pickup reminders (Release 2 story map).
- Real payments, real ID verification, real messaging backend. Everything in the prototype is simulated client-side.

## Assumptions the prototype still cannot test

- Whether trust cues are enough for Vicky to book from a stranger (the primary assumption in the planning doc). Test with mock listings with and without trust cues.
- Whether at least 10 lenders in one Lower Manhattan cluster will list fixtures with weekend pickup slots. Test by contacting 30 businesses and counting sign-ups in two weeks.
