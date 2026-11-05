# numinia-fleet

The Numinia worlds fleet: everything a server needs to host, monitor and update Numinia worlds.

**Today this repository is empty on purpose.** The recipe each machine installs still lives in
[numinia-assets](https://github.com/numengames/numinia-assets) under `open-worlds/machine/`, and
every machine follows that folder. Nothing here is read by any machine yet: a merge here changes
no world. The recipe moves here in its own step, decided by Pablo; `open-1` is not part of it.

## Licence

`AGPL-3.0-only` (`LICENSE`): the fleet is a program that runs a service, the core (PRI-005).
Contributors sign the [CLA](CLA.md) once, in their first pull request, and every commit carries a
DCO sign-off (`git commit -s`). Orders and other data, when they come, are `CC0-1.0`, declared
per path in `REUSE.toml`. The names Numinia and Numen Games are not licensed.
