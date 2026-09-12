# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Nguyễn Thọ Đạt
- Mã học viên: 2A202602484
- Nhóm: Gác cửa B
- Candidate problem nhóm chọn: Khó nghĩ ra chiến lược marketing để đưa sản phẩm mới ra thị trường — Giải pháp AI Marketing Kit cho Seller nhỏ lẻ trên sàn TMĐT (của bạn Phan Đức Duy)

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Scan 10 bài toán thực tế của sinh viên CNTT & thực tập sinh phần mềm. | Đóng góp 3 bài toán kỹ thuật chất lượng vào cụm C (tự động hóa lập trình). |
| Pitch Problem Card | Trình bày bài toán tự động sinh PR Description từ Git diff và Daily Standup. | Giúp nhóm hiểu cách bóc tách một workflow kỹ thuật thành từng bước đo đạc được bằng phút. |
| Challenge bài của bạn khác | Phản biện bài F&B của Tùng (No AI là đủ) và bài Marketing Kit của Duy về rủi ro ảnh AI bị hallucination / sai lệch sản phẩm thật. | Nhóm nhận ra không thể thả nổi cho AI tự sinh ảnh rồi đăng ngay, mà bắt buộc phải có chốt chặn người duyệt. |
| Gom trùng / cluster | Cùng Minh phân loại 18 bài thành 4 cụm lớn (A, B, C, D) theo đối tượng thụ hưởng. | Nhóm nhìn rõ bức tranh tổng thể và tách được cụm Kinh doanh nhỏ ra khỏi cụm Tiện ích học đường. |
| Chọn candidate problem | Chấp nhận lùi bài PR Description của mình lại để bỏ phiếu cho bài AI Marketing Kit của Duy sau khi cân nhắc quy mô tác động kinh tế. | Nhóm đạt đồng thuận 100% về bài toán marketing cho shop online nhỏ. |
| Validation / research | Cùng An đối chiếu tính năng của các tool có sẵn (Canva Magic Studio, Midjourney, Jasper). | Nhận diện khoảng trống: các tool hiện tại chỉ tạo lẻ tẻ (text riêng, ảnh riêng), chưa có luồng end-to-end theo đúng chiến dịch. |
| Workflow nhóm | Cùng Tùng bóc tách Current State (7 bước, 3–7 ngày) và Future State (7 bước, <2 giờ); xác lập 2 điểm Human Boundary. | Đảm bảo quy trình có đường fallback an toàn, không bị biến thành một "black-box". |
| Problem Statement | Tham gia viết phần Boundary (Làm gì và KHÔNG làm gì) trong Problem Statement v1. | Nhóm chốt chặt: Không làm video phức tạp, không tự ý nạp tiền quảng cáo hay tự xuất bản khi chưa có người duyệt. |
| Rule / Workflow / Agent | Chủ trì phân tích kỹ thuật: Phản biện đề xuất làm Autonomous Agent tự chạy chiến dịch, bảo vệ phương án chọn mô hình Workflow có Human-in-the-loop. | Nhóm tránh được bẫy over-engineering, hạ từ Agent xuống Workflow để đảm bảo tính khả thi và an toàn chi phí. |
| Decision | Thiết lập 3 tiêu chí kỹ thuật cho bài toán Pilot và xác định điều kiện dừng (Rollback trigger). | Nhóm thống nhất ra quyết định GO có căn cứ đo lường rõ ràng (thời gian <90', thỏa mãn ≥8/10). |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Dấu tay rõ nhất của tôi là việc kiên quyết kéo nhóm từ ý tưởng ban đầu muốn làm 'Autonomous Agent tự chạy marketing và tự đăng bài' về mô hình 'AI Workflow có 2 chốt chặn con người (Human Boundary)' ở khâu chọn concept và duyệt ảnh, giúp bài toán vừa giải quyết được nỗi đau vừa triệt tiêu rủi ro thương hiệu cho người bán.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Prompt mở rộng góc nhìn theo 4 lăng kính từ bối cảnh sinh viên năm 4 kiêm intern dev. | Gợi ý được góc nhìn hay về lỗi log CI-CD dài và ticket bug thiếu spec từ QA. | Đưa ra một số ý tưởng chung chung kiểu "trợ lý AI học tiếng Anh" hoặc "AI tạo slide thuyết trình toàn năng". | Lọc bỏ toàn bộ các ý tưởng thiếu số liệu, chỉ giữ lại các workflow có thời gian đo được bằng phút/lần. |
| Problem Card | Nhờ AI đóng vai Skeptical PM để phản biện card PR Description và Standup report. | Chỉ ra điểm yếu: Git diff quá lớn sẽ làm tràn token hoặc khiến AI tóm tắt mơ hồ. | AI không chỉ ra được liệu lead/mentor có chấp nhận đọc một bản PR do AI viết hộ hay không. | Bổ sung thêm boundary: dev phải nhập 1 câu tóm tắt intent ngắn và kiểm tra trước khi bấm tạo PR. |
| Workflow | Dùng AI để format lại cú pháp ASCII / Mermaid cho sơ đồ Before/After. | Vẽ sơ đồ trực quan, thẳng hàng, tiết kiệm thời gian căn chỉnh. | AI tự động bỏ qua các bước kiểm tra thủ công và đề xuất tự động hóa 100% không có fallback. | Tự tay vẽ thêm 2 chốt chặn Human Boundary và nhánh rẽ Fallback quay về làm thủ công nếu AI sinh ảnh sai. |
| Research | Tìm kiếm các giải pháp đối thủ trên thị trường (Canva, Midjourney, Jasper). | Tổng hợp nhanh danh sách công cụ và tính năng chính trong vài giây. | Bịa ra một số số liệu thị phần không có link kiểm chứng nguồn cụ thể. | Tự tay truy cập website chính thức của từng công cụ, kiểm tra pricing và tính năng thực tế để điền link thật. |
| Problem Statement | Nhờ AI review câu chữ các field trong Problem Statement v0/v1. | Gợi ý cách diễn đạt ngắn gọn, gãy gọn các tiêu chí metric. | AI thường làm mờ ranh giới Boundary, cố tình gom cả việc làm video và chạy ads vào. | Viết lại ranh giới 'Không làm' thật cứng: cấm AI đụng vào tiền quảng cáo và đăng bài tự động. |
| Rule / Workflow / Agent | Hỏi phản biện ma trận độ phức tạp vs độ mơ hồ cho bài toán Marketing Kit. | Giúp làm rõ marketing là bài toán có độ mơ hồ cao (sáng tạo) và phức tạp vừa phải. | AI có xu hướng khuyên dùng 'Multi-Agent System' để nghe hiện đại và phức tạp hơn. | Nhận định kỹ thuật: Multi-Agent sẽ làm tăng chi phí token và khó kiểm soát ảo giác; quyết định chốt mức Workflow. |
| Decision | Tham khảo các tiêu chí pilot và rollback trigger trong ngành phần mềm. | Gợi ý các khung đo lường tiêu chuẩn (thời gian, độ hài lòng, CTR). | Đưa ra các chỉ số viển vông kiểu 'tăng 300% doanh thu trong 1 tuần'. | Hạ chỉ số kỳ vọng về thực tế: CTR từ <1% lên 2-3%, đo lường trên 3 sản phẩm chạy pilot thực tế. |

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
Tham gia lab với vai trò Technical Lead, bài học lớn nhất của tôi là bài toán hay không nằm ở công nghệ 'ngầu' nhất, mà nằm ở ranh giới can thiệp chính xác của AI. Ban đầu khi pitch top 3 cá nhân, tôi khá tự tin với bài toán tự động sinh PR Description vì workflow kỹ thuật rất quen thuộc với một intern dev; tuy nhiên, khi bị nhóm phản biện rằng GitHub Copilot đã làm quá tốt và thị trường quá hẹp, tôi nhận ra mình đang bị an toàn và sẵn sàng lùi lại để ủng hộ bài toán Marketing Kit cho shop online của Duy vì tác động kinh tế lớn hơn rất nhiều. 

Trong quá trình làm bài nhóm, có thời điểm cả nhóm bị cuốn vào tâm lý solution-first, hào hứng muốn xây dựng một 'Autonomous Agent tự động nghiên cứu, tự tạo ảnh và tự bấm xuất bản bài lên sàn TMĐT'. Lúc này, với góc nhìn kỹ thuật, tôi đã phải challenge nhóm quyết liệt về rủi ro ảo giác khi sinh ảnh sản phẩm thật và nguy cơ tài khoản bán hàng bị khóa nếu AI vi phạm chính sách sàn. 

Điều khó nhất với tôi khi viết Problem Statement không phải là metric mà là việc xác định ranh giới 'Không làm': kiên quyết không làm video phức tạp và không cho AI tự nạp tiền chạy ads. Dấu tay rõ nhất của tôi trong bản nộp nhóm chính là việc hạ mức giải pháp từ Agent về Workflow, thiết lập 2 chốt chặn con người bắt buộc ở bước chọn concept và duyệt ảnh, cùng phương án rollback quay về moodboard nếu AI sinh ảnh lỗi. Nếu được làm lại từ đầu, tôi sẽ challenge nhóm sớm hơn ngay từ khâu phỏng vấn seller để đào sâu hơn về chi phí họ sẵn sàng chi trả cho một sản phẩm GenAI thực tế.
```

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [x] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [x] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [x] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [x] [15đ] Nhóm có workflow trước/sau
- [x] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [x] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [x] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [x] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [x] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI

