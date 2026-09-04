# DFP TC Burn — releases

The update feed for **DFP TC Burn**, and the builds it points at. No source
lives here; the app is developed in a private repository.

- `appcast.xml` — the Sparkle feed the app reads. Published **after** the
  GitHub release it names, so it never advertises a download that is not
  there yet.
- Releases — each one carries the notarized, stapled app as a zip.

Every build is signed by DF Productions' Developer ID, notarized by Apple,
and additionally signed with an EdDSA key whose private half never leaves
the developer's Keychain. The app refuses an update that fails either check.

Nothing here reports anything about you. The app fetches this feed and
nothing else; there is no account and no telemetry.
