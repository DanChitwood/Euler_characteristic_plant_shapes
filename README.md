# Euler_characteristic_plant_shapes
A repository for code and data analyzing plant shapes using the Euler characteristic transform (ECT)

![alt text](https://github.com/DanChitwood/Euler_characteristic_plant_shapes/blob/main/ect_animation.gif)

**Figure 1: Euler characteristic transform (ECT) converts graphs into cylindrical images. A)** Graph-representations of cut-outs from *The Parakeet and the Mermaid* (Henri Matisse, 1952). Vertices of each shape graph are plotted in black along the outline. **B)** Rotation of a shape graph (top) and corresponding ECT images (middle) and cylindrical representations (bottom). Cylindrical padding created by corresponding regions "A" and "B" and zero padding for convolutional neural networks (CNNs) are indicated. Euler characteristic ($\chi$) color values are shown. **C)** t-distributed stochastic neighbor embedding (t-SNE), **D)** uniform manifold approximation and projection (UMAP), and **E)** potential of heat-diffusion for affinity-based trajectory embedding (PHATE) embeddings of principal component analysis (PCA)-normalized ECT images. Shapes and corresponding colors are projected onto embeddings for visualization purposes.

Code reproducing ***Figure 1*** can be found in the following Jupyter notebook: https://github.com/DanChitwood/Euler_characteristic_plant_shapes/blob/main/Figure1/figure_1.ipynb

![alt text](https://github.com/DanChitwood/Euler_characteristic_plant_shapes/blob/main/Figure1/Figure1.png)

**Figure 2: Shapes and associated Euler characteristic transform (ECT) images. A)** Randomly selected leaf and **B)** pavement cell shapes and corresponding ECT images. Species names and Euler characteristic ($\chi$) color values are provided.

Code reproducing ***Figure 2*** can be found in the following Jupyter notebook: https://github.com/DanChitwood/Euler_characteristic_plant_shapes/blob/main/Figure2/figure_2.ipynb

![alt text](https://github.com/DanChitwood/Euler_characteristic_plant_shapes/blob/main/Figure2/Figure2.png)

**Figure 3: Manifold-learning using potential of heat-diffusion for affinity-based trajectory embedding (PHATE) on Euler characteristic transform (ECT) images of leaves. A)** Leaves from across the land plants (black points) and specific taxa (indicated by color kernel density distributions, see legend), **B)** representative leaf shapes (black contours) and features of the shape space (indicated by arrows and lowercase letters, see text for explanation), **C)** width-to-length ratio (indicated by color, see legend), and **D)** solidity to the eighth power (indicated by color, see legend) projected onto a three-dimensional PHATE embedding of ECT images. For all panels, PHATE2 vs. PHATE 1 (left), PHATE3 vs. PHATE1 (middle), and PHATE3 vs. PHATE2 (right) plots are provided.

![alt text](https://github.com/DanChitwood/Euler_characteristic_plant_shapes/blob/main/Figure3/Figure3.png)

**Figure 4: Manifold-learning using potential of heat-diffusion for affinity-based trajectory embedding (PHATE) on Euler characteristic transform (ECT) images of pavement cells. A)** Pavement cells colored by major clade identity (see legend), **B)** representative cell shapes (black contours) and features of the shape space (indicated by arrows and lowercase letters, see text for explanation), **C)** width-to-length ratio (indicated by color, see legend), and **D)** solidity to the eighth power (indicated by color, see legend) projected onto a three-dimensional PHATE embedding of ECT images. For all panels, PHATE2 vs. PHATE 1 (left), PHATE3 vs. PHATE1 (middle), and PHATE3 vs. PHATE2 (right) plots are provided.

![alt text](https://github.com/DanChitwood/Euler_characteristic_plant_shapes/blob/main/Figure4/Figure4.png)
