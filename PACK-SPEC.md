# Voice-pack metadata specification

The catalog uses JSON metadata so that the website and tooling can show available
packs without downloading audio archives.

## Required pack fields

Each published pack entry should include:

```json
{
  "id": "CatQuestExtended_Voices",
  "name": "CatQuest Extended Voices",
  "version": "1.3.0-extended.2",
  "status": "published",
  "locales": ["ruRU"],
  "clientProfiles": ["3.3.5a"],
  "modules": ["Voices"],
  "license": "CC BY-NC-SA 4.0",
  "attribution": "See the pack attribution and upstream project page",
  "downloadUrl": "https://catquest.mvse.ws/downloads/CatQuestExtended_Voices.zip",
  "sizeBytes": 1491328329,
  "sha256": "36b3df45659a40f898b75f5b63aa51c1eb7f25ec87c4660ac8340d2cd91530fe"
}
```

## Naming rules

- The canonical folder and archive name is `CatQuestExtended_Voices`.
- A pack folder must match the archive root directory.
- Locale values use WoW locale identifiers such as `ruRU`, `enUS`, or `zhCN`.
- Client profiles identify the target client, for example `3.3.5a`, `tbc`, or
  `mop`.
- Every downloadable release must have a SHA-256 checksum and a declared license.

## Track proposals

Track proposals should use the existing quest or content identifier and include
the locale, speaker/voice, source text reference, and status. Do not commit the
audio itself to the catalog repository. Maintainers exchange review material
separately and publish only approved releases.
