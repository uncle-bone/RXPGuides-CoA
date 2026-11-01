# RXPGuides-CoA Roadmap

## Phase 1 — Compatibility audit
- [ ] Review the RXPGuides v4.11.29 source and its license/redistribution conditions.
- [ ] Inventory incompatible APIs, XML templates, libraries, and client-version checks.
- [ ] Create a 3.3.5a addon TOC and test a minimal loading path.
- [ ] Ensure the addon does not interfere with existing chat channels.

## Phase 2 — Working guide engine
- [ ] Render and navigate a small test guide.
- [ ] Validate accept/complete/turn-in events using the Conquest Reborn client.
- [ ] Persist guide position and user settings.
- [ ] Test maps/waypoints with Questie-X, Mapster/Magnify, DragonUI, and ElvUI.
- [ ] Measure memory use and avoid eager loading all guide content.

## Phase 3 — Guide data pipeline
- [ ] Define normalized guide-step format with provenance and confidence labels.
- [ ] Import current-realm Vanilla, TBC, Wrath, and custom CoA research as candidates.
- [ ] Resolve Pale Reach coordinate coverage discrepancy (14 vs 32 quests).
- [ ] Translate Pale Reach dependency graph into quest-chain branches.
- [ ] Separate pickup, objective, and hand-in steps; exclude placeholders.
- [ ] Verify scaling-mode behavior in game before enabling specialized routing.

## Phase 4 — Quality and release
- [ ] Test partially completed characters and relog recovery.
- [ ] Verify class recognition for all 21 CoA classes.
- [ ] Validate guide packs in game; mark unverified content accurately.
- [ ] Release installation-ready versioned ZIPs with a changelog.

**Status:** Planning; no completion claims implied.
