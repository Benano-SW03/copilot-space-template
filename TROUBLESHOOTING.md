# 🛠️ 常見問題排查 (Troubleshooting Guide)

---

## 問題一：`ModuleNotFoundError`  
**Issue 1: `ModuleNotFoundError`**

### 🔍 錯誤訊息 (Error Message)
ModuleNotFoundError: No module named 'cv2'

**解決方案：**  
- 請確認已安裝 OpenCV：

  ```bash
  pip install opencv-python


## 問題二：模型預測結果為空  
**Issue 2: Empty prediction results from model**

**可能原因 (Possible Causes)：**  
- `threshold` 設定太高  
  _Threshold value is set too high_  
- 輸入資料未經標準化處理  
  _Input data is not properly normalized_
