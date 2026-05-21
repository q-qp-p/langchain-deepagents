# Deep Agents Code Changelog

## [0.1.0](https://github.com/q-qp-p/langchain-deepagents/compare/deepagents-code==0.1.3...deepagents-code==0.1.0) (2026-05-21)


### Features

* **code:** `--timeout` flag for non-interactive ([#3351](https://github.com/q-qp-p/langchain-deepagents/issues/3351)) ([44e86ab](https://github.com/q-qp-p/langchain-deepagents/commit/44e86abbb1870f689dace8b1be6ed430d65e74c1))
* **code:** `/model` toggle for recommended-only list ([#3453](https://github.com/q-qp-p/langchain-deepagents/issues/3453)) ([c326b7e](https://github.com/q-qp-p/langchain-deepagents/commit/c326b7ec1b9940861175e0466ab4221f03e2bcba))
* **code:** `/restart` hidden slash command ([#3514](https://github.com/q-qp-p/langchain-deepagents/issues/3514)) ([74bdd36](https://github.com/q-qp-p/langchain-deepagents/commit/74bdd3688948d8369cdd978590f5a822eabeb12c))
* **code:** browser loopback OAuth callback for MCP auth ([#3467](https://github.com/q-qp-p/langchain-deepagents/issues/3467)) ([d83aa07](https://github.com/q-qp-p/langchain-deepagents/commit/d83aa07c818af35800f81d062a147fa45a47ace7))
* **code:** disable MCP servers from TUI ([#3501](https://github.com/q-qp-p/langchain-deepagents/issues/3501)) ([5725de8](https://github.com/q-qp-p/langchain-deepagents/commit/5725de857722dbca768a95bc6d97af5b838a11a9))
* **code:** float unauthorized MCP servers to top and prompt before reconnect ([#3493](https://github.com/q-qp-p/langchain-deepagents/issues/3493)) ([2d66580](https://github.com/q-qp-p/langchain-deepagents/commit/2d665804131961dfa7e2849248047deec818e4ef))
* **code:** in-TUI MCP OAuth login with auto-refresh ([#3469](https://github.com/q-qp-p/langchain-deepagents/issues/3469)) ([20e38b8](https://github.com/q-qp-p/langchain-deepagents/commit/20e38b8ebd8d9aa4697334432f7832a0a07aea3a))
* **code:** JS interpreter middleware via `langchain-quickjs` ([#3525](https://github.com/q-qp-p/langchain-deepagents/issues/3525)) ([f0ca89c](https://github.com/q-qp-p/langchain-deepagents/commit/f0ca89c962c22058194121526638bc2d29f546bd))
* **code:** MCP screen metadata ([#3349](https://github.com/q-qp-p/langchain-deepagents/issues/3349)) ([ce2f07e](https://github.com/q-qp-p/langchain-deepagents/commit/ce2f07e7211f22b3f44a1a232088b89a469a0a99))
* **code:** port from `libs/cli` ([#3388](https://github.com/q-qp-p/langchain-deepagents/issues/3388)) ([2ac7d41](https://github.com/q-qp-p/langchain-deepagents/commit/2ac7d4153398889100d5fd163ab4a122633862b5))
* **sdk:** v0.6 ([4db09ac](https://github.com/q-qp-p/langchain-deepagents/commit/4db09acba34b38521192b8f278723524be560779))


### Bug Fixes

* **code:** correct LangSmith sandbox working directory ([#3415](https://github.com/q-qp-p/langchain-deepagents/issues/3415)) ([b0e8d83](https://github.com/q-qp-p/langchain-deepagents/commit/b0e8d83f97a2a698268173a839000c84e8368324))
* **code:** drop sections from `system_prompt.md` already supplied by SDK middleware ([#3448](https://github.com/q-qp-p/langchain-deepagents/issues/3448)) ([9dbf2c2](https://github.com/q-qp-p/langchain-deepagents/commit/9dbf2c2f19e941e012d0c93418ef09fb56f30d6a))
* **code:** guard `fetch_url` against SSRF ([#3411](https://github.com/q-qp-p/langchain-deepagents/issues/3411)) ([54d8521](https://github.com/q-qp-p/langchain-deepagents/commit/54d8521976940dfe147ead4b56565360241335be))
* **code:** persist `_context_tokens` via `after_model` middleware ([#3496](https://github.com/q-qp-p/langchain-deepagents/issues/3496)) ([e2bb284](https://github.com/q-qp-p/langchain-deepagents/commit/e2bb284e506e0e49a05169fc6de01bdf42350267))
* **code:** recover initial session prompts from writes table ([#3535](https://github.com/q-qp-p/langchain-deepagents/issues/3535)) ([46b6f3f](https://github.com/q-qp-p/langchain-deepagents/commit/46b6f3f3e6ce880cd5ec9cf59622bb745d6ac2eb))
* **code:** refresh MCP OAuth tokens on restart ([#3509](https://github.com/q-qp-p/langchain-deepagents/issues/3509)) ([8919b3f](https://github.com/q-qp-p/langchain-deepagents/commit/8919b3f78c736108b5446b0ff8992a96d6965ac6))
* **code:** refresh status bar model after recovering from failed startup ([#3511](https://github.com/q-qp-p/langchain-deepagents/issues/3511)) ([c96f822](https://github.com/q-qp-p/langchain-deepagents/commit/c96f822de187431404d093b852c4a855d3ab8d30))
* **code:** rename stale usage commands ([#3460](https://github.com/q-qp-p/langchain-deepagents/issues/3460)) ([da43b7f](https://github.com/q-qp-p/langchain-deepagents/commit/da43b7f9d913e6190ff03c496a269faf08bbf182))
* **code:** show tool call previews during batched HITL approvals ([#3530](https://github.com/q-qp-p/langchain-deepagents/issues/3530)) ([84daa1a](https://github.com/q-qp-p/langchain-deepagents/commit/84daa1a2e27963a6d7694dc9278de83782b4a7b7))
* **code:** suppress interrupt-cleanup state writes from traces ([#3465](https://github.com/q-qp-p/langchain-deepagents/issues/3465)) ([319b24e](https://github.com/q-qp-p/langchain-deepagents/commit/319b24e6f179eaf56f105a6db683901c82fe95be))
* **code:** token-safe MCP OAuth login error handling and loopback edge cases ([#3492](https://github.com/q-qp-p/langchain-deepagents/issues/3492)) ([6199c71](https://github.com/q-qp-p/langchain-deepagents/commit/6199c71d6056a603a261b33b99ca3c421670ea4f))

## [0.1.3](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.2...deepagents-code==0.1.3) (2026-05-20)

### Features

* In-TUI MCP OAuth login with auto-refresh ([#3469](https://github.com/langchain-ai/deepagents/issues/3469)) ([20e38b8](https://github.com/langchain-ai/deepagents/commit/20e38b8ebd8d9aa4697334432f7832a0a07aea3a))
  * Float unauthorized MCP servers to top and prompt before reconnect ([#3493](https://github.com/langchain-ai/deepagents/issues/3493)) ([2d66580](https://github.com/langchain-ai/deepagents/commit/2d665804131961dfa7e2849248047deec818e4ef))
  * Disable MCP servers from TUI ([#3501](https://github.com/langchain-ai/deepagents/issues/3501)) ([5725de8](https://github.com/langchain-ai/deepagents/commit/5725de857722dbca768a95bc6d97af5b838a11a9))
* `/restart` hidden slash command ([#3514](https://github.com/langchain-ai/deepagents/issues/3514)) ([74bdd36](https://github.com/langchain-ai/deepagents/commit/74bdd3688948d8369cdd978590f5a822eabeb12c))

### Bug Fixes

* Persist `_context_tokens` via `after_model` middleware ([#3496](https://github.com/langchain-ai/deepagents/issues/3496)) ([e2bb284](https://github.com/langchain-ai/deepagents/commit/e2bb284e506e0e49a05169fc6de01bdf42350267))
* Refresh status bar model after recovering from failed startup ([#3511](https://github.com/langchain-ai/deepagents/issues/3511)) ([c96f822](https://github.com/langchain-ai/deepagents/commit/c96f822de187431404d093b852c4a855d3ab8d30))

## [0.1.2](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.1...deepagents-code==0.1.2) (2026-05-19)

### Features

* `/model` toggle for recommended-only list ([#3453](https://github.com/langchain-ai/deepagents/issues/3453)) ([c326b7e](https://github.com/langchain-ai/deepagents/commit/c326b7ec1b9940861175e0466ab4221f03e2bcba))
* `--timeout` flag for non-interactive ([#3351](https://github.com/langchain-ai/deepagents/issues/3351)) ([44e86ab](https://github.com/langchain-ai/deepagents/commit/44e86abbb1870f689dace8b1be6ed430d65e74c1))
* Browser loopback OAuth callback for MCP auth ([#3467](https://github.com/langchain-ai/deepagents/issues/3467)) ([d83aa07](https://github.com/langchain-ai/deepagents/commit/d83aa07c818af35800f81d062a147fa45a47ace7))
* MCP screen metadata ([#3349](https://github.com/langchain-ai/deepagents/issues/3349)) ([ce2f07e](https://github.com/langchain-ai/deepagents/commit/ce2f07e7211f22b3f44a1a232088b89a469a0a99))

### Bug Fixes

* Drop sections from `system_prompt.md` already supplied by SDK middleware ([#3448](https://github.com/langchain-ai/deepagents/issues/3448)) ([9dbf2c2](https://github.com/langchain-ai/deepagents/commit/9dbf2c2f19e941e012d0c93418ef09fb56f30d6a))
* Rename stale usage commands ([#3460](https://github.com/langchain-ai/deepagents/issues/3460)) ([da43b7f](https://github.com/langchain-ai/deepagents/commit/da43b7f9d913e6190ff03c496a269faf08bbf182))
* Suppress interrupt-cleanup state writes from traces ([#3465](https://github.com/langchain-ai/deepagents/issues/3465)) ([319b24e](https://github.com/langchain-ai/deepagents/commit/319b24e6f179eaf56f105a6db683901c82fe95be))

## [0.1.1](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.1.0...deepagents-code==0.1.1) (2026-05-16)

### Bug Fixes

* Correct LangSmith sandbox working directory ([#3415](https://github.com/langchain-ai/deepagents/issues/3415)) ([b0e8d83](https://github.com/langchain-ai/deepagents/commit/b0e8d83f97a2a698268173a839000c84e8368324))
* Guard `fetch_url` against SSRF ([#3411](https://github.com/langchain-ai/deepagents/issues/3411)) ([54d8521](https://github.com/langchain-ai/deepagents/commit/54d8521976940dfe147ead4b56565360241335be))

## [0.1.0](https://github.com/langchain-ai/deepagents/compare/deepagents-code==0.0.1...deepagents-code==0.1.0) (2026-05-12)

Hello world! Ported from `libs/cli`.

---

`deepagents-code` was forked from `deepagents-cli` at v0.1.0 (2026-05-12).
For history prior to the fork, see [the `deepagents-cli` changelog](https://github.com/langchain-ai/deepagents/blob/main/libs/cli/CHANGELOG.md).
