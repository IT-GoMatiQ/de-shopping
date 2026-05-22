# Delaware Outlet Shopping Tracker

Personal shopping helper for Tanger Rehoboth (no sales tax!).
**Chat-based.** No app. You talk, I track.

## Files

- `items.csv` — every item, source of truth (sample data pre-loaded)
- `tracker.md` — readable manifest view, updates as items are added/changed
- `stores.md` — store list and walking route from Applebee's

## How it works

You walk into a store and tell me about anything you're considering. I log
it to `items.csv` and reply in chat with:

1. ✅ Confirmation of what was logged
2. 📋 Current manifest (counts + total)
3. ⭐ Top-2 cheapest of each item type
4. 📍 Current store + 🚶 Next direction

You can also ask me anytime:
- "What's the cheapest green shirt I've seen?"
- "What pairs with my grey Calvin Klein pants?"
- "How much would I spend if I bought everything marked Buy?"
- "Mark item #5 as buy" / "Skip item #3"
- "I'm finished" → final buy plan by store

## What to tell me per item

In any order:
- Item type (pants, shorts, shirt, polo, slacks, belt, shoes, etc.)
- Color
- Tag price
- Discount (% or $)
- Colors you'd pair it with (optional)
- Notes (size, fit, etc. — optional)

Store is whatever you're "currently in" — I'll remember it across items.
