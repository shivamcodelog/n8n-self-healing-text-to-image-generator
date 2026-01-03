# Self-Healing Image Generation Pipeline (n8n)

A robust, production-grade AI image generation workflow that handles API failures gracefully using a Primary/Fallback architecture.

# Preview images
(/assets/image.png)


## 🚀 Features
- **Zero Cost:** Uses free tiers of Groq, Hugging Face, and Google Drive.
- **Smart Routing:** Detects API failures (503/404) instantly.
- **Auto-Fallback:** Switches from Flux.1 (Primary) to Stable Diffusion XL (Backup) automatically.
- **Prompt Enhancement:** Uses Llama 3 to rewrite simple prompts into detailed artistic descriptions.

## 🛠️ Tech Stack
- **Orchestration:** n8n (Self-Hosted via Docker)
- **AI Models:** Llama 3, Flux.1-Dev, SDXL
- **APIs:** Groq, Hugging Face Inference API

## 📦 How to Use
1. Import `workflow.json` into your n8n instance.
2. Set up credentials for:
   - Hugging Face (Read Access)
   - Groq Cloud
   - Google Drive
3. Activate and enjoy!
