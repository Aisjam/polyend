# Polyend Tracker

A little space for my experiments, tools and other bits and pieces for the **Polyend Tracker**.

With Polyend opening up the Tracker software, I wanted to make a place to share some of the things I create and discover while exploring what can be done with it.

## Polyend Tracker Community Edition

The open-source Tracker project is available here: [Polyend Tracker CE](https://github.com/polyend/tracker-ce).

## Effects and generators

**[Polyend Tracker Effects](https://github.com/Aisjam/polyendtracker_effects)** is included in this repository as a Git submodule at [`polyendtracker_effects/`](polyendtracker_effects).

It contains free `.ptfx` sample-editor generators, drum and percussion tools, effects and converters for the original Polyend Tracker with Community Edition firmware. Its README documents the controls, how each generator works and the conceptual sound-generation architecture.

**[Listen to the audio demo browser](https://aisjam.github.io/polyendtracker_Effects/)** to preview Synth, Drum and Percussion sounds before downloading.

The effects project is maintained in its own repository. The submodule points to a specific commit; updates to the effects repository do not automatically change the version pinned here.

### Clone with the effects submodule

```bash
git clone --recurse-submodules https://github.com/Aisjam/PolyendTracker.git
```

If you have already cloned the parent repository:

```bash
git submodule update --init --recursive
```

To bring the submodule up to the latest commit on its `main` branch, then save the new pinned version in this parent repository:

```bash
git submodule update --remote polyendtracker_effects
git add polyendtracker_effects
git commit -m "Update Polyend Tracker effects submodule"
```

## What's planned?

This repository is a home for ongoing Tracker experiments and resources, including:

- `.ptfx` patches, generators and sample-processing effects
- Small tools and utilities
- Notes, discoveries and useful resources
- Other experiments worth sharing

## Find me elsewhere

- [YouTube — Aisjam](https://www.youtube.com/@Aisjam)
- [GitHub — Aisjam](https://github.com/Aisjam)
- [Website — aisjam.com.au](https://aisjam.com.au)

---

*An independent collection of experiments and resources. Not affiliated with or endorsed by Polyend.*
