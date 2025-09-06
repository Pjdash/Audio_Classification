# Audio Vision – Poaching Detection Application  

## 📌 Overview  
This project is a **deep learning-based system** for **poaching detection** using **audio signals**.  
It leverages **transfer learning (VGGish)**, **CNNs**, and **spectrogram features** to classify poaching-related sounds.  
The pipeline is managed using **MLflow** for experiment tracking, with **audio overlaying techniques** implemented via the **Pydub** library.  

---

## ⚙️ Features  
- Transfer Learning with **VGGish** for audio embeddings  
- **CNN models** applied on spectrogram features for secondary classification  
- **Audio preprocessing** and augmentation using **Pydub**  
- **ETL-style ML pipeline** with modular components  
- **MLflow** integration for tracking and experiment management  

---

## 🏗️ Workflow  

1. Update `config.yaml`  
2. Update `secrets.yaml` (Optional)  
3. Update `params.yaml`  
4. Update the entity  
5. Update the configuration manager in `src/config`  
6. Update the components  
7. Update the pipeline  
8. Update `main.py`  
9. Update `dvc.yaml`  
10. Update `app.py`  

---

## 🛠️ Tools & Technologies  
- **Deep Learning**: CNN, Transfer Learning (VGGish)  
- **Libraries**: Scikit-Learn, Pydub, MLflow  
- **Data Representation**: Spectrogram-based feature extraction  
- **Pipeline Management**: DVC, Config-driven setup  

---

## 🚀 How to Run  

### Step 1 – Clone the repository  
```bash
git clone https://github.com/kanishka-maurya/Audio_Classification
cd Audio_Classification
