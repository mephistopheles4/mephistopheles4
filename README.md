<p align="center">
  <img src="pact-head.svg" width="888" alt="The Pact. Instrument of agreement No. 0004. Terms under which machines work beside me." />
</p>

**This agreement** is made between **Ayman Diab**, tech lead in Montréal, hereinafter *the Architect*, and **any agent that runs under these terms**, hereinafter *the Familiar*.

The Architect supplies intent. The Familiar supplies labour. Both parties agree to the articles below, which are enforced by CI rather than by honour, and drawn in Schedule A.

---

### Article I · Intent

The Architect states **what** and **why**. The Familiar proposes **how**. Nothing ships that a human did not intend.

### Article II · Main

The Familiar **shall not** push to `main`. Every change arrives as a pull request. Force-push and deletion are forbidden, and no party, the Architect included, holds a bypass.

### Article III · Gates

No pull request merges until the `gates` check passes: install, tests, build, and the editorial rules. A green gate is the only signature the branch accepts.

### Article IV · Provenance

Every third-party action is pinned to a commit SHA. A tag can be moved after it is signed; a hash cannot.

### Article V · The Grimoire

The Familiar may draw on the spells in [**grimoire**](https://github.com/mephistopheles4/grimoire). It shall cast them wisely.

### Article VI · Consideration

In return, the Architect provides a clear brief, a working test suite, and forgiveness for the first draft.

---

### Schedule A · The drawing

<p align="center">
  <img src="sheet.svg" width="888" alt="Engineering drawing MEPH-0004, 'Humans as architects of intent', drawn by A. Diab in Montréal and checked by CI. It shows how a change reaches main: intent, then agent, pull request, gates, main. A red dashed line from agent straight to main is crossed out as forbidden." />
</p>

### Schedule B · The drawing set

The sheets published at [aymandiab.com](https://aymandiab.com), in the site's order.

| Sheet | Work | Description |
| :-: | --- | --- |
| W-01 | [The Engineering Workflow Playbook](https://aymandiab.com/work/engineering-workflow-playbook/) | A company-wide operating philosophy for how humans and AI build together, and the six-stage engineering pilot that tests it, authored and run against real delivery on SquadBox. |
| W-02 | [AI-Robustness Gates](https://aymandiab.com/work/ai-robustness-gates/) | Making a codebase’s architectural invariants mechanically enforceable in CI, because human reviewer vigilance does not scale with AI-authored code. |
| W-03 | [Threat-Modeling AI Workflows](https://aymandiab.com/work/threat-modeling-ai-workflows/) | A multi-framework threat model for AI-augmented engineering workflows, so an agent-adoption decision could be made on mapped risk instead of vendor marketing. |
| W-04 | [Safe Mode: Unblocking an Org-Wide Agentic Rollout](https://aymandiab.com/work/safe-mode-rollout/) | A bilingual, arcade-style security game that replaced the policy page nobody reads. Built to satisfy the guardrail requirement gating an organization-wide rollout of agentic AI tooling. |

**In production.** The same thesis, with a 400-tonne haul truck on the other end of it.

| Sheet | Work | Description |
| :-: | --- | --- |
| W-05 | [NIC: Agents That Recommend, Humans Who Decide](https://aymandiab.com/work/nic-industrial-agents/) | Tech lead on a production AI-agent platform for ArcelorMittal Canada’s mining operations, where every agent recommends and every decision stays human. |

**Pre-flight.** Pilots run a checklist before every flight, and not because they have forgotten how to fly. [Run the Pre-Flight Checklist](https://aymandiab.com/pre-flight/): twelve questions, about four minutes, no email.

### Schedule C · Works

| Item | Work | Description |
| :-: | --- | --- |
| 1 | [grimoire](https://github.com/mephistopheles4/grimoire) | A spellbook of agent skills. The one balloon 4 refers to. |
| 2 | [stacks](https://github.com/mephistopheles4/stacks) | Local-first reading tracker. Obsidian vault in, 3D bookshelf out. MIT. The reference implementation behind W-02, published at [stacks.aymandiab.com](https://stacks.aymandiab.com). |
| 3 | [aymandiab.com](https://aymandiab.com) | The full drawing set, indexed in Schedule B. |

<p align="center">
  <img src="pact-sign.svg" width="888" alt="Signed: the Architect, /s/ Ayman Diab. Countersigned: the Familiar, on every commit, as Co-Authored-By." />
</p>
