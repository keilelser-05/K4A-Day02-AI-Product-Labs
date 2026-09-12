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

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| 1 | | | |
| 2 | | | |
| 3 | | | |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — [Tên problem]

```text
Problem 1 câu:

Actor:

Thời điểm / bối cảnh:

Current workflow 3-7 bước:
1.
2.
3.
4.
5.

Bottleneck:

Impact:

Success metric:

Non-AI alternative:

AI hypothesis:

Quick gut:
[ ] No AI / process fix
[ ] Rule
[ ] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — ___ phút

[1 ...: __'] → [2 ...: __'] → [3 ...: __'] → [4 ...: __']  <-- bottleneck

FUTURE STATE — ___ phút

[1 ...: __'] → [2 ...: __'] → [3 ... review: __']  <-- human boundary

Fallback: nếu AI sai thì ...
```

File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-1.png`

---

#### Problem Card #2 — [Tên problem]

```text
Problem 1 câu:

Actor:

Thời điểm / bối cảnh:

Current workflow 3-7 bước:
1.
2.
3.
4.
5.

Bottleneck:

Impact:

Success metric:

Non-AI alternative:

AI hypothesis:

Quick gut:
[ ] No AI / process fix
[ ] Rule
[ ] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — ___ phút

[1 ...] → [2 ...] → [3 ...]  <-- bottleneck

FUTURE STATE — ___ phút

[1 ...] → [2 ...] → [3 ... review]  <-- human boundary

Fallback: ...
```

File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

---

#### Problem Card #3 — [Tên problem]

```text
Problem 1 câu:

Actor:

Thời điểm / bối cảnh:

Current workflow 3-7 bước:
1.
2.
3.
4.
5.

Bottleneck:

Impact:

Success metric:

Non-AI alternative:

AI hypothesis:

Quick gut:
[ ] No AI / process fix
[ ] Rule
[ ] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — ___ phút

[1 ...] → [2 ...] → [3 ...]  <-- bottleneck

FUTURE STATE — ___ phút

[1 ...] → [2 ...] → [3 ... review]  <-- human boundary

Fallback: ...
```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text

```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text

```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text

```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra:
- Tôi sửa gì:

### Self-check nộp phần 01
- [ ] Có 5+ problems + top 3 Cards đủ field
- [ ] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [ ] Đã chọn 1 card pitch + câu hỏi challenge
