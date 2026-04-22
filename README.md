# 🎮 Commands - Tính Điểm Game GARENA FREE FIRE

> Bộ lệnh tính điểm, hồ sơ và thống kê cho game **Garena Free Fire** — dành cho các bot Facebook (GoatBot / NashBot / FCA Bot).

---

## 📁 Cấu trúc cài đặt

```
📂 Bot của bạn/
├── 📂 commands/              ← Bỏ các file lệnh vào đây
│   ├── hoso.js
│   ├── limit.js
│   ├── luotdung.js
│   ├── tinhdiem.js
│   └── tinhdiemlogo.js
│
└── 📂 ffrank/                ← Chỉ bỏ file này vào đây
    └── api.js
```

---

## ⚙️ Cách cài đặt

### Bước 1: Tải về

```bash
git clone https://github.com/tandeptrai556-maker/commands.git
```

### Bước 2: Copy file `api.js` vào thư mục `ffrank`

Tìm thư mục `ffrank` trong bot của bạn và copy file vào:

```
api.js  →  ffrank/api.js
```

### Bước 3: Copy các file lệnh còn lại vào thư mục `commands`

```
hoso.js         →  commands/hoso.js
limit.js        →  commands/limit.js
luotdung.js     →  commands/luotdung.js
tinhdiem.js     →  commands/tinhdiem.js
tinhdiemlogo.js →  commands/tinhdiemlogo.js
```

### Bước 4: Khởi động lại bot

```bash
node index.js
# hoặc
npm start
```

---

## 📋 Danh sách lệnh

| File | Mô tả |
|------|-------|
| `hoso.js` | Xem hồ sơ người chơi Free Fire |
| `limit.js` | Kiểm tra giới hạn sử dụng |
| `luotdung.js` | Quản lý lượt dùng lệnh |
| `tinhdiem.js` | Tính điểm rank Free Fire |
| `tinhdiemlogo.js` | Tính điểm rank có logo |
| `api.js` *(ffrank)* | File API xử lý dữ liệu Free Fire |

---

## 📌 Lưu ý

- `api.js` **bắt buộc phải** nằm trong thư mục `ffrank/` — các lệnh khác gọi đến file này.
- Các file lệnh `.js` còn lại bỏ thẳng vào `commands/`, **không** tạo thêm thư mục con.
- Sau khi cài xong nhớ **restart bot** để load lệnh mới.

---

## 👤 Tác giả

**tandeptrai556-maker** — MINH TRÍ  
GitHub: [tandeptrai556-maker](https://github.com/tandeptrai556-maker)
