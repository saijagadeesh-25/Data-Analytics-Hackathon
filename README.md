# 🏏 IPL Data Analytics Hackathon

An advanced data analytics platform engineered to extract deep competitive insights from historical Indian Premier League (IPL) matches. This project analyzes player performances, match dynamics, venue behaviors, and team strategies to uncover hidden patterns that influence match outcomes.

---

## 📊 Data Source & Setup

> ⚠️ **Important File Size Restriction Notice:**
> Due to GitHub's strict **100 MB file size limit**, the raw `IPL.csv` dataset (102.30 MB) cannot be hosted directly in this repository. 

To run the analysis locally on your machine, follow these simple setup steps:

1. **Download the Dataset:** [Click here to download the IPL Hackathon Dataset from Google Drive](PASTE_YOUR_GOOGLE_DRIVE_LINK_HERE) *(Replace this text with your actual Google Drive sharing URL)*.
2. **Directory Structure:** Create a folder named `data/` in the root directory of this project on your computer.
3. **Placement:** Move the downloaded `IPL.csv` file inside that `data/` folder.
4. **Execution:** Open `ipl_analysis_enhanced.ipynb` in Jupyter Notebook or VS Code, and run the cells sequentially. The code will automatically load the local file.

```text
📁 Data-Analytics-Hackathon
│
├── 📄 ipl_analysis_enhanced.ipynb  <-- Reads data from local 'data/' directory
├── 📄 .gitignore                  <-- Configured to protect and hide local raw data
├── 📄 README.md                   <-- Technical project overview
│
├── 📁 problem statement           
│   └── 📄 SDC_Data_Hackathon.pdf   <-- Official hackathon documentation guidelines
│
└── 📁 data                        
    └── 📄 IPL.csv                 <-- [KEEP LOCAL] Run your data files here
