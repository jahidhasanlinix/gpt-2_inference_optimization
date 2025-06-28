# 🧠 GPT-2 Inference API with FastAPI on Google Colab

This project demonstrates how to deploy a Hugging Face GPT-2 model for inference using FastAPI, hosted directly from a Google Colab notebook. It also includes a separate client notebook to test both single and batch inference via HTTP.

---

## 🚀 1. GPT-2 Inference Server (FastAPI + ngrok)

**Run this notebook to:**
- Load a GPT-2 model using Hugging Face Transformers
- Serve it using FastAPI
- Expose the API publicly using ngrok

👉 [**Open Inference Server Notebook**](https://colab.research.google.com/drive/1fREdBR0K0spA-kTzKdtM4Y0pL6quQola?usp=sharing)

### 🛠️ Features
- `/generate` endpoint for single-prompt inference
- `/batch_generate` endpoint for multi-prompt batch inference
- Automatic use of GPU (if available)
- Lightweight and ideal for prototyping & demos

---

## 🧪 2. API Client Notebook

**Use this notebook to:**
- Send test requests to your public FastAPI endpoint
- Measure tokens generated and latency
- Support both single and batch inference calls

👉 [**Open Client Test Notebook**](https://colab.research.google.com/drive/1hrwb8K3Iu39WnI3yXZOVytAikQqjwPnS?usp=sharing)

---

## 📣 3. Use Cases

⚡ Fast prototyping with Hugging Face models

🔌 Running inference APIs directly inside notebooks

🎓 Teaching, tutorials, and quick ML demos

🧪 Experimenting with quantization, batching, and latency

---

## 🙌 Credits

Built with:

- ⚡ [FastAPI](https://fastapi.tiangolo.com/) – High-performance Python web framework for building APIs  
- 🤗 [Hugging Face Transformers](https://huggingface.co/transformers/) – State-of-the-art NLP models  
- 🧠 [Google Colab](https://colab.research.google.com/) – Free cloud notebooks with GPU support  
- 🌐 [ngrok](https://ngrok.com/) – Public URLs for localhost APIs
