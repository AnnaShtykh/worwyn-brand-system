# Setup Instructions — Your AI Brand Assistant

Set up ChatGPT or Claude to create on-brand Worwyn content. One-time setup, about 5 minutes. *(This document also exists as `Setup_Instructions.pdf` — same content.)*

## What you'll upload

From this repository, you need these files:

**Knowledge files (7):**
1. `01_BRAND_FOUNDATION/Brandbook.pdf`
2. `02_AI_GUIDELINES/AI_Brand_Instructions.md`
3. `02_AI_GUIDELINES/Visual_Language.md`
4. `02_AI_GUIDELINES/Tone_of_Voice.md`
5. `02_AI_GUIDELINES/Do_Dont.md`
6. `03_CONTENT_SYSTEM/Instagram_Posts.md` and/or `LinkedIn_Posts.md` and/or `Presentations.md` (whichever you create content for)

**Instructions file:** `04_SETUP/Master_Prompt.txt` (you'll paste its text, not upload it)

Tip: click the green **Code ▾** button on the GitHub repo page → **Download ZIP** to get everything at once.

## Option A — ChatGPT (Projects)

1. Go to [chatgpt.com](https://chatgpt.com) → sidebar → **Projects** → **New project**. Name it `Worwyn Brand`.
2. Open the project → **Project files** → **Add files** → upload the 7 knowledge files listed above.
3. Open **Instructions** (in the project settings) → paste the full text of `Master_Prompt.txt` → save.
4. Start a new chat inside the project. It should greet you with *"Worwyn Brand Assistant ready."*

*(Alternative: create a Custom GPT via **Explore GPTs → Create**, paste the master prompt into Instructions and upload the same files into Knowledge — useful if you want to share the assistant with the team.)*

## Option B — Claude (Projects)

1. Go to [claude.ai](https://claude.ai) → sidebar → **Projects** → **Create project**. Name it `Worwyn Brand`.
2. In the project, open **Project knowledge** → **Add content** → upload the 7 knowledge files.
3. Click **Set custom instructions** → paste the full text of `Master_Prompt.txt` → save.
4. Start a new chat in the project. It should greet you with *"Worwyn Brand Assistant ready."*

## Using your assistant — example prompts

- "Write Monday's Instagram statement post about why resumes hide personality. Give me the visual concept + caption + hashtags + alt text."
- "Create a 6-slide tip carousel: '5 Vibe Video™ mistakes'. Copy for every slide."
- "Write a LinkedIn perspective post for employers about feeling the fit before the first interview."
- "Draft the content of a 10-slide intro deck following the deck skeleton."
- "Give me a Midjourney prompt for a celebration image for a Mutual Rise™ announcement."

## Keeping it on-brand

- If output drifts off-brand, reply: *"Check this against Do_Dont.md and fix it."*
- When brand files change in this repo, re-upload the changed files to the project (delete the old copy first).
- The assistant is instructed to ask rather than invent facts — answer its questions, don't let it guess.

## Troubleshooting

| Problem | Fix |
|---|---|
| Doesn't greet / ignores rules | Instructions weren't saved — re-paste `Master_Prompt.txt` into the project's instructions field |
| Wrong colors or fonts in concepts | Say "follow AI_Brand_Instructions.md section 2" — check files are actually uploaded |
| Generic corporate tone | Say "rewrite per Tone_of_Voice.md voice traits table" |
| Can't read the brand book | Make sure you uploaded `Brandbook.pdf` (the merged file), not the 22 single pages |
