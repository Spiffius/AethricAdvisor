# AethricAdvisor

A smart gear and skill evaluator for **Hero of Aethric** and **Orna: The GPS RPG**.

## Features

- **Build Profiles**: Store multiple character profiles with detailed stats, gear, and skill loadouts
- **Gear Evaluator**: Analyze gear via screenshot or manual entry against your build identity
- **Skill Evaluator**: Evaluate skills/spells for build fit, elemental coverage, and rotation placement
- **Loadout Tracker**: Track your current equipped gear and active skills
- **Meta Refresh**: Search for latest patch notes, tier lists, and community discussions

## How It Works

AethricAdvisor goes beyond raw stat comparison. It understands:
- Build identity and endgame goals
- Faction synergies (Knights of Inferno, Earthen Legion, Stormforce, Frozenguard)
- Known weaknesses and priorities
- Combat rotation and skill synergies

## Setup

1. Open `index.html` in your browser
2. Enter your Anthropic API key in the Profile tab
3. Switch between the pre-loaded profiles (Biffius and Spiffius) or create your own

## API Key

This app uses the Anthropic Claude API for:
- Screenshot analysis (vision)
- Contextual gear/skill evaluation
- Meta search with web search tool

Your API key is stored locally in your browser's localStorage and is only sent to Anthropic's API.

## Tech Stack

- React 18 (via CDN)
- Tailwind CSS (via CDN)
- Anthropic Claude API (claude-sonnet-4-20250514)
- LocalStorage for persistence
- Single-file deployment
