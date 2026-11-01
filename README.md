# pj-join — members sign-up mock-up

A click-through mock-up of the PJ O'Rourke II members sign-up, made to show PJ the idea before anything is built into the Shopify store. Nothing typed into it is saved or sent.

Six screens, phone-first:

1. **Sign up**: email needed; Instagram, phone (texts behind their own checkbox) and birthday month optional
2. **Lost & Found reveal**: tap a card to find a code (10 / 15 / 20% off, free sticker, or a 1-in-100 golden ticket for a signed print) plus a member number
3. **PJ's Pick**: members vote between two sketches; the winner becomes a numbered run
4. **Which stop are you?**: three-question quiz, matched to a piece, with a code
5. **Bring a friend**: personal link and a reward ladder
6. **Lost & Found peek**: the members-only page for old stock and one-off vintage upgrades

"Notes for PJ" (top right) shows a short why under every screen.

## Placeholders

- PJ's Pick uses two existing prints as stand-ins for new sketches; vote percentages are fixed demo numbers.
- Lost & Found items are examples from the current site; the real list comes from the locker count. Member prices are hidden on purpose.
- Reward odds, the friend ladder and the codes are suggestions for PJ to set. The golden ticket needs official rules before it goes live.
- The club has no name yet.

## Run it

Open `index.html` in a browser, or serve the folder (`python3 -m http.server`).

## Link preview

`build/make_card.sh` renders `build/card.html` to `og.jpg` (1200 × 630) with headless Chrome. The og:image tags point at `https://feldtdesign-ship-it.github.io/pj-join/` in case it's published there; it is not published.
