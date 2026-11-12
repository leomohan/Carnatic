# Carnatic

**Raga Geometry**: an interactive picture of Carnatic raga and tala, drawn to scale.

Open `index.html` in a browser, or view it on GitHub Pages once Pages is enabled for this repo.

## What it shows

- **Raga pitch wheel.** All 12 swarasthanas sit around a circle with Sa at the top, each at its true pitch position (30° per semitone). The arohana is drawn as a gold shape on the outer ring and the avarohana as a pink shape on the inner ring, so ragas that ascend and descend differently look different.
- **Raga picker** (top right) with ten widely performed ragas: Shankarabharanam, Kalyani, Todi, Kharaharapriya, Bhairavi, Kambhoji, Mayamalavagowla, Mohanam, Hamsadhwani and Madhyamavati.
- **Raga facts:** arohana and avarohana, parent melakarta, scale type (audava, shadava, sampoorna), a traditionally associated mood, and one fact particular to the raga.
- **Adi Talam wheel:** 8 aksharas in the 4 + 2 + 2 structure (laghu, drutam, drutam), with kriya (Clap, Pinky, Ring, Middle, Clap, Wave, Clap, Wave), solkattu (Ta ka di mi Ta ka Jha nu) and sam marked.
- **Playback:** plays the arohana and avarohana over a Sa–Pa drone while the notes light up on the wheel and the tala ticks through each beat. Tempo is adjustable, and any note on the wheel can be tapped to hear it.

## Notes on accuracy

- Pitches use just-intonation ratios with Sa set to C (261.6 Hz).
- Real performance adds gamakas (oscillations and slides) that a scale drawing and plain tones cannot show, so each wheel is the raga's skeleton, not the raga itself.
- Kambhoji's occasional anya swara, kakali nishadam (N3), is mentioned in its notes but not drawn.
- Mood associations are traditional and vary between schools.

## Tech

A single self-contained HTML file: inline SVG, vanilla JavaScript and the Web Audio API. It needs no build step or dependencies; Google Fonts load if they're available.

© Mohan Krishnamurthy
