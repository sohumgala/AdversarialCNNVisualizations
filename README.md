# Visualizing Adversarial Input in CNN



## Open Source Code
[Pytorch CNN Visualization Library](https://github.com/utkuozbulak/pytorch-cnn-visualizations) - This is the base library we extended to visualize adversarial inputs. We used roughly 1k lines of this code written in Python, which mainly using the PyTorch library.

## Datasets
[ImageNet](https://www.image-net.org/) - An image database containing hundreds of thousands of images for each of one thousand classes. 

## File Descriptions
The `src` directory contains all the source and executable code for this project. `GradientSaliency.ipynb`, `LayerwiseRelevance.ipynb`, `LayerCAM.ipynb`, `ScoreCAM.ipynb`, and `SmoothGrad.ipynb` are the files which included the modified library code used to produce each respective visualization. 

`AdversarialAccuracy.ipynb` contains the code used for assessing the model's ability to handle increasingly perturbed images. 

`adv_generation_inverted_image.ipynb` contains the code used for generating adversarial images, and producing inverted image visualizations.

`img_diff_checker.ipynb` contains some exploratory code relating to analyzing absolute differences in image pixel values to understand where perturbations tend to be added.

## Performance Measuring Tools - Analysis
[Final report slides]

