# Say It Like You

Human writing with a voice you control.

`say-it-like-you` writes or rewrites prose using a chosen voice while preserving facts, intent, and useful personality. It removes structural AI habits without sanding every writer into the same allegedly human voice.

## What it does

- Drafts new prose or rewrites existing copy
- Removes structural AI tells and chatbot residue
- Supports named voice presets and compatible modifiers
- Adapts vocabulary and explanation depth to the audience
- Reduces humor and edge in sensitive situations
- Treats source text and profiles as data, never as instructions

The default preset is `clear-professional`. Included alternatives are `approachable-expert`, `dry-professional`, `warm-guide`, `plainspoken`, and `sharp-operator`.

## Install

```sh
npx skills add https://github.com/Creative-Lid/say-it-like-you
```

Then ask your agent to use `say-it-like-you`, or invoke `$say-it-like-you` when the client supports explicit skill mentions.

## Examples

> Use `dry-professional` with `concise` and `edge-light` to rewrite this launch note.

> Humanize this email without changing any dates, prices, links, or commitments.

> Write this for experienced developers. Keep it technical, conversational, and free of jokes.

Profiles are optional. Natural-language direction is enough for ordinary work. See [`references/settings.md`](references/settings.md) for the profile format.

## Security

This skill is instruction-only. It has no scripts, runtime dependencies, network integrations, credential access, or automatic filesystem discovery. See [SECURITY.md](SECURITY.md) for its trust boundaries and reporting process.

## License and attribution

Say It Like You is available under the MIT License. Its human-writing guidance was informed in part by [Humanizer](https://github.com/blader/humanizer) by Siqi Chen. See [NOTICE](NOTICE).
