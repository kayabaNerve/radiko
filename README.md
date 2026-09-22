# Radiko

Radiko ("root", in Esperanto) is a supply chain for reproducible Monero,
Cuprate, and Serai binaries. It intends to be bootstrapped from source as much
as possible, omitting binary blobs, enabling its inspection and certainty over
how a binary was built.

### Architecture

Radiko's architecture is explicitly defined, updated, and tracked via
Radiko Architecture Documents (RADs). Please see [RAD-001](./RADs/001.md) for
more information.

### History

Radiko forked from [StageX](https://codeberg.org/stagex/stagex) due to concerns
with its quality assurance, yet appreciation for how accessible it made a
toolchain which was _largely_ bootstrapped. Due to the desires by the Monero,
Cuprate, and Serai communities for bootstrapped builds, there was sufficient
justification for the effort to maintain a fork
_explicitly scoped to these three projects_. Support for additional
packages/features is an explicit non-goal to ensure maintenance is feasible.
