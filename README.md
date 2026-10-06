# Awesome Suno AI [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![Stars](https://img.shields.io/github/stars/shaizadok92/awesome-suno?style=social)](https://github.com/shaizadok92/awesome-suno/stargazers)

> The canonical curated list of tools, resources, and communities for [Suno AI](https://suno.com) music generation.

**Suno** is a generative AI music platform that creates full songs — vocals, instruments, production — from text prompts. This list is the definitive reference for its ecosystem.

**Maintenance**: Updated weekly. Contributions welcome — see [Contributing](#contributing).
**Last updated**: April 2026.

---

## Contents

- [Official Suno Resources](#official-suno-resources)
- [Prompt Building Tools](#prompt-building-tools)
- [Meta Tag References](#meta-tag-references)
- [Educational Resources](#educational-resources)
- [YouTube Channels](#youtube-channels)
- [Communities](#communities)
- [Complementary Tools](#complementary-tools)
- [Wikis](#wikis)
- [Blog Articles](#blog-articles)
- [Developer Resources](#developer-resources)
- [Related Awesome Lists](#related-awesome-lists)
- [Contributing](#contributing)

---

## Official Suno Resources

- [Suno](https://suno.com) — Official site. Generate songs from prompts. Free tier + paid plans.
- [Suno Help Center](https://help.suno.com) — Official documentation and FAQs.
- [Suno Blog](https://suno.com/blog) — Platform updates and release notes.
- [Suno Discord](https://discord.gg/suno) — Official community (~400K members).
- [Suno on YouTube](https://www.youtube.com/@SunoMusic) — Official channel.

---

## Prompt Building Tools

Tools that help you write better Suno prompts before generating.

- [**AceTagGen**](https://acetaggen.com) — Free structured prompt builder for Suno AI. Pick mood, genre, instruments, SFX from 3,000+ curated tags; outputs a Suno-ready prompt that respects the 200-character Style field. Includes quality-score validator, example library, and AI Chat mode (Premium).
- [Suno Prompt Builder at usesuno.online](https://usesuno.online/tools) — Community-built prompt helpers.
- Generic LLMs (ChatGPT, Claude) — Can generate prompts but often exceed Suno's 200-char Style limit and include tags Suno silently ignores.

---

## Meta Tag References

- [Suno AI Wiki: Metatags](https://sunoaiwiki.com) — Community meta tag reference covering structural, vocal, instrument, and effects categories.
- [AceTagGen Example Library](https://acetaggen.com) — Genre-grouped tested prompt combinations.

> **Note**: Suno tag behavior differs between versions (v4 vs v4.5 vs v5). Always test on your target version.

---

## Educational Resources

### Articles & Guides

- [Learn Prompting: Suno Guide](https://learnprompting.org/blog/guide-suno) — 4 prompt components (genre, mood, instrumentation, vocals) walkthrough.
- [AceTagGen Blog](https://acetaggen.com/blog) — Deep research on Suno v5 vs v4, prompt mechanics, why generic prompts fail, tag-test data.

### Key Deep Dives

- ["The Science Behind Perfect SUNO Prompts"](https://acetaggen.com/blog/science-behind-perfect-suno-prompts) — How Suno actually processes tags.
- ["Why Most Suno Prompts Fail"](https://acetaggen.com/blog/why-most-suno-prompts-fail-and-how-to-stop-guessing) — 3 structural failure patterns.
- ["Suno v5 vs v4: Complete Comparison"](https://acetaggen.com/blog/suno-v5-vs-v4-complete-comparison) — Version differences.
- ["17 Suno Tricks That Change How You Make Music"](https://acetaggen.com/blog/17-suno-tricks-change-how-you-make-music) — Advanced techniques.

---

## YouTube Channels

Creators consistently covering Suno-related content.

- [@AceTagGen](https://youtube.com/@AceTagGen) — Tag breakdowns with on-screen prompts (new channel).
- [@BobDoyleMedia](https://youtube.com/@BobDoyleMedia) — AI tools coverage including Suno.
- [@Misstiq](https://youtube.com/@misstiq666) — Music production + Suno.
- [@ChillPanic](https://youtube.com/@chillpanic) — Suno AI tutorials (Vincent Connell).

---

## Communities

### Reddit

- [r/SunoAI](https://www.reddit.com/r/SunoAI) — Primary subreddit (~100K members).
- [r/AIMusic](https://www.reddit.com/r/AIMusic) — Broader AI music (Suno, Udio, etc).
- [r/aiMusicGeneration](https://www.reddit.com/r/aiMusicGeneration) — Technical AI music discussions.

### Discord

- [Suno Official Discord](https://discord.gg/suno) — 400K members.

### Facebook

- "Suno & AI Music Creators" (Group)
- "AI Music Creators - Discuss & Share" (Group)

---

## Complementary Tools

For a complete Suno workflow.

### Lyrics Writing

- [ChatGPT](https://chat.openai.com) / [Claude](https://claude.ai) / [Gemini](https://gemini.google.com) — General LLMs for lyric drafts.
- [AceTagGen AI Lyrics Writer](https://acetaggen.com) — Premium feature.

### Post-Production

- [Audacity](https://www.audacityteam.org) — Free open-source DAW.
- [LALAL.AI](https://www.lalal.ai) — Stem separation for remixing Suno tracks.
- [Adobe Audition](https://www.adobe.com/products/audition.html) — Professional post-production.

### Distribution

- [DistroKid](https://distrokid.com), [SoundCloud](https://soundcloud.com), [BandCamp](https://bandcamp.com).

> **Legal note**: Suno's terms on commercial rights have changed multiple times. Always check current ToS before distributing commercially.

---

## Wikis

- [Suno AI Wiki](https://sunoaiwiki.com) — Comprehensive community wiki.
- [AI Music Wiki (Fandom)](https://aimusic.fandom.com/wiki/AI_Music_Wiki) — Broader AI music reference.

---

## Blog Articles

External articles worth reading about Suno:

- [Suno AI Reviews on Futurepedia](https://www.futurepedia.io/tool/suno) — User reviews and alternatives.
- [Suno on Wikipedia](https://en.wikipedia.org/wiki/Suno_(platform)) — Platform overview.

---

## Developer Resources

- [**suno-prompt-scorer**](https://github.com/shaizadok92/suno-prompt-scorer) — Zero-dependency TypeScript/JavaScript library that scores Suno prompts on a 100-point scale across 4 metrics (length, tag collisions, specificity, density). MIT-licensed. Also available as a [free public API](https://acetaggen.com/api/suno-score).
- [AceTagGen Public Scorer API](https://acetaggen.com/api/suno-score) — CORS-enabled HTTP endpoint for scoring Suno prompts from any web app. `GET /api/suno-score?prompt=...` — no auth, no rate-limit.
- [Suno API wrappers (GitHub)](https://github.com/search?q=suno+api&type=repositories) — Unofficial community wrappers. Suno has no official public API.
- [AceTagGen GitHub](https://github.com/shaizadok92/acetaggen) — Example implementation.

---

## Related Awesome Lists

- [awesome-ai-music-generation](https://github.com/Curated-Awesome-Lists/awesome-ai-music-generation)
- [awesome-ai-tools (mahseema)](https://github.com/mahseema/awesome-ai-tools)
- [awesome-generative-ai (steven2358)](https://github.com/steven2358/awesome-generative-ai)

---

## Contributing

Pull requests welcome. Guidelines:

1. **Tool must be specifically relevant to Suno AI.** Generic "AI music" tools belong in [awesome-ai-music-generation](https://github.com/Curated-Awesome-Lists/awesome-ai-music-generation).
2. **No dead links.** Tool must have been active in the last 6 months.
3. **No affiliate links.** Descriptions should describe what the tool does, not sell it.
4. **Alphabetical within sections** (except obvious featured items).
5. **One line per tool.** Format: `- [Name](url) — Description under 140 chars.`

To contribute:
1. Fork this repo
2. Edit `README.md`
3. Open a PR with a one-sentence explanation of why the tool belongs here

---

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

[CC0-1.0](https://creativecommons.org/publicdomain/zero/1.0/) — Public domain. Copy, adapt, redistribute freely.

---

**Maintainer**: [@shaizadok92](https://github.com/shaizadok92) — creator of [AceTagGen](https://acetaggen.com). Disclosure: I maintain this list and have added AceTagGen to it; I welcome PRs for any genuinely Suno-relevant tool including direct competitors.

**Star this repo** if it helped you discover useful Suno resources ⭐
