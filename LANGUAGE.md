---
name: dreamcore-domain-and-evaluation-glossary
hostname: local-workspace
description: Authoritative domain vocabulary and strict evaluation parameters for the Dreamcore interactive HTML experience.
---

# Domain Vocabulary (Dreamcore System)

- **Dream Stratum (`Stratum`)**: One of the three canonical liminal environments (`sunday_meadow`, `warm_poolroom`, `twilight_staircase`), bundling its bespoke visual plate, sky/grid palette, Web Audio harmonic voicing, and spatial hotspot coordinates.
- **Hotspot Portal (`Portal`)**: Normalized `(x%, y%)` interactive anchor overlaid on the active Dream Stratum viewport that reveals a poetic memory fragment and triggers a pitched harmonic chime when inspected.
- **Seraphic Watcher (`Watcher`)**: The interactive six-winged SVG eye motif whose iris tracks pointer coordinates via critically bounded interpolation and toggles lucid/dream-blur focus state on click.
- **Memory Dialog (`FloatingWindow`)**: Viewport-clamped draggable Y2K/liminal dialog window (`liminal_viewer.exe`, `memories.idx`, `reminder.msg`) managed with deterministic z-index focus ordering.
- **Tape Pad Synth (`DreamAudioEngine`)**: User-gesture-activated Web Audio synthesizer generating tape-warbled (`0.18 Hz` pitch wow) warm low-pass polyphonic chords and feedback-delay chimes without external audio file dependencies.

---

# Evaluation Parameters

## {errors}
- Explicit failure states or structural invariant breaches surfaced during the planning, execution, or verification of a component.
- **Qualifiers:** Stack traces, syntax errors, unhandled exceptions, compilation failures, non-zero exit codes, fatal timeouts, severe warnings that halt execution, silent exception suppression or arbitrary default fallbacks (`RULE[user_global]`), disconnected dead-code helpers, broken image assets (`naturalWidth === 0`), or unfulfilled specification requirements.

## {correctness}
- The precise execution and contract fidelity of a component within its operational context, verifying that it performs its designated task without logical, mathematical, or state-transition flaws and without silent fallbacks, even if no explicit `{errors}` are thrown.
- **Qualifiers:** All strata transitions update visual plates, canvas palettes, hotspots, and audio voicings atomically; draggable windows remain strictly clamped inside viewport bounds; loops and animations use pre-allocated state without per-frame leaks.

## {functionality}
- The broader, global objective or business logic the component is meant to achieve within the larger integrated system under real-world runtime conditions.
- **Qualifiers:** Renders an authentic, immersive, interactive Dreamcore HTML experience that loads cleanly over both `http://` and `file://` protocols at smooth interactive framerates with zero broken assets or console errors.

## {correct required outputs}
- The exact, literal expected state and observable system behavior after a component executes successfully in its real runtime context. This must be objectively measurable.
- **Qualifiers:** Verified `200 OK` / complete DOM load in live headless Chromium via Playwright, `0` console/page errors, all `<img>` plates verified with `complete === true && naturalWidth > 0`, interactive stratum switching, hotspot inspection, window dragging, and Web Audio synthesis verified via live DOM/JS telemetry.

## {sufficient}
- The state of documentation, planning, or verification where zero ambiguity remains, architectural root causes and surrounding system dependencies are accounted for, physical and runtime feasibility is empirically grounded, and the coding assistant can implement and verify the end-to-end `{functionality}` without guessing, inventing workarounds, or relying on synthetic mocks.

## {insufficient}
- The state of documentation, planning, or verification where critical context is missing, ambiguous, physically unfeasible, or restricted to superficial symptoms.
