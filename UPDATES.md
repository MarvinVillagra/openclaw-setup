# Model Update History

## 2026-10-03

- Refreshed the active OpenAI/ChatGPT selection list from the main OpenClaw agent: GPT-5.4, GPT-5.4 Mini, GPT-5.5, GPT-5.6 Luna, GPT-5.6 Sol, GPT-5.6 Terra, and GPT-6 Luna.
- Recorded the active OpenClaw selection aliases for GPT-5.4, GPT-5.4 Mini, GPT-5.6 Sol, and GPT-5.6 Luna.
- Excluded GPT-5.6 because the configured-model listing marked it unavailable, and removed model IDs not present in the active allowlist.

## 2026-10-02

- Set `openai/gpt-6-luna` as the primary text model.
- Recorded the configured text fallback chain: Kimi K3, Nemotron 3 Super 120B, GPT-5.6 Luna, then GPT-6 Luna.
- Recorded GPT-5.6 Terra as the visual-understanding model, with GPT-5.6 Luna as fallback.
- Updated tool-level image, audio, and video routing to the current configured model IDs.
- Removed non-model repository material; this repository now tracks models and model routing only.
