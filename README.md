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

```plaintext
ai-ppt-generator/
│
├── ppt_generator/
│   ├── __init__.py
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

```

⚡ Installation
```
git clone https://github.com/JeswinJestin/GenAI_PPT_Generator.git
cd GenAI_PPT_Generator
pip install -r requirements.txt
```

🔑 Setup & Usage

You’ll need:

A Google Gemini API key for content generation

(Optional) An image API key (e.g. Pexels) for downloading images

Sample code:
```
from ppt_generator import PPTGenerator  # or adapt to your package path

generator = PPTGenerator(api_key="YOUR_GEMINI_API_KEY")
generator.generate_presentation(
    topic="Artificial Intelligence",
    num_slides=6,
    output_path="ai_presentation.pptx"
)
```

You can also run and test using the Jupyter notebook: PPT_Generator.ipynb.

🎯 Example (Colab / Notebook)

Open and try the example notebook:
PPT_Generator.ipynb in the repository.

🛠 Dependencies
```
Python 3.9+

python-pptx

google-generativeai

Pillow

requests

Install via:

pip install -r requirements.txt
```
📸 Demo



🚀 Future Work / Roadmap
 ```
Improve prompt engineering for more creative slides

Add theme / style templates (colors, fonts, layouts)

More image sources & fallback visuals

Support for PowerPoint animations / transitions

Add unit tests & CI pipeline
```
🤝 Contributing

We welcome contributions! Here’s how to get started:
```
Fork the repo

Create a branch: git checkout -b feature/YourFeature

Make your changes & commit: git commit -m "Add feature …"

Push branch: git push origin feature/YourFeature

Open a Pull Request

Please follow conventional commit messages and write clean, documented code.
```
📜 License

This project is open source.


🌟 Support & Acknowledgements

If you found this project useful, please give it a ⭐ on GitHub!
Feel free to open issues or request features — happy to collaborate.
