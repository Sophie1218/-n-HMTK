Xây Dựng Dữ Liệu Và Mô Hình Phân Loại Các Bình Luận Phàn Nàn Của Khách Hàng Trên Mạng Xã Hội

---Bài toán---
 
 Phân loại câu phàn nàn (Phân lớp nhị phân):
Đầu vào: Một câu hay một đoạn văn ngắn.
Đầu ra: 0 (Không phàn nàn) và 1 (Phàn nàn).


---Bộ dữ liệu---
  
  Bao gồm 2,415 câu bình luận lấy trên mạng xã hội. Mỗi điểm dữ liệu có bốn thuộc tính: ID, Commnet, Label và Domain. Trong đó Label có nhãn 1 - bình luận phàn nàn và nhãn 0 - bình luận không phàn nàn. Và Domain có miền dữ liệu là Mỹ phẩm, Ứng dụng và Điện thoại.
  Sử dụng thuộc tính Commnet làm đầu vào và đầu ra dự đoán thuộc tính Label.
  
  
---Phương pháp thử nghiệm---

 Tiền xử lý dữ liệu
 Áp dụng phương pháp Máy học là Decision Tree, Random Forest, Logistic Regression, K - Nearest Neighbor, Naive Bayes và Support Vector Machine. Và một mô hình học sâu PhoBERT.


---Kết quả---

  Trong các phương pháp máy học được thử nghiệm, thuật toán Logistic Regression có kết quả cao nhất F1 bằng 75.25%. Nhưng mô hình cho hiệu suất tốt nhất là mô hình học sâu PhoBERT, hai độ đo Accuracy và F1 có kết quả lần lượt là 85.35% và 85.00%.




