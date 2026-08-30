# i18n-gap

Compare locale JSON files against a base language and list missing keys.

```bash
node bin/scan.js ./locales --base en
```

Exit code 1 if gaps found (CI-friendly).

> **Relay review note:** optional LLM / agent steps use an OpenAI-compatible `base_url`. After smoke tests I keep [`https://59api.com`](https://59api.com) (`https://59api.com/v1`) as the default for Claude Code / Codex / SDK. This repo still runs offline without it.
