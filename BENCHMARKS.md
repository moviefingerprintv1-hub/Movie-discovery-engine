# Movie Discovery Engine — Benchmarks

These benchmark searches are used to test whether the recommendation engine understands complex viewing requests.

The benchmarks should remain unchanged so different versions of the engine can be compared fairly.

---

# Benchmark 001 — 1960s Future / First Coca-Cola

## Original User Request

"I would like to watch something futuristic, a movie that takes place in a futuristic world but the technology, architecture and everything look like they did in the 1960s.

I would like the movie to be made post 1995.

I also want the movie to make me feel like I'm a little kid who has been introduced to Coca-Cola for the first time and it's a whole new experience to me."

## Interpretation

### Must Have

- Movie
- Produced after 1995
- Futuristic world
- Strong retrofuturistic design
- Technology visually influenced by the 1960s
- Architecture/design visually influenced by the 1960s

### Important

- Wonder
- Discovery
- Novelty
- Childlike curiosity
- Excitement
- Feeling of experiencing something completely new

### Nice to Have

- Optimistic tone
- Space-age design
- Analog technology
- Mid-century modern architecture
- Period-inspired clothing
- Vintage-inspired vehicles

## Important Semantic Rule

"Coca-Cola" is NOT a literal search requirement.

The phrase describes an emotional experience.

The engine should interpret it as concepts including:

- Novelty
- Wonder
- Excitement
- Discovery
- Childlike curiosity
- Sensory fascination

## Failure Conditions

The engine fails this benchmark if it:

- Recommends movies simply because they were made in the 1960s
- Ignores the futuristic requirement
- Treats Coca-Cola as a literal subject requirement
- Recommends generic science fiction without the requested aesthetic
- Ignores the emotional experience
- Allows personalized taste to override explicit Must Have requirements

## Known Test Titles

### Gattaca

Expected:

- Extremely strong visual/world match
- Strong retrofuturistic match
- Weak-to-moderate emotional match
- Serious/melancholic tone should reduce final score

### Pleasantville

Expected:

- Extremely strong emotional match
- Strong retro-American visual match
- Fails futuristic-world Must Have
- Should NOT appear as a normal Precision recommendation
- May appear as an Outside Pick in Explore mode

### 2001: A Space Odyssey

Expected:

- Extremely strong 1960s vision-of-the-future match
- Fails production-date Must Have
- Should NOT appear as a normal Precision recommendation
