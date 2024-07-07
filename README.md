# Angiogenesis Simulation Model

## Introduction

This repository contains a simulation model for angiogenesis, the process by which new blood vessels form from pre-existing vessels. Angiogenesis is crucial for various physiological processes, including wound healing and embryonic development, as well as pathological conditions like cancer. The model simulates angiogenesis under different conditions to study the effects of various treatments.

### Angiogenesis Overview

Angiogenesis involves several steps:
1. **Activation**: Endothelial cells become activated by angiogenic signals like VEGF (Vascular Endothelial Growth Factor).
2. **Migration**: Activated endothelial cells migrate towards the source of the angiogenic signal.
3. **Proliferation**: Endothelial cells proliferate to form new blood vessel structures.
4. **Maturation**: New blood vessels stabilize and mature.

#### Angiogenesis Process

1. **Initial Blood Vessel**
2. **Endothelial Cell Activation**
3. **Migration Towards Signal**
4. **Formation of New Blood Vessels**
### Simulations

This model includes five different simulations:
1. **Without Any Treatment/Original**: Baseline simulation of angiogenesis without any interventions.
2. **Stalk Cell Inhibiting Drug**: Simulation with a drug that inhibits the growth of stalk cells.
3. **T-Cell Integration**: Simulation incorporating the effects of immune cells, specifically T-cells, on angiogenesis.
4. ** Immune Integraton & Drug Therapy**: Combined simulation of immune cell effects and stalk cell inhibiting drug.
5. **Increasing VEGF Threshold**: Simulation with an increased VEGF threshold to prevent the conversion of endothelial cells to tip cells.

### Installation

To run this model, you need to install the `libMesh` library. Follow these steps to install `libMesh`:

1. **Download libMesh**:
   ```sh
   git clone https://github.com/libMesh/libmesh.git
   cd libmesh

   ./configure
   make
   make install

### Running Simulation
**Copy the Makefile:**
Copy the Makefile from libmesh/introduction/ex4 and paste it into your working directory:
 ```sh
 make run
