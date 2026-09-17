# Audiobook Listener-Fit Framework

An open framework for describing audiobook quality, listening characteristics, evidence confidence, and listener fit.

This repository documents a simplified, reusable version of the listening-focused framework developed by [Recommended Audiobooks](https://recommendedaudiobooks.com/).

## Why this exists

Traditional star ratings compress many different parts of an audiobook experience into a single number. Audiobook listeners may also care about narration, pacing, attention demands, mood, complexity, production, and whether a recording fits a particular listening situation.

This project separates those concepts so they can be described more transparently.

## Framework

The framework is organized into three layers:

1. **Quality dimensions** — factors that contribute to the overall Recommendation DNA quality score.
2. **Listening profile** — descriptive traits that explain what the listening experience may feel like.
3. **Listener fit** — indicators describing situations or listeners for whom an audiobook may be a stronger match.

Evidence confidence is tracked separately so a score or trait does not imply more certainty than the available evidence supports.

## Repository contents

* [`methodology.md`](methodology.md) — overview of the framework and scoring approach
* [`criteria.md`](criteria.md) — definitions of the quality, profile, fit, and confidence fields
* [`examples/example-audiobook.json`](examples/example-audiobook.json) — illustrative audiobook record
* [`examples/example-profile.json`](examples/example-profile.json) — illustrative listener-fit profile
* [`schema/audiobook-listener-fit.schema.json`](schema/audiobook-listener-fit.schema.json) — JSON Schema for structured records

## Recommendation DNA

Recommendation DNA is the methodology used by Recommended Audiobooks to separate audiobook quality from listening characteristics and listener fit.

Read the full public methodology:

**[How Recommendation DNA Works](https://recommendedaudiobooks.com/how-recommendation-dna-works/)**

Explore the publication:

**[RecommendedAudiobooks.com](https://recommendedaudiobooks.com/)**

## Important note

The example records in this repository are fictional and are provided only to demonstrate the structure. They should not be treated as reviews, ratings, or evidence about a real audiobook.

## License

## Citation and DOI

The Audiobook Listener-Fit Framework is archived on Zenodo and has a persistent Digital Object Identifier (DOI).

**DOI:** [10.5281/zenodo.22815435](https://doi.org/10.5281/zenodo.22815435)

If you use or reference this framework, please cite the archived Zenodo release or use the citation information provided by GitHub.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.22815435.svg)](https://doi.org/10.5281/zenodo.22815435)


This repository is released under the MIT License. See [`LICENSE`](LICENSE).

