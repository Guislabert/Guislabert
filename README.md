## Guislabert

Building agent tooling and Skills on open models. Founder of [CauriumX](https://github.com/CauriumX).

I work on one problem from two ends: **can a model actually execute a method, or does it only sound like it did?** On the product side that means Skills that encode a methodology with hard rules; on the research side it means a benchmark that can tell the two apart.

### What I am building

| project | what it is |
|---|---|
| [**molu** 墨炉](https://github.com/Guislabert/molu) · Apache-2.0 | 11-module Chinese content-production engine as Agent Skills, distilled from 899 articles into 16,227 verified content units |
| [**molu-bench**](https://github.com/Guislabert/molu-bench) · Apache-2.0 | eval harness for doctrine following: 20-item dev set, pre-registered protocol, itemized GPU-hour bill instead of a hand-waved number |
| [**magpie-cloudflare-workers-ai**](https://github.com/Guislabert/magpie-cloudflare-workers-ai) · Apache-2.0 | provider plugin for OpenCode/magpie: Cloudflare Workers AI with live models.dev discovery and quota windows |
| [**readme-harness**](https://github.com/Guislabert/readme-harness) · Apache-2.0 | version-train discipline for READMEs: badges, changelog and package.json cannot drift apart |
| [**jevhub**](https://github.com/Guislabert/jevhub) | launch discovery for the Jev ecosystem, static Astro, zero paid APIs |

### Caurium

Endpoint monitoring, built evidence-first: a public site that only claims what is verified, and a private preview that runs before it promises.

- [caurium.tech](https://caurium.tech) — what exists today, stated plainly
- [caurium-site](https://github.com/Guislabert/caurium-site) — the static site, evidence-first by construction

### Current work

Fine-tuning and evaluating open models (Qwen3, Llama) on curated Chinese content doctrine — does LoRA on 16k units beat a good prompt, does the gain survive held-out tasks, and which hours on a GPU are actually earning their keep. Every number lands in [molu-bench](https://github.com/Guislabert/molu-bench), including the ones that go against the hypothesis.

### Working rules

- Publish the protocol before the numbers, and publish the disconfirming result with the same font size.
- A benchmark with an LLM judge as the primary scorer measures the judge.
- Licensing is a claim: if the licence forbids commercial use, the repo is source-available, and I say so instead of writing "open source".
- Compute asks get itemized. 70 hours of work does not need an 800-hour grant.

<sub>中文：做 agent 工具链与 Skill，底座是开源模型。产品侧把方法论写成带硬规则的 Skill，研究侧用 benchmark 判断模型是"真在执行方法"还是"只是像"。写过的东西按上面两张表排；算力只要算得出来，就不报虚数。</sub>

---

<p align="center"><sub><a href="https://caurium.tech">caurium.tech</a> · <a href="mailto:210294947+Guislabert@users.noreply.github.com">210294947+Guislabert@users.noreply.github.com</a></sub></p>