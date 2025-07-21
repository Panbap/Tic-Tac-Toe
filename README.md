# 🎮 Tic Tac Toe AI

Trò chơi Caro (Tic-Tac-Toe) cổ điển kết hợp với **Trí tuệ nhân tạo (AI)**. Người chơi có thể đấu với AI thông minh sử dụng thuật toán **Minimax**. Giao diện đơn giản, dễ chơi, có thống kê trận đấu và hỗ trợ nhập tên người chơi.

![screenshot](https://raw.githubusercontent.com/Panbap/js/main/icon/TicTacToe-preview.png)

---

## 🚀 Demo

🔗 Truy cập demo trực tuyến:  
👉 https://panbap.github.io/Tic-Tac-Toe

Hoặc tải về và mở `index.html` bằng trình duyệt.

---

## 📦 Tính năng

- ✅ Giao diện trực quan, dễ sử dụng
- ✅ Chơi với AI thông minh (thuật toán Minimax)
- ✅ Nhập tên người chơi trước khi bắt đầu
- ✅ Thống kê số trận, thắng, hòa, thua
- ✅ Nút Reset để chơi lại nhanh chóng
- ✅ Giao diện responsive (hiển thị tốt trên điện thoại)

---

## 🛠️ Công nghệ sử dụng

| Công nghệ     | Mô tả                             |
|--------------|-----------------------------------|
| HTML5        | Tạo cấu trúc trang                |
| CSS3         | Giao diện người dùng (UI)         |
| JavaScript   | Xử lý logic game & trí tuệ nhân tạo |
| Minimax      | Thuật toán giúp AI chơi "thông minh" |
| jsDelivr CDN | Load `AITicTacToe.js` nhanh chóng từ GitHub |

---

## 📂 Cấu trúc dự án

```text
js/
├── game/
│   ├── index.html              # Giao diện chính
│   ├── AITicTacToe.js          # Logic AI và trò chơi
├── icon/
│   └── TicTacToe.ico           # Favicon
└── README.md                   # Tài liệu dự án

⚙️ Cài đặt & chạy
bash
Copy
Edit
# Clone repository
git clone https://github.com/Panbap/js.git

# Di chuyển vào thư mục game
cd js/game

# Mở file trong trình duyệt (click hoặc lệnh)
open index.html      # macOS
start index.html     # Windows

🧠 Cách hoạt động
Người chơi là X, AI là O

Trò chơi dùng minimax() để tìm nước đi tốt nhất

Trạng thái trò chơi cập nhật theo từng lượt

Khi kết thúc, hệ thống thống kê kết quả

Trò chơi không cần backend – chạy 100% client-side

🧠 Dự án cá nhân phục vụ học tập và thực hành AI trong game mini.
