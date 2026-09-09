# NotebookLM — How to generate the briefing narration

## Setup
1. Create a new notebook in NotebookLM.
2. Upload `NotebookLM-Pitch-Brief.md` from this folder as the only source. Optionally add `PROJECT-BRIEF.md` and `ASSETS.md` from the repo root for depth, but the pitch brief alone is enough and keeps the hosts on message.
3. Open Studio, choose Audio Overview, pick the **Brief** format and the **shorter** length. Paste the prompt below into the customization box.
4. Download the audio as WAV or MP3 and drop it in the repo as `strategy-briefing-audio.wav` (or .mp3). The video will be re-timed to it.

## Prompt to paste

Copy everything between the lines.

---
You are producing a short campaign strategy briefing, not a discussion. Target length: about two minutes. Tone: confident, direct, plain-spoken, like a strategist walking a client through a plan. No banter, no jokes, no "welcome to the show," no speculation beyond the source.

Follow this order and do not skip a step:

1. Open on the line "D.C. has heard a lot of promises. This campaign is built on something different. Proof."
2. State the objective in one breath: build broad visibility, repeated familiarity, and cultural relevance for Rhonda Hamilton, so she is known and credible before residents ever see an ad.
3. Read the audit numbers exactly as written in the source: 77 percent cost of living, 73 percent public safety, 71 percent housing, 32 percent primary turnout, 91,000 independents locked out of the closed primary. Say who the audience is: the two thirds who sat out, the 91,000 independents, and the undecided east of the Anacostia River.
4. Walk the seven public critiques one at a time, each with its one-line answer, in the order the source lists them. Keep the exact names of the content lanes: "Who Is Rhonda Hamilton?", "Independent, Explained", "Proof, Not Slogans", "Why I Ran Again", "Beyond Mental Health".
5. Describe the clipping and seeding machine in six steps: collect, review, reposition, campaign content folder, post and seed, measure and scale. Name Opus Clip. Name Daily Posters and Seeders. End the step with "the winners become ads."
6. Close on the brand position, exactly: "Promises are easy. Follow-through is the proof. D.C., we just have to win."

Rules: use only facts from the source. Do not add statistics, names, or claims that are not in it. Do not editorialize about the candidate or her opponents. Do not summarize at the end. Stop after the closing line.
---

## If the Brief format still sounds like two hosts chatting
Regenerate with this added to the top of the prompt: "Deliver this as a single continuous narration. If two voices are required, the second voice only reads the critique questions in step 4, and the first voice answers them."
