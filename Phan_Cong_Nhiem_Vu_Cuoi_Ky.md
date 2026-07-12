# BẢNG PHÂN CÔNG NHIỆM VỤ ĐỒ ÁN CUỐI KỲ
**Môn học:** Nhập môn Học máy
**Đề tài đề xuất:** Phân loại tin nhắn văn bản (SMS Spam Collection)

---

## 👩‍💻 Thành viên 1: Thùy Vân - "Data Master" (Tiền xử lý & Báo cáo nền tảng)
**Công việc chịu trách nhiệm:**
1. **Tiền xử lý dữ liệu Text:** Tải bộ dữ liệu SMS Spam về, làm sạch văn bản (xóa dấu câu, viết thường), dùng Tokenizer biến chữ thành số, và Padding (chèn số 0) để các câu dài bằng nhau. Chia tập Train/Val/Test.
2. **Code mô hình Baseline (Cơ sở):** Code nhanh 1 mô hình Machine Learning truyền thống (như Logistic Regression hoặc Naive Bayes) để lấy điểm gốc (Baseline) so sánh.
3. **Viết Báo cáo (Word):** Gõ Phần 1 (Giới thiệu), Phần 2 (Mô tả dữ liệu) và Phần 3 (Tiền xử lý) theo đúng form yêu cầu của thầy.

---

## 👩‍💻 Thành viên 2: Mỹ Anh - "LSTM Master" (Chuyên gia Mạng Hồi tiếp)
**Công việc chịu trách nhiệm:**
1. **Code mô hình LSTM:** Lấy dữ liệu đã xử lý từ Vân để đưa vào mạng LSTM (hoặc GRU).
2. **Thiết kế thực nghiệm (Bắt buộc):** Code thử nghiệm 2-3 cấu hình khác nhau (Ví dụ: Lần 1 dùng 32 units, Lần 2 dùng 64 units, Lần 3 thêm Dropout chống học vẹt).
3. **Vẽ biểu đồ & Đánh giá:** Vẽ biểu đồ đường Loss/Accuracy của mạng LSTM qua từng Epoch. Trích xuất Classification Report và Confusion Matrix.
4. **Viết Báo cáo (Word):** Tự viết phần mô tả kiến trúc, quá trình huấn luyện và nhận xét kết quả của mô hình LSTM vào file Báo cáo chung.

---

## 👩‍💻 Thành viên 3: Kim Lợi - "CNN Master" (Chuyên gia Mạng Tích chập)
**Công việc chịu trách nhiệm:**
1. **Code mô hình CNN 1D:** Lấy dữ liệu đã xử lý từ Vân để đưa vào mạng CNN 1D.
2. **Thiết kế thực nghiệm (Bắt buộc):** Code thử nghiệm 2-3 cấu hình khác nhau cho CNN (Ví dụ: Thay đổi số Filter, thay đổi Learning rate, thay đổi Batch size).
3. **Vẽ biểu đồ & Đánh giá:** Vẽ biểu đồ đường Loss/Accuracy của mạng CNN. Trích xuất các chỉ số đánh giá.
4. **Tổng hợp Báo cáo chốt hạ (Word):** Chịu trách nhiệm kẻ **"Bảng vàng so sánh"** ở cuối bài (So sánh kết quả của Logistic vs LSTM vs CNN). Viết phần kết luận đồ án: Mô hình nào chạy nhanh nhất? Mô hình nào chính xác nhất? Phân tích hiện tượng Overfitting/Underfitting.
