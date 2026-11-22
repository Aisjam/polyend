# Aisjam × Polyend — Tools & Experiments

An independent home for my projects, sounds, tools and experiments across the **Polyend Play**, **Polyend Tracker** and **Polyend Synth** families.

I use this repository as a central directory for things I make and discover while experimenting with Polyend instruments. Individual projects can live in their own repositories, with their own releases, documentation and development histories.

> **Independent community project.** This repository is not affiliated with, sponsored by or endorsed by Polyend. Product names are used to identify compatible devices.

## Explore by instrument

| Instrument | What's here | Status |
| --- | --- | --- |
| **Polyend Play / Play+** | Patterns, sample packs, performance experiments, MIDI tools and workflows | Space reserved for future projects |
| **Polyend Tracker family** | Community Edition effects, sample generators, sound design, instrument resources and utilities | [Explore Tracker resources](#polyend-tracker) |
| **Polyend Synth** | Patch design, preset collections, synthesis experiments and utilities | Space reserved for future projects |

Compatibility varies between hardware models and firmware versions. Each project should document its tested devices and any requirements; resources listed here are not automatically compatible with every model in a family.

## Polyend Play / Play+

A space for exploring sequencing, generative patterns and performance-oriented workflows on Play and Play+.

Potential resources include:
- Pattern and project collections
- Sample kits and curated sound packs
- MIDI, sequencing and arrangement tools
- Performance techniques and workflow experiments

**Projects:** Nothing published here yet. Links will be added as individual projects are released.

## Polyend Tracker

Tools and sounds for the Tracker family, with particular attention to the original Tracker running **Community Edition (CE)**. Check each linked project's requirements before using it on other Tracker models.

### Community Edition

The open-source community firmware project is available at [Polyend Tracker CE](https://github.com/polyend/tracker-ce).

### Effects, generators and sample tools

**[Polyend Tracker Effects](https://github.com/Aisjam/polyendtracker_effects)** contains free `.ptfx` sample-editor generators, drum and percussion tools, effects and converters designed for the original Polyend Tracker with compatible Community Edition firmware.

- [Browse the effects source and documentation](https://github.com/Aisjam/polyendtracker_effects)
- [Listen to the audio demo browser](https://aisjam.github.io/polyendtracker_Effects/)
- [Open the included submodule](polyendtracker_effects/)

The effects project is independently maintained and is included here as a Git submodule pinned to a particular commit. Updating the effects repository does **not** automatically update this repository's pinned version.

### More Tracker resources

This section can grow to include instrument presets, sample packs, project templates, conversion utilities, tutorials and experiments. Each resource will have its own compatibility notes.

## Polyend Synth

A dedicated area for Synth sound design and experimentation.

Potential resources include:
- Synth patches and preset banks
- Sound design demonstrations and technique guides
- MIDI integration and performance utilities
- Original audio experiments and downloadable resources

**Projects:** Nothing published here yet. Tested compatibility and download links will be added when resources become available.

## Repository organisation

This repository is a **hub**, not a requirement that every project be maintained in one codebase.

- **README.md** — directory of projects grouped by instrument
- **polyendtracker_effects/** — existing Tracker effects Git submodule
- **Separate repositories** — source code, releases and documentation for individual projects
- **Future directories or submodules** — only when useful for a specific published project

Use descriptive project names and document supported hardware, firmware, installation instructions, licence and any caveats in each project's own README.

### Clone the existing Tracker effects submodule

```bash
git clone --recurse-submodules https://github.com/Aisjam/polyendtracker.git
```

If you've already cloned this repository:

```bash
git submodule update --init --recursive
```

To update the pinned effects revision from its remote `main` branch:

```bash
git submodule update --remote polyendtracker_effects
git add polyendtracker_effects
git commit -m "Update Polyend Tracker effects submodule"
```

## Find me elsewhere

- [YouTube — Aisjam](https://www.youtube.com/@Aisjam)
- [GitHub — Aisjam](https://github.com/Aisjam)
- [Website — aisjam.com.au](https://aisjam.com.au)

---

*Made independently by Aisjam for music making, creative experimentation and sharing with the community.*
