# music-emotion-project

# How to Run the Notebook from GitHub 

Follow these steps to open and run the notebook using Google Colab.

---

## 1. Copy the GitHub repository link
Go to the repository and copy the URL from your browser.

---

## 2. Open Google Colab
Go to: https://colab.research.google.com

---

## 3. Open the notebook from GitHub
- Click **File → Open notebook**
- Go to the **GitHub** tab
- Paste the repository link
- Press **Enter**
- Select: SusanaBB_C432_FinalProject.ipynbk.ipynb


---

## 4. Connect to a runtime
Click the **Connect** button (top right).

---

## 5. Enable GPU
- Click **Runtime → Change runtime type**
- Set:
  - Hardware accelerator → **GPU**
- Click **Save**

---

## 6. Run the notebook
Click:
- **Runtime → Run all**

This will execute the full pipeline from start to finish.

---

## 7. Wait for execution
The notebook will automatically:
- install required libraries
- download the dataset
- extract features (audio + lyrics)
- train models
- run evaluation
- generate plots and results

---

## 8. Outputs
All outputs are saved in:
/content/data/

This includes:
- embeddings
- trained models
- predictions
- evaluation metrics
- plots

---

## Important Notes
- Run the notebook **from top to bottom**
- Do **not skip cells**
- Later phases depend on earlier outputs
- Full execution may take around **20-25 minutes**
