# 🧩 系統架構與流程 (System Architecture & Workflow)

## 架構圖（可用文字說明）  
## Architecture Flow (Descriptive)

1. 資料輸入 (Data Input)  
2. 前處理 (Preprocessing)  
3. 模型推論 (Model Inference)  
4. 結果輸出或可視化 (Output or Visualization)

---

## 參數設計 (Parameter Configuration)

- `threshold`：控制過濾強度（預設值 0.5）  
  _Controls filtering sensitivity (default: 0.5)_
- `model_path`：模型檔案位置（預設為 `./model/model.pt`）  
  _Path to model file (default: `./model/model.pt`)_

---

## 建議架構圖（Mermaid 畫圖）  
## Suggested Diagram (Mermaid Syntax)

```mermaid
flowchart TD
    A[Input] --> B[Preprocessing]
    B --> C[Inference]
    C --> D[Output]
