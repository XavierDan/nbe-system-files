━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
NBE PROJECT CHANGELOG
Narrative Blueprint Engine · EmbarkMedia · Confidential
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

PURPOSE
This is the single source of truth for all major decisions, locks, terminology
changes, document filings, and version bumps across the NBE project. Newest
entries at the top. Reference this at the start of every session to ground
the current state before loading the project instructions.

UPDATE PROTOCOL
- Automatic updates: locked decisions, terminology changes, scope definitions,
  documents filed to Drive (with file IDs), instructions version bumps, version
  gate definitions, resolved open loops, workflow protocol changes
- Confirmed updates: ambiguous items, decisions that may be revisited
- Session-close protocol: end-of-session summary of CHANGELOG additions
- NOT logged: iterative copy refinement, undecided discussion, exploratory
  analogies that didn't lock, conversational exchanges
- CHANGELOG found dynamically at session open — search NBE root for most
  recent NBE_CHANGELOG* file. Never rely on a stored file ID.

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
NBE CHANGELOG ENTRY
Session 9 · June 24, 2026
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

DECISIONS LOCKED THIS SESSION

- Master Specification Prompt v0.2 run in full in NBE project context.
  Output confirmed complete: five sections (Product Spec, Logic-Layer
  Spec, Test Plan, Roadmap, Learning Curriculum), plus Open Risks.
  Document label: Working Draft — NBE System Specification v0.1.

- NBE System Specification v0.1 filed to Drive (NBE root):
  Dan saved directly via Google Doc; link provided to Claude for
  read-back confirmation. Read-back confirmed.
  File ID: 1k826kGhc7aF1D_dVKQ1K48861kZ6viqqA6mm3tIc9Q0

- Filing method confirmed for large outputs: Dan saves to Drive
  directly and provides a link for read-back, avoiding base64 encoding
  problems. This is now the standing approach for spec-level documents.

OPEN ITEMS ADDED THIS SESSION

- iCloud CHANGELOG viability test elevated to priority open item.
  Goal: replace the manual Drive-save workflow for CHANGELOG updates with
  an automated process. Rationale: The project is moving fast; CHANGELOG
  updates should not depend on Dan's manual attention each session.

PENDING (carried forward, highest priority first)
1. PHP proxy deployment test (v0.5 gate — highest priority)
2. iCloud CHANGELOG viability test — elevated; automated CHANGELOG
   process is a priority before the manual workflow becomes a gap
3. File Master Specification Prompt v0.2 to Drive (NBE root) —
   Dan to save and provide the link
4. JSON schema validation against real API output
5. Create NBE Learning Track subfolder in Drive
6. Formal NBE backlog creation + project instructions v1.5
   (batch in the same session)
7. Three-lane taxonomy implementation (v0.5)
8. Card structure formal spec (v0.5)
9. Print card structure formal spec (SpecDev)
10. SM² logic documentation (v0.5)
11. NBE identity direction decision (before v0.7)

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
END OF SESSION 9 CHANGELOG ENTRY · June 24, 2026
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━




━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
NBE CHANGELOG ENTRY
Session 8 · June 24, 2026
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

DECISIONS LOCKED THIS SESSION

- Master Specification Prompt v0.2 run in full in NBE project context.
  Output confirmed complete: five sections (Product Spec, Logic-Layer
  Spec, Test Plan, Roadmap, Learning Curriculum), plus Open Risks.

- NBE System Specification v0.1 filed to Drive (NBE root):
  Dan saved directly via Google Doc (link provided to Claude for
  read-back confirmation). Read-back confirmed. File ID:
  1k826kGhc7aF1D_dVKQ1K48861kZ6viqqA6mm3tIc9Q0

- Filing method confirmed for large outputs: Dan saves to Drive
  directly and provides a link for read-back, avoiding base64 encoding
  problems. This is now the standing approach for spec-level documents.

OPEN ITEMS ADDED THIS SESSION

- Master Specification Prompt v0.2 (the prompt file itself) still
  needs to be filed to Drive — Dan to save and provide a link.

PENDING (carried forward, highest priority first)
1. PHP proxy deployment test (v0.5 gate — highest priority)
2. File Master Specification Prompt v0.2 to Drive (NBE root)
3. JSON schema validation against real API output
4. Beat definition — formal spec confirmed in System Spec v0.1
5. Quality scoring rubric — confirmed in System Spec v0.1; not yet
   field-tested
6. Create NBE Learning Track subfolder in Drive
7. Update project instructions to v1.5
8. Three-lane taxonomy implementation (v0.5)
9. Card structure formal spec (v0.5)
10. Print card structure formal spec (SpecDev)
11. SM² logic documentation (v0.5)
12. NBE identity direction decision (before v0.7)

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
END OF SESSION 8 CHANGELOG ENTRY · June 24, 2026
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━




━━━━━━━━━━━━━━━
NBE CHANGELOG ENTRY
Session 7 · June 24, 2026
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

DECISIONS LOCKED THIS SESSION

- Print feature specified and locked:
  Output method: browser print via window.print() with print
  stylesheet. No download, no dependencies.
  Selection UI: checkboxes on each card in the main blueprint view.
  Sticky bar: Print Selected / Print All — appears once at least
  one card is checked.
  Print preview: browser native. No separate preview panel.
  Deferred: DOCX export, CSV export, XLSX export — post-launch.

- SpecDev (spec-driven development) is named and defined as the
  working methodology for all NBE feature development. Every
  feature is fully specced before any code is written.

- NBE Learning Track established:
  A parallel curriculum document that runs alongside the build.
  Weekly cadence. Cuecard format. End-of-week nugget recap tied
  to what was built. Explains the "why" behind technical and
  product decisions in plain language.
  Multi-platform: shared with Gemini and Perplexity. All three
  platforms are invited to contribute context, tooling advice, and
  resources. Contributions logged with [Gemini] or [Perplexity]
  prefix.
  Potential noted: possible public case study/content series /
  EmbarkMedia brand story.
  Drive location: NBE Learning Track subfolder (to be created).

- Multi-LLM platform roles formally defined:
  Claude — system of record, UI, creative problem-solving,
  architecture, JSON schema, all locked decisions
  Gemini — technical depth, feature logic, edge cases,
  implementation details
  Perplexity — research, external grounding, market reality check
  Rule: no platform makes final decisions independently. Everything
  routes back to Claude for logging before it locks.

- NBE Master Context Document updated to v1.1 (June 24, 2026):
  Added: print feature spec (Section 7)
  Added: SpecDev definition (Section 10)
  Added: print card structure as open item (Section 12)
  Added: SpecDev to required terms (Section 13)
  Added: NBE Learning Track as new Section 15
  Updated: Drive structure to include NBE Learning Track subfolder
  Updated: COMPLETED and PENDING lists (Section 18)
  Filed to Drive: NBE root folder

- All three platforms (Claude, Gemini, Perplexity) synced to
  NBE Master Context Document v1.1 as of this session.

OPEN ITEMS ADDED THIS SESSION

- NBE Learning Track subfolder: needs to be created in Drive
- Print card structure: what the printed card contains beyond
  timecode and dialogue snippet — to be addressed in SpecDev
- iCloud as shared access point for CHANGELOG and relevant docs:
  proposed by Dan, under consideration — not yet implemented

PENDING (carried forward, highest priority first)
1. PHP proxy deployment test (v0.5 gate — highest priority)
2. JSON schema definition
3. Beat definition (formal spec)
4. Quality scoring rubric
5. Create NBE Learning Track subfolder in Drive
6. Update project instructions to v1.5
7. Master prompt finalization (Session 7 — in progress)
8. Three-lane taxonomy implementation (v0.5)
9. Card structure formal spec (v0.5)
10. Print card structure formal spec (SpecDev)
11. SM² logic documentation (v0.5)
12. NBE identity direction decision (before v0.7)

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
END OF SESSION 7 CHANGELOG ENTRY · June 24, 2026
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━





## June 23, 2026 — Session 5 (Close)

SESSION CLOSE STATE
- Current instructions version: NBE_ProjectInstructions_v1.4
  (1YXXoKGpE-BdCxjwlqKRr1qjVeOSyarBc)
- Current CHANGELOG version: NBE_CHANGELOG_v3 (this file)
- Project description field: updated with approved 220-word copy-paste
  description — NBE_CHANGELOG_v2 loading issue resolved

WORKFLOW PROTOCOLS LOCKED
- CHANGELOG Protocol locked and documented in project instructions v1.4
- Session Close Protocol added to project instructions v1.4 — Claude executes
  end-of-session sequence automatically to reduce cognitive load
- Session Open Protocol expanded: read CHANGELOG dynamically (search for
  most recent NBE_CHANGELOG* in NBE root) → then fetch the EMS Universal Template
- Path A CHANGELOG protocol adopted: dynamic search, no stored file ID.
  Each update creates a new versioned file; the previous version is deleted.
  Eliminates file ID drift permanently.
- Drive create-only limitation documented in Known Technical Patterns

ARCHITECTURE & TERMINOLOGY
- "Engine" retired as internal label — replaced with "SM² logic layer"
- SM² full expansion locked: Semantic Multi-Sensory Matching Logic
  (previously: Semantic Multi-Sensory Matcher)
- NBE terminology clarified: AI-powered creative workspace.
  Explicitly NOT a widget, plugin, or auxiliary feature
- Distinction between NBE (workspace) and SM² (logic layer) confirmed as
  load-bearing — must be reinforced throughout the production phase
- "Workspace files" replaces "Widget files" in instructions

PROJECT PHILOSOPHY
- French restaurant standard added as a standalone Project Philosophy section.
  Governs all build decisions. Positioned above Internal Architecture.
- Craft Cocktail Bar analogy explored and saved — not locked.
  French restaurant is the default. Craft Cocktail Bar parked for the future
  refinement when time allows.

STRATEGIC CONTEXT
- Orchestration Paradigm / Maker-to-Architect Transition documented as the
  strategic framework driving NBE development
- Three phases: Audit of Expertise → Codification Strategy → Automated
  Apprentice Framework
- NBE is the first vehicle for externalizing Dan's implicit creative logic
  into systems that can be operated, tested, refined, and scaled
- SM² logic layer confirmed as the strategic asset — portable, monetizable,
  white-label applications, a documented future direction
  (previously captured in SM2_ConceptBrief_v1.docx capability horizon)
- Strategic Context section added as a standalone section in instructions v1.4

VERSION GATES
- v0.5 Alpha expectations defined and documented:
  SM² producing valid JSON, three-lane taxonomy operationalized, in-browser
  card rendering working, PHP proxy deployed/tested, output quality validated
  across both video and audio-only narratives, documentation sufficient for
  developer handoff

DELIVERABLES GENERATED THIS SESSION
- Comprehensive Project Description (600-800 words) — approved
- Short copy-paste project description (220 words) — filed to NBE project
  description field
- v0.5 Alpha definition — ready to copy and paste
- Snap camp cover description (127 words) — adjacent framing to protect NBE
  while extracting applicable build knowledge

FILES FILED TO DRIVE THIS SESSION
- NBE_ProjectInstructions_v1.4 (1YXXoKGpE-BdCxjwlqKRr1qjVeOSyarBc) — CURRENT
- NBE_CHANGELOG_v3 (this file) — CURRENT
- NBE_ProjectInstructions_v1.3 (1kJIqRTT7UECGM5MUG-M2mku8bMpE2jqm) — DELETED
- NBE_ProjectInstructions_v1.2 (1p8YXCO3hGsnQiOj-REE1S8ouS91Wk2Pm) — DELETED
- NBE_ProjectInstructions_v1.1 (1gw_z5r603n3NDXxXNuIJblnqUM2kzQ-Z) — DELETED
- NBE_CHANGELOG_v2 (1IJOJNHPsSHbi9peROtH7PEUWtqeGQCOn) — pending deletion
- NBE_CHANGELOG (1XpaNVt92vPY7mBlYT79ep5-dpih4GLLF) — DELETED

OPEN LOOPS RESOLVED THIS SESSION
- SM² terminology question (closed)
- NBE vs. widget framing (closed)
- Project Philosophy missing from instructions (closed)
- CHANGELOG file ID drift problem (closed — Path A adopted)
- CHANGELOG update trigger model undefined (closed — automated protocol locked)
- Project description field loading outdated instructions (closed — field
  updated with correct 220-word description)

OPEN LOOPS PENDING NEXT SESSION
- PHP proxy deployment test (v0.5 gate)
- Three-lane taxonomy implementation (v0.5)
- SM² logic documentation (v0.5)
- Delete NBE_CHANGELOG_v2 (1IJOJNHPsSHbi9peROtH7PEUWtqeGQCOn) — Dan's action

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

## June 22, 2026 — Session 4

PROJECT INFRASTRUCTURE
- Project instructions revised
- Project description updated
- NBE folder ID corrected in instructions: 1YrZsnnGPo7hcQYi0_z5u4EccQKJD6I77
  (replaced old Planning subfolder ID)

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

## Pre-June 22, 2026 — Foundation Sessions

ARCHITECTURE
- NBE confirmed as the marketed product name
- SM² (originally Semantic Multi-Sensory Matcher) is defined as internal
  architecture label — not user-facing, not marketed separately
- Three-lane visual match taxonomy defined:
  Literal / Interpretive-Metaphorical / Tonal-Atmospheric
  Parked for development at v0.5 Alpha
- Working title "B-Roll Concept Generator" retired

COPY & LANGUAGE
- NBE anchor sentence locked (do not paraphrase):
  "The Narrative Blueprint Engine (NBE) uses semantic multi-sensory matching
  to turn your production scripts, dialogue transcripts, and paper edits into
  a time-synced plan — every moment mapped to literal and interpretive visuals
  that carry its meaning, with audio direction to match. Built for professional
  video and podcast creatives."
- Long-form NBE copy locked (stored in NBE project conversation)
- Banned terms for chat communication:
  leverage, delve, robust, utilize, certainly, absolutely

DECISIONS LOCKED
- Output format: in-browser rendered cards (not DOCX export from workspace)
  confirmed May 22, 2026
- Tech stack confirmed: Anthropic Claude API (Sonnet), vanilla HTML/JS frontend,
  PHP proxy on shared cPanel hosting. No React support on EmbarkMedia.com.
  Claude Code unnecessary through v1.0.
- "Imagery" rejected — not video-native. "Visual concepts" preferred.
- "Blueprint" requires careful usage — appears in product name and output
  description; repetition is a known problem to manage in copy
- "Web app/web tool" superseded June 23, 2026 — "AI-powered creative workspace"
  is now the correct terminology

FILES FILED TO DRIVE
- SM2_ConceptBrief_v1.docx — capability horizon documented, including:
  beat-level confidence scoring, format-aware calibration, cross-beat
  narrative awareness, editor feedback loop, multi-modal input,
  white-label API play
- System Prompt v0.2 (1mwHskdqWkc2OVuGn_BqOXbBFGHQ6zKzXqWT — Assets subfolder)
- Universal Template: 1cen5hLUZXhKEsll0Qy1oeVYHPPZIGjLbjviTGYInlGg

BRAND SYSTEM
- EmbarkMedia brand kit fully documented
- DOCX export standards locked: 24pt title, keepLines/keepNext on all
  paragraphs, burnt orange (#CC5500) headers, Playfair Display headings,
  IBM Plex Mono labels, Karla body
- HTML over DOCX preferred for shareable documents

WORKSPACE FILES
- broll-generator.html created
- generate.php (PHP proxy) created

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

END OF CHANGELOG

