# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Lê Thanh Trường
- Mã học viên: 2A202602492
- Nhóm: nửa trên giữa lớp
- Vai trò trong nhóm: **Workflow**
- Candidate problem nhóm chọn: Ghi chép thông tin tư vấn bán hàng thủ công làm giảm hiệu suất nhập liệu CRM và làm đứt gãy kết nối cảm xúc với khách hàng.

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động                   | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
| ------------------------------ | ------------------------------------ | ----------------------------------- |
| Scan cá nhân                 | Tự scan 10 problems theo 4 lăng kính từ bối cảnh thật (full-time khóa Vin AI + học tiếng Anh + part-time 15-20h/tuần); chỉnh lại bối cảnh nhiều lần cho đúng thực tế | Đóng góp 3 candidates (#7 đọc tài liệu lab, #8 feedback tiếng Anh, #9 viết reflection) vào pool 15 ý của nhóm |
| Pitch Problem Card             | Pitch Card #1 "Đọc tài liệu lab để hiểu yêu cầu nộp bài" với baseline 40-60'/lab × 4-5 lab/tuần ≈ 3-5 giờ/tuần | Nhóm ghi nhận là "pain chung rõ nhất, ai cũng gật đầu", nhưng cuối cùng không được chọn để đào sâu |
| Challenge bài của bạn khác | Đặt câu hỏi cho bài của Dương Hải Minh (cảnh báo ngập lụt): nguồn dữ liệu sensor/camera thành phố có open API không, hay phụ thuộc hoàn toàn bên thứ ba | Giúp nhóm loại sớm candidate phụ thuộc hạ tầng ngoài tầm kiểm soát, gom vào cluster D |
| Gom trùng / cluster           | Cùng nhóm gom 15 ý thành 4 cluster A/B/C/D; góp ý gộp #7 (đọc tài liệu lab) và #8 (feedback tiếng Anh) vào cluster C "hỗ trợ học tập, tra cứu" | Cluster gọn lại, dễ shortlist |
| Chọn candidate problem        | Chấm điểm bảng 3.4 và đồng thuận chọn bài "Ghi chép tư vấn bán hàng" của Ân (34/35) dù bài mình pitch không trúng | Nhóm thống nhất 1 candidate duy nhất, không kéo dài tranh cãi |
| Validation / research          | Tham gia đọc lại kết quả interview 3 sales + survey 8 người; góp ý giữ ràng buộc Human Review từ câu nói của anh Tuấn (B2B SaaS) | Củng cố boundary "sales phải duyệt trước khi sync CRM" |
| Workflow nhóm                 | **Vai trò chính**: dựng workflow before (5.1 — 5 bước, ~45'/khách, bottleneck bước 4 nhập CRM 18') và after (5.2 — 5 bước, ~31', thời gian thao tác máy 3.5'), kèm bảng before/after impact và infographic minh họa | Nhóm có workflow chi tiết đến từng phút, chỉ rõ bottleneck + human boundary + fallback khi audio ồn |
| Problem Statement              | Góp phần rà field Bottleneck và Success Metric của PS v0 → v1 (đảm bảo metric có số trước/sau: 20' → <3.5', sót 25-30% → <5%) | PS v1 chặt hơn, metric đo được |
| Rule / Workflow / Agent        | Cùng nhóm lập luận vì sao hạ từ Agent xuống Workflow: đầu ra là schema 6 trường cố định, luồng tuyến tính, không cần agent tự lập kế hoạch | Nhóm chốt Workflow (STT + LLM extract + human review) |
| Decision                       | Rà tiêu chí GO và exit/rollback (dừng nếu nhận diện sai SĐT/ngân sách >20% hoặc chi phí >3.000đ/khách) | Nhóm chốt GO với pilot 15 file ghi âm |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Hai sơ đồ workflow before/after ở mục 5.1 và 5.2 (kèm bảng before/after
impact và infographic) — đúng vai trò Workflow mà nhóm phân công cho tôi.
Đây là phần tôi tự dựng và chịu trách nhiệm từng con số thời gian.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase                   | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
| ----------------------- | ---------------------------- | ---------------------- | ---------------------------- | -------------------------------------------- |
| Scan                    | Nhờ AI gợi ý problems theo 4 lăng kính sau khi đã tự nghĩ trước vài ý | Ra nhanh danh sách phủ đủ 4 lăng kính, mỗi ý có actor + số đo | **AI tự bịa các con số** (40-60', 30'/ngày, quên ~50%) — toàn ước đoán, không phải số tôi bấm giờ; AI cũng không tự biết bối cảnh thật của tôi | Chỉnh bối cảnh 3 lần ("tìm việc" → "full-time + tiếng Anh + part-time" → "4-5 lab + 4-5 lý thuyết/tuần") và tự đối chiếu lại từng con số với trải nghiệm thật |
| Problem Card            | Nhờ AI soạn 3 Problem Cards + workflow trước/sau | Đủ 11 field, workflow ASCII có bottleneck/human boundary/fallback rõ ràng | Card #2 bản đầu AI soạn là "Tailor CV khi apply việc" — **lệch hoàn toàn** bối cảnh vì tôi không còn đi xin việc | Bỏ card CV, thay bằng card "feedback tiếng Anh trễ" cho khớp; thu hẹp AI hypothesis lại |
| Workflow                | Nhờ AI dựng workflow và tạo infographic (3 biến thể, có bước verify chữ tiếng Việt bằng vision) | Nhanh, trực quan, before/after rõ bottleneck | AI dễ gộp sai bước và chữ tiếng Việt trên infographic có nguy cơ lỗi dấu; một số bước AI vẽ chưa đúng thứ tự thật | Tự kiểm lại từng bước, tách đúng bottleneck bước 4, chọn biến thể infographic ít lỗi chữ nhất |
| Research                | Không dùng AI cho phần này — research là vai trò của Dương (Fathom, Gong, Fireflies) | — | — | — |
| Problem Statement       | Nhờ AI phản biện field nào còn mơ hồ, chưa nhờ AI viết lại | Chỉ ra metric và boundary cần số đo cụ thể hơn | AI có xu hướng đề xuất solution "ngầu" (agent) sớm | Cùng nhóm hạ về Workflow, thêm số vào metric (20' → <3.5') |
| Rule / Workflow / Agent | Nhờ AI đặt câu hỏi phản biện mức chọn | Giúp soi lại "có thật sự cần Agent không" | AI không quyết định thay nhóm được | Nhóm tự chốt Workflow dựa trên tính tuyến tính của luồng |
| Decision                | Không dùng AI để chốt — nhóm tự quyết | — | — | — |
| Reflection (phase này)  | Nhờ AI dựng lại bảng hoạt động + bảng dùng AI từ artifact, và gợi ý câu hỏi tự soi | Tiết kiệm thời gian "cố nhớ" mình đã làm gì | Phần tự sự là trải nghiệm cá nhân, AI chỉ gợi ý chứ không nên viết thay cảm nhận thật | Tôi tự viết mục 3 bằng lời của mình dựa trên những gì thật sự đã diễn ra |

> Nếu phase nào không dùng AI, ghi `Không dùng` và vì sao tự làm.

---

## 3. Reflection câu hỏi mở

Chọn 3-4 câu trong 6 câu dưới để viết thành đoạn 8-12 câu (không trả lời bullet 1 dòng):

- Tôi học được gì khi nghe top 3 problems của các bạn khác?
- Nhóm có lúc nào bị solution-first, đòi làm Agent cho ngầu không?
- Tôi có thay đổi ý kiến sau khi bị challenge không, vì sao đổi?
- Tôi đóng góp gì thật sự vào artifact cuối, phần nào có dấu tay của tôi?
- Điều khó nhất khi viết Problem Statement là gì, metric hay boundary?
- Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?

**Reflection:**

```text
Điều tôi học được nhiều nhất lại đến từ chính lúc bài của mình KHÔNG được
chọn. Tôi pitch Card #1 "đọc tài liệu lab để hiểu yêu cầu nộp bài" vì tin đó
là pain chung — bản thân tôi mất 40-60 phút mỗi lab, nhân với 4-5 lab/tuần
thành 3-5 giờ chỉ để "hiểu đề". Nhưng khi nghe bài "ghi chép tư vấn bán
hàng" của Ân, tôi nhận ra bài đó có actor rõ hơn, bottleneck đo được bằng
phút và quan trọng là có giá trị kinh tế trực tiếp. Lúc đầu tôi có hơi hụt
hẫng, nhưng rồi tôi thấy việc nhóm chấm bài của Ân 34/35 là hợp lý, và tôi
chọn buông ý mình để dồn sức vào phần workflow — đúng vai trò nhóm giao.

Về cách dùng AI, tôi phải thừa nhận một điểm chưa đúng nguyên tắc: tôi đã
để AI scan Phase 1 khá sớm thay vì tự soi thật kỹ trước. AI hữu ích ở chỗ
phủ nhanh 4 lăng kính, nhưng nó tự bịa ra những con số nghe rất hợp lý mà
không phải số tôi bấm giờ, và nó còn soạn nhầm hẳn một card "tailor CV xin
việc" chẳng liên quan gì bối cảnh của tôi nữa. Chính những lần sửa card sai
và chỉnh bối cảnh tới ba lần (từ "đang tìm việc" sang "học full-time + tiếng
Anh + part-time") khiến tôi thấm rằng AI đoán được cái "nghe có vẻ đúng",
còn pain thật và số liệu thật thì chỉ mình mình có. Bài học lớn nhất với tôi
là phải dùng AI để phản biện và mở rộng góc nhìn, chứ không phải để nó nghĩ
hộ mình ngay từ đầu.

Điều khó nhất khi viết Problem Statement với tôi là phần metric: làm sao để
con số vừa tham vọng vừa đo được, nên chúng tôi phải chốt rõ "20 phút xuống
dưới 3.5 phút/khách" và "sót dữ liệu từ 25-30% xuống dưới 5%" kèm cách đo
cụ thể. Nếu làm lại, tôi sẽ tự scan và tự pitch bằng trải nghiệm thật nhiều
hơn trước khi nhờ đến AI, và tôi sẽ challenge nhóm mạnh hơn ở giả định "khách
hàng đồng ý bị ghi âm" — vì đây đúng là chỗ Dương từng lo về quyền riêng tư
và nhóm đã phải thiết kế thêm chế độ voice-note 60 giây để dung hòa.
```

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [X] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [X] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [X] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [X] [15đ] Nhóm có workflow trước/sau
- [X] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [X] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [X] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [X] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [X] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI
