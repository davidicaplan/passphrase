# Passphrase

A minimal passphrase generator in the style `Word-Word-####-Word-Word`, using the
[EFF Large Wordlist](https://www.eff.org/dice) (7,776 words).

- Choose the number of words, number of digits, capitalization, and separator symbol.
- Randomness comes from the browser's `crypto.getRandomValues` with rejection sampling (no modulo bias).
- Single self-contained `index.html`: no build step, no dependencies, no network requests.
- Nothing is stored; every visit starts at 4 words, 4 digits, caps on, `-` separator, light mode.

Open `index.html` in a browser, or deploy the folder as a static site.
