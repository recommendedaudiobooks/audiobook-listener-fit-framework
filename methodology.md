# Methodology

## Purpose

The Audiobook Listener-Fit Framework provides a structured way to describe an audiobook without collapsing every aspect of the experience into a single star rating.

It is derived from the public Recommendation DNA methodology used by [Recommended Audiobooks](https://recommendedaudiobooks.com/).

## Four concepts

### 1. Quality

Quality dimensions describe aspects of the audiobook that may contribute to an overall quality assessment. The current public Recommendation DNA framework uses eight weighted dimensions:

| Dimension             | Weight |
| --------------------- | -----: |
| Narration Quality     |  17.8% |
| Story Quality         |  17.1% |
| Character Development |  12.5% |
| Emotional Impact      |  11.8% |
| Audio Production      |  11.2% |
| Originality           |  10.5% |
| Replay Value          |   9.9% |
| World Building        |   9.2% |

The weights total 100%.

### 2. Listening profile

Listening-profile fields describe what the audiobook experience may feel like rather than whether the audiobook is objectively better or worse.

Examples can include:

* pacing
* tone
* humor
* romance
* complexity
* accessibility
* attention demand
* immersion

A higher descriptive value means a trait is more prominent. It does not automatically mean the audiobook is better.

### 3. Listener fit

Listener-fit indicators describe contexts in which an audiobook may be a useful match.

Examples can include:

* commute listening
* road trips
* workouts
* bedtime
* focused listening
* casual or background-friendly listening

Listener fit is intentionally separate from the quality score.

### 4. Evidence confidence

Evidence confidence describes how strongly the available evidence supports the published profile.

A framework should distinguish between:

* well-supported recording-specific evidence
* broader book-level evidence
* limited or developing evidence

Confidence should not be treated as a quality rating.

## Weighted quality score

When all required quality dimensions have numeric values, an illustrative weighted score can be calculated as:

`weighted score = sum(dimension score × dimension weight) / 100`

The schema uses a 0–10 scale for numeric examples. Implementations may choose a different internal representation as long as it is clearly documented.

## Evidence principles

A responsible implementation should:

1. distinguish the book from the specific audiobook recording;
2. avoid narration claims when recording-specific evidence is unavailable;
3. keep descriptive listening traits separate from quality scoring;
4. expose uncertainty rather than filling evidence gaps with assumptions;
5. update records when stronger evidence becomes available.

## Source methodology

The authoritative public explanation of Recommendation DNA is maintained here:

[How Recommendation DNA Works](https://recommendedaudiobooks.com/how-recommendation-dna-works/)
