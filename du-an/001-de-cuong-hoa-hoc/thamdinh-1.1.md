# BÁO CÁO THẨM ĐỊNH — BẢN TÁI BẢN 1.1 "ĐỀ CƯƠNG ÔN THI KS HÓA HỌC"

- Hội đồng: Tổng biên tập (chủ trì) + Kiểm chứng viên độc lập (khác người viết, khác họ model với tác giả).
- Căn cứ: báo cáo audit độc lập trên bản 1.0; kiemchung-1.1.md; báo cáo của các tác giả vá.
- Quy ước: mỗi mục vá có kết luận Tiếp thu / Giải trình rõ ràng, không mục nào bỏ qua.

## Mục 1 — Vá lỗi hiển thị (LaTeX thô trong bản in 1.0)
- **Kết luận: TIẾP THU TOÀN BỘ — ĐÃ THỰC HIỆN, ĐẠT.**
- Bằng chứng: chuyển đổi 98 dòng công thức trong de-cuong-source.md sang text sạch; grep độc lập của kiểm chứng viên: 9/9 pattern (equiv, overset, frac, left(, right), backslash, _{, ^{, $$) = 0 hit trên toàn văn; đối chiếu 12/12 dòng mẫu với bản backup v1.0 giữ nguyên hệ số, điều kiện, chỉ số.
- **Giải trình lưu ý KT1** (phần đáp án dòng 2105–2548 không dòng nào thay đổi so với backup): đây là đúng thực tế, không phải bỏ sót — phần đáp án vốn được viết bằng text thường ngay từ bản 1.0 (không chứa LaTeX), và grep toàn văn = 0 hit bao phủ cả phần này. Các vị trí rác audit bắt được (CĐ3, CĐ4, CĐ6, CĐ7, CĐ10) đều nằm ở thân chuyên đề và đã nằm trong 98 dòng được chuyển đổi.

## Mục 2 — Phụ lục N (nền lớp 10–11: enthalpy chuẩn + đếm σ/π)
- **Kết luận: TIẾP THU TOÀN BỘ — ĐẠT.**
- Kiểm chứng tính lại độc lập khớp 100%: CH₄ theo ΔfH° = −890,3 kJ; theo Eb = −802 kJ; propane = −2219,9 kJ; ethanol theo Eb = −1247 kJ; Đ/S N.1.1 = Đ–Đ–S–Đ; σ/π: ethyl acetate 13σ/1π (kiểm chứng xác nhận con số gợi ý ban đầu "14σ" là sai, tác giả đếm đúng), glycine 9σ/1π, triolein 166σ/6π (kiểm chéo bằng độ bất bão hòa k = 6 của C₅₇H₁₀₄O₆), acetaldehyde 6σ/1π.
- Ghi chú sư phạm được chấp nhận: giá trị theo Eb là gần đúng theo năng lượng liên kết trung bình — phụ lục đã có đoạn giải thích chênh lệch Eb/ΔfH° ngay trong bài, giữ nguyên.

## Mục 3 — Bổ sung lý thuyết 8 điểm thiếu
- **Kết luận: TIẾP THU 7/8 NGUYÊN VẸN; 1 MỤC TIẾP THU CÓ SỬA (lỗi L2).**
- 7 mục đạt ngay: điều kiện áp dụng k + muối ammonium (có ví dụ số), IR phân biệt bậc amine, cộng Br₂ 1,2/1,4 của buta-1,3-diene + styrene, iodoform (đã cân bằng từng nguyên tố), HCOOH + Br₂, điện di amino acid theo pH (chiều di chuyển đúng), phân loại tơ + mạch polymer.
- **L2 (lớn, đã sửa):** mục danh pháp amine từng khẳng định tồn tại tiền tố "N,N,N-" — sai kiến thức (amine trung hòa tối đa "N,N-"). Đã xóa khẳng định này, sửa thành quy tắc đúng; các ví dụ methanamine, ethanamine, N-methylmethanamine, N,N-dimethylmethanamine giữ nguyên.

## Mục 4 — Nâng cấp bài tập Phần III (TLN vận dụng)
- **Kết luận: TIẾP THU — ĐẠT SAU SỬA L1.**
- Kiểm chứng tính lại: 10/11 câu đúng ngay (đã soi sâu B1 bảo toàn khối lượng 61,1 = 61,1 g và nước chỉ từ acid tự do; B4 chuẩn độ ngược trừ KOH dư đúng, SV = 210; B8 Glu nối tiếp 0,40 + 0,20 + 0,10 = 0,70 mol — logic đúng).
- **L1 (lớn, đã sửa):** B3 đáp án "4 triester" là sai — bỏ qua vị trí giữa của glycerol. Đáp án đúng **6 triester** (vị trí giữa 2 lựa chọn × cặp vị trí đầu đối xứng 3 lựa chọn); lời giải đã viết lại kèm cảnh báo bẫy đếm theo thành phần.
- **Giải trình số lượng:** bản giao việc nêu "10–12 câu" nhưng liệt kê chi tiết 9 câu; tác giả bổ sung B10 (tristearin → glycerol) và B11 (đốt xăng E5) đúng tinh thần phân bổ CĐ7/CĐ8 để đủ 11 câu — hội đồng chấp nhận, giữ cả 11 câu.

## Mục 5 — Bài tập đọc phổ từ hình thật
- **Kết luận: TIẾP THU CÓ SỬA (lỗi L3) — ĐẠT SAU SỬA.**
- Hình IR acetic acid đạt nguyên vẹn (C=O 1715 cm⁻¹, O–H rộng 2500–3300, C–O 1250; đã gỡ chú thích để không lộ đáp án).
- **L3 (phụ, đã sửa):** phổ MS ban đầu vẽ cột M+1 (m/z 89) cao 5% thang pic cơ sở trong khi lời giải tính 4–5% so với pic M — mâu thuẫn thang đo. Đã vẽ lại với cột 89 = 1% thang cơ sở và sửa lời giải nêu rõ hai thang (4–5% so với pic M ≈ 1% so với pic cơ sở). Đáp án M = 88 không đổi; base peak 43 giữ nguyên.

## KẾT LUẬN HỘI ĐỒNG
**ĐẠT — cho phép tích hợp và chế bản tái bản 1.1.** Cả 3 lỗi lớn/phụ (L1, L2, L3) đã sửa và có báo cáo đối chiếu; không còn lỗi treo. Khâu chế bản phải: tích hợp đúng vị trí đã đánh dấu, cập nhật trang mở đầu (phiên bản 1.1, mục lục, tổng số câu đếm lại từ bản nguồn cuối), nhúng 2 hình phổ, và bản thành phẩm phải qua duyệt bông độc lập trước khi phát hành.
