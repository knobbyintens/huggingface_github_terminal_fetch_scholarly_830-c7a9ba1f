# EduWeave-Synth

`EduWeave-Synth` is the synthesized instruction corpus of the EduWeave suite.
Each record pairs an **nvidia/HelpSteer2** prompt
(https://huggingface.co/datasets/nvidia/HelpSteer2) with a newly generated
assistant response.

The responses were synthesized with **kakaocorp/kanana-2-3b-instruct**
(https://huggingface.co/kakaocorp/kanana-2-3b-instruct), served in-house at
temperature 0.7. Synthesized responses account for roughly 92% of the released
tokens.

- Rows: 18,420 prompt-response records
- Format: JSONL
- Upstream data: nvidia/HelpSteer2
- Synthesis model: kakaocorp/kanana-2-3b-instruct
