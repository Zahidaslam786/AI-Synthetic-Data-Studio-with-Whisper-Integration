# 🤖 AI Synthetic Data Studio: Multimodal Data Orchestration

A professional-grade **Synthetic Data Generator** powered by quantized LLMs (**Llama 3.2 & Phi-4**) and **OpenAI Whisper**. This studio allows users to generate high-fidelity, diverse datasets for testing and research using voice or text commands, all optimized for **T4 GPUs**.

## 🚀 Key Technical Features
- **Whisper Transcription**: Integrated audio processing to convert voice prompts into structured data requests.
- **Advanced Inference**: Utilizes **Llama 3.2 (3B)** and **Phi-4** with **4-bit NF4 Quantization** for high-speed local inference.
- **Real-time Streaming**: Implemented `TextIteratorStreamer` with multi-threading for a responsive, lag-free UI.
- **Dynamic UI/UX**: Professional dashboard built with **Gradio**, featuring custom CSS and dual-model selection.

## 🛠️ The Workflow
1. **Input**: User provides a prompt via voice (Whisper) or text.
2. **Quantized Processing**: The 4-bit model processes the request to ensure privacy and efficiency.
3. **Data Synthesis**: Generates diverse data points (JSON/Table) ranging from technical catalogs to medical trials.
4. **Output**: Instant rendering of synthetic datasets with a focus on diversity and instruction following.

## 📊 Visual Benchmarks (Agent Outputs)

### 🇵🇰 Test Case: Local Currency Diversity (PKR)
This output demonstrates the model's ability to localize data, generating employee records with salaries in Pakistani Rupees and diverse local cities.
<div align="center">
  <img src="https://github.com/user-attachments/assets/554e7737-e3bd-466d-a0b1-ed87d8a783d9" width="90%" />
  <p><i>Synthetic Employee Records with PKR Salaries and Local City Diversity.</i></p>
</div>

### 💵 Test Case: Global Logistics (USD)
Testing global instruction following, the model generates technical technical inventory with international pricing in Dollars.
<div align="center">
  <img src="https://github.com/user-attachments/assets/d3f8d1b0-625f-4754-9a7e-bddd1a103669
" width="90%" />
  <p><i>Technical Inventory Generation with Dollar-based Pricing.</i></p>
</div>

## 🔧 Tech Stack
- **Models**: Llama 3.2-3B, Phi-4 Mini, Whisper.
- **Libraries**: Transformers, BitsAndBytes (4-bit), Gradio, PyTorch.
- **Hardware**: Optimized for **NVIDIA T4 GPU**.

---
*Developed by Muhammad Zahid Aslam | FAST-NUCES*
