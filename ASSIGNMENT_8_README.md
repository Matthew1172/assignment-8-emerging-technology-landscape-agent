# Assignment 8 — Emerging Technology Landscape Agent

The working specialist is in [agents/landscape_agent](agents/landscape_agent/README.md). Start with the [Agent Record](agents/landscape_agent/records/agent_record.md), [evidence register](agents/landscape_agent/records/sources.md), and [test comparison](agents/landscape_agent/records/test_comparison.md). The primary and contrast inputs, saved structured analyses, and reproducible prompt packets are included. These analyses use a hypothetical organization and need Matthew's review before submission.

The frozen course scaffold is retained. Run the following from this directory:

```sh
python3 tools/check_frozen_core.py
python3 tools/validate_response.py agents/landscape_agent/responses/primary_response.json
python3 tools/validate_response.py agents/landscape_agent/responses/contrast_1_response.json
python3 tools/build_prompt.py --agent agents/landscape_agent --case agents/landscape_agent/cases/primary.json
```

The generated packets can be pasted into ChatGPT, and the returned JSON saved and validated with the included tool. See the Agent Record for the distinction between the recorded Codex analyses and independent interactive testing. No API account is needed.
