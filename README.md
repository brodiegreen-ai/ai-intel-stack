# AI Intel Stack

Personal AI research and daily briefing system designed to keep me up to date on the most important developments in AI, and relate them directly to my work and future career.

## What this project is

This is a working “AI intel stack” that will eventually:

- Pull updates from high-signal AI sources (lab blogs, newsletters, selected YouTube channels).
- Normalise and filter the raw information.
- Generate a structured daily/weekly digest with sections for:
  1. Models & Infrastructure  
  2. Agents, Tools & Workflows  
  3. Business & Strategy  
  4. Policy, Safety & Industry Moves  
  5. What This Means for Brodie (Action Ideas)

Right now this is an early proof of concept: the focus is on designing the structure, sources, and prompts before full automation.

## Who it’s for

- **Primary user:** Brodie Green – learning AI deeply, building AI-assisted side businesses (Etsy planners, digital products), and aiming to move from call centre work into an AI-focused career.
- **Future users:** Anyone who wants a configurable AI briefing system that connects general AI news to their own domain (e.g. cybersecurity, app development, trading).

## Core ideas

- Separate the **engine** (fetch + summarise) from the **user profile** (goals, domains, preferred sources).
- Provide a consistent digest structure so it’s easy to scan and compare across days.
- Always end with concrete implications and action ideas for the user, not just headlines.

## Example digest entry (NotebookLM Cinematic Video Overviews – 2026-03-11)

**1. Models & Infrastructure**

- Google added *Cinematic Video Overviews* to NotebookLM: a three-model stack (Gemini 3, Nano Banana Pro, Veo 3) that turns documents into short, fully animated explainer videos instead of narrated slideshows.[web:329][web:335][web:340]

**2. Agents, Tools & Workflows**

- Workflow: you upload sources (PDFs, Docs, transcripts), Gemini 3 acts as a creative director deciding narrative and emphasis, Nano Banana Pro generates custom imagery, and Veo 3 stitches it into fluid, documentary-style video.[web:329][web:341][web:345]

**3. Business & Strategy**

- At launch, Cinematic is locked to the $249.99/mo Google AI Ultra plan, but that price includes Gemini 3 Deep Think, Veo 3, Flow editor, and large storage; the clearest ROI is for teams turning dense specs/docs into internal explainers and sales enablement content.[web:329][web:345][web:348]

**4. Policy, Safety & Industry Moves**

- Google runs this entirely on its own cloud and tags visuals with SynthID-style watermarks so AI output can be recognised later, which helps provenance and trust but means all data flows through Google’s stack and users are locked to Gemini rather than choosing their own models.[web:329][web:345][web:348]

**5. What This Means for Brodie (Action Ideas)**

- Treat “LLM as creative director + specialist models as executors” as a reusable pattern for your own stacks (for example: newsletter director → email sender, research director → chart generator).[web:329][web:341]
- When it becomes affordable or gets a trial, test NotebookLM (or similar tools) to turn planner instructions or Etsy listing copy into quick educational videos for listings, onboarding, or YouTube.[web:329][web:335][web:340][web:345]
- Keep a running list of “videos that don’t exist because they’re too hard to make” (ING help hub flows, planner walk-throughs, AI-intel explainers); those are prime candidates for tools like this.[web:329][web:335][web:340][web:345]

---
## Project goals (2026)

- Build a working AI intel system that briefs me on the most important AI developments and how they affect my career and businesses.
- Learn the core tools of an AI workflow stack (GitHub, Supabase, n8n, LLM APIs) by using them on a real project.
- Turn this into a portfolio piece that could later evolve into a configurable product for other people (different profiles, same engine).
---
## Next steps

- Add `sources.yaml` describing the initial AI sources (lab blogs, newsletters, selected channels).
- Add a `digest_prompt.md` file with the full prompt template used to generate daily/weekly digests.
- Later: implement fetching, storage, and automated digest generation using an orchestration tool (e.g. n8n + Supabase + LLM API).
