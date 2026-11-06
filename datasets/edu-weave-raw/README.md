# EduWeave-Raw

`EduWeave-Raw` is the raw prompt corpus of the EduWeave suite. It contains the
`prompt` field from a filtered subset of **nvidia/HelpSteer2**
(https://huggingface.co/datasets/nvidia/HelpSteer2). The text is repackaged
without modification; no model-generated content is added.

- Rows: 18,420 prompt records
- Format: JSONL
- Upstream: nvidia/HelpSteer2
- Field map: `prompt` -> `instruction`
