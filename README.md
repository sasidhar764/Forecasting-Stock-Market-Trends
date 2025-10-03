# Financial Forecasting with Multimodal Fusion and Cross-Modal Attention  

This work introduces a **approach to financial forecasting** by implementing and evaluating an **advanced multimodal fusion architecture with a cross-modal attention mechanism**. Unlike traditional methods that simply concatenate numerical and textual features, our approach enables the model to **dynamically learn the context-specific importance of news sentiment relative to market conditions**. This results in a more **sophisticated and potentially more accurate** integration of qualitative (news-driven) and quantitative (market-driven) data sources.  

---

## 📊 Models Evaluated  

To establish a controlled benchmark, we evaluate multiple architectures on the multimodal dataset:  

- **LightGBM** – A classical gradient boosting model for baseline performance.  
- **Multi-Layer Perceptron (MLP)** – A foundational deep learning model to assess nonlinear interactions.  
- **Sequential (LSTM)** – An advanced sequential model designed to capture temporal dependencies in financial data.  

This comparative evaluation highlights which architectures are best suited for integrating **traditional financial indicators** with **modern NLP-derived sentiment features**.  

---

## 🔍 Ablation Studies for Explainability  

To validate the complexity and necessity of our proposed architecture, we perform **systematic ablation studies**. These experiments selectively remove key components—such as:  

- The **cross-modal attention mechanism**  
- **Sentiment features** from financial news  
- **Engineered financial indicators**  

This approach provides clear insights into the **contribution of each component** to overall forecasting performance, improving transparency and interpretability.  

---

## 🤖 Benchmarking Against Large Language Models  

We further benchmark our models against the **out-of-the-box capabilities of Qwen (LLM)** for sentiment classification. Using **zero-shot, one-shot, and few-shot inference**, we compare the performance of our specialized trained models against a **general-purpose LLM**.  

This offers a **novel comparison point** that not only contextualizes the effectiveness of our proposed models but also explores the **viability of LLMs in financial sentiment analysis with minimal fine-tuning**.  

---

## ✅ Key Contributions  

- A **multimodal fusion framework** with cross-modal attention for financial forecasting.  
- **Controlled benchmark** across classical, foundational, and sequential deep learning models.  
- **Ablation studies** for enhanced explainability.  
- **Comparative evaluation** against state-of-the-art Large Language Models.  
