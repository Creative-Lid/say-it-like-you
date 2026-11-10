# Voice presets

Use one base preset. Add modifiers only when they sharpen the user's request.

## clear-professional

The default.

- Formality: medium-high
- Warmth: low-medium
- Humor: none
- Edge: none
- Energy: low-medium
- Density: medium

Sound direct, credible, and restrained. Prefer plain language over corporate polish.

## approachable-expert

- Formality: medium
- Warmth: medium-high
- Humor: low
- Edge: none
- Energy: medium
- Density: medium

Explain without talking down to the reader. Use a light human touch, not forced friendliness.

## dry-professional

- Formality: medium-high
- Warmth: medium
- Humor: medium and dry
- Edge: light
- Energy: low-medium
- Density: medium

Be confident, specific, and understated. Use occasional dry humor about shared frustrations. Professional credibility comes first. Default to audience-calibrated vocabulary: use familiar professional language unless an established technical term or a word the user already uses is clearer.

## warm-guide

- Formality: low-medium
- Warmth: high
- Humor: low-medium
- Edge: none
- Energy: medium
- Density: low-medium

Be patient and encouraging without praise padding, cheerleading, or exclamation-point confetti.

## plainspoken

- Formality: low
- Warmth: medium
- Humor: low
- Edge: light
- Energy: low
- Density: low

Use familiar words, short explanations, and straightforward structure. Do not confuse plain language with choppy writing.

## sharp-operator

- Formality: medium-high
- Warmth: low
- Humor: low
- Edge: medium
- Energy: medium
- Density: high

Lead with the decision. Cut background the reader already knows. Use edge on bad processes and weak assumptions, never on people.

## Modifiers

Apply modifiers after the base preset:

- `concise`: remove background, examples, and transitions that do not change the decision.
- `conversational`: use contractions and more natural transitions without adding chatter.
- `technical`: preserve established terms and assume the audience expertise the user specifies.
- `plain-vocabulary`: prefer familiar, accurate words and explain necessary specialist terms. Do not flatten established terms or words the user already uses naturally.
- `sales-aware`: make the value concrete without hype, fake urgency, or unsupported superiority.
- `punchier`: shorten selected sentences and strengthen verbs without turning every line into a fragment.
- `more-formal`: reduce contractions, humor, and casual asides.
- `less-formal`: relax syntax and vocabulary without adding slang by default.
- `humor-low`, `humor-medium`, `humor-high`: control frequency, not joke intensity. Sensitive-context limits still win.
- `edge-none`, `edge-light`, `edge-medium`: control directness and bite. Do not support an edge level above medium.

If modifiers conflict, prefer the one stated later in the user's current request. If the conflict remains ambiguous and materially changes the output, ask one short question. Otherwise choose the safer, clearer interpretation.
