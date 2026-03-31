# Lab0 — 1-page report (Hello NLP, random data)

## Pipeline đã chạy
- Thực hiện kiểm tra môi trường hệ thống bằng src/env_check.py.2
Chạy pipeline NLP cơ bản qua src/hello_nlp.py: Sinh dữ liệu văn bản giả lập (ngẫu nhiên) → Trích xuất đặc trưng TF-IDF → Huấn luyện mô hình LogisticRegression → Đánh giá hiệu năng.3

## Kết quả
- Xem `results/lab0_metrics.json` (accuracy, macro-F1, confusion matrix).

## Vấn đề gặp phải + cách xử lý (ví dụ)
- Vấn đề: Không thể cài đặt thư viện PyTorch thông qua lệnh conda install như hướng dẫn mặc định.5
-Cách xử lý: Chuyển sang sử dụng pip để cài đặt trực tiếp, giúp quá trình cài đặt diễn ra thành công và thư viện hoạt động ổn định trong môi trường csc4007-nlp.6

## Ghi chú
- Dữ liệu random chỉ dùng để kiểm tra quy trình thiết lập (setup), không dùng để đánh giá hay so sánh các mô hình thực tế.
- Đã hoàn thành đầy đủ các tệp minh chứng và bài kiểm tra pytest theo yêu cầu.