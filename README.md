# 📡 Đồ án Giám sát Mạng với SolarWinds NPM

> Triển khai hệ thống giám sát hiệu năng mạng thời gian thực bằng công cụ **SolarWinds Network Performance Monitor (NPM)**, kết hợp mô phỏng môi trường mạng với GNS3 và VMware.

---

## 🎯 Mục tiêu dự án

- Thiết lập mô hình mạng giả lập với nhiều node (router, switch, server)  
- Cấu hình giám sát hiệu năng hệ thống bằng **SolarWinds NPM**
- Gửi cảnh báo tự động qua email khi phát hiện lỗi hoặc quá tải
- Thử nghiệm các tình huống thực tế như node down, CPU overload, mất kết nối

---

## 🛠 Công nghệ & Công cụ sử dụng

| Thành phần       | Công nghệ / Công cụ           |
|------------------|-------------------------------|
| Giám sát mạng    | SolarWinds Network Performance Monitor (NPM) |
| Mô phỏng mạng    | GNS3 + VMware (Windows Server) |
| Giao thức giám sát| SNMP (v2, v3), ICMP          |
| Email cảnh báo   | SMTP cấu hình trên SolarWinds |
| Client kiểm thử  | Windows, Linux (agentless or SNMP-enabled) |

---

## 🧪 Các chức năng đã triển khai

- ✅ Giám sát **hiệu năng thiết bị mạng** (CPU, RAM, trạng thái)
- ✅ Cảnh báo khi mất kết nối, quá tải tài nguyên
- ✅ Quản lý và theo dõi nhiều node mạng từ giao diện tập trung
- ✅ Thiết lập biểu đồ hiệu năng theo thời gian thực
- ✅ Báo cáo định kỳ và thống kê chi tiết

---

## 🖼️ Hình ảnh minh họa

<p align="center">
  <strong>Giao diện dashboard SolarWinds:</strong><br>

  ![DB](https://github.com/Cuong312004/solarwind/blob/main/Picture2.png)

  <strong>Thiết lập cảnh báo:</strong><br>
  ![alert](https://github.com/Cuong312004/solarwind/blob/main/Picture3.png)

  <strong>Sơ đồ topology mô phỏng trên GNS3:</strong><br>
  ![topology](https://github.com/Cuong312004/solarwind/blob/main/Picture1.png)
</p>

---

## 📁 Cấu trúc & tài liệu

```
SolarWinds_Project/
├── report/
├── gns3_project/           # File cấu hình GNS3
├── README.md
```

---

## 👨‍💻 Thành viên thực hiện

- **Lưu Quốc Cường** – Phụ trách cấu hình SolarWinds, SNMP, kịch bản kiểm thử  
- **Nhóm 16 – Môn NT531.P11**

## ▶️ Demo video 
* Demo: https://drive.google.com/drive/folders/16qddXRqW-bW-Ew2q4BhoV6oU2gm6X9XT?usp=sharing  
