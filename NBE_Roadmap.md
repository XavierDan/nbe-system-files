# NBE Roadmap v1.0
**Narrative Blueprint Engine · EmbarkMedia · Confidential**

- **From:** v0.4 Alpha · June 25, 2026
- **To:** v1.0 Launch · September 12, 2026

---

## Purpose

This roadmap covers all forward-looking development work from v0.4 Alpha through the September 12, 2026 launch. Organized by deliverable, with phase labels and milestone dates as supporting context. It is the primary tool for tracking what remains and understanding how the pieces fit together.

It does not recapitulate completed work. The CHANGELOG owns that record.

---

## Planning Assumptions

- 15–20 hours/week sustained capacity
- PHP proxy deployment test is the first gate — all v0.5 work depends on it
- September 12, 2026 is the target launch date (~11 weeks from roadmap date)
- Product name (Narrative Blueprint Engine / NBE) is confirmed and locked

---

## Timeline Summary

| Version | Phase | Target |
|---|---|---|
| v0.5 | Validation & Logic Lock | July 11, 2026 |
| v0.6 | Output Quality & UX | July 25, 2026 |
| v0.7 | Internal QA & Documentation | August 8, 2026 |
| v0.8 | External Testing | August 22, 2026 |
| v0.9 | Launch Prep | September 5, 2026 |
| v1.0 | Launch | September 12, 2026 |

---

## Phase 1 — Validation & Logic Lock
**v0.5 Alpha · Target: July 11, 2026 · ~2 weeks**

> **Gate:** PHP proxy must be deployed and confirmed before other v0.5 deliverables can be tested end-to-end.

### D1 — PHP Proxy Deployment Test
Deploy `generate.php` to cPanel and confirm live API calls return valid responses.

- [ ] PHP proxy live on server
- [ ] Test call returns valid JSON from Claude API
- [ ] Error handling confirmed (timeout, malformed input, API failure)

### D2 — JSON Schema Validation
Validate SM² output schema against real API responses.

- [ ] Schema defined and documented
- [ ] Validation run against minimum 3 real API outputs
- [ ] Edge cases identified and handled

### D3 — Three-Lane Visual Match Taxonomy Implementation
Operationalize Literal / Interpretive-Metaphorical / Tonal-Atmospheric in the SM² logic layer.

- [ ] Taxonomy rules documented
- [ ] SM² system prompt updated to reflect taxonomy
- [ ] Output confirmed to produce all three lanes per beat

### D4 — SM² Logic Rules Documentation
Formal spec of the logic layer sufficient for developer handoff.

- [ ] Beat identification rules documented
- [ ] Multi-register output rules documented
- [ ] Format-awareness rules documented (video vs. audio-only)

### D5 — In-Browser Card Rendering
Confirm output renders correctly in `broll-generator.html`.

- [ ] JSON → card rendering working end-to-end
- [ ] Beat-by-beat output displays cleanly
- [ ] Copy-to-clipboard functional per section

**Milestone:** v0.5 Alpha complete when PHP proxy is live, JSON validates against real output, three-lane taxonomy is operational in the prompt, and cards render correctly in-browser.

---

## Phase 2 — Output Quality & UX
**v0.6 · Target: July 25, 2026 · ~2 weeks**

### D6 — Output Quality Validation
Test blueprint quality across both video and audio-only narrative formats.

- [ ] Minimum 5 video narrative test inputs run
- [ ] Minimum 5 audio-only narrative test inputs run
- [ ] Quality scoring rubric applied to each output
- [ ] Failure modes documented and addressed in prompt

### D7 — UX Polish
Refine the input experience and output display.

- [ ] Input field UX reviewed and tightened
- [ ] Output card layout finalized
- [ ] Print feature confirmed working (Print Selected / Print All)
- [ ] EmbarkMedia brand tokens applied throughout

### D8 — Card Structure Formal Spec
Document what each output card contains, including print card structure.

- [ ] Visual beat card structure documented
- [ ] Audio beat card structure documented
- [ ] Print card structure documented

**Milestone:** v0.6 complete when output quality is validated across both formats, UX is polished, and card structure is formally specced.

---

## Phase 3 — Internal QA & Documentation
**v0.7 · Target: August 8, 2026 · ~2 weeks**

### D9 — Internal QA Pass
Full end-to-end review before external eyes.

- [ ] All input types tested (script, VO draft, transcript, theme)
- [ ] Edge cases tested (very short input, very long input, audio-only, no clear beats)
- [ ] API cost per run measured and documented
- [ ] Known issues logged

### D10 — Developer Handoff Package
Everything a developer needs to build from, with no prior context required.

- [ ] System architecture documented
- [ ] SM² logic layer spec complete
- [ ] JSON schema documented
- [ ] Frontend/backend interaction documented
- [ ] Deployment instructions documented

### D11 — NBE Learning Curriculum
Complete Weeks 3–6 content (Weeks 1–2 exist in System Specification Section 5).

- [ ] Week 3 written
- [ ] Week 4 written
- [ ] Week 5 written
- [ ] Week 6 written

### D12 — GitHub Repo Migration
Migrate remaining MD candidates to the repo.

- [ ] System Specification migrated
- [ ] Project Instructions migrated
- [ ] Roadmap live (this document)

**Milestone:** v0.7 complete when internal QA passes, developer handoff package is complete, and all repo files are current.

---

## Phase 4 — External Testing
**v0.8 · Target: August 22, 2026 · ~2 weeks**

### D13 — External Test Users
Identify and brief 3–5 test users from the target audience.

- [ ] Test users identified (video producers, podcast producers, documentary filmmakers)
- [ ] Test brief prepared
- [ ] Sessions scheduled

### D14 — External Test Sessions
Run structured feedback sessions.

- [ ] Sessions completed
- [ ] Feedback documented and categorized
- [ ] Critical fixes identified and prioritized

### D15 — Access Model Decision
Confirm freemium, gated, or open access for launch.

- [ ] Model selected
- [ ] Technical requirements for chosen model documented

**Milestone:** v0.8 complete when external test sessions are done, feedback is synthesized, and access model is confirmed.

---

## Phase 5 — Launch Prep
**v0.9 · Target: September 5, 2026 · ~2 weeks**

### D16 — Critical Fixes from External Testing

- [ ] All P0 issues resolved
- [ ] P1 issues resolved or consciously deferred post-launch

### D17 — Website Integration
Embed NBE on EmbarkMedia.com.

- [ ] Dedicated page built
- [ ] Widget embedded and functional on live site
- [ ] Access model implemented

### D18 — Launch Copy
All user-facing text finalized.

- [ ] Page copy written and approved
- [ ] Input field labels and placeholder text finalized
- [ ] Output card labels finalized
- [ ] Error messages written

### D19 — Pre-Launch Checklist

- [ ] API cost monitoring confirmed
- [ ] Error logging confirmed
- [ ] Final QA pass on live site

**Milestone:** v0.9 complete when the workspace is live on EmbarkMedia.com, all launch copy is in place, and the pre-launch checklist is clear.

---

## Phase 6 — Launch
**v1.0 · September 12, 2026**

### D20 — Public Launch
Public launch of the Narrative Blueprint Engine on EmbarkMedia.com.

---

## Open Questions

These must be resolved before the gates noted.

| # | Question | Must resolve by |
|---|---|---|
| Q1 | NBE identity direction — visual identity and UI aesthetic | Before v0.7 |
| Q2 | Access model — freemium, gated (email capture), or open | Before v0.8 |
| Q3 | NBE Learning Curriculum location — standalone Drive subfolder or embedded in System Specification? | Before v0.7 |

---

*EmbarkMedia · Narrative Blueprint Engine · Roadmap v1.0 · June 25, 2026 · Confidential*
