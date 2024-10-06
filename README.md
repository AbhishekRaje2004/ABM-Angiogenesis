# Angiogenesis Simulation Model


This model includes five different simulations:
1. **Without Any Treatment/Original**: Baseline simulation of angiogenesis without any interventions.
2. **Stalk Cell Inhibiting Drug**: Simulation with a drug that inhibits the growth of stalk cells.
3. **T-Cell Integration**: Simulation incorporating the effects of immune cells, specifically T-cells, on angiogenesis.
4. **Immune Integraton & Drug Therapy**: Combined simulation of immune cell effects and stalk cell inhibiting drug.
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
