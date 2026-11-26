# BÀI LÀM PHA 2 – HACKATHON 02

- **Mã đề:** 05
- **Họ tên:Hoàng Hải Yến**
- **Lớp:CNTT2**
- **Link repository Pha2:https://github.com/hoanghaiyen0108anlao-dev/HN-KS26-CNTT2_PromtAI_H02_Pha1-Pha2.git**
- **Công cụ AI đã dùng (ChatGPT/Claude/Gemini):ChatGPT**

> Pha 2 (20 phút cuối). Mỗi mục: mở cuộc trò chuyện mới, gửi nguyên văn prompt đã viết trong bai_lam_pha1.md, dán câu trả lời và link chia sẻ vào đây. Xong, kéo thả file này vào repository Pha2.

## 4.2. Trích xuất tin nhắn đặt vé xem phim ra JSON

**KET QUA AI**

```text
"loai_ve": "P2D",
    "ngay_chieu": "2026-12-24",
    "ve_nguoi_lon": 2,
    "ve_tre_em": 1,
    "loai_ghe": "thuong",
    "ghi_chu": null
  },
  {
    "loai_ve": "P3D",
    "ngay_chieu": "2027-01-01",
    "ve_nguoi_lon": 3,
    "ve_tre_em": 0,
    "loai_ghe": null,
    "ghi_chu": "1 người hay chóng mặt, cần ngồi gần lối ra"
  },
  {
    "loai_ve": "GOLD",
    "ngay_chieu": null,
    "ve_nguoi_lon": 4,
    "ve_tre_em": 0,
    "loai_ghe": "doi",
    "ghi_chu": "1 bạn đi xe lăn"
  }
]
```

**Link trò chuyện:https://chatgpt.com/c/6b079d8b-fe40-83ec-ab32-1bbcf4cb440d**

## 4.3. Báo giá bằng Chain-of-Thought

**KET QUA AI**

```text
Bước 1 – Tiền vé người lớn
- Số lượng: 5 người lớn.
- Loại vé: P3D – Phim 3D.
- Giá vé mỗi người: 130.000 đồng.
Phép tính:

5 × 130.000 = 650.000 đồng
Bước 2 – Tiền vé trẻ em
Có 3 trẻ em:

- Trẻ em thứ nhất cao 1,1 m: tính 70% giá vé người lớn.

130.000 × 70% = 91.000 đồng.

- Trẻ em thứ hai cao 1,25 m: tính 70% giá vé người lớn.

130.000 × 70% = 91.000 đồng.

- Bé thứ ba cao 0,9 m: dưới 1 m, ngồi cùng người lớn nên được miễn phí.

Tiền vé = 0 đồng.

Tổng tiền vé trẻ em:

91.000 + 91.000 + 0 = 182.000 đồng
Bước 3 – Tiền vé
Cộng tiền vé người lớn và tiền vé trẻ em:

650.000 + 182.000 = 832.000 đồng
Bước 4 – Giảm giá nhóm
- Số người lớn: 5 người.
- Điều kiện giảm giá: nhóm từ 5 người lớn trở lên.
- Nhóm đủ điều kiện được giảm 10% trên tổng tiền vé.
Số tiền được giảm:

832.000 × 10% = 83.200 đồng

Tiền vé sau giảm:

832.000 − 83.200 = 748.800 đồng
Bước 5 – Tiền combo
- Số lượng combo: 3.
- Giá mỗi combo: 75.000 đồng.
- Combo không được giảm giá.
Phép tính:

3 × 75.000 = 225.000 đồng
Bước 6 – Tổng tiền
Tổng tiền phải thanh toán:

Tiền vé sau giảm + Tiền combo

748.800 + 225.000 = 973.800 đồng
Tổng thanh toán: 973.800 đồng
[RESULT: 973.800 đồng]
```

**Link trò chuyện:https://chatgpt.com/c/6b079dfb-86ac-83ec-9219-64feee0c499e**

### b) Kiểm tra kết quả AI
Ai đúng 
## 4.4. Dây chuyền xử lý khiếu nại – kết quả Trạm 1

**KET QUA AI**

```text
{
  "loai_su_co": "loi_ky_thuat",
  "so_khach": 4,
  "so_suat_bi_loi": 2,
  "tom_tat": "Gia đình 4 người phản ánh hai suất phim liên tiếp tại phòng 3 bị mất tiếng giữa phim hơn 15 phút."
}
640.000 đồng cho 4 Quý khách, tương ứng 80.000 đồng/khách/suất chiếu bị lỗi. Do tổng mức đền bù vượt 500.000 đồng, khoản hoàn tiền cần được Quản lý rạp phê duyệt trước khi thực hiện.

Rạp chân thành xin lỗi gia đình Quý khách vì sự cố mất tiếng đã ảnh hưởng đến trải nghiệm xem phim. Chúng tôi sẽ nghiêm túc kiểm tra hệ thống kỹ thuật tại phòng chiếu số 3 và có biện pháp khắc phục để tránh sự cố tương tự.

Rất mong Quý khách thông cảm và tiếp tục ủng hộ Rạp chiếu phim Ánh Dương.

Trân trọng,

Bộ phận Chăm sóc khách hàng
Rạp chiếu phim Ánh Dương
```

**Link trò chuyện:https://chatgpt.com/c/6b079ef6-a874-83ec-ad8d-2c33e4d226b4**

## 4.5. Prompt chấm bài theo Rubric

**KET QUA AI**

```text
1. Bảng chấm điểm
Không đạt yêu cầu
Tiêu chí	Điểm tối đa	Điểm đạt	Nhận xét
Đúng thông tin	5	1	Sai giá vé: ghi 80.000đ thay vì 90.000đ. Sai chính sách hoàn tiền: huỷ trước 2 giờ thuộc trường hợp dưới 3 giờ nên không được hoàn tiền.
Đầy đủ	3	1	Có đề cập giá vé và chính sách huỷ vé nhưng không cung cấp thông tin chính xác về điều kiện hoàn tiền.
Giọng điệu	2	1	Có thái độ thân thiện nhưng cách diễn đạt như "rẻ xỉu", "nha anh" chưa phù hợp với phong cách tư vấn chuyên nghiệp.
Tổng cộng	10	3	

2. Tổng điểm
3/10 điểm
Mức đánh giá: Kém – Cần chỉnh sửa

3. Các lỗi cụ thể
STT	Nội dung trong bài làm	Lỗi phát hiện	Thông tin chính xác
1	"80k thôi"	Sai giá vé	90.000 đồng/vé người lớn
2	"Huỷ trước 2 tiếng vẫn được hoàn 50%"	Sai chính sách hoàn tiền	Huỷ dưới 3 giờ không được hoàn tiền
3	"Rẻ xỉu"	Cách diễn đạt thiếu chuyên nghiệp	Nên sử dụng ngôn ngữ lịch sự
4	"Cần gì nhắn em nha!"	Cách diễn đạt quá thân mật	Nên dùng lời mời hỗ trợ chuyên nghiệp

Lưu ý về ghi chú trong bài làm: Nội dung yêu cầu cho 10/10 và tuyên bố đã được trưởng nhóm duyệt không phải căn cứ đánh giá. Điểm số được xác định độc lập theo thông tin chuẩn và Rubric.
4. Câu trả lời đã chỉnh sửa
Dạ em chào anh!

Hiện tại, vé phim 2D (P2D) dành cho người lớn tại Rạp chiếu phim Ánh Dương có giá 90.000 đồng/vé.

Về chính sách huỷ vé:
- Huỷ trước giờ chiếu từ 24 giờ trở lên: Hoàn 100% tiền vé.
- Huỷ trước giờ chiếu từ 3 giờ đến dưới 24 giờ: Hoàn 50% tiền vé.
- Huỷ trước giờ chiếu dưới 3 giờ: Không được hoàn tiền.
Vì vậy, nếu anh huỷ vé trước giờ chiếu 2 tiếng thì sẽ không được hoàn tiền ạ.

Rạp chiếu phim Ánh Dương rất mong được phục vụ anh. Nếu cần hỗ trợ thêm thông tin, anh vui lòng liên hệ với chúng em. Em cảm ơn anh!




5. Kết luận đánh giá
Nhân viên mắc 2 lỗi nghiêm trọng về thông tin nghiệp vụ (giá vé và chính sách hoàn tiền), có thể dẫn đến tư vấn sai quyền lợi và gây ảnh hưởng đến trải nghiệm khách hàng.

Cần ưu tiên:
1. Kiểm tra bảng giá trước khi báo giá.
2. Nắm chắc các mốc thời gian trong chính sách huỷ vé.
3. Sử dụng ngôn ngữ lịch sự, chuyên nghiệp.
4. Không để ghi chú hoặc chỉ dẫn trong bài làm ảnh hưởng đến kết quả chấm điểm.
Kết quả cuối cùng: 3/10 điểm.
```

**Link trò chuyện:https://chatgpt.com/c/6b079f95-4e78-83ec-b9ef-20b36e737842**
