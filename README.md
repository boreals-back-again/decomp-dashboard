# Minecraft LCE Decomp Dashboard

Live progress tracker for the Minecraft Legacy Console Edition (Switch v1.0.17) decompilation effort.

**Live: https://decomp.coah80.com**

## What is this?

A static dashboard showing real-time matching decompilation progress.
Updates automatically every minute via the [decomp-agent](https://github.com/coah80) pipeline.

## Stack

- Static HTML/CSS/JS — no backend
- Auto-deployed via Cloudflare Pages
- Data file `progress.json` written by the local decomp pipeline
- Auto-pushed to GitHub on changes

## Reference Project

[GRAnimated/MinecraftLCE](https://github.com/GRAnimated/MinecraftLCE) — community decomp at 11.2%
