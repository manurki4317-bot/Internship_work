{
 "cells": [
  {
   "cell_type": "markdown",
   "id": "intro-cell",
   "metadata": {},
   "source": [
    "# Spike and Burst Analysis with ABF Files\n",
    "\n",
    "This repo shares some practice sessions on analyzing electrophysiology signals from **ABF (Axon Binary File)** recordings. The main focus is spotting *spikes* and *bursts*, pulling out key metrics, and visualizing patterns with tools like **UMAP**.\n",
    "\n",
    "### What you can do\n",
    "- Detect action potentials (*spikes*).\n",
    "- Find burst patterns (*bursts*).\n",
    "- Calculate simple stats (mean, ISI, area under curve, etc.).\n",
    "- Classify activity by shape and timing.\n",
    "- Explore conditions in low-dimensional spaces.\n",
    "\n",
    "### Why intracranial data?\n",
    "Compared to M/EEG (non-invasive but noisy), intracranial recordings give cleaner, higher-res signals. That makes it possible to look at single spikes and their bursts.\n",
    "\n",
    "### Tools\n",
    "- `pyabf` for reading `.abf` files\n",
    "- `numpy`, `pandas`, `scipy` for math/stats\n",
    "- `matplotlib`, `seaborn`, `plotly` for plots\n",
    "- `umap-learn`, `scikit-learn` for dimension reduction\n",
    "\n",
    "```{tip}\n",
    "Use a **virtual environment (conda/venv)** so dependencies don’t clash.\n",
    "```\n",
    "\n",
    "### Repo goals\n",
    "1. A reproducible pipeline for ABF analysis.\n",
    "2. Document the workflow from practice sessions.\n",
    "3. Base for future neuro data projects.\n",
    "\n",
    "---\n",
    "\n",
    "✍️ Made during electrophysiology data analysis practice.\n",
    "\n",
    "📂 Inspired by [Data Science and Spikes](https://fabien-campillo.github.io/data-science-spikes/).\n",
    "\n",
    "📜 License: CC BY-NC-SA 4.0.\n"
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "name": "python",
   "version": "3.11"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}
