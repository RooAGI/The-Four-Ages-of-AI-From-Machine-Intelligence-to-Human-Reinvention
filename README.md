# The Four Ages of AI: From Machine Intelligence to Human Reinvention

**An essay on AI architecture, parallel computing, agentic systems, scientific discovery and human purpose.**

**[Read the website](https://rooagi.github.io/The-Four-Ages-of-AI-From-Machine-Intelligence-to-Human-Reinvention/)**

## Chapters

1. [The Age of Alchemy](docs/age-1-alchemy.md) — learning architectures and the Transformer transition.
2. [The Age of Large Language Models](docs/age-2-llms.md) — scalable decoder-only models, block-oriented parallel execution, memory efficiency and reasoning trajectories.
3. [The Age of Agentic Computing](docs/age-3-agentic-computing.md) — personal and cloud agents, local AI, generative software, SaaS and trust.
4. [The Age of Scientific Renaissance](docs/age-4-scientific-renaissance.md) — future mathematics, physics, quantum technologies and scientific discovery.
5. [Human Reinvention](docs/human-reinvention.md) — a philosophical synthesis.

Read [the overview](docs/index.md) or [references](docs/references.md).

## Run locally

```bash
python3 -m pip install "mkdocs-material>=9.5,<10"
mkdocs serve
```

Then visit http://127.0.0.1:8000/.

## Publish

On a push to `main`, [GitHub Actions](.github/workflows/pages.yml) runs `mkdocs gh-deploy --force` and publishes the generated static site to the `gh-pages` branch.

**One-time setup:** Under **Settings → Pages → Build and deployment**, select **Deploy from a branch**, then choose **gh-pages / (root)**. Ensure workflow permissions allow writing repository contents.

The essay source is written in standard Markdown under `docs/`. The site's visual style is defined in `docs/stylesheets/extra.css`.

## Context

The four ages are an interpretive framework, not an inevitable sequence. Stages overlap; the scientific renaissance is explicitly speculative.
