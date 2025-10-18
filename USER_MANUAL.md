# User Manual – Internship Work Repository

## Overview

This repository serves as a record of all the work completed during an internship at **BCAM (Basque Center for Applied Mathematics)**.  
It documents the progress, methodologies, and results developed across multiple analytical and computational tasks.

Rather than covering introductory explanations or theoretical background, the focus lies on **specific analyses, visualizations, and applications** performed during the internship.

## Repository Structure

The repository is organized as follows:

| Folder / File | Description |
|----------------|--------------|
| **[Context](./task/1_context.md):** | Provides the initial context of the analyses. |
| **[Resources and references](./task/2_Libraries_used.md):** | Contains information about the packages and libraries used, including links to their documentation. |
| **[Visibility graph and 2D and 3D embedding](./task/Task1.ipynb):** | Includes notebooks related to visibility graph construction and 2D/3D embeddings. |
| **[UMAP and Histplot](./task/Task2.ipynb):** | Focused on Shapelet analysis and visualization. |
| **[Shapelets](./task/Task3.ipynb):** | Presents “clustering” representations of bursts using UMAP and histograms. |
| **[Better UMAP identification](./task/Task4.ipynb):** | Refined clustering and UMAP analysis for conflictive burst areas *(in progress)*. |
| **[Applications for bursts identification and evaluation](./task/Task5.ipynb):** | Tools to compare anomalous bursts with their surroundings, allowing both quantitative and visual analysis. |
| **[Python related content](.python)** | Python scripts, CSV files, and `.abf` datasets used across tasks. |
| **[Images of each of the projects/tasks](./Images_outputs)** | Visual outputs of each project or task (stored in 4 folders — one per project). |

Subfolders for images:
  - **[Task1 images](./Images_outputs/Task1)** 
  - **[Task2 images](./Images_outputs/Task2)**
  - **[Task3 images](./Images_outputs/Task3)**
  - **[Task4 images](./Images_outputs/Task4)**
  - **[Task5 images](./Images_outputs/Task5)** 


## Requirements

To explore or reproduce the work, ensure the following environment:

- **Language:** Python 3.8+
- **Core Libraries:**
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `seaborn`
  - `scipy`
  - `umap-learn`
  - `networkx`
  - `neo` (for `.abf` file handling)
  - `pyabf` (if used for electrophysiological data)

Install dependencies:
```bash
pip install -r requirements.txt
```


## Usage

### Running Notebooks
1. Clone the repository:
   ```bash
   git clone https://github.com/manurki4317-bot/Internship_work.git
   cd Internship_work
   ```
2. Open the desired Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Navigate to the notebook of interest and execute the cells sequentially.


## Project Topics Overview

| Topic | Description |
|--------|--------------|
| **Visibility Graph Analysis** | Conversion of time series into complex networks and visualization in 2D/3D. |
| **UMAP and Histplot** | Dimensionality reduction and visualization of burst patterns. |
| **Shapelets & Clustering** | Identification and grouping of similar burst structures. |
| **Enhanced UMAP Analysis** | Improved methods for detecting and visualizing conflictive burst zones. |
| **Applications for Burst Evaluation** | Tools for comparing anomalous vs. normal bursts visually and quantitatively. |


## Outputs

Each task or project includes:
- Generated **plots and figures** (stored in `TaskX_images/`)
- **Processed CSV files** with analysis results
- **Python scripts** implementing specific methods
- **ABF files** representing electrophysiological data inputs


## Notes

- Not all image outputs are visible within the `.ipynb` preview on GitHub; the dedicated image folders ensure full access.
- Some parts of the analysis (e.g., “Better UMAP identification”) are **ongoing work**.


## Author

**Manurki4317**  
Internship at **BCAM (Basque Center for Applied Mathematics)**  
GitHub: [manurki4317-bot](https://github.com/manurki4317-bot)


## License

This repository is intended for academic and research purposes.  
If you use or refer to this work, please provide appropriate citation or acknowledgment.



**This specific markdown was partially done with AI as a support tool.**
