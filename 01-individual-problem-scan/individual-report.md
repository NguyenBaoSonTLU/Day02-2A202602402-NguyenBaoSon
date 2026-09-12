## Thông tin cá nhân

- Họ và tên: Nguyễn Bảo Sơn 
- Mã học viên: 2A202602402
- Vai trò / bối cảnh : intern Dev
- Công việc hằng tuần:
    Ngại hỏi khi bị block hoặc chưa biết cách đặt câu hỏi.
    Dễ tập trung vào “code chạy được” nhưng chưa chú ý maintainability.

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)
| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 | Lặp lại + Tốn thời gian | Giáo viên mất nhiều thời gian tạo bài tập phù hợp từng nhóm năng lực học sinh | Giáo viên tiểu học, học sinh cần bài tập cá nhân hóa | - Mỗi tuần giáo viên tạo khoảng **3-5 bộ bài tập/môn**.<br>- Một lớp có **30-40 học sinh** nhưng thường chỉ có **1-2 phiên bản bài tập**.<br>- Giáo viên mất khoảng **30-60 phút/lần soạn bài tập** để chỉnh mức độ. |
| 2 | Lặp lại + AI có thể tốt hơn | Giáo viên phải chấm bài và viết nhận xét thủ công cho từng học sinh | Giáo viên, phụ huynh cần biết tiến bộ của con | - Chấm khoảng **100-200 bài/tuần/lớp**.<br>- Mỗi bài mất **1-3 phút** để chấm + nhận xét.<br>- Cuối tuần mất khoảng **3-5 giờ** cho việc chấm và tổng hợp.<br>- Có thể kiểm chứng qua số lượng vở/bài kiểm tra đã chấm. |
| 3 | AI có thể tốt hơn + Pain từ giáo viên | Giáo viên khó xác định chính xác học sinh đang yếu kỹ năng nào | Giáo viên, học sinh yếu cần hỗ trợ sớm | - Giáo viên theo dõi bằng điểm số + quan sát cá nhân.<br>- Một giáo viên phụ trách **30-40 học sinh** nhưng chỉ có **1-2 tiết/tuần** để theo sát từng em.<br>- Có thể mất **2-4 tuần** mới phát hiện lỗi kiến thức khi điểm giảm. |
| 4 | Tốn thời gian + Pain từ giáo viên | Luyện đọc cho học sinh lớp 1 chưa đủ cá nhân hóa vì giáo viên không đủ thời gian nghe từng em | Giáo viên lớp 1, học sinh mới học đọc | - Một lớp có **30-40 học sinh**.<br>- Mỗi em cần luyện đọc **5-10 phút/ngày** nhưng giáo viên chỉ có khoảng **1-2 giờ/tuần** cho hoạt động cá nhân.<br>- Cần đo số lần học sinh được sửa phát âm trực tiếp/tuần. |
| 5 | Lặp lại + Pain từ người khác | Phụ huynh hỏi giáo viên nhiều câu giống nhau về cách hỗ trợ con học tại nhà | Giáo viên, phụ huynh | - Giáo viên nhận khoảng **5-20 tin nhắn/tuần** liên quan bài tập/học tập.<br>- Các câu hỏi thường lặp lại: "Dạy con cộng trừ thế nào?", "Luyện chữ ra sao?".<br>- Có thể kiểm chứng qua lịch sử chat/Zalo nhóm lớp. |
| 6 | Tốn thời gian + AI có thể tốt hơn | Giáo viên mất thời gian tìm kiếm và chỉnh sửa tài liệu dạy học | Giáo viên, tổ chuyên môn | - Mỗi tuần giáo viên tìm tài liệu khoảng **3-5 lần**.<br>- Mỗi lần mất **15-45 phút** để tìm, đọc, chỉnh sửa.<br>- Tài liệu nằm ở nhiều nguồn: Drive, nhóm chat, file cá nhân. |
| 7 | Lặp lại + Tốn thời gian | Theo dõi tiến độ học tập của từng học sinh bằng Excel/sổ thủ công | Giáo viên, quản lý chuyên môn | - Giáo viên nhập điểm/ghi chú cho **30-40 học sinh**.<br>- Cập nhật dữ liệu khoảng **1-2 lần/tuần**.<br>- Mất **30-90 phút/tuần** để tổng hợp.<br>- Bằng chứng: file Excel, sổ theo dõi, bảng điểm. |
| 8 | Tốn thời gian + AI có thể tốt hơn | Viết báo cáo đánh giá cuối kỳ mất nhiều thời gian | Giáo viên, nhà trường | - Mỗi học kỳ giáo viên viết báo cáo cho **30-40 học sinh**.<br>- Mất khoảng **1-3 ngày** để hoàn thiện nhận xét.<br>- Có thể kiểm chứng qua deadline báo cáo, số file nhận xét đã tạo. |
AI đã dùng ở Phase 1:

Prompt đã hỏi:
"Đóng vai trò là chuyên gia Product Discovery, hãy giúp tìm các pain point thực tế của giáo viên tiểu học có thể ứng dụng AI. Mỗi pain point cần có: công việc cụ thể, người chịu ảnh hưởng, dấu hiệu đo lường được (thời gian, tần suất, số lượng), quy trình hiện tại và cơ hội AI."
Ý dùng được:
Giáo viên mất nhiều thời gian chấm bài và viết nhận xét → có quy trình lặp lại, dễ đo bằng số lượng bài/ngày, thời gian chấm.
Giáo viên khó cá nhân hóa bài tập cho từng học sinh → có pain rõ từ sự khác biệt năng lực trong cùng một lớp.
Giáo viên khó phát hiện sớm lỗ hổng kiến thức → có thể khai thác dữ liệu bài làm để hỗ trợ.
Giáo viên tốn thời gian tìm và chỉnh sửa tài liệu → có hành vi lặp lại, có thể đo bằng số lần tìm tài liệu/tuần.
Phụ huynh hỏi nhiều câu giống nhau ngoài giờ → có pain từ người khác (không chỉ người dùng trực tiếp).
Ý bỏ vì không phải pain thật:
Các ý quá thiên về "AI có thể làm được gì" nhưng chưa chứng minh giáo viên đang gặp vấn đề (ví dụ: AI tạo giáo án tự động).
Các ý chỉ mô tả mong muốn chung chung như "ứng dụng AI để nâng cao chất lượng giáo dục" nhưng không có workflow cụ thể.
Các vấn đề chưa đủ tần suất hoặc không gây ảnh hưởng lớn đến công việc hằng tuần.

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

| Rank | Problem (copy từ bảng scan)| Vì sao chọn (2-3 ý)|Điều còn chưa chắc |
| 1    | Giáo viên tiểu học mất nhiều thời gian tạo bài tập Toán phù hợp với nhiều mức năng lực trong cùng một lớp học. | - Actor rõ: giáo viên tiểu học là người trực tiếp thực hiện.<br>- Workflow có thể vẽ được: phân loại năng lực học sinh → chọn mục tiêu bài học → tạo bài tập → điều chỉnh độ khó → gửi học sinh.<br>- Bottleneck nằm ở bước tạo/chỉnh nhiều phiên bản bài tập; impact đo được bằng thời gian soạn bài, số phiên bản tạo mỗi tuần. | - Chưa biết giáo viên thực tế mất bao nhiêu thời gian cho việc tạo bài tập.<br>- Chưa rõ họ có thường xuyên tạo nhiều phiên bản hay chỉ dùng chung tài liệu.<br>- Cần xác định tiêu chí phân hóa bài tập hiện tại.         |
| 2    | Giáo viên không đủ thời gian nghe và sửa lỗi đọc cho từng học sinh lớp 1 mỗi ngày.| - Actor rõ: giáo viên lớp 1 và học sinh cần luyện đọc.<br>- Workflow rõ: giao bài đọc → học sinh đọc → giáo viên nghe → ghi lỗi phát âm → phản hồi → theo dõi tiến bộ.<br>- Bottleneck nằm ở bước nghe và phản hồi từng học sinh; impact đo được bằng số học sinh được sửa đọc/tuần, thời gian giáo viên dành cho luyện đọc.| - Chưa biết giáo viên hiện dành bao nhiêu phút/ngày cho việc nghe đọc.<br>- Chưa rõ lỗi phát âm có đủ nghiêm trọng để cần AI hỗ trợ không.<br>- Cần kiểm chứng mức độ chấp nhận việc học sinh dùng AI giọng nói.           |
| 3    | Giáo viên mất nhiều thời gian chuẩn bị nội dung dạy học và viết nhận xét cá nhân cho học sinh.| - Actor rõ: giáo viên là người thực hiện chính.<br>- Có workflow cụ thể: tìm tài liệu → chọn nội dung → chỉnh sửa giáo án → dạy học → tổng hợp kết quả → viết nhận xét.<br>- Impact có thể đo bằng thời gian chuẩn bị bài, số nhận xét phải viết mỗi kỳ.| - Problem đang quá rộng, có thể tách thành 2 bài toán khác nhau (chuẩn bị bài và viết nhận xét).<br>- Chưa xác định bước nào là bottleneck lớn nhất.<br>- Cần tìm workflow gây mất thời gian nhất trước khi xây giải pháp. |


### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — AI tạo bài tập Toán cá nhân hóa lớp 1

**Problem 1 câu:**

Giáo viên lớp 1 mất khoảng 3–5 giờ/tuần để tạo và điều chỉnh bài tập Toán theo nhiều mức năng lực trong cùng một lớp, khiến việc cá nhân hóa bài học khó duy trì.

**Actor:**

Giáo viên lớp 1 chịu trách nhiệm thiết kế bài tập, giao bài và theo dõi tiến độ học tập của học sinh.

**Thời điểm / bối cảnh:**

Trước mỗi buổi học hoặc đầu tuần khi giáo viên chuẩn bị bài tập Toán cho lớp có nhiều mức năng lực khác nhau.

**Current workflow:**

1. Xác định mục tiêu kiến thức của bài học

2. Đánh giá mức độ tiếp thu của các nhóm học sinh

3. Tạo bài tập Toán phù hợp với từng mức năng lực

4. Giao bài cho học sinh

5. Chấm bài và ghi nhận lỗi sai

6. Điều chỉnh bài tập cho lần học tiếp theo

**Bottleneck:**

Bước 3 — tạo nhiều phiên bản bài tập theo năng lực từng nhóm học sinh.

Giáo viên phải tự nghĩ câu hỏi, điều chỉnh độ khó và kiểm tra tính phù hợp của từng bộ bài tập.

**Impact:**

Giáo viên mất khoảng 180–300 phút/tuần cho việc tạo và chỉnh sửa bài tập.

Một lớp có khoảng 30–40 học sinh nhưng thường chỉ có 1–2 phiên bản bài tập, khiến một số học sinh gặp tình trạng bài quá dễ hoặc quá khó.

**Success metric:**

Giảm thời gian tạo bài tập từ 3–5 giờ/tuần xuống dưới 1 giờ/tuần.

Tăng tỷ lệ học sinh nhận được bài tập phù hợp với mức năng lực cá nhân.

**Non-AI alternative:**

Dùng ngân hàng câu hỏi có sẵn, template bài tập hoặc phân loại bài tập thủ công theo nhóm học sinh.

Giải pháp này giảm thời gian tạo mới nhưng vẫn cần giáo viên tự chọn và điều chỉnh bài phù hợp.

**AI hypothesis:**

AI Agent phân tích mục tiêu bài học và mức năng lực học sinh, sau đó tạo nhiều phiên bản bài tập với độ khó khác nhau.

Giáo viên review, chỉnh sửa và quyết định bài tập cuối cùng trước khi giao.

**Quick gut:**

☐ No AI
☐ Rule
☐ Workflow
☑ Agent
☐ Chưa biết

Draft current workflow
CURRENT STATE — 180–300 phút/tuần

[1 Xác định mục tiêu bài học: 15']

→ [2 Phân loại mức năng lực học sinh: 30']

→ [3 Tạo nhiều phiên bản bài tập: 120–180'] <-- bottleneck

→ [4 Giao bài: 10']

→ [5 Chấm bài + ghi nhận lỗi: 30–60']

→ [6 Điều chỉnh bài tiếp theo: 15']
Draft future workflow
FUTURE STATE — 45–60 phút/tuần

[1 Giáo viên nhập mục tiêu bài học + nhóm năng lực: 5']

→ [2 AI Agent tạo bộ bài tập theo mức độ: 5']

→ [3 AI gợi ý điều chỉnh độ khó + đáp án: 5']

→ [4 Giáo viên review + chỉnh sửa: 30–45'] <-- human boundary

→ [5 Giao bài cho học sinh: 5']

Fallback:
AI tạo bài chưa phù hợp → giáo viên chỉnh prompt hoặc sửa thủ công

#### PROBLEM CARD #02 — AI hỗ trợ chuẩn bị giáo án và viết nhận xét học sinh 

│ │
│ Problem 1 câu: │
│ Giáo viên lớp 1 mất nhiều thời gian chuẩn bị │
│ giáo án, thiết kế hoạt động học tập và viết │
│ nhận xét cá nhân cho học sinh sau mỗi buổi │
│ học. │
│ │
│ Ai chịu ảnh hưởng? │
│ Giáo viên lớp 1, tổ chuyên môn, học sinh. │
│ │
│ Thời điểm / bối cảnh: │
│ Trước mỗi buổi dạy và cuối ngày sau khi kết │
│ thúc tiết học, đặc biệt khi giáo viên cần │
│ chuẩn bị bài mới hoặc tổng hợp đánh giá học │
│ sinh. │
│ │
│ Workflow hiện tại: │
│ │
│ 1. Tìm tài liệu từ giáo án cũ, file cá nhân │
│ hoặc nguồn chia sẻ │
│ → 2. Chọn nội dung phù hợp với mục tiêu bài │
│ học │
│ → 3. Soạn giáo án và thiết kế hoạt động │
│ trên lớp │
│ → 4. Chuẩn bị bài tập/phiếu học tập │
│ → 5. Sau giờ học ghi nhận tình hình học tập │
│ → 6. Viết nhận xét cá nhân cho từng học │
│ sinh │
│ │
│ Bước nghẽn nhất: │
│ Bước 2-3 — tổng hợp tài liệu và chuyển │
│ thành giáo án/hoạt động phù hợp với lớp. │
│ │
│ Giáo viên phải tự chọn nội dung, điều chỉnh │
│ mức độ và viết lại nhiều phần thủ công. │
│ (30–60 phút/lần chuẩn bị bài) │
│ │
│ Impact: │
│ Giáo viên mất khoảng 5–8 giờ/tuần cho │
│ việc chuẩn bị bài và viết nhận xét. │
│ │
│ Với lớp 30–40 học sinh, việc viết nhận │
│ xét cá nhân có thể mất thêm 1–3 giờ/cuối │
│ tuần. │
│ │
│ Đo thành công bằng gì? │
│ Giảm thời gian chuẩn bị bài từ **5–8 giờ/tuần│
│ xuống còn 2–3 giờ/tuần. │
│ │
│ Giảm thời gian viết nhận xét cá nhân ít │
│ nhất 50–70% nhưng vẫn giữ được tính │
│ cá nhân hóa. │
│ │
│ Non-AI alternative: │
│ Template giáo án, thư viện bài giảng có │
│ sẵn, checklist chuẩn bị bài. │
│ │
│ Các cách này giúp giảm thời gian format │
│ nhưng giáo viên vẫn phải tự tìm, chọn và │
│ viết nội dung. │
│ │
│ AI hypothesis: │
│ AI Agent đọc mục tiêu bài học, tài liệu có │
│ sẵn và thông tin lớp học để đề xuất giáo │
│ án, hoạt động, bài tập và draft nhận xét │
│ cá nhân. │
│ │
│ Giáo viên review, chỉnh sửa và quyết định │
│ nội dung cuối cùng trước khi sử dụng. │
│ │
│ Quick gut: │
│ ☐ No AI │
│ ☐ Rule │
│ ☐ Workflow │
│ ☑ Agent │
│ ☐ Chưa biết │
└──────────────────────────────────────────────┘

Draft current workflow
CURRENT STATE — 5–8 giờ/tuần

[1 Tìm tài liệu cũ + nguồn tham khảo: 60']

→ [2 Chọn nội dung phù hợp mục tiêu bài học: 60']

→ [3 Soạn giáo án + thiết kế hoạt động: 120–180'] <-- bottleneck

→ [4 Chuẩn bị bài tập/phiếu học tập: 60']

→ [5 Ghi nhận tiến độ học sinh: 30']

→ [6 Viết nhận xét cá nhân: 60–180']
Draft future workflow
FUTURE STATE — 2–3 giờ/tuần

[1 Giáo viên nhập mục tiêu bài học + thông tin lớp: 10']

→ [2 AI Agent tìm và tổng hợp tài liệu phù hợp: 5']

→ [3 AI tạo draft giáo án + hoạt động + bài tập: 5']

→ [4 AI draft nhận xét theo dữ liệu học sinh: 5']

→ [5 Giáo viên review + chỉnh sửa: 90–150'] <-- human boundary

→ [6 Xuất bản giáo án / gửi nhận xét: 10']

Fallback:
AI đề xuất chưa phù hợp → giáo viên sửa nội dung thủ công

#### ROBLEM CARD #03 — AI Reading Coach lớp 1 

Problem 1 câu:

Giáo viên lớp 1 không đủ thời gian nghe và sửa lỗi đọc cho từng học sinh thường xuyên, khiến nhiều lỗi phát âm và tốc độ đọc chậm được phát hiện muộn.

Ai chịu ảnh hưởng:

Học sinh lớp 1, giáo viên lớp 1, phụ huynh.

Thời điểm / bối cảnh:

Trong các buổi luyện đọc hằng ngày hoặc khi giáo viên kiểm tra khả năng đọc của học sinh.

Workflow hiện tại:

1. Giáo viên giao đoạn đọc

→ 2. Học sinh luyện đọc

→ 3. Giáo viên nghe từng học sinh đọc

→ 4. Ghi nhận lỗi phát âm/tốc độ đọc

→ 5. Giao bài luyện tập bổ sung

→ 6. Theo dõi tiến bộ

Bước nghẽn nhất:

Bước 3 — nghe và đánh giá từng học sinh.

Giáo viên cần khoảng 5 phút/học sinh/tuần, với lớp 30–40 học sinh sẽ cần khoảng 150–200 phút/tuần chỉ để nghe đọc.

Impact:

Nhiều học sinh chỉ được giáo viên sửa đọc 1 lần/tuần hoặc ít hơn.

Giáo viên khó duy trì phản hồi cá nhân liên tục cho từng học sinh.

Đo thành công bằng gì:

Tăng thời gian luyện đọc cá nhân từ dưới 5 phút/tuần lên 15–20 phút/tuần/học sinh.

Giảm lỗi phát âm, tăng tốc độ đọc sau 8 tuần theo dõi.

Non-AI alternative:

Chia nhóm học sinh, tăng trợ giảng hoặc dùng bài luyện đọc có sẵn.

Tuy nhiên vẫn khó đánh giá phát âm chi tiết cho từng em.

AI hypothesis:

AI Speech Agent nghe học sinh đọc, phát hiện lỗi phát âm, tốc độ đọc và đưa phản hồi ngay sau khi luyện tập.

Giáo viên theo dõi dashboard để biết học sinh nào cần hỗ trợ thêm.

Quick gut:

☐ No AI
☐ Rule
☐ Workflow
☑ Agent
☐ Chưa biết

Draft current workflow
CURRENT STATE — 150–200 phút/tuần

[1 Giao bài đọc: 5']

→ [2 Học sinh đọc: liên tục]

→ [3 Giáo viên nghe từng học sinh + ghi lỗi: 150–200'] <-- bottleneck

→ [4 Giao bài luyện tập: 15']

→ [5 Theo dõi tiến bộ: 30']
Draft future workflow
FUTURE STATE — 30–45 phút/tuần

[1 Học sinh đọc với AI Coach: 10–15']

→ [2 AI phân tích phát âm + tốc độ đọc: tự động]

→ [3 AI tạo feedback cá nhân: tự động]

→ [4 Giáo viên xem dashboard + can thiệp nhóm yếu: 30'] <-- human boundary

Fallback:
AI phát hiện không chắc chắn → chuyển giáo viên kiểm tra


### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)
**Card tôi muốn pitch nhất:**

PROBLEM CARD #01 — AI tạo bài tập Toán cá nhân hóa lớp 1

Giáo viên lớp 1 mất nhiều thời gian tạo bài tập Toán phù hợp với
nhiều mức năng lực khác nhau trong cùng một lớp học.

Actor:
Giáo viên lớp 1

Workflow:
1. Xác định mục tiêu bài học
→ 2. Đánh giá mức độ học sinh
→ 3. Tạo bài tập theo từng mức năng lực
→ 4. Giao bài
→ 5. Chấm bài và điều chỉnh bài tiếp theo

Bottleneck:
Bước 3 — tạo nhiều phiên bản bài tập theo năng lực từng nhóm học sinh
(180–300 phút/tuần).

AI Solution:
AI Agent tạo và điều chỉnh bài tập theo mục tiêu bài học,
dữ liệu năng lực học sinh; giáo viên review trước khi sử dụng.

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

Tôi chọn bài toán này vì workflow rõ ràng, xảy ra lặp lại hàng tuần và
có bottleneck cụ thể ở bước tạo nhiều phiên bản bài tập.

Impact có thể đo được bằng thời gian giáo viên dành cho việc tạo bài
(từ 3–5 giờ/tuần xuống dưới 1 giờ/tuần) và tỷ lệ học sinh nhận được
bài tập phù hợp với năng lực.

Ngoài việc giảm workload cho giáo viên, bài toán này có tác động trực
tiếp đến khả năng cá nhân hóa việc học cho từng học sinh trong cùng
một lớp.

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

1. Đây có phải là pain đủ lớn để giáo viên sẵn sàng thay đổi workflow,
hay chỉ là một công việc có thể giải quyết bằng template/ngân hàng câu hỏi?

2. AI Agent có thực sự cần thiết hay một hệ thống rule-based với
ngân hàng bài tập phân loại sẵn đã đủ tạo ra giá trị?

**AI phản biện Card (nếu có):**
* **Điểm yếu AI chỉ ra:**

  * Chưa chứng minh đây là **pain lớn nhất** của giáo viên; có thể giáo viên đã quen dùng ngân hàng câu hỏi, giáo án mẫu hoặc tài liệu có sẵn nên mức độ đau chưa đủ cao.
  * Số liệu **180–300 phút/tuần** và **3–5 giờ/tuần** mới là ước lượng, chưa có bằng chứng thực tế từ phỏng vấn, quan sát hoặc log công việc.
  * Chưa rõ AI Agent tạo bài tập tốt hơn cách làm hiện tại ở điểm nào; nếu chỉ sinh câu hỏi theo độ khó thì có thể giải quyết bằng rule/template đơn giản.
  * Chưa xác định dữ liệu đầu vào để AI cá nhân hóa: điểm số, lỗi sai, tốc độ làm bài, lịch sử học tập hay đánh giá của giáo viên.
  * Success metric hiện tập trung nhiều vào **tiết kiệm thời gian giáo viên**, chưa chứng minh được **impact lên kết quả học tập của học sinh**.

* **Tôi sửa gì:**

  * Thu hẹp problem vào workflow cụ thể hơn: **bước tạo nhiều phiên bản bài tập Toán theo nhóm năng lực**, thay vì nói chung là "cá nhân hóa bài tập".
  * Bổ sung cách validate số liệu: phỏng vấn 5–10 giáo viên, bấm giờ 3 lần quy trình tạo bài, kiểm tra số lượng phiên bản bài tập thực tế mỗi tuần.
  * Làm rõ vai trò AI Agent: không chỉ tạo câu hỏi mà còn **phân tích mục tiêu bài học + dữ liệu học sinh + điều chỉnh độ khó + đề xuất bài tập phù hợp**.
  * Bổ sung metric về học sinh: tỷ lệ học sinh hoàn thành bài, số lỗi sai giảm, mức độ phù hợp của bài tập sau khi áp dụng AI.
  * Đặt câu hỏi challenge lại nhóm: "Nếu giáo viên chỉ cần dùng ngân hàng câu hỏi phân loại sẵn thì AI Agent có còn tạo ra lợi thế đủ lớn không?"
