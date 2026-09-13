# The Long Goodbye VN — CG Art Path Fix List

## Summary
126 CG_ART entries point to files that don't exist on the deployed site. 31 of these are actively used in scenes and will show broken/blank images during gameplay.

## Fix 1: Remove `new_uploads__` prefix (41 entries)

These CG_ART keys reference files with the `new_uploads__` prefix, but the actual files exist WITHOUT that prefix. Just remove the prefix from the CG_ART value.

| CG_ART Key | Currently Points To | Should Point To |
|---|---|---|
| tommy_family_sukiyaki_pov | assets/new_uploads__tommy_family_sukiyaki_pov.jpg | assets/tommy_family_sukiyaki_pov.jpg |
| harrison_park_first_date_latest | assets/new_uploads__harrison_park_first_date_latest.jpg | assets/harrison_park_first_date_latest.jpg |
| harrison_job_offer_airi_laptop | assets/new_uploads__harrison_job_offer_airi_laptop.jpg | assets/harrison_job_offer_airi_laptop.jpg |
| harrison_job_offer_apartment_before_email | assets/new_uploads__harrison_job_offer_apartment_before_email.jpg | assets/harrison_job_offer_apartment_before_email.jpg |
| marcus_first_date_mall_gift | assets/new_uploads__marcus_first_date_mall_gift.jpg | assets/marcus_first_date_mall_gift.jpg |
| harrison_museum_date_latest | assets/new_uploads__harrison_museum_date_latest.jpg | assets/harrison_museum_date_latest.jpg |
| harrison_girlfriend_ask_latest | assets/new_uploads__harrison_girlfriend_ask_latest.jpg | assets/harrison_girlfriend_ask_latest.jpg |
| harrison_white_party_latest | assets/new_uploads__harrison_white_party_latest.jpg | assets/harrison_white_party_latest.jpg |
| harrison_white_roses_latest | assets/new_uploads__harrison_white_roses_latest.jpg | assets/harrison_white_roses_latest.jpg |
| tommy_karaoke_lilac_latest | assets/new_uploads__tommy_karaoke_lilac_latest.jpg | assets/tommy_karaoke_lilac_latest.jpg |
| tommy_ise_jingu_entrance_latest | assets/new_uploads__tommy_ise_jingu_entrance_latest.jpg | assets/tommy_ise_jingu_entrance_latest.jpg |
| tommy_ise_jingu_path_sunset_latest | assets/new_uploads__tommy_ise_jingu_path_sunset_latest.jpg | assets/tommy_ise_jingu_path_sunset_latest.jpg |
| tommy_hep5_game_fun | assets/new_uploads__tommy_hep5_game_fun.jpg | assets/tommy_hep5_game_fun.jpg |
| tommy_hep5_arcade_buttons_couple | assets/new_uploads__tommy_hep5_arcade_buttons_couple.jpg | assets/tommy_hep5_arcade_buttons_couple.jpg |
| tommy_arcade_bull_bridal_ren_interruption | assets/new_uploads__tommy_arcade_bull_bridal_ren_interruption.jpg | assets/tommy_arcade_bull_bridal_ren_interruption.jpg |
| tommy_planetarium_bg | assets/new_uploads__tommy_planetarium_bg.jpg | assets/tommy_planetarium_bg.jpg |
| tommy_planetarium_couple_latest | assets/new_uploads__tommy_planetarium_couple_latest.jpg | assets/tommy_planetarium_couple_latest.jpg |
| tommy_planetarium_handhold_close_latest | assets/new_uploads__tommy_planetarium_handhold_close_latest.jpg | assets/tommy_planetarium_handhold_close_latest.jpg |
| tommy_festival_market_bg | assets/new_uploads__tommy_festival_market_bg.jpg | assets/tommy_festival_market_bg.jpg |
| tommy_festival_solo_yukata_awake | assets/new_uploads__tommy_festival_solo_yukata_awake.jpg | assets/tommy_festival_solo_yukata_awake.jpg |
| tommy_festival_handhold_close_latest | assets/new_uploads__tommy_festival_handhold_close_latest.jpg | assets/tommy_festival_handhold_close_latest.jpg |
| tommy_festival_solo_stalls | assets/new_uploads__tommy_festival_solo_stalls.jpg | assets/tommy_festival_solo_stalls.jpg |
| tommy_festival_yukata_solo_dark | assets/new_uploads__tommy_festival_yukata_solo_dark.jpg | assets/tommy_festival_yukata_solo_dark.jpg |
| tommy_festival_secret_kiss | assets/new_uploads__tommy_festival_secret_kiss.jpg | assets/tommy_festival_secret_kiss.jpg |
| tommy_hidden_after_festival_kiss | assets/new_uploads__tommy_hidden_after_festival_kiss.jpg | assets/tommy_hidden_after_festival_kiss.jpg |
| ren_ferris_wheel_closeup_latest | assets/new_uploads__ren_ferris_wheel_closeup_latest.jpg | assets/ren_ferris_wheel_closeup_latest.jpg |
| ren_cherry_blossom_date_new | assets/new_uploads__ren_cherry_blossom_date_new.jpg | assets/ren_cherry_blossom_date_new.jpg |
| ren_cherry_blossom_kiss_new | assets/new_uploads__ren_cherry_blossom_kiss_new.jpg | assets/ren_cherry_blossom_kiss_new.jpg |
| ren_motorcycle_after_tommy_station | assets/new_uploads__ren_motorcycle_after_tommy_station.jpg | assets/ren_motorcycle_after_tommy_station.jpg |
| harrison_good_ending_couch_kiss | assets/new_uploads__harrison_good_ending_couch_kiss.jpg | assets/harrison_good_ending_couch_kiss.jpg |
| kenji_final_kiss_cherry | assets/new_uploads__kenji_final_kiss_cherry.jpg | assets/kenji_final_kiss_cherry.jpg |
| ren_festival_girlfriend_latest | assets/new_uploads__ren_festival_girlfriend_latest.jpg | assets/ren_festival_girlfriend_latest.jpg |
| tommy_ise_jingu_solo_cream_sweater | assets/new_uploads__tommy_ise_jingu_solo_cream_sweater.jpg | assets/tommy_ise_jingu_solo_cream_sweater.jpg |
| kenji_tommy_shadow_cherry | assets/new_uploads__kenji_tommy_shadow_cherry.jpg | assets/kenji_tommy_shadow_cherry.jpg |
| harrison_cafe_conversation_latest | assets/new_uploads__harrison_cafe_conversation_latest.jpg | assets/harrison_cafe_conversation_latest.jpg |
| harrison_girlfriend_ask_latest | assets/new_uploads__harrison_girlfriend_ask_latest.jpg | assets/harrison_girlfriend_ask_latest.jpg |
| harrison_good_ending_couch_kiss | assets/new_uploads__harrison_good_ending_couch_kiss.jpg | assets/harrison_good_ending_couch_kiss.jpg |
| harrison_job_offer_airi_laptop | assets/new_uploads__harrison_job_offer_airi_laptop.jpg | assets/harrison_job_offer_airi_laptop.jpg |
| harrison_job_offer_apartment_before_email | assets/new_uploads__harrison_job_offer_apartment_before_email.jpg | assets/harrison_job_offer_apartment_before_email.jpg |
| harrison_museum_date_latest | assets/new_uploads__harrison_museum_date_latest.jpg | assets/harrison_museum_date_latest.jpg |
| harrison_park_first_date_latest | assets/new_uploads__harrison_park_first_date_latest.jpg | assets/harrison_park_first_date_latest.jpg |
| harrison_white_party_latest | assets/new_uploads__harrison_white_party_latest.jpg | assets/harrison_white_party_latest.jpg |

## Fix 2: Truly missing assets (85 entries)

These CG_ART keys point to files that don't exist in ANY form. They need to either be:
- Generated/added to the assets folder, OR
- Remapped to an existing asset that fits the scene, OR
- Removed from the code

Many of these appear to be generic descriptive names (e.g., `romantic_sunset_by_the_beach`, `cozy_evening_in_a_modern_apartment`) that may have been placeholder names from an AI image generator. They are mostly in the gallery (GALLERY_ORDER) but 2 are used in SCENE_ASSETS:
- `golden_hour_stroll_by_the_river` (used in `tommy_boat_tease`)
- `romantic_sunset_by_the_beach` (used in `tommy_snoopy_cafe`)

## Fix 3: Speaker name duplication

The `shouldRepeatSpeakerInDialogue()` function adds the speaker name as a prefix to dialogue text (e.g., "Ren: It made you smile.") even though the speaker name is already shown in the speaker header above. This creates redundant text.

**Fix:** In the `startType()` function, change `shouldRepeatSpeakerInDialogue` to always return `false`, OR remove the call entirely:
```javascript
// Change this line:
if(shouldRepeatSpeakerInDialogue(p.speaker,body,p.hadExplicitSpeaker))body=p.speaker+': '+body;
// To:
// (remove the line entirely, or replace with:)
// body = body; // speaker is already shown in header
```
