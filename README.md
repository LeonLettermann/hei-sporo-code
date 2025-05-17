# hei-sporo-code

**Overview repository for an upcoming publication on *Plasmodium* sporozoite movement.**

This repository includes example code for STED microscopy analysis and serves as an entry point to related projects.

## Related Repositories

- 🔬 [hei-sporo-code-tracking](https://github.com/LeonLettermann/hei-sporo-code-tracking)  
  → Code for image analysis, tracking, and traction force analysis.

- 🌀 [hei-sporo-code-simulation](https://github.com/LeonLettermann/hei-sporo-code-simulation)  
  → Code for simulating sporozoite gliding motility.

📦 **Data for running and testing the code** can be found at the [associated dataset repository](https://doi.org/10.11588/DATA/4YBYXE).

---

## Repository Structure

```text
hei-sporo-code/
├── STED/
│   └── AnalyzeSTED.ipynb  # Angular profile generation and microtubule position inference
└── environment.yml        # Conda environment file
                           # ⚠️ JAX version might need to be adapted to your system
