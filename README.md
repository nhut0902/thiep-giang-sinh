# 🎄 Thiệp Giáng Sinh — Gửi Người Yêu

Thiệp Giáng sinh phong cách **Matrix**, dành tặng người yêu 💝

## ✨ Có gì trong thiệp

- 🌧️ Mưa chữ Matrix đỏ — xanh trên nền đen
- ⏳ Đếm ngược bằng hạt sáng: **3 → 2 → 1 → Merry → Xmas → My Love**
- 🎄 Chữ vỡ ra hợp thành **cây thông Noel phát sáng** + ngôi sao trên đỉnh
- 💌 Thiệp gập có **dấu niêm phong vàng** — chạm để mở
- 🚪 Cánh cửa thiệp mở 3D + ánh sáng bung + pháo hoa, confetti
- 🎄 **Cây thông hạt bên trong thiệp** — cùng sprite đèn / tim / sao, xoay lấp lánh
- ⌨️ Lời chúc **hiệu ứng đánh máy** kiểu giải mã Matrix, tự co chữ vừa khung
- 🌠 Tuyết rơi, sao băng, dây đèn nhấp nháy, di chuột ra tia lấp lánh

## 🔧 Sửa tên / lời chúc

Mở `index.html`, sửa block `CFG` ở đầu `<script>`:

```js
const CFG={
  name:'Hồng Lạc',            // tên hiện dưới cây thông
  to:'Gửi em, Hồng Lạc',      // dòng đầu trong thiệp
  seq:[...],                  // chuỗi chữ hạt [chữ, số giây, màu RGB]
  text:'...',                 // lời chúc gõ máy
  sign:'— Một người luôn nghĩ đến em ❤'
};
```

## 🌐 Xem online

<https://nhut0902.github.io/thiep-giang-sinh/>

---

**Code By NhutCoder Team** 💚
