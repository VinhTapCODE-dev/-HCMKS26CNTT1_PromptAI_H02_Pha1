# BÀI LÀM PHA 2 – HACKATHON 02

- **Mã đề:** 06
- **Họ tên:*Võ Quốc Vinh*
- **Lớp:*CNTT1*
- **Link repository Pha2:**
- **Công cụ AI đã dùng (ChatGPT/Claude/Gemini):*Claude*

> Pha 2 (20 phút cuối). Mỗi mục: mở cuộc trò chuyện mới, gửi nguyên văn prompt đã viết trong bai_lam_pha1.md, dán câu trả lời và link chia sẻ vào đây. Xong, kéo thả file này vào repository Pha2.

## 4.2. Trích xuất tin nhắn đặt bàn ra JSON

**KET QUA AI**

```[
  {"ma_buffet": null, "ngay_dat": "2026-12-19", "nguoi_lon": 2, "tre_em": 1, "khu_vuc": "trong_nha", "ghi_chu": null},
  {"ma_buffet": "HAISAN", "ngay_dat": "2027-01-03", "nguoi_lon": 3, "tre_em": 0, "khu_vuc": null, "ghi_chu": "1 người dị ứng sữa"},
  {"ma_buffet": "LAU", "ngay_dat": null, "nguoi_lon": 4, "tre_em": 0, "khu_vuc": "san_vuon", "ghi_chu": "ông ngoại đi xe lăn"}
]
```

**Link trò chuyện:*https://claude.ai/share/31b91798-e6d5-44c8-8429-702b3c0dddcf*

## 4.3. Báo giá bằng Chain-of-Thought

**KET QUA AI**

```**Dữ liệu áp dụng:** buffet nướng (NUONG) = 399.000 đồng/người lớn.

**1. Tiền người lớn**
10 × 399.000 = 3.990.000 đồng

**2. Tiền trẻ em**
- 3 trẻ cao 1,1 m, 1,2 m, 1,35 m đều nằm trong khoảng 1 m – 1,4 m nên tính 50% giá: 399.000 × 50% = 199.500 đồng/trẻ
- Tiền 3 trẻ: 3 × 199.500 = 598.500 đồng
- Bé cao 0,8 m (dưới 1 m): miễn phí = 0 đồng
- Tổng tiền trẻ em: 598.500 + 0 = 598.500 đồng

**3. Tiền buffet**
3.990.000 + 598.500 = 4.588.500 đồng

**4. Giảm giá đoàn**
Đoàn có 10 người lớn (đủ điều kiện từ 10 người lớn trở lên) nên được giảm 5% trên tiền buffet:
- Số tiền giảm: 4.588.500 × 5% = 229.425 đồng
- Tiền buffet sau giảm: 4.588.500 − 229.425 = 4.359.075 đồng

**5. Phụ thu**
1 phòng riêng: 1 × 500.000 = 500.000 đồng (không được giảm giá)

**6. Tổng tiền**
4.359.075 + 500.000 = 4.859.075 đồng

[RESULT:4.859.075 đồng]
```

**Link trò chuyện:*https://claude.ai/share/99890b58-b4c0-44d2-a38f-6402e9ec31d3*

### b) Kiểm tra kết quả AI

Kết quả của AI đúng 

## 4.4. Dây chuyền xử lý khiếu nại – kết quả Trạm 1

**KET QUA AI**

```text
(Dán câu trả lời của AI vào đây (bấm nút Copy dưới câu trả lời) – xoá dòng này)
```

**Link trò chuyện:**

## 4.5. Prompt chấm bài theo Rubric

**KET QUA AI**

```text
(Dán câu trả lời của AI vào đây (bấm nút Copy dưới câu trả lời) – xoá dòng này)
```

**Link trò chuyện:**
