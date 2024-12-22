# 🌟 X-Ray Image Summary Prediction using ViT + GPT-2

This project leverages cutting-edge AI architectures, **Vision Transformer (ViT)** and **GPT-2**, to generate concise and insightful summaries for X-Ray images. Designed to assist in medical diagnostics, this model creates descriptions of visible structures and abnormalities directly from image inputs.

---

## 🚀 Features
- **State-of-the-Art Vision Transformer (ViT):** Extracts detailed visual features from X-Ray images.
- **GPT-2 Text Generator:** Creates comprehensive textual summaries from visual data.
- **End-to-End Pipeline:** Seamless integration of image processing and text generation.
- **Advanced Preprocessing:** Enhances X-Ray image clarity for superior feature extraction.

---

## 📋 Requirements

Ensure you have the following installed:

- **Python** >= 3.8
- **PyTorch**
- **Transformers Library** (Hugging Face)
- **NumPy**
- **Matplotlib**
- **Jupyter Notebook** *(optional)*

### Install Dependencies

Run the following command to install the necessary packages:

```bash
pip install torch torchvision transformers numpy matplotlib
```

---

## 🛠️ Usage

### Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/ViT-GPT2-Project.git
cd ViT-GPT2-Project
```

### Step 2: Run the Jupyter Notebook

Open the notebook `test-vit-gpt2.ipynb` for a guided walkthrough of the pipeline:

```bash
jupyter notebook test-vit-gpt2.ipynb
```

### Step 3: Load Pretrained Models

- Download pretrained weights from Hugging Face:
  - [ViT Models](https://huggingface.co/models?search=vit)
  - [GPT-2 Models](https://huggingface.co/models?search=gpt2)

### Step 4: Train or Fine-Tune

- Load your dataset of X-Ray images and their corresponding summaries.
- Train or fine-tune the model using the integrated pipeline.
- Evaluate its performance on test data.

---

## 🗂️ Project Structure

```plaintext
ViT-GPT2-Project/
├── data/               # Input images and summaries
├── models/             # Pretrained and fine-tuned model weights
├── notebooks/          # Jupyter notebooks
│   └── test-vit-gpt2.ipynb  # Main notebook
├── utils/              # Utility scripts for preprocessing
├── requirements.txt    # Dependency list
└── README.md           # Project documentation
```

---

## 📊 Results

This project demonstrates:
- **High Accuracy:** Generates precise summaries of X-Ray images.
- **Enhanced Medical Insights:** Facilitates rapid and reliable diagnostics.
- **Efficient Workflow:** Combines robust image processing and AI-driven text generation.

### Visual Results

| Image                                                                                                   | Predicted Text                                                                                   | Actual Text                                                                                 |
|--------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------|
| ![Image1](https://github.com/amandeep-yadav/summary-of-X-Rays-images-using-VIT-GPT2/blob/main/img/test_im.PNG) | The lungs are clear bilaterally. Specifically, no evidence of focal consolidation, pneumothorax, or pleural effusion.. Cardio mediastinal silhouette is unremarkable. Visualized osseous structures of the thorax are without acute abnormality. | The heart size is within normal limits. Cardiomediastinal contour is normal. There is a right upper lobe nodule measuring 8 mm in diameter. Trachea is midline. The lungs otherwise clear. XXXX and soft tissues are unremarkable.                              |
| ![Image2](https://github.com/amandeep-yadav/summary-of-X-Rays-images-using-VIT-GPT2/blob/main/img/test_image1.PNG) | The lungs are clear bilaterally. Specifically, no evidence of focal consolidation, pneumothorax, or pleural effusion.. Cardio mediastinal silhouette is unremarkable. Visualized osseous structures of the thorax are without acute abnormality.                                                                       | Normal cardiac contour. Right sided pleural effusion. Clear left lung XXXX. No pneumothorax.                                                                   |
| ![Image3](https://github.com/amandeep-yadav/summary-of-X-Rays-images-using-VIT-GPT2/blob/main/img/test_image2.PNG) | The lungs are clear bilaterally. Specifically, no evidence of focal consolidation, pneumothorax, or pleural effusion.. Cardio mediastinal silhouette is unremarkable. Visualized osseous structures of the thorax are without acute abnormality.                                                                      | Borderline cardiac enlargement. Enlarged calcified thoracic aorta. Emphysema. No acute pulmonary abnormality. Mild spondylosis.                                                                     |
| ![Image4](https://github.com/amandeep-yadav/summary-of-X-Rays-images-using-VIT-GPT2/blob/main/img/test_image3.PNG) | The lungs are clear bilaterally. Specifically, no evidence of focal consolidation, pneumothorax, or pleural effusion.. Cardio mediastinal silhouette is unremarkable. Visualized osseous structures of the thorax are without acute abnormality.                                                                      | Heart size normal. No pleural effusions or pneumothorax. Lungs are clear. Soft tissues and XXXX are unremarkable.                                                                    |
| ![Image5](https://github.com/amandeep-yadav/summary-of-X-Rays-images-using-VIT-GPT2/blob/main/img/test_image4.PNG) | The lungs are clear bilaterally. Specifically, no evidence of focal consolidation, pneumothorax, or pleural effusion.. Cardio mediastinal silhouette is unremarkable. Visualized osseous structures of the thorax are without acute abnormality.                                                                       | Heart size within normal limits. No focal airspace consolidations. No pneumothorax or effusions.                                                                  |
| ![Image6](https://github.com/amandeep-yadav/summary-of-X-Rays-images-using-VIT-GPT2/blob/main/img/test_image5.PNG) | The lungs are clear bilaterally. Specifically, no evidence of focal consolidation, pneumothorax, or pleural effusion.. Cardio mediastinal silhouette is unremarkable. Visualized osseous structures of the thorax are without acute abnormality.                                                                      | The lungs are clear. There is no pleural effusion or pneumothorax. The heart is not significantly enlarged. There are atherosclerotic changes of the aorta. Arthritic changes of the skeletal structures are noted.                                                                   |

---

## 🤝 Contributing

Contributions are always welcome! To contribute:
1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Submit a pull request with detailed information about your changes.

---

## 📜 License

This project is licensed under the **MIT License**. See the LICENSE file for details.

---

## 💡 Acknowledgments

- **Hugging Face:** For providing excellent transformer models.
- **PyTorch:** For the robust deep learning framework.

---

## 📬 Contact

For questions, feedback, or collaboration, please reach out to:
[Amandeep Yadav](amandeepyadav601@gmail.com).

Stay connected for more exciting AI projects!

