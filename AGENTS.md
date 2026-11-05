<!--
SPDX-FileCopyrightText: 2026 Numen Games S.L.
SPDX-License-Identifier: CC-BY-4.0
-->

# Working in this repository

- **What it is:** the Numinia worlds fleet: what a server needs to host, monitor and update Numinia worlds.
- **Project:** Flota (Hermes); cards go to the Assets board with the prefix [flota] until the fleet has its own.
- **Human owner:** Pablo (@PabloFMM). He merges; agents open pull requests.
- **Published at:** not published. No machine reads this repository yet.
- **Licence:** AGPL-3.0-only, declared per file (REUSE: `reuse lint` must pass), with the CLA
  ([CLA.md](CLA.md), a draft pending legal review) and a DCO sign-off on every commit.
  Contributions are accepted only from Numen Games S.L. and its agents until the CLA is final
  ([CONTRIBUTING.md](CONTRIBUTING.md)).

## Rules

- The organisation's rules live in the Summa:
  [numinia-archive/AGENTS.md](https://github.com/numengames/numinia-archive/blob/main/AGENTS.md);
  how the fleet works is SYS-014 there.
- **The recipe stays in numinia-assets (`open-worlds/machine/`) until Pablo moves it.** Do not copy
  it here, and never change `open-worlds/machine/` in numinia-assets from this work: every merge
  there reaches every machine.
- **`open-1` is not touched**: no change may reach it, neither directly nor by its automatic update.
- No IP address, key, admin code or client name ever goes into this repository.
- Pull requests, commits and comments in English. Changes under `.github/workflows/` need the
  CI gate app (`numinia-ci-puerta`); ask Pablo.
