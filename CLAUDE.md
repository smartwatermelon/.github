# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Purpose

This is the **`.github` organization-level repository** for the `smartwatermelon` GitHub organization. It provides defaults inherited by all repos in the org:

- **`.github/FUNDING.yml`** — Sponsorship config (Ko-fi, Buy Me a Coffee) inherited by repos without their own
- **`workflow-templates/`** — Reusable workflow templates available in the Actions tab of any org repo

## Architecture

There is no build system, test suite, or application code. This repo contains only GitHub configuration files:

- `workflow-templates/dependabot-auto-merge.yml` — Workflow template that auto-merges eligible Dependabot PRs
- `workflow-templates/dependabot-auto-merge.properties.json` — Metadata (name, description, icon, categories) that GitHub uses to display the template

## Key Details

- The actual workflow logic lives in `smartwatermelon/github-workflows`, not here — this repo only holds the template pointer
- FUNDING.yml is automatically inherited org-wide; no per-repo action needed
