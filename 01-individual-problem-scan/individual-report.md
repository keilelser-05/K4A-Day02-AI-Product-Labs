# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Phùng Gia Khánh
- Mã học viên: 2A202602585
- Vai trò / bối cảnh (VD: sinh viên năm X, intern PM, ...): Sinh viên năm 4, Trường Đại học FPT
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem):
  - Đọc README/lab specification, làm bài thực hành AI/LLM và nộp qua GitHub.
    
  - Ôn tập Machine Learning, Deep Learning, toán và Python qua ngân hàng câu hỏi.

  - Code Python, tạo virtual environment, chạy notebook/repository và xử lý lỗi môi trường.

  - Làm việc nhóm, chọn problem, viết mô tả dự án và chuẩn bị deliverable.

  - Dùng AI để phản biện, giải thích kiến thức và hỗ trợ cấu trúc artifact, sau đó tự kiểm lại.

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 |Tốn thời gian|Yêu cầu bài lab nằm rải ở nhiều file, người học phải đối chiếu để biết chính xác output, rubric và trình tự làm. |Học viên AI Thực Chiến |Lab Day 02 yêu cầu đọc ít nhất 3 tài liệu lõi: README.md, 01-worksheet.md, 02-deliverable-example.md.|
| 2 |Tốn thời gian |Viết đoạn giới thiệu tuyển thành viên bị giới hạn ký tự nên phải chỉnh nhiều vòng mà vẫn giữ đủ thông tin quan trọng. |Sinh viên tìm teammate |Report nêu flat topic lookup không lấy được fine-grained facts ngoài 11 predefined topics |
| 3 |Tốn thời gian / Pain từ người khác |Trong dự án nhóm, nếu owner code chính phải gánh phần lớn implementation thì tiến độ và chất lượng review bị rủi ro. |Thành viên phụ trách code / cả nhóm | |
| 4 |AI có thể tốt hơn | Sau khi hoàn thành lab/project, việc biến notes rời rạc thành artifact nộp có cấu trúc vẫn cần nhiều bước kiểm tra chéo. | Sinh viên AI / project team | Day 02 yêu cầu **3 phần nộp chính** và phần nhóm phải chứa convergence, validation, research, workflow, PS v0/v1, R/W/A, decision — nhiều điểm dễ thiếu nếu không có checklist. |
| 5 |AI có thể tốt hơn | Khi đọc rubric/readme dài, người học dễ tối ưu “cho đủ form” nhưng bỏ sót logic problem → workflow → metric → boundary. | Học viên làm lab | Rubric Day 02 chia **60 điểm nhóm + 40 điểm cá nhân** và có nhiều dependency; chỉ điền form mà không nối logic sẽ mất điểm ở nhiều mục cùng lúc. |

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi: Dựa trên các thông tin bạn đã có dựa từ lịch sử trò chuyện với tôi, hãy liệt kế các vấn đề trong việc mà tôi là dựa trên mẫu sau dựa trên bối cảnh lần làm dự án trước của tôi(Healthbot)
- Ý dùng được: Yêu cầu bài lab nằm rải ở nhiều file, người học phải đối chiếu để biết chính xác output, rubric và trình tự làm, Viết đoạn giới thiệu tuyển thành viên bị giới hạn ký tự nên phải chỉnh nhiều vòng mà vẫn giữ đủ thông tin quan trọng, Trong dự án nhóm, nếu owner code chính phải gánh phần lớn implementation thì tiến độ và chất lượng review bị rủi ro, Sau khi hoàn thành lab/project, việc biến notes rời rạc thành artifact nộp có cấu trúc vẫn cần nhiều bước kiểm tra chéo, Khi đọc rubric/readme dài, người học dễ tối ưu “cho đủ form” nhưng bỏ sót logic problem → workflow → metric → boundary
- Ý bỏ vì không phải pain thật: Khi chạy repo Python trên Windows, lệnh cài/activate môi trường giữa Linux và PowerShell dễ gây lỗi và làm gián đoạn lab, Ngân hàng ôn thi có nhiều câu gần nghĩa/trùng ý, cần sàng lọc câu khác nhau trước khi chia theo phân môn, Lịch sử làm câu hỏi có nhiều lần sai nhưng việc tự nhớ câu nào cần ưu tiên ôn lại không bền vững, Khi ôn từng câu, người học phải lặp lại quy trình: xác định mảng kiến thức → giải → dạy nền → lỗi dễ nhầm → biến thể → ví dụ

**Self-check Phase 1:**
- [x] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [x] Dùng ít nhất 3/4 lăng kính
- [x] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan)                                                                                              | Vì sao chọn (2-3 ý)                                                                                                                                                                                                          | Điều còn chưa chắc                                                                                             |
| ---- | ------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- |
| 1    | Sau khi hoàn thành lab/project, việc biến notes rời rạc thành artifact nộp có cấu trúc vẫn cần nhiều bước kiểm tra chéo. | Actor rõ là sinh viên/project team; workflow tổng hợp artifact có thể mô tả thành các bước cụ thể; có bottleneck rõ ở bước map notes/evidence vào đúng section; impact có thể đo bằng thời gian tổng hợp và số mục bị thiếu. | Chưa có baseline chính xác về thời gian tổng hợp artifact và tỷ lệ lỗi/missing section trước khi nộp.          |
| 2    | Khi đọc rubric/readme dài, người học dễ tối ưu “cho đủ form” nhưng bỏ sót logic problem → workflow → metric → boundary.  | Đây là pain trực tiếp trong AI Thực Chiến; lỗi không chỉ là thiếu form mà là inconsistency giữa nhiều phần; AI có khả năng semantic reasoning tốt hơn checklist thuần túy.                                                   | Chưa rõ có thể đo coherence một cách khách quan tới mức nào; cần sample submission và peer review để validate. |
| 3    | Yêu cầu bài lab nằm rải ở nhiều file, người học phải đối chiếu để biết chính xác output, rubric và trình tự làm.         | Actor cụ thể; workflow đọc và đối chiếu tài liệu rõ; bottleneck nằm ở bước tổng hợp requirement giữa nhiều nguồn; dễ đo thời gian hiểu bài và số requirement bị bỏ sót.                                                      | Một phần problem có thể được giải tốt chỉ bằng README/checklist chuẩn hóa, chưa chắc AI mang lại đủ giá trị.   |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — Biến notes rời rạc thành artifact nộp hoàn chỉnh

```text
Problem 1 câu:
Sau khi hoàn thành các hoạt động của lab/project, sinh viên vẫn phải mất nhiều bước để tổng hợp notes, evidence, research và quyết định rời rạc thành artifact nộp đúng cấu trúc và không thiếu nội dung.

Actor:
Sinh viên AI Thực Chiến / thành viên project team phụ trách tổng hợp bài nộp.

Thời điểm / bối cảnh:
Cuối một buổi lab hoặc cuối một project, khi phần thảo luận, validation, research và thiết kế solution đã gần hoàn thành nhưng nội dung vẫn nằm rải rác ở notes, chat, bảng, link và draft.

Current workflow 3-7 bước:
1. Thu notes và kết quả từ các thành viên.
2. Thu validation, research link, workflow và metric.
3. Đối chiếu worksheet / README / rubric.
4. Map từng nội dung vào đúng section của bài nộp.
5. Viết lại thành report có cấu trúc.
6. Kiểm tra section thiếu, contradiction và format.
7. Human review trước khi nộp.

Bottleneck:
Bước 4 — map thông tin bán cấu trúc vào đúng section và giữ đúng quan hệ giữa evidence, claim, metric và decision.

Impact:
Tăng thời gian hoàn thiện bài; dễ thiếu section; evidence có thể không gắn đúng claim; các phần trong report có thể không đồng bộ.

Success metric:
- Giảm ít nhất 50% thời gian từ lúc kết thúc hoạt động đến khi có draft submission.
- 100% section bắt buộc được phát hiện/check.
- Giảm số lỗi missing section hoặc contradiction trước khi nộp.

Non-AI alternative:
Dùng template Markdown cố định, checklist bắt buộc, form chuẩn hóa và script kiểm tra heading/file tồn tại.

AI hypothesis:
AI có thể phân loại notes theo section, map evidence với claim, phát hiện contradiction, tạo draft từ nội dung có sẵn và cảnh báo những phần còn thiếu.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — ~30-45 phút (assumption, cần validate)

[1 Thu notes: 5'] 
→ [2 Thu evidence/research: 5'] 
→ [3 Đối chiếu rubric: 5'] 
→ [4 Map nội dung vào section: 10-15']  <-- bottleneck
→ [5 Viết report: 10']
→ [6 Kiểm tra thiếu/lỗi: 5']

FUTURE STATE — ~15-20 phút (hypothesis)

[1 Thu artifacts: 3']
→ [2 Rule kiểm tra file/section: 1']
→ [3 AI map notes + evidence + draft: 5']
→ [4 AI flag contradiction/missing logic: 2']
→ [5 Human review + chỉnh sửa: 5-10']  <-- human boundary

Fallback: nếu AI map sai section, tạo claim không đúng evidence hoặc bỏ sót requirement thì human review giữ quyền quyết định cuối; workflow quay về checklist/template thủ công.
```

File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-1.png`

---

#### Problem Card #2 — Đủ form nhưng thiếu logic xuyên suốt bài

```text
Problem 1 câu:
Khi rubric và README dài, học viên dễ tập trung hoàn thành từng field nhưng không phát hiện các phần problem, workflow, bottleneck, metric, boundary và AI fit đang mâu thuẫn hoặc không support lẫn nhau.

Actor:
Học viên AI Thực Chiến làm lab/project theo rubric.

Thời điểm / bối cảnh:
Sau khi đã điền gần đủ template và chuẩn bị review bài trước khi nộp.

Current workflow 3-7 bước:
1. Đọc template.
2. Điền từng section.
3. Tick các mục đã hoàn thành.
4. Đọc rubric.
5. Bổ sung phần còn thiếu.
6. Kiểm tra format.
7. Nộp bài.

Bottleneck:
Bước 5 — kiểm tra quan hệ logic giữa nhiều section, không chỉ kiểm tra sự hiện diện của từng field.

Impact:
Một lỗi logic ở problem hoặc bottleneck có thể kéo theo workflow, metric, AI intervention và decision sai; bài có thể đủ form nhưng vẫn mất điểm ở nhiều rubric item.

Success metric:
- Phát hiện ≥80% contradiction giữa các section trước khi nộp.
- Tăng tỷ lệ metric thực sự đo đúng impact của problem.
- Giảm số trường hợp AI intervention không giải đúng bottleneck.
- Giảm lỗi boundary không khớp với future workflow.

Non-AI alternative:
Dùng coherence checklist thủ công và peer review giữa các thành viên.

AI hypothesis:
AI có thể đánh giá semantic dependency giữa Problem ↔ Workflow ↔ Bottleneck ↔ Metric ↔ Boundary ↔ AI intervention ↔ Decision và chỉ ra contradiction hoặc missing reasoning.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — ~15-25 phút (assumption, cần validate)

[1 Điền template: 5']
→ [2 Đọc rubric: 5']
→ [3 Kiểm tra đủ mục: 5']
→ [4 Tự đọc lại logic toàn bài: 5-10']  <-- bottleneck
→ [5 Sửa và nộp]

FUTURE STATE — ~8-15 phút (hypothesis)

[1 Rule kiểm tra completeness: 1']
→ [2 AI review dependency giữa các section: 2-3']
→ [3 AI flag contradiction + missing reasoning: 2']
→ [4 Human review và quyết định sửa: 5-10']  <-- human boundary

Fallback: nếu AI đánh giá coherence không chính xác hoặc đưa feedback quá chủ quan thì reviewer quay lại coherence checklist và peer review thủ công.
```

File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

---

#### Problem Card #3 — Requirement của lab bị phân tán giữa nhiều file

```text
Problem 1 câu:
Yêu cầu của một bài lab nằm rải ở nhiều file khiến học viên phải liên tục đối chiếu để xác định output, rubric, thứ tự thực hiện và các yêu cầu bắt buộc.

Actor:
Học viên chương trình AI Thực Chiến.

Thời điểm / bối cảnh:
Ngay khi nhận một repository lab mới hoặc trong quá trình làm bài khi cần kiểm tra lại yêu cầu.

Current workflow 3-7 bước:
1. Mở repository.
2. Đọc README.
3. Đọc worksheet.
4. Đọc deliverable example.
5. Quay lại các file để đối chiếu requirement.
6. Tự tạo checklist và thứ tự làm.
7. Trong lúc làm tiếp tục quay lại tài liệu để kiểm tra.

Bottleneck:
Bước 5 — tổng hợp và reconcile requirement từ nhiều tài liệu khác nhau thành một kế hoạch thực thi thống nhất.

Impact:
Mất thời gian trước khi bắt đầu; dễ hiểu sai thứ tự; bỏ sót deliverable hoặc rubric item; phải chuyển context giữa nhiều file.

Success metric:
- Giảm thời gian từ lúc mở repo đến lúc có checklist đầy đủ xuống dưới 10 phút.
- Capture ≥95% requirement bắt buộc.
- Giảm số lần phải quay lại tài liệu trong quá trình làm.
- Giảm số deliverable bị bỏ sót.

Non-AI alternative:
Tạo MASTER_CHECKLIST.md, README chuẩn hóa hoặc template lab thống nhất từ phía giảng viên.

AI hypothesis:
AI có thể đọc nhiều tài liệu, trích xuất requirement, nhóm theo phase, phân biệt phần cá nhân/nhóm, map requirement với rubric và sinh execution checklist.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — ~20-30 phút (assumption, cần validate)

[1 Đọc README: 5']
→ [2 Đọc worksheet: 7']
→ [3 Đọc deliverable example: 5']
→ [4 Đối chiếu requirement giữa các file: 8-10']  <-- bottleneck
→ [5 Tạo checklist: 5']

FUTURE STATE — ~5-10 phút (hypothesis)

[1 Load toàn bộ tài liệu: <1']
→ [2 Rule/parser lấy heading + structure: <1']
→ [3 AI extract + normalize requirement: 2-3']
→ [4 AI map requirement → phase/rubric: 2']
→ [5 Học viên review checklist: 2-3']  <-- human boundary

Fallback: nếu AI bỏ sót hoặc hiểu sai requirement thì học viên quay lại tài liệu gốc; checklist chỉ được coi là hỗ trợ, không thay thế source of truth.
```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Problem Card #1 — Biến notes rời rạc thành artifact nộp hoàn chỉnh.
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
Workflow hiện tại có nhiều bước rõ ràng: thu notes/evidence → đối chiếu rubric → map nội dung → viết report → kiểm tra lại, trong đó bottleneck chính nằm ở bước map thông tin rời rạc vào đúng section mà vẫn giữ được logic và evidence.

Problem có thể đo bằng thời gian tổng hợp artifact, số missing section, số contradiction và số vòng review trước khi submission-ready. Nếu giải tốt, impact trực tiếp là giảm thời gian cuối lab và giảm rủi ro bài đủ nội dung nhưng thiếu hoặc sai cấu trúc.
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
1. Phần pain này có thực sự cần AI hay một template + checklist tốt đã giải được phần lớn vấn đề?

2. Nếu dùng AI để tổng hợp artifact, làm thế nào để ngăn AI tự thêm claim, làm sai evidence hoặc biến assumption thành fact?
```

**AI phản biện Card (nếu có):**

* Điểm yếu AI chỉ ra: Problem dễ bị solution-first thành “AI viết report”, trong khi root cause có thể chỉ là process/template chưa tốt; baseline thời gian và error rate hiện chưa được validate.
* Tôi sửa gì: Giới hạn AI ở phần semantic mapping, contradiction detection và draft support; giữ deterministic checklist cho requirement cố định và bắt buộc human review trước khi nộp.

### Self-check nộp phần 01

* [x] Có 5+ problems + top 3 Cards đủ field
* [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
* [x] Đã chọn 1 card pitch + câu hỏi challenge
