# HR Analytics Deep Learning Project Website

Website tóm tắt dự án **Deep Learning trong phân tích dữ liệu nguồn nhân lực: Nghiên cứu về tỷ lệ nghỉ việc**

## 🎨 Thiết Kế

Website được thiết kế với **light blue pastel theme** tương tự portfolio, bao gồm:

- **Màu sắc chủ đạo**: Xanh dương pastel (#7b9cff, #4a90e2, #a6c1ee)
- **Typography**: Inter (body) và Outfit (headings)
- **Hiệu ứng**: Gradient backgrounds, smooth animations, hover effects
- **Responsive**: Tương thích với mọi thiết bị

## 📂 Cấu Trúc File

```
website/
├── index.html          # Trang chính
├── styles.css          # CSS với light blue pastel theme
├── script.js           # JavaScript cho tương tác
└── README.md           # File này
```

## 🚀 Cách Sử Dụng

### Mở trực tiếp
1. Mở file `index.html` bằng trình duyệt web
2. Hoặc double-click vào file `index.html`

### Sử dụng Live Server (khuyến nghị)
1. Cài đặt Live Server extension trong VS Code
2. Right-click vào `index.html` → "Open with Live Server"
3. Website sẽ tự động mở tại `http://localhost:5500`

### Sử dụng Python HTTP Server
```bash
cd website
python -m http.server 8000
```
Sau đó mở `http://localhost:8000` trong trình duyệt

## 📋 Nội Dung Website

### 1. **Hero Section**
- Giới thiệu dự án
- Thống kê chính: 75% Accuracy, 10,000 Records, 3 Clusters
- Call-to-action buttons

### 2. **Tổng Quan Dự Án**
- Mục tiêu
- Dữ liệu
- Phương pháp
- Chatbot RAG

### 3. **Phương Pháp Nghiên Cứu**
Timeline 8 bước:
1. Xác định vấn đề
2. Xây dựng & tiền xử lý dữ liệu
3. EDA
4. Phân cụm nhân viên
5. Huấn luyện mô hình Deep Learning
6. Huấn luyện mô hình chuyên gia
7. Đánh giá & tối ưu
8. Triển khai RAG Chatbot

### 4. **Kết Quả**
- Hiệu suất mô hình tổng thể
- Hiệu suất theo từng cluster (0, 1, 2)
- Những phát hiện quan trọng

### 5. **Chatbot RAG**
- Kiến trúc RAG
- Tính năng chatbot
- Quy trình hoạt động

### 6. **Tech Stack**
- Data Processing: Pandas, NumPy, Faker
- Deep Learning: TensorFlow, Keras, PyTorch
- Machine Learning: Scikit-learn, SMOTE, KMeans
- RAG & LLM: Vector DB, Embeddings, LLM
- Visualization: Matplotlib, Seaborn

### 7. **Nhóm Thực Hiện**
- Thông tin nhóm 7
- Môn học: Machine Learning
- Học kỳ: Cuối Kỳ 2025-2026

## ✨ Tính Năng Đặc Biệt

### Animations
- Smooth scroll navigation
- Fade-in animations khi scroll
- Hover effects trên cards
- Counter animation cho số liệu
- Floating gradient orbs

### Responsive Design
- Tương thích mobile, tablet, desktop
- Hamburger menu cho mobile
- Flexible grid layouts

### Interactive Elements
- Active nav link khi scroll
- Scroll indicator với animation
- Smooth transitions
- Hover states cho tất cả interactive elements

## 🎯 Mục Đích

Website này được tạo để:
1. **Tóm tắt dự án** một cách trực quan và dễ hiểu
2. **Trình bày kết quả** nghiên cứu Deep Learning
3. **Giới thiệu phương pháp** RAG Chatbot
4. **Chia sẻ kiến thức** về HR Analytics với AI

## 🛠️ Tùy Chỉnh

### Thay đổi màu sắc
Chỉnh sửa CSS variables trong `styles.css`:
```css
:root {
    --primary-gradient: linear-gradient(135deg, #7b9cff 0%, #2d47d9 100%);
    --accent-cyan: #4a90e2;
    /* ... */
}
```

### Thêm nội dung
Chỉnh sửa HTML trong `index.html` theo cấu trúc có sẵn

### Thay đổi animations
Chỉnh sửa JavaScript trong `script.js`

## 📱 Tương Thích

- ✅ Chrome, Edge, Firefox, Safari (latest versions)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)
- ✅ Tablet browsers
- ✅ Desktop browsers

## 📝 Ghi Chú

- Website sử dụng Google Fonts (Inter, Outfit) - cần kết nối internet
- Tất cả animations sử dụng CSS và vanilla JavaScript
- Không cần framework hay library ngoài
- Tối ưu cho hiệu suất và SEO

## 🎓 Nhóm Thực Hiện

**Nhóm 7 - ML Cuối Kỳ**
- Dự án: Deep Learning HR Analytics
- Môn học: Machine Learning
- Năm học: 2025-2026

---

Made with ❤️ by Nhóm 7
