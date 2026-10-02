# Claude Token Efficient

This repository is presented as guidance for reducing Claude token use. The previous README claimed 60–90% savings, measured efficiency methods, profiles, install/configuration workflows, tests, benchmarks, and case studies. Those claims were not supported by the checked profile and guide paths, so the savings figure and instructions are removed pending evidence.

## Verification state

| Item | Result |
|---|---|
| Root README | Present |
| Root LICENSE | MIT license present |
| Claimed `TOKEN-SAVING.md`, `RULES-IN-PROMPT.md`, `caveman.md`, `profiles/README.md` | Not found at checked paths |
| Claimed docs banner/index, package manifest, security policy | Not found at checked paths |
| Savings or benchmark results | Not verified |

Repository search was unavailable, so this is not a full tree audit. Token use depends on the model, prompt, task, settings, and output quality. Any savings claim needs a reproducible comparison with quality checks and a stated baseline.

## Safe evaluation

For a prompt or context change, compare representative tasks with and without the change. Record input/output tokens, latency, cost where applicable, and task quality. Keep the baseline and avoid removing information needed for correctness.

See [CONTENT_REVIEW.md](CONTENT_REVIEW.md) for paths checked and claims removed.

See [SECURITY.md](SECURITY.md) for prompt data and evaluation guidance.
