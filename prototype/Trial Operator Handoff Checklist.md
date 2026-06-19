# Codex Local Model Bench Kit — Trial Operator Handoff Checklist

Status: prepared for the next real trial; evidence pending.
Source: [[Codex OSS Mode for Local Models]]
Prototype: [[Codex Local Model Bench Kit/Local Model Bench Packet]]
Evidence index: [[Codex Local Model Bench Kit/Trial Evidence Index]]
Promotion gate: [[Codex Local Model Bench Kit/Post-Trial Promotion Decision Card]]
Debrief gate: [[Codex Local Model Bench Kit/Post-Trial Debrief Template]]

## Operator brief
Use this checklist to hand the next real trial to a bench operator without losing the evidence chain. The trial goal is to compare hosted Codex and one OSS/local provider on the same repo task.

## Before the trial
- [ ] Choose one real VinClawLabs task; do not use fabricated or demo-only evidence.
- [ ] Open the prototype artifact: `Local Model Bench Packet.md`.
- [ ] Open `Trial Evidence Index.md` and reserve rows for every proof link you expect to capture.
- [ ] Confirm where logs, screenshots, diffs, and notes will be stored.
- [ ] Write the expected decision question in one sentence: "Should this artifact be promoted, iterated, or held after this trial?"

## During the trial
- [ ] Capture timestamps for key operator actions.
- [ ] Save raw logs/transcripts before summarizing.
- [ ] Record any confusing step immediately; do not clean it up before the debrief.
- [ ] Link each claim-worthy observation into `Trial Evidence Index.md`.
- [ ] Keep separate notes for observed facts vs. interpretation.

## Evidence to attach
- [ ] Repo/task link and branch or patch under test
- [ ] Codex hosted run transcript or terminal log
- [ ] OSS/local provider config, model name, hardware, and run log
- [ ] Diff/output artifact from each run
- [ ] Scorecard notes for correctness, latency, cost, ergonomics, and failure modes

## After the trial
- [ ] Complete `Post-Trial Promotion Decision Card.md` with a promote / iterate / hold decision.
- [ ] Fill `Post-Trial Debrief Template.md` with exact README, prototype, and skill-draft patches.
- [ ] Patch only claims backed by `Trial Evidence Index.md` links.
- [ ] Leave unresolved or low-confidence claims marked as evidence pending.

## Red flags that block promotion
- Different task prompts or repo states between hosted and local runs
- Missing model/config details that prevent rerun
- Claiming speed or quality wins without timestamps, logs, or diff evidence
- Promoting the skill draft before the debrief identifies repeatable steps

## Handoff summary
- Next operator:
- Trial date:
- Real task link:
- Evidence folder/link:
- Decision owner:
- Follow-up patch owner:
