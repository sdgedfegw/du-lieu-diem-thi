# Dữ liệu điểm thi Tuyển sinh Đại học - Cao đẳng 2013-2014, THPT Quốc gia 2016-2019 và Tốt nghiệp THPT 2020-2025

## Trường dữ liệu

### 2013-2014
| Trường | Mô tả |
| :--- | :--- |
| **Nam** | Năm thí sinh dự thi (dãy 2 số, 13 hoặc 14). |
| **Tinh** | Mã tỉnh hoặc thành phố dự thi của thí sinh (2 số, từ 1 đến 64). [Xem tại đây](https://luatminhkhue.vn/danh-sach-ma-tinh-ma-huyen-ma-xa-thi-thpt-quoc-gia.aspx) |
| **KyThi** | Phân biệt thí sinh thi Đại học hay thi Cao đẳng |
| **DH** | Mã trường Đại học hoặc Cao đẳng mà thí sinh dự thi. |
| **Khoi** | Mã khối thi của thí sinh. |
| **SBD** | Số báo danh của thí sinh (dãy 6 số dạng str). |
| **HovaTen**| Họ và tên của thí sinh (Lưu ý: Năm 2014 bị lỗi font) |
| **NgaySinh**| Ngày tháng năm sinh của thí sinh (dãy 6 số; 2 số đầu là ngày, 2 số giữa là tháng và 2 số sau cùng là năm; "000000" tương ứng với để trống). |
| **Mon1** | Điểm số của môn đầu tiên mà thí sinh dự thi trong kỳ thi tương ứng với mã khối thi (mỗi năm 1 khác, môn 1 thường là môn chính như Toán hoặc Ngữ văn; xem ở bên dưới) ; 4 số, ví dụ 1000 tương ứng với 10.00 điểm, 425 tương ứng với 4.25 điểm). |
| **Mon2** | Điểm số của môn thứ 2 mà thí sinh dự thi trong kỳ thi tương ứng với mã khối thi; 4 số. |
| **Mon3** | Điểm số của môn thứ 3 mà thí sinh dự thi trong kỳ thi tương ứng với mã khối thi; 4 số. |
| **TongDiem**| Tổng điểm số 3 môn thi của khối thi mà thí sinh dự thi (điểm trần, chưa cộng điểm vùng, điểm ưu tiên); 4 số. |

| Khối thi   | Môn 1  | Môn 2     | Môn 3     |
|------------|--------|-----------|-----------|
| Khối A     | Toán   | Vật lí    | Hóa học   |
| Khối A1    | Toán   | Vật lí    | Tiếng Anh |
| Khối B     | Toán   | Sinh học  | Hóa học   |
| Khối C     | Địa lí | Lịch sử   | Ngữ văn   |
| Khối D1-D6 | Toán   | Ngoại ngữ | Ngữ văn   |

### 2016

| Trường        | Mô tả                                                                                                                                                                                                                                                                    |
|---------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| SBD          | Số báo danh gốc của thí sinh.                                                                                                                                                                           |
| Nam          | Năm thí sinh dự thi (dãy 2 số, 16 = 2016).                                                                                                                                                                           |
| Tinh          | 2 loại dữ liệu: Mã cụm thi đại học của thí sinh (của những thí sinh xét tuyển đại học) gồm dãy 3 chữ chứa mã cụm thi đại học thí sinh dự thi (Ví dụ: BKA) và Mã cụm thi địa phương của thí sinh (của những thí sinh không xét tuyển đại học) (2 số, từ 1 đến 64). Xem [danh sách cụm thi đại học](https://thi.tuyensinh247.com/danh-sach-cum-thi-thpt-quoc-gia-nam-2016-c24a25674.html) và [danh sách cụm thi địa phương](https://luatminhkhue.vn/danh-sach-ma-tinh-ma-huyen-ma-xa-thi-thpt-quoc-gia.aspx) tại đây                                                                                                                                                                           |
| SBD_New           | Số báo danh của thí sinh (đã chuyển thành int).                       |
| Toan          | Điểm môn Toán (tự luận)của thí sinh với thang điểm 10 và 0.25 điểm/1 câu đúng (tổng 50 câu).                                                                                                                                                                           |
| NguVan        | Điểm môn Ngữ văn (tự luận) của thí sinh với thang điểm 10 và làm tròn tới 0.25 điểm.                                                                                                                                                                                           |
| VatLy         | Điểm môn Vật lí (trắc nghiệm) của thí sinh với thang điểm 10 và 0.2 điểm/1 câu đúng (tổng 50 câu).                                                                                                                                                                        |
| HoaHoc        | Điểm môn Hóa học (trắc nghiệm) của thí sinh với thang điểm 10 và 0.2 điểm/1 câu đúng (tổng 50 câu).                                                                                                                                                                       |
| SinhHoc       | Điểm môn Sinh học (trắc nghiệm) của thí sinh với thang điểm 10 và 0.2 điểm/1 câu đúng (tổng 50 câu).                                                                                                                                                                      |
| LichSu        | Điểm môn Lịch sử (tự luận) của thí sinh với thang điểm 10 và làm tròn tới 0.25 điểm.                                                                                                                                                                       |
| DiaLy         | Điểm môn Địa lí (tự luận) của thí sinh với thang điểm 10 và làm tròn tới 0.25 điểm.                                                                                                                                                                        |
| GDCD          | Điểm môn Giáo dục công dân (trắc nghiệm) của thí sinh với thang điểm 10 và 0.25 điểm/1 câu đúng (tổng 40 câu).                                                                                                                                                             |
| NgoaiNgu      | Điểm của 1 trong 7 môn Ngoại ngữ của thí sinh với thang điểm 10. Đề thi bao gồm 64 câu trắc nghiệm (0.125 điểm), 5 câu trả lời ngắn (0.2 điểm) và 1 câu tự luận (1 điểm).                                                                                                                                                       |
| MaMonNgoaiNgu | Mã môn Ngoại ngữ của thí sinh, với N1 – Tiếng Anh; N2 – Tiếng Nga; N3 – Tiếng Pháp; N4 – Tiếng Trung Quốc; N5 – Tiếng Đức; N6 – Tiếng Nhật; N7 - Tiếng Hàn.                                                                                                                              |
| TongDiem | Tổng điểm 6 môn thi của thí sinh với thang điểm 60. Công thức tính: Toán + Ngữ văn + Ngoại ngữ + Khoa học tự nhiên (Vật lí, Hóa học, Sinh học).  |
| KhoiA | Tổng điểm Tổ hợp A00 của thí sinh với thang điểm 30. Công thức tính: Toán + Vật lí + Hóa học. (Loại trừ những thí sinh không thi bất kỳ 1 trong 3 môn hoặc điểm của 1 trong 3 môn = 0) |
| KhoiA1 | Tổng điểm Tổ hợp A01 của thí sinh với thang điểm 30. Công thức tính: Toán + Vật lí + Ngoại ngữ. (Loại trừ những thí sinh không thi bất kỳ 1 trong 3 môn hoặc điểm của 1 trong 3 môn = 0) |
| KhoiB | Tổng điểm Tổ hợp B00 của thí sinh với thang điểm 30. Công thức tính: Toán + Hóa học + Sinh học. (Loại trừ những thí sinh không thi bất kỳ 1 trong 3 môn hoặc điểm của 1 trong 3 môn = 0) |
| KhoiC | Tổng điểm Tổ hợp C00 của thí sinh với thang điểm 30. Công thức tính: Ngữ văn + Lịch sử + Địa lí. (Loại trừ những thí sinh không thi bất kỳ 1 trong 3 môn hoặc điểm của 1 trong 3 môn = 0) |
| KhoiD | Tổng điểm Tổ hợp D00 của thí sinh với thang điểm 30. Công thức tính: Toán + Ngữ văn + Ngoại ngữ. (Loại trừ những thí sinh không thi bất kỳ 1 trong 3 môn hoặc điểm của 1 trong 3 môn = 0) |
| KhoiA02 | Tổng điểm Tổ hợp A02 của thí sinh với thang điểm 30. Công thức tính: Toán + Vật lí + Sinh học. (Loại trừ những thí sinh không thi bất kỳ 1 trong 3 môn hoặc điểm của 1 trong 3 môn = 0) |
| KhoiC01 | Tổng điểm Tổ hợp C01 của thí sinh với thang điểm 30. Công thức tính: Toán + Ngữ văn + Vật lí. (Loại trừ những thí sinh không thi bất kỳ 1 trong 3 môn hoặc điểm của 1 trong 3 môn = 0) |
| KhoiD07 | Tổng điểm Tổ hợp D07 của thí sinh với thang điểm 30. Công thức tính: Toán + Hóa học + Ngoại ngữ. (Loại trừ những thí sinh không thi bất kỳ 1 trong 3 môn hoặc điểm của 1 trong 3 môn = 0) |
| KHTN | Điểm trung bình giữa 3 môn Khoa học tự nhiên (Vật lí - Hóa học - Sinh học) của thí sinh. (Loại trừ những thí sinh không thi bất kỳ 1 trong 3 môn hoặc điểm của 1 trong 3 môn = 0) |
| KHXH |  |
| TongDiemKHTN | Tổng điểm 6 môn thi của thí sinh với thang điểm 60. Công thức tính: Toán + Ngữ văn + Ngoại ngữ + Khoa học tự nhiên (Vật lí, Hóa học, Sinh học). (Loại trừ những thí sinh không thi bất kỳ 1 trong 6 môn hoặc điểm của 1 trong 6 môn = 0) |
| TongDiemKHXH |  |

### 2017-2025

* Lưu ý: Dữ liệu năm 2025 dựa theo format này chỉ bao gồm thí sinh tự do dự thi chương trình 2006.

| Trường        | Mô tả                                                                                                                                                                                                                                                                    |
|---------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| SBD          | Số báo danh gốc của thí sinh.                                                                                                                                                                           |
| Nam          | Năm thí sinh dự thi (dãy 2 số, từ 17 đến 25, tương ứng với 2017 đến 2025).                                                                                                                                                                           |
| Tinh          | Mã tỉnh hoặc thành phố dự thi của thí sinh (2 số, từ 1 đến 64). [Xem tại đây](https://luatminhkhue.vn/danh-sach-ma-tinh-ma-huyen-ma-xa-thi-thpt-quoc-gia.aspx)                                                                                                                                                                           |
| SBD_New           | Số báo danh của thí sinh (6 số, từ 1 đến 108573).                       |
| Toan          | Điểm môn Toán (trắc nghiệm) của thí sinh với thang điểm 10 và 0.2 điểm/1 câu đúng (tổng 50 câu).                                                                                                                                                                           |
| NguVan        | Điểm môn Ngữ văn (tự luận) của thí sinh với thang điểm 10 và làm tròn tới 0.25 điểm.                                                                                                                                                                                           |
| VatLy         | Điểm môn Vật lí (trắc nghiệm) của thí sinh với thang điểm 10 và 0.25 điểm/1 câu đúng (tổng 40 câu).                                                                                                                                                                        |
| HoaHoc        | Điểm môn Hóa học (trắc nghiệm) của thí sinh với thang điểm 10 và 0.25 điểm/1 câu đúng (tổng 40 câu).                                                                                                                                                                       |
| SinhHoc       | Điểm môn Sinh học (trắc nghiệm) của thí sinh với thang điểm 10 và 0.25 điểm/1 câu đúng (tổng 40 câu).                                                                                                                                                                      |
| LichSu        | Điểm môn Lịch sử (trắc nghiệm) của thí sinh với thang điểm 10 và 0.25 điểm/1 câu đúng (tổng 40 câu).                                                                                                                                                                       |
| DiaLy         | Điểm môn Địa lí (trắc nghiệm) của thí sinh với thang điểm 10 và 0.25 điểm/1 câu đúng (tổng 40 câu).                                                                                                                                                                        |
| GDCD          | Điểm môn Giáo dục công dân (trắc nghiệm) của thí sinh với thang điểm 10 và 0.25 điểm/1 câu đúng (tổng 40 câu).                                                                                                                                                             |
| NgoaiNgu      | Điểm của 1 trong 7 môn Ngoại ngữ (trắc nghiệm) của thí sinh với thang điểm 10 và 0.25 điểm/1 câu đúng (tổng 40 câu).                                                                                                                                                       |
| MaMonNgoaiNgu | Mã môn Ngoại ngữ của thí sinh, với N1 – Tiếng Anh; N2 – Tiếng Nga; N3 – Tiếng Pháp; N4 – Tiếng Trung Quốc; N5 – Tiếng Đức; N6 – Tiếng Nhật; N7 - Tiếng Hàn.                                                                                                                              |
| TongDiem | Tổng điểm 6 môn thi của thí sinh với thang điểm 60. Công thức tính: Toán + Ngữ văn + Ngoại ngữ + Khoa học tự nhiên (Vật lí, Hóa học, Sinh học) hoặc Khoa học xã hội (Lịch sử, Địa lí và Giáo dục công dân). Nếu thí sinh thi cả 2 khối Khoa học tự nhiên và Khoa học xã hội, tổng điểm sẽ là điểm cao hơn giữa tổng điểm 2 khối.  |
| KhoiA | Tổng điểm Tổ hợp A00 của thí sinh với thang điểm 30. Công thức tính: Toán + Vật lí + Hóa học. (Loại trừ những thí sinh không thi bất kỳ 1 trong 3 môn hoặc điểm của 1 trong 3 môn = 0) |
| KhoiA1 | Tổng điểm Tổ hợp A01 của thí sinh với thang điểm 30. Công thức tính: Toán + Vật lí + Ngoại ngữ. (Loại trừ những thí sinh không thi bất kỳ 1 trong 3 môn hoặc điểm của 1 trong 3 môn = 0) |
| KhoiB | Tổng điểm Tổ hợp B00 của thí sinh với thang điểm 30. Công thức tính: Toán + Hóa học + Sinh học. (Loại trừ những thí sinh không thi bất kỳ 1 trong 3 môn hoặc điểm của 1 trong 3 môn = 0) |
| KhoiC | Tổng điểm Tổ hợp C00 của thí sinh với thang điểm 30. Công thức tính: Ngữ văn + Lịch sử + Địa lí. (Loại trừ những thí sinh không thi bất kỳ 1 trong 3 môn hoặc điểm của 1 trong 3 môn = 0) |
| KhoiD | Tổng điểm Tổ hợp D00 của thí sinh với thang điểm 30. Công thức tính: Toán + Ngữ văn + Ngoại ngữ. (Loại trừ những thí sinh không thi bất kỳ 1 trong 3 môn hoặc điểm của 1 trong 3 môn = 0) |
| KhoiA02 | Tổng điểm Tổ hợp A02 của thí sinh với thang điểm 30. Công thức tính: Toán + Vật lí + Sinh học. (Loại trừ những thí sinh không thi bất kỳ 1 trong 3 môn hoặc điểm của 1 trong 3 môn = 0) |
| KhoiC01 | Tổng điểm Tổ hợp C01 của thí sinh với thang điểm 30. Công thức tính: Toán + Ngữ văn + Vật lí. (Loại trừ những thí sinh không thi bất kỳ 1 trong 3 môn hoặc điểm của 1 trong 3 môn = 0) |
| KhoiD07 | Tổng điểm Tổ hợp D07 của thí sinh với thang điểm 30. Công thức tính: Toán + Hóa học + Ngoại ngữ. (Loại trừ những thí sinh không thi bất kỳ 1 trong 3 môn hoặc điểm của 1 trong 3 môn = 0) |
| KHTN | Điểm trung bình giữa 3 môn Khoa học tự nhiên (Vật lí - Hóa học - Sinh học) của thí sinh. (Loại trừ những thí sinh không thi bất kỳ 1 trong 3 môn hoặc điểm của 1 trong 3 môn = 0) |
| KHXH | Điểm trung bình giữa 3 môn Khoa học xã hội (Lịch sử - Địa lí - Giáo dục công dân) của thí sinh. (Loại trừ những thí sinh không thi bất kỳ 1 trong 3 môn hoặc điểm của 1 trong 3 môn = 0) |
| TongDiemKHTN | Tổng điểm 6 môn thi của thí sinh với thang điểm 60. Công thức tính: Toán + Ngữ văn + Ngoại ngữ + Khoa học tự nhiên (Vật lí, Hóa học, Sinh học). (Loại trừ những thí sinh không thi bất kỳ 1 trong 6 môn hoặc điểm của 1 trong 6 môn = 0) |
| TongDiemKHXH | Tổng điểm 6 môn thi của thí sinh với thang điểm 60. Công thức tính: Toán + Ngữ văn + Ngoại ngữ + Khoa học xã hội (Lịch sử, Địa lí và Giáo dục công dân).  (Loại trừ những thí sinh không thi bất kỳ 1 trong 6 môn hoặc điểm của 1 trong 6 môn = 0) |

### 2025

| Trường        | Mô tả                                                                                                                                                                                                                                                                    |
|---------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| SBD          | Số báo danh gốc của thí sinh.                                                                                                                                                                           |
| Nam          | Năm thí sinh dự thi (dãy 2 số, hiện tại chỉ có 25, tương ứng với năm 2025).                                                                                                                                                                           |
| Tinh          | Mã tỉnh hoặc thành phố dự thi của thí sinh (2 số, từ 1 đến 64). [Xem tại đây](https://luatminhkhue.vn/danh-sach-ma-tinh-ma-huyen-ma-xa-thi-thpt-quoc-gia.aspx)                                                                                                                                                                           |
| SBD_New           | Số báo danh của thí sinh (6 số, từ 1 đến 124072).                       |
| Toan          | Điểm môn Toán của thí sinh với thang điểm 10. Đề thi bao gồm 12 câu trắc nghiệm (0.25 điểm), 4 câu đúng sai (0.1/0.25/0.5/1 điểm với 1/2/3/4 ý đúng mỗi câu) và 6 câu trả lời ngắn (0.5 điểm).                                                                                                                                                                           |
| NguVan        | Điểm môn Ngữ văn (tự luận) của thí sinh với thang điểm 10 và làm tròn tới 0.25 điểm.                                                                                                                                                                                           |
| VatLy         | Điểm môn Vật lí của thí sinh với thang điểm 10. Đề thi bao gồm 18 câu trắc nghiệm (0.25 điểm), 4 câu đúng sai (0.1/0.25/0.5/1 điểm với 1/2/3/4 ý đúng mỗi câu) và 6 câu trả lời ngắn (0.25 điểm).                                                                                                                                                                        |
| HoaHoc        | Điểm môn Hóa học của thí sinh với thang điểm 10. Đề thi bao gồm 18 câu trắc nghiệm (0.25 điểm), 4 câu đúng sai (0.1/0.25/0.5/1 điểm với 1/2/3/4 ý đúng mỗi câu) và 6 câu trả lời ngắn (0.25 điểm).                                                                                                                                                                       |
| SinhHoc       | Điểm môn Sinh học của thí sinh với thang điểm 10. Đề thi bao gồm 18 câu trắc nghiệm (0.25 điểm), 4 câu đúng sai (0.1/0.25/0.5/1 điểm với 1/2/3/4 ý đúng mỗi câu) và 6 câu trả lời ngắn (0.25 điểm).                                                                                                                                                                      |
| LichSu        | Điểm môn Lịch sử của thí sinh với thang điểm 10. Đề thi bao gồm 24 câu trắc nghiệm (0.25 điểm), 4 câu đúng sai (0.1/0.25/0.5/1 điểm với 1/2/3/4 ý đúng mỗi câu).                                                                                                                                                                       |
| DiaLy         | Điểm môn Địa lí của thí sinh với thang điểm 10. Đề thi bao gồm 18 câu trắc nghiệm (0.25 điểm), 4 câu đúng sai (0.1/0.25/0.5/1 điểm với 1/2/3/4 ý đúng mỗi câu) và 6 câu trả lời ngắn (0.25 điểm).                                                                                                                                                                        |
| KinhTePhapLuat          | Điểm môn Giáo dục Kinh tế - Pháp luật của thí sinh với thang điểm 10. Đề thi bao gồm 24 câu trắc nghiệm (0.25 điểm), 4 câu đúng sai (0.1/0.25/0.5/1 điểm với 1/2/3/4 ý đúng mỗi câu).                                                                                                                                                             |
| TinHoc          | Điểm môn Tin học của thí sinh với thang điểm 10. Đề thi bao gồm 24 câu trắc nghiệm (0.25 điểm), 4 câu đúng sai (0.1/0.25/0.5/1 điểm với 1/2/3/4 ý đúng mỗi câu).                                                                                                                                                             |
| CongNgheCongNghiep          | Điểm môn Công nghệ - Công nghiệp của thí sinh với thang điểm 10. Đề thi bao gồm 24 câu trắc nghiệm (0.25 điểm), 4 câu đúng sai (0.1/0.25/0.5/1 điểm với 1/2/3/4 ý đúng mỗi câu).                                                                                                                                                             |
| CongNgheNongNghiep          | Điểm môn Công nghệ - Nông nghiệp của thí sinh với thang điểm 10. Đề thi bao gồm 24 câu trắc nghiệm (0.25 điểm), 4 câu đúng sai (0.1/0.25/0.5/1 điểm với 1/2/3/4 ý đúng mỗi câu).                                                                                                                                                             |
| NgoaiNgu      | Điểm của 1 trong 7 môn Ngoại ngữ (trắc nghiệm) của thí sinh với thang điểm 10 và 0.25 điểm/1 câu đúng (tổng 40 câu).                                                                                                                                                       |
| MaMonNgoaiNgu | Mã môn Ngoại ngữ của thí sinh, với N1 – Tiếng Anh; N2 – Tiếng Nga; N3 – Tiếng Pháp; N4 – Tiếng Trung Quốc; N5 – Tiếng Đức; N6 – Tiếng Nhật; N7 - Tiếng Hàn.                                                                                                                              |
| TongDiem | Tổng điểm 4 môn thi bao gồm 2 môn Toán, Ngữ văn và 2 môn tự chọn của thí sinh với thang điểm 40. Công thức tính: Toán + Ngữ văn + 2 môn tự chọn (trong số Vật lí, Hóa học, Sinh học, Lịch sử, Địa lí, Giáo dục Kinh tế - Pháp luật, Ngữ văn, Tin học, Công nghệ - Công nghiệp, Công nghệ - Nông nghiệp).  |
| KhoiA | Tổng điểm Tổ hợp A00 của thí sinh với thang điểm 30. Công thức tính: Toán + Vật lí + Hóa học. (Loại trừ những thí sinh không thi bất kỳ 1 trong 3 môn hoặc điểm của 1 trong 3 môn = 0) |
| KhoiA1 | Tổng điểm Tổ hợp A01 của thí sinh với thang điểm 30. Công thức tính: Toán + Vật lí + Ngoại ngữ. (Loại trừ những thí sinh không thi bất kỳ 1 trong 3 môn hoặc điểm của 1 trong 3 môn = 0) |
| KhoiB | Tổng điểm Tổ hợp B00 của thí sinh với thang điểm 30. Công thức tính: Toán + Hóa học + Sinh học. (Loại trừ những thí sinh không thi bất kỳ 1 trong 3 môn hoặc điểm của 1 trong 3 môn = 0) |
| KhoiC | Tổng điểm Tổ hợp C00 của thí sinh với thang điểm 30. Công thức tính: Ngữ văn + Lịch sử + Địa lí. (Loại trừ những thí sinh không thi bất kỳ 1 trong 3 môn hoặc điểm của 1 trong 3 môn = 0) |
| KhoiD | Tổng điểm Tổ hợp D00 của thí sinh với thang điểm 30. Công thức tính: Toán + Ngữ văn + Ngoại ngữ. (Loại trừ những thí sinh không thi bất kỳ 1 trong 3 môn hoặc điểm của 1 trong 3 môn = 0) |
| KhoiA02 | Tổng điểm Tổ hợp A02 của thí sinh với thang điểm 30. Công thức tính: Toán + Vật lí + Sinh học. (Loại trừ những thí sinh không thi bất kỳ 1 trong 3 môn hoặc điểm của 1 trong 3 môn = 0) |
| KhoiC01 | Tổng điểm Tổ hợp C01 của thí sinh với thang điểm 30. Công thức tính: Toán + Ngữ văn + Vật lí. (Loại trừ những thí sinh không thi bất kỳ 1 trong 3 môn hoặc điểm của 1 trong 3 môn = 0) |
| KhoiD07 | Tổng điểm Tổ hợp D07 của thí sinh với thang điểm 30. Công thức tính: Toán + Hóa học + Ngoại ngữ. (Loại trừ những thí sinh không thi bất kỳ 1 trong 3 môn hoặc điểm của 1 trong 3 môn = 0) |
