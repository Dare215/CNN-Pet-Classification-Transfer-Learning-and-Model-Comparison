# CNN Capstone: Pet Classification With Model Comparison

This project trains and compares four CNN architectures for dog-vs-cat classification:

1. Simple Custom CNN
2. VGG16 Transfer Learning
3. ResNet50 Transfer Learning
4. EfficientNetB0 Transfer Learning

## Local Dataset Paths

```python
CAT_DIR = "/Users/dare/CaseStudy6Files/dog-cat-dataset/data/cats"
DOG_DIR = "/Users/dare/CaseStudy6Files/dog-cat-dataset/data/dogs"
```

## Outputs Generated After Running Notebook

- `cnn_capstone_outputs/results/cnn_lab_results.json`
- `cnn_capstone_outputs/results/cnn_lab_comparison.csv`
- Training curves
- Confusion matrices
- t-SNE feature visualizations
- Saved `.keras` models

## How to Run

1. Open `CNN_Capstone_Pet_Classification_Submission_Ready.ipynb` in JupyterLab.
2. Confirm the `CAT_DIR` and `DOG_DIR` paths.
3. Run all cells.
4. Submit the executed notebook and generated results files.
