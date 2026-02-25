# Stress-testing CLIP's zero-shot classification

# Dresses & Clothes Classification with CLIP

This project explores zero-shot image classification and semantic territory mapping using OpenAI's CLIP model.

It investigates how CLIP assigns meaning to fashion aesthetic using cosine similarity in embedding space and visualizes the resulting semantic territories.

---

## Project Goals

- Understand CLIP’s zero-shot classification process
- Compare unlabeled vs labeled categorization
- Visualize embedding space projections (2D)
- Analyze semantic similarity and bias patterns
- Generate Voronoi-like prompt territories


## Method Overview

1. Encode images using CLIP image encoder
2. Encode text prompts at different detail levels
3. Normalize embeddings
4. Compute cosine similarity
5. Assign each image to nearest prompt
6. Visualize territories in projected space



## Example Visualization

- Nearest-prompt assignment regions
- Cosine similarity scoring
- 2D embedding projections

---

## Installation

Clone the repository:

```bash
git clone https://github.com/estherpadrao/ai-lab-clip.git

