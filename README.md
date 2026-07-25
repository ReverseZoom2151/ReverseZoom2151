<div align="center">

# T I B E R I U &nbsp;&nbsp; T O C A

**The orchestration layer for the agentic economy.**

Romanian solo founder · [General Liquidity](https://generalliquidity.com), an applied product and research lab

[generalliquidity.com](https://generalliquidity.com) · [gordoncli.com](https://gordoncli.com) · [@tiberiu_toca](https://x.com/tiberiu_toca) · [LinkedIn](https://www.linkedin.com/in/tiberiu-aurelian-toca-80b88a200/)

</div>

<br />

> I am interested in ambitious, slightly illegible ideas before they become consensus.

<br />

## The thesis

The economy is being handed to actors that are not people.

[Fabric's essay on the machine economy](https://www.fabric.vc/writing/the-machine-economy) gets the shape right: compute, models, and programmable money converging until agents become economic actors rather than tools, transacting at machine speed against counterparties they have never met. Its sharpest observation is that once capability is abundant, "the scarce and therefore precious resource is no longer capability, it becomes direction."

Where I part company is on what follows. The essay treats the question of who directs the flywheel as political and philosophical rather than an engineering one. It is both, and the engineering half is the part nobody is building. Direction has to live somewhere concrete: delegated, bounded, priced, and refusable. In practice that somewhere is a single API call, made by an agent, at machine speed, with no human watching it happen. Governance that cannot be enforced inside that call is not governance. It is a policy document.

So the thing I am building is the **API for the machine economy**: one governed surface over payment, commerce, identity, and provenance, where an agent states an intent and a mandate decides whether it becomes an action. The agent never holds the settle primitive. Every enforcement decision is falsifiable after the fact, by anyone, offline.

Everything below is that thesis at a different altitude. General Liquidity is the surface. Gordon is what it looks like pointed at capital markets, where the consequences arrive fastest and the excuses are cheapest.

<br />

## General Liquidity

An applied product and research lab for the machine economy. Capital markets are the first vertical, not the mission.

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

**The model proposes. The harness disposes.** The same architecture carried into other domains where a confident wrong answer is worse than no answer. Each one puts a machine-checkable verifier between the model and the artifact, so the thing you are handed has already survived a check that does not care how fluent it sounded.

| | | |
|:--|:--|:--|
| **[Theoremata](https://github.com/ReverseZoom2151/theoremata)** | The AI mathematician that breaks conjectures before proving them, discharges every step inside a proof assistant, and hands you a proof you can check yourself. | `Rust` |
| **[HarnessCAD](https://github.com/ReverseZoom2151/harnesscad)** | The verifier-first text-to-CAD agent harness, with a computer-using agent for 3D CAD generation in real GUIs, and Parts-Driven Development. | `Python` |
| **[HarnessBIM](https://github.com/ReverseZoom2151/harnessbim)** | The first fully-native, open-source text-to-BIM agentic harness: natural language to standards-compliant IFC, with no proprietary authoring tool in the loop. | `Python` |

<br />

## About

I am a philosopher-builder and contrarian at heart: part technologist, part systems thinker, part obsessive founder. I studied Computer Science with Innovation at the University of Bristol (MEng), then spent the last year or so moving through hacker houses, founder fellowships, and builder ecosystems across Europe, the US, and MENA.

Coming from Eastern Europe shaped my relationship with grit, resourcefulness, and perseverance, and made me comfortable operating outside obvious institutions. That is mostly an advantage. The ideas worth working on are rarely the ones with an established venue, and the people who find them early are usually the ones who did not need permission to start.

What holds my attention: AI agents, financial infrastructure, coordination systems, and tools that expand human agency. I build with intellectual grounding first, because a product with a thesis behind it can survive being early, and one without a thesis can only survive being right.

<br />

<div align="center">

**Building the orchestration layer for the agentic economy.**

[generalliquidity.com](https://generalliquidity.com) · [@tiberiu_toca](https://x.com/tiberiu_toca) · [LinkedIn](https://www.linkedin.com/in/tiberiu-aurelian-toca-80b88a200/)

</div>
