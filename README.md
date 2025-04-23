## Recipe Recommendation AI Agent

A Python-based AI agent that combines vector search and natural language generation to recommend simple recipes, powered by a custom fine-tuned Traditional Chinese model.

### Features
- **Database Management**: Import recipes from JSON to SQLite.
- **Recipe Search**: Query recipes by name or ingredients.
- **Smart Recommendations**: Generate concise recipe suggestions in Traditional Chinese.

### Tech Stack
- **Vector Search**: moka-ai/m3e-small embeddings + FAISS.
- **Language Model**: `Floravs/my-awesome-model` (based on LLaMA 3.2 3B, fine-tuned with LoRA on 5k samples from `chinese-dolly` dataset for Traditional Chinese).
- **Tools**: SQLite (storage), Gradio (interface).

### Usage
1. Install: `pip install -r requirements.txt`.
2. Prepare JSON recipe data (`dataset.json`).
3. Run the script and query via Gradio interface.

### Example
- Input: "Recommend a simple dish with chicken"
- Output: "Try 'Three Cup Chicken'. Ingredients: chicken, garlic, ginger. Steps: Stir-fry aromatics, simmer with chicken."

### Screenshot
![Gradio Interface](https://raw.githubusercontent.com/mofanchang/Recipe-Recommendation-AI-Agent/main/recipe.png)



## 食譜推薦 AI Agent

一個基於 Python 的 AI 代理，結合向量搜尋與自然語言生成，為使用者推薦簡單食譜，使用自訓練的繁體中文模型。

### 功能
- **資料庫管理**：從 JSON 匯入食譜至 SQLite。
- **食譜搜尋**：根據菜名或食材查詢相關食譜。
- **智能推薦**：生成繁體中文的簡潔食譜建議與做法。

### 技術
- **向量搜尋**：moka-ai/m3e-small 嵌入 + FAISS。
- **語言模型**：`Floravs/my-awesome-model`（基於 LLaMA 3.2 3B，使用 `chinese-dolly` 取 5k 資料集，以 LoRA 方式 Fine-tune 為繁體中文）。
- **工具**：SQLite（儲存）、Gradio（介面）。

### 使用
1. 安裝依賴：`pip install -r requirements.txt`。
2. 準備 JSON 食譜資料（`dataset.json`）。
3. 執行程式，透過 Gradio 介面查詢。

### 範例
- 輸入：「請推薦一道用雞肉做的簡單料理」
- 輸出：「推薦『三杯雞』。食材：雞肉、蒜頭、薑。做法：炒香配料，加入雞肉燉煮。」

### 介面截圖
![Gradio 介面](https://raw.githubusercontent.com/mofanchang/Recipe-Recommendation-AI-Agent/main/recipe.png)








