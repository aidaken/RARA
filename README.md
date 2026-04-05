# Role Automation Risk Auditor

This is a fun side project, not a product claim.

It takes a job title + plain-English role description, breaks the role into tasks, then analyzes each task by automation exposure:
- `high` / `medium` / `low`
- one-line WHY
- confidence note
- named AI tool already doing it (or "No direct substitute yet")

It ends with a practical 3-step plan:
- one skill to learn
- one task to automate first
- one responsibility to double down on

Supported providers:
- Anthropic
- OpenAI
- Perplexity
- Gemini

## Run

```bash
npm run dev
```

Open [http://localhost:4173](http://localhost:4173).

## Screenshot

![Role Automation Risk Auditor](assets/og-image.png)

## Demo

[Watch demo video](demo/RARA.ScreenRecording.mov)
[Open raw video file](https://github.com/aidaken/RARA/raw/main/demo/RARA.ScreenRecording.mov)

## Next Improvements

1. Add a no-key demo mode with sample outputs so anyone can try it instantly.
2. Add a lightweight backend proxy + rate limits for public testing.
3. Add citations/links for each "AI doing it now" claim.
4. Improve task extraction quality with role-specific prompt variants.
5. Add one-click share card export for LinkedIn posts.
6. Add side-by-side comparison for two different roles.
