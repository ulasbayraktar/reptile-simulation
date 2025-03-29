# Reptile Simulation

This project is a **dynamic creature simulation** built using JavaScript and HTML5 Canvas. It creates a visually engaging and interactive experience where procedurally generated creatures (e.g., reptiles, tentacles, or squid-like entities) move and respond to user input in real time.

## Features

- **Procedural Creature Generation**:
  - Creatures are composed of interconnected segments, forming spines, limbs, and tails.
  - Supports various configurations like reptiles, tentacles, and squid-like creatures.

- **Interactive Movement**:
  - Creatures follow the user's mouse movements dynamically.
  - Limbs and tails move naturally using physics-based calculations.

- **Customizable Configurations**:
  - Multiple setup functions (`setupSimple`, `setupTentacle`, `setupArm`, `setupTestSquid`, `createReptile`) allow for different creature designs.
  - Parameters like size, number of legs, and tail length can be adjusted.

- **Physics Simulation**:
  - Implements realistic movement with stiffness, angles, and range constraints for each segment.
  - Limb systems and leg systems simulate walking and reaching behaviors.

- **Canvas Rendering**:
  - Uses HTML5 Canvas for rendering creatures and animations.
  - Includes gradient-based styling for a visually appealing background.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/ulasbayraktar/reptile-simulation.git
   cd reptile-simulation