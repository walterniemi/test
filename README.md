📡 ETBeacon: A Search for Intelligence in Gravitational Waves
Welcome to ETBeacon, a structured investigation into a persistent 1314.22 Hz signal found in multiple LIGO observation runs. Could this be the first gravitational wave technosignature?

Using SETI’s “Rosetta Stone” criteria, we break down whether this signal shows evidence of mathematical encoding, persistence across time, and potential modulation—all hallmarks of intelligent communication.

📌 How Do We Know If This Signal is Intelligent?
SETI defines specific criteria for detecting an artificial signal. Here’s how our analysis lines up:

SETI Test	What It Means	Which Notebook Proves It
1. The Signal is in a Specific, Isolated Frequency Band	Not just random noise—should be a narrowband signal that stands out.	notebooks/2-Narrowband_Structure.ipynb
2. The Signal Persists Over Time	If it’s real, it should show up across different years, detectors, and runs.	notebooks/5-Persistence_Across_Time.ipynb
3. The Signal Contains Mathematical Structure	Random radio static won’t give us prime numbers and fundamental constants.	notebooks/3-Mathematical_Encoding.ipynb
4. The Signal is Modulated or Drifted	A transmission should shift in a controlled way, like a radio station changing frequency.	notebooks/4-Frequency_Drift_Modulation.ipynb
5. The Signal is Detected by More Than One Telescope	If only one detector sees it, it’s probably just noise. If multiple do, it’s real.	notebooks/1-Initial_FFT_Graph.ipynb, notebooks/5-Persistence_Across_Time.ipynb
6. The Signal Shows Up in Other Kinds of Telescopes	If it also appears in radio waves or X-rays, that’s a huge deal—but we can’t test that with LIGO.	Not applicable.
📂 Repository Structure
This repository is organized into Jupyter Notebooks and Python scripts that guide users through each phase of the investigation.

bash
Copy
Edit
📂 ETBeacon/
│── 📂 notebooks/  
│    ├── 1-Initial_FFT_Graph.ipynb          # Shows spectral spikes at two timestamps (H1 and L1)
│    ├── 2-Narrowband_Structure.ipynb       # Confirms that 1314.22 Hz is isolated & persistent  
│    ├── 3-Mathematical_Encoding.ipynb      # Prime gaps, π² * 100, φ, Fibonacci  
│    ├── 4-Frequency_Drift_Modulation.ipynb # Phase offsets & modular transformations  
│    ├── 5-Persistence_Across_Time.ipynb    # Verifies signal stability over years  
│── 📂 scripts/  
│    ├── run_all.py                         # Automates full analysis  
│── 📂 data/  
│    ├── README.md                          # Instructions for downloading LIGO data  
│    ├── example_dataset.hdf5               # (Optional) Small test dataset  
│── 📂 figures/  
│    ├── FFT_Spectrum_H1_L1.png  
│    ├── Prime_Gap_Distribution.png  
│    ├── Phase_Modulation_Analysis.png  
│── 📜 README.md                             # This file  
│── 📜 LICENSE                               # Open-source license  
│── 📜 requirements.txt                      # Python dependencies for easy setup  
🚀 How to Run This Analysis
If you’d like to replicate our findings, follow these steps:

1️⃣ Clone the Repository:
sh
git clone https://github.com/YOUR_GITHUB_USERNAME/ETBeacon.git
cd ETBeacon

2️⃣ Install Dependencies:
sh
pip install -r requirements.txt
3️⃣ Run Jupyter Notebook:

sh
jupyter notebook
4️⃣ Open and execute the notebooks in order to follow the full analysis.

