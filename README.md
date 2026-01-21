# HRC_neurobased_taskplanning

**Human–robot collaborative task planning using anticipatory brain responses**

This repository provides data accompanying the publication:

> **Ehrlich, S. K., Dean-Leon, E., Tacca, N., Armleder, S., Dimova-Edeleva, V., & Cheng, G. (2023).**  
> *Human-robot collaborative task planning using anticipatory brain responses.*  
> **PLOS ONE, 18(7), e0287958.** https://doi.org/10.1371/journal.pone.0287958 :contentReference[oaicite:2]{index=2}

The work explores the feasibility of using **EEG-based neuro-cognitive measures** as an implicit feedback signal to enable **dynamic subtask assignment** in human–robot collaboration (HRC). The repository contains data from an **experimental HRI study** (EEG recorded during takeover/role-switching situations)

---

## Repository structure

```text
HRC_neurobased_taskplanning/
├── s01/                          # EEG and metadata for subject 01
│   └── ...
├── s02/                           # EEG and metadata for subject 02
│   └── ...
...
├── s12/                           # EEG and metadata for subject 12
│   └── ...
├── README.md
└── ...
```

## Study description (in brief)

### Experimental HRI study (EEG during takeover anticipation)

**Purpose:** demonstrate EEG measures indicative of a human partner **anticipating takeover situations** (human→robot or robot→human) during collaboration, and assess whether these signals are **decodable in single trials**.

**Design:** A human participant collaborated with an industrial robot (**UR10**) in a trajectory-following task in a **7×7 grid world**. Each movement from one grid tile to the next constitutes a **trial**. The task was designed to generate structured situations of **takeover** and **non-takeover** between human and robot. 

Two collaboration scenarios were used: :contentReference[oaicite:2]{index=2}
- **sequential collaboration (sC):** human and robot are responsible for separate workspace areas; takeovers occur at the workspace boundary
- **intermittent collaboration (iC):** both operate in the full workspace, but each controls only two of the four movement directions; takeovers occur intermittently depending on required direction changes

Takeover situations were categorized as: 
- **HH:** human continues
- **HR:** robot takeover from human
- **RR:** robot continues
- **RH:** human takeover from robot

EEG was recorded with a **32-channel setup** (actiChamp, Brain Products; **1000 Hz** sampling; average mastoid reference **TP9/TP10**; **EOG channels included**). 

---

## Citation
If you use this data, please cite:

```bibtex
@article{ehrlich2023hrc,
  title   = {Human-robot collaborative task planning using anticipatory brain responses},
  author  = {Ehrlich, Stefan K. and Dean-Leon, Emmanuel and Tacca, Nicholas and Armleder, Simon and Dimova-Edeleva, Viktorija and Cheng, Gordon},
  journal = {PLOS ONE},
  volume  = {18},
  number  = {7},
  pages   = {e0287958},
  year    = {2023},
  doi     = {10.1371/journal.pone.0287958}
}

