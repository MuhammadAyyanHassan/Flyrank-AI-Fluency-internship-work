# Reviewer Context

## What this repository is

This is the public evidence archive for the FlyRank AI General AI Fluency internship. It separates assignment evidence, capstone work, portfolio evidence, supporting artifacts, and final-package materials so a reviewer can trace the work without relying on an informal folder dump.

## How to review it

Start with `final-submission/FINAL_INDEX.md`. It contains the current requirement/status audit and links to the live portfolio, retrospective, demo, and external submission context. Then open the relevant assignment folder and read the preserved artifact.

## Evidence policy

The archive distinguishes evidence from external administrative state. A GitHub file does not automatically prove that the FlyRank portal submission was saved, a URL does not automatically prove a portal requirement, and an existing artifact is not treated as complete merely because its filename sounds correct.

## Portfolio context

The portfolio is a separate repository: `MuhammadAyyanHassan/Ayyan_Hassan_portfolio`. Its locked identity uses Space Grotesk for headings, Inter for body text, Deep Burgundy `#6B1F2A`, Ink `#171717`, and Warm White `#F7F5F2`. The intended mood is quietly technical and deliberate, with typography, spacing, and restraint carrying the visual identity.

The portfolio currently documents a claim → proof → contact journey, a Next.js/TypeScript implementation, a working contact route, a v2 hardening pass, known limitations, a retrospective, and AI-use transparency.

## Key build decisions

The stack decision compared plain HTML/CSS/JavaScript, Astro, and Next.js + TypeScript against actual constraints. Next.js + TypeScript was selected because it matched the author's practical experience, provided reusable structure for repeated case-study patterns, and left room to expand without requiring a backend immediately.

The design system was deliberately constrained rather than decoration-heavy. Real project captures remain the source of security evidence; generated imagery is limited to connective atmosphere.

## Verification / hardening

The portfolio's documented hardening work covered form validation and edge cases, rapid duplicate submission, script-like input, boundaries, special characters and Unicode, submission/refresh behavior, API method rejection, narrow layouts, links, findability, social preview, PageSpeed evidence, and mobile behavior. The documented hardening result is PASS. The known limitation is that the public contact endpoint does not yet have a dedicated rate-limiting / anti-spam layer.

## FL-09 documentation/demo

The portfolio README is the documentation artifact. It contains purpose/audience, setup, usage, a simple architecture sketch, v2 hardening results, limitations, and AI-use disclosure. The permanent demo Drive URL is recorded in the master index and portfolio README. The video was supplied as the demo artifact; this audit does not claim that the video was independently watched.

## FL-10 final checkpoint

The portfolio repository contains the 500–800 word retrospective and reviewer context. The master repository contains the final index and links to those artifacts. The following remain external verification items unless direct evidence is supplied: portal hours log, required FlyRank launch/custom-domain condition, build-in-public post, final human review/sign-off, and any showcase-thread submission.

## FL-08 caution

The current authoritative FlyRank public assignment page lists seventeen assignments across ten weeks and names the Week 9 assignments explicitly, but it does not use the user's FL-08 code in the public page. Therefore this archive intentionally does not invent an FL-08 code mapping. The exact internal code/portal card should be verified before marking FL-08 complete.

## Review path

`FINAL_INDEX.md` → assignment folder → artifact → live/external evidence → final checkpoint context.
