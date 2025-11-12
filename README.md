# EEG Confusion Detection: Analyzing Student Brainwaves

This repo analyzes the [Confused Student EEG Brainwave Dataset](https://www.kaggle.com/datasets/wanghaohan/confused-eeg) using Python in Google Colab. We explore band powers (Delta, Theta, etc.), visualize confusion patterns, run stats (t-tests), and build a simple ML classifier (Random Forest, ~75% accuracy).

## Key Insights
- Confusion correlates with ↑ Theta/Delta (drowsiness) and ↓ Beta/Gamma (low focus).
- Significant differences: Theta (p<0.01), Beta2 (p<0.05).
- [Link to Colab Notebook](https://colab.research.google.com/drive/1sRprc2OJPRF6een-BUB1nH_q75R9Tthv?usp=sharing)

## Setup & Run
1. Open the notebook in [Google Colab](https://colab.research.google.com).
2. Download data: Run the Kaggle API cells (upload your `kaggle.json`).
3. Install libs: Already included (pandas, sklearn, seaborn).
4. Execute all cells—plots and model train automatically.

## Files
- `confused-student.ipynb`: Main notebook with code, visuals, and results.
