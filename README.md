# Brain Tumor MRI Image Classification

This project focuses on building a deep learning model to classify MRI images of the brain into two categories: tumor and no tumor. The model is based on transfer learning using the VGG16 architecture.

## 🛠 Technologies Used
- Python
- PyTorch
- VGG16 (Pretrained on ImageNet)

## 📚 Project Steps
1. **Data Loading:** Imported the MRI brain tumor dataset.
2. **Preprocessing:** Resized images and applied necessary transformations.
3. **Model Building:** Used VGG16 with transfer learning:
   - Frozen the convolutional layers.
   - Modified the classifier to fit the binary classification task.
4. **Training:** Trained the model using PyTorch’s training loop (forward pass, backward pass, optimization).
5. **Evaluation:** Evaluated the model performance using metrics like accuracy and loss.
6. **Prediction:** Used the model to predict new unseen MRI images.

## 🎯 Objective
To create a reliable and efficient model capable of detecting brain tumors from MRI images using deep learning.

## 🚀 How to Run
1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/brain-tumor-mri-classification.git
    ```
2. Install the required libraries:
    ```bash
    pip install torch torchvision matplotlib numpy
    ```
3. Run the notebook:
    Open `Brain_Tumor_MRI_Image_Classification.ipynb` in Jupyter Notebook or any compatible IDE.

## 📈 Results
- Achieved strong performance during both training and testing.
- The model successfully differentiates between tumor and no tumor images.

## 🤝 Contribution
Contributions are welcome! Feel free to open issues and pull requests.
