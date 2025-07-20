# About me
Hi! My name is Edoardo and I'm a Master's student at the Technical University of Munich, where I'm studying Mathematics in Science and Engineering. I recently graduated from Bocconi University with a Bachelor's degree in Mathematical and Computing Sciences for Artificial Intelligence. I'm deeply passionate about mathematics and algorithms, and my main interests are optimization and graph theory.

My ambition is to apply my expertise in mathematical optimization to solve interesting real-world problems.

I'm currently working as a student researcher in Machine Learning at Bocconi under the guidance of Professor Francesca Buffa.

When I'm not coding or mathing around, you can find me practicing martial arts, playing chess, hiking, or watching football.

---

# Education

**MSc Mathematics in Science and Engineering**, Technical University of Munich, Munich, 2024-2026

**BSc Mathematical and Computing Sciences for Artificial Intelligence**, Bocconi University, Milan, 2021-2024

---

# Experience

**Research Assistant in Machine Learning**, Bocconi University, Milan, 2024-2025
- Funding: European Research Council - "Agent-Based Modelling of Gene Networks to model clonal selection in the tumour microenvironment and predict therapeutic resistance"
- Scientific Coordinator: Francesca Buffa
- Topics: transcriptomics, proteomics, gene networks, boosting algorithms, attention and transformers, semi-supervised learning, physics-informed neural networks.
- We explore the dynamics of protein abundance and its relation to mRNA levels, leading to a richer understanding of gene regulation in cancer.

---

# Projects

### BSc Thesis: "Inference of the Dynamics of Protein Abundance and Regulation in Cancer: Boosting and Deep Learning Approaches"
Proteins are fundamental actors in our bodies that carry out a wide range of critical cell functions. Understanding how diseases affect the protein landscape can reveal important insights into the biological mechanisms implicated in such diseases, and it can help in designing effective treatments.

However, diseases are often better understood at the level of mRNA, which is easier to quantify precisely. Several studies have reported discordance between mRNA and protein levels. Moreover, the relationship between the two is complex, noisy, and highly non-linear. Bridging this gap helps to provide a more comprehensive understanding of cellular function and regulatory mechanisms.

In an attempt to analyze at large scale the non-linear relationships between mRNA expression and protein abundance in cancer, we employ two popular state-of-the-art classes of non-linear methods: boosting and deep learning.

In particular, this work focuses on AdaBoost and XGBoost, transformers, and latent representations from autoencoders. These techniques capture the hidden relationships between variables, elucidating the complex dynamics governing protein synthesis and regulation in cancer.

![](/assets/img/ccle.png)

### A comparison of deep and transfer learning approaches for image-based galaxy morphology classification [(pdf)](folder/Galaxy_Morphologies.pdf)
[(Download pdf)](folder/Galaxy_Morphologies.pdf)

Astronomy generates vast amounts of image data, which necessitate reliable automated classification algorithms that can capture the subtle differences in galaxy shapes. We explore a wide range of supervised strategies, from fine-tuning pre-trained models to devising our custom architecture, a convolutional network with early denoising layers. Finally, we approach the problem in an unsupervised fashion, leveraging DINO embeddings and clustering techniques. Through comparative analysis, we identified the most effective methodologies for the classification of galaxy morphology, providing insights into the broader question of model development versus adaptation in computer vision.

![](/assets/img/image_galaxies.png)
*An example from each of the ten morphology classes*

### Investigating mice 3d representation capabilities from exposure to monocular stimuli
We investigate the ability of mice to perceive the three-dimensional structure of their surrounding environment by analyzing two-dimensional images perceived with a single eye. Exposing them to monocular stimuli, we aim to elucidate the role of single-eye visual input in the depth perception of mice moving in a 3D world.

![](/assets/img/depth.png)
*MiDaS was used to obtain a depth map for each frame shown to the mice*

![](/assets/img/crop.png)
*Analyzing a small crop in the image helps dealing with limited receptive fields and depth variance*
