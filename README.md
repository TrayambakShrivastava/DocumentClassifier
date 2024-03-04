# DocumentClassifier
# LayoutLMv2 Image Classification

This repository contains code for training a layout-based image classification model using LayoutLMv2 and PyTorch. The model is trained on a custom dataset, achieving an accuracy of 74%.

## Requirements
- Python 3.10
- PyTorch
- Transformers
- Detectron2
- Tesseract OCR
- Other dependencies (install using requirements.txt)

## Dataset
The model is trained on a custom dataset consisting of various document types, such as government documents, legal texts, medical reports, finance documents, news articles, educational materials, scientific research papers, business documents, technical manuals, and creative writing samples.

### Dataset Statistics
| Category                | Count |
|-------------------------|-------|
| Government              | 70    |
| Legal                   | 68    |
| Medical                 | 18    |
| Finance                 | 75    |
| News                    | 28    |
| Educational             | 20    |
| Scientific Research     | 55    |
| Business                | 16    |
| Technical Manuals       | 23    |
| Creative Writing        | 22    |

## Training
- The model is trained for 7 epochs with an AdamW optimizer and a learning rate of 5e-5.

## Model Performance
- The trained model achieved an accuracy of 74% on the test dataset.

## How to Use
- Follow the code in `train_layoutlmv2_model.ipynb` to train your own model on a custom dataset.
- Adjust hyperparameters and configurations as needed for your specific use case.

## Acknowledgments
- The layout-based image classification model is based on the LayoutLMv2 architecture developed by Microsoft Research.

Feel free to explore, modify, and use the code for your own projects!
