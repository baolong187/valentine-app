# 💕 Valentine Date App

Website cute để rủ bạn gái đi hẹn hò!

## Cách chạy

### Bước 1: Cài dependencies
```bash
npm install
```

### Bước 2: Chạy server
```bash
npm start
# hoặc
node server.js
```

### Bước 3: Mở trình duyệt
Truy cập: **http://localhost:3000**

---

## Tính năng
- 💖 Giao diện pink cute giống ảnh mẫu
- 🐶 Chú chó dễ thương đang van xin
- ✅ Button "Đồng ý" → hiện màn hình mừng + confetti
- ❌ Button "Không" → **không bấm được**, hover hiện tooltip hài hước
- 💕 Tim bay lơ lửng nền
- 🎉 Confetti khi bạn gái đồng ý

## Tùy chỉnh
Mở file `public/index.html` và chỉnh:
- Dòng `Fine girl, anh rủ em đi hẹn hò nhé?` → thay tên bạn gái
- Dòng `Anh sẽ chuẩn bị một buổi hẹn thật đặc biệt nhé` → thay lời nhắn
- Thay SVG chó bằng ảnh thật: đổi thẻ `<svg>` thành `<img src="dog.jpg" .../>`
