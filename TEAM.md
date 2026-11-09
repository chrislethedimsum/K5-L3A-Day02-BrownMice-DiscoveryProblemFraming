# Team

> Điền file này trên repo chung do nhóm trưởng fork. Nhóm điền phần **Thông tin nhóm** và **Thành viên**. Mỗi người tự điền phần của mình trong **Cá nhân**. Không copy file này sang repo khác.

## Thông tin nhóm

- Tên nhóm: BrownMice
- Candidate problem nhóm chọn (1 câu): Khi cần trả lời email từ trường hoặc công ty (xác nhận, xin phép nghỉ, xin tài liệu, xin gia hạn), tôi muốn có bản nháp đúng giọng điệu và đủ ý ngay, để gửi nhanh mà không phải nghĩ lại từ đầu.
- Quyết định cuối (Go / Not Yet / No-Go): Go (Pilot phạm vi hẹp 2 tuần)

## Thành viên

| STT | Họ và tên         | MSSV        | Vai trò trong nhóm | Tài khoản GitHub                                                             |
| --: | :---------------- | :---------- | :----------------- | :--------------------------------------------------------------------------- |
|   1 | Lê Xuân Phúc      | 2A202603655 | Nhóm trưởng        | [https://github.com/chrislethedimsum](https://github.com/chrislethedimsum)   |
|   2 | Nguyễn Lê Hải Nam | 2A202603699 | Thành viên         | [https://github.com/NguyenNam999-hash](https://github.com/NguyenNam999-hash) |
|   3 | Phan Văn Diện     | 2A202603653 | Thành viên         | [https://github.com/phanvandien](https://github.com/phanvandien)             |

Không ghi email hay số điện thoại vào bảng này, vì repo có thể để public.

Gợi ý vai trò (một người có thể giữ nhiều vai): điều phối thời gian, ghi chép, người phản biện chính, phụ trách kiểm chứng (phỏng vấn/survey), phụ trách research, vẽ quy trình, viết Problem Statement.

## Phân công theo checkpoint

| Checkpoint                                 | Người chính       | Người hỗ trợ                     | Sản phẩm                                       |
| :----------------------------------------- | :---------------- | :------------------------------- | :--------------------------------------------- |
| CP3 — Hội tụ nhóm                          | Lê Xuân Phúc      | Nguyễn Lê Hải Nam, Phan Văn Diện | Cluster, cây OST, bảng chấm điểm               |
| CP4 — Kiểm chứng                           | Nguyễn Lê Hải Nam | Lê Xuân Phúc, Phan Văn Diện      | Assumption map, snapshot hoặc survey           |
| CP4 — Research                             | Nguyễn Lê Hải Nam | Lê Xuân Phúc, Phan Văn Diện      | Bảng research có link                          |
| CP5 — Quy trình trước/sau                  | Lê Xuân Phúc      | Nguyễn Lê Hải Nam, Phan Văn Diện | Quy trình \+ bảng before/after                 |
| CP5 — Problem Statement v0                 | Lê Xuân Phúc      | Nguyễn Lê Hải Nam, Phan Văn Diện | Problem Statement v0                           |
| CP6 — Mức can thiệp + Problem Statement v1 | Phan Văn Diện     | Lê Xuân Phúc, Nguyễn Lê Hải Nam  | Ma trận, AI Canvas, eval, Problem Statement v1 |
| CP6 — Quyết định                           | Phan Văn Diện     | Lê Xuân Phúc, Nguyễn Lê Hải Nam  | 4 rủi ro \+ Go/Not Yet/No-Go                   |

## Cá nhân

Mỗi thành viên thêm một mục theo mẫu dưới đây, tiêu đề là `HoVaTen-MSSV`.

### HoVaTen-MSSV

**Phần việc phụ trách:**

- **Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- **Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- **Điều mình học được từ phần nhóm:**

### LeXuanPhuc-2A202603655

**Phần việc phụ trách:** Nhóm trưởng, điều phối tiến độ, phụ trách chính CP3 (Hội tụ nhóm) và CP5 (Quy trình trước/sau & Problem Statement v0).

- **Đóng góp cụ thể**:
  - Đóng góp Problem Card #1 (Email giải trình giảng viên); mang góc nhìn về kính ngữ và áp lực tâm lý học thuật tích hợp vào bài toán của Nam.
  - Chủ trì vẽ luồng quy trình trước/sau 5 bước, xác định chính xác bottleneck và thiết lập boundary nghiêm ngặt (cấm AI tự động gửi thư).
  - Soạn thảo Problem Statement v0 và xây dựng các success metric có baseline/target định lượng.
- **Bằng chứng**:
  - Mục 2 (Cluster, cây OST, bảng chấm điểm CP3) và Mục 4, 5 (Quy trình trước/sau, Problem Statement v0) trong `report/team/group_report.md`.
  - Các commit tạo khung báo cáo nhóm và bài cá nhân `report/individual/2A202603655_LeXuanPhuc.md`.
- **Điều mình học được từ phần nhóm:**
  - Nhận thức rõ sự khác biệt giữa "bài toán có nỗi đau lớn nhưng tần suất thấp" và "bài toán lặp lại hàng ngày có tần suất cao".
  - Kỷ luật tách bạch giữa Problem và Solution, kiên quyết loại bỏ tư duy "nhảy ngay vào làm chatbot" khi chưa thấu hiểu quy trình gốc.
    
### PhanVanDien-2A202603653

**Phần việc phụ trách:** Thành viên, phản biện kỹ thuật, phụ trách chính **CP6** (Mức can thiệp AI, Problem Statement v1, Đánh giá 4 rủi ro sản phẩm & Quyết định cuối cùng).

- **Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):  
  - Đóng góp 3 Candidate Problems (#7, #8, #9) thuộc Cluster B (Vận hành & Hỗ trợ kỹ thuật IT); mang góc nhìn thực tế về quy trình hỗ trợ doanh nghiệp vào buổi thảo luận nhóm.
  - Đóng vai trò phản biện tích cực nhất trong phiên pitch CP3: đặt 6 câu hỏi sắc bén cho Phúc và Nam xoay quanh rủi ro bảo mật dữ liệu doanh nghiệp, nguy cơ AI bịa đặt thông tin và khả năng kiểm soát khi AI phân loại sai độ ưu tiên.
  - Chủ trì xây dựng toàn bộ nội dung **CP6**: Xác định vị trí bài toán trên ma trận độ mơ hồ × độ phức tạp, so sánh 4 mức can thiệp để chốt mức Workflow; hoàn thiện AI Canvas rút gọn và trả lời 2 câu hỏi thiết kế của Google PAIR (Augment vs. Automate; phân tích rủi ro kiểu sai tệ hơn).
  - Soạn thảo Problem Statement v1, thiết lập 3 tiêu chí đánh giá đầu ra (Eval), phân tích ma trận 4 rủi ro (Value, Usability, Feasibility, Viability), đề xuất quyết định **Go** kèm kịch bản pilot 2 tuần và 4 ngưỡng dừng (Stop threshold) an toàn.

- **Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):  
  - Các câu hỏi phản biện tại bảng 2.1 (Pitch) trong `report/team/group_report.md`.
  - Toàn bộ Mục 6 (Mức can thiệp AI), Mục 7 (Problem Statement v1 & tiêu chí eval), Mục 8 (Bốn rủi ro & Quyết định) trong `report/team/group_report.md`.
  - File báo cáo cá nhân `report/individual/2A202603653_PhanVanDien.md` và các commit tương ứng trên repo nhóm.

- **Điều mình học được từ phần nhóm:**  
  - Nhận thức rõ ràng rằng cấp độ AI càng cao (Agent tự trị) không đồng nghĩa với giải pháp càng tốt. Với bài toán giao tiếp email đại diện cho uy tín cá nhân và tổ chức, cấp độ Workflow có con người kiểm duyệt (Human-in-the-loop) mới là giải pháp tối ưu và an toàn nhất.
  - Học được phương pháp luận thiết kế lấy con người làm trung tâm qua 2 câu hỏi của Google PAIR và tư duy sản phẩm của Marty Cagan: Luôn phải xác định "kiểu sai nào tệ hơn" và đặt ra "ngưỡng dừng" cụ thể trước khi bắt tay vào triển khai pilot.
