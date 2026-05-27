# Google for Startups Cloud Program Application Packet

Date: 2026-05-26

## Recommended Application Target

- Program: Google for Startups Cloud Program
- Tier to target first: Start tier
- Reason: The project appears early-stage and pre-funded. The Start tier is designed for technology startups that have not received institutional equity funding and can offer up to USD 2,000 in Google Cloud credits.
- Possible future upgrade: AI / Scale tier, only if there is verified Seed-Series A equity funding and a stronger public startup footprint.

## Current Google Cloud Facts

- Closed billing account: `015C0F-6CF3DD-AA8854`
- Closed billing account display name: `我的结算账号`
- Old project: `project-23377f97-70ef-411f-8ae`
- Old project billing state: `billingEnabled: false`
- Open billing account: `015E85-7C81FC-9405FD`
- Open billing account display name: `My Billing Account`
- Open billing account currently linked project: `gen-lang-client-0675531481`
- Credits page for open billing account: no issued credits displayed

Use the open billing account ID in the application unless you intentionally create a new startup-specific billing account.

## Startup Positioning

Working name:
Animal Music Studio

One-line description:
Animal Music Studio is an AI-assisted media tool that turns real animal sounds into structured musical clips and short-form video assets for creators, educators, and entertainment channels.

Short description:
Animal Music Studio helps creators build novel music and video content from real animal vocalizations. The product pipeline ingests public or licensed animal sounds, analyzes pitch and timbre, ranks usable clips, maps them to melody templates, and generates ready-to-use audio/video outputs. The goal is to make a creator workflow that is faster, more transparent, and more controllable than generic text-to-video generation.

Customer/problem:
Short-form creators and niche media operators want fresh, repeatable content formats, but current AI music/video tools often produce generic results and give limited control over source sounds. Animal Music Studio focuses on a distinct workflow: real source audio, transparent scoring, reusable sound libraries, and structured generation for repeatable content series.

Why Google Cloud:
Google Cloud is a strong fit because the product needs scalable media processing, object storage, model-assisted audio/video analysis, and generative AI for multimodal ideation and production. Vertex AI / Gemini can support metadata extraction, script and caption generation, quality review, and later video generation experiments. Cloud Run, Cloud Storage, and Firestore can support the web workflow and asset library.

Current stage:
Prototype/MVP. A local working prototype already manages a sound library, processed audio clips, pitch analysis, melody templates, generated compositions, and a browser-based management UI.

Planned use of credits:
- Host the prototype backend and UI on Cloud Run.
- Store processed sound/audio assets in Cloud Storage.
- Use Vertex AI / Gemini for metadata extraction, captioning, QA review, and content packaging.
- Experiment with Veo/Imagen only after budgets and guardrails are set.
- Add monitoring, budgets, and usage alerts before production traffic.

Estimated initial usage:
Low-volume MVP testing for 1-3 months, focused on creator workflow validation, content quality, and cost monitoring.

## Suggested Form Answers

Company/startup name:
Animal Music Studio

Website:
Published temporary landing page:
`https://sj2025506282-creator.github.io/animal-music-studio/`

This GitHub Pages site is usable as a public startup website for an MVP application. A custom domain and matching business email would be stronger, but the current Google form blocks personal Gmail before the website step.

Free developer subdomain request:
`animalmusicstudio.is-a.dev`

PR:
`https://github.com/is-a-dev/register/pull/39390`

Status as of 2026-05-27 morning: CI checks passed; waiting for is-a.dev maintainer review/merge.

Business email:
User-provided email: `sj2025506282@gmail.com`
Form result: Google rejects Gmail with "Personal email accounts are not eligible for the program."
Temporary fallback tested in form: `2025506282@qq.com` was not immediately rejected by front-end validation, but it is still weaker than a domain-matched business email.
Best: an email at the same domain as the website.
Fallback: Gmail may work for informal early-stage applications, but Google FAQ says the business email should match the startup public website domain.

Business phone:
User-provided phone: `+86 13020271731`
Form note: set Calling Code to China (+86); Singapore (+65) makes the number invalid.

Industry:
Media / Entertainment / Creator Tools / AI

Funding stage:
Pre-funded / bootstrapped, unless there is real equity funding to disclose.

Has received institutional funding:
No, unless true.

Founded:
Use the real startup/project start date. If no legal entity exists, describe as early-stage startup project/MVP, but do not invent incorporation details.

Cloud billing account ID:
`015E85-7C81FC-9405FD`

Google Cloud products planned:
Cloud Run, Cloud Storage, Firestore, Vertex AI, Gemini API, Cloud Monitoring, Cloud Build.

Primary AI products:
Gemini on Vertex AI for multimodal metadata, creative assistance, review, and orchestration; Veo/Imagen later for video/image generation experiments if credits and eligibility permit.

Why credits are needed:
Credits would let the startup validate the MVP without prematurely incurring production cloud and generative media costs. The focus is to test technical feasibility, creator demand, and unit economics under budget controls.

## Stronger 500-Character Pitch

Animal Music Studio turns real animal sounds into structured music and short-form media. The MVP analyzes pitch/timbre, ranks usable clips, maps sounds to melody templates, and generates creator-ready audio/video assets. Google Cloud credits would support Cloud Run hosting, asset storage, and Vertex AI/Gemini workflows for metadata, captions, QA, and multimodal production experiments.

## Stronger 1,000-Character Pitch

Animal Music Studio is an AI-assisted creator tool for turning real animal vocalizations into repeatable music and video content. The current MVP manages a sound library, processed clips, pitch analysis, melody templates, generated compositions, and a browser UI for auditioning and exporting outputs. Unlike generic generation tools, the workflow is source-audio-first: it uses transparent scoring, reusable sound libraries, and structured composition templates so creators can build recognizable series formats. Google Cloud credits would help move the prototype from local tooling to a hosted MVP using Cloud Run, Cloud Storage, Firestore, and Vertex AI/Gemini for metadata extraction, captioning, QA review, content packaging, and later controlled Veo/Imagen experiments. The goal is to validate creator demand and unit economics before scaling usage.

## Submission Risks / Blockers

- Public website is probably required or strongly recommended.
- Business email matching the website domain is recommended by Google.
- User does not currently have a company/legal entity. Do not invent one in the application.
- Do not claim funding, incorporation, users, revenue, or partnerships unless true.
- Credits are not guaranteed and may not cover all products or third-party marketplace services.
- If the application asks for final submission, the user should confirm before sending.

## Minimum Next Step

Create or point to a simple public landing page and matching email/domain if possible, then submit the Start tier application using the open billing account ID `015E85-7C81FC-9405FD`.
