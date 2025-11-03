🛡️ Cyber-Attack Detection with QR Code Images using Lightweight Deep Learning

This project presents an intelligent cybersecurity system designed to detect malicious QR codes using a lightweight deep learning architecture (MobileNetV2) optimized by a Genetic Algorithm (GA).
The system achieved 92% accuracy while maintaining low computational cost — making it ideal for real-time protection on mobile and IoT devices.



🧭 Project Overview

QR codes are widely used in digital payments and authentication systems — but attackers exploit them to deliver phishing links or malware.
This project aims to detect and prevent cyber-attacks hidden in QR codes using artificial intelligence and feature optimization.

🎯 Objectives:
	•	🧩 Build a secure dataset of legitimate and malicious QR code images.
	•	🤖 Train a lightweight deep learning model (MobileNetV2) for detection.
	•	🧬 Apply Genetic Algorithm to enhance feature selection and accuracy.
	•	⚡ Optimize performance for real-time mobile and IoT security systems.

“This approach contributes to safer digital interactions by securing QR-based systems against modern cyber threats.”


🧠 Methodology
	1.	🗂️ Dataset Preparation
	•	200,000 QR images (100K safe, 100K malicious).
	•	Resized to 64×64×3 and split (80% train / 20% test).
	2.	🧩 Feature Extraction
	•	MobileNetV2 used for extracting deep visual features from QR codes.
	3.	🧬 Feature Optimization
	•	Genetic Algorithm used to select the most critical security-related features.
	4.	🔍 Attack Detection
	•	Support Vector Machine (SVM) classifies QR codes as safe or malicious.



🧰 Tools & Technologies
	•	🐍 Python — main programming language
	•	🧠 TensorFlow / Keras — deep learning framework
	•	🔍 Scikit-learn / OpenCV — image and feature analysis
	•	🧬 DEAP — Genetic Algorithm library
	•	💻 Jupyter Notebook — development and testing environment



📊 Results
	•	✅ Accuracy: 92%
	•	🔁 Precision / Recall / F1-score: Consistent across metrics
	•	⚡ Efficiency: Reduced computational cost compared to standard CNNs
	•	🔐 Security Impact: Detects malicious QR codes instantly before exploitation

💡 The model successfully strengthens QR-based communication security while remaining lightweight and efficient.



🚀 How to Run the Project
	1.	🧱 Clone this repository:
git clone https://github.com/hsssonii/Cyber-Attack-Detection-with-QR-Codes.git
	2.	⚙️ Install dependencies:
pip install -r requirements.txt
	3.	💡 Run the notebook:
jupyter notebook cyber-attack-detection-with-qr-code-images-using-l.ipynb



🔮 Future Enhancements

	•	🧩 Integrate the model into real-time QR scanning systems to detect threats instantly.
	•	🔐 Combine AI-based detection with cybersecurity threat intelligence to block malicious URLs.
	•	☁️ Deploy the model in a secure cloud environment for large-scale QR code monitoring.
	•	🧠 Enhance robustness against adversarial attacks targeting QR code manipulation.   
      •     📱 Develop an Android application using TensorFlow Lite to enable real-time QR scanning and on-device cyber-attack detection.



📚 References

Research based on the graduation project supervised by Prof. Mohammed Ayoub,
University of Bisha — Cybersecurity Department (2025).



🕵🏻‍♂️ Authors
	•	Hassan Alamri
	•	Eiad Alqarni
