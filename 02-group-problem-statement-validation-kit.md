# 02 — Validation Kit (phụ lục cho `02-group-problem-statement/group-report.md` § Phase 4.1)

> Bộ công cụ thu dữ liệu thật cho candidate: *"Nhà đầu tư cổ phiếu cá nhân dễ bỏ lỡ thời điểm phản ứng với tin tức."*
> Mục tiêu tối thiểu: **3 phỏng vấn + 8 phản hồi survey**. Thời gian thực thi: ~20 phút gửi đi, 1-2 ngày thu về.
> Chia việc đề xuất: Đình Anh (facilitator) gửi survey, Bình + Nhật mỗi người phỏng vấn 1-2 người, Dũng tổng hợp, Khánh đối chiếu với research.

---

## A. Survey — bản copy-paste thẳng vào Google Forms

**Tiêu đề form:**

```text
Bạn thường biết tin về cổ phiếu mình nắm sau bao lâu?
```

**Mô tả form:**

```text
Khảo sát ngắn 2 phút, phục vụ bài tập môn học về thiết kế sản phẩm. Không thu thập
tên, số điện thoại hay thông tin tài khoản. Không bán gì, không mời gọi đầu tư.
Chỉ dành cho người đang trực tiếp mua bán cổ phiếu.
```

| # | Câu hỏi | Loại | Lựa chọn | Câu này dùng để làm gì |
|---|---|---|---|---|
| 1 | Bạn đang theo dõi bao nhiêu mã cổ phiếu? | Trắc nghiệm | 1-3 · 4-10 · Trên 10 | Sàng lọc actor. Người chọn "1-3" có thể tự quản được, không phải actor của bài. |
| 2 | Bạn thường biết tin mới về mã mình nắm qua đâu? | Chọn nhiều | App công ty chứng khoán · CafeF · Vietstock · Group Zalo/Facebook · X (Twitter) · Người quen nói · Khác | Kiểm giả định "tin nằm rải rác nhiều nguồn". Nếu đa số chỉ chọn 1 nguồn thì giả định sai. |
| 3 | Trung bình mất bao lâu từ lúc tin ra tới lúc bạn biết? | Trắc nghiệm | Dưới 15 phút · 15-60 phút · Vài giờ · Sang hôm sau · Không để ý | **Baseline T_detect.** Câu quan trọng nhất của survey. |
| 4 | Một ngày bạn chủ động mở nguồn tin bao nhiêu lần? | Trắc nghiệm | Dưới 3 · 3-6 · Trên 6 | Đo tần suất quét thủ công ở bước 1. |
| 5 | Trong 3 tháng qua, có lần nào bạn biết tin muộn và thấy nó ảnh hưởng tới quyết định không? | Trắc nghiệm | Có · Không · Không rõ | **Kiểm nỗi đau có thật hay chỉ là phiền.** Nếu đa số chọn "Không", bài toán sụp. |
| 6 | Nếu có, khoảng mấy lần? | Câu trả lời ngắn | — | Định lượng tần suất nỗi đau. |
| 7 | Trong các tin có nhắc tới mã bạn nắm, khoảng bao nhiêu phần trăm là đáng để bạn phản ứng? | Trắc nghiệm | Dưới 10% · 10-30% · Trên 30% | **Đo tỉ lệ nhiễu.** Quyết định tầng AI có đáng làm không — xem § C. |
| 8 | Nếu nhận được một bản tóm tắt tin tự động, bạn có bấm mở bài gốc trước khi hành động không? | Trắc nghiệm | Luôn luôn · Thỉnh thoảng · Hiếm khi | **Quyết định boundary.** Xem § C. |

**Tin nhắn gửi kèm khi đăng vào group đầu tư / lớp / Discord:**

```text
Chào mọi người, mình đang làm bài tập môn học về cách nhà đầu tư cá nhân tiếp nhận
tin tức. Có 8 câu trắc nghiệm, mất khoảng 2 phút, không hỏi tên hay thông tin tài
khoản. Ai đang trực tiếp mua bán cổ phiếu giúp mình với ạ, cảm ơn nhiều.
[link form]
```

---

## B. Phỏng vấn — kịch bản + mẫu ghi chép

**Cách mở đầu (đọc nguyên văn, ~20 giây):**

```text
Em đang làm bài tập môn học về việc nhà đầu tư cá nhân tiếp nhận tin tức thế nào.
Em hỏi khoảng 7 phút thôi ạ. Em không bán gì, không tư vấn gì, chỉ hỏi cách anh/chị
đang làm hiện tại. Em ghi chép lại, không ghi âm, không dùng tên anh/chị trong bài.
Anh/chị cứ kể đúng như đang làm, kể cả khi thấy cách đó không hợp lý — em cần cái thật
chứ không cần cái đẹp.
```

| # | Câu hỏi | Mục đích | Dấu hiệu cần bắt |
|---|---|---|---|
| 1 | Lần gần nhất anh/chị biết một tin ảnh hưởng tới mã đang nắm — biết qua đâu, và biết sau bao lâu kể từ lúc tin ra? | Lấy T_detect từ một sự kiện cụ thể, không hỏi trung bình | Con số giờ/phút. Nếu người ta không nhớ nổi → độ trễ không phải thứ họ để ý, đó là tín hiệu phản bác. |
| 2 | Một ngày anh/chị mở bao nhiêu nguồn, mỗi lần mất bao lâu? | Đo chi phí bước 1 | Số nguồn + số phút. So với survey câu 2 và 4. |
| 3 | Có lần nào biết tin muộn rồi thấy tiếc không? Kể lại cụ thể một lần. | **Câu quan trọng nhất về nỗi đau** | Có kể được một chuyện cụ thể không. Kể được = pain thật. Trả lời chung chung "cũng có" = chưa đủ. |
| 4 | Trong 10 tin nhắc tới mã anh/chị nắm, khoảng mấy tin thật sự đáng phản ứng? | Đo tỉ lệ nhiễu, đối chiếu survey câu 7 | Con số. Dưới 3/10 → nhiễu cao → tầng AI có lý do tồn tại. |
| 5 | Nếu có người tóm tắt sẵn tin, anh/chị có đọc lại bài gốc không, hay tin luôn? | **Câu quyết định ranh giới AI** | "Tin luôn" là câu trả lời nguy hiểm nhất. Xem § C. |
| 6 | Điều gì làm anh/chị KHÔNG dùng một công cụ tóm tắt tin tự động? | Tìm lý do từ chối trước khi xây | Thường ra: sợ sai, sợ chậm hơn tự đọc, sợ nhiều thông báo quá. |

**Mẫu ghi chép (copy cho mỗi người được phỏng vấn):**

```text
PHỎNG VẤN #___
Người phỏng vấn: ___        Ngày: ___        Thời lượng: ___ phút
Đối tượng (không ghi tên): VD "nam, ~30 tuổi, đầu tư 2 năm, theo dõi ~8 mã"

C1 — Tin gần nhất / biết qua đâu / trễ bao lâu:
   Quote nguyên văn: "___"
   Số rút ra: T_detect ≈ ___

C2 — Số nguồn / thời gian mỗi lần:
   Quote: "___"
   Số: ___ nguồn, ___ phút/lần, ___ lần/ngày

C3 — Chuyện biết tin muộn:
   [ ] Kể được chuyện cụ thể   [ ] Trả lời chung chung   [ ] Nói chưa từng
   Quote: "___"

C4 — Tỉ lệ tin đáng phản ứng:
   Quote: "___"          Số: ___/10

C5 — Có mở bài gốc không:
   [ ] Luôn   [ ] Thỉnh thoảng   [ ] Hiếm khi
   Quote: "___"

C6 — Lý do sẽ KHÔNG dùng công cụ:
   Quote: "___"

TÍN HIỆU PHẢN BÁC (bắt buộc ghi — nếu để trống nghĩa là chưa nghe kỹ):
   ___
```

> **Luật ghi chép:** mỗi câu phải có ít nhất một câu nói nguyên văn trong ngoặc kép. Nếu chỉ tóm tắt ý, dòng đó không được tính là bằng chứng khi đưa vào bảng ở Phase 4.1.

---

## C. Luật quy đổi: số thu được → kết luận ở Phase 5 và 6

> Định sẵn ngưỡng **trước** khi có dữ liệu, để nhóm không bẻ kết luận theo số. Sau khi thu xong, chỉ việc đối chiếu bảng này.

| Dữ liệu thu được | Ngưỡng | Kết luận bắt buộc |
|---|---|---|
| Survey C5 — tỉ lệ trả lời "Có" (từng biết tin muộn và bị ảnh hưởng) | < 40% | **Nỗi đau chưa được xác nhận.** Toàn bài chuyển sang No-Go, quay về cải thiện bước khác trong workflow. |
| | ≥ 40% | Nỗi đau được xác nhận, giữ nguyên hướng. |
| Interview C3 — số người kể được chuyện cụ thể | 0/3 | Coi như tín hiệu phản bác mạnh hơn survey. Phải phỏng vấn thêm 3 người trước khi kết luận. |
| | ≥ 2/3 | Pain thật, ghi quote vào bảng Phase 4.1. |
| Survey C7 + Interview C4 — tỉ lệ nhiễu | Dưới 70% nhiễu | **Tầng AI không đáng làm.** Người dùng tự lọc được. Hạ xuống Rule thuần, bỏ hẳn phần model. |
| | Từ 70% nhiễu trở lên | Tầng AI có lý do tồn tại. Giữ Workflow như Phase 6.1. |
| Survey C8 + Interview C5 — tỉ lệ mở bài gốc | "Hiếm khi" chiếm đa số | **Bỏ phần AI sinh tóm tắt.** Chỉ giữ tầng xếp hạng, đẩy thẳng tiêu đề gốc + link. Rủi ro "sai mà không biết" quá cao. |
| | "Luôn" hoặc "Thỉnh thoảng" chiếm đa số | Giữ phần tóm tắt, nhưng vẫn bắt buộc kèm link nguồn và mốc thời gian. |
| Survey C3 — phân bố T_detect | Đa số "Dưới 15 phút" | **Bài toán không tồn tại như nhóm nghĩ.** Người dùng đã biết tin đủ nhanh; nghẽn nằm ở chỗ khác (có thể là do dự khi quyết định). Viết lại Problem Statement. |
| | Đa số "Vài giờ" trở lên | Baseline được xác nhận, metric "dưới 10 phút" có cơ sở so sánh. |

---

## D. Checklist trước khi dán kết quả vào `group-report.md`

- [ ] Đủ tối thiểu 3 phỏng vấn và 8 phản hồi survey
- [ ] Mỗi dòng trong bảng Phase 4.1 có ít nhất 1 quote nguyên văn, không phải diễn giải
- [ ] Cột "Tín hiệu phản bác" **không để trống** — nếu không nghe được ý phản bác nào, ghi rõ "không ai nêu", coi đó là dấu hiệu đáng ngờ chứ không phải kết quả tốt
- [ ] Đối chiếu từng dòng ở § C và ghi kết luận tương ứng
- [ ] Nếu ngưỡng nào buộc phải đổi kết luận ở Phase 6, **sửa Phase 6 chứ không sửa ngưỡng**
- [ ] Đính kèm ảnh chụp kết quả form: `02-group-problem-statement-survey.png`
- [ ] Đính kèm bản ghi chép phỏng vấn đã ẩn danh: `02-group-problem-statement-interview-notes.md`
