# Stress-testing CLIP's zero-shot classification

# Dresses & Clothes Classification with CLIP

This project explores zero-shot image classification and semantic territory mapping using OpenAI’s CLIP model.

Instead of focusing only on classification accuracy, I treat zero-shot prediction as a question of **semantic structure**. By analyzing cosine similarities and visualizing embeddings, I examine how wedding aesthetic concepts like _traditional, modern, romantic, and dramatic_ appear (or fail to appear) as stable regions in CLIP’s vector space. This is tested across different domains, including wedding dresses, shoes, and venues.

The findings suggest that culturally loaded aesthetic labels do not form clear, separate clusters. Instead, they tend to overlap, shift, and change **depending on prompt wording**. In CLIP, meaning is not stored as fixed categories, but as relational structure distributed across the multimodal embedding space.

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

