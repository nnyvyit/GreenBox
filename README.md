<div align="center">

# 🌱 GREENBOX – Mô hình Thu hồi và Tái sử dụng Bao bì Carton

**Giải pháp Logistics xanh & Kinh tế tuần hoàn tại Thành phố Cần Thơ**

[![Award](https://img.shields.io/badge/Giải_Khuyến_Khích_Toàn_Quốc-Vietnam_Young_Logistics_Talents_2025-FFD700?style=for-the-badge&logo=trophy&logoColor=black)](https://github.com/nnyvyit/GreenBox)
[![Role](https://img.shields.io/badge/Role-Team_Leader_&_IT_Lead-2ea44f?style=for-the-badge&logo=github&logoColor=white)](https://github.com/nnyvyit)
[![Team](https://img.shields.io/badge/Team-Think_Different_(CTUT)-0078D4?style=for-the-badge)](https://github.com/nnyvyit/GreenBox)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Bootstrap 5](https://img.shields.io/badge/Bootstrap_5.3-7952B3?style=flat-square&logo=bootstrap&logoColor=white)
![Leaflet](https://img.shields.io/badge/Leaflet_Map-199900?style=flat-square&logo=leaflet&logoColor=white)

🔗 **Live Demo:** https://nnyvyit.github.io/GreenBox/

[Tổng quan](#-tổng-quan-dự-án) • [Hệ sinh thái](#-hệ-sinh-thái-công-nghệ-greenbox) • [Tính năng Website](#-tính-năng-chính-của-website) • [Công nghệ](#-công-nghệ-sử-dụng) • [Cấu trúc thư mục](#-cấu-trúc-thư-mục) • [Cài đặt & Deploy](#-hướng-dẫn-cài-đặt--triển-khai) • [Đội ngũ](#-đội-ngũ-thực-hiện)

</div>

---

## 🏆 Thành tích nổi bật

* **Giải Khuyến khích Toàn quốc** – *Cuộc thi Tài năng trẻ Logistics Việt Nam 2025 (Vietnam Young Logistics Talents 2025)*.
* Đại diện đội thi **Think Different** – Trường Đại học Kỹ thuật – Công nghệ Cần Thơ (CTUT).

---

## 📖 Tổng quan dự án

Sự bùng nổ của thương mại điện tử tại Việt Nam tạo ra hàng trăm nghìn tấn rác thải bao bì carton mỗi năm, trong khi phần lớn chỉ được sử dụng một lần rồi thải bỏ hoặc bán phế liệu với giá trị thấp. Tại TP. Cần Thơ, tỷ lệ tái sử dụng trực tiếp hộp carton mới chỉ đạt khoảng **5–7%** do thiếu mạng lưới logistics ngược kết nối giữa người tiêu dùng, doanh nghiệp và đơn vị tái chế.

**GREENBOX** được xây dựng nhằm giải quyết bài toán này thông qua mô hình **thu hồi – phân loại – tái sử dụng bao bì carton khép kín**:
* **Kéo dài vòng đời bao bì:** Hộp carton đạt chuẩn (>90% độ nguyên vẹn) được vệ sinh, gia cố bằng lớp phủ màng sinh học **PLA Fusion** chống ẩm và gắn **mã QR** để tái sử dụng từ **3–5 vòng đời**, giúp tiết kiệm 30–40% chi phí đóng gói và giảm 1,5–2 kg CO₂/hộp.
* **Thúc đẩy tiêu dùng xanh:** Người dùng trả hộp tại các trạm thu gom được tích điểm xanh qua mã QR để đổi quà tặng thân thiện môi trường hoặc voucher mua sắm.

---

## 🌐 Hệ sinh thái công nghệ GreenBox

Giải pháp công nghệ của dự án được thiết kế đồng bộ trên 3 nền tảng:

1. **Website GreenBox *(Mã nguồn trong repository này)*:** Cổng thông tin mở giới thiệu mô hình kinh tế tuần hoàn, quy trình vận hành 5 bước, tin tức cộng đồng và bản đồ trực quan hóa mạng lưới kho – trạm thu gom tại TP. Cần Thơ.
2. **Ứng dụng di động Android GreenBox:** Phục vụ 4 nhóm người dùng (*Quản trị viên, Khách hàng, Đối tác thu gom, Nhân viên thu gom*) với các tính năng quét mã QR truy xuất vòng đời hộp, tích điểm đổi quà, đặt lịch thu gom và điều hướng lộ trình qua **Google Maps SDK & Directions API**.
3. **Trạm thu gom thông minh (AI + IoT):** Xác thực người dùng qua số điện thoại, tích hợp camera và cảm biến tự động nhận diện – phân loại hộp có mã QR và không mã QR, cập nhật điểm thưởng và gửi cảnh báo đầy kho theo thời gian thực.

---

## ✨ Tính năng chính của Website

* **Trang chủ (`index.html`):**
  * Thanh điều hướng (Navigation Bar) tương thích đa thiết bị (Responsive Mobile Menu).
  * Trình chiếu banner chiến dịch tự động (Bootstrap Carousel).
  * Giới thiệu tổng quan, Sứ mệnh – Tầm nhìn – Triết lý hoạt động và hướng dẫn 3 bước tham gia dọn dẹp, tích điểm đổi quà.
  * Footer tích hợp thông tin doanh nghiệp và các tiêu chuẩn chứng nhận (*FSC, ISO 14001, Nhãn xanh Việt Nam*).
* **Giới thiệu (`php/gioithieu.html`):**
  * Trình bày Tầm nhìn đến năm 2030, Sứ mệnh, 5 Giá trị cốt lõi (*Bền vững, Đổi mới, Trách nhiệm, Kết nối, Lan tỏa*) và hồ sơ đội ngũ sáng lập.
* **Quy trình vận hành (`php/timhieungay.html`):**
