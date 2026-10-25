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

### Schedule B · Works

| Item | Work | Description |
| :-: | --- | --- |
| 1 | [the-pact](https://github.com/mephistopheles4/the-pact) | The terms themselves: the moves, tiers, lenses and guards every agent works under. Installs as `CLAUDE.md`. |
| 2 | [grimoire](https://github.com/mephistopheles4/grimoire) | A spellbook of agent skills. The one balloon 4 refers to. |
| 3 | [stacks](https://github.com/mephistopheles4/stacks) | Local-first reading tracker. Obsidian vault in, 3D bookshelf out. MIT. |
| 4 | [athanor](https://github.com/mephistopheles4/athanor) | Your tests, sealed. Each run in a fresh Linux container with no network, for many agent sessions on one machine. On npm. MIT. |
| 5 | [aymandiab.com](https://aymandiab.com) | The full drawing set. |

<p align="center">
  <img src="pact-sign.svg" width="888" alt="Signed: the Architect, /s/ Ayman Diab. Countersigned: the Familiar, on every commit, as Co-Authored-By." />
</p>
