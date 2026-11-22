# PATCH NOTE — BẢN TÁI BẢN 1.1 (so với 1.0)

Ngày vá: 22/11/2026. Căn cứ: audit độc lập trên bản 1.0 (lỗi hiển thị + lỗ hổng độ khó). Bản nguồn v1.0 được lưu tại de-cuong-source-v1.0-backup.md.

## 1. Vá lỗi hiển thị (toàn văn)
- Chuyển đổi 98 dòng công thức LaTeX ($$...$$, \frac, \overset, \xrightarrow, \equiv, chỉ số _{ }) trong de-cuong-source.md thành text sạch Unicode (→, ⇌, ≡, chỉ số dưới Unicode, phân số dạng a/b).
- Hết các chuỗi rác trong bản in kiểu "CHequiv CH", "oversetH₂SO₄ đặc, t°⇌", "fracmKOH (mg)...", "left(frac...)right".
- Nghiệm thu: grep 9 pattern (equiv, overset, frac, left(, right), backslash, _{, ^{, $$) = 0 hit toàn văn, kiểm chứng độc lập xác nhận; 12/12 dòng mẫu đối chiếu backup giữ nguyên nghĩa.

## 2. Thêm Phụ lục N — Nền tảng lớp 10–11 (sau trang mở đầu, trước Phần A)
- N.1 Biến thiên enthalpy chuẩn ΔrH°₂₉₈: công thức theo ΔfH° và theo Eb (nêu rõ chiều dấu khác nhau), 2 ví dụ mẫu (CH₄ theo ΔfH° = −890,3 kJ; theo Eb = −802 kJ), bài tập: 1 câu Đ/S 4 ý + 2 TLN (propane −2219,9 kJ; ethanol theo Eb −1247 kJ).
- N.2 Đếm liên kết σ/π: quy tắc + phương pháp đếm, 2 ví dụ mẫu (ethyl acetate 13σ/1π; glycine 9σ/1π), bài tập: 1 câu Đ/S (triolein 166σ/6π) + 1 TLN (acetaldehyde 6σ/1π).

## 3. Bổ sung lý thuyết vào đúng chuyên đề
- CĐ7 (B): điều kiện áp dụng công thức độ bất bão hòa k — không áp dụng trực tiếp cho muối ammonium (HCOONH₄, CH₃NH₃Cl), kèm giải thích.
- CĐ1 (+CĐ9): phổ IR phân biệt bậc amine (bậc 1: 2 pic N–H 3300–3500 cm⁻¹; bậc 2: 1 pic; bậc 3: không có).
- CĐ3: alkadiene liên hợp (buta-1,3-diene cộng Br₂ 1,2 ở −80 °C / 1,4 ở 40 °C; isoprene) và styrene → PS.
- CĐ5: phản ứng iodoform của ethanal và methyl ketone (CHI₃ kết tủa vàng).
- CĐ6: HCOOH + Br₂ → CO₂↑ + 2HBr (HCOOH mất màu nước bromine).
- CĐ9: danh pháp thay thế IUPAC của amine (methanamine, ethanamine, N-methylmethanamine, N,N-dimethylmethanamine); tính điện di của amino acid theo pH.
- CĐ10: bảng phân loại tơ 3 nhóm (thiên nhiên / bán tổng hợp: visco, cellulose acetate / tổng hợp) + phân loại mạch polymer (không phân nhánh, phân nhánh, mạng không gian).

## 4. Thêm 11 câu TLN vận dụng (Phần III) kèm lời giải từng bước ở phần đáp án
- CĐ7: B1 xà phòng hóa chất béo + acid béo tự do (bảo toàn khối lượng, nước chỉ từ acid tự do — xà phòng 55,6 g); B2 thủy phân phenyl acetate tỉ lệ 1:2 (muối 19,8 g); B3 biện luận triester tạp chức của glycerol (6 triester — đã sửa sau kiểm chứng); B4 chỉ số xà phòng hóa chuẩn độ ngược (SV = 210); B10 tristearin → glycerol 1,84 g.
- CĐ8: B5 lên men gạo 80% tinh bột → rượu 40° (113,6 L); B6 lên men sắn 75% (ethanol tuyệt đối 79,86 L); B7 pha xăng E5 nối tiếp lên men (110,1 kg gạo); B11 đốt 1 L xăng E5 (CO₂ 1200 L đkc).
- CĐ9: B8 glutamic acid + HCl dư → + NaOH dư (0,70 mol NaOH); B9 thủy phân Gly–Gly–Ala (23,9 g amino acid).

## 5. Thêm bài tập đọc phổ từ hình thật
- pho-IR.png (CĐ1): phổ IR acetic acid, trục 4000→400 cm⁻¹ — 2 câu hỏi (nhận pic C=O 1715; phân biệt O–H acid/alcohol).
- pho-MS.png (CĐ2): phổ MS ethyl acetate — 2 câu hỏi (xác định M = 88, tránh bẫy M+1; base peak m/z 43).
- Sửa sau kiểm chứng (L3): cột M+1 vẽ lại ở mức 1% thang pic cơ sở (đúng tỉ lệ ~4–5% so với pic M), lời giải ghi rõ hai thang đo.

## 6. Sửa lỗi kiến thức bắt được ở khâu kiểm chứng chéo
- L1: B3 đáp án 4 → 6 triester, viết lại lập luận (vị trí giữa glycerol).
- L2: xóa khẳng định tiền tố "N,N,N-" không tồn tại trong mục danh pháp amine.
- L3: nhất quán số liệu M+1 giữa hình MS và lời giải (xem mục 5).

## 7. Cập nhật trang mở đầu
- Ghi rõ "Bản tái bản 1.1", tóm tắt các thay đổi; mục lục thêm Phụ lục N; tổng số câu được đếm lại từ bản nguồn sau tích hợp và cập nhật vào trang mở đầu + hướng dẫn sử dụng (ưu tiên học Phụ lục N cùng CĐ1–CĐ2).
