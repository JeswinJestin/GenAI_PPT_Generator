# GenAI_PPT_Generator
“Transforming ideas into professional presentations with the power of AI.”

---

```markdown
# 🎨 AI PPT Generator

> *Transforming ideas into professional presentations with the power of AI.*  
> *A case study and open-source project demonstrating AI-powered PowerPoint generation with Google Gemini.*

---

## 📖 Case Study Theme

### 🎯 Problem
Creating professional, well-structured presentations often takes **hours of manual effort**.  
Students, educators, and professionals spend more time **designing slides** than **communicating ideas**.

### 💡 Solution
**AI PPT Generator**:
- Converts **any topic** into a **structured deck** in seconds.
- Generates **titles, bullet points, images, and conclusion slides**.
- Adds **speaker notes** and **design hints** for better delivery.
- Suggests **relevant images** with optional API integration.
- Works seamlessly in **Google Colab** or local Python.

### 📊 Use Cases
- 🎓 **Education** – Quick lecture slides for teachers & students.  
- 💼 **Business** – Agile pitch decks & meeting presentations.  
- 🔬 **Research** – Simplified sharing of technical findings.  

---

## ✨ Features
✅ AI-generated **slide outlines** from any topic  
✅ Supports **title, content, image, and conclusion** slide types  
✅ **Speaker notes + design hints** per slide  
✅ Optional **image suggestions** via external APIs  
✅ Works in **Google Colab** and local Python  

---

## 📂 Project Structure
```

ai-ppt-generator/
│
├── ppt_generator/
│   ├── **init**.py
│   ├── ppt_generator.py       # Core PPTGenerator class
│
├── examples/
│   ├── generate_sample_ppt.ipynb   # Jupyter/Colab demo
│
├── docs/
│   ├── demo.gif               # (Optional) Demo screen recording
│
├── requirements.txt
├── README.md
└── LICENSE

````

---

## ⚡ Installation

Clone the repo and install dependencies:

```bash
git clone https://github.com/your-username/ai-ppt-generator.git
cd ai-ppt-generator
pip install -r requirements.txt
````

---

## 🔑 Setup

You’ll need:

* **Google Gemini API key** (for AI content generation)
* *(Optional)* An image API key (e.g., Pexels) for slide illustrations

Set them in your code:

```python
from ppt_generator.ppt_generator import PPTGenerator

generator = PPTGenerator(api_key="YOUR_GEMINI_API_KEY")
generator.generate_presentation(
    topic="Artificial Intelligence",
    num_slides=6,
    output_path="ai_presentation.pptx"
)
```

---

## 🎯 Example Usage (Colab)

Try it directly in Google Colab:
👉 [Open Notebook Example](examples/generate_sample_ppt.ipynb)

---

## 🛠 Requirements

* Python 3.9+
* `python-pptx`
* `google-generativeai`
* `Pillow`
* `requests`

Install via:

```bash
pip install -r requirements.txt
```

---

## 📸 Demo

![Demo GIF](docs/demo.gif)
*(Replace with your Colab screen recording or screenshots)*

---

## 🤝 Contributing

Contributions are welcome! 🎉
Here’s how you can help:

1. Fork the repo
2. Create your feature branch (`git checkout -b feature/awesome-idea`)
3. Commit changes (`git commit -m 'Add awesome idea'`)
4. Push to the branch (`git push origin feature/awesome-idea`)
5. Open a Pull Request 🚀


## 🌟 Support

If you find this project useful, please give it a ⭐ on GitHub!
For issues or feature requests, open an [issue](../../issues).

```

