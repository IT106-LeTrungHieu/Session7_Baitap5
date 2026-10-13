# BÀI TẬP 5 – THIẾT KẾ CƠ CHẾ THEO DÕI KẾ HOẠCH SPRINT CHO ĐỘI RIKKEIGO

**Vai trò:** Lan (Scrum Master), thiết kế cơ chế để Đức (Product Owner) và Developers dùng lại mỗi Sprint.

## Phần 1 – Thiết kế cơ chế

### 1. Phạm vi và nguyên tắc

Cơ chế áp dụng từ lúc chuẩn bị Sprint Planning, trong suốt Sprint, đến Sprint Review và Retrospective. Mục tiêu là phát hiện sớm rủi ro đối với Sprint Goal và có căn cứ dự báo Sprint sau, với **4 thành phần** được duy trì trên một trang theo dõi Sprint và bảng công việc chung.

**Sprint Goal là điểm tham chiếu cho mọi quyết định về phạm vi.** SP dùng để ước lượng tương đối; Capacity dùng để xem thời gian và khả năng sẵn có. Không quy đổi SP sang giờ, không dùng Velocity hoặc Burndown làm KPI và không dùng chúng để xếp hạng các đội.

Dữ liệu lịch sử ban đầu là **18, 20, 19, 15, 13 SP**: Average Velocity **17 SP**, Velocity Range **13–20 SP**. Đề bài không cung cấp các giá trị Burndown từng ngày từ Bài 2–3, nên cơ chế sử dụng biểu đồ thực tế của đội, không tự tạo số liệu để kết luận tiến độ.

### 2. Bốn thành phần của cơ chế

| Thành phần | Dữ liệu đầu vào | Ai cập nhật? | Khi nào? | Giúp đội quyết định điều gì? |
|---|---|---|---|---|
| **1. Phiếu dự báo Sprint** | Sprint Goal dự kiến; Product Backlog đã sắp thứ tự; SP, Acceptance Criteria và phụ thuộc của PBI; Definition of Done; Capacity theo lịch làm việc/nghỉ phép; Velocity 5 Sprint gần nhất. | Developers xác nhận Capacity và đề xuất phạm vi; Đức cập nhật ưu tiên và phối hợp thống nhất Goal; Lan hỗ trợ ghi lại căn cứ. | Chuẩn bị trước và hoàn thiện trong Sprint Planning; cập nhật khi có thay đổi lớn về nguồn lực. | Chọn tập PBI đủ rõ, phục vụ Goal và có kế hoạch khả thi; nhận diện rủi ro trước khi chốt dự báo. Average và Range là tham chiếu, không phải mức bắt buộc. |
| **2. Bảng Sprint Backlog và Burndown** | PBI đã chọn, công việc thực hiện, trạng thái, trở ngại, PBI Done theo Definition of Done và thay đổi phạm vi đã thống nhất. | Developers cập nhật công việc và trạng thái Done; biểu đồ lấy từ bảng hoặc được người luân phiên trong đội cập nhật. | Mỗi ngày trước Daily Scrum; ghi thay đổi phạm vi ngay khi xảy ra. | Nhìn thấy công việc bị kẹt, việc chưa kiểm thử/tích hợp và xu hướng hoàn thành; chọn việc cần hỗ trợ hoặc ưu tiên hoàn tất. Không suy ra năng suất từ giờ làm hay hình dạng biểu đồ. |
| **3. Kiểm tra rủi ro Sprint Goal** | Sprint Goal; bảng công việc; Burndown; kết quả đã kiểm chứng; phụ thuộc và thời gian còn lại. | Developers đánh giá rủi ro trong Daily Scrum; Lan giúp gỡ trở ngại; Đức tham gia khi cần thương lượng phạm vi. | Mỗi Daily Scrum; xem kỹ vào giữa Sprint và ngay khi có dấu hiệu bất thường. | Đánh giá khả năng đạt Goal ở mức xanh/vàng/đỏ; chọn hành động, người phụ trách và thời điểm kiểm tra lại. Khi cần, Developers thương lượng với Đức đổi hoặc bỏ bớt phạm vi mà vẫn bảo vệ Goal. |
| **4. Sổ kết quả và học hỏi giữa các Sprint** | SP thực sự Done; kết quả Sprint Goal; phản hồi khách hàng; Capacity thực tế so với kế hoạch; nguyên nhân trở ngại, thay đổi phạm vi và dữ liệu chất lượng. | Developers xác nhận Done; Đức ghi nhận kết quả và phản hồi tại Review; Lan hỗ trợ tổng hợp bài học tại Retrospective. | Cuối mỗi Sprint; dùng lại khi chuẩn bị Sprint kế tiếp. | Cập nhật Average/Range của 5 Sprint gần nhất, hiểu nguyên nhân biến động và chọn một cải tiến cụ thể. Khi đội đổi thành viên hoặc cách ước lượng, ghi rõ bối cảnh để tránh áp dụng lịch sử máy móc. |

### 3. Quy ước vận hành để cơ chế dễ duy trì

**Burndown:** Thống nhất dùng SP còn lại của các PBI trong phạm vi hiện tại. Chỉ giảm SP của một PBI khi toàn bộ PBI đạt Definition of Done; PBI làm dở không được tính một phần Velocity. Ghi chú riêng khi thêm hoặc bỏ PBI để phân biệt thay đổi phạm vi với hoàn thành công việc; đường tham chiếu chỉ hỗ trợ quan sát, không phải đường đội buộc phải bám theo.

**Kiểm tra Sprint Goal:** Xanh nghĩa là chưa thấy trở ngại đáng kể đối với Goal; vàng nghĩa là có rủi ro cần xử lý; đỏ nghĩa là với kế hoạch hiện tại, Goal khó đạt và cần hành động ngay. Đây là mức rủi ro của kế hoạch, không phải điểm đánh giá con người. Mỗi rủi ro được ghi ngắn gọn theo mẫu: **dấu hiệu → ảnh hưởng đến Goal → hành động → người phụ trách → thời điểm kiểm tra lại**.

**Điều chỉnh trong Sprint:** Developers chủ động cập nhật kế hoạch công việc; khi cần đổi phạm vi PBI, thương lượng với Đức để giữ Sprint Goal. Nếu Goal trở nên lỗi thời, Đức với vai trò Product Owner có quyền hủy Sprint; không đổi Goal tùy tiện chỉ để báo cáo đạt kế hoạch.

**Nhịp sử dụng:** Planning dùng phiếu dự báo; mỗi ngày dùng bảng công việc và kiểm tra Goal ngay trong Daily Scrum; Review/Retrospective cập nhật sổ kết quả. Lan hỗ trợ đội sử dụng dữ liệu để ra quyết định, không đặt thêm cuộc họp báo cáo chỉ để đọc số liệu.

## Phần 2 – Xử lý tình huống

### 1. Ngày 4–6, Burndown nằm ngang dù Developers vẫn làm đủ giờ

Ngay ngày 4, bảng công việc và kiểm tra Goal trong Daily Scrum giúp phát hiện đường Burndown chưa giảm; với cách ghi SP theo PBI Done, điều này cho biết chưa có thêm PBI Done, nhưng chưa đủ để kết luận đội không làm việc hoặc Goal chắc chắn thất bại. Developers kiểm tra PBI lớn đang làm dở, công việc bị chặn, hàng chờ kiểm thử/tích hợp và tiêu chí Done, rồi đánh giá ảnh hưởng đến Goal thay vì chỉ nhìn số giờ đã làm. Đội ưu tiên cùng hoàn tất PBI phục vụ Goal, gỡ trở ngại và kiểm tra lại ở Daily Scrum hôm sau; nếu rủi ro còn cao đến ngày 5–6, thương lượng với Đức bỏ bớt phạm vi ít cần thiết cho Goal, tuyệt đối không ghi Done sớm để làm đẹp biểu đồ.

### 2. Sprint tới, 2 trong 4 Developers nghỉ mỗi người 3 ngày; Capacity giảm khoảng 15%

Phiếu dự báo phát hiện thay đổi trước Planning khi Developers cập nhật lịch nghỉ và phần kỹ năng/phụ thuộc bị ảnh hưởng; nếu Sprint dài 10 ngày và giờ làm của 4 người bằng nhau thì 6 ngày nghỉ trên 40 ngày-người tương ứng khoảng 15%, nhưng vẫn cần xác nhận Capacity thực tế. Đội dùng Average 17 SP và Range 13–20 SP làm tham chiếu, ưu tiên các PBI đủ rõ phục vụ Goal, rồi kiểm tra kế hoạch theo Capacity mới thay vì lấy 17 × 85% làm số SP phải nhận. Các PBI phụ thuộc người nghỉ cần được sắp lịch hoặc có người hỗ trợ; chỉ chốt phạm vi sau khi Developers thấy kế hoạch khả thi, đồng thời ghi rủi ro để kiểm tra hằng ngày.

### 3. Phản hồi đề nghị xếp hạng đội theo Velocity

“Velocity phụ thuộc cách ước lượng, loại công việc và bối cảnh riêng của từng đội nên không phù hợp để xếp hạng RikkeiGo với đội ứng dụng tài xế, cũng không nên dùng làm KPI. Quản lý nên theo dõi kết quả Sprint Goal kèm nguyên nhân, giá trị và phản hồi khách hàng, thời gian đưa thay đổi đến người dùng, chất lượng sản phẩm và các trở ngại cần hỗ trợ; xem xu hướng của từng đội trong bối cảnh của họ thay vì lập bảng thi đua SP.”
