# Roadmap

This document tracks the public direction of the outer `MCC` repository.

## Current status

The public repo is still in setup mode.

- The outer repository is a public scaffold and workspace shell.
- The actual upstream mod sources currently live in nested local clones and a composite Gradle workspace.
- The checked-out upstream Minecolonies code is still Forge-based today.
- The Fabric port is planned work, not completed work.

## Goals

### Phase A

Build a Fabric-native port of the Minecolonies ecosystem on Minecraft 1.21.1.

Current expected scope:

- Minecolonies
- BlockUI
- Structurize
- Domum Ornamentum
- Piston-Unlimited

This phase is expected to start from the upstream `release/1.21` line rather than the older Forge 1.20.1 branch that is currently checked out in the local nested clone.

### Phase B

Upgrade the Fabric port forward to Minecraft 26.2 after the 1.21.1 Fabric baseline is working.

## Workspace direction

The outer repo is moving toward a clearer workspace shell for the port effort.

Today that means:

- keeping public repository docs and workflow files here
- keeping upstream source clones separate
- using a composite Gradle workspace while the larger port plan takes shape

## Non-goals for this repo right now

- pretending the Fabric port already exists
- committing local-only planning files
- mixing this outer scaffold with the full upstream source trees

## License

This public scaffold repo is licensed under GPL-3.0. See [LICENSE](LICENSE).
