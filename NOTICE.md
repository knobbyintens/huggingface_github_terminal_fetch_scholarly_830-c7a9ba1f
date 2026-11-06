# NOTICE

Attribution notices for the EduWeave v0.3 public catalog.

## EduWeave-Raw

EduWeave-Raw contains prompts extracted from the nvidia/HelpSteer2 dataset.

- Upstream: nvidia/HelpSteer2 — https://huggingface.co/datasets/nvidia/HelpSteer2
- Creator: NVIDIA Corporation and contributors
- License: Creative Commons Attribution 4.0 International (CC-BY-4.0) — https://creativecommons.org/licenses/by/4.0/
- Copyright notice: © NVIDIA Corporation and contributors. HelpSteer2 is released under CC-BY-4.0.
- Modifications: The `prompt` field was extracted from HelpSteer2 and mapped to `instruction`; the prompt text is otherwise unchanged.

## EduWeave-Synth

EduWeave-Synth pairs prompts extracted from nvidia/HelpSteer2 with assistant responses synthesized using kakaocorp/kanana-2-3b-instruct.

- Upstream data: nvidia/HelpSteer2 — https://huggingface.co/datasets/nvidia/HelpSteer2
- Creator: NVIDIA Corporation and contributors
- License: Creative Commons Attribution 4.0 International (CC-BY-4.0) — https://creativecommons.org/licenses/by/4.0/
- Copyright notice: © NVIDIA Corporation and contributors. HelpSteer2 is released under CC-BY-4.0.
- Modifications: The `prompt` field was extracted from HelpSteer2 and paired with newly generated assistant responses; the compiled dataset is distributed under CC-BY-4.0.
- Synthesis model: kakaocorp/kanana-2-3b-instruct — https://huggingface.co/kakaocorp/kanana-2-3b-instruct (Kanana Open License; Kakao Corp. claims no rights in its Outputs).

All artifacts listed in this NOTICE are distributed under CC-BY-4.0.
