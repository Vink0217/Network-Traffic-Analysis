# 🛡️ Network Traffic Analysis for Cybersecurity

This project focuses on analyzing network traffic data to detect and classify cybersecurity threats using machine learning techniques. It provides a foundational approach to building an Intrusion Detection System (IDS) using real-world datasets like CICIDS2017 and tools like Wireshark.

---

## 🚀 Features

- 📊 **Traffic Pattern Analysis** to identify anomalies and suspicious behavior
- 🤖 **Machine Learning Models** (Random Forest, Neural Networks) for threat classification
- ⚠️ Detection of threats such as **DDoS, Brute Force, Port Scans, and Phishing**
- 🧪 Uses **real-world network data** (CICIDS2017) for model training and evaluation
- 🛠️ Hands-on traffic capture and inspection using **Wireshark**
- 📈 Visualizations of data distribution, model performance, and confusion matrices

---

## 🧰 Tools & Technologies

- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- Jupyter Notebook
- Wireshark (for manual traffic inspection)
- CICIDS2017 Dataset (https://www.unb.ca/cic/datasets/ids-2017.html)

---

## 📁 Project Structure

network-traffic-analysis/
├── network_traffic_analysis.ipynb # Main analysis notebook
├── requirements.txt # Python dependencies
├── README.md # Project documentation
└── .gitignore # File exclusions


---

## ⚙️ Installation

1. **Clone the repository**

```bash
git clone https://github.com/Vink0217/network-traffic-analysis.git
cd network-traffic-analysis
```

2. **Install dependencies**
```bash
pip install -r requirements.txt
```

3. Open the notebook
```bash
jupyter notebook network_traffic_analysis.ipynb
```

## 📊 Sample Models Used

  ✅ Random Forest Classifier

  ✅ Neural Network (Multi-Layer Perceptron)

## 📊 Visual Results
🔹 Confusion Matrix
Add your confusion matrix image here.


🔹 Network Traffic Pattern Visualization
Include PCA, t-SNE, or any clustering visualization.


🔹 Model Accuracy & Performance Plots
Add line/bar charts showing model accuracy, precision, recall, etc.

## 📚 Dataset

CICIDS2017 – A comprehensive dataset containing benign and malicious traffic samples.

Download link: [UNB CIC IDS 2017](https://www.unb.ca/cic/datasets/ids-2017.html)

## 📌 Notes

Large .csv files are excluded via .gitignore. Add your dataset locally before running.

Wireshark is used outside this notebook to inspect packet details and capture live traffic.

## 🤝 Contributing

Feel free to fork, improve, or extend the project! Pull requests are welcome.

---

### 📁 Folder Tip for GitHub:

Create a folder named `images/` in your project directory and place your PNGs/JPGs inside it:

```bash
mkdir images
```
Save your figures from Jupyter like this:
```bash
plt.savefig("images/confusion_matrix.png")
```



