# Libris dictionary packs

Offline dictionary packs for the Libris e-book reader, built from Wiktionary
with `tools/dictionary/build_dictionary.py` (Libris repository).

- Data: Wiktionary contributors, CC BY-SA 4.0 (and GFDL), extracted with
  wiktextract via https://kaikki.org. These packs are distributed under the
  same licence (CC BY-SA 4.0).
- Layout: `manifest.json` on `main`; each pack is gzip-compressed SQLite split
  into parts that live on branches `<lang>-<n>`, served through jsDelivr:
  `https://cdn.jsdelivr.net/gh/hudaiapa88/libris-dict@<branch>/<file>`.
