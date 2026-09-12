# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Nguyễn Thọ Đạt
- Mã học viên: 2A202602484
- Vai trò / bối cảnh (VD: sinh viên năm X, intern PM, ...): Sinh viên năm 4 ngành CNTT (đang làm đồ án tốt nghiệp) kiêm Thực tập sinh Phần mềm (Software Engineer Intern).
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem): 
  - Nhận task bug fix/tính năng nhỏ từ Jira, trace code và đọc codebase lớn của công ty.
  - Tạo Pull Request, viết PR description, refactor code theo review của Mentor.
  - Viết daily standup và nhật ký thực tập nộp mentor/nhà trường cuối ngày.
  - Họp nhóm đồ án tốt nghiệp trường (2 buổi/tuần), phân chia task, review/merge code bài tập nhóm.
  - Đọc tài liệu công nghệ/API mới và viết báo cáo tiến độ đồ án.

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 |Lặp lại |Viết Pull Request (PR) Description theo chuẩn template công ty. Mỗi lần push code phải tự tóm tắt: mục đích thay đổi, danh sách file sửa, cách test và đính kèm cURL/ảnh chụp demo. |Intern / Junior Dev |20–25 phút/PR, trung bình 3–4 PR/tuần. Từng bị Senior nhắc 2 lần vì ghi description sơ sài kiểu "fix bug in cart". |
| 2 |Pain từ người khác |Code của bạn cùng nhóm đồ án push lên không theo convention và thiếu bắt lỗi (try-catch) |Nhóm trưởng / Lớp trưởng |40–60 phút/lần review và refactor hộ bạn. Tuần chạy deadline giữa kỳ mất đứt 1 ngày cuối tuần chỉ để đi dọn code lỗi. |
| 3 |Tốn thời gian |Tìm lại tin nhắn chốt quyết định quan trọng bị trôi trong kênh Discord/Zalo nhóm |Toàn bộ thành viên nhóm (5 người) |Mất 10–15 phút lục lại chat history mỗi khi có tranh cãi "Hôm trước ai bảo làm thế này?" |
| 4 |AI có thể tốt hơn |Đọc hiểu luồng dữ liệu trong codebase lớn của công ty (chưa có docs hoàn chỉnh) Khi nhận task mới, phải nhảy qua 5–6 file để hiểu logic xử lý trước khi code. |Intern mới onboard |Mất 2–3 tiếng chỉ để trace flow trước khi gõ dòng code đầu tiên. Hỏi Senior thì Senior bận họp hoặc trả lời ngắt quãng. |
| 5 |Lặp lại |Viết Daily Standup và Nhật ký thực tập cuối ngày. Cuối mỗi ngày phải lục lại git log, các ticket Jira đã mở, tin nhắn Slack để nhớ lại hôm nay đã làm gì, gặp blocker gì để báo cáo mentor. |Intern thực tập |15–20 phút mỗi cuối ngày (5 ngày/tuần). Hay bị quên những việc nhỏ đã xử lý buổi sáng nếu không ghi chú ngay. |
| 6 |Tốn thời gian |Tổng hợp tài liệu tham khảo và format trích dẫn chuẩn cho báo cáo đồ án trường. Viết chương cơ sở lý thuyết, phải đọc 10+ paper/doc công nghệ, tóm tắt và format lại trích dẫn theo chuẩn IEEE/APA. |Sinh viên |3–4 tiếng cho mỗi đợt nộp báo cáo; từng bị thầy gạch 4 nguồn vì dẫn link blog cá nhân hoặc sai format trích dẫn. |
| 7 |AI có thể tốt hơn |Tạo Mock Data / Test Cases bao phủ các Edge Cases cho API. Khi viết API hoặc unit test, người code thường chỉ nghĩ đến Happy Path, bỏ sót các trường hợp null, chuỗi rỗng, số âm, ký tự đặc biệt gây lỗi 500 khi demo. |Sinh viên / Intern Backend |Mất 30–40 phút/API để tự bịa dữ liệu test; khi thầy hoặc mentor test thử payload lạ thì API bị sập. |
| 8 |Pain từ người khác |Ticket Bug từ QA gửi sang thiếu bước tái hiện (Steps to Reproduce) và payload mẫu. QA ghi vắn tắt "Lỗi thanh toán", không đính kèm ID test hay log. |Intern Dev nhận fix bug |Mất 20–30 phút nhắn tin qua lại trên Slack với QA để xin thêm info hoặc gọi Meet tái hiện; xảy ra với 3/5 ticket. |
| 9 |Tốn thời gian |Đọc và giải mã Stack Trace / Build Log CI-CD dài 300+ dòng khi deploy đồ án/staging fail. Mất thời gian cuộn tìm dòng Exception thực tế giữa rừng log dependencies. |Sinh viên IT / Intern dev |Mất 30–45 phút/lần build fail; gặp 2–3 lần/tuần; 70% thời gian là cuộn tìm đúng dòng root-cause. |
| 10 |Lặp lại |Lọc tìm deadline và thay đổi yêu cầu bài tập bị trôi giữa các kênh Zalo/Teams/LMS lớp do giảng viên dời hạn hoặc sửa đề rải rác. |Sinh viên học 4–5 môn |Mất 15 phút/tuần rà soát chéo; 1 lần từng nộp muộn bài tập lớn do thầy dời hạn trên Zalo mà không đọc kịp. |

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi: Tôi là sinh viên năm 4 IT đang đi học và thực tập. Hãy gợi ý thêm problem theo 4 lăng kính: lặp lại, tốn thời gian, AI có thể tốt hơn, pain từ người khác với actor, workflow sơ bộ và cách đo.
- Ý dùng được: Viết PR Description, Đọc log build CI-CD, Daily standup cuối ngày, Ticket bug thiếu spec từ QA.
- Ý bỏ vì không phải pain thật: Trợ lý học tiếng Anh cá nhân hóa, AI tạo slide thuyết trình toàn năng (quá rộng và không phản ánh workflow hàng ngày).

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
| 1 |Viết Pull Request (PR) Description theo chuẩn template công ty |Workflow cực kỳ rõ ràng. Workflow có AI hỗ trợ (không cần đến Agent phức tạp, Rule/Script tự lấy git diff, AI draft markdown, người thật bấm review). Rất dễ Go! |Khả năng hiểu context logic nghiệp vụ sâu của diff lớn |
| 2 |Viết Daily Standup và Nhật ký thực tập cuối ngày (Problem #5) |Lặp lại hàng ngày (5 ngày/tuần), bottleneck ở bước gom thông tin từ Git/Jira/Slack; metric đo được rõ ràng (giảm từ 20' xuống <5'); dễ áp dụng AI Workflow hỗ trợ. |Cần copy/paste log thủ công hay viết script kéo tự động |
| 3 |Code của bạn cùng nhóm đồ án không theo convention và thiếu bắt lỗi (Problem #2) |Pain point nhức nhối thực tế khi làm bài tập lớn/đồ án; tốn nhiều thời gian dọn dẹp trước hạn nộp. |Khó kiểm soát nếu thành viên không chịu chạy tool review trước khi push |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — Viết Pull Request (PR) Description theo chuẩn template công ty

```text
Problem 1 câu:
Mỗi lần tạo PR, intern mất 20–25 phút đọc lại git diff và viết PR description theo đúng template (Summary, Impact, Test steps), dễ bị Senior nhắc nhở nếu viết qua loa.

Actor:
Intern / Junior Developer tạo PR trên GitHub/GitLab công ty.

Thời điểm / bối cảnh:
Sau khi hoàn thành code cho một ticket và chuẩn bị tạo PR để nhờ team review.

Current workflow 3-7 bước:
1. Chạy git diff hoặc xem file changes trên giao diện GitHub.
2. Mở template PR description của công ty.
3. Đọc lại từng file sửa để tóm tắt mục đích thay đổi (Why & What).
4. Viết các bước test (How to test) và đính kèm cURL/ảnh demo.
5. Đánh dấu checklist (unit test, coding convention).
6. Tự rà soát lại và bấm Create Pull Request.

Bottleneck:
Bước 3 & 4: Đọc lại toàn bộ diff và viết tóm tắt logic thay đổi + hướng dẫn test (mất 12-15 phút).

Impact:
20–25 phút/PR x 3–4 PR/tuần = 60–100 phút/tuần. PR viết rõ ràng giúp Senior review nhanh hơn 30%, giảm số vòng comment hỏi lại.

Success metric:
Giảm thời gian viết PR từ 20 phút xuống dưới 6 phút; không bị reviewer comment hỏi lại "PR này sửa cái gì?".

Non-AI alternative:
Dùng PR template có sẵn với các placeholder cố định (vẫn phải tự đọc git diff và tự gõ tóm tắt).

AI hypothesis:
Script trích xuất git diff và commit log, AI phân tích các hàm thay đổi và draft phần Summary + Test steps vào đúng template. Dev review và thêm demo screenshot trước khi submit.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — 22 phút

[1 Chạy git diff: 2']
→ [2 Đọc code diff & nhớ logic: 10']  <-- bottleneck
→ [3 Viết Summary & Test steps theo template: 7']
→ [4 Self-review & check checklist: 2']
→ [5 Submit PR: 1']

FUTURE STATE — 5 phút

[1 Hook/Script lấy Git diff & commit log: 30s]
→ [2 AI phân tích & draft template PR: 1']
→ [3 Dev review, bổ sung screenshot/cURL: 3']  <-- human boundary
→ [4 Submit PR: 30s]

Fallback: nếu AI draft không đúng ngữ cảnh logic nghiệp vụ, Dev dùng template trắng tự viết như cũ.
```

File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-1.png`

---

#### Problem Card #2 — Viết Daily Standup và Nhật ký thực tập cuối ngày (Problem #5)

```text
Problem 1 câu:
Cuối mỗi ngày intern mất 15–20 phút lục lại git commit, Jira ticket và Slack để nhớ lại việc đã làm và blocker nhằm viết standup/nhật ký thực tập, bước gom dữ liệu tốn thời gian và dễ bỏ sót đầu việc nhỏ.

Actor:
Thực tập sinh CNTT (Software Engineer Intern) cần báo cáo hằng ngày cho Mentor và ghi sổ nhật ký thực tập.

Thời điểm / bối cảnh:
17h30–18h00 mỗi ngày làm việc (thứ 2 đến thứ 6).

Current workflow 3-7 bước:
1. Mở terminal gõ git log --since="today" và check branch đã commit.
2. Mở Jira lọc các issue/subtask đang phụ trách để xem status đã đổi (In Progress/Done).
3. Lướt lại các thread trao đổi trên Slack để nhớ lại blocker hoặc quyết định kỹ thuật đã thảo luận.
4. Mở Google Docs / template nhật ký thực tập công ty.
5. Tự viết narrative theo 3 mục: Việc đã làm hôm nay, Khó khăn/Blocker, Kế hoạch ngày mai.
6. Rà soát lại format và bảo mật (không để lộ secret/API key/nội dung mật).
7. Gửi tin nhắn vào Slack channel #daily-standup của team và copy vào sổ nhật ký thực tập.

Bottleneck:
Bước 1, 2, 3: Phải chuyển ngữ cảnh qua 3 công cụ (Git, Jira, Slack) để hồi tưởng và tổng hợp thủ công, mất 10–12 phút và hay quên các commit nhỏ buổi sáng.

Impact:
15–20 phút/ngày x 5 ngày = 75–100 phút/tuần cho 1 intern. Giảm nguy cơ mentor không nắm được blocker kịp thời khiến task bị trễ sang ngày hôm sau.

Success metric:
Giảm tổng thời gian từ 20 phút xuống dưới 5 phút/ngày; 100% commit và ticket phát sinh trong ngày được phản ánh chính xác trong report.

Non-AI alternative:
Tạo template checklist ghi chú sẵn trên Notion/Text file, sau mỗi task tự ghi chú vào (nhưng hay quên khi đang tập trung code).

AI hypothesis:
Rule/Script gom log git + Jira ID, AI tóm tắt thành bản nháp 3 mục (Done / Blocker / Next). Intern chỉ cần kiểm tra 2 phút và bấm gửi.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — 20 phút

[1 Check git log: 4']
→ [2 Check Jira: 4']
→ [3 Đọc Slack recap: 4']  <-- bottleneck (gom thông tin rời rạc)
→ [4 Mở template: 1']
→ [5 Viết 3 mục (Done/Blocker/Next): 5']
→ [6 Rà soát nội dung: 1']
→ [7 Gửi Slack & lưu Docs: 1']

FUTURE STATE — 4 phút

[1 Script tự động lấy Git commit + Jira status: 30s]
→ [2 AI phân loại & draft 3 mục standup: 30s]
→ [3 Intern review, bổ sung blocker & chỉnh sửa: 2']  <-- human boundary
→ [4 Gửi Slack & lưu Docs: 1']

Fallback: Nếu AI draft sai hoặc thiếu, Intern bỏ draft và tự gõ nhanh dựa trên git log thô.
```

File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

---

#### Problem Card #3 — Kiểm tra Coding Convention & Xử lý lỗi trước khi merge code đồ án nhóm (Problem #2)

```text
Problem 1 câu:
Trưởng nhóm đồ án mất 40–60 phút mỗi lần review PR của thành viên nhóm vì code đặt tên cẩu thả, thiếu validate input và try-catch, dễ gây crash nhánh main trước hạn nộp.

Actor:
Trưởng nhóm kỹ thuật / Thành viên phụ trách merge code đồ án môn học.

Thời điểm / bối cảnh:
Trước mỗi mốc nộp bài tập lớn / đồ án cuối kỳ, khi các thành viên nộp PR vào nhánh chung.

Current workflow 3-7 bước:
1. Nhận thông báo PR từ thành viên nhóm đồ án trên GitHub/GitLab.
2. Mở tab Files Changed đọc từng file code của bạn.
3. Phát hiện đặt tên biến vô nghĩa (data1, temp), thiếu try-catch ở các hàm gọi API hoặc query DB.
4. Comment chỉ lỗi trên GitHub hoặc nhắn tin Zalo giải thích cho bạn sửa.
5. Bạn sửa không hết hoặc làm hỏng logic khác; gần sát hạn nộp đành tự pull code về máy refactor hộ.
6. Chạy test lại toàn bộ chức năng và bấm Merge vào nhánh main.

Bottleneck:
Bước 4 & 5: Thành viên không hiểu hoặc sửa sót lỗi convention/exception, dẫn đến người review phải tự tay sửa hộ code của người khác (mất 30-40 phút).

Impact:
Mất 40–60 phút/PR x 3–4 PR/đợt = 3–4 tiếng mỗi tuần chạy deadline; trưởng nhóm bị quá tải và ức chế tâm lý.

Success metric:
Giảm thời gian review code từ 50 phút xuống dưới 15 phút/PR; 0 lỗi crash runtime do thiếu try-catch trên nhánh main.

Non-AI alternative:
Cài đặt linter (ESLint, Prettier) và pre-commit hook (giải quyết được format/cú pháp, nhưng chưa bắt được thiếu logic nghiệp vụ hoặc thiếu error handling theo context).

AI hypothesis:
Tích hợp GitHub Action / bot review tự động chạy khi mở PR: phát hiện các hàm thiếu try-catch, biến đặt tên không rõ ngữ cảnh, và gợi ý code fix ngay tại dòng code để bạn tự bấm apply.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — 50 phút

[1 Mở PR: 2']
→ [2 Đọc từng file code: 15']
→ [3 Comment nhắc lỗi trên Zalo/PR: 10']
→ [4 Chờ bạn sửa / bạn sửa sót: 15']  <-- bottleneck
→ [5 Trưởng nhóm tự refactor hộ: 15']
→ [6 Merge: 3']

FUTURE STATE — 12 phút

[1 Thành viên push code mở PR: 1']
→ [2 Bot AI tự scan & comment code review + suggestion: 1']
→ [3 Thành viên tự bấm Apply Suggestion: 5']  <-- boundary
→ [4 Trưởng nhóm review nhanh logic & bấm Merge: 5']  <-- human boundary

Fallback: Nếu AI gợi ý sai context, trưởng nhóm để lại comment thủ công như cũ.
```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Card #1 — Viết Pull Request (PR) Description theo chuẩn template công ty (hoặc Card #2: Viết Daily Standup và Nhật ký thực tập cuối ngày)
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
1. Workflow hiện tại rất rõ ràng và lặp lại liên tục với mọi intern/junior dev (20-25 phút/lần, 3-4 lần/tuần).
2. Bottleneck nằm rõ ở khâu đọc git diff và viết tóm tắt có cấu trúc (Why, What, Test steps), có thể đo lường giảm từ 20' xuống dưới 6'.
3. Đây là bài toán hoàn hảo cho mức độ AI Workflow (Rule trích xuất git diff + AI draft narrative + dev review), rủi ro hallucination thấp vì dev luôn kiểm tra trước khi bấm tạo PR.
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
1. Nếu git diff quá lớn (hàng chục file hoặc cả nghìn dòng code), workflow này có bị tràn context của LLM hoặc tóm tắt quá chung chung không?
2. Liệu giải pháp này có cần đến Agent tự động gõ git hay chỉ cần một shell script / GitHub Action / extension IDE kích hoạt theo sự kiện?
```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra: Với các PR chứa code logic phức tạp, AI có thể chỉ mô tả bề mặt (surface changes) mà không hiểu được root motive của task; nguy cơ dev ỷ lại vào AI mà không tự kiểm tra kỹ.
- Tôi sửa gì: Đặt thêm boundary bắt buộc dev phải nhập 1 câu tóm tắt intent ngắn gọn trước khi AI sinh draft, và AI chỉ đóng vai trò trợ lý sinh bản nháp (drafting), quyền bấm submit và checklist luôn do con người làm.

### Self-check nộp phần 01
- [x] Có 5+ problems + top 3 Cards đủ field
- [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [x] Đã chọn 1 card pitch + câu hỏi challenge
