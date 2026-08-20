# 🎵 VOLHOLLA / MOTO Music-to-Film Scoring & Edit Matches

We analyzed all 34 curated tracks from **[VOLHOLLA / moto](https://hartswf0.github.io/moto/)** against the 14 WYGWYL poem halfworlds, mapping each song's tempo, atmosphere, and duration to the optimal film cut:

---

## 🎧 Top Curated Soundtrack Pairings for WYGWYL

```
========================================================================================================================
VOLHOLLA TRACK SLUG       TRACK TITLE & ALBUM                   MATCHED WYGWYL SUITE / CUT     EDITORIAL / MOOD ALIGNMENT
========================================================================================================================
song-aeolian-02           Flashing Lights (Roadside Omen)       02 FLASHING LIGHTS             Surreal, dark urgent momentum.
song-aeolian-03           How to Break Off an Engagement        03 BREAK OFF AN ENGAGEMENT     Triumphant, solemn, heartbreak release.
song-aeolian-09           Dial Tone Echoes                      08 NEWLY SINGLE                Nocturnal transit beat, drops at 120s.
song-aeolian-13           How to Win My Heart (Dial-Tone)       13 HOW TO WIN MY HEART         Deep soul, distant romantic yearning.
song-midnightsteppe-17    When the Soul Becomes People          05 BLOODLINES (SKELETON)       Spanish radio energy, ancestral vigor.
song-inthemiddle-10       Dust and Dawn                         01 OUT OF LIFE                 Low-key domestic morning haze stasis.
song-inthemiddle-38       Vinyl Incense Ritual                  01 OUT OF LIFE / 04 NEVERMORE  Soulful vinyl crackle & ritual smoke.
song-mareamemory-30       Submerged Afrofuturist Ignition       06 RESURRECTING ATLANTIS       Submerged oceanic synth pulse & TV pyramids.
song-mareamemory-25       Shaolin Sunrise Pulse                 11 NEW DAY (CHRYSANTHEMUMS)    Upbeat soulful dawn awakening & temple rebuild.
song-mareamemory-20       Radiant Lockdown Ritual               12 REUNION (SISTERHOOD)        Radiant familial joy & communal laughter.
song-mareamemory-14       Lost in the Sun                       10 MAGIC RIDE                  Hopeful seaside twilight acceleration.
song-mareamemory-06       Ecstatic Dawn                         09 YET, HEARD (ROOF LEAP)      Chilling vocal presence & celestial flight.
song-dustrest-10          Non-Abiding Flow                      04 NEVERMORE                   Deep solemnness, parched cathedral crows.
song-dustrest-20          Polishing the Data Mirror             07 DJ TURN ME UP               Rain noise, reflective acoustic diner tone.
song-cathedral-04         Data Purge                            14 HOT MINUTE                  Heavy beat, urban swag & flare smoke.
song-cathedral-11         Stained Glass Rims                    04 NEVERMORE                   Gothic stone atmosphere & choir resonance.
song-mallground-19        INDEXED EVIDENCE 120                  14-SHOT COMPLETE DEDUP CUT     Fast-moving kinetic rhythm (Winner cut).
song-nightbus-08          Saltwater Static (The Last Shanty)    14 HOT MINUTE (FINALE)         Haunting seaside closure & door choosing.
========================================================================================================================
```

---

## 🎬 Master Music-Synced Video Renders (FFmpeg Conforms)

Using FFmpeg, any VOLHOLLA soundtrack can be multiplexed directly with the video cuts:

```bash
# Example: Mux 'Shaolin Sunrise Pulse' onto the 14-Shot Deduplicated Cut
ffmpeg -y -i downloads/MARKOV_POET_ARCHIVE/rendered_cuts/WYGWYL_14SHOT_NARRATIVE_CUT.mp4 \
  -i "https://hartswf0.github.io/moto/MEDIA_DERIVATIVES/audio/MAREA%20MEMORY/Marea%20Memory%20-%20Shaolin%20Sunrise%20Pulse%20-%20Treblo--stream.mp3" \
  -c:v copy -c:a aac -b:a 192k -shortest \
  downloads/MARKOV_POET_ARCHIVE/rendered_cuts/WYGWYL_14SHOT_SCORED_SHAOLIN.mp4
```
