# Fashion Image Captioning

A deep learning project for generating captions for fashion images using an encoder-decoder architecture with soft attention.

**Architecture:**
- **Encoder:** ResNet-50 (pretrained) extracts spatial visual features
- **Attention:** Soft attention mechanism focuses on relevant image regions
- **Decoder:** LSTM generates captions word-by-word using attended features

**Key Features:**
- Transfer learning with pretrained ResNet
- Spatial attention for interpretability
- Teacher forcing during training
- Greedy search for inference

## Files

- `CCAS.5.16 Final Project.ipynb` - Main notebook containing the model implementation and training
- `best_model.pth` - Trained model weights (stored with Git LFS)

## Requirements

- Python 3.x
- PyTorch
- Jupyter Notebook

## Usage

Open the Jupyter notebook to train the model or generate captions:

```bash
jupyter notebook "CCAS.5.16 Final Project.ipynb"
```

## Model

The trained model weights are stored using Git Large File Storage (LFS) due to the file size.
