# SiteCheck

An agent that pre-inspects homes from phone photos, built for the
**Meta Global AI Developer Hackathon** (Indie track, solo).

## Problem
Professional home inspections are expensive, so many renters and
first-time buyers skip them and find damp, cracks, and other defects
only after they've committed.

## What it does (planned)
1. User uploads photos of a room (optionally with an A4 sheet for scale).
2. **SAM 3.1** segments cracks and damp stains from text prompts.
3. **OpenCV** converts the masks into measurements (area, crack length).
4. **Muse Spark** classifies each defect, rates severity, and returns
   structured JSON.
5. The app produces a defect report for the user.

It is a screening aid, not a replacement for a licensed inspector.

## Status
Started Oct 26, 2026. Everything in this repo is built during the
hackathon.

## Tech
Python, SAM 3.1, Meta Model API (Muse Spark), OpenCV, NumPy, Gradio

## Setup
Coming soon.

## Evaluation
Coming soon: test set results, including failure cases.
