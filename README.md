# The Golden Octave — A Hearable Dial (v1.0)

Companion tool for the paper **"The Golden Octave: Why the Fibonacci Ring's Dial Sings Only Whole Tones, and Falls Silent Only at φ"** (Strassner, 2026).

**▶ Run it live:** https://nealstrassner.github.io/golden-octave-calculator/

**📄 The Cosine Ruler & Selection Law (OSF):** https://osf.io/n5pwt/files/y6w7e

---

## What it does

An interactive, *hearable* version of the paper's instrument: two equal circles crossing on the Fibonacci 60-ring. Turn the dial **k = 1 … 14** and the two crossing points are read as musical pitches. You **see** the geometry and **hear** what it plays — only whole-tone intervals, and a fused octave at exactly two settings, both of which are the golden ratio.

It runs entirely offline in any browser — no installation, no internet, no data leaves your computer. Sound plays through your speakers when you press **Start Tone**.

## How to use the dial

- **Slider / ◀ ▶ / arrow keys** — set k (1 to 14)
- **Start Tone** (or spacebar) — play the two crossing notes
- **Move k while it plays** — the two voices change live
- **Key of …** — transpose the whole ring to any root (default C); a new note sits on top and the tones shift with it
- **k = 6 and k = 12** — the two voices fuse into one note (the octave) and a large **φ** appears: the distance is exactly **R·φ** and **R/φ** — the golden octave

## What to listen for

The dial sounds only even (whole-tone) intervals and never an odd one — it cannot play a perfect fifth or a perfect fourth. Step through all fourteen settings and the interval cycles every six steps. At the two golden settings the two pitches become the same note an octave apart: the one moment the geometry equals φ.

## The cosine ruler

The bright-yellow line that grows and shrinks between the two circle centres is the **cosine ruler** — the measuring instrument from the companion paper *The Cosine Ruler and the Selection Law* (Strassner, 2026). Its length is the distance **d = 2R·cos(6k°)** that the dial sets. See that paper on OSF (linked above) to learn what the mechanism is and does.

## Credits

The Golden Octave — the whole-tone law and the octave-at-φ coincidence on the Fibonacci 60-ring — is the work of **Neal Strassner** (2026). The code was written by Claude (Anthropic) working under the author's direction; all mathematics is as stated in the paper, and every note, distance, and interval is recomputed from scratch in the page each time it loads.

The program is one readable file — open `golden-octave-calculator-v1.0.html` and "View Source" to read every line.

## License

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) — share and adapt freely, with credit to Neal Strassner.

— Neal Strassner, 2026 · https://github.com/NealStrassner
