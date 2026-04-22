# IS-Project-PTIT
Dưới đây là các dự án học thuật của tôi trong quá trình học tập tại PTIT:

**1. Kiểm thử xâm nhập hệ thống tích hợp và triển khai liên tục Jenkins**
- Nghiên cứu và phân tích hai lỗ hổng bảo mật nghiêm trọng: lỗ hổng đọc tệp tùy ý qua giao diện dòng lệnh (CVE-2024-23897) và lỗ hổng nâng cao đặc quyền nhân hệ điều hành Linux (CVE-2024-1086)
- Thiết kế mô hình mạng thực tế gồm 5 máy ảo (tường lửa pfSense, máy tấn công, máy chủ Jenkins mục tiêu, máy chủ web, cơ sở dữ liệu) và triển khai toàn bộ môi trường thử nghiệm
- Thực hiện đầy đủ 5 giai đoạn kiểm thử: trinh sát và nhận diện bề mặt tấn công → khai thác lỗ hổng → hậu khai thác → duy trì truy cập → xóa dấu vết
- Tổng hợp báo cáo đánh giá rủi ro và đề xuất biện pháp khắc phục, vá lỗi cho hệ thống
- Công cụ sử dụng: Kali Linux, Metasploit, Nmap, Wireshark, pfSense

**2. Triển khai giám sát an toàn mạng bằng Security Onion**
- Nghiên cứu tổng quan về giám sát an toàn mạng và kiến trúc của nền tảng Security Onion; so sánh với các giải pháp giám sát khác trên thị trường
- Cài đặt, cấu hình Security Onion và tích hợp các công cụ phân tích: hệ thống phát hiện xâm nhập, công cụ phân tích lưu lượng mạng, bảng điều khiển trực quan hóa
- Mô phỏng và thực hành phát hiện các kịch bản tấn công thực tế: lây nhiễm mã độc và thiết lập kênh điều khiển từ xa (C2), quét cổng, dò mật khẩu
- Đánh giá hiệu quả phát hiện tấn công và đề xuất cải thiện cấu hình hệ thống
- Công cụ sử dụng: Security Onion, Snort, Suricata, Zeek, Kibana, Elasticsearch
