# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Phạm Long Nhật
- Mã học viên: 2A202602844
- Nhóm: Fintech-Zone C
- Candidate problem nhóm chọn: Nhà đầu tư cổ phiếu cá nhân dễ bỏ lỡ thời điểm phản ứng với tin tức hoặc sự kiện doanh nghiệp, vì tin nằm rải rác nhiều nguồn và phải tự đánh giá theo từng mã.

---

## 1. Tôi đã tham gia vào phần nào?

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Scan 10 problems theo 4 lăng kính, ở 3 vùng: học tập, nhóm, vận hành. Với bài gộp file đồ án, tôi lấy được 3 số độc lập: ~70 phút mỗi lần gộp, 5-6 lượt nhắn hỏi lại, 3 lần nộp sát giờ. | Có một card đủ chắc để pitch, và có sẵn ví dụ về "số đo phải tách được" để đối chiếu với các card khác. |
| Pitch Problem Card | Pitch card gộp file đồ án trong 2 phút: workflow 7 bước, bottleneck ở bước 4-6, và điểm chính là khoảng 45/70 phút bị xoá bởi Rule chứ không phải AI. | Nhóm dùng đúng cách tách số này để soi các card còn lại — đặc biệt là tách "phần nào Rule xoá được" trước khi bàn tới AI. |
| Challenge bài của bạn khác | Hỏi Đình Anh ở card test case thủ công và hỏi Dũng ở card chốt ngưỡng cùng một câu: nếu không dùng AI thì có cách rẻ hơn giải được 70-80% không. Hỏi Đình Anh ở card jailbreak: trong nhóm mấy người đủ hiểu hệ thống để phản biện. | Hai card đầu được chính người pitch tự hạ xuống "script tự động là đủ" và "bảng tính quy đổi có thể là đủ". Câu hỏi về domain là lý do card jailbreak chỉ được 2/5 ở tiêu chí "nhóm hiểu domain" và không vào bài chính. |
| Gom trùng / cluster | Đề xuất gom 15 candidate thành 4 cụm theo pattern chung thay vì theo người pitch: vận hành hệ AI đang chạy, thông tin tài chính rải rác, cộng tác nhóm, xử lý văn bản cá nhân. | Nhìn ra cụm A có 6 bài nhưng chỉ 2/5 thành viên hiểu domain — đây là thông tin quyết định để loại cả cụm. |
| Chọn candidate problem | Bảo vệ card của mình (gộp file đồ án) đến cùng, thua ở phần tranh luận, rồi chuyển sang hỗ trợ card của Bình nhưng giữ bảo lưu rằng bài đó yếu nhất ở evidence. | Bảo lưu được nhóm ghi vào biên bản và chuyển thành điều kiện bắt buộc: phải validate xong mới được viết Problem Statement. |
| Validation / research | Kiểm HTTP từng link trước khi đưa vào bảng research; bỏ một nguồn vì không truy cập được. Rà 3 nhóm tool đã có: Google Alerts, RSS CafeF/Vietstock, FireAnt/Simplize. | Phát hiện 3/5 bước trong workflow đã được tool miễn phí giải sẵn. Nhóm cắt hẳn ý định build lại phần phát hiện tin, và thu phạm vi AI xuống còn đúng hai khoảng trống. |
| Workflow nhóm | Vẽ current workflow 5 bước kèm actor, thời gian, tần suất; đặt tên cho biến then chốt là T_detect — khoảng cách từ mốc xuất bản tin đến lúc nhà đầu tư biết. | Có một con số khách quan để đo thay vì nói "biết tin muộn". Cũng lộ ra là nhóm chưa từng đo con số đó. |
| Problem Statement | Ở v1, tách success metric làm hai phần: phần nhóm cam kết (T_detect và tỉ lệ nhiễu, đo được trong 1 tuần) và phần không cam kết (chất lượng quyết định đầu tư). | Xử lý được đúng điểm nhóm tự ghi là chưa chắc ngay từ lúc chọn bài: không lẫn tốc độ thông tin với hiệu quả quyết định. |
| Rule / Workflow / Agent | Lập luận vì sao bài rơi vào ô mơ hồ cao + phức tạp cao mà vẫn không chọn Agent: độ mơ hồ nằm trong phán đoán nội dung của một bước, không nằm trong lộ trình các bước. | Nhóm chốt Workflow có tầng Rule chạy trước, thay vì mặc định theo gợi ý của ma trận. |
| Decision | Đề xuất không trả lời Go hay Not Yet cho cả bài, mà tách theo tầng: Go tầng Rule vì rẻ và đảo ngược được, Not Yet tầng AI vì chưa có baseline và chưa biết người dùng có mở nguồn gốc không. | Nhóm có một quyết định làm được ngay tuần này, đồng thời không cam kết phần chưa đủ bằng chứng. |

**Dấu tay rõ nhất của tôi trong artifact cuối:**

```text
Hai chỗ. Một là việc tách success metric thành phần cam kết và phần không cam kết
trong Problem Statement v1. Hai là quyết định cuối được tách theo tầng thay vì một
câu Go hoặc Not Yet cho cả bài. Cả hai đều xuất phát từ cùng một thứ tôi học được
ở card của chính mình: phải tách số ra trước khi kết luận, vì cái tổng luôn giấu
mất chỗ thật sự nghẽn.
```

---

## 2. Bảng dùng AI

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Đưa bối cảnh thật (sinh viên năm cuối làm đồ án nhóm 4 người, intern báo cáo 2 tuần/lần) và nhờ gợi ý problem theo 4 lăng kính, bắt buộc mỗi dòng có actor và đơn vị đo | Khung 4 lăng kính làm tôi nhìn ra nhóm problem có handoff giữa người với người, vốn là nhóm tôi bỏ sót khi tự nghĩ — tự nghĩ thì chỉ ra toàn việc tốn thời gian của riêng mình | AI đẩy "viết báo cáo định kỳ" lên làm bài chính, trong khi đó chính là case mẫu của tài liệu lab và đề bài ghi rõ không được copy | Loại bài báo cáo khỏi vị trí số 1, chuyển xuống rank 2 và bẻ hướng phân tích sang khâu khác |
| Problem Card | Nhờ phản biện card gộp file trước khi pitch | Chỉ ra khoảng 45/70 phút thuộc về ghép file và chỉnh format, mà template cộng file chung co-edit xoá được — nghĩa là nếu tôi vẫn đặt AI làm trọng tâm thì chính tôi đang solution-first | — | Hạ vai trò AI xuống đúng một bước là soát trùng ý và thiếu ý, đưa Rule lên làm phương án chính, và thêm hẳn câu challenge "có nên No-Go riêng phần AI không" vào phần pitch |
| Workflow | Nhờ dựng cặp workflow trước/sau và chỉ ra chỗ đặt boundary | Gợi ý tách biến T_detect ra làm biến đo riêng thay vì nói chung chung là biết tin muộn | Bản đầu đặt AI ở cả bước gom nguồn lẫn bước xếp hạng | Cắt AI khỏi bước gom nguồn vì research cho thấy RSS đã làm việc đó miễn phí và không bao giờ bịa |
| Research | Nhờ liệt kê tool và pattern đã giải bài toán này | Ra được 3 nhóm nguồn đúng trọng tâm, và đặc biệt là kết luận 3/5 bước đã có tool giải sẵn | Đưa cả nguồn không truy cập được, nếu tôi không kiểm thì đã đưa link hỏng vào bài nộp | Tự kiểm mã trả về của từng link, bỏ nguồn không truy cập được, ghi ngày kiểm vào bảng |
| Problem Statement | Nhờ soi v0 xem field nào mơ hồ | Chỉ ra success metric đang đo tốc độ cung cấp thông tin trong khi vấn đề nhóm nêu là chất lượng thời điểm quyết định — hai thứ không tự động bằng nhau | — | Ở v1 tách hai loại metric và ghi thẳng là nhóm chỉ cam kết loại đo được trong một tuần |
| Rule / Workflow / Agent | Nhờ so sánh ba mức trên cùng bài và trả lời 5 câu chốt | Phân tích hai kiểu sai không đối xứng: báo thừa thì người dùng thấy ngay, còn bỏ sót thì không ai phát hiện được vì người ta không biết cái mình không nhận | Bản đầu theo ma trận và gợi ý Agent vì bài nằm ở ô mơ hồ cao cộng phức tạp cao | Giữ Workflow và viết rõ lý do: độ mơ hồ nằm trong phán đoán nội dung một bước chứ không nằm trong lộ trình, mà Agent chỉ đáng khi lộ trình là thứ không biết trước |
| Decision | Nhờ soạn phương án quyết định cuối | Đưa ra lựa chọn tách đôi theo tầng thay vì một câu trả lời cho cả bài | Bản đầu nghiêng về Go toàn bộ với một pilot nhỏ, trong khi nhóm còn hai điều tự ghi là chưa chắc | Chốt Not Yet cho tầng AI và viết ra ba điều kiện định lượng để chuyển sang Go, thay vì để Go rồi vừa làm vừa tính |

---

## 3. Reflection câu hỏi mở

**Reflection:**

```text
Điều bất ngờ nhất với tôi trong buổi lab là card của chính mình bị loại dù nó chấm
điểm bằng card được chọn. Tôi vào lab với bài gộp file đồ án, workflow 7 bước rõ
ràng, ba con số độc lập, và tôi khá chắc nó sẽ thắng vì nó là bài chắc tay nhất
trong ba bài lọt shortlist. Dũng hỏi một câu làm tôi đứng lại: bài nào buộc nhóm
phải tranh luận về việc AI được làm gì và người phải kiểm cái gì. Với bài của tôi
thì ranh giới hiển nhiên đến mức không có gì để bàn, vì đằng nào phần lớn thời gian
cũng bị Rule xoá mất rồi. Tôi nhận ra mình đang chọn bài theo tiêu chí dễ làm xong,
không phải theo tiêu chí đáng làm.

Tôi có đổi ý, nhưng không đổi hoàn toàn. Tôi chuyển sang ủng hộ bài của Bình và
đồng thời nói rõ tôi vẫn thấy nó yếu nhất ở phần bằng chứng, vì đến lúc chốt thì cả
nhóm mới chỉ có mô tả định tính từ một người, chưa có nhà đầu tư nào ngoài nhóm xác
nhận. Điều tôi thấy nhóm mình làm đúng là không gạt bảo lưu đó đi cho nhanh, mà
biến nó thành điều kiện: không được viết Problem Statement trước khi validate.

Nhóm có một lần suýt solution-first, nhưng không phải kiểu đòi làm Agent cho ngầu.
Chúng tôi định tự xây phần phát hiện tin và gắn tin với mã, cho tới khi rà lại thì
thấy Google Alerts, RSS của các trang tin trong nước và mấy nền tảng dữ liệu chứng
khoán đã làm xong ba trong năm bước, gần như miễn phí. Nếu không rà bước đó, chúng
tôi đã bỏ cả buổi để xây lại thứ có sẵn, rồi gọi đó là sản phẩm AI.

Điều khó nhất khi viết Problem Statement với tôi là metric chứ không phải boundary.
Boundary tương đối dễ vì chỉ cần trả lời AI không được làm gì: không khuyến nghị mua
bán, không nêu con số mà nguồn không nói. Metric khó hơn nhiều vì cái nhóm đo được
là thời gian từ lúc tin ra đến lúc người dùng biết, còn cái nhóm thật sự quan tâm là
nhà đầu tư có ra quyết định tốt hơn không, mà hai thứ đó không tự động kéo theo nhau.
Cuối cùng chúng tôi chọn cách thành thật: tách làm hai loại và ghi rõ nhóm chỉ cam
kết loại đo được trong một tuần.

Bài học tôi giữ lại là phải tách số ra trước khi kết luận. Ở card cá nhân, tôi từng
tưởng viết báo cáo intern nghẽn ở khâu nhớ lại việc đã làm, đến khi bấm giờ tách ra
mới thấy khâu đó chỉ mất 5 trong 30 phút. Giải pháp tôi định đề xuất là ghi một dòng
mỗi ngày, tính ra tốn khoảng 28 phút mỗi chu kỳ để tiết kiệm nhiều nhất 5 phút, tức
là giải pháp đắt hơn chính vấn đề. Nếu làm lại, tôi sẽ challenge nhóm sớm hơn ở chỗ
này: ngay ở vòng pitch, nên hỏi mỗi người cái tổng thời gian bạn nêu tách được thành
mấy phần, chứ không đợi đến lúc vẽ workflow mới tách.
```

---

## 4. Tự kiểm cuối bài

- [x] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards — 10 problems, 4 lăng kính, 3 cards đủ field
- [x] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [x] Nhóm có nhật ký hội tụ từ 15 candidates về 1 bài — cluster, shortlist, bảng score, disagreement
- [x] [15đ] Nhóm có workflow trước/sau — kèm actor, thời gian, boundary, fallback, risk mới
- [x] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ — metric tách phần cam kết và không cam kết
- [x] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent + 5 câu hỏi chốt
- [x] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ — tách theo tầng, kèm điều kiện chuyển Go và exit
- [x] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [x] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI
- [ ] **Còn lại:** phần validation ở file 02 chưa có dữ liệu thật — phải điền các ô `[chờ validation]` bằng quote nguyên văn trước khi nộp
