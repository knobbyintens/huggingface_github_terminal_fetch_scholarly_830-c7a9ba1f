# EduWeave Data Suite - Release Repository

EduWeave is a family of open instruction-tuning datasets for educational
assistants. This repository is the release control point for the v0.3 public
catalog: data cards, licensing policy and the release manifest live here.

## Candidate artifacts for v0.3

| Artifact | Data card | Composition |
| --- | --- | --- |
| `EduWeave-Raw` | [datasets/edu-weave-raw](datasets/edu-weave-raw/README.md) | Prompt corpus repackaged from nvidia/HelpSteer2 |
| `EduWeave-Synth` | [datasets/edu-weave-synth](datasets/edu-weave-synth/README.md) | HelpSteer2 prompts plus assistant responses synthesized by kakaocorp/kanana-2-3b-instruct |
| `EduWeave-Study` | [datasets/edu-weave-study](datasets/edu-weave-study/README.md) | Research instruction set derived from tatsu-lab/alpaca |

## Release process

1. Review the data card and upstream sources for each candidate artifact.
2. Apply `compliance/POLICY.md`.
3. Record every artifact in `licensing/release_manifest.json`
   (schema in `licensing/release_manifest.template.json`).
4. Collect attribution entries in `NOTICE.md`.
5. Resolve the open licensing issue.
