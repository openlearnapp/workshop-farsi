# Workshop: Farsi (Persian)

## Purpose

Language workshop for learning Farsi (Persian) — the most important words and phrases for daily interaction.

## Target Audience

- **Level**: Absolute beginner
- **Native languages**: German, English, or Farsi (for heritage speakers)
- **Goal**: Basic Farsi vocabulary and phrases, reading Persian script

## Structure

- **10 lessons** covering core vocabulary
- **Interface languages**: Deutsch, English, Farsi
- **Teaching language**: Farsi (fa-IR) — right-to-left script
- **Features**: audio pronunciation, RTL text rendering

## Labels

`Language`

## Conventions

- `q` = Farsi example (teaching language, RTL)
- `a` = translation in interface language
- Persian script must render correctly (RTL)

## Development

```bash
# Generate audio (Edge TTS) for each interface language
bash generate-audio.sh deutsch/farsi
bash generate-audio.sh english/farsi
bash generate-audio.sh farsi/farsi
```

## See Also

- [Open Learn Platform](https://github.com/openlearnapp/openlearnapp.github.io)
- [Workshop Guide](https://github.com/openlearnapp/openlearnapp.github.io/blob/main/docs/workshop-guide.md)
- [Lesson Schema](https://github.com/openlearnapp/openlearnapp.github.io/blob/main/docs/lesson-schema.md)
- [Workshop Creator Plugin](https://github.com/openlearnapp/plugin-workshop-creator)
