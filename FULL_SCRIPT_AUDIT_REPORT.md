# The Long Goodbye — Full Script Audit

Input HTML: `index_story_polish_v5_7_10_full_jp_FULL_AUDIT_FIXED.html`

## Summary

- Routes audited: 6
- English story scenes: 201
- Japanese translated scene patches: 201
- CG art keys: 256
- Scene asset mappings: 197
- Line-specific asset mappings: 29
- Ending asset mappings: 32
- Route covers: 6
- Gallery entries: 256

## Route coverage

| Route | EN scenes | JP translated patches | Status |
|---|---:|---:|---|
| ren | 77 | 77 | OK |
| harrison | 23 | 23 | OK |
| marcus | 22 | 22 | OK |
| hiroshi | 16 | 16 | OK |
| kenji | 22 | 22 | OK |
| tommy | 41 | 41 | OK |

## Ending asset mapping highlights

- `Harrison Bittersweet Ending: Loved Her Enough to Let Her Go` → `harrison_bittersweet_airport_goodbye`
- `Harrison Bittersweet Ending: The Right Man, Wrong Life` → `harrison_bittersweet_airport_goodbye`
- `Harrison Bad Ending: Safe Was Not Enough` → `harrison_bad_empty_space_between_us`
- `Tommy Variant: Back to You` → `tommy_back_to_you_car`
- `Tommy Bad Ending: Endless Loop` → `lonely_night_in_the_city`

## Checks performed

- EN/JP route keys match.
- EN/JP scene keys match after Japanese patch application.
- JP scene choice counts, choice targets, and stat deltas match English.
- All choice targets resolve to scenes or known special handlers/endings.
- Scene asset keys resolve to `CG_ART`.
- Line-specific asset keys resolve to `CG_ART` and line indexes are in range.
- Ending asset keys resolve to `CG_ART`.
- Route cover keys resolve to `CG_ART`.
- Gallery keys resolve to `CG_ART`.
- Japanese menu assets are wired to `assets/menu_locked_secret_jp.jpg` and `assets/menu_unlocked_kenji_jp.jpg`.

## Issues

- ✅ No blocking script/data issues found.

## Warnings / cleanup notes

- ✅ No warnings.

## English leftovers in Japanese script

- ✅ No obvious English speaker/name leftovers found in JP script.

## Asset package note

- Patch ZIP checked: `the_long_goodbye_jp_harrison_ending_update_v5_7_10.zip` with 40 entries.
- This ZIP is a patch package, not necessarily a full deploy package with every historical CG asset.