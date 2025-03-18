# thuy0an.github.io

- **Accuracy (Độ chính xác)**  
  $$ Accuracy = \frac{TP + TN}{TP + TN + FP + FN} $$

- **Precision (Độ chính xác theo lớp dương)**  
  $$ Precision = \frac{TP}{TP + FP} $$

- **Recall (Khả năng phát hiện mẫu dương - Độ phủ)**  
  $$ Recall = \frac{TP}{TP + FN} $$

- **F1-score (Trung bình hài hòa giữa Precision và Recall)**  
  $$ F1 = 2 \times \frac{Precision \times Recall}{Precision + Recall} $$

- **AUC-ROC (Đánh giá khả năng phân biệt giữa hai lớp)**  
  - **True Positive Rate (TPR - Sensitivity/Recall)**  
    $$ TPR = \frac{TP}{TP + FN} $$
  - **False Positive Rate (FPR - 1-Specificity)**  
    $$ FPR = \frac{FP}{FP + TN} $$
