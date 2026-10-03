# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this repo is

This is the `.github` repository for the **Next Gen Insights** GitHub organization ("Harvest your data, fast." — AI-powered data solutions built on a consistent, repeatable framework). It contains no application code: there is no build, lint, or test tooling.

## About the owner

Sole proprietor of Next Gen Insights; no team. Works in data and AI across multiple industries.

## Working rules

- Ask before changing `profile/README.md` (or anything else public-facing). Show the proposed edit first.
- Claude may commit and push on its own when it makes sense; no need to ask each time.
- Tone: friendly but concise. Applies to public writing and to replies.

## Layout

- `profile/README.md` — the organization's public profile page, shown on the org's GitHub landing page. Edits here are customer-facing. It still contains a placeholder (`[your email or website]`) in the "Get in touch" section.
- `TASKS.md` and `dashboard.html` — personal task tracking from the productivity plugin. `TASKS.md` uses fixed sections (Active, Waiting On, Someday, Done). `dashboard.html` is a self-contained single-file UI (inline CSS/JS, no build step) that the user opens in a browser and points at `TASKS.md` via the File System Access API. It also reads and edits `CLAUDE.md` and `memory/` from the same directory, so keep those names and locations stable.
- `memory/` — working-memory directory used by the productivity plugin (currently empty).

## Notes

- Files in the root of an org `.github` repo can act as organization-wide defaults (e.g. `profile/`, and community health files such as issue templates, `CONTRIBUTING.md`, `SECURITY.md` if added). Changes here can affect every repo in the org that lacks its own copy.
