# 📂 ETBeacon Notebooks

This folder contains Jupyter Notebooks that systematically analyze the **1314.22 Hz signal** detected in multiple LIGO runs, validating its structure using SETI’s criteria.

## 📌 Notebook Breakdown:
| **Notebook** | **Purpose** |
|-------------|------------|
| `1-Initial_FFT_Graph.ipynb` | Computes FFT and identifies spectral spikes in H1 and L1 at different timestamps. |
| `2-Narrowband_Structure.ipynb` | Confirms that 1314.22 Hz is isolated and persistent across multiple datasets. |
| `3-Mathematical_Encoding.ipynb` | Analyzes Prime-Lattice gaps, π² * 100, φ relationships, and modular structures. **(Note: Prime gap analysis was conducted outside the 1314.22 Hz range; the initial paper focused on 1285 Hz - 1295 Hz.)** |
| `4-Frequency_Drift_Modulation.ipynb` | Tests whether 1314.22 Hz exhibits drift, phase modulation, or encoding features. |
| `5-Persistence_Across_Time.ipynb` | Demonstrates the signal's presence over multiple years and detectors. |

## 🛠️ How to Use These Notebooks
1. Open a terminal and navigate to the repository:
   ```sh
   cd ETBeacon
   pip install -r requirements.txt
   jupyter notebook
