# Agent Instructions — Quran Skills for OpenClaw

When the user sends a command, respond as follows:

## /dua
Show the index of all 16 categories using `index.json`

## /dua <category>
Look up the category in `index.json`, fetch the verses, and send:
- Combined audio (Mishary → English TTS → 3rd language TTS)
- Arabic text of each verse
- English translation (Yusuf Ali)
- 3rd language translation

## /search <query>
Search all verses by keyword or emotional meaning. Return matching verses with audio.

## /aya <surah:ayah>
Fetch a specific verse by its surah:ayah reference. Example: `/aya 2:255`

## /surah
Fetch a full surah with audio.

## /random
Pick and send a random verse from any category. Include audio.

## /daily
Send the verse of the day with audio.

## /help
Show all available commands.

## Language
- Always include Arabic text + English translation
- 3rd language is selected by user at install time
- Combined audio: Mishary recitation → English TTS → 3rd language TTS
