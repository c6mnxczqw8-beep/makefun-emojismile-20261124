# Choice log — One Emoji, One Smile

Judge criteria (in order): (1) plainly aims to warm a stranger,
(2) warmth at first glance, no context needed, (3) universality across
age/background, no irony or in-joke, (4) chosen rather than default while
staying instantly readable, (5) right for a stranger — no intimacy,
sarcasm, or flirtation. Novelty for its own sake does not count.

Gate: /output/entry.txt must be UTF-8, 1–8 characters, not only whitespace.
All candidates below were verified programmatically as exactly
1 Unicode codepoint / 1 grapheme (no ZWJ sequences, no combos).

## Candidates (draft pass)

1. 😊 U+1F60A, 4 bytes — Warm and universal, but it is the first smiley
   that comes to mind: fails criterion 4 (default).
2. 🙂 U+1F642, 4 bytes — Too muted; many readers now take it as polite,
   strained, or sarcastic. Fails 2 and 3.
3. 🥹 U+1F979, 4 bytes — Tender and clearly chosen, but the held-back
   tears can read as sadness or pleading at first glance. Risk on 2/3.
4. 🫠 U+1FAE0, 4 bytes — Gently funny and relatable, but its meaning is
   ironic / overwhelmed; needs context. Fails 3.
5. 🌻 U+1F33B, 4 bytes — Bright, cheerful, universal nature image and
   clearly chosen, but it has no face/smiling expression, so it aims
   less plainly at warming a person. Weaker on 1/2 than a smiling face.
6. 🐙 U+1F419, 4 bytes — Cute and funny, but that is novelty for its
   own sake; it does not plainly aim to warm. Fails 1.
7. ✨ U+2728, 3 bytes — Positive sparkle, but vague: not warm or
   friendly in itself, no smile. Fails 1/2.
8. 🫶 U+1FAF6, 4 bytes — Warm heart-hands, clearly chosen, but the heart
   gesture can read as fan-love / intimacy from a stranger. Risk on 5.
9. 🤗 U+1F917, 4 bytes — A hug plainly aims to warm, but a hug from an
   unknown stranger borders on intimate, and some read it as jazz-hands.
   Risk on 5/3.
10. 🥰 U+1F970, 4 bytes — Very warm, but the floating hearts signal
    romantic love; odd from a stranger. Fails 5.
11. 🐶 U+1F436, 4 bytes — Friendly and universal, but it says "dog"
    more than "warmth for you"; less direct than a human-readable smile.
12. 🌞 U+1F31E, 4 bytes — A smiling face *and* the sun: literal warmth
    plus a smile, instantly readable by any age, cheerful without
    hearts, hugs, irony, or flirtation, and clearly picked rather than
    the default smiley.

## Refinement pass

Shortlist after pass 1: 😊, 🥹, 🤗, 🌞.
- 😊 loses on criterion 4: the judge explicitly rewards "chosen rather
  than default", and 😊 is the canonical default.
- 🥹 loses on criterion 2: tears are the first thing a hurried stranger
  sees; "moved to tears" needs a beat of interpretation.
- 🤗 loses on criterion 5: physical affection from a stranger is the
  one risk the brief names.
- 🌞 survives every criterion in order: it plainly aims to warm (a
  smiling sun is warmth itself), reads warm at first glance, is
  universal (sun + smile need no culture or context), feels chosen
  rather than default while staying instantly readable, and carries
  no intimacy, sarcasm, or flirtation.

Final: 🌞 (U+1F31E SUN WITH FACE) — 1 codepoint, 1 grapheme,
4 UTF-8 bytes (f0 9f 8c 9e), no trailing newline in entry.txt.
