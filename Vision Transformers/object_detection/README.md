# Vision Transformer Experiments

This repository contains three experiments focusing on object detection using Vision Transformers (ViT) pretrained on Google's vit-base-patch16-224-in21k model. Each experiment explores different approaches to fine-tuning and applying the ViT model for specific tasks.

## Experiment 1: Custom Head and Partial Relearning of ViT

### Overview
- **Objective**: Object detection with custom head and relearning the last two layers of ViT.
- **Dataset**: Caltech 101 Dataset.
- **Key Features**:
  - Utilizes a custom head for the Vision Transformer.
  - Relearns the last two layers of the transformer.
  - Implements Generalized Intersection over Union (GIoU) for loss calculation.
- **Libraries Used**: PyTorch, PyTorch Lightning, Transformers (Hugging Face), PIL, Matplotlib.
- [Notebook Link](https://github.com/regis-funke/experiments/blob/main/pytorch_object_detection_custom_head_two_transformer_layers.ipynb)

## Experiment 2: Full Relearning of ViT

### Overview
- **Objective**: Complete relearning of the Vision Transformer for object detection.
- **Dataset**: Caltech 101 Dataset.
- **Key Features**:
  - Implements the Vision Transformer with all layers unfrozen for retraining.
  - Uses GIoU for performance measurement.
- **Libraries Used**: PyTorch, PyTorch Lightning, Transformers (Hugging Face), PIL, Matplotlib.
- [Notebook Link](https://github.com/regis-funke/experiments/blob/main/pytorch_object_detection_full_vit.ipynb)

## Experiment 3: Custom Head with Original ViT

### Overview
- **Objective**: Object detection using the original ViT with a custom head.
- **Dataset**: Caltech 101 Dataset.
- **Key Features**:
  - Keeps the original ViT layers frozen.
  - Implements a custom head for detection tasks.
  - GIoU metric for bounding box accuracy.
- **Libraries Used**: PyTorch, PyTorch Lightning, Transformers (Hugging Face), PIL, Matplotlib.
- [Notebook Link](https://github.com/regis-funke/experiments/blob/main/pytorch_object_detection_original_vit_with_custom_head.ipynb)

## Installation and Usage
- Clone this repository.
- Install required dependencies as specified in each notebook.
- Run the Jupyter notebooks to replicate the experiments.

## License
This project is open-source and available under standard open-source licenses.

