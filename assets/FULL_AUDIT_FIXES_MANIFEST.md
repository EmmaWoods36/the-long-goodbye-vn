# Full Audit Fixes Manifest

## Script/UI fixes applied

- Verified EN/JP route keys, scene keys, choices, choice targets, and stat deltas.
- Verified scene assets, line-specific assets, route covers, ending assets, and gallery keys all resolve to CG_ART.
- Added Harrison ending assets to CG_ART, ASSET_META, END_ASSETS, and GALLERY_ORDER.
- Mapped Harrison bittersweet endings to `harrison_bittersweet_airport_goodbye.png`.
- Mapped Harrison bad ending to `harrison_bad_empty_space_between_us.png`.
- Standardized Japanese route-select hidden-route wording from `シークレットルート` to `隠しルート`.
- Localized the Kenji reveal screen for Japanese mode.
- Confirmed Japanese menu locked/revealed assets are wired to:
  - `assets/menu_locked_secret_jp.jpg`
  - `assets/menu_unlocked_kenji_jp.jpg`

## Unchanged per request

- `Tommy Variant: Back to You`
- `Tommy Bad Ending: Endless Loop`
