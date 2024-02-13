# Segmentation of Aortic Vessel Tree with Misclassification Loss

## Overview

This repository contains the implementation for the paper titled "Segmentation of Aortic Vessel Tree with Misclassification Loss." The paper proposes a novel Misclassification Loss (MC loss) function, along with a differentiable eXclusive OR (XOR) operation, to improve image segmentation performance, specifically focusing on the aortic vessel tree.

## Key Features

- **Misclassification Loss (MC Loss):** A novel loss function designed to address challenges in fine-scale structure segmentation, suppressing false positives, and rescuing false negatives.
- **Differentiable XOR Operation:** Implemented to identify false predictions, contributing to the effectiveness of the MC loss function.
- **Performance Metrics:** Achieves a Dice score of 0.93 and a Hausdorff Distance (HD) of 3.50 mm on a 5-fold split of 56 training subjects in the SEG.A. 2023 challenge.
- **Challenge Participation:** Ranked among the top-six approaches in the validation phase-1 of the SEG.A. 2023 challenge.

## Repository Structure

- `src/`: Contains the source code for the proposed method.
- `data/`: Placeholder for dataset information or links.
- `results/`: Holds the results achieved by the proposed method.
- `docs/`: Documentation, including the paper or additional notes.

## Getting Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/kabbas570/segmentation-aortic-vessel.git
   cd segmentation-aortic-vessel
