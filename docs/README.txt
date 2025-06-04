AI-Generated Fingerprint Detection Using Machine Learning


Overview

This project detects AI-generated fingerprints using machine learning techniques. It includes training a deep learning model, testing fingerprint authenticity, and generating structured datasets for analysis. The project was executed using Kaggle’s resources due to high system requirements.


Features

✔️ Training Model (training-machine.ipynb) – Uses the SOCOFing dataset for training a deep learning fingerprint classifier.
✔️ Testing Model (testing-trained-model.ipynb) – Validates real and AI-generated fingerprints using the trained .h5 model.
✔️ Dataset Generator (dataset-generator.ipynb) – Converts captured fingerprint images into structured data suitable for ML training/testing.


Project Structure

AI-Fingerprint-Detection/  
│-- code/  
│   │-- training-machine.ipynb  
│   │-- testing-trained-model.ipynb  
│   │-- dataset-generator.ipynb  
│  
│-- dataset/  
│   │-- sample-images/ (stores AI-generated fingerprint images)  
│   │-- trained-model.h5 (saved model for testing)  
│  
│-- docs/  
│   │-- project-report.pdf  
│   │-- README.md  
│  
│-- LICENSE  


Installation & Usage

1️⃣ Clone the Repository:
git clone https://github.com/nandan-d-s/AI---Fingerprint---Detection.git
cd AI-Fingerprint-Detection

2️⃣ Set Up Dependencies (Install required Python libraries):
pip install -r requirements.txt

3️⃣ Run Code in Kaggle or Locally:
- Training: Open training-machine.ipynb in Kaggle.
- Testing: Use testing-trained-model.ipynb to validate fingerprints.
- Dataset Generation: Use dataset-generator.ipynb to preprocess images.


Requirements
- Python 3.x
- Kaggle (for execution)
- Libraries: TensorFlow, OpenCV, NumPy, Matplotlib


License
This project is released under the MIT License, allowing free use with attribution. See LICENSE for more details.

