# 03 — Individual Reflection
## Thông tin cá nhân

- Họ và tên: Nguyễn Bảo Sơn
- Mã học viên: 2A202602402
- Nhóm: DPS
- Candidate problem nhóm chọn: Trợ lý ảo tổng hợp và tìm kiếm thông báo liên quan cho cư dân chung cư trong chat


## 1. Tôi đã tham gia vào phần nào?

| Hoạt động                  | Tôi đã làm gì? (việc cụ thể)                                                                                                                          | Kết quả / ảnh hưởng tới nhóm                                                               |
| -------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------ |
| Scan cá nhân               | Tìm và liệt kê các pain point trong lĩnh vực chung cư dựa trên các lăng kính: lặp lại, tốn thời gian, AI có thể tốt hơn, pain từ người khác.          | Tạo danh sách candidate problem ban đầu để nhóm có nhiều lựa chọn trước khi chọn bài toán. |
| Pitch Problem Card         | Pitch problem "Thông báo quan trọng của chung cư bị chìm trong kênh chat tương tác chung", làm rõ actor, workflow, bottleneck, impact.                | Giúp nhóm có một problem cụ thể thay vì ý tưởng AI chung chung.                            |
| Challenge bài của bạn khác | Đặt câu hỏi phản biện về việc pain có đủ lớn không, có cần AI Agent không, và dữ liệu validation đã đủ chưa.                                          | Giúp nhóm nhận ra cần phân biệt giữa giả thuyết và evidence thực tế.                       |
| Gom trùng / cluster        | Gom các problem có cùng bản chất như tìm kiếm thông tin, trả lời câu hỏi lặp lại, tổng hợp dữ liệu thành nhóm pain về "information retrieval".        | Giúp loại bỏ các problem trùng và tập trung vào problem có workflow rõ.                    |
| Chọn candidate problem     | Tham gia đánh giá các candidate theo tiêu chí: actor cụ thể, workflow 3–7 bước, bottleneck rõ, impact đo được.                                        | Nhóm chọn problem chung cư vì có trải nghiệm thực tế và workflow dễ mô tả.                 |
| Validation / research      | Xây dựng câu hỏi validation cho cư dân, ban quản lý; kiểm tra giả thuyết về việc khó tìm lại thông báo.                                               | Làm rõ pain không nằm ở việc gửi thông báo mà nằm ở việc tìm lại thông tin.                |
| Workflow nhóm              | Vẽ current workflow: nhận thông báo → tìm trong chat → xác minh → hỏi lại BQL; xác định bước nghẽn là tìm kiếm/xác minh.                              | Giúp xác định điểm AI có thể tham gia thay vì tự động hóa toàn bộ quy trình.               |
| Problem Statement          | Viết lại problem statement theo hướng: cư dân và BQL mất thời gian tìm kiếm, giải thích lại thông tin đã có vì dữ liệu phân tán.                      | Problem rõ hơn, tránh mô tả giải pháp AI trước khi hiểu pain.                              |
| Rule / Workflow / Agent    | Phân tích lựa chọn giải pháp: FAQ/rule, workflow tự động hay AI Agent.                                                                                | Nhóm chọn hướng AI Agent vì cần hiểu câu hỏi tự nhiên và tìm thông tin trong nhiều nguồn.  |
| Decision                   | Tham gia quyết định giữ problem chung cư và loại các problem có workflow chưa đủ rõ.                                                                  | Giúp nhóm tập trung vào một bài toán có khả năng validate và xây dựng prototype.           |


## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase                   | Tôi dùng AI để làm gì?                                                         | AI hữu ích ở đâu?                                                                         | AI sai / hời hợt              | Tôi sửa gì           | |
| Scan                    | Dùng AI brainstorm các pain point có khả năng áp dụng AI trong nhiều lĩnh vực. | AI giúp tạo nhanh nhiều hướng problem và gợi ý các góc nhìn khác nhau.                    | AI thường đưa ra nhiều ý tưởng quá rộng như "AI quản lý chung cư", "AI giáo dục" nhưng chưa có workflow cụ thể. | Tôi lọc lại theo tiêu chí actor + workflow + bottleneck + impact.                                                |
| Problem Card            | Dùng AI hỗ trợ viết Problem Card theo format chuẩn.                            | AI giúp cấu trúc problem, workflow, bottleneck, success metric nhanh hơn.                 | AI có xu hướng tự thêm số liệu giả định như "mất 30 phút/ngày" nếu không kiểm chứng.                            | Tôi chuyển các số liệu thành hypothesis cần validate, không xem là evidence thật.                                |
| Workflow                | Dùng AI để mô tả current workflow và future workflow.                          | AI giúp chia nhỏ quy trình thành các bước dễ phân tích.                                   | AI đôi khi nhảy ngay sang workflow có AI mà chưa hiểu quy trình hiện tại.                                       | Tôi xác định bottleneck trước rồi mới quyết định AI can thiệp ở bước nào.                                        |
| Research                | Dùng AI tạo khung câu hỏi interview và bảng validation.                        | AI giúp thiết kế câu hỏi để kiểm chứng pain, alternative solution và mức độ thường xuyên. | AI không thể thay thế dữ liệu phỏng vấn thật và có thể tạo ra insight giả nếu không có nguồn.                   | Tôi coi AI là công cụ chuẩn bị research, còn evidence phải đến từ người dùng thật.                               |
| Problem Statement       | Dùng AI hỗ trợ viết lại problem statement ngắn gọn hơn.                        | AI giúp loại bỏ câu chữ mô tả giải pháp quá sớm.                                          | AI có thể làm problem nghe hấp dẫn nhưng thiếu tính cụ thể.                                                     | Tôi chỉnh lại để tập trung vào hành vi thực tế: tìm kiếm, xác minh, trả lời lại thông tin.                       |
| Rule / Workflow / Agent | Dùng AI phân tích nên chọn Rule, Workflow hay Agent.                           | AI giúp so sánh mức độ phù hợp của từng hướng giải pháp.                                  | AI thường ưu tiên Agent vì nghe hiện đại dù rule/workflow có thể đủ.                                            | Tôi kiểm tra lại: nếu chỉ tìm FAQ cố định thì rule đủ; nếu cần hiểu câu hỏi mở và nhiều nguồn thì mới cần Agent. |
| Decision                | Dùng AI để phản biện lựa chọn cuối cùng.                                       | AI đưa ra các điểm yếu và rủi ro của problem.                                             | AI không biết context nhóm, nguồn lực và mức độ ưu tiên thực tế.| Tôi kết hợp phản biện AI với trải nghiệm thực tế và khả năng validate để ra quyết định.                          |


## 3. Reflection câu hỏi mở

-Tôi thấy ý tưởng của các bạn rất hay, nhưng có 1 số case không sát thực tế, dễ gây loạn thông tin khi AI hiểu sai thông tin người dùng
-Điều khó nhất khi viết Problem Statement là xác định được bài toán cần gì và cách bài toán đó được giải quyết theo các ngoại lệ phát sinh
-Cảm thấy Agent chỉ thích hợp trong trường hợp 1 mục tiêu bài toán cần giải quyết số lượng lớn các yêu cầu của người dùng mà chưa thể đưa ra các trường hợp như rule

Nếu làm lại:
    Tôi sẽ cải thiện lại cách tối ưu hiệu suất cho bài toán để có thể trở thành cỗ máy AI tốt nhất, vì level của agent hiện tại chỉ áp dụng cho 1 giới hạn nhỏ


