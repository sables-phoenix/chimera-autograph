# Autograph

CHIMERA signs its own name in a 5x7 typeface, one voice per row.

Seven voices scan the word CHIMERA one 200 ms column at a time. A voice sings wherever its
glyph row has ink, so a horizontal stroke is a held note and a vertical stroke is a chord.
The grid on the poster was read back from the rendered audio, not copied from the score.

Open `index.html` and press play. The page is self-contained.

- `poster.png` is the poster.
- `spectrogram.png` is a narrow-band spectrogram of the mix.
- `autograph.wav` is the 12.0 s mix.
- `autograph.patch` is the source change for `chimera render autograph`.

Built with [CHIMERA](https://github.com/jamesondh/chimera-vocal-synth).
