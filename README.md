# 🚀 DDoS Attack Detection System  

Hey there! 👋 This project is focused on detecting **DDoS attacks** using **machine learning**. It analyzes different types of network attacks, such as **ICMP Flood, TCP SYN Flood, and UDP Flood**, using a dataset derived from **KDDCup**.  

By leveraging **Python, Scikit-learn, and Jupyter Notebooks**, this system classifies network traffic and identifies potential attacks in real-time. Let’s dive in!  

---

## 📌 What's Inside?  

### 🔍 **Attack Detection Notebooks**  
Each Jupyter Notebook analyzes a specific type of DDoS attack:  
- **📄 `icmp_attack-checkpoint.ipynb`** → Detects ICMP Flood attacks  
- **📄 `tcp_syn_attack-checkpoint.ipynb`** → Detects TCP SYN Flood attacks  
- **📄 `udp_attack-checkpoint.ipynb`** → Detects UDP Flood attacks  

### 📊 **Dataset (`revised_kddcup_dataset.csv`)**  
A **cleaned and modified version of the KDDCup dataset**, containing both normal and malicious network traffic samples.  

### ⚡ **Machine Learning Models**  
The project uses different ML techniques to classify attacks:  
- **Random Forest** 🌳  
- **Support Vector Machine (SVM)** 🎯  
- **Gradient Boosting** 🚀  

---

## 🚀 How to Get Started  

### 1️⃣ **Clone the Repository**  
```bash
git clone https://github.com/Megaraj-P/ddos-detection.git
cd ddos-detection
```

### 2️⃣ **Set Up Your Environment**  
Install dependencies using:  
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

### 3️⃣ **Run the Notebooks**  
Open **Jupyter Notebook** and run the individual `.ipynb` files to analyze each attack type.  

```bash
jupyter notebook
```

---

## 🎯 Example  

### 📥 **Input:** *(Captured Network Traffic Features)*  
🛜 Packet details including **source IP, destination IP, protocol, flag values, and data rates**.  

### 📤 **Output:** *(Attack Classification)*  
✅ **Normal Traffic**  
🚨 **ICMP Flood Detected**  
🚨 **TCP SYN Attack Detected**  
🚨 **UDP Flood Detected**  

---

## 🛠 Built With  

🔹 **Python** – Core programming language  
🔹 **Scikit-learn** – Machine learning models  
🔹 **Pandas & NumPy** – Data processing  
🔹 **Matplotlib & Seaborn** – Visualization  
🔹 **Jupyter Notebook** – Code execution & analysis  

---

## 🔥 What's Next?  

🔜 Implementing **real-time network traffic monitoring**  
🔜 Enhancing **feature selection for better accuracy**  
🔜 Developing a **web-based dashboard** for easier monitoring  

---

## 👨‍💻 About Me  

Hi! I’m **Megaraj P** 👋, a cybersecurity enthusiast passionate about AI-driven network security. Let’s connect!  

🔗 **GitHub:** [Megaraj P](https://github.com/Megaraj-P)  

---

## 📜 License  

This project is licensed under the **MIT License**. Feel free to use and improve it! 🚀  

---

Let me know if you'd like any further modifications! 😊
