# Task F: Flowers Recognition

## Project Overview
The Oxford Flowers 102 dataset is a collection of 102 flower categories commonly occurring in the United Kingdom. Each class consists of between 40 and 258 images with large scale, pose and light variations. The dataset includes categories with large variations within the category and several very similar categories.

## Dataset Details
- **Training set**: 10 images per class (1020 images total)
- **Validation set**: 10 images per class (1020 images total)
- **Test set**: 6149 images (minimum 20 per class)

## Main Task
Implement a classification model to classify the flower images.

## Datasets
- **TorchVision**: https://pytorch.org/vision/main/generated/torchvision.datasets.Flowers102.html
- **Oxford Flowers 102 Dataset**: https://www.robots.ox.ac.uk/~vgg/data/flowers/102/

## Additional Tasks to Explore

### 1. Architecture Modifications
- Modify previously published architectures (e.g., increase network depth, reduce parameters)
- Explore advanced techniques:
  - Deformable convolution
  - Visual prompt tuning for Transformers

### 2. Few-Shot Learning
- Analyze results using fewer training images
- Investigate few-shot learning performance

### 3. Advanced Data Augmentation
- Implement MixUp transformation techniques
- Reference: [Original MixUp paper](https://arxiv.org/abs/1710.09412) and [PyTorch implementation](https://github.com/facebookresearch/mixup-cifar10)

### 4. Advanced Loss Functions
- Experiment with triplet loss
- Compare performance against standard cross-entropy loss

## Project Requirements
- **Report**: 10 pages (Arial 10 font) excluding references, content page, and cover page
- **Code**: Well-commented and easily testable
- **Deadline**: November 14, 2025 (11:59 PM)

## Assessment Criteria
- Project execution (30%)
- Experiments and results (30%)
- Report presentation (15%)
- Novelty (15%)
- Peer review (10%)

## Computational Resources
- Use course-assigned computational resources
- Alternative: Google Colab (note session duration limits for long experiments)

## Deliverables
1. PDF report with team member names
2. ZIP file containing commented code
3. Comparison with existing methods
4. Experimental results and analysis