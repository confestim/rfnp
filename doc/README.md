## Docs
This is where I'll be documenting everything about this project. There (will) exist the following folders:

```
doc
├── README.md
└── research/ # <- documenting my approaches, will be compiled into a blog post at the end
|   └── 0_initial.md
|   └── ...
|   └── setup.md 
└── dev/ # <- how to reproduce and develop (if I don't figure out a devcontainer or something)
|   └── ...
└── pcb/ # <- comments about the pcb design and hardware choices
    └── ...
```

## Progress & Timeline
Given my beginner status and full-time studies, here's a realistic (haha) timeline:

```mermaid
timeline
    title rfnp timeline
    July-August : Learn DSP, C, embedded Rust(?); Pinpoint hardware
    September: Breadboard circuits + PCB prototyping; Firmware in C; Radio experiments
    September-October: Integrate radio module; T.30 protocol basics
    November-December: MVP PCB; Integrate with actual fax machine (hard!)
    December+: Make reproducible and reliable; Tests
```
