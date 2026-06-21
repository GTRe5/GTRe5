<div align="center">

# 👋 Hi, I'm GTRe5

### Data Analyst · Machine Learning Engineer · Deep Learning Enthusiast

📍 Vietnam &nbsp;·&nbsp; 🎓 Ton Duc Thang University &nbsp;·&nbsp; 📫 hungpro123b@gmail.com

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pqh2005)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=vercel&logoColor=white)](https://portfolio-gtre5.vercel.app/)
[![Profile Views](https://komarev.com/ghpvc/?username=GTRe5&style=flat-square&color=orange)](https://github.com/GTRe5)

</div>

---

## 🧠 About Me

- 💡 Passionate about **Data**, **AI**, and building intelligent systems
- 🔍 Interested in: **NLP**, **Computer Vision**, **Recommendation Systems**
- 🚀 Goal: Become an **AI Engineer / Data Scientist**
- 🌱 Currently learning: MLOps, model deployment, LLM fine-tuning

---

## ⚡ Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-003B57?style=flat-square&logo=postgresql&logoColor=white)

**Data & ML**

![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)

**Tools**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=white)

---

## 📂 Featured Projects

![Banner](./assets/logo_hagrid.jpg)

### 🤚 [HaGRID - Hand Gesture Recognition](https://github.com/GTRe5/hagrid-gesture-recognition)

[![Python 3.12](https://img.shields.io/badge/Python-3.12.3-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![timm](https://img.shields.io/badge/timm-EfficientNet-0081C9?style=flat-square&logo=huggingface&logoColor=white)](https://github.com/huggingface/pytorch-image-models)
[![Dataset](https://img.shields.io/badge/Dataset-HaGRID-22C55E?style=flat-square&logo=huggingface&logoColor=white)](https://huggingface.co/datasets/GestureDetectionConnoisseurs/hagrid_subsets)
[![Model](https://img.shields.io/badge/Model-EfficientNet--B0-F97316?style=flat-square&logo=huggingface&logoColor=white)](https://huggingface.co/timm/efficientnet_b0.ra_in1k)

📌 Real-time hand gesture classification from webcam using **EfficientNet-B0** fine-tuned on the HaGRID dataset (34 gesture classes).  
⚙️ Tech: PyTorch, timm, HuggingFace Datasets, OpenCV  
📊 Achievements:
- Fine-tuned EfficientNet-B0 with 2-phase freeze/unfreeze training strategy
- Achieved **97.8% validation accuracy** across 34 gesture classes
- Built a real-time webcam HUD demo with top-K predictions and FPS counter

---

![Banner](./assets/logo_pixel.svg)

### 🖼️ [PixelNarrator - AI Image Captioning (COCO)](https://github.com/GTRe5/Image-Captioning-COCO)

[![Python 3.12](https://img.shields.io/badge/Python-3.12.3-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-2.0%2B-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)](https://pytorch.org/)
[![Dataset](https://img.shields.io/badge/Dataset-MS%20COCO%202017-5C9BD6?style=flat-square&logo=microsoftazure&logoColor=white)](https://cocodataset.org/)
[![Gradio](https://img.shields.io/badge/Demo-Gradio-FF7C00?style=flat-square&logo=gradio&logoColor=white)](https://gradio.app/)

📌 End-to-end image captioning system combining **CNN + LSTM + Bahdanau Attention** - generates natural-language descriptions with per-word attention heat-maps.  
⚙️ Tech: PyTorch, ResNet-50, NLTK, Gradio  
📊 Achievements:
- Improved BLEU score with soft spatial Attention mechanism
- Benchmarked 4 ablation configs (baseline → pretrained encoder → attention → full model)
- Built interactive Gradio demo with clipboard paste and attention heat-map visualisation

---
![Banner](./assets/logo_trend.svg)

### 📈 [TrendScope - Real-time GitHub Trending Dashboard](https://github.com/GTRe5/TrendScope)

[![Python 3.12](https://img.shields.io/badge/Python-3.12.3-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)](https://streamlit.io/)
[![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white)](https://plotly.com/)
[![BeautifulSoup4](https://img.shields.io/badge/BeautifulSoup4-59666C?style=flat-square&logo=python&logoColor=white)](https://www.crummy.com/software/BeautifulSoup/)
[![ngrok](https://img.shields.io/badge/ngrok-1F1E37?style=flat-square&logo=ngrok&logoColor=white)](https://ngrok.com/)

📌 A live GitHub Trending dashboard that scrapes and visualises trending repositories in real time - **no API key required**. Features an interactive dark-orange themed UI with bar charts, daily star rankings, and KPI summaries.  
⚙️ Tech: Streamlit, Plotly, BeautifulSoup4, ngrok, Python  
📊 Achievements:
- Built a zero-auth scraper using **BeautifulSoup4** to pull live GitHub trending data without any API token
- Designed interactive **Plotly** bar charts ranking repositories by daily stars gained
- Exposed the local Streamlit app publicly via **ngrok** tunnel for easy live sharing
- Developed a custom dark-orange dashboard theme with a KPI strip (repos count, total stars, stars gained, top language)

---

![Banner](./assets/logo_snip.png)

### 🔗 [Snipline - Real-Time URL Shortener](https://github.com/GTRe5/Snipline)

[![Next.js](https://img.shields.io/badge/Next.js-16-000000?style=flat-square&logo=nextdotjs&logoColor=white)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-v4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
[![Upstash Redis](https://img.shields.io/badge/Upstash-Redis-00E9A3?style=flat-square&logo=redis&logoColor=white)](https://upstash.com/)

📌 Real-time URL shortener built with **Next.js 16** (App Router) and **TypeScript** - paste a long link, get a short one back instantly, with custom aliases, live click tracking, and a full link ledger. Ready to deploy on **Vercel** in minutes.  
⚙️ Tech: Next.js 16, TypeScript, Tailwind CSS v4, Framer Motion, Upstash Redis  
📊 Achievements:
- Built short-code generation and click-tracked redirects entirely server-side with Next.js Server Components
- Implemented persistent storage via **Upstash Redis**, with an automatic in-memory fallback for local dev
- Added custom aliases, per-IP rate limiting, and a collision-safe **nanoid**-based code generator
- Engineered a real-time link ledger with live click-count polling and **Framer Motion** animations

---

## 📊 GitHub Analytics

<div align="center">

<!-- Streak + total contributions (demolab - very stable) -->
[![GitHub Streak](https://streak-stats.demolab.com/?user=GTRe5&theme=gruvbox&hide_border=true)](https://git.io/streak-stats)

<!-- Profile Summary Cards - languages by repo count + most committed language -->
| ![Repos by Language](https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=GTRe5&theme=gruvbox) | ![Most Commit Language](https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=GTRe5&theme=gruvbox) |
| --- | --- |

<!-- Full profile overview card -->
![GitHub profile overview card](https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=GTRe5&theme=gruvbox)

<!-- Trophies -->
[![trophy](https://github-profile-trophy.vercel.app/?username=GTRe5&theme=gruvbox&no-frame=true&row=1&column=6)](https://github.com/ryo-ma/github-profile-trophy)

![GitHub Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=GTRe5&theme=gruvbox&hide_border=true)

</div>

---

## 🏆 Highlights

- 🤚 Real-time gesture recognition with **97.8% val accuracy** (34 classes, EfficientNet-B0)
- 🖼️ End-to-end image captioning pipeline on **COCO** with Attention mechanism
- 📦 Big data processing with **PySpark + Hadoop** on market basket datasets
- 🔬 Hands-on experience with **COCO**, **HaGRID**, **DAQUAR**, and custom datasets

---

<div align="center">

⭐️ From **GTRe5** - Building AI for the future 🚀

</div>