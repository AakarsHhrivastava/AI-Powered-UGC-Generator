# AI-Powered-UGC-Generator
# 🖼️ AI-Powered UGC Generator (n8n + Google Nano Banana)

Turn boring **product photos on plain backgrounds** into **photorealistic lifestyle UGC images** – powered by **n8n** + **Google’s Nano Banana model**.

## 🚀 What it Does
- Upload a plain product photo (e.g., dress on white background).
- Workflow calls **Google Nano Banana API** via n8n.
- Outputs a **high-quality lifestyle image** of the product in use.
- All automated – no Photoshop, no Canva. Just AI + automation.

## ⚙️ Tech Stack
- **n8n** → Workflow orchestration  
- **Google Nano Banana API** → AI-powered image generation  
- **OpenRouter API** (optional) → API gateway  
- **Node.js / JSON** → Workflow configuration  

## 📸 Example
| Input (Plain) | Output (Lifestyle) |
|---------------|---------------------|
![e0945f2199a1d5b000d6a9c370246b3d](https://github.com/user-attachments/assets/894ca847-b724-48ea-91ef-f3663d7c2fe3)|![](https://github.com/user-attachments/assets/a907a85b-829e-4f5f-910d-23f6ca276d1b)


## 🏗️ How it Works
1. User uploads a product image via form.  
2. n8n parses the file and calls Google Nano Banana API.  
3. API processes and returns lifestyle UGC.  
4. Workflow outputs final images + logs results.  

![](docs/workflow-diagram.png)

## 💡 Potential Use Cases
- E-commerce brands → quick lifestyle visuals for catalogs  
- Marketing teams → ad creatives in seconds  
- Agencies → scalable product creative generation  
- Startups → reduce GTM (go-to-market) time  

