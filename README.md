# 📧 Cold Email Generator

<img width="1920" height="820" alt="Screenshot (841)" src="https://github.com/user-attachments/assets/a94ccea7-29d1-4c18-bc48-5642f608165c" />

---

## 🔑 Setup Instructions

### 1️⃣ Get Your Groq API Key  
Generate an API key here:  
**https://console.groq.com/keys**

Update the value of `GROQ_API_KEY` inside `app/.env`.

---

## ⚙️ Installation & Running the App

### **1. Create a virtual environment**
```bash
python -m venv venv
````

### **2. Activate the virtual environment**

**Windows:**

```bash
venv\Scripts\activate
```

**Mac/Linux:**

```bash
source venv/bin/activate
```

### **3. Install uv**

```bash
pip install uv
```

### **4. Sync dependencies**

```bash
uv sync
```

### **5. Run the Streamlit app**

```bash
streamlit run app/main.py
```


