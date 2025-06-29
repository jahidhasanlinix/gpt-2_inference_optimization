# 🧠 GPT-2 Inference API Development

In this project, I used the HuggingFace GPT-2 model for inference using FastAPI and tested on Google Colab.

---

### 🚀 1. GPT-2 Inference Server-side (FastAPI + ngrok)

**Run this notebook to:**
- Load a GPT-2 model using the HuggingFace transformers library
- Test the FastAPI using ngrok

👉 [**GPT-2 Inference Server Google Colab**](https://colab.research.google.com/drive/1fREdBR0K0spA-kTzKdtM4Y0pL6quQola?usp=sharing)

### 🛠️ Features
- `/generate` endpoint for single-prompt inference
- `/batch_generate` endpoint for multi-prompt batch inference
- Build your own prototype or demos to further test it
- Experimenting with quantization, batching, and latency

---

### 🧪 2. API Client-end Testing

**Use this notebook to:**
- Send test requests to your public FastAPI endpoint
- Measure tokens generated and latency
- Support both single and batch inference calls

👉 [**Client-end Testing Google Colab**](https://colab.research.google.com/drive/1hrwb8K3Iu39WnI3yXZOVytAikQqjwPnS?usp=sharing)

---


### 🙌 Credits

Built with:

- ⚡ [FastAPI](https://fastapi.tiangolo.com/) – High-performance Python web framework for building APIs  
- 🤗 [Hugging Face Transformers](https://huggingface.co/transformers/) – State-of-the-art NLP models  
- 🧠 [Google Colab](https://colab.research.google.com/) – Free cloud notebooks with GPU support  
- 🌐 [ngrok](https://ngrok.com/) – Public URLs for localhost APIs
