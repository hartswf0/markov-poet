# 🛡 6-Dimensional LEGOS Ground Truth Linter Report

This linter measures the strict narrative alignment between the **Ground Truth Written Poem Lines** and every candidate video shot across **Location (L), Entity (E), Goal (G), Obstacle (O), Shift (S), and Solution (U)**.

## 📊 Global Audit Summary
- 🟢 **CANONICAL FIT (Belongs in Poem)**: `35` evaluations
- 🟡 **METAPHORICAL DRIFT (Thematic Echo)**: `64` evaluations
- 🔴 **ANACHRONISTIC OUTLIER (Does NOT Belong)**: `1791` evaluations

---

## Suite 01 — OUT OF LIFE
> *"What we've made, we don't want. What we've sold — to the world, to ourselves — doesn't exist. I look for a way out: through the hallways, within the drawers, and fire escapes. The vape gathers, inside and out. My vision blurs. I move toward the window — and you only get further away. More haze. What isn't mine, I still can not give."*

### 🎯 Ground Truth Poem LEGOS Baseline
- **L**: Domestic Apartment Hallways, Drawers, Fire Escapes & Misty Bedroom Window.
- **E**: The Disillusioned Poet & Departing Partner ('You').
- **G**: Finding a Way Out — Seeking an authentic exit from manufactured pretenses, false commodities, and domestic stasis.
- **O**: Suffocating Domestic Haze & Emotional Drift — Vape smoke and detachment blurring vision as the partner moves further away.
- **S**: Moving toward the window only for the distance between lovers to widen into an impenetrable haze.
- **U**: Severing False Obligations — Acknowledging the departure and accepting: 'What isn't mine, I still can not give.'

### 🔍 Top Evaluated Candidates & Linter Verdicts
| Shot ID | Category | Total Score | L | E | G | O | S | U | Verdict |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| `e01016b7` | POET_DIM_BEDROOM | **80%** | PASS | PASS | PASS | PASS | DRIFT | DRIFT | CANONICAL_FIT |
| `05df5f1b` | POET_DIM_BEDROOM | **80%** | PASS | PASS | PASS | PASS | DRIFT | DRIFT | CANONICAL_FIT |
| `7a701277` | POET_DIM_BEDROOM | **80%** | PASS | PASS | PASS | PASS | DRIFT | DRIFT | CANONICAL_FIT |
| `8342f352` | POET_DIM_BEDROOM | **80%** | PASS | PASS | PASS | PASS | DRIFT | DRIFT | CANONICAL_FIT |
| `c42d545f` | POET_DIM_BEDROOM | **80%** | PASS | PASS | PASS | PASS | DRIFT | DRIFT | CANONICAL_FIT |
| `c81cb1b0` | POET_DIM_BEDROOM | **80%** | PASS | PASS | PASS | PASS | DRIFT | DRIFT | CANONICAL_FIT |
| `46782136` | POET_DIM_BEDROOM | **80%** | PASS | PASS | PASS | PASS | DRIFT | DRIFT | CANONICAL_FIT |
| `a5a18f9d` | POET_DIM_BEDROOM | **73%** | PASS | PASS | PASS | PASS | DRIFT | DRIFT | CANONICAL_FIT |

### ❌ Outliers Flagged for Pruning (Does NOT Belong in this Suite)

- 🔴 **`222c8cca` (TEMPORAL_ECHO_TRAIL)** — Score: `31%` | Issues: *Location 'Metropolitan Night Avenue — Ur...' does not match poem setting (bedroom, hallway, drawer).*
- 🔴 **`53666716` (TEMPORAL_ECHO_TRAIL)** — Score: `31%` | Issues: *Location 'Metropolitan Night Avenue — Ur...' does not match poem setting (bedroom, hallway, drawer).*
- 🔴 **`2255ec6b` (TEMPORAL_ECHO_TRAIL)** — Score: `31%` | Issues: *Location 'Metropolitan Night Avenue — Ur...' does not match poem setting (bedroom, hallway, drawer).*
- 🔴 **`8aff03e4` (ROOFTOP_STEAM_ALLEY)** — Score: `30%` | Issues: *Location 'Industrial Rooftop Alleyway — ...' does not match poem setting (bedroom, hallway, drawer).*

---

## Suite 02 — FLASHING LIGHTS
> *"It was the type of silent scream a trapped lover makes to escape: a pending marriage, a concussion, a set of walls caving inward. An emergency call while tossing and turning — the silent call a man makes to the mirror after midnight, to digest a truth. A truth he could neither alter nor change. What isn't mine, I still can not give."*

### 🎯 Ground Truth Poem LEGOS Baseline
- **L**: Midnight Insomnia Bedroom with Caving Walls & Solitary Bathroom Mirror.
- **E**: The Trapped Lover / Conflicted Man Facing His Reflection.
- **G**: Digesting the Unspoken Truth — Escaping the claustrophobic pressure of an impending marriage and internal concussion.
- **O**: Caving Walls & Tossing Insonmia — The paralyzing dread of breaking a social commitment and causing pain.
- **S**: The silent call made directly into the mirror after midnight during an emergency psychological crisis.
- **U**: Solitary Confrontation — Facing the mirror to admit the unalterable truth that love cannot be forced.

### 🔍 Top Evaluated Candidates & Linter Verdicts
| Shot ID | Category | Total Score | L | E | G | O | S | U | Verdict |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| `6750a5d1` | SUBWAY_SPRINT_STAIRS | **47%** | PASS | PASS | DRIFT | MISMATCH | MISMATCH | MISMATCH | METAPHORICAL_DRIFT |
| `34051c38` | SKELETAL_PROFILE | **26%** | PASS | DRIFT | MISMATCH | MISMATCH | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |
| `516f88fd` | SKELETAL_PROFILE | **26%** | PASS | DRIFT | MISMATCH | MISMATCH | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |
| `80b32fdf` | SKELETAL_PROFILE | **26%** | PASS | DRIFT | MISMATCH | MISMATCH | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |
| `f91d5823` | SKELETAL_PROFILE | **26%** | PASS | DRIFT | MISMATCH | MISMATCH | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |
| `2474f1b5` | POET_DIM_BEDROOM | **17%** | DRIFT | DRIFT | MISMATCH | MISMATCH | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |
| `7534249f` | POET_DIM_BEDROOM | **17%** | DRIFT | DRIFT | MISMATCH | MISMATCH | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |
| `0a69c776` | POET_DIM_BEDROOM | **17%** | DRIFT | DRIFT | MISMATCH | MISMATCH | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |

### ❌ Outliers Flagged for Pruning (Does NOT Belong in this Suite)

- 🔴 **`34051c38` (SKELETAL_PROFILE)** — Score: `26%` | Issues: *Visual narrative pursues a goal alien to this poem's intention.*
- 🔴 **`516f88fd` (SKELETAL_PROFILE)** — Score: `26%` | Issues: *Visual narrative pursues a goal alien to this poem's intention.*
- 🔴 **`80b32fdf` (SKELETAL_PROFILE)** — Score: `26%` | Issues: *Visual narrative pursues a goal alien to this poem's intention.*
- 🔴 **`f91d5823` (SKELETAL_PROFILE)** — Score: `26%` | Issues: *Visual narrative pursues a goal alien to this poem's intention.*

---

## Suite 03 — HOW TO BREAK OFF AN ENGAGEMENT
> *"Ode to forever — a tambourine sounds off an empty temple, empty choir stands, empty prayer lines. And abandoned baptism pools. It flies in through the rose window — still whole. A broken promise."*

### 🎯 Ground Truth Poem LEGOS Baseline
- **L**: Abandoned Sacred Sanctuary — Empty choir stands, deserted prayer lines, dry baptism pools, and stained-glass rose window.
- **E**: The Betrothed Soul Severing the Lifelong Vow.
- **G**: Graceful Dissolution of the Vow — Releasing the heavy mantle of 'forever' without shattering his inner spirit.
- **O**: Sanctified Permanence — The immense moral and spiritual weight of empty altars and ceremonial expectations.
- **S**: A lone tambourine vibrates off empty temple walls, and memory flies unbroken through the stained-glass rose window.
- **U**: Sacred Release — Acknowledging that the sanctuary is empty, allowing the broken promise to rest whole without guilt.

### 🔍 Top Evaluated Candidates & Linter Verdicts
| Shot ID | Category | Total Score | L | E | G | O | S | U | Verdict |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| `d847a1b8` | BEACH_HEART_RIBBON | **67%** | PASS | PASS | DRIFT | DRIFT | DRIFT | DRIFT | CANONICAL_FIT |
| `447a4780` | BEACH_HEART_RIBBON | **67%** | PASS | PASS | DRIFT | DRIFT | DRIFT | DRIFT | CANONICAL_FIT |
| `882db957` | BEACH_HEART_RIBBON | **67%** | PASS | PASS | DRIFT | DRIFT | DRIFT | DRIFT | CANONICAL_FIT |
| `0b025dc2` | RED_FLUID_SUBMERSION | **22%** | DRIFT | DRIFT | MISMATCH | MISMATCH | DRIFT | MISMATCH | ANACHRONISTIC_OUTLIER |
| `db9c23a4` | POET_DIM_BEDROOM | **17%** | DRIFT | DRIFT | MISMATCH | MISMATCH | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |
| `5b9ec655` | BEDROOM_FOG_GESTURE | **17%** | DRIFT | DRIFT | MISMATCH | MISMATCH | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |
| `222c8cca` | TEMPORAL_ECHO_TRAIL | **17%** | MISMATCH | PASS | MISMATCH | MISMATCH | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |
| `53666716` | TEMPORAL_ECHO_TRAIL | **17%** | MISMATCH | PASS | MISMATCH | MISMATCH | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |

### ❌ Outliers Flagged for Pruning (Does NOT Belong in this Suite)

- 🔴 **`0b025dc2` (RED_FLUID_SUBMERSION)** — Score: `22%` | Issues: *Visual narrative pursues a goal alien to this poem's intention.*
- 🔴 **`db9c23a4` (POET_DIM_BEDROOM)** — Score: `17%` | Issues: *Visual narrative pursues a goal alien to this poem's intention.*
- 🔴 **`5b9ec655` (BEDROOM_FOG_GESTURE)** — Score: `17%` | Issues: *Visual narrative pursues a goal alien to this poem's intention.*
- 🔴 **`222c8cca` (TEMPORAL_ECHO_TRAIL)** — Score: `17%` | Issues: *Location 'Metropolitan Night Avenue — Ur...' does not match poem setting (temple, choir, altar).; Visual narrative pursues a goal alien to this poem's intention.*

---

## Suite 04 — NEVERMORE
> *"What if I followed this trail, to where the broken pieces have washed ashore — and the ashes of expired wildfires cover sands, and debris lifted from the night sea water's floor. The waves calm to folded whispers; the winds mute the trees. The right level of silence, to find a throbbing heart — it used to be mine. I lift it with care: nevermore."*

### 🎯 Ground Truth Poem LEGOS Baseline
- **L**: Night Ocean Shoreline — Wildfire ashes over sand and ancient debris washed ashore from the seabed.
- **E**: The Shoreline Wanderer / Recoverer of the Lost Heart.
- **G**: Reclaiming the Lost Heart — Tracking washed-up wreckage to locate and salvage his former capacity for feeling.
- **O**: Wildfire Ashes & Sea Debris — The desolate wreckage of past burns and the roar of ocean waves obscuring the heart.
- **S**: Waves calm to folded whispers and winds mute the trees, producing the exact silence needed to hear the heart throbbing in the sand.
- **U**: Sacred Reclamation — Lifting the recovered beating heart with delicate care and sealing the boundary: 'nevermore.'

### 🔍 Top Evaluated Candidates & Linter Verdicts
| Shot ID | Category | Total Score | L | E | G | O | S | U | Verdict |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| `63d387a4` | POET_CATHEDRAL_CROWS | **40%** | PASS | PASS | DRIFT | MISMATCH | MISMATCH | MISMATCH | METAPHORICAL_DRIFT |
| `84592d51` | POEMS_TITLE_CARD | **35%** | DRIFT | PASS | MISMATCH | MISMATCH | DRIFT | DRIFT | METAPHORICAL_DRIFT |
| `9d16432c` | POEMS_TITLE_CARD | **35%** | DRIFT | PASS | MISMATCH | MISMATCH | DRIFT | DRIFT | METAPHORICAL_DRIFT |
| `e3e52e35` | POEMS_TITLE_CARD | **35%** | DRIFT | PASS | MISMATCH | MISMATCH | DRIFT | DRIFT | METAPHORICAL_DRIFT |
| `8478f997` | POEMS_TITLE_CARD | **35%** | DRIFT | PASS | MISMATCH | MISMATCH | DRIFT | DRIFT | METAPHORICAL_DRIFT |
| `8e5ebf2d` | POET_DIM_BEDROOM | **21%** | DRIFT | DRIFT | MISMATCH | DRIFT | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |
| `8aff03e4` | ROOFTOP_STEAM_ALLEY | **17%** | DRIFT | DRIFT | MISMATCH | MISMATCH | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |
| `d1dfc1d0` | ROOFTOP_STEAM_ALLEY | **17%** | DRIFT | DRIFT | MISMATCH | MISMATCH | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |

### ❌ Outliers Flagged for Pruning (Does NOT Belong in this Suite)

- 🔴 **`8e5ebf2d` (POET_DIM_BEDROOM)** — Score: `21%` | Issues: *Visual narrative pursues a goal alien to this poem's intention.*
- 🔴 **`8aff03e4` (ROOFTOP_STEAM_ALLEY)** — Score: `17%` | Issues: *Visual narrative pursues a goal alien to this poem's intention.*
- 🔴 **`d1dfc1d0` (ROOFTOP_STEAM_ALLEY)** — Score: `17%` | Issues: *Visual narrative pursues a goal alien to this poem's intention.*
- 🔴 **`eb298ed7` (ROOFTOP_STEAM_ALLEY)** — Score: `17%` | Issues: *Visual narrative pursues a goal alien to this poem's intention.*

---

## Suite 05 — BLOODLINES
> *"Now go, they tell me. To ask if I can inherit the earth — to ask if I can name my own stars. Even galaxies, if I may. The past, too, was waiting for me — coming of age in the shared rooms of humid basements as bedrooms; mattress pads where the wood beams of Southern pine could comfort my spine. It didn't. To dream was to prevail."*

### 🎯 Ground Truth Poem LEGOS Baseline
- **L**: Shared Humid Southern Basement Bedroom & Deep Galactic Starfield.
- **E**: The Young Lineage Heir / Galactic Dreamer.
- **G**: Inheriting the Earth & Naming Galaxies — Transcending the physical poverty and bone-aches of his origins.
- **O**: Humid Basement Walls & Rigid Pine Beams — Unyielding wood beams that offered no comfort to his growing spine.
- **S**: Realizing that dreaming was not an escape, but the foundational act of prevalence that unlocked cosmic sovereignty.
- **U**: Interstellar Sovereign Lineage — Claiming the power to name galaxies while honoring the unbreakable spine built in the basement.

### 🔍 Top Evaluated Candidates & Linter Verdicts
| Shot ID | Category | Total Score | L | E | G | O | S | U | Verdict |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| `764b035a` | BEATING_HEART_SKELETON | **38%** | DRIFT | PASS | MISMATCH | DRIFT | DRIFT | DRIFT | METAPHORICAL_DRIFT |
| `b8d2065c` | BEATING_HEART_SKELETON | **38%** | DRIFT | PASS | MISMATCH | DRIFT | DRIFT | DRIFT | METAPHORICAL_DRIFT |
| `34051c38` | SKELETAL_PROFILE | **33%** | DRIFT | PASS | MISMATCH | MISMATCH | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |
| `1cdf9a75` | EMBRACING_YOUTHS_BUTTERF | **32%** | MISMATCH | PASS | MISMATCH | DRIFT | MISMATCH | DRIFT | ANACHRONISTIC_OUTLIER |
| `5c7f1747` | EMBRACING_YOUTHS_BUTTERF | **32%** | MISMATCH | PASS | MISMATCH | DRIFT | MISMATCH | DRIFT | ANACHRONISTIC_OUTLIER |
| `0107df88` | EMBRACING_YOUTHS_BUTTERF | **32%** | MISMATCH | PASS | MISMATCH | DRIFT | MISMATCH | DRIFT | ANACHRONISTIC_OUTLIER |
| `516f88fd` | SKELETAL_PROFILE | **26%** | DRIFT | PASS | MISMATCH | MISMATCH | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |
| `80b32fdf` | SKELETAL_PROFILE | **26%** | DRIFT | PASS | MISMATCH | MISMATCH | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |

### ❌ Outliers Flagged for Pruning (Does NOT Belong in this Suite)

- 🔴 **`34051c38` (SKELETAL_PROFILE)** — Score: `33%` | Issues: *Visual narrative pursues a goal alien to this poem's intention.*
- 🔴 **`1cdf9a75` (EMBRACING_YOUTHS_BUTTERFLIES)** — Score: `32%` | Issues: *Location 'Ethereal Dark Void with Biolum...' does not match poem setting (basement, bedroom, southern pine).; Visual narrative pursues a goal alien to this poem's intention.*
- 🔴 **`5c7f1747` (EMBRACING_YOUTHS_BUTTERFLIES)** — Score: `32%` | Issues: *Location 'Ethereal Dark Void with Biolum...' does not match poem setting (basement, bedroom, southern pine).; Visual narrative pursues a goal alien to this poem's intention.*
- 🔴 **`0107df88` (EMBRACING_YOUTHS_BUTTERFLIES)** — Score: `32%` | Issues: *Location 'Ethereal Dark Void with Biolum...' does not match poem setting (basement, bedroom, southern pine).; Visual narrative pursues a goal alien to this poem's intention.*

---

## Suite 06 — RESURRECTING ATLANTIS
> *"Poets, who eased generations down yellow brick roads — and plucked our souls out of their secret places, to follow comets to the capital city of our collective consciousness. Resurrecting Atlantis. Here we are all one — the pact we've made here with nature, abandoned and hoped for the best, back on life."*

### 🎯 Ground Truth Poem LEGOS Baseline
- **L**: The Capital City of Collective Consciousness / Submerged Atlantis Resurrected.
- **E**: The Lineage of Poets & The United Human Collective.
- **G**: Resurrecting Atlantis — Following comet trails to reunite fragmented human souls back into harmony with the natural world.
- **O**: Generational Amnesia & Abandoned Ecological Pact — The historical severance from nature and lost collective memory.
- **S**: Poets pluck hidden souls from their secret shelters, guiding them along cosmic yellow brick roads into unified awareness.
- **U**: Universal Oneness — 'Here we are all one' — restoring the sacred pact with life across the resurrected collective matrix.

### 🔍 Top Evaluated Candidates & Linter Verdicts
| Shot ID | Category | Total Score | L | E | G | O | S | U | Verdict |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| `84c43938` | CRT_TV_PYRAMID_ATLANTIS | **46%** | PASS | PASS | MISMATCH | DRIFT | MISMATCH | MISMATCH | METAPHORICAL_DRIFT |
| `b38a6302` | CRT_TV_PYRAMID_ATLANTIS | **37%** | PASS | DRIFT | MISMATCH | DRIFT | MISMATCH | MISMATCH | METAPHORICAL_DRIFT |
| `464b4dcc` | CRT_TV_PYRAMID_ATLANTIS | **37%** | PASS | DRIFT | MISMATCH | DRIFT | MISMATCH | MISMATCH | METAPHORICAL_DRIFT |
| `d06fff56` | CRT_TV_PYRAMID_ATLANTIS | **37%** | PASS | DRIFT | MISMATCH | DRIFT | MISMATCH | MISMATCH | METAPHORICAL_DRIFT |
| `60ea25fc` | CRT_TV_PYRAMID_ATLANTIS | **37%** | PASS | DRIFT | MISMATCH | DRIFT | MISMATCH | MISMATCH | METAPHORICAL_DRIFT |
| `c2a64680` | CRT_TV_PYRAMID_ATLANTIS | **37%** | PASS | DRIFT | MISMATCH | DRIFT | MISMATCH | MISMATCH | METAPHORICAL_DRIFT |
| `35855d8a` | MIRRORED_ISLAND_METROPOL | **24%** | DRIFT | DRIFT | MISMATCH | DRIFT | MISMATCH | DRIFT | ANACHRONISTIC_OUTLIER |
| `10440c21` | MIRRORED_ISLAND_METROPOL | **24%** | DRIFT | DRIFT | MISMATCH | DRIFT | MISMATCH | DRIFT | ANACHRONISTIC_OUTLIER |

### ❌ Outliers Flagged for Pruning (Does NOT Belong in this Suite)

- 🔴 **`35855d8a` (MIRRORED_ISLAND_METROPOLIS)** — Score: `24%` | Issues: *Visual narrative pursues a goal alien to this poem's intention.*
- 🔴 **`10440c21` (MIRRORED_ISLAND_METROPOLIS)** — Score: `24%` | Issues: *Visual narrative pursues a goal alien to this poem's intention.*
- 🔴 **`92cc2431` (MIRRORED_ISLAND_METROPOLIS)** — Score: `24%` | Issues: *Visual narrative pursues a goal alien to this poem's intention.*
- 🔴 **`2b779f89` (ANCESTRAL_COMMUNION_ROSES)** — Score: `22%` | Issues: *Location 'Submerged Ethereal Sanctuary —...' does not match poem setting (capital city, atlantis, collective consciousness).*

---

## Suite 07 — DJ TURN ME UP
> *"DJ, turn me up, please. Eyes wide shut, chin nested at the arch of the weight of these spoken words. I have a love story to tell — of ghosts, whispering unfolded dilutions, birthed in purity, and dying in the vineyards of sun-soaked evergreen fields, unnourished."*

### 🎯 Ground Truth Poem LEGOS Baseline
- **L**: Subterranean Soundstage Booth & Unnourished Sun-Soaked Evergreen Vineyards.
- **E**: The Spoken Word Lyricist & The DJ.
- **G**: Amplifying the Unspoken Ghost Story — Channeling acoustic power to testify to pure love that withered unnourished.
- **O**: Suffocating Weight of Words & Ghostly Dilutions — The crushing heaviness of unexpressed grief dying in silent fields.
- **S**: Calling out 'DJ, turn me up, please' with eyes wide shut, nesting chin at the microphone arch to release the narrative.
- **U**: Acoustic Catharsis — Transforming silent ghostly sorrow into an amplified, undeniable sonic broadcast.

### 🔍 Top Evaluated Candidates & Linter Verdicts
| Shot ID | Category | Total Score | L | E | G | O | S | U | Verdict |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| `e9c18d8d` | BOY_AT_RAIN_WINDOW | **21%** | DRIFT | DRIFT | MISMATCH | MISMATCH | MISMATCH | DRIFT | ANACHRONISTIC_OUTLIER |
| `0183fedb` | BOY_AT_RAIN_WINDOW | **21%** | DRIFT | DRIFT | MISMATCH | MISMATCH | MISMATCH | DRIFT | ANACHRONISTIC_OUTLIER |
| `84c137db` | POET_DIM_BEDROOM | **8%** | MISMATCH | DRIFT | MISMATCH | MISMATCH | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |
| `8daa2ef0` | TRAIN_WINDOW_REFRACTION | **8%** | DRIFT | MISMATCH | MISMATCH | MISMATCH | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |
| `13fee118` | TRAIN_WINDOW_REFRACTION | **8%** | DRIFT | MISMATCH | MISMATCH | MISMATCH | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |
| `4d3fc262` | TRAIN_WINDOW_REFRACTION | **8%** | DRIFT | MISMATCH | MISMATCH | MISMATCH | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |
| `7b30f724` | TRAIN_WINDOW_REFRACTION | **8%** | DRIFT | MISMATCH | MISMATCH | MISMATCH | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |
| `afa81d04` | TRAIN_WINDOW_REFRACTION | **8%** | DRIFT | MISMATCH | MISMATCH | MISMATCH | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |

### ❌ Outliers Flagged for Pruning (Does NOT Belong in this Suite)

- 🔴 **`e9c18d8d` (BOY_AT_RAIN_WINDOW)** — Score: `21%` | Issues: *Visual narrative pursues a goal alien to this poem's intention.*
- 🔴 **`0183fedb` (BOY_AT_RAIN_WINDOW)** — Score: `21%` | Issues: *Visual narrative pursues a goal alien to this poem's intention.*
- 🔴 **`84c137db` (POET_DIM_BEDROOM)** — Score: `8%` | Issues: *Location 'Dim Teal Bedroom — Modern bedr...' does not match poem setting (dj booth, soundstage, vineyards).; Visual narrative pursues a goal alien to this poem's intention.*
- 🔴 **`8daa2ef0` (TRAIN_WINDOW_REFRACTION)** — Score: `8%` | Issues: *Entity 'The POET in Transit — Handsome...' does not align with poem characters.; Visual narrative pursues a goal alien to this poem's intention.*

---

## Suite 08 — NEWLY SINGLE
> *"Pulsing, and head throbbing from the music — and empty, on a crowded floor of sweated perfumes and temptations. The soul escapes my body, and leaves him on the dance floor — just flesh and bones. Rejection and heartache hit different, with no feelings afloat."*

### 🎯 Ground Truth Poem LEGOS Baseline
- **L**: Sweated, Crowded Nightclub Dance Floor Lit by Throbbing Bass.
- **E**: The Newly Single Man (Bifurcated into Dancing Flesh and Ascending Soul).
- **G**: Surviving Post-Breakup Heartache — Navigating sensual distractions while emotionally hollowed out.
- **O**: Throbbing Music, Temptation, & Acute Rejection — The suffocating crush of dancing bodies pressing against inner numbness.
- **S**: The soul detaches and floats upward out of the physical body, leaving an empty vessel of flesh and bones on the floor.
- **U**: Anesthetized Elevation — Overcoming heartbreak by floating above sensation, surviving with zero emotional drag.

### 🔍 Top Evaluated Candidates & Linter Verdicts
| Shot ID | Category | Total Score | L | E | G | O | S | U | Verdict |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| `8daa2ef0` | TRAIN_WINDOW_REFRACTION | **26%** | MISMATCH | DRIFT | DRIFT | DRIFT | DRIFT | DRIFT | ANACHRONISTIC_OUTLIER |
| `13fee118` | TRAIN_WINDOW_REFRACTION | **26%** | MISMATCH | DRIFT | DRIFT | DRIFT | DRIFT | DRIFT | ANACHRONISTIC_OUTLIER |
| `4d3fc262` | TRAIN_WINDOW_REFRACTION | **26%** | MISMATCH | DRIFT | DRIFT | DRIFT | DRIFT | DRIFT | ANACHRONISTIC_OUTLIER |
| `7b30f724` | TRAIN_WINDOW_REFRACTION | **26%** | MISMATCH | DRIFT | DRIFT | DRIFT | DRIFT | DRIFT | ANACHRONISTIC_OUTLIER |
| `afa81d04` | TRAIN_WINDOW_REFRACTION | **26%** | MISMATCH | DRIFT | DRIFT | DRIFT | DRIFT | DRIFT | ANACHRONISTIC_OUTLIER |
| `c52c52ca` | TRAIN_WINDOW_REFRACTION | **26%** | MISMATCH | DRIFT | DRIFT | DRIFT | DRIFT | DRIFT | ANACHRONISTIC_OUTLIER |
| `2474f1b5` | POET_DIM_BEDROOM | **8%** | DRIFT | MISMATCH | MISMATCH | MISMATCH | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |
| `7534249f` | POET_DIM_BEDROOM | **8%** | DRIFT | MISMATCH | MISMATCH | MISMATCH | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |

### ❌ Outliers Flagged for Pruning (Does NOT Belong in this Suite)

- 🔴 **`8daa2ef0` (TRAIN_WINDOW_REFRACTION)** — Score: `26%` | Issues: *Location 'Speeding Passenger Train Windo...' does not match poem setting (dance floor, crowded floor, speeding train).*
- 🔴 **`13fee118` (TRAIN_WINDOW_REFRACTION)** — Score: `26%` | Issues: *Location 'Speeding Passenger Train Windo...' does not match poem setting (dance floor, crowded floor, speeding train).*
- 🔴 **`4d3fc262` (TRAIN_WINDOW_REFRACTION)** — Score: `26%` | Issues: *Location 'Speeding Passenger Train Windo...' does not match poem setting (dance floor, crowded floor, speeding train).*
- 🔴 **`7b30f724` (TRAIN_WINDOW_REFRACTION)** — Score: `26%` | Issues: *Location 'Speeding Passenger Train Windo...' does not match poem setting (dance floor, crowded floor, speeding train).*

---

## Suite 09 — YET, HEARD
> *"Before I go, we look at the moon the way we used to see it. We talk for years, travel through time — we grow old together, I believe. Before I go, I call on my mother — in tears, speaking of an abyss she's never known. Before I go, I call on my father — his calming demeanor summoned from the yonders. We stroll, father and son, hearted and shaken. Someone borrowed, and someone blue — yet, broken. Yet, heard."*

### 🎯 Ground Truth Poem LEGOS Baseline
- **L**: Moonlit Harbor Horizon & Wave Shadows of the Inner Bay.
- **E**: The Departing Son Reconnecting with Mother & Father.
- **G**: Ancestral Reconciliation Before Departure — Summoning parental presence to explain his wounds and seek peace.
- **O**: The Unbridgeable Abyss — Wounds his mother has never known and tears falling in the dark harbor waves.
- **S**: Walking east toward the sunrise with his father, retracing generational footsteps while weeping in the harbor shadows.
- **U**: Heard Across the Void — Strolling together as father and son: broken, blue, yet profoundly and undeniably heard.

### 🔍 Top Evaluated Candidates & Linter Verdicts
| Shot ID | Category | Total Score | L | E | G | O | S | U | Verdict |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| `d5abc940` | ROOFTOP_STEAM_LEAP | **47%** | PASS | PASS | DRIFT | DRIFT | MISMATCH | DRIFT | METAPHORICAL_DRIFT |
| `db9c23a4` | POET_DIM_BEDROOM | **25%** | MISMATCH | PASS | MISMATCH | MISMATCH | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |
| `5b9ec655` | BEDROOM_FOG_GESTURE | **25%** | MISMATCH | PASS | MISMATCH | MISMATCH | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |
| `8aff03e4` | ROOFTOP_STEAM_ALLEY | **17%** | DRIFT | DRIFT | MISMATCH | MISMATCH | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |
| `d1dfc1d0` | ROOFTOP_STEAM_ALLEY | **17%** | DRIFT | DRIFT | MISMATCH | MISMATCH | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |
| `eb298ed7` | ROOFTOP_STEAM_ALLEY | **17%** | DRIFT | DRIFT | MISMATCH | MISMATCH | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |
| `af9410b7` | ROOFTOP_STEAM_ALLEY | **17%** | DRIFT | DRIFT | MISMATCH | MISMATCH | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |
| `cc6917c6` | ROOFTOP_STEAM_ALLEY | **17%** | DRIFT | DRIFT | MISMATCH | MISMATCH | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |

### ❌ Outliers Flagged for Pruning (Does NOT Belong in this Suite)

- 🔴 **`db9c23a4` (POET_DIM_BEDROOM)** — Score: `25%` | Issues: *Location 'Dim Teal Bedroom — Modern bedr...' does not match poem setting (moon, harbor, wave shadows).; Visual narrative pursues a goal alien to this poem's intention.*
- 🔴 **`5b9ec655` (BEDROOM_FOG_GESTURE)** — Score: `25%` | Issues: *Location 'Fog-Engulfed Bedroom with Writ...' does not match poem setting (moon, harbor, wave shadows).; Visual narrative pursues a goal alien to this poem's intention.*
- 🔴 **`8aff03e4` (ROOFTOP_STEAM_ALLEY)** — Score: `17%` | Issues: *Visual narrative pursues a goal alien to this poem's intention.*
- 🔴 **`d1dfc1d0` (ROOFTOP_STEAM_ALLEY)** — Score: `17%` | Issues: *Visual narrative pursues a goal alien to this poem's intention.*

---

## Suite 10 — MAGIC RIDE
> *"I wasn't looking for a ride, but here you are — blissful, and oddly sensitive. I rub my aggressions into your steel coverings, and hop on. Loneliness is having everything with no one to tell — being everywhere, with no one to love. I let the noise block the noise. The way I ride: eyes turn, heads twist — and prove the magic still exists. The moon settles, and I can see a morning ahead for me."*

### 🎯 Ground Truth Poem LEGOS Baseline
- **L**: Open Steel Motorcycle on Coastal Highway Transitioning into Dawn.
- **E**: The Solitary Rider on the Steel Machine.
- **G**: Proving Magic Still Exists — Drowning out isolation and aggressions through the roar of machine velocity.
- **O**: Profound Loneliness — Having everything with no one to tell, being everywhere with no one to love.
- **S**: Letting the mechanical noise block the psychic noise, leaning into the throttle until heads twist and the morning appears.
- **U**: Awakened Morning — Darkness and distant stars subside, revealing a crisp morning of authentic hope and living magic.

### 🔍 Top Evaluated Candidates & Linter Verdicts
| Shot ID | Category | Total Score | L | E | G | O | S | U | Verdict |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| `653ecfbe` | COASTAL_MAGIC_RIDE | **46%** | PASS | DRIFT | DRIFT | DRIFT | MISMATCH | DRIFT | METAPHORICAL_DRIFT |
| `fc64e987` | COASTAL_MAGIC_RIDE | **46%** | PASS | DRIFT | DRIFT | DRIFT | MISMATCH | DRIFT | METAPHORICAL_DRIFT |
| `474a21a0` | COASTAL_MAGIC_RIDE | **46%** | PASS | DRIFT | DRIFT | DRIFT | MISMATCH | DRIFT | METAPHORICAL_DRIFT |
| `eaea9d0a` | COASTAL_MAGIC_RIDE | **46%** | PASS | DRIFT | DRIFT | DRIFT | MISMATCH | DRIFT | METAPHORICAL_DRIFT |
| `e9c18d8d` | BOY_AT_RAIN_WINDOW | **8%** | DRIFT | MISMATCH | MISMATCH | MISMATCH | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |
| `0183fedb` | BOY_AT_RAIN_WINDOW | **8%** | DRIFT | MISMATCH | MISMATCH | MISMATCH | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |
| `48a7a55a` | SAFFRON_SANCTUARY_MONKS | **8%** | DRIFT | MISMATCH | MISMATCH | MISMATCH | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |
| `63d387a4` | POET_CATHEDRAL_CROWS | **8%** | MISMATCH | DRIFT | MISMATCH | MISMATCH | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |

### ❌ Outliers Flagged for Pruning (Does NOT Belong in this Suite)

- 🔴 **`e9c18d8d` (BOY_AT_RAIN_WINDOW)** — Score: `8%` | Issues: *Entity 'The Boy in Red — Young Black b...' does not align with poem characters.; Visual narrative pursues a goal alien to this poem's intention.*
- 🔴 **`0183fedb` (BOY_AT_RAIN_WINDOW)** — Score: `8%` | Issues: *Entity 'The Boy in Red — Young Black b...' does not align with poem characters.; Visual narrative pursues a goal alien to this poem's intention.*
- 🔴 **`48a7a55a` (SAFFRON_SANCTUARY_MONKS)** — Score: `8%` | Issues: *Entity 'The Saffron Monks — Buddhist a...' does not align with poem characters.; Visual narrative pursues a goal alien to this poem's intention.*
- 🔴 **`63d387a4` (POET_CATHEDRAL_CROWS)** — Score: `8%` | Issues: *Location 'Gothic Cathedral Grounds — Par...' does not match poem setting (steel coverings, ride, highway).; Visual narrative pursues a goal alien to this poem's intention.*

---

## Suite 11 — NEW DAY
> *"Fog covers the seas and hugs the tree-covered hills, floating through the morning as it exhales its introduction. This world is at peace. In the awakening of dawn, in fresh muted colors: we can rebuild this temple. It's a new day — a catharsis for me to say, with newfound energies and recycled airs. Edgeless dreams that reflect the skies... that we too can walk on water."*

### 🎯 Ground Truth Poem LEGOS Baseline
- **L**: Morning Hillside Forest Overlooking Coastal Seas & Infinite Edgeless Reflection Pools.
- **E**: The Awakened Temple Rebuilder.
- **G**: Rebuilding the Temple & Claiming Catharsis — Welcoming a peaceful new day with fresh creative energies.
- **O**: Past Destructions & Lingering Sea Fog — The historical ruins of previous temples and residual exhaustion.
- **S**: Dawn breaks in muted pastels as morning dews and vibrant sun rays illuminate the edgeless waters.
- **U**: Miraculous Renewal — Taking deep appreciative breaths of present life: 'We can rebuild this temple... we too can walk on water.'

### 🔍 Top Evaluated Candidates & Linter Verdicts
| Shot ID | Category | Total Score | L | E | G | O | S | U | Verdict |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| `badaf97b` | APOTHECARY_YELLOW_FLOWER | **29%** | PASS | MISMATCH | DRIFT | DRIFT | MISMATCH | DRIFT | ANACHRONISTIC_OUTLIER |
| `8a9e7a1e` | RUINED_COLONNADE_PILGRIM | **24%** | DRIFT | DRIFT | MISMATCH | PASS | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |
| `48a7a55a` | SAFFRON_SANCTUARY_MONKS | **17%** | DRIFT | DRIFT | MISMATCH | MISMATCH | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |
| `db9c23a4` | POET_DIM_BEDROOM | **8%** | DRIFT | MISMATCH | MISMATCH | MISMATCH | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |
| `5b9ec655` | BEDROOM_FOG_GESTURE | **8%** | DRIFT | MISMATCH | MISMATCH | MISMATCH | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |
| `0b025dc2` | RED_FLUID_SUBMERSION | **8%** | DRIFT | MISMATCH | MISMATCH | MISMATCH | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |
| `1cdf9a75` | EMBRACING_YOUTHS_BUTTERF | **8%** | DRIFT | MISMATCH | MISMATCH | MISMATCH | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |
| `5c7f1747` | EMBRACING_YOUTHS_BUTTERF | **8%** | DRIFT | MISMATCH | MISMATCH | MISMATCH | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |

### ❌ Outliers Flagged for Pruning (Does NOT Belong in this Suite)

- 🔴 **`badaf97b` (APOTHECARY_YELLOW_FLOWERS)** — Score: `29%` | Issues: *Entity 'The POET in the Flower Field —...' does not align with poem characters.*
- 🔴 **`8a9e7a1e` (RUINED_COLONNADE_PILGRIM)** — Score: `24%` | Issues: *Visual narrative pursues a goal alien to this poem's intention.*
- 🔴 **`48a7a55a` (SAFFRON_SANCTUARY_MONKS)** — Score: `17%` | Issues: *Visual narrative pursues a goal alien to this poem's intention.*
- 🔴 **`db9c23a4` (POET_DIM_BEDROOM)** — Score: `8%` | Issues: *Entity 'The POET — Athletic Black man ...' does not align with poem characters.; Visual narrative pursues a goal alien to this poem's intention.*

---

## Suite 12 — REUNION
> *"Decades later, there is less time for words, and more space for laughter — hugs with no reason, and loud voices, so our hearts can be overheard. Reflecting on legacies, and creeds once told — of elders, now past. Or will we make time, in the sands of burning hourglasses? Before our winds part ways — to a next lifetime. This is brotherhood."*

### 🎯 Ground Truth Poem LEGOS Baseline
- **L**: Sanctuary of Burning Hourglasses & Winds of Legacy.
- **E**: Reunited Brothers / Kinship Descendants of Departed Elders.
- **G**: Making Time for Brotherhood — Overcoming decades of separation to celebrate shared survival.
- **O**: The Burning Hourglass & Inevitable Mortality — The rapid passage of time threatening to scatter their winds.
- **S**: Abandoning formal words in favor of loud voices, unreasoned hugs, and full-bodied laughter so hearts are overheard.
- **U**: Sacred Brotherhood — Forging a triumphant bond that defies time and echoes into the next lifetime.

### 🔍 Top Evaluated Candidates & Linter Verdicts
| Shot ID | Category | Total Score | L | E | G | O | S | U | Verdict |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| `48a7a55a` | SAFFRON_SANCTUARY_MONKS | **22%** | MISMATCH | PASS | DRIFT | MISMATCH | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |
| `37235c7f` | TWO_KIN_WOMEN | **21%** | DRIFT | DRIFT | MISMATCH | MISMATCH | MISMATCH | DRIFT | ANACHRONISTIC_OUTLIER |
| `02185971` | TWO_KIN_WOMEN | **21%** | DRIFT | DRIFT | MISMATCH | MISMATCH | MISMATCH | DRIFT | ANACHRONISTIC_OUTLIER |
| `6ac81cae` | TWO_KIN_WOMEN | **21%** | DRIFT | DRIFT | MISMATCH | MISMATCH | MISMATCH | DRIFT | ANACHRONISTIC_OUTLIER |
| `1cdf9a75` | EMBRACING_YOUTHS_BUTTERF | **14%** | MISMATCH | DRIFT | DRIFT | MISMATCH | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |
| `5c7f1747` | EMBRACING_YOUTHS_BUTTERF | **14%** | MISMATCH | DRIFT | DRIFT | MISMATCH | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |
| `0107df88` | EMBRACING_YOUTHS_BUTTERF | **14%** | MISMATCH | DRIFT | DRIFT | MISMATCH | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |
| `2b779f89` | ANCESTRAL_COMMUNION_ROSE | **8%** | MISMATCH | DRIFT | MISMATCH | MISMATCH | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |

### ❌ Outliers Flagged for Pruning (Does NOT Belong in this Suite)

- 🔴 **`48a7a55a` (SAFFRON_SANCTUARY_MONKS)** — Score: `22%` | Issues: *Location 'Stone Pillar Sanctuary Courtya...' does not match poem setting (gathering hall, hourglasses, celebration hall).*
- 🔴 **`37235c7f` (TWO_KIN_WOMEN)** — Score: `21%` | Issues: *Visual narrative pursues a goal alien to this poem's intention.*
- 🔴 **`02185971` (TWO_KIN_WOMEN)** — Score: `21%` | Issues: *Visual narrative pursues a goal alien to this poem's intention.*
- 🔴 **`6ac81cae` (TWO_KIN_WOMEN)** — Score: `21%` | Issues: *Visual narrative pursues a goal alien to this poem's intention.*

---

## Suite 13 — HOW TO WIN MY HEART
> *"Find me at the harbor, at the small tables, watching. The couples orbit each other the way Jupiter keeps its moons — close, and counted. Life has burned all my love stories — victory-less seasons. So I harvest the flowers instead — scarlet poppies, purple blossoms — and they become my power. Then, a distant window. She says: you'll see me. Capture the eyes. Refocus. Step back. Say hello. Don't make me leave. I escaped here for a reason."*

### 🎯 Ground Truth Poem LEGOS Baseline
- **L**: Seaside Harbor Small Tables & Distant Window Looking Over the Bay.
- **E**: The Guarded Harbor Watcher & The Distant Muse.
- **G**: Protecting Inner Power While Opening to Love — Navigating romantic curiosity after repeated past heartbreak.
- **O**: Victory-Less Seasons & Past Ashes — All prior love stories burned, creating fear of leaving his harbor refuge.
- **S**: Harvesting scarlet poppies and purple blossoms into personal power, then catching her gaze in a distant window.
- **U**: Refocused Vulnerability — Stepping back, capturing the eyes, and choosing to say hello without abandoning his sanctuary.

### 🔍 Top Evaluated Candidates & Linter Verdicts
| Shot ID | Category | Total Score | L | E | G | O | S | U | Verdict |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| `222c8cca` | TEMPORAL_ECHO_TRAIL | **33%** | DRIFT | PASS | MISMATCH | DRIFT | MISMATCH | DRIFT | ANACHRONISTIC_OUTLIER |
| `53666716` | TEMPORAL_ECHO_TRAIL | **33%** | DRIFT | PASS | MISMATCH | DRIFT | MISMATCH | DRIFT | ANACHRONISTIC_OUTLIER |
| `2255ec6b` | TEMPORAL_ECHO_TRAIL | **33%** | DRIFT | PASS | MISMATCH | DRIFT | MISMATCH | DRIFT | ANACHRONISTIC_OUTLIER |
| `ce4762b5` | ROOFTOP_CRIMSON_FLARES | **8%** | MISMATCH | DRIFT | MISMATCH | MISMATCH | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |
| `2474f1b5` | POET_DIM_BEDROOM | **0%** | MISMATCH | MISMATCH | MISMATCH | MISMATCH | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |
| `7534249f` | POET_DIM_BEDROOM | **0%** | MISMATCH | MISMATCH | MISMATCH | MISMATCH | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |
| `0a69c776` | POET_DIM_BEDROOM | **0%** | MISMATCH | MISMATCH | MISMATCH | MISMATCH | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |
| `1ea914c8` | POET_DIM_BEDROOM | **0%** | MISMATCH | MISMATCH | MISMATCH | MISMATCH | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |

### ❌ Outliers Flagged for Pruning (Does NOT Belong in this Suite)

- 🔴 **`222c8cca` (TEMPORAL_ECHO_TRAIL)** — Score: `33%` | Issues: *Visual narrative pursues a goal alien to this poem's intention.*
- 🔴 **`53666716` (TEMPORAL_ECHO_TRAIL)** — Score: `33%` | Issues: *Visual narrative pursues a goal alien to this poem's intention.*
- 🔴 **`2255ec6b` (TEMPORAL_ECHO_TRAIL)** — Score: `33%` | Issues: *Visual narrative pursues a goal alien to this poem's intention.*
- 🔴 **`ce4762b5` (ROOFTOP_CRIMSON_FLARES)** — Score: `8%` | Issues: *Location 'High-Rise Rooftop Balcony — El...' does not match poem setting (harbor, small tables, distant window).; Visual narrative pursues a goal alien to this poem's intention.*

---

## Suite 14 — HOT MINUTE
> *"A hot minute. The haze gathers on the water — and everything I built here learns to be weather: the city, the temple, the harbor. It takes me last, and from the ground up. I am reluctant — but I have been weather before. All black again. But no walls this time. A life flashes the way a reel does: the window, the tambourine, the field, the stars, the candle, the daisy, the ride, the temple, the hourglass. Our dance together is a victory. An old door, from a vintage somewhere. It opens on a slow party — the kind I once fell out of a window to escape. This time, I choose the door."*

### 🎯 Ground Truth Poem LEGOS Baseline
- **L**: Atmospheric Dissolution Shoreline (City, Temple, Harbor Becoming Weather) & Vintage Doorway.
- **E**: The Transmuted Poet / Sovereign Muse.
- **G**: Conscious Narrative Transcendence — Allowing the built world to dissolve into weather and choosing his exit with dignity.
- **O**: Reluctance to Dissolve & Darkness — The terrifying collapse of all physical structures into black void.
- **S**: Life flashes like a film reel (window, tambourine, ride, temple, hourglass); what was once a traumatic escape becomes a dance of victory.
- **U**: Choosing the Door — Rather than falling out of a window to escape, consciously and calmly walking through the door into the gathering.

### 🔍 Top Evaluated Candidates & Linter Verdicts
| Shot ID | Category | Total Score | L | E | G | O | S | U | Verdict |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| `ce4762b5` | ROOFTOP_CRIMSON_FLARES | **29%** | PASS | DRIFT | MISMATCH | MISMATCH | MISMATCH | DRIFT | ANACHRONISTIC_OUTLIER |
| `63fd3f15` | SHADOWED_STYLIST_PLASMA | **17%** | DRIFT | DRIFT | MISMATCH | MISMATCH | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |
| `60c4c35f` | SHADOWED_STYLIST_PLASMA | **17%** | DRIFT | DRIFT | MISMATCH | MISMATCH | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |
| `4ed309f2` | SHADOWED_STYLIST_PLASMA | **17%** | DRIFT | DRIFT | MISMATCH | MISMATCH | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |
| `0b025dc2` | RED_FLUID_SUBMERSION | **17%** | PASS | MISMATCH | MISMATCH | MISMATCH | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |
| `db9c23a4` | POET_DIM_BEDROOM | **8%** | DRIFT | MISMATCH | MISMATCH | MISMATCH | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |
| `5b9ec655` | BEDROOM_FOG_GESTURE | **8%** | DRIFT | MISMATCH | MISMATCH | MISMATCH | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |
| `34051c38` | SKELETAL_PROFILE | **8%** | DRIFT | MISMATCH | MISMATCH | MISMATCH | MISMATCH | MISMATCH | ANACHRONISTIC_OUTLIER |

### ❌ Outliers Flagged for Pruning (Does NOT Belong in this Suite)

- 🔴 **`ce4762b5` (ROOFTOP_CRIMSON_FLARES)** — Score: `29%` | Issues: *Visual narrative pursues a goal alien to this poem's intention.*
- 🔴 **`63fd3f15` (SHADOWED_STYLIST_PLASMA)** — Score: `17%` | Issues: *Visual narrative pursues a goal alien to this poem's intention.*
- 🔴 **`60c4c35f` (SHADOWED_STYLIST_PLASMA)** — Score: `17%` | Issues: *Visual narrative pursues a goal alien to this poem's intention.*
- 🔴 **`4ed309f2` (SHADOWED_STYLIST_PLASMA)** — Score: `17%` | Issues: *Visual narrative pursues a goal alien to this poem's intention.*

---
