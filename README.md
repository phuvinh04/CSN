## Giới thiệu
PV GARDEN là một website bán cây cảnh được thiết kế để cung cấp trải nghiệm mua sắm trực tuyến thuận tiện cho người dùng quan tâm đến cây cảnh và các sản phẩm liên quan. Website cung cấp các chức năng chính như:

- Xem danh sách và chi tiết sản phẩm
- Giỏ hàng và thanh toán 
- Tìm kiếm sản phẩm
- Chat hỗ trợ khách hàng
- Hướng dẫn chăm sóc cây

## Công nghệ sử dụng

### Frontend:
- HTML5
- CSS (Tailwind CSS)
- JavaScript
- Font Awesome (icons)

### Backend:
- Node.js
- Express.js
- MongoDB (Mongoose)

### API:
- Google Generative AI (cho chatbot)
- REST API

## Cấu trúc thư mục
```
project/
├── images/
├── index.html
├── gioithieu.html
├── sanpham.html
├── thongtin.html
├── cart.html
├── checkout.html
├── nav.html
├── js/
│ ├── main.js
│ ├── cart.js
│ ├── chat.js
│ ├── bot.js
│ ├── include.js
│ └── java.js
├── server.js
└── package.json
```

## Cách chạy dự án

### 1. Cài đặt Node.js và npm

### 2. Clone repository về máy:
```bash
git clone [url-repository]
```

### 3. Cài đặt các dependencies:
```bash
npm install
```

### 4. Chạy server:
```bash
npm start
```

### 5. Truy cập website tại địa chỉ:
```
http://localhost:3000
```

## Lưu ý quan trọng:
- Cần có kết nối internet để load Tailwind CSS và Font Awesome
- Cần có API key hợp lệ cho Google Generative AI để chatbot hoạt động
- Cần cấu hình MongoDB để lưu trữ dữ liệu sản phẩm

