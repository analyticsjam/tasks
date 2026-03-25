## Backlog
- [ ] Lazy-load playlist dropdown on quick_flux #frontend
  - [ ] Move playlist loading to async AJAX after page render
  - [ ] Use existing /dropdown_data endpoint
  - [ ] Pass spotyid into get_playlists() to eliminate redundant /me call
- [ ] Add fluxtape account token for editing fluxtape-owned playlists #auth
- [ ] Investigate Jenntron 429 rate limiting (393 hits last run) #performance

## In Progress

## Done
- [x] Add artist blocklist to playlist generation done:2026-03-23
- [x] Create seed_discover.py and seed_add.py done:2026-03-21
- [x] Snapshot Redis cache to CSV (audio features) done:2026-03-21
- [x] Create cron_check.py for monitoring playlist runs done:2026-03-22
- [x] Review and clean up Haltron seed playlist done:2026-03-23
- [x] Review Jenntron seed playlist done:2026-03-24
