<div align="center">

# T I B E R I U &nbsp;&nbsp; T O C A

**Founder, [General Liquidity](https://generalliquidity.com)**

An applied research lab for the machine economy

[generalliquidity.com](https://generalliquidity.com) · [gordoncli.com](https://gordoncli.com) · [@tiberiu_toca](https://x.com/tiberiu_toca) · [LinkedIn](https://www.linkedin.com/in/tiberiu-aurelian-toca-80b88a200/)

</div>

<br />

> Taste is a form of engineering. It decides what you refuse to build.

<br />

## About

I am Romanian, and I build the machine economy's missing layer out of [General Liquidity](https://generalliquidity.com).

**Disposition**

- Philosopher-builder
- Soulful aristocrat
- Contrarian
- Techno-vitalist
- Systems thinker

**Education, fellowships, and residencies**

- **MEng, Computer Science with Innovation**, [University of Bristol](https://www.bristol.ac.uk/)
- **Fellow**, [Oxford Cambridge Fellowship](https://joinocf.com) · [Brightdale](https://www.brightdale.co/)
- **Serial hacker house resident**, [Augmentation Lab](https://augmentationlab.org/) · [Arrayah City](https://arrayah.city/) · [The Residency](https://www.livetheresidency.com/) · [Harvard St](https://harvardst.co/)
- Building across Europe, the US, and MENA

Coming from Eastern Europe shaped my relationship with grit, resourcefulness, and perseverance, and left me comfortable operating outside obvious institutions. That is mostly an advantage. The work worth doing rarely has an established venue, and the people who find it early are usually the ones who did not wait to be invited. Rooms full of people building things nobody asked for yet are the closest thing I have found to a native habitat.

<br />

## The thesis

The economy is being handed to actors that are not people.

[Fabric's essay on the machine economy](https://www.fabric.vc/writing/the-machine-economy) gets the shape right: compute, models, and programmable money converging until agents become economic actors rather than tools, transacting at machine speed against counterparties they have never met. Its sharpest observation is that once capability is abundant, "the scarce and therefore precious resource is no longer capability, it becomes direction."

Where I part company is on what follows. The essay treats the question of who directs the flywheel as political and philosophical rather than an engineering one. It is both, and the engineering half is the part nobody is building. Direction has to live somewhere concrete: delegated, bounded, priced, and refusable. In practice that somewhere is a single API call, made by an agent, at machine speed, with no human watching it happen. Governance that cannot be enforced inside that call is not governance. It is a policy document.

So the thing I am building is the **API for the machine economy**: one governed surface over payment, commerce, identity, and provenance, where an agent states an intent and a mandate decides whether it becomes an action. The agent never holds the settle primitive. Every enforcement decision is falsifiable after the fact, by anyone, offline.

Everything below is that thesis at a different altitude. General Liquidity is the surface. Gordon is what it looks like pointed at capital markets, where the consequences arrive fastest and the excuses are cheapest.

<br />

## General Liquidity

An applied research lab for the machine economy. Capital markets are the first vertical, not the mission.

| | | |
|:--|:--|:--|
| **[The API](https://github.com/general-liquidity/general-liquidity-openapi)** | One governed surface over payment, commerce, identity, and provenance, with a mandate and a deny-first gate in the call path that agents cannot route around. SDKs in [TypeScript](https://github.com/general-liquidity/general-liquidity-typescript), [Python](https://github.com/general-liquidity/general-liquidity-python), [Rust](https://github.com/general-liquidity/general-liquidity-rust), [Go](https://github.com/general-liquidity/general-liquidity-go), plus an [MCP server](https://github.com/general-liquidity/general-liquidity-mcp) and a [CLI](https://github.com/general-liquidity/general-liquidity-cli). | `OpenAPI 3.1` |
| **[Gordon](https://github.com/general-liquidity/gordon)** | A plan-first AI trading agent bringing institutional-grade discipline to retail traders. You state intent in plain language, it drafts a structured plan, you approve it, and a deny-first risk harness gates every order before it reaches a venue. | `TypeScript` `MIT` |
| **[SharpeBench](https://github.com/general-liquidity/sharpebench)** | A luck-robust benchmark for AI trading agents. Ranks risk-adjusted skill that survives deflation, not raw return. Ships as a [CLI](https://www.npmjs.com/package/@general-liquidity/sharpebench) and an [MCP server](https://www.npmjs.com/package/@general-liquidity/sharpebench-mcp). | `Rust` `npm` |
| **[SharpeArena](https://github.com/general-liquidity/sharpearena)** | A leak-free, point-in-time reinforcement-learning environment for trading agents, and the language-agnostic contract they speak. | `Python` |

```console
$ npm install -g @general-liquidity/gordon
```

<br />

## Verifier-first harnesses

**The model proposes. The harness disposes.** The same architecture carried into other domains where a confident wrong answer is worse than no answer. Each one puts a machine-checkable verifier between the model and the artifact, so what you are handed has already survived a check that does not care how fluent it sounded.

| | | |
|:--|:--|:--|
| **[Theoremata](https://github.com/ReverseZoom2151/theoremata)** | The AI mathematician that breaks conjectures before proving them, discharges every step inside a proof assistant, and hands you a proof you can check yourself. | `Rust` |
| **[HarnessCAD](https://github.com/ReverseZoom2151/harnesscad)** | The verifier-first text-to-CAD agent harness, with a computer-using agent for 3D CAD generation in real GUIs, and Parts-Driven Development. | `Python` |
| **[HarnessBIM](https://github.com/ReverseZoom2151/harnessbim)** | The first fully-native, open-source text-to-BIM agentic harness: natural language to standards-compliant IFC, with no proprietary authoring tool in the loop. | `Python` |

<br />

<div align="center">

[generalliquidity.com](https://generalliquidity.com) · [@tiberiu_toca](https://x.com/tiberiu_toca) · [LinkedIn](https://www.linkedin.com/in/tiberiu-aurelian-toca-80b88a200/)

</div>
