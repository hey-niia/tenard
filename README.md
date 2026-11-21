# Tenard

Pocket tenant advocate for NYC renters. Gemini 4 NYC Hackathon, Nov 21 2026.

A renter describes a problem in their apartment in a chat, adds photos or video, and Tenard:

1. checks it against NYC housing rules (Housing Maintenance Code, HPD violation classes),
2. explains the renter's rights in plain language,
3. drafts the landlord notice and the 311 complaint,
4. tracks the case through escalation: notice → 311 → HPD inspection → violation → HP action in Housing Court,
5. closes the case once the repair is confirmed with a photo.

Problem types in the MVP: mould, leaks, peeling paint, windows and window guards, smoke and CO detectors.

## Status

Clickable prototype. The chat is scripted from the team's decision tree; it is not connected to Gemini yet.
Rule sections, 311 categories and product links are placeholders (`[section]`, `[311 type]`, `[Store]`).

## Try it

- Live: https://hey-niia.github.io/tenard/
- First grayscale version: https://hey-niia.github.io/tenard/v1/

## Run it locally

```bash
python3 -m http.server 5180
```

Then open:

- http://localhost:5180 — current version (brown and cream accents, cases in a bottom sheet)
- http://localhost:5180/v1/ — first grayscale prototype, kept for comparison

## Not legal advice

Tenard explains the law. It is not a lawyer, and every result is a possible violation, not an official finding.
