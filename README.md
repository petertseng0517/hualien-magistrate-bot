# 🏛️ Magistrate Response Generator (縣長回應生成器)

> **"這完全是中央政府的責任呀！"**

一個基於 LLM 的諷刺型聊天機器人，模擬地方首長在面對質詢時的「官腔」與「推諉」藝術。
本專案源自於學校作業：「做一個有趣又符合真實世界需求的 Chatbot」，於是我選擇了最真實的...政治修辭。

## 🔗 Live Demo
👉 **[點此體驗 (Hugging Face Space)](https://huggingface.co/spaces/petertsengtw/hualien_gov)**

## ✨ 特色 (Features)

* **沉浸式人設**：模擬地方首長第一人稱視角，語氣溫和但立場堅定（地甩鍋）。
* **太極大師**：無論使用者輸入什麼問題（地震、交通、預算），AI 都能優雅地將責任歸屬導向「中央政府」。
* **情緒穩定**：保持官場禮儀，用最客氣的話說最不負責任的內容。

## 🛠️ 技術架構 (Tech Stack)

* **Model Provider**: [Groq API](https://groq.com/) (Llama-3.1-8b-instant) - 追求極速生成回應。
* **Framework**: [Gradio](https://www.gradio.app/) - 快速建構 Web UI。
* **Prompt Engineering**: 精心設計的 System Prompt，確保角色性格的一致性 (Persona Consistency)。

## 🚀 如何在本地執行 (Run Locally)

如果你想在自己的電腦上測試這個專案：

1. **Clone 專案**
   ```bash
   git clone [https://github.com/petertseng0517/hualien_gov.git](https://github.com/petertseng0517/hualien_gov.git)
   cd hualien_gov
