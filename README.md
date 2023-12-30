# SemanticGeometry

Toy project in LLM training.
The goal of the project is create the embedding space whith semantically meaningful geometry.

Milestones:
1. Find and download the text database
2. Define the network architecture
3. Train the network
4. Check if the embedding space (latent word vector space) posess the semantic geometry, where e.g. King-Man+Woman=Queen.

Environment:
- Python 3.9
- Torch 2.1.0+cu118
- Cuda 11.8
- Make sure to use tfds-nightly instead of tensorflow-datasets \
  `pip install tfds-nightly`

![Два дебила это сила](DevelopmentBuddies.jpg)

TODO 2023.12.30
1. Save model after each epoch
2. Save training and validation curves
