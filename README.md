# CS-6304 – Advanced Topics in Machine Learning
**PA0**

The assignment focuses on developing practical understanding of fundamental deep learning concepts and implementing experiments involving:

Convolutional Neural Networks (CNNs)
ResNet-152 and residual learning
Transfer learning and feature representations
Vision Transformers (ViTs)
Self-attention and attention visualization
Contrastive learning
CLIP and multimodal representations
Variational Autoencoders (VAEs)

All experiments were implemented using Python and relevant deep learning and machine learning libraries.

## Tasks

### Task 1 – ResNet-152
This task explores how pretrained ResNet-152 can be used for transfer learning on a different dataset. It also looks at the role of residual connections, feature representations at different layers, and the effect of fine-tuning different parts of the network.

* Transfer learning with pretrained ResNet-152
* Residual connection ablation
* Feature visualization using t-SNE/UMAP
* Transfer learning and fine-tuning experiments

### Task 2 – Vision Transformer
This task explores how Vision Transformers process images as sequences of patches and how self-attention contributes to their predictions. Attention maps are visualized to see which parts of an image the model focuses on, along with experiments on patch masking and different token representations.

* Pretrained ViT image classification
* Patch attention visualization
* Patch-masking experiment
* [CLS] token vs. mean-pooled patch tokens

### Task 3 – CLIP
This task investigates CLIP's ability to connect visual and textual information through contrastive learning. Zero-shot classification is tested on STL-10 using different prompts, followed by visualization and analysis of the gap between image and text embeddings.

* Zero-shot classification on STL-10
* Prompting strategy comparison
* Image/text embedding visualization
* Modality gap and Procrustes alignment

### Task 4 – VAE
This task implements a Variational Autoencoder on MNIST to understand how neural networks can learn a meaningful latent representation of data. The learned latent space, reconstruction quality, and ability to generate new handwritten digits are analyzed and compared with Doersch's VAE implementation.

* VAE implementation on MNIST
* Latent-space visualization
* Image reconstruction
* New sample generation
* Comparison with Doersch's VAE

