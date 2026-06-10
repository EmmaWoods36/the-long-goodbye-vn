# The Long Goodbye — Full Script Audit V3

## Summary

- Routes audited: 6
- English story scenes: 201
- Japanese translated scene patches: 201
- CG art keys: 256
- Scene asset mappings: 201
- Line-specific asset mappings: 14
- Ending asset mappings: 32
- Uncapped scenes: 0
- Non-JPEG image files in deploy package: 0

## Fixes from V2

- Added scene-level image caps for the four Ren truth-result scenes:
  - `ren_truth_full`
  - `ren_truth_lie`
  - `ren_truth_unsure`
  - `ren_truth_deflect`
- Converted Harrison ending assets from PNG to JPG:
  - `assets/harrison_bittersweet_airport_goodbye.jpg`
  - `assets/harrison_bad_empty_space_between_us.jpg`
- Updated HTML references to use the JPG versions.

## Harrison ending mappings

- `Harrison Bittersweet Ending: Loved Her Enough to Let Her Go` → `harrison_bittersweet_airport_goodbye`
- `Harrison Bittersweet Ending: The Right Man, Wrong Life` → `harrison_bittersweet_airport_goodbye`
- `Harrison Bad Ending: Safe Was Not Enough` → `harrison_bad_empty_space_between_us`

## Unchanged per request

- `Tommy Variant: Back to You` → `tommy_back_to_you_car`
- `Tommy Bad Ending: Endless Loop` → `lonely_night_in_the_city`

## Checks

- Missing scene caps: []
- Missing scene or line caps: []
- Non-JPEG image files: []
