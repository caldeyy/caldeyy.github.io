# About me
Hi! My name is Edoardo and I'm a master's student at TU Munich, where I'm studying Mathematics in Science and Engineering. I recently graduated from Bocconi with a bachelor's degree in Mathematical and Computing Sciences for Artificial Intelligence. I'm deeply passionate about mathematics and algorithms, and my main interests are graph theory, optimization, geometric deep learning, and bioinformatics.

Indeed, my ambition is to work in the field of computational biology, as I find this path to be intriguing and purposeful, and I'm convinced that I can make a large positive impact by applying my skills to this area.

When I'm not coding or mathing around, you may find me playing chess or practicing martial arts.

---

# Education

**MSc Mathematics in Science and Engineering**, Technical University of Munich, Munich, 2024-2026
- Application focus area: biomedical machine learning

**BSc Mathematical and Computing Sciences for Artificial Intelligence**, Bocconi University, Milan, 2021-2024
- Thesis: "Inference of the dynamics of protein abundance and regulation in cancer: boosting and deep learning approaches", advised by Francesca Buffa

---

# Projects

### Inferring protein abundance in cancer with boosting and deep learning
Proteins are fundamental actors in our bodies that carry out a wide range of critical cell functions. Understanding how diseases affect the protein landscape can reveal important insights into the biological mechanisms implicated in such diseases, and it can help in designing effective treatments.

However, diseases are often better understood at the level of mRNA, which is easier to quantify precisely. Several studies have reported discordance between mRNA and protein levels. Moreover, the relationship between the two is complex, noisy, and highly non-linear. Bridging this gap helps to provide a more comprehensive understanding of cellular function and regulatory mechanisms.

In an attempt to analyze at large scale the non-linear relationships between mRNA expression and protein abundance in cancer, we employ two popular state-of-the-art classes of non-linear methods: boosting and deep learning.

In particular, this work focuses on AdaBoost and XGBoost, transformers, and latent representations from autoencoders.
These techniques capture the hidden relationships between variables, elucidating the complex dynamics governing protein synthesis and regulation in cancer.

![](/assets/img/ccle.png)

### Detecting hypoxia from scRNA-seq expression
Bla bla bla

### A comparison of deep and transfer learning approaches for image-based galaxy morphology classification
Astronomy generates vast amounts of image data, which necessitate reliable automated classification algorithms that can capture the subtle differences in galaxy shapes.

![](/assets/img/image_galaxies.png)
*An example from each of the ten morphology classes*

We explore a wide range of supervised strategies, from fine-tuning pre-trained models to devising our custom architecture. Finally, we approach the problem in an unsupervised fashion, leveraging DINO embeddings and clustering techniques.

Through comparative analysis, we identified the most effective methodologies for the classification of galaxy morphology, providing insights into the broader question of model development versus adaptation in computer vision.

### Investigating mice 3d representation capabilities from exposure to monocular stimuli
We investigate the ability of mice to perceive the three-dimensional structure of their surrounding environment by analyzing two-dimensional images perceived with a single eye. Exposing them to monocular stimuli, we aim to elucidate the role of single-eye visual input in the depth perception of mice moving in a 3D world.

![](/assets/img/depth.png)
*MiDaS was used to obtain a depth map for each frame shown to the mice*

![](/assets/img/crop.png)
*Analyzing a small crop in the image helps dealing with limited receptive fields and depth variance*
