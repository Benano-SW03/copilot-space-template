# 📚 API 參考文件 (API Reference)

## 函式名稱：`run_inference(input_path, threshold)`  
**Function:** `run_inference(input_path, threshold)`

---

### 參數說明 (Parameters)

| 參數 (Parameter) | 類型 (Type) | 說明 (Description)          |
|------------------|-------------|------------------------------|
| `input_path`     | `str`       | 輸入圖片或資料路徑 (Input image or data path) |
| `threshold`      | `float`     | 判定臨界值，範圍 0~1 (Threshold value from 0 to 1) |

---

### 回傳說明 (Return)

- 傳回推論結果（`list` of predictions）  
  _Returns inference result as a list of predictions._

---

## 🧪 API 使用範例 (Example Usage)

```python
result = run_inference("test.jpg", threshold=0.6)
print(result)
