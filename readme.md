# Various analog and modular synthesizer projects are collected here

### Mostly Eurorack, but also some custom large format modular stuff, and some fixed architecture synths.

---

### Each project will typically have all the files needed to open and edit the schematic/pcb using KiCad, and a collection of files needed to build the circuitboards
This usually includes:
- an interactive HTML BOM
- a pdf copy of the schematic
- gerbers
- a few projects include assembly files for using the low cost smd assembly service from JLCpcb.
    - usually a few parts are not included, either because they were not in stock or they were extended parts at the time I ordered boards.
    - if using this service, double check that all the parts are actually in stock, and check for extended parts.

---

### `Readme` files are sprinkled around liberally
- the project readme files typically indicate whether it is safe to order pcbs or not, and the general state of the project.
- if a project doesn't explicitly say that boards are tested and safe to order, errors are possible. 
    - I've built at least one of just about everything here, and nothing catastrophic is going to happen if you make one, but some projects are more well developed than others

---

Some projects have been updated to KiCad 6, but many are still using KiCad 5. If a project is made using KiCad 6, the folder containing the KiCad project will be called `kicad_6_docs`. Projects still using KiCad 5 will have a folder simply called `kicad_docs`. I will probably update projects now and again, but old and well tested projects may not be updated to KiCad 6 anytime soon.

Older projects may not follow the exact directory structure described above, especially regarding custom symbol and footprint libraries. The general idea is pretty consistent across projects though, and there shouldn't be any major surprises.

---