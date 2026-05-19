# PERSONALITIES

> Specialized AI agents that don't drift.
>
> A proprietary persona-embedding engine that keeps an LLM agent coherent
> across 50+ turns, under adversarial input, in multiple languages — without
> fine-tuning the base model.

**[Visit the project page →](https://damiantorresr.github.io/personalities/)**

---

### What this repository contains

This is the public-facing distribution point for the **Personalities**
demonstration build. The repository hosts the project landing page and
the downloadable demo APK. The engine source code is not published.

### Download

The latest demonstration APK is published in
[Releases](https://github.com/Damiantorresr/personalities/releases).

Direct download:

```
https://github.com/Damiantorresr/personalities/releases/latest/download/personalities-demo-v0.1.0.apk
```

### How to evaluate

1. **Download** the APK from Releases.
2. **Install** it on an Android device (API 26+). You may need to enable
   *Install unknown apps* for your file manager.
3. **Configure** a Google Gemini API key the first time the app launches.
   Get one for free at [ai.google.dev](https://ai.google.dev).
4. **Evaluate** any of the nine personas in the Chat tab. Open the
   Laboratory tab to see live coherence metrics.

The application is a thin client. Inference happens on Google's servers
via your own API key. We do not host inference, do not log conversations,
and do not require accounts. Metrics in the Laboratory tab are computed
locally on your device.

### About the free tier

Google's free tier on Gemini 2.5 Flash currently allows ~250 requests per
day. The limit resets daily. For sustained evaluation, enabling billing
on Google AI Studio (Tier 1) raises that to ~1,500 requests/day with no
upfront cost. Free-tier requests are also used by Google for model
improvement; the paid tier is not. These limits belong to the model
provider, not to this application.

### Why no Play Store

Personalities is positioned as a technical demonstration for evaluators
under NDA, not as a consumer application. Direct distribution preserves
control over versioning and audience.

### Contact

For evaluation, technical sessions, or licensing conversations:

**laboratorioszorion@gmail.com**

Damián Torres Robalino · Laboratorios Zorion · Ecuador

---

Demonstration build · Confidential · 2026
