Pipeline đã thực hiện:
Thiết lập môi trường ảo Anaconda với Python 3.10 và cài đặt các thư viện cần thiết từ requirements_core.txt.
Kiểm tra môi trường thành công với src/env_check.py, khởi tạo các tệp log và cấu hình hệ thống.
Chạy chương trình src/hello_nlp.py để thực hiện một pipeline NLP đơn giản trên dữ liệu ngẫu nhiên, đạt độ chính xác (accuracy) và Macro F1 là 1.0.
Vấn đề gặp phải và xử lý:
Quá trình cài đặt thư viện diễn ra thuận lợi, không gặp lỗi xung đột phiên bản.
Các thư viện quan trọng như PyTorch đã được cài đặt và kiểm tra thành công để sẵn sàng cho các bài Lab tiếp theo.
Kết quả đạt được:
Hoàn thành việc tạo các tệp minh chứng bắt buộc trong thư mục logs/ và results/.
Hệ thống đã sẵn sàng để thực hiện các bài kiểm tra với pytest.