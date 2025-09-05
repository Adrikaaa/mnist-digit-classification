# MNIST Handwritten Digit Classifier

Beginner-friendly TensorFlow/Keras project classifying digits (0–9) using the MNIST dataset.

## Repository Structure
- `mnist_dense.ipynb` — Jupyter notebook for training & evaluation  
- `mnist_dense.keras` — Saved trained model (native Keras format)  
- `requirements.txt` — Python dependencies  
- `.gitignore` — (to exclude unnecessary files)

## Setup & Run
```bash
git clone https://github.com/Adrikaaa/mnist-digit-classification.git
cd mnist-digit-classification
python -m venv venv
source venv/bin/activate            # or venv\Scripts\activate on Windows
pip install -r requirements.txt
jupyter notebook mnist_dense.ipynb
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/a82012ee-f9a2-4b7e-bd7e-5bab6b031170" />
