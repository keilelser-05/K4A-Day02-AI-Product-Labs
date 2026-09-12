# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

* Họ và tên: Phùng Gia Khánh
* Mã học viên: 2A202602585
* Nhóm: Nhóm 5 người gồm Bùi Đình Đề, Phùng Gia Khánh, Lê Hoàng Đạt, Lê Minh Hiếu, Nguyễn Ngọc Minh
* Candidate problem nhóm chọn: Tra cứu quy chế, thủ tục học vụ từ Sổ tay sinh viên PDF dày >100 trang

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động                  | Tôi đã làm gì? (việc cụ thể)                                                                                                                                                                                          | Kết quả / ảnh hưởng tới nhóm                                                                                             |
| -------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------ |
| Scan cá nhân               | Tôi scan 5 problem từ chính workflow học tập và làm lab của mình, trong đó tập trung vào việc requirement nằm rải ở nhiều file, notes khó tổng hợp thành artifact và bài có thể đủ form nhưng thiếu logic xuyên suốt. | Đưa thêm một cụm problem xoay quanh workflow học tập và quality control vào tập candidate của nhóm.                      |
| Pitch Problem Card         | Tôi pitch Problem Card “Biến notes rời rạc thành artifact nộp hoàn chỉnh”, giải thích bottleneck nằm ở bước map notes/evidence vào đúng section và vẫn giữ được logic giữa claim, metric và decision.                 | Candidate này được giữ lại trong shortlist cuối cùng của nhóm và được chấm 24 điểm trong ma trận convergence.            |
| Challenge bài của bạn khác | Tôi cùng nhóm challenge các candidate theo câu hỏi: actor có đủ rõ không, bottleneck có nằm ở một bước cụ thể không, metric có đo được không và có thực sự cần AI không.                                              | Giúp nhóm loại sớm các bài chỉ cần QR code, rule hoặc workflow automation đơn giản và tránh chọn bài chỉ vì “nghe AI”.   |
| Gom trùng / cluster        | Tôi tham gia gom các problem về notes, tài liệu, paper và khôi phục context vào cluster “Tổng hợp thông tin rời rạc”; đồng thời nhận ra problem #8 và #9 của mình có overlap.                                         | Giảm số candidate rời rạc thành các pattern lớn hơn và giúp shortlist rõ hơn.                                            |
| Chọn candidate problem     | Tôi tham gia so sánh 3 candidate cuối theo actor, workflow, evidence, impact, khả năng làm trong lab và độ phù hợp Rule/Workflow/Agent.                                                                               | Nhóm thống nhất chọn bài tra cứu quy chế PDF vì actor và workflow rõ hơn, đồng thời dễ phân tích RAG và fallback.        |
| Validation / research      | Tôi không trực tiếp phụ trách research chính, nhưng tham gia xem lại evidence và nhận diện rằng các con số 50-70 email/ngày, 10-25 phút và mức giảm email vẫn chưa được validate thật.                                | Giúp nhóm không trình bày assumption như fact và dẫn tới quyết định “Not Yet” thay vì “Go”.                              |
| Workflow nhóm              | Tôi phụ trách workflow, cùng nhóm mô tả current state gồm luồng sinh viên tự tra và luồng gửi email CTSV; sau đó thiết kế future state theo RAG: hỏi → retrieve → trả lời kèm nguồn → escalate.                       | Tạo mạch before/after rõ, chỉ ra bottleneck, AI boundary, human boundary và fallback.                                    |
| Problem Statement          | Tôi tham gia kiểm tra sự nhất quán giữa actor, workflow, bottleneck, metric, boundary và AI intervention point.                                                                                                       | Problem Statement v1 chặt hơn v0, đặc biệt ở phần boundary và vị trí AI can thiệp.                                       |
| Rule / Workflow / Agent    | Tôi cùng nhóm so sánh FAQ dạng Rule, RAG Workflow và Agent; tập trung vào việc workflow thực tế có tuyến tính hay cần AI tự lập kế hoạch.                                                                             | Nhóm chọn Workflow thay vì Agent vì luồng nhận câu hỏi → retrieve → trả lời/escalate đã đủ rõ và không cần autonomy cao. |
| Decision                   | Tôi đồng ý với quyết định Not Yet vì baseline chưa được đo và risk trả lời sai quy chế chưa có quy trình review đủ chắc.                                                                                              | Decision cuối phản ánh đúng mức readiness thay vì cố kết luận Go khi evidence chưa đủ.                                   |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Dấu tay rõ nhất của tôi nằm ở phần workflow. Tôi tham gia biến bài toán từ một mô tả chung về “khó tra cứu quy chế” thành current workflow và future workflow cụ thể, từ đó nhóm mới xác định được bottleneck, AI intervention point, fallback và lý do chọn Workflow thay vì Agent.
```

---

## 2. Bảng dùng AI

| Phase                   | Tôi dùng AI để làm gì?                                                                                                 | AI hữu ích ở đâu?                                                                                             | AI sai / hời hợt ở đâu?                                                                                                                   | Tôi sửa gì bằng nhận định của mình?                                                                                                  |
| ----------------------- | ---------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| Scan                    | Tôi dùng AI để gợi ý các pain point dựa trên workflow học AI, làm lab, code và làm project của mình.                   | AI giúp mở rộng không gian problem và nhắc lại những pain tôi từng gặp nhưng chưa hệ thống hóa.               | Một số gợi ý nghe hợp lý nhưng không phải pain đủ mạnh hoặc evidence không khớp, ví dụ lỗi môi trường Python hay ngân hàng câu hỏi trùng. | Tôi loại các ý không đủ pain hoặc không đúng scope và giữ lại 5 problem gần với workflow học/làm lab thực tế nhất.                   |
| Problem Card            | Tôi dùng AI để phản biện actor, bottleneck, metric, non-AI alternative và AI hypothesis cho top 3 cards.               | AI giúp biến problem chung thành workflow 3-7 bước và chỉ ra cần tách completeness khỏi semantic coherence.   | AI ban đầu có xu hướng đẩy solution theo hướng “AI viết report”, dễ solution-first.                                                       | Tôi giới hạn AI ở semantic mapping, contradiction detection và draft support; deterministic checklist vẫn xử lý requirement cố định. |
| Workflow                | Tôi dùng AI để kiểm tra xem workflow có đủ bước, có bottleneck, human boundary và fallback chưa.                       | AI hữu ích trong việc phát hiện workflow còn thiếu fallback và trong việc phân biệt AI step với human review. | AI có thể làm workflow trông quá lý tưởng và tự gán các con số thời gian chưa đo thật.                                                    | Tôi giữ nhãn assumption/hypothesis cho các số chưa validate và không coi chúng là baseline thật.                                     |
| Research                | Tôi không trực tiếp dùng AI làm research chính của nhóm.                                                               | —                                                                                                             | —                                                                                                                                         | Tôi chủ yếu đọc lại research của nhóm và kiểm tra xem conclusion có vượt quá evidence hay không.                                     |
| Problem Statement       | Tôi dùng AI để kiểm tra consistency giữa problem, workflow, bottleneck, metric, boundary và intervention point.        | AI giúp phát hiện nếu metric không đo đúng impact hoặc boundary mâu thuẫn với future workflow.                | AI có thể khiến câu chữ nghe chắc chắn hơn mức evidence thực tế.                                                                          | Tôi giữ các giả định chưa xác nhận dưới dạng assumption và không biến 50-70 email/ngày thành fact.                                   |
| Rule / Workflow / Agent | Tôi dùng AI để phân biệt khi nào bài cần Rule, Workflow hay Agent và phản biện xem có đang chọn Agent vì “ngầu” không. | AI giúp làm rõ tiêu chí: workflow tuyến tính thì không cần autonomy cao.                                      | AI đôi lúc suy luận “độ mơ hồ cao + độ phức tạp cao = Agent” quá nhanh.                                                                   | Tôi dựa lại vào workflow thực tế và kết luận RAG Workflow là đủ vì các bước đã biết trước.                                           |
| Decision                | Tôi dùng AI để phản biện readiness và xem Go / Not Yet / No-Go nào phù hợp nhất.                                       | AI giúp chỉ ra thiếu baseline và thiếu validation với user thật là blocker quan trọng.                        | AI có thể thiên về “build trước rồi test” nếu chỉ nhìn technical feasibility.                                                             | Tôi ưu tiên evidence và risk, nên giữ quyết định Not Yet cho đến khi baseline và quy trình review được xác nhận.                     |

---

## 3. Reflection câu hỏi mở

**Reflection:**

```text
Điều tôi học được rõ nhất từ bài lab này là một problem nghe “rất hợp AI” chưa chắc đã là problem nên làm đầu tiên. Khi nghe các top 3 problems của các bạn khác, tôi thấy nhiều bài có pain thật nhưng nếu nhìn kỹ thì QR code, rule hoặc workflow automation đơn giản đã đủ, nên không cần cố thêm AI vào. Bản thân tôi ban đầu tập trung khá nhiều vào các problem xoay quanh việc dùng AI để tổng hợp hoặc review artifact, nhưng khi nhóm so sánh candidate thì bài tra cứu quy chế có actor, workflow và bottleneck cụ thể hơn nên tôi đồng ý chuyển sang bài đó. Phần tôi đóng góp rõ nhất là workflow, vì khi vẽ được từng bước trước và sau thì nhóm mới nhìn ra AI chỉ cần đứng giữa câu hỏi của sinh viên và CTSV để retrieve và tổng hợp thông tin. Tôi cũng thay đổi cách nghĩ về Agent: độ mơ hồ và độ phức tạp cao chưa đủ để kết luận cần Agent; nếu đường đi của workflow đã biết trước thì Workflow vẫn hợp lý hơn. Điều khó nhất với tôi không phải nghĩ ra solution mà là giữ metric và evidence trung thực, vì nhiều con số ban đầu như 50-70 email/ngày hoặc 10-25 phút thực tế vẫn chưa được nhóm đo trực tiếp. Vì vậy tôi thấy quyết định Not Yet hợp lý hơn Go, dù technical solution RAG tương đối rõ. Một điểm tôi thấy quan trọng nữa là AI có thể giúp rất tốt ở bước phản biện logic nhưng cũng dễ làm câu chữ trở nên chắc chắn hơn bằng chứng thật. Nếu làm lại, tôi sẽ challenge nhóm sớm hơn ở phần validation và yêu cầu ít nhất một baseline thật trước khi chấm điểm candidate. Tôi cũng sẽ phân biệt rõ hơn giữa “problem có vẻ phổ biến” và “problem đã có evidence từ đúng actor”. Sau bài này, tôi hiểu mạch problem → workflow → bottleneck → metric → boundary → AI fit quan trọng hơn việc bắt đầu từ câu hỏi “nên dùng model hay Agent nào”.
```

---

## 4. Tự kiểm cuối bài

* [x] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
* [x] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
* [x] Nhóm có nhật ký hội tụ từ candidates về 1 bài
* [x] [15đ] Nhóm có workflow trước/sau
* [x] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
* [x] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
* [x] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
* [x] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
* [x] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI
