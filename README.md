# MEDIOEVO / Lutren

[Sponsor](https://github.com/sponsors/Lutren) · [Website](https://medioevo.space) · [Open source](https://medioevo.space/software.html#open-source) · [Store](https://lrgonzalez.gumroad.com)

## Español

Construyo MEDIOEVO: herramientas local-first para que agentes de IA trabajen
con evidencia, límites y continuidad antes de actuar.

La idea humana es simple. Cuando una IA toca código, archivos, cuentas o
decisiones reales, no basta con que responda bien. Tiene que dejar evidencia,
explicar qué va a hacer, separar lo seguro de lo riesgoso y permitir revisión
humana cuando corresponde.

La capa pública de MEDIOEVO libera software MIT y documentación práctica para
builders: ActionGate, logs de evidencia, handoffs entre sesiones, fichas
técnicas, checklists de publicación, curaduría de datos y demos sintéticas.

La capa de pago ahorra tiempo: plantillas, paquetes listos, soporte, briefings
y research curado. Las deconstrucciones observacionistas avanzadas,
Observacionismo Inverso y la Teoría de la Información MEDIOEVO pertenecen a
tiers altos como material revisado, no como dumps crudos.

Lo privado queda protegido: libros no publicados, videojuego/RPG/TCG, runtime
interno, OS, DUAT/GEODIA interno, prompts crudos, datasets reales, secretos,
calibración propietaria y fórmulas no liberadas.

## English

I build MEDIOEVO: local-first tools that help AI agents work with evidence,
boundaries and continuity before they act.

The human idea is simple. When an AI agent touches code, files, accounts or real
decisions, sounding smart is not enough. It should leave evidence, explain the
action, separate safe work from risky work and route sensitive steps to human
review.

MEDIOEVO's public layer releases MIT software and practical documentation for
builders: ActionGate, evidence logs, session handoffs, technical fichas, release
checklists, data curation workflows and synthetic demos.

The paid layer saves time: templates, packaged workflows, support, briefings and
curated research. Advanced Observacionismo deconstructions, inverse
Observacionismo and MEDIOEVO information theory belong in high tiers as reviewed
material, not raw dumps.

The private layer stays protected: unpublished books, the game/RPG/TCG,
internal runtime, OS, internal DUAT/GEODIA, raw prompts, real datasets, secrets,
proprietary calibration and unreleased formulas.

## Qué Hace / What It Does

MEDIOEVO turns agent work into something inspectable:

- evidence before action;
- source fichas before reuse;
- `APPROVE`, `REVIEW` or `BLOCK` gates before risky work;
- witness logs and handoffs across sessions;
- synthetic demos and falsifiers instead of inflated claims;
- public/private boundaries before release.

## Problemas Que Resuelve / Problems Solved

- Agentes con demasiados permisos pueden actuar demasiado rápido.
- Las conversaciones pierden contexto y no dejan continuidad verificable.
- Los repos mezclan código abierto, productos pagos, libros, secretos, vendors y
  material privado.
- Las demos de IA pueden convertirse en claims públicos más fuertes que la
  evidencia real.
- Los equipos necesitan saber qué hizo un agente antes de confiar en su output.

English:

- Agents with broad permissions can act too fast.
- Conversations lose context and do not leave verifiable continuity.
- Repositories mix open code, paid products, books, secrets, vendors and private
  material.
- AI demos can become public claims stronger than the evidence.
- Teams need to know what an agent did before they trust the output.

## Public Work

| line | what it does | typical use | access |
|---|---|---|---|
| [obsai-core](https://github.com/Lutren/obsai-core) | evidence, residue, claim and continuity primitives | agent memory, claim gates, fingerprints | MIT/public-safe |
| [residueos](https://github.com/Lutren/residueos) | local ActionGate with `APPROVE`, `REVIEW`, `BLOCK` | preflight before risky actions | MIT/public-safe |
| [observacionismo-gate](https://github.com/Lutren/observacionismo-gate) | small SDK for evidence, jamming, cost and approval gates | scripts, libraries and pipelines | MIT/public-safe |
| [obs-safe-integration-kit](https://github.com/Lutren/obs-safe-integration-kit) | envelopes, evidence store and dry-run wrappers | safer wrappers for agent tools | MIT/public-safe |
| [data-curation-observatory](https://github.com/Lutren/data-curation-observatory) | fichas, manifests and evidence labels | intake for messy folders and datasets | MIT/public-safe |
| [safe-exec](https://github.com/Lutren/safe-exec) | safe tool execution patterns for LLM agents | shell/tool review before execution | MIT/public-safe |
| [agent-handoff-protocol](https://github.com/Lutren/agent-handoff-protocol) | practical handoff workflow | multi-session coding agents | MIT/public-safe |
| [agent-release-checklist](https://github.com/Lutren/agent-release-checklist) | release checklist for agent-built projects | scans, proof and release discipline | MIT/public-safe |
| [duat-genesis](https://github.com/Lutren/duat-genesis) | synthetic observable simulation sandbox | falsifiers and low-claim demos | MIT/public-safe; internal DUAT retained |
| [duat-lab](https://github.com/Lutren/duat-lab) | sanitized lab skeleton for research workflows | synthetic reports and public-safe experiments | MIT/public-safe skeleton |
| [la-biblioteca-de-alejandria](https://github.com/Lutren/la-biblioteca-de-alejandria) | public index and claims boundary | map of public repos and whitepapers | MIT/public-safe |

## Tier Ladder

| layer | receives | does not include |
|---|---|---|
| Free / MIT | fundamental tools, schemas, validators, examples, docs and synthetic demos | private runtime, books, RPG/TCG, raw research, secrets |
| Gumroad | templates, checklists, workflow packs and time-saving artifacts | source vaults, internal prompts, account access |
| Sponsors | updates, public-safe demos, implementation notes and curated research | raw dumps, guaranteed outcomes, private datasets |
| Top tier | reviewed Observacionismo deconstructions, inverse Observacionismo, MEDIOEVO information theory, paper previews and transfer maps | complete raw formula, notebooks, proprietary calibration, internal OS/DUAT |
| Private | protected IP, books, game, runtime, OS, DUAT/GEODIA, prompts, datasets and calibration | automatic public or sponsor access |

MIT code is actually MIT once released. Tiers provide curation, support,
packaging, briefings and reviewed research; they do not restrict the rights of
already-published MIT code.

## Technical Surface

MEDIOEVO public tooling is built around a few repeatable objects:

- `ObservationEnvelope`: records what was observed, source, uncertainty, risk
  and evidence.
- `ActionGate`: routes proposed work to `APPROVE`, `REVIEW` or `BLOCK`.
- `EvidenceStore`: keeps traces, manifests, reports and proof artifacts.
- `WitnessLog`: makes agent work replayable across sessions.
- `Fichas`: classify sources before reuse, copying, publishing or deletion.
- `Falsifiers`: define what would downgrade or block a claim.
- `Claims Boundary`: prevents demos from becoming promises of science, safety
  or prediction.

Public repos use MIT only when they are target-clean: no secrets, no private
runtime, no raw research dumps, no full books, no RPG/TCG, no account state and
no guaranteed-outcome claims.

## Current Focus

- local-first agent safety gates;
- evidence stores and witness logs;
- handoff and release workflows for coding agents;
- public-safe curation of messy research/data folders;
- synthetic simulation and falsifier labs;
- curated Observacionismo research without exposing raw private IP.

## Public Boundary

I do not publish:

- the full internal orchestration layer;
- private prompts or account/session material;
- unpublished books or full editorial canon;
- RPG/TCG source, mechanics, lore, assets or bridge code;
- internal OS/runtime implementation;
- internal DUAT/GEODIA;
- raw Observacionismo, raw inverse Observacionismo or raw information theory;
- real private datasets, proprietary calibration or complete unreleased formulas.

I also do not claim guaranteed safety, solved hallucinations, social prediction,
diagnosis, proved consciousness or validated new physics.

The public promise is narrower and more useful:

```text
Evidence before action. Public-safe MIT foundations. Curated research by tiers. Core IP protected.
```

## Links

- [Sponsor](https://github.com/sponsors/Lutren)
- [Website](https://medioevo.space)
- [Software / Open Source](https://medioevo.space/software.html#open-source)
- [Store](https://lrgonzalez.gumroad.com)
- [GitHub Projects](https://github.com/Lutren?tab=repositories)
