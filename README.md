# 🌍 Living World Simulation (C++)

## Project Description

"Living World" is a simulation of a simple ecosystem where different organisms coexist: wolves, sheep, grass, dandelions, and fly agarics (poisonous mushrooms). Each organism exhibits unique behaviors:

- **Feeding:** Predators hunt prey, while plants are consumed by herbivores.  
- **Reproduction:** Organisms reproduce to create new lifeforms.  
- **Death:** Lack of food or old age leads to death.

The simulation takes place on a two-dimensional grid, where each organism occupies a position and makes decisions during each turn.

---

## Key Features

### 1. Organisms and Their Traits
- **Wolf:** Predator that hunts sheep.  
- **Sheep:** Herbivore that eats grass and dandelions.  
- **Grass:** Passive plant that spreads slowly.  
- **Dandelion:** Fast-reproducing plant.  
- **Toadstool:** Poisonous mushroom that kills animals that consume it.

### 2. World Mechanics
- **Reproduction:** Organisms can reproduce when their health is sufficient.  
- **Aging:** Each organism has a limited lifespan measured in turns.

### 3. Interface
- **Text Mode:** Displays the current state of the world in the console.  
- **SDL Visualization:** Provides a graphical representation of the simulation.

---

## How to Run

Build and start the simulation using the following command:

```bash
./world_app
