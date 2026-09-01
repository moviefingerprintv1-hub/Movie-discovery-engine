# Movie Fingerprint V1

The Movie Fingerprint is the structured description of a movie or TV show used by the Movie Discovery Engine.

The goal is to describe not only what a title is about, but what it looks like, feels like, and what kind of viewing experience it creates.

Every subjective attribute should contain:

- Strength: 0.00–1.00
- Confidence: 0.00–1.00
- Evidence/source where possible

---

## 1. Identity

- Title
- Original title
- Movie or TV
- Release date
- Production year
- Runtime
- Country
- Language
- Genres
- Age rating
- Production companies
- Franchise/series

For TV:

- Seasons
- Episodes
- Episode runtime
- Current status

---

## 2. People

- Actors
- Director
- Writers
- Creator/showrunner
- Cinematographer
- Production designer
- Costume designer
- Composer
- Editor

---

## 3. Time

Distinguish between when a title was produced and when its story takes place.

Examples:

- Ancient
- Medieval
- Victorian
- 1920s
- 1950s
- 1960s
- 1980s
- Present day
- Near future
- Far future

Where possible include exact years/ranges.

Also measure:

- Historical accuracy
- Stylization
- Alternate history
- Era influences

A title may contain influences from several eras simultaneously.

---

## 4. Place & Setting

- Country
- Region
- City
- Fictional location

Environment examples:

- Urban
- Suburban
- Small town
- Rural
- Wilderness
- Coastal
- Desert
- Mountains
- Forest
- Space
- Space station
- Underground
- Single location

Additional characteristics:

- Wealth level
- Industrialization
- Population density
- Indoor/outdoor emphasis
- Claustrophobic/expansive

---

## 5. Visual Fingerprint

### Architecture

Examples:

- Mid-century modern
- Art Deco
- Victorian
- Gothic
- Brutalist
- Bauhaus
- Industrial
- Futuristic

### Technology

Distinguish between:

- Actual technological sophistication
- Visible technological appearance

Examples:

- Analog
- Mechanical
- Steam
- Vacuum tube
- Atomic age
- Digital
- Near future
- Advanced futuristic

Technology aesthetics:

- Retrofuturism
- Steampunk
- Dieselpunk
- Atompunk
- Cyberpunk
- Cassette futurism

### Objects

Examples:

- Classic cars
- Trains
- Aircraft
- Spaceships
- CRT monitors
- Rotary phones
- Neon signs
- Diners
- Arcades

### Clothing

- Historical period
- Style
- Formality
- Uniforms
- Workwear
- Futuristic clothing

### Cinematography

Measure characteristics such as:

- Bright / dark
- Warm / cold
- Naturalistic / stylized
- Static / kinetic
- Clean / gritty
- Minimalist / visually dense
- Handheld
- Long takes
- Symmetry
- Black and white
- Selective color

---

## 6. Aesthetic Fingerprint

Examples:

- Americana
- Gothic
- Dark academia
- Solarpunk
- Retrofuturism
- Space age
- Fairytale
- Film noir
- Neo-noir
- Western
- Y2K
- Mid-century modern

Multiple aesthetics may coexist.

---

## 7. Atmosphere

Examples:

- Cozy
- Dreamlike
- Eerie
- Oppressive
- Whimsical
- Mysterious
- Romantic
- Nostalgic
- Melancholic
- Hopeful
- Lonely
- Intimate
- Grand
- Surreal
- Peaceful
- Chaotic
- Playful

Atmosphere may change during the title.

Record an atmosphere trajectory when appropriate.

---

## 8. Emotional Fingerprint

Describe the emotions the title tends to create in the viewer.

Examples:

- Wonder
- Curiosity
- Discovery
- Hope
- Nostalgia
- Excitement
- Anxiety
- Comfort
- Awe
- Inspiration
- Melancholy
- Loneliness
- Triumph
- Relief

More specific emotional experiences can include:

- Childlike wonder
- Joy of experiencing something new
- Longing for another place or time
- Pleasant melancholy
- Awe at scale
- Comfort through familiarity

Record emotional trajectory where appropriate:

Beginning -> Middle -> Ending

---

## 9. Story Fingerprint

Plot types:

- Mystery
- Quest
- Revenge
- Survival
- Coming of age
- Heist
- Investigation
- Road trip
- Fish out of water

Themes can include:

- Family
- Identity
- Mortality
- Friendship
- Ambition
- Technology
- War
- Love
- Grief
- Freedom
- Social conformity

Measure:

- Character-driven
- Plot-driven
- World-driven
- Idea-driven
- Linear/nonlinear
- Simple/complex
- Predictable/unpredictable

---

## 10. Viewing Experience

Measure:

- Pacing
- Complexity
- Emotional heaviness
- Visual importance
- Worldbuilding importance
- Attention required
- Easy/challenging viewing
- Intellectual stimulation
- Rewatchability

Situational characteristics can include:

- Comfort watch
- Date night
- Family viewing
- Late night
- Rainy day
- Sunday afternoon
- Background friendly
- Requires full attention
- Good with friends

---

## 11. Content

Measure intensity where appropriate:

- Violence
- Gore
- Horror
- Jump scares
- Sex
- Nudity
- Profanity
- Drug use
- Disturbing imagery

---

## 12. Human Response

Keep different evidence sources separate.

### Professional Critics

- Common praise
- Common criticism
- Frequently mentioned characteristics
- Critical consensus

### General Audience

- Common praise
- Common criticism
- Frequently mentioned characteristics

### Enthusiast Communities

Sources may include movie communities, Reddit, forums, and other relevant public discussions where permitted.

Possible signals:

- Cult following
- Underrated
- Overrated
- Comfort movie
- Worldbuilding praised
- Visuals praised
- Story criticized
- Divisive ending
- Rewatchability

Do not treat individual comments as universal opinion.

Look for patterns across multiple sources.

---

## 13. Trajectories

A fingerprint should be capable of describing change over time.

Examples:

Visual:
Monochrome -> selective color -> full color

Atmosphere:
Comfort -> curiosity -> conflict -> liberation

Emotion:
Wonder -> tension -> sadness -> hope

World:
Stable -> disrupted -> transformed

---

## 14. Confidence & Evidence

Every inferred characteristic should distinguish between:

### Strength

How strongly the characteristic applies.

Example:

Retrofuturism: 0.92

### Confidence

How confident we are that the assessment is correct.

Example:

Confidence: 0.96

Where possible, store the evidence that produced the assessment.

Possible evidence sources:

- Official metadata
- Creator/production information
- Professional criticism
- Audience reviews
- Community discussion
- Approved visual analysis
- AI inference

---

## Core Principle

The Movie Fingerprint should answer:

"What is this movie or TV show?"

but also:

"What does it look like?"

"What does its world feel like?"

"What does watching it feel like?"

"How does that experience change over time?"

and ultimately:

"Why might this particular person want to watch it right now?"
