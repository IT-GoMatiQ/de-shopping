# Delaware Outlet Shopping Tracker

Personal shopping helper for Delaware outlet malls (no sales tax!).

## How this works

As you walk into each store, tell me about items you're considering. I'll log
them and at the end I'll tell you exactly where to buy what — based on price,
discounts, and color pairings.

## Files

- `stores.md` — list of stores we plan to visit + map / route notes
- `items.json` — source of truth: every item you've shown me
- `tracker.md` — human-readable running view of all logged items
- `recommendations.md` — final "buy this here, pair with that" output (filled
  in when you say "I'm finished")

## What to tell me per item

When you're in a store and find something, just say it however is natural.
I need (in any order):

1. **Item type** — pants / shorts / shirt / belt / shoes / socks / etc.
2. **Color** — of the item itself
3. **Price tag** — the listed/original price
4. **Discount** — % off, $ off, or "buy one get one", etc.
5. **Pairs with** — colors you'd wear it with (e.g. "I'd wear with green or
   white shirts")
6. **Store** — which store you're in (I'll remember it for follow-up items
   in the same store)
7. **Notes** *(optional)* — size, material, fit, "maybe", etc.

Example you can paste:
> "Polo Ralph Lauren — grey chino pants, tag $89.50, 40% off, would pair
> with green / white / navy shirts."

You don't have to be that structured. Just give me the facts; I'll log them.

## Useful commands while shopping

- **"What did I see in [store]?"** — I'll list items from that store
- **"What [color] shirts have I seen?"** — color/category lookup
- **"What pairs with my grey pants?"** — pairing lookup
- **"I'm finished"** — I'll produce final buy-list + route in
  `recommendations.md`

## Prices

All prices are recorded post-discount, pre-tax. Delaware = no sales tax, so
the final price you'll actually pay is what I show.
