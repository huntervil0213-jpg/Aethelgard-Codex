# Aethelgard Codex

The master database for the Aethelgard novel project: original languages, vocabulary, alphabet/script, races, creatures, cultures, characters, locations, magic, history, and terminology.

## Language standard

The primary constructed language being developed here is the High Elven/Court language used in Kael-Vossen. It is original to Aethelgard, with its own vocabulary, grammar, phonology, registers, and writing system. It is deliberately distinct from Common and from real-world languages.

The language data includes Romanized forms for manuscript use, stable word IDs, Common meanings, grammar notes, formal and informal registers, military/diplomatic vocabulary, idioms, curses, and translator mappings.

## Translator standard

Translator data uses explicit phrase/word mappings and deterministic romanization so the language can later power a searchable Common ↔ High Elven translator. We are not treating repeated fantasy syllables as a language; new vocabulary must follow the established system and avoid accidental English/Common-like forms.

## Canon policy

`canon` entries are established story facts. `development` entries are proposed database material that can be refined through manuscript use. The manuscript's established meaning, plot, lore, character identity, and reveals always take priority.

## Structure

- `data/language.json` — language system, alphabet, grammar, vocabulary, phrases, and translator mappings
- `data/world.json` — races, creatures, cultures, factions, locations, magic, and terminology
- `data/characters.json` — character reference data
- `data/canon-rules.json` — continuity and terminology rules
- `index.html` — searchable Codex interface

## Expansion

The Codex is modular so future chapters can add material without rebuilding the project. D&D-inspired races and creatures may be catalogued, but Aethelgard's versions, terminology, lore, and descriptions remain original to the novel rather than copying setting text.
