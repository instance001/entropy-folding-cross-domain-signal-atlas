# Tool-Derived Candidate Signals

## Purpose

Separate candidate signals that come from existing tool outputs from signals that come directly from textual source materials.

## Material That Belongs Here

- existing output artifacts
- provenance of the tool that generated them
- explicit limits on what those outputs can support
- links to per-entry cards in `atlas/tool-derived/`

## Material That Must Not Go Here

- new tool runs
- new exploratory discovery
- interpretation beyond the tool's stated scope

## Likely Starting Sources

- `Cognitive_Crowbar/examples/generated_profile/introspective_notes.json`
- `Cognitive_Crowbar/examples/generated_profile/mechanisms.json`
- sample outputs inside `Symbound-Entropy-Architecture/CognitiveGenome-ApeTest-v0.1/examples/`

## Current Tool-Derived Body

The tool-derived tier is for existing artifacts and instruments that may surface candidate structure without being treated as direct validation.

Lead this lane with ApeTest.

Treat Cognitive Crowbar as supporting reflective extraction tooling.

Treat UAE/GVS as a tooling lens only, not as signal evidence.

### 1. ApeTest Cognitive Topology Snapshots

- Signal type: `tool-derived candidate`
- Secondary role: `tooling lens`
- Primary sources:
  - `Symbound-Entropy-Architecture/CognitiveGenome_ApeTest_v0.1.md`
  - `Symbound-Entropy-Architecture/CognitiveGenome-ApeTest-v0.1/README.md`
  - `Symbound-Entropy-Architecture/ape_test_v0_1.py`
  - `Symbound-Entropy-Architecture/ape_score_v0_1.py`
  - `Symbound-Entropy-Architecture/ape_score_llm_v0_1.py`
  - bundled sample profile and raw-response artifacts
- Why it matters:
  - ApeTest is the closest existing instrument in the source ecosystem to a cognitive-topology snapshot/profiling method.
  - It is relevant to the topology-fit side of the hypothesis without being treated as proof of the full mechanism.
- Boundary:
  - existing sample profiles remain tool-derived artifacts, not validation.

### 2. Cognitive Crowbar Example Outputs

- Signal type: `tool-derived candidate`
- Primary sources:
  - `Cognitive_Crowbar/examples/example_summary.md`
  - `Cognitive_Crowbar/examples/generated_profile/pattern_samples.json`
  - `Cognitive_Crowbar/examples/generated_profile/introspective_notes.json`
  - `Cognitive_Crowbar/examples/generated_profile/mechanisms.json`
- Why it matters:
  - it shows a reflective/pattern-extraction workflow already present in the ecosystem
- Boundary:
  - it remains illustrative and non-diagnostic

### Tooling-Lane Hierarchy

- ApeTest is the main cognitive-topology snapshot/profiling instrument in the current atlas.
- Cognitive Crowbar is a supporting reflective and pattern-extraction aid.
- UAE/GVS belongs in tooling appendix language as an analogy/vector sweep lens only.
