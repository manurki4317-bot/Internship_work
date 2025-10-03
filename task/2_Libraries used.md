# 1. Resources and references

I’ve put together some resources and references using Python. These are the main libraries that supported my analyses, computations, and visualizations during the internship.

1.1. Some Python packages
Core numerical & scientific computing

NumPy – Fundamental library for numerical computing, arrays, and linear algebra.

SciPy – Scientific computing, including signal processing (find_peaks, hilbert) and interpolation (interp1d).

os – Provides a way of interacting with the operating system.

Data handling & manipulation

pandas – Data structures and analysis tools (DataFrame, Series).

tslearn – Time-series machine learning, including preprocessing (TimeSeriesScalerMinMax) and shapelets learning (LearningShapelets).

Statistics & metrics

scipy.stats – Provides statistical functions such as skew and kurtosis.

numpy.linalg – Linear algebra operations, e.g. least squares (lstsq).

scikit-learn (sklearn) – Tools for machine learning and model evaluation:

TruncatedSVD for dimensionality reduction.

StandardScaler for feature scaling.

r2_score for model evaluation.

Signal processing & electrophysiology

pyABF – Specialized library to read and analyze Axon Binary Files (ABF) from electrophysiology experiments.

Machine learning & dimensionality reduction

UMAP – Dimensionality reduction and visualization technique.

TensorFlow/Keras – Deep learning framework (used here with the Adam optimizer).

Graphs & network analysis

networkx – Creation, analysis, and visualization of complex networks/graphs.

Plotting & visualization

matplotlib – Standard Python plotting library.

matplotlib.cm – Colormap handling for visualizations.

seaborn – High-level statistical data visualization built on matplotlib.

plotly.express – Interactive plotting library.

plotly.io – Lower-level interface for rendering plotly figures.

Jupyter utilities

%matplotlib widget – Enables interactive plots within Jupyter notebooks.
