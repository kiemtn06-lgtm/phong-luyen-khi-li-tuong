# Phòng luyện tập Vật lí 12 · Chương 2. Khí lí tưởng (523 câu, 26 buổi)

Dữ liệu sinh tự động từ file `CHUONG2_KHI_LI_TUONG_tu_de_thi_tong_hop_DA_GOP_523_cau.docx`, chia buổi giống file
`CHUONG2_KHI_LI_TUONG_Bo_on_theo_buoi_DU_523_cau.docx` (công cụ: `D:\Hồ sơ dạy học số\tools\chuong2\`). Nội dung giữ nguyên văn.

- 26 nhóm = 26 buổi (Bài 8: buổi 1–4, Bài 9: 5–9, Bài 10: 10–13, Bài 11: 14–22, Bài 12: 23–26).
- Mỗi buổi tối đa 18 câu trắc nghiệm, 4 câu đúng/sai, 6 câu trả lời ngắn.
- 2 câu nguồn không có đáp án (B9-TH-I-34, B12-VD-I-02): học sinh vẫn làm, phòng ghi nhận nhưng không chấm.

## Mở câu (trang /teacher)
1. **Mở hết buổi**: mở cả buổi kế tiếp theo kế hoạch.
2. **Cài đặt thêm → Mở câu theo nhóm và số lượng**:
   - *Nhóm câu*: chọn buổi (hoặc "Theo kế hoạch").
   - *Dạng câu*: Nhiều lựa chọn / Đúng - Sai / Trả lời ngắn / Mọi dạng.
   - *Từng câu* (chọn số câu) hoặc *Cả nhóm một lần*.

## Cập nhật dữ liệu khi sửa file Word nguồn
```
cd "D:\Hồ sơ dạy học số\tài liệu 4 chương 12"
python -I -X utf8 ..\tools\chuong2\tao_phong.py CHUONG2_KHI_LI_TUONG_tu_de_thi_tong_hop_DA_GOP_523_cau.docx D:\phong-luyen-khi-li-tuong
cd D:\phong-luyen-khi-li-tuong && node tools\kiem_tra.js
```

## Chạy thử trên máy / Đưa lên Render
- Trên máy: bấm đôi `chay-tren-may.bat`.
- Render: New → Blueprint, chọn kho này, nhập `TEACHER_PASS`. Gói miễn phí tự ngủ sau ~15 phút; cập nhật mã sẽ xóa bài làm đang có.
