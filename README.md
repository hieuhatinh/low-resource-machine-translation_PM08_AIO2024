# low-resource-machine-translation_PM08_AIO2024
# Project Low Resource Machine Translation PM08 AIO2024

 **Dịch Máy (Machine Translation)** với mục đích tự động dịch văn bản từ ngôn ngữ tự nhiên này
 sang ngôn ngữ tự nhiên khác. Một trong những thách thức lớn hiện nay của các hệ thống dịch là có ít  tài nguyên để huấn luyện mô hình. Vì vậy, trong phần này, chúng ta sẽ tập trung vào cải thiện các mô
 hình dịch với ít tài nguyên (Low-resource machine translation), số lượng các cặp dữ liệu song ngữ hạn
 chế, ví dụ mô hình dịch huấn luyện với chỉ 20000 cặp câu tiếng Anh và tiếng Việt. Vì vậy, để cải tiến
 mô hình dịch trong trường hợp có ít tài nguyên, chúng ta tập trung vào 2 hướng tiếp cận như sau:
 1. Hướng 1: Sử dụng mô hình pre-trained mBART50, T5
 2. Hướng 2: Sử dụng kỹ thuật để tăng cường dữ liệu như thu thập thêm dữ liệu, kỹ thuật học bán
 giám sát,...

Project này sẽ Fine-tuning mô hình mBART50 cho bài toán dựa trên bộ dữ liệu dịch **IWSLT’15 English-Vietnamese** với số lượng mẫu cho training: 133,317 cặp câu song ngữ, tập validation: 1,553 cặp câu
 song ngữ và tập test: 1,269 cặp câu song ngữ. 