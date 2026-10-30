# Intelligent Analysis of Biomedical Images

Coursework and project material from the first semester of my M.Sc. in Computer Engineering at Sharif University of Technology, taught by Dr. Mohammad Hossein Rohban. Author: Farzan Rahmani.

The collection covers medical-image formats and preprocessing, reconstruction, segmentation, registration, and deep-learning approaches to biomedical image analysis.

## Repository Guide

| Path | Material |
| --- | --- |
| `HWs/HW1/` | DICOM exploration and retinal segmentation notebooks, including starter and submitted versions |
| `HWs/HW2/` | Brain-tumor analysis and sinogram exercises |
| `HWs/HW4/` | VoxelMorph registration and multiple-instance learning/graph neural network exercises |
| `HWs/HW5/` | U-Net segmentation and vision-transformer classification/visualization |
| `project/practical_project/` | Project work including metadata linking, DICOM-to-NIfTI conversion, reorientation, and N4 bias-field correction notebooks |
| `project/representation/` | Project presentation material |
| `TAs/`, `quizes/`, `exams/`, `last_terms_sample_exams/` | Teaching support, quizzes, exams, and previous sample exams |
| `Policy.pdf`, `src.txt` | Course policy and external resource reference |

## Environment and Usage

Use Jupyter or Google Colab. Requirements depend on the notebook: common libraries include NumPy, Matplotlib, scikit-image, scikit-learn, PyTorch, torchvision, and MONAI, with additional medical-image tools for format conversion and preprocessing.

1. Read the assignment statement and select a notebook. Files containing the author's name or student ID distinguish submissions from many starter versions.
2. Inspect installation cells, imports, dataset links, and working-directory assumptions.
3. Obtain the relevant data and configure local or Drive paths.
4. Execute cells in order; use a GPU for deep-learning training where appropriate.

Some `.py` files are notebook exports and still contain notebook syntax such as `!pip install`; they cannot be run unchanged by the standard Python interpreter. Prefer the corresponding `.ipynb` when reproducing those exercises.

## Data and Interpretation

Medical datasets and pretrained weights may be external to the repository. Follow the original source's access and usage terms. Results are coursework experiments and have not been established as clinical tools. Saved notebook outputs reflect specific data splits, parameters, and environments.

## License

See [LICENSE](LICENSE) for repository license terms. Course materials and external datasets retain their original attribution and applicable terms.
