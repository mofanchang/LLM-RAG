
## Recipe Recommendation AI Agent

A Python-based AI agent that combines vector search and natural language generation to recommend simple recipes.

### Features
- **Database Management**: Import recipes from JSON to SQLite.
- **Recipe Search**: Query recipes by name or ingredients.
- **Smart Recommendations**: Generate concise recipe suggestions and instructions.

### Tech Stack
- **Vector Search**: moka-ai/m3e-small embeddings + FAISS.
- **Language Model**: Qwen1.5-0.5B for response generation.
- **Tools**: SQLite (storage), Gradio (interface).

### Usage
1. Install: `pip install -r requirements.txt`.
2. Prepare JSON recipe data (`dataset.json`).
3. Run the script and query via Gradio interface.

### Example
- Input: "Recommend a simple dish with chicken"
- Output: "Try 'Three Cup Chicken'. Ingredients: chicken, garlic, ginger. Steps: Stir-fry aromatics, simmer with chicken."

### Dependencies
- sqlite3, sentence-transformers, faiss, transformers, torch, gradio

## 食譜推薦 AI Agent

一個基於 Python 的 AI 代理，結合向量搜尋與自然語言生成，為使用者推薦簡單食譜。

### 功能
- **資料庫管理**：從 JSON 匯入食譜至 SQLite。
- **食譜搜尋**：根據菜名或食材查詢相關食譜。
- **智能推薦**：生成簡潔的食譜建議與做法。

### 技術
- **向量搜尋**：moka-ai/m3e-small 嵌入 + FAISS。
- **語言模型**：Qwen1.5-0.5B 生成回應。
- **工具**：SQLite（儲存）、Gradio（介面）。

### 使用
1. 安裝依賴：`pip install -r requirements.txt`。
2. 準備 JSON 食譜資料（`dataset.json`）。
3. 執行程式，透過 Gradio 介面查詢。

### 範例
- 輸入：「請推薦一道用雞肉做的簡單料理」
- 輸出：「推薦『三杯雞』。食材：雞肉、蒜、薑。做法：炒香配料，加入雞肉燉煮。」

### 依賴
- sqlite3, sentence-transformers, faiss, transformers, torch, gradio


