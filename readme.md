# My various modular synthesizer projects are collected here

### Mostly Eurorack, but I have done some weird custom format stuff as well.

---

### The directories for each project roughly follow this structure:

```
├── project_name
│   ├── construction_docs
│   │   ├── project_name_BOM.html
│   │   ├── project_name_schematic.pdf
│   │   └── gerbers
│   │       ├── project_name_gerbers.zip
│   │       └── various gerber files
│   ├── kicad_[/6]_docs
│   │   ├── all KiCad project files needed to open the project in KiCad
│   │   ├── custom_footprints
│   │   │   └── any non-standard footprints used by the project
│   │   └── custom_symbols
│   │       └── any non-standard symbols used by the project
│   └── pics
│       ├── pcb_front.png
│       └── pcb_rear.png
└── readme.md
```

### The `construction_docs` directory contains everything you need to build the physical pcb.
- an interactive HTML BOM
- a pdf copy of the schematic
- gerbers
- a few projects include assembly files for using the low cost smd assembly service from JLCpcb.

    - usually a few parts are not included, either because they were not in stock or they were extended parts at the time I ordered boards.

    - if using this service, double check that all the parts are actually in stock, and check for extended parts.

---

### The `kicad_[/6]_docs` directory contains everything you need to edit the schematic and pcb layout using KiCad.
- KiCad project files
- optional custom symbol libraries
- optional custom footprint libraries

---
### The `pics` directory just contains a few rendered images of the pcb so you can get an idea of what it looks like.

---

### `Readme` files are sprinkled around liberally
- the project readme files typically indicate whether it is safe to order pcbs or not, and the general state of the project.
- if a project doesn't explicitly say that boards are tested and safe to order, errors are likely.
- additionally, if there are no gerbers in the `construction_docs/gerbers` directory, the project is unlikely to be well tested.

---

Some projects have been updated to KiCad 6, but many are still using KiCad 5. If a project is made using KiCad 6, the folder containing the KiCad project will be called `kicad_6_docs`. Projects still using KiCad 5 will have a folder simply called `kicad_docs`. I will probably update projects now and again, but old and well tested projects may not be updated to KiCad 6 anytime soon.

Older projects may not follow the exact directory structure described above, especially regarding custom symbol and footprint libraries. The general idea is pretty consistent across projects though, and there shouldn't be any major surprises.

---