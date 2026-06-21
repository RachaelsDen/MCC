# MCC

MCC is the public scaffold repo for a planned Fabric port of the Minecolonies ecosystem.

## Current status

This repository is currently in setup mode.

- The outer `MCC` repo tracks public project scaffolding and documentation.
- The actual upstream Minecolonies source is currently kept in separate nested clones and a composite workspace setup, rather than being tracked directly in this outer repo.
- The current checked-out upstream code is still Forge-based. The Fabric port is planned work, not completed work.

## What this repo is for

This repo is meant to hold the public project shell while the workspace and migration approach are being established.

That includes things like:

- top-level project documentation
- repository hygiene
- future workspace setup for the port effort

## Workspace layout today

```text
MCC/
├── settings.gradle
├── README.md
├── ROADMAP.md
├── .gitignore
├── blockui/
├── domum-ornamentum/
├── minecolonies/
├── structurize/
├── Piston-Unlimited/
├── OperaPublicaCreator/
└── ldtteam-common/
```

## Direction

The long-term goal is a Fabric-native port of the Minecolonies ecosystem, starting from the right upstream branch and then evolving into a fuller workspace as that work begins.

Until then, this outer repo stays intentionally small and clean.

## Roadmap

See [ROADMAP.md](ROADMAP.md) for the public status and phased direction.

## License

This repository is licensed under [GPL-3.0](LICENSE).
