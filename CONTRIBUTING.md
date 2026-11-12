# Contributing voice packs

Thank you for helping expand CatQuest Extended with new voices and languages.

## What belongs here

This repository is a public catalog and review hub. Contributions may add or
change:

- pack metadata and manifests;
- voice actor and license information;
- a new language or client profile;
- a proposed voice, replacement track, or correction;
- documentation and validation notes.

Do not commit full audio packs or bulk `.ogg`, `.mp3`, `.wav`, or `.flac` files.
The repository intentionally contains no large audio distribution files.

## Three ways to participate

### 1. Request a missing quest voice

Open the **Quest voice request** issue template. Add the quest ID, locale, client
profile, and a short reason why the quest is useful or urgent. You do not need to
record anything. Maintainers use these requests to build the public priority queue.

### 2. Submit a ready recording

Open the **Ready voice contribution** template. Add the quest or track identifier,
language, voice actor, license, and a review link or short sample when it is legal
to share. Maintainers check the text match and rights, then add approved audio to a
versioned release outside Git.

### 3. Propose another language

Open the **New language pack** template. State the WoW locale, target client, scope
of the translation/recording, sample coverage, contributors, and redistribution
license. A language can start as a small pilot and grow as more tracks are ready.

The issue templates are intentionally written for non-technical contributors. A
maintainer can help convert an approved proposal into the JSON metadata used by the
catalog.

## Before opening a Pull Request

1. Confirm that you created the recording or have permission to redistribute it.
2. Record the language, client profile, voice actor, source, and license.
3. Use a stable track identifier and follow [PACK-SPEC.md](PACK-SPEC.md).
4. Include a short sample or private review link only when it is legally shareable.
5. Explain whether the proposal adds a new track or replaces an existing one.

For a first proposal, opening an Issue is preferred. Maintainers can help choose
the correct metadata and track identifiers before a pack is prepared.

## Review and publication

Maintainers check text matching, audio quality, client compatibility, attribution,
and redistribution rights. Approved changes are assigned a pack version, packaged
outside Git, and published through the CatQuest Extended download page.

Submitting a Pull Request does not grant permission to redistribute material that
you do not own or have licensed. The contributor remains responsible for the
rights and credits of submitted material.
