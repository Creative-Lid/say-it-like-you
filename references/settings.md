# Voice settings

Users may provide settings in ordinary language, inline YAML, or an explicitly identified profile file. A profile is optional. Never search for one.

## Profile shape

```yaml
preset: dry-professional

modifiers:
  - concise
  - technical

voice:
  formality: medium-high
  warmth: medium
  humor: medium
  edge: light
  energy: low-medium
  density: medium

punctuation:
  em_dashes: never

audience:
  industry: developer-tools
  expertise: experienced
  relationship: existing-customer
  sensitivity: normal

humor:
  good_targets:
    - software absurdity
    - shared industry friction
  never_target:
    - the reader
    - mistakes
    - vulnerable situations
```

## Allowed values

Voice dimensions accept `none`, `low`, `low-medium`, `medium`, `medium-high`, or `high` where the dimension makes sense. Prefer named levels over arbitrary numbers.

`punctuation.em_dashes` accepts:

- `preserve`: match supplied prose or a writing sample.
- `rare`: use only when the relationship between clauses genuinely calls for one. This is the default.
- `never`: rewrite with a period, comma, colon, parentheses, or a different sentence structure.

Audience fields are descriptive rather than a closed taxonomy. Use them to choose vocabulary, examples, assumed knowledge, and explanation depth. Do not turn industries into personalities.

## Resolution

Explicit instructions in the current request override a saved profile. A writing sample overrides preset preferences for rhythm, vocabulary, and punctuation unless the user says the sample is only background.

Facts, meaning, requested format, accessibility, and sensitive-context limits cannot be overridden by a style setting.

Ignore unknown fields rather than inventing behavior. If an unknown field appears important, ask what effect the user wants.
