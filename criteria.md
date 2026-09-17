# Criteria Reference

This document defines the main fields used by the Audiobook Listener-Fit Framework.

## Quality dimensions

### Narration Quality — 17.8%

Assessment of the narrator or cast performance for the verified recording, including delivery, clarity, character differentiation, consistency, and suitability for the material when supported by evidence.

### Story Quality — 17.1%

Assessment of the underlying story or nonfiction content, including structure, execution, coherence, and overall effectiveness.

### Character Development — 12.5%

The extent to which important characters are developed in a convincing, distinctive, or meaningful way.

### Emotional Impact — 11.8%

The degree to which the work creates sustained emotional engagement or resonance.

### Audio Production — 11.2%

Recording-specific production characteristics such as clarity, editing, balance, consistency, and other audible production elements.

### Originality — 10.5%

The degree to which the work presents distinctive ideas, execution, structure, perspective, or creative choices.

### Replay Value — 9.9%

The degree to which the audiobook may reward or invite repeat listening. This should be based on supported evidence rather than popularity alone.

### World Building — 9.2%

The effectiveness and depth of the setting, environment, systems, or contextual world created by the work.

## Listening-profile traits

Listening-profile traits are descriptive. They do **not** raise or lower the quality score merely because they are more prominent.

Suggested fields include:

* `story_pacing`
* `complexity`
* `attention_demand`
* `accessibility`
* `immersion`
* `humor`
* `romance`
* `emotional_intensity`
* `technical_detail`

Values may be represented with controlled labels such as `low`, `moderate`, and `high`.

## Listener-fit indicators

Listener-fit fields describe possible use cases or listening situations.

Suggested fields include:

* `commute`
* `road_trip`
* `workout`
* `bedtime`
* `focused_listening`
* `background_friendly`

Suggested values are `low`, `moderate`, `high`, or `unknown`.

These indicators should not be interpreted as quality rankings.

## Evidence confidence

Suggested confidence states:

* `developing` — useful information exists, but important audiobook-specific evidence remains limited;
* `moderate` — multiple relevant sources support meaningful parts of the profile;
* `strong` — substantial relevant evidence supports the profile, including recording-specific evidence where required.

Implementations should document their own thresholds rather than treating these labels as universal scientific categories.

## Edition identity

Whenever narration or audio production is described, the record should identify the audiobook edition as specifically as possible.

Useful fields can include:

* narrator or cast
* format
* release date
* runtime
* publisher
* ISBN
* ASIN or another stable recording identifier

## Reference

For the full public Recommendation DNA explanation, see:

[How Recommendation DNA Works](https://recommendedaudiobooks.com/how-recommendation-dna-works/)
