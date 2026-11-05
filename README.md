<!--
SPDX-FileCopyrightText: 2026 Numen Games S.L.
SPDX-License-Identifier: CC-BY-4.0
-->

# numinia-fleet

The Numinia worlds fleet: everything a server needs to host, monitor and update Numinia worlds.

**Today this repository is empty on purpose.** The recipe each machine installs still lives in
[numinia-assets](https://github.com/numengames/numinia-assets) under `open-worlds/machine/`, and
every machine follows that folder. Nothing here is read by any machine yet: a merge here changes
no world. The recipe moves here in its own step, decided by Pablo; `open-1` is not part of it.

## Licence

`AGPL-3.0-only` (`LICENSE`): the fleet is a program that runs a service, the core (PRI-005). The
terms are declared per file in the REUSE format (`LICENSES/`, `REUSE.toml`; STD-010): code and
configuration `AGPL-3.0-only`, explanatory texts `CC-BY-4.0`, the CLA files all rights reserved.
Orders and other data, when they come, are `CC0-1.0`, declared per path in `REUSE.toml`.

Every commit carries a DCO sign-off (`git commit -s`). The [CLA](CLA.md) is a **draft pending
legal review**: it is not yet offered to outside contributors, and until it is final only Numen
Games S.L. and its agents contribute ([CONTRIBUTING.md](CONTRIBUTING.md)). The names Numinia and
Numen Games are not licensed ([TRADEMARKS.md](TRADEMARKS.md)).
