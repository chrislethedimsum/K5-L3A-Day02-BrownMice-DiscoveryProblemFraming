# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân. Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: BrownMice
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu): Khi cần trả lời email từ trường hoặc công ty (xác nhận, xin phép nghỉ, xin tài liệu, xin gia hạn), tôi muốn có bản nháp đúng giọng điệu và đủ ý ngay, để gửi nhanh mà không phải nghĩ lại từ đầu.
- Quyết định cuối: Go (Pilot phạm vi hẹp 2 tuần)

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

|  \# | Người đưa ra      | Candidate (Job Story ngắn)                                                                                                                                                                                                        | Actor                                                                                    | Bottleneck                                                                                                                                                                                                                                                                                                                                                           | Câu hỏi phản biện nhận được (ai hỏi)                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| --: | :---------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :--------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|   1 | Lê Xuân Phúc      | Khi gửi email giải trình hoặc xin phép giáo viên, tôi muốn soạn thảo đúng văn phong, để gửi đi sớm thay vì trì hoãn vì sợ dùng từ sai.                                                                                            | Sinh viên đại học cần liên hệ về học vụ/xin nghỉ/ xin hoãn deadline với giảng viên.      | Đọc đi đọc lại và sửa văn phong (30 phút), gây tâm lý e ngạidẫn đến trì hoãn không dám bấm gửi suốt 1-2 ngày.                                                                                                                                                                                                                                                        | Nguyễn Lê Hải Nam: Bình thường mọi người chỉ cần dùng chatgpt để viết email, hệ thống có sự cải tiến gì so với chatgpt? Phan Văn Diện: Nếu hệ thống có thể sử dụng AI để soạn email theo yêu cầu, vậy làm thế nào để đảm bảo nội dung email không bị sai lệch so với sự việc thực tế, đặc biệt với những email giải trình hoặc xin phép có thể ảnh hưởng đến kết quả học tập của sinh viên?                                                                                                                     |
|   2 | Lê Xuân Phúc      | Khi gặp một khái niệm kỹ thuật khó hiểu trong môn học,tôi muốn tìm tài liệu giải thích đơn giản kèm hình ảnh trực quan, để nắm bắt bản chất nhanh chóng mà không cần học lan man                                                  | Sinh viên ngành công nghệ thông tin, tự học hoặc ôn thi.                                 | Đọc lướt từng trang hoặc xem tua qua video để tìm có vị dụ củ thể hoặc hình vẽ                                                                                                                                                                                                                                                                                       | Nguyễn Lê Hải Nam: Phan Văn Diện: Nếu hệ thống cung cấp tài liệu giải thích kèm hình ảnh trực quan, làm thế nào để đảm bảo hình ảnh và nội dung giải thích thực sự chính xác về mặt chuyên môn, thay vì chỉ đơn giản hóa kiến thức đến mức gây hiểu sai bản chất?                                                                                                                                                                                                                                               |
|   3 | Lê Xuân Phúc      | Khi vào tối chủ nhật, tôi muốn tổng hợp lại các công việc đã làm, các khoản chi tiêu trong tuần, để đánh giá độ kỷ luật bản thân và lên kế hoạch cho tuần tới.                                                                    | Sinh viên tự lập cần quản lý ngân sách sinh hoạt vàt iến độ học tập.                     | Nhớ lại và gom các khoản chi tiêu nhỏ lẻ, không có hóa đơn, lúc mất 10-20 phút và số tiền có khi không đúng hoặc quên luôn.                                                                                                                                                                                                                                          | Nguyễn Lê Hải Nam: Phan Văn Diện: Với những khoản chi tiêu nhỏ lẻ không có hóa đơn, hệ thống sẽ thu thập dữ liệu bằng cách nào? Nếu người dùng vẫn phải tự nhập từng khoản chi thì giải pháp có thực sự giảm được thời gian và công sức so với việc ghi chép thông thường không?                                                                                                                                                                                                                                |
|   4 | Nguyễn Lê Hải Nam | Khi bắt đầu ngày làm việc, tôi muốn có một bản tổng hợp ngắn gọn về các việc sắp tới từ cả lịch trường và lịch công ty, để không bỏ sót việc và chủ động sắp xếp thời gian.                                                       | Tôi — lập trình viên đi làm, đồng thời là học viên chương trình thực chiến AI.           | Bước 2–4 (gom và đối chiếu chéo nhiều nguồn): khoảng 10–15 phút mỗi sáng. Ngoài ra mở lại kiểm tra 4–6 lần/ngày, mỗi lần 2–3 phút.                                                                                                                                                                                                                                   | Lê Xuân Phúc: Các công ty đều có chính sách bảo mật nghiêm ngặt về các thông tin liên quan tới công ty. Nếu giải pháp không truy cập trực tiếp vào lịch nội bộ công ty thì liệu Nam định giải quyết việc lấy dữ liệu này như thế nào? Phan Văn Diện: Nếu lịch công ty không thể kết nối trực tiếp do chính sách bảo mật, còn lịch trường nằm trên một nền tảng khác, vậy hệ thống sẽ đồng bộ dữ liệu từ hai nguồn như thế nào để đảm bảo thông tin luôn cập nhật mà không yêu cầu người dùng nhập lại thủ công? |
|   5 | Nguyễn Lê Hải Nam | Khi cần trả lời email từ trường hoặc công ty (xác nhận, xin phép nghỉ, xin tài liệu, xin gia hạn), tôi muốn có bản nháp đúng giọng điệu và đủ ý ngay, để gửi nhanh mà không phải nghĩ lại từ đầu.                                 | Tôi; người nhận là giảng viên, quản lý và đồng nghiệp.                                   | Bước 3–5 (tìm mẫu, viết nháp, đọc lại): 10–20 phút/email khó và 3–5 phút/email đơn giản; tổng khoảng 30–45 phút/ngày.                                                                                                                                                                                                                                                | Lê Xuân Phúc: Nếu với các lí do cố định mà Nam đã nêu ra mà đã có bộ template. Điều gì khiến Nam phải mất đến 10-20 phút để soạn email liên quan? Phan Văn Diện: Nếu AI tạo ra email dựa trên những thông tin người dùng cung cấp, trong trường hợp email có nội dung nhạy cảm hoặc liên quan đến công việc nội bộ công ty, hệ thống sẽ xử lý và bảo vệ dữ liệu cá nhân cũng như dữ liệu doanh nghiệp như thế nào?                                                                                              |
|   6 | Nguyễn Lê Hải Nam | Khi hộp thư có nhiều email từ trường và công ty, tôi muốn phân loại email theo nguồn, mức độ ưu tiên và loại việc, để biết ngay email nào cần xử lý trước và email nào chỉ cần đọc.                                               | Tôi — người nhận email từ hai nguồn trường và công ty.                                   | Bước 2–3 (đọc lướt và phân loại thủ công): 15–25 phút/lần, 2–3 lần/ngày, tức 30–60 phút/ngày. Email quan trọng dễ bị chìm lẫn trong newsletter/thông báo.                                                                                                                                                                                                            | Lê Xuân Phúc: Email trường và công ty đều là 2 emails riêng biệt. Vậy tiêu chí nào để xác định 1 email là cần xử lí ngay? <br>Phan Văn Diện: Nếu hệ thống phân loại email dựa trên mức độ ưu tiên bằng AI, trong trường hợp AI đánh giá sai một email quan trọng thành email thông thường, khiến người dùng bỏ lỡ thời hạn xử lý, giải pháp sẽ có cơ chế cảnh báo hoặc kiểm soát sai sót như thế nào?                                                                                                           |
|   7 | Phan Văn Diện     | Khi nhân viên gặp sự cố liên quan đến máy tính, máy in, mạng hoặc phần mềm, tôi muốn tiếp nhận và phân loại yêu cầu hỗ trợ một cách nhanh chóng để đảm bảo công việc của họ không bị gián đoạn.                                   | IT support, nhân viên các phòng ban, trưởng bộ phân IT                                   | Từ bước 3-5 mất 30 phút 3\. IT support tiếp nhận và ghi nhận thông tin sự cố 4.IT support đánh giá mức độ nghiêm trọng và xác định nguyên nhân sơ bộ 5\. tiến hành xử lý trực tiếp hoặc từ xa 6.xác nhận với người dùng và hoàn tất yêu cầu.                                                                                                                         | Lê Xuân Phúc: Nhân viên các phòng ban thường không rành kỹ thuật và khi họ gặp sự cố và báo cáo mọi thứ rất chung chung như là máy đơ, mạng lag, thì làm sao để hệ thống tiếp nhận để phân loại chính xác dữ liệu đầu vào? Nguyễn Lê Hải Nam:                                                                                                                                                                                                                                                                   |
|   8 | Phan Văn Diện     | Khi cần kiểm tra, bàn giao, sửa chữa hoặc thu hồi thiết bị IT, tôi muốn tra cứu được đầy đủ thông tin và lịch sử sử dụng của từng thiết bị để quản lý tài sản chính xác và giảm thất thoát.                                       | IT Support, quản trị viên IT, nhân viên sử dụng thiết bị, bộ phận hành chính và kế toán. | Bước 2-7: Mất cả ngày 2.ghi nhận tên thiết bị, mã tài sản, serial number và cấu hình. 3\. cập nhật thông tin thiết bị vào excel hoặc hệ thống quản lý 4.bàn giao thiết bị cho nhân viên và xác nhận người sử dụng. 5 cập nhật trạng thái khi thiết bị sửa chữa, thay thế hoặc điều chuyển. 6 kiểm kê tài sản định kỳ.7 đối chiếu dữ liệu thực tế với dữ liệu lưu trữ | Lê Xuân Phúc: Nếu gốc rễ của thất thoát tải sản do người dùng thì việc xây dựng công cụ tra cứu có thực sự giúp giảm được thời gian cả ngày kiểm kê hay không? <br>Nguyễn Lê Hải Nam:                                                                                                                                                                                                                                                                                                                           |
|   9 | Phan Văn Diện     | Khi trưởng bộ phận IT yêu cầu báo cáo hiệu suất làm việc hoặc tình hình sự cố, tôi muốn tổng hợp dữ liệu nhanh chóng và chính xác để đánh giá khối lượng công việc, nhận diện vấn đề và đưa ra quyết định cải thiện hoạt động IT. | Nhân viên IT Support, trưởng nhóm IT, quản lý IT, ban lãnh đạo.                          | Bước 2-7: Mất 2-3h 2.kiểm tra và chuẩn hóa dữ liệu 3\. phân loại sự cố theo loại thiết bị , phòng ban và mức độ ưu tiên 4.tổng hợp số lượng yêu cầu và thời gian xử lý 5 tính toán các chỉ số hiệu suất 6.tạo bảng biểu, biểu đồ và báo cáo 7.gửi báo cáo cho quản lý                                                                                                | Lê Xuân Phúc: Tần suất nhận report là bao lâu? Nếu diễn ra 1-2 lần/ tháng và mất 2-3 giờ thì liệu có đủ cấp thiết để ưu tiên so với các công việc diễn ra hằng ngay không? <br>Nguyễn Lê Hải Nam:                                                                                                                                                                                                                                                                                                               |

### 2.2. Cluster

| Cluster                                                   | Các candidate                                                                                                                                      | Pattern chung                                                                                                                                               |
| :-------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Cluster A: Giao tiếp & Xử lý văn bản email                | #1: Soạn email giải trình giảng viên (Phúc) <br>#5: Soạn email phản hồi trường & cty (Nam) <br>#6: Phân loại email trường & cty theo ưu tiên (Nam) | Đều xoay quanh kênh giao tiếp email, điểm nghẽn là việc đọc, phân loại, đắn đo câu từ và mất nhiều thời gian để viết bản nháp đúng chuẩn mực.               |
| Cluster B: Quản trị vận hành & Hỗ trợ kỹ thuật IT         | #7: Tiếp nhận và phân loại sự cố IT (Diện) <br>#8: Quản lý và tra cứu thiết bị IT (Diện) <br>#9: Báo cáo hiệu suất làm việc IT (Diện)              | Xoay quanh quy trình vận hành phòng IT doanh nghiệp, điểm nghẽn là xử lý thông tin phân tán, thao tác thủ công trên Sheet và tốn thời gian kiểm kê/báo cáo. |
| Cluster C: Quản lý thời gian, tri thức & Kế hoạch cá nhân | #2: Tìm tài liệu giải thích trực quan (Phúc) <br>#3: Tổng hợp chi tiêu & hoạt động tuần (Phúc) <br>#4: Tổng hợp lịch trường và lịch công ty (Nam)  | Phục vụ năng suất cá nhân của sinh viên/người đi làm, điểm nghẽn là khâu thu thập, tổng hợp dữ liệu từ nhiều nguồn rời rạc để ra quyết định                 |

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```
OUTCOME: Giảm ít nhất 60% thời gian xử lý các tác vụ hành chính và giao tiếp lặp lại hàng ngày của sinh viên và người đi làm trẻ
├── Opportunity A: Giảm thời gian đắn đo văn phong và viết bản nháp cho các email phản hồi quan trọng (từ 20' xuống < 5'/email)
├── Opportunity B: Tự động hóa khâu phân loại và tiếp nhận các yêu cầu hỗ trợ kỹ thuật để giảm thời gian chờ của nhân viên
└── Opportunity C: Rút ngắn thời gian đối chiếu chéo lịch trình giữa trường học và công ty vào mỗi đầu buổi sáng
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

- Xây dựng Chatbot tự động trả lời email thay thế hoàn toàn con người (Đây là công cụ kỹ thuật tự trị, vi phạm nguyên tắc an toàn dữ liệu và thiếu sự kiểm soát của người dùng).
- Cài đặt Extension AI trên trình duyệt tự động tóm tắt giáo trình (Đây là một tính năng phần mềm, không phải là cơ hội giải quyết nhu cầu cốt lõi).
- Tạo phần mềm quét mã QR tích hợp Excel để kiểm kê thiết bị IT (Đây là giải pháp công nghệ cụ thể, không làm rõ được điểm nghẽn thực sự trong hành vi con người).

### 2.4. Chấm điểm shortlist (1–5)

Candidate 5 (Nam): Soạn email phản hồi (trường và công ty).  
Candidate 1 (Phúc): Soạn thảo email giải trình / xin phép giảng viên.  
Candidate 7 (Diện): Tiếp nhận và phân loại yêu cầu hỗ trợ IT.

| Candidate                                 | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain |   Tổng |
| :---------------------------------------- | -------: | -----------: | -----------------: | -------------: | ----------: | -------------------------------------: | ---------------: | -----: |
| Candidate 5: Soạn email phản hồi (Nam)    |        5 |            5 |                  5 |              5 |           5 |                                      4 |                4 | **33** |
| Candidate 1: Soạn email giải trình (Phúc) |        4 |            4 |                  5 |              4 |           5 |                                      4 |                4 |     30 |
| Candidate 7: Tiếp nhận hỗ trợ IT (Diện)   |        4 |            4 |                  4 |              4 |           3 |                                      4 |                4 |     27 |

**Candidate được chọn:** Candidate #5 của Nam: Soạn email phản hồi  
**Vì sao chọn:**

- Actor và quy trình cực kỳ sắc nét: Cả 3 thành viên đều đang vừa đi học vừa đi làm, trực tiếp trải nghiệm nỗi đau viết email hàng ngày với tần suất cao (3–8 email/ngày). Quy trình 6 bước rõ ràng từ khi đọc đến khi bấm gửi.
- Bottleneck có số liệu đo lường cụ thể: Tốn 10–20 phút cho một email khó, đốt 30–45 phút mỗi ngày, gây trễ hạn gửi thư quá 24h làm ảnh hưởng uy tín và tiến độ công việc.

**Vì sao loại các candidate còn lại:**

- Loại Candidate 1 (Soạn email giải trình của Phúc): Bài toán của Phúc có cùng bản chất với bài toán của Nam (cùng thuộc Cluster A), nhưng phạm vi hẹp hơn (chỉ tập trung vào email giải trình cho giảng viên, tần suất thấp 2–4 lần/tháng). Nhóm quyết định tích hợp điểm mạnh về yêu cầu kính ngữ và văn phong sư phạm của Phúc vào trường hợp "Email khó" trong bài toán của Nam.
- Loại Candidate 7 (Tiếp nhận hỗ trợ IT của Diện): Quy trình tiếp nhận IT phụ thuộc nhiều vào thói quen nhắn tin tự do của nhân viên qua Zalo/cuộc gọi (dữ liệu đầu vào quá nhiễu và thiếu cấu trúc). Ngoài ra, trên thị trường các giải pháp Helpdesk doanh nghiệp (Jira, Zendesk) đã giải quyết rất sâu mảng này, việc đưa vào bài lab dễ dẫn đến việc làm lại thứ thị trường đã có hoặc vượt quá thời gian thực hiện.

**Xử lý bất đồng (nếu có):** Ban đầu có sự tranh luận giữa bài toán của Nam và Diện vì nhóm muốn thử thách với một bài toán doanh nghiệp thực tế của IT Support. Tuy nhiên, sau khi phân tích bảng tiêu chí "Vừa sức bài lab" và "Khả năng kiểm chứng trong buổi học", nhóm nhận thấy bài toán IT của Diện rất khó để cả nhóm tự kiểm chứng và lấy dữ liệu thật ngay trong ngày. Cả nhóm (bao gồm cả bạn Diện) đã hoàn toàn nhất trí chọn bài toán Soạn email phản hồi của Nam để đi tiếp vào CP4, CP5 và CP6.

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

|   # | Giả định                                                                 | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
| --: | :----------------------------------------------------------------------- | :------------------------------------------------- | ---------------: | ---------------------: | :---------------- |
|   1 | Các cá nhân khác cũng mất trên 15 phút/ngày cho việc viết phản hồi email | Value                                              |                5 |                      3 | ✅                |
|   2 | Bước tốn nhất là format lại email cho đúng chuẩn                         | Value                                              |                5 |                      2 | ✅                |
|   3 | Người viết cần đọc lại email trước khi gửi                               | Value                                              |                5 |                      2 | ✅                |
|   4 | Người dùng cần cung cấp thông tin cho công cụ (nội dung chính, ...)      | Feasibility                                        |                5 |                      2 | ✅                |
|   5 | Người dùng cài đặt công cụ, đồng ý để AI viết email nháp                 | Viability                                          |                5 |                      2 | ✅                |

_Điền 4–6 giả định; xóa dòng thừa._

Giả định nhóm kiểm chứng trong buổi này: 1, 2, 3, 4, 5

### 3.2. Kiểm chứng

Cách đã dùng: Phỏng vấn / Survey / Log, ticket, review

Interview snapshot (mỗi buổi phỏng vấn một bảng, hoặc đặt file trong `report/assets/cp4-interview-snapshot-N.md`):

| Trường                                            | Nội dung                                                                                                |
| :------------------------------------------------ | :------------------------------------------------------------------------------------------------------ |
| Người được hỏi (vai trò, không ghi tên thật)      | Thành viên trong lớp                                                                                    |
| Câu nói đáng nhớ nhất (nguyên văn)                | "Bước khó nhất là format lại email cho vừa đúng chuẩn email công việc, vừa đầy đủ thông tin."           |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | Hôm qua, phản hồi chậm do viết email lâu.                                                               |
| Hiện đang xử lý bằng cách nào (workaround)?       | Dùng chatgpt sửa format.                                                                                |
| Mất bao lâu, bao lần?                             | Tuy việc viết email không lâu (khoảng 5 phút 1 email), nhưng nếu cần viết nhiều email sẽ mất thời gian. |
| Insight / opportunity rút ra                      | Pain nằm ở chỗ phải viết email vừa đúng chuẩn, vừa đầy đủ thông tin.                                    |

Tổng hợp:

| Nguồn          | Số người / số mẫu | Tín hiệu xác nhận                                                                 | Tín hiệu phản bác                                           |
| :------------- | ----------------: | :-------------------------------------------------------------------------------- | :---------------------------------------------------------- |
| Phỏng vấn      |                 3 | 2/3 người viết email thủ công và đều mất nhiều thời gian nhất ở phần format email | 1 người nói tự viết email sẽ giúp bày tỏ ý kiến rõ ràng hơn |
| Poll trong lớp |                 3 | 2/3 người đồng ý sử dụng công cụ soạn email phản hồi                              | 1 người nói không cần công cụ giúp viết email phản hồi      |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**
Từ tín hiệu phản bác của 1 người được phỏng vấn, nhóm đã nhận ra vấn đề không phải email nào cũng sự can thiệp tự động hóa. Cho nên nhóm đã thu hẹp phạm vi bài toán thành không áp dụng cho các email đơn giản/ngắn mà chỉ tập trung giải quyết phân khúc "Email khó và nhậy cảm" ví dụ xin gia hạn, từ chối họp, giải trình sự cố, nơi người dừng thử sự gặp bế tắc ở khâu format và lựa chọn kính ngữ phù hợp với ngữ cảnh.

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link                                                                       | Giải bước nào trong quy trình?                                                                   | Điểm mạnh                                                                                         | Khoảng trống / rủi ro                    | Bài học cho nhóm                    |
| :----------------------- | :------------------------------------------------------------------------- | :----------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------ | :--------------------------------------- | :---------------------------------- |
| Microsoft Copilot        | https\://www\.microsoft.com/vi-vn/microsoft-365/outlook/ai-email-assistant | Đọc email gửi đến,tóm tắt email dài, ưu tiên thư quan trọng và đề xuất nội dung trả lời tự động. | Đa dụng                                                                                           | Cần trả phí để sử dụng hết các chức năng | Có thể học tập kiến trúc, tính năng |
| Spike                    | https\://www\.spikenow.com/                                                | Tóm tắt email, soạn thảo thông minh, tổng hợp các tin nhắn, nhiệm vụ quan trọng trên bảng tin    | Biến các chuỗi email dài thành các đoạn hội thoại trực quan, dễ theo dõi giống như tin nhắn chat. | Cần trả phí                              | Có thể học tập kiến trúc, tính năng |

---

## 4\. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ (ASCII, Mermaid hoặc link ảnh trong `report/assets/`):

```c
[Nhận email cần phản hồi từ trường/công ty]
       │
       ▼
┌────────────────────────────────────────────────────────┐
│ Bước 1: Đọc email, xác định người gửi & việc cần trả lời│ (1–2 phút)
└────────────────────────────────────────────────────────┘
       │
       ▼
┌────────────────────────────────────────────────────────┐
│ Bước 2: Xác định giọng điệu (trang trọng vs thân mật)  │ (1 phút)
└────────────────────────────────────────────────────────┘
       │
       ▼
┌────────────────────────────────────────────────────────┐
│ Bước 3: Mở email cũ / lên mạng tìm mẫu câu tương tự     │ (3–5 phút)   [Bottleneck]
└────────────────────────────────────────────────────────┘
       │
       ▼
┌────────────────────────────────────────────────────────┐
│ Bước 4: Viết nháp từ đầu (lý do, đề xuất, thời gian)   │ (5–10 phút)  [Bottleneck]
└────────────────────────────────────────────────────────┘
       │
       ▼
┌────────────────────────────────────────────────────────┐
│ Bước 5: Đọc lại, rà soát kính ngữ, chính tả, ngày giờ  │ (2–3 phút)   [Bottleneck]
└────────────────────────────────────────────────────────┘
       │
       ▼
┌────────────────────────────────────────────────────────┐
│ Bước 6: Gửi thư (hoặc nhờ bạn/đồng nghiệp xem lại)     │ (1 phút)
└────────────────────────────────────────────────────────┘
       │
       ▼
[Hoàn tất gửi email]
```

| Bước | Actor            | Input                            | Output                                                                 | Thời gian / tần suất     | Ghi chú                                                                       |
| ---: | :--------------- | :------------------------------- | :--------------------------------------------------------------------- | :----------------------- | :---------------------------------------------------------------------------- |
|    1 | Người dùng (Tôi) | Email mới nhận trong hộp thư     | Xác định rõ ai gửi (thầy cô, sếp, đồng nghiệp) và nội dung cần trả lời | 1–2 phút / 3–8 lần/ngày  | Đọc hiểu nhanh, chưa gặp khó khăn                                             |
|    2 | Người dùng (Tôi) | Vai vế người nhận                | Định hình tone giọng (kính cẩn, trang trọng hay thân thiện)            | 1 phút / 3–8 lần/ngày    | Đắn đo khi gặp người nhận có vị thế cao                                       |
|    3 | Người dùng (Tôi) | Ký ức hoặc hộp thư tìm kiếm      | Mẫu câu, cấu trúc thư tương tự từng dùng trước đây                     | 3–5 phút / 2–4 lần/ngày  | Bottleneck: Lục tìm thủ công các email cũ để copy mẫu câu                     |
|    4 | Người dùng (Tôi) | Mẫu câu cũ \+ hoàn cảnh hiện tại | Bản nháp email hoàn chỉnh                                              | 5–10 phút / 2–4 lần/ngày | Bottleneck chính: Tốn nhiều thời gian ghép ý, lựa chọn từ ngữ né gây mất lòng |
|    5 | Người dùng (Tôi) | Bản nháp vừa viết                | Bản email đã được sửa lỗi chính tả, kính ngữ, ngày giờ                 | 2–3 phút / 3–8 lần/ngày  | Bottleneck: Đọc đi đọc lại nhiều lần do tâm lý sợ sai sót                     |
|    6 | Người dùng (Tôi) | Bản email hoàn chỉnh             | Email được gửi đi thành công                                           | 1 phút / 3–8 lần/ngày    | Nếu quá phân vân thường trì hoãn chưa bấm gửi ngay                            |

**Bottleneck chính:** Nằm ở Bước 3, 4 và 5 (Tìm mẫu câu cũ → Tự gõ nháp từ đầu → Rà soát kính ngữ và chỉnh sửa format). Tổng cộng 3 bước này ngốn từ 10–20 phút cho một email khó (xin hoãn deadline, xin nghỉ, từ chối việc). Nguyên nhân sâu xa là người dùng thiếu một khung phản hồi chuẩn ngữ cảnh ngay tại chỗ và sợ mắc lỗi ứng xử với cấp trên.

### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.

```
[Nhận email cần phản hồi]
       │
       ▼
┌─────────────────────────────────────────────────────────────────────────┐
│ Bước 1 (Con người): Đọc email, chọn hướng giải quyết (Đồng ý / Từ chối / │ (~30 giây)
│ Xin gia hạn) & gõ 1–2 ý chính ngắn gọn                                   │
└─────────────────────────────────────────────────────────────────────────┘
       │
       ▼
┌─────────────────────────────────────────────────────────────────────────┐
│ Bước 2 (Rule-based): Tự động trích xuất Tên, Vai vế, Ngày giờ từ email  │ (~3 giây)
│ gốc; lọc bỏ thông tin nhạy cảm (PII)                                    │
└─────────────────────────────────────────────────────────────────────────┘
       │
       ▼
┌─────────────────────────────────────────────────────────────────────────┐
│ Bước 3 (AI hỗ trợ): Đọc ngữ cảnh email gốc + ý chính người dùng         │ (~5 giây)
│ $\rightarrow$ Sinh bản nháp hoàn chỉnh đúng format và chuẩn mực kính ngữ │
└─────────────────────────────────────────────────────────────────────────┘
       │
       ▼
┌─────────────────────────────────────────────────────────────────────────┐
│ Bước 4 (Rule-based): Kiểm tra ràng buộc an toàn (đối chiếu tên người    │ (~2 giây)
│ nhận, ngày giờ, cảnh báo từ ngữ cấm/nhạy cảm)                           │
└─────────────────────────────────────────────────────────────────────────┘
       │
       ▼
┌─────────────────────────────────────────────────────────────────────────┐
│ Bước 5 (Con người - HITL): Đọc lướt bản nháp, chỉnh sửa nhanh 1-2 từ    │ (1–2 phút)
│ theo ý thích cá nhân $\rightarrow$ Bấm nút "Gửi"                         │
└─────────────────────────────────────────────────────────────────────────┘
       │
       ▼
[Email được gửi đi an toàn & đúng hạn]
```

### 4.3. Before / after

| Chỉ số               |                                                  Trước |                                                                      Sau (kỳ vọng) | Ghi chú                                                      |
| :------------------- | -----------------------------------------------------: | ---------------------------------------------------------------------------------: | :----------------------------------------------------------- |
| Số bước              |                                        6 bước thủ công |                                           5 bước (3 bước tự động hóa bằng Rule/AI) | Người dùng chỉ thao tác ở bước đầu và bước cuối              |
| Tổng thời gian       |                   10–20 phút / email khó (30–45'/ngày) |                                             ≤ 3–5 phút / email khó (dưới 15'/ngày) | Tiết kiệm \> 60% tổng quỹ thời gian mỗi ngày                 |
| Số bước thủ công     |                          6 bước (100% tự gõ và tự tìm) |                                                 2 bước (chọn ý chính \+ duyệt gửi) | Giảm áp lực tâm lý sợ viết sai văn phong                     |
| Bottleneck chính     | Bước 3, 4, 5 (lục mẫu cũ, đắn đo câu từ, soi kính ngữ) |                                             Bước 5 (Người dùng đọc duyệt bản nháp) | Người dùng chỉ đọc lướt để kiểm tra thay vì phải nghĩ từ đầu |
| Rủi ro mới phát sinh |      Chậm trễ gửi thư, lỡ việc, văn phong thiếu tự tin | Nguy cơ "ảo giác" (AI thêm ý sai) hoặc người dùng chủ quan bấm gửi mà không đọc kỹ | Giải quyết bằng bắt buộc bấm checkbox xác nhận trước khi gửi |

---

## 5\. Problem Statement v0 (CP5)

| Trường                                                                     | Nội dung                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| :------------------------------------------------------------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Actor**                                                                  | Sinh viên đại học kiêm người đi làm trẻ (thực tập sinh, nhân viên mới) thường xuyên nhận 3–8 email/ngày từ giảng viên, quản lý và đồng nghiệp.                                                                                                                                                                                                                                                                                                  |
| **Quy trình**                                                              | Đọc email cần trả lời → Chọn giọng điệu phù hợp → Tìm mẫu cũ → Tự gõ bản nháp từ đầu → Đọc rà soát kính ngữ, ngày giờ → Gửi thư.                                                                                                                                                                                                                                                                                                                |
| **Bottleneck**                                                             | Khâu tìm mẫu câu cũ, viết nháp và đắn đo format chuẩn mực đúng kính ngữ (mất 10–20 phút/email khó; tổng 30–45 phút/ngày).                                                                                                                                                                                                                                                                                                                       |
| **Impact**                                                                 | Phản hồi chậm (có khi quá 24h khiến đối phương phải gửi thư nhắc nhở) hoặc câu chữ thiếu tự tin hoặc thiếu lý do cụ thể khiến đối phương phải hỏi lại. Dễ trễ hạn xin phép/học vụ.                                                                                                                                                                                                                                                              |
| **Success Metric** (baseline → target, cách đo)                            | • Thời gian soạn email khó giảm từ 10–20 phút xuống ≤ 5 phút/email. • Tổng thời gian soạn email/ngày giảm từ 30–45 phút xuống dưới 15 phút/ngày. • Chất lượng truyền thông tốt lên khi tỷ lệ email phải hỏi lại thông tin giảm từ \~15% xuống dưới 10%. • Tính kịp thời khi 100% email quan trọng được gửi trong vòng 24 giờ. • Cách đo bằng người dùng tự ghi chép nhật ký thời gian và theo dõi trạng thái phản hồi email trong 2 tuần pilot. |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | • AI tuyệt đối không được tự động bấm gửi email mà chưa có sự đồng ý của người dùng. • AI không được tự bịa ra lý do cá nhân hoặc tự hứa hẹn mốc thời gian ngoài những ý con người đã nhập. • Con người (HITL) bắt buộc phải đọc duyệt bản nháp và tự tay bấm nút gửi cuối cùng.                                                                                                                                                                |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

---

## 6\. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô:**Độ mơ hồ trung bình – Độ phức tạp thấp đến trung bình.**

Vì sao:  
**Độ mơ hồ trung bình:** Nội dung email đầu vào có thể khác nhau tùy người gửi, mục đích và ngữ cảnh. Người dùng cần xác định ý định phản hồi như đồng ý, từ chối, xin nghỉ hoặc xin gia hạn. Tuy nhiên, người dùng vẫn có thể cung cấp 1–2 ý chính để định hướng nội dung.

**Độ phức tạp thấp đến trung bình:** Quy trình phản hồi email tương đối rõ ràng, gồm đọc email, xác định giọng điệu, trích xuất thông tin, tạo bản nháp và kiểm tra trước khi gửi. Các thông tin như tên người nhận, ngày giờ và cấu trúc email có thể xử lý bằng Rule-based, trong khi AI đảm nhiệm việc hiểu ngữ cảnh và diễn đạt nội dung.

### 6.2. So sánh 4 mức

| Mức                       | Phương án cho bài của nhóm                                                                                                                                                                                       | Đủ khi nào                                                                                                   | Rủi ro                                                                                                                          | Chọn?             |
| :------------------------ | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------ | :---------------- |
| **No AI** (sửa quy trình) | Xây dựng thư viện template email theo từng tình huống như xin nghỉ xin gia hạn , xác nhận công việc phản hồi giảng viên . Người dùng chọn mẫu và tự điền thông tin.                                              | Khi các tình huống email có nội dung cố định , ít thay đổi và không cần hiểu ngữ cảnh                        | Template cứng nhắc không xử lý tốt các tình huống mới người dùng vẫn phải tự chỉnh sửa nội dung và văn phong                    | Không chọn        |
| **Rule**                  | Sử dụng các quy tắc để nhận diện người gủi m, trích xuất tên , ngày giờ , phân loại email và áp dụng template tương ứng                                                                                          | Khi quy trình đã xác định rõ nhưng nội dung đầu vào thay đỏi theo từng tình huống và cần AI hỗ trợ diễn đạt  | Khó xử lý ngôn ngữ tự nhiên, email dài hoặc những tình huống có nhiều ngữ cảnh khác nhau.                                       | Có mức lựa chọn   |
| **Workflow**              | Kết hợp Rule-based và AI: người dùng nhập ý chính, hệ thống trích xuất thông tin từ email, AI tạo bản nháp theo ngữ cảnh và giọng điệu phù hợp, Rule kiểm tra các thông tin quan trọng, người dùng duyệt và gửi. | Khi quy trình đã xác định rõ nhưng nội dung đầu vào thay đổi theo từng tình huống và cần AI hỗ trợ diễn đạt. | AI có thể hiểu sai ý định, thêm thông tin không chính xác hoặc tạo văn phong chưa phù hợp. Cần có bước kiểm tra của con người.  | Có – Mức lựa chọn |
| **Agent**                 | Xây dựng AI Agent tự đọc email, tự xác định mục đích, tìm thông tin liên quan, soạn và gửi email hoặc thực hiện các hành động tiếp theo.                                                                         | Khi cần xử lý nhiều bước phức tạp, có khả năng tự lập kế hoạch và thực hiện nhiều hành động liên tục.        | Có thể tự đưa ra quyết định sai, gửi nhầm nội dung, làm lộ thông tin nhạy cảm hoặc gửi email khi chưa được người dùng cho phép. | Không chọn        |

**Mức chọn:**Workflow (Rule-based \+ AI \+ Human-in-the-loop).

**Vì sao không chọn mức đơn giản hơn:**  
No AI chỉ sử dụng template cố định nên không đáp ứng được sự đa dạng về nội dung, hoàn cảnh và giọng điệu của từng email.

Rule-based có thể trích xuất thông tin và phân loại email nhưng khó hiểu được ý định, sắc thái giao tiếp và diễn đạt nội dung phản hồi linh hoạt.

AI cần được sử dụng để hiểu ngữ cảnh email và tạo bản nháp tự nhiên, đúng mục đích giao tiếp.

Workflow là mức phù hợp vì kết hợp được khả năng xử lý dữ liệu có cấu trúc của Rule-based với khả năng hiểu và tạo ngôn ngữ của AI, đồng thời vẫn giữ quyền kiểm soát cho người dùng.

### 6.3. AI Canvas rút gọn

| Thành phần                                                        | Nội dung                                                                                                                                                                                                                                    |
| :---------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Prediction** — AI dự đoán / tạo ra gì?                          | AI phân tích nội dung email gốc và ý chính do người dùng cung cấp để xác định ngữ cảnh, mục đích phản hồi, giọng điệu phù hợp và tạo bản nháp email hoàn chỉnh.                                                                             |
| **Judgment** — con người cân nhắc, quyết định gì?                 | Người dùng xác định hướng phản hồi (đồng ý, từ chối, xin phép, xin gia hạn...), kiểm tra nội dung AI tạo ra, đánh giá mức độ chính xác, sự phù hợp của kính ngữ và quyết định có sử dụng bản nháp hay không.                                |
| **Action** — hành động cuối cùng là gì, ai làm?                   | Hệ thống tạo bản nháp và hiển thị cho người dùng. Người dùng tự chỉnh sửa nếu cần và trực tiếp bấm nút gửi email. AI không được tự động gửi email.                                                                                          |
| **Outcome** — đo kết quả bằng gì?                                 | Đo thời gian soạn email, thời gian chỉnh sửa, tỷ lệ email phải viết lại, tỷ lệ nội dung sai thông tin và tỷ lệ email quan trọng được phản hồi trong vòng 24 giờ.                                                                            |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | Nội dung email gốc, người gửi, người nhận, ý định phản hồi, 1–2 ý chính của người dùng và thông tin bổ sung nếu cần. Email gốc có sẵn trong hộp thư nếu người dùng cung cấp quyền truy cập; ý định và nội dung phản hồi do người dùng nhập. |
| **Feedback** — lấy phản hồi ở đâu để cải thiện?                   | Lấy phản hồi từ người dùng thông qua việc chỉnh sửa bản nháp, đánh giá mức độ phù hợp của văn phong, lựa chọn sử dụng hoặc không sử dụng bản nháp và ghi nhận các lỗi AI thường gặp.                                                        |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Bằng chứng:  
  Người dùng muốn được AI hỗ trợ (Augment), không muốn giao hoàn toàn việc phản hồi email cho AI.  
  Bằng chứng: Trong quy trình hiện tại, người dùng vẫn cần tự xác định mục đích phản hồi, lựa chọn giọng điệu và kiểm tra nội dung trước khi gửi.  
  Kết quả phỏng vấn cho thấy 2/3 người được hỏi xác nhận việc viết email thủ công mất nhiều thời gian nhất ở khâu định dạng và diễn đạt nội dung.  
  Vì vậy, AI chỉ nên hỗ trợ tìm kiếm ngữ cảnh, tạo bản nháp và chuẩn hóa văn phong. Người dùng vẫn là người chịu trách nhiệm về nội dung và quyết định gửi email.

- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào:  
  Đối với bài toán này, trường hợp AI báo nhầm (tự tạo thêm thông tin sai, tự đưa ra cam kết hoặc diễn giải sai ý định người dùng) nguy hiểm hơn.  
  Nguyên nhân: Nếu người dùng không phát hiện sai sót và gửi email, thông tin sai có thể gây hiểu nhầm với giảng viên, quản lý hoặc đồng nghiệp, ảnh hưởng đến uy tín và công việc.  
  Trường hợp AI bỏ sót một thông tin, email có thể chưa đầy đủ nhưng người dùng vẫn có cơ hội bổ sung trước khi gửi.  
  Cách xử lý:

  Chỉ sử dụng thông tin có trong email gốc và nội dung người dùng cung cấp.  
  Không cho phép AI tự bịa lý do cá nhân, ngày giờ hoặc cam kết thời hạn.  
  Sử dụng Rule-based để kiểm tra tên người nhận, ngày giờ và các thông tin quan trọng.  
  Hiển thị bản nháp để người dùng kiểm tra và chỉnh sửa.  
  Bắt buộc người dùng xác nhận trước khi gửi email.

  ***

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường                                          | Nội dung                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| :---------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Actor**                                       | Sinh viên đại học kiêm người đi làm trẻ (thực tập sinh, nhân viên mới), thường xuyên nhận khoảng 3–8 email/ngày từ giảng viên, quản lý và đồng nghiệp.                                                                                                                                                                                                                                                                                                                                                                                                       |
| **Quy trình**                                   | Nhận email cần phản hồi → Đọc và xác định mục đích → Chọn giọng điệu phù hợp → Tìm mẫu email cũ → Tự viết bản nháp → Kiểm tra nội dung, kính ngữ, ngày giờ → Gửi email.                                                                                                                                                                                                                                                                                                                                                                                      |
| **Bottleneck**                                  | Khâu tìm kiếm mẫu email, diễn đạt nội dung và rà soát văn phong phù hợp với từng đối tượng nhận email. Người dùng mất khoảng 10–20 phút cho một email khó và tổng cộng 30–45 phút/ngày theo ước tính ban đầu.                                                                                                                                                                                                                                                                                                                                                |
| **Impact**                                      | Mất thời gian cho các công việc giao tiếp lặp lại; phản hồi email chậm, có thể quá 24 giờ; nội dung thiếu thông tin hoặc văn phong chưa phù hợp khiến người nhận phải hỏi lại; người dùng thiếu tự tin khi gửi email quan trọng.                                                                                                                                                                                                                                                                                                                             |
| **Success Metric** (baseline → target, cách đo) | \- Thời gian soạn email khó: từ 10–20 phút xuống ≤ 5 phút/email. \- Tổng thời gian soạn email/ngày: từ 30–45 phút xuống dưới 15 phút/ngày. \- Tỷ lệ email phải hỏi lại thông tin: từ khoảng 15% xuống dưới 10%. \- Tỷ lệ email quan trọng được phản hồi trong vòng 24 giờ: mục tiêu 100%. \- Tỷ lệ bản nháp có thông tin sai do AI tự thêm: mục tiêu 0% trong bộ kiểm thử. \- Cách đo: Ghi nhật ký thời gian, lưu bản nháp trước/sau chỉnh sửa và đánh giá kết quả trong pilot 2 tuần. Baseline thực tế cần được đo lại vì số liệu phỏng vấn ban đầu còn ít. |
| **Boundary**                                    | \- AI không được tự động gửi email khi chưa có sự đồng ý của người dùng. \- AI không được tự bịa ra lý do cá nhân, thông tin sự việc, ngày giờ hoặc cam kết thời hạn. \- Không tự ý thay đổi mục đích phản hồi của người dùng. \- Không sử dụng thông tin nhạy cảm không cần thiết để tạo email. \- Người dùng bắt buộc phải kiểm tra nội dung, người nhận và thông tin quan trọng trước khi gửi. \- Nếu thiếu dữ liệu hoặc không xác định được mục đích phản hồi, hệ thống phải yêu cầu người dùng bổ sung thay vì tự suy đoán.                             |
| **AI intervention point**                       | Can thiệp chính tại bước tạo bản nháp: AI đọc ngữ cảnh email gốc kết hợp với ý chính người dùng nhập để tạo nội dung phản hồi. Rule-based hỗ trợ trích xuất thông tin và kiểm tra các trường quan trọng trước khi hiển thị bản nháp.                                                                                                                                                                                                                                                                                                                         |
| **Mức chọn**                                    | Workflow (kết hợp Rule-based \+ AI \+ Human-in-the-loop).                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| **Rủi ro & người kiểm tra**                     | Rủi ro AI hiểu sai ngữ cảnh, tạo thông tin không có trong email gốc, sai kính ngữ hoặc sai ngày giờ. Người dùng trực tiếp kiểm tra và chịu trách nhiệm duyệt nội dung trước khi gửi. Hệ thống có bước kiểm tra bằng Rule-based và yêu cầu xác nhận của người dùng.                                                                                                                                                                                                                                                                                           |

**Thay đổi so với v0 và lý do:**

| Trường | v0                                                             | v1                                                                                                                  | Vì sao đổi                                         |
| :----- | :------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------ | :------------------------------------------------- |
| Actor  | Sinh viên và người đi làm trẻ nhận email từ trường và công ty. | Làm rõ nhóm người dùng gồm sinh viên kiêm người đi làm, thực tập sinh và nhân viên mới, nhận khoảng 3–8 email/ngày. | Xác định rõ đối tượng sử dụng và phạm vi bài toán. |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

|   # | Tiêu chí               | Đạt khi                                                                                                     | Không đạt khi                                                                 |
| --: | :--------------------- | :---------------------------------------------------------------------------------------------------------- | :---------------------------------------------------------------------------- |
|   1 | Độ chính xác thông tin | Nội dung email phản ánh đúng email gốc và thông tin người dùng cung cấp; không tự thêm dữ kiện.             | Tự bịa lý do, thời gian, sự kiện hoặc cam kết không được người dùng cung cấp. |
|   2 | Đúng mục đích phản hồi | Email thể hiện đúng ý định của người dùng như đồng ý, từ chối, xin nghỉ, xin gia hạn hoặc xác nhận.         | Diễn đạt sai ý định, làm thay đổi quan điểm hoặc yêu cầu của người dùng.      |
|   3 | Văn phong và kính ngữ  | Cách diễn đạt phù hợp với người nhận là giảng viên, quản lý hoặc đồng nghiệp; lịch sự, rõ ràng và tự nhiên. | Sử dụng sai cách xưng hô, thiếu kính ngữ hoặc văn phong không phù hợp.        |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro          | Câu hỏi                                                           | Mức độ rủi ro (Thấp \= an toàn / TB / Cao \= nguy hiểm) | Lý do / bằng chứng                                                                                                                                                                                                                                                                     |
| :-------------- | :---------------------------------------------------------------- | :------------------------------------------------------ | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Value**       | Người dùng có thật sự cần và sẽ dùng không?                       | Trung bình                                              | Kết quả phỏng vấn 3 người cho thấy 2/3 người gặp khó khăn trong việc định dạng và diễn đạt email; khảo sát trong lớp cũng có 2/3 người đồng ý sử dụng công cụ. Tuy nhiên, số lượng mẫu còn ít nên cần kiểm chứng thêm với người dùng thực tế.                                          |
| **Usability**   | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | Thấp \- trung bình                                      | Giao diện dự kiến đơn giản, người dùng chỉ cần cung cấp ý chính, xem bản nháp và chỉnh sửa trước khi gửi. Tuy nhiên, cần đảm bảo người dùng hiểu rằng nội dung AI tạo ra chỉ là bản đề xuất, không phải nội dung mặc định chính xác tuyệt đối.                                         |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không?                     | Trung bình                                              | Nhóm có thể triển khai bằng mô hình ngôn ngữ lớn kết hợp Rule-based để trích xuất thông tin và kiểm tra dữ liệu. Đầu vào là email gốc và ý chính do người dùng cung cấp. Khó khăn chính là xử lý đa dạng ngữ cảnh và đánh giá độ chính xác của nội dung AI tạo ra.                     |
| **Viability**   | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành?     | Trung bình \- Cao                                       | Email trường và công ty có thể chứa thông tin cá nhân hoặc dữ liệu nội bộ. Việc sử dụng API AI bên ngoài có thể phát sinh chi phí và rủi ro bảo mật. Cần giới hạn dữ liệu gửi đi, có cơ chế ẩn thông tin nhạy cảm, thông báo rõ cách xử lý dữ liệu và tuân thủ chính sách của tổ chức. |

### 8.2. Kết luận

**Quyết định:** **GO – Triển khai thử nghiệm ở phạm vi nhỏ (Pilot).**

**Lý do:**

- Bài toán có nhu cầu thực tế: người dùng thường xuyên phải phản hồi email từ trường học và công ty, đặc biệt ở các tình huống cần lựa chọn văn phong và diễn đạt phù hợp.
- Kết quả kiểm chứng ban đầu cho thấy 2/3 người được phỏng vấn gặp khó khăn ở khâu định dạng email và 2/3 người tham gia khảo sát đồng ý sử dụng công cụ.
- Bottleneck đã được xác định cụ thể tại các bước tìm mẫu, viết nháp và rà soát nội dung.
- Giải pháp có thể triển khai trong phạm vi bài lab bằng Workflow kết hợp Rule-based và AI, không cần xây dựng Agent tự chủ.
- Các rủi ro về nội dung sai và bảo mật có thể được giới hạn bằng cơ chế kiểm tra của con người, lọc thông tin nhạy cảm và không tự động gửi email.

**Nếu Go — pilot nhỏ nhất:**

- **Đối tượng thử nghiệm:** 3–5 người dùng thuộc nhóm sinh viên đang đi làm, thực tập sinh hoặc nhân viên mới.
- **Thời gian:** 2 tuần.
- **Phạm vi:** Thử nghiệm với 3 nhóm tình huống email phổ biến:
  1. Email xác nhận và phản hồi thông tin.
  2. Email xin phép nghỉ hoặc xin gia hạn deadline.
  3. Email xin tài liệu hoặc trao đổi công việc.
- **Cách thực hiện:**
  1. Người dùng cung cấp email đầu vào và ý định phản hồi.
  2. Hệ thống sử dụng Rule-based để trích xuất thông tin cần thiết.
  3. AI tạo bản nháp theo ngữ cảnh và giọng điệu phù hợp.
  4. Rule-based kiểm tra các trường thông tin quan trọng.
  5. Người dùng đọc, chỉnh sửa và đánh giá bản nháp.
  6. So sánh thời gian và chất lượng giữa cách viết thủ công với cách sử dụng hệ thống.
- **Chỉ số đánh giá:** Thời gian soạn email, mức độ chính xác thông tin, mức độ phù hợp văn phong, số lần chỉnh sửa và mức độ hài lòng của người dùng.
- **Bảo mật:** Giai đoạn đầu sử dụng dữ liệu email giả lập hoặc đã ẩn thông tin cá nhân; không kết nối trực tiếp hộp thư công ty khi chưa có sự cho phép và cơ chế bảo mật phù hợp.

**Nếu Not Yet — cần kiểm chứng gì trước:**

- Phỏng vấn thêm người dùng ngoài nhóm để xác định tần suất và thời gian thực tế dành cho việc soạn email.
- Kiểm tra mức độ sẵn sàng sử dụng AI trong các email liên quan đến công việc nội bộ.
- Đánh giá độ chính xác của AI với các tình huống email khác nhau.
- Kiểm tra chi phí sử dụng mô hình AI và phương án bảo vệ dữ liệu.

**Nếu No-Go — nên làm gì thay AI:**

- Xây dựng thư viện template email theo từng tình huống.
- Phân loại mẫu theo đối tượng nhận: giảng viên, quản lý, đồng nghiệp.
- Sử dụng Rule-based để điền các trường thông tin cố định như tên, ngày giờ, tiêu đề và nội dung mẫu.
- Cho phép người dùng chỉnh sửa trước khi gửi.

**Ngưỡng dừng** (nếu sau … mà … thì quay về …):

- Nếu thời gian soạn email không giảm ít nhất 30% so với cách làm thủ công thì cần xem xét lại quy trình và mức can thiệp AI.
- Nếu tỷ lệ email có thông tin sai do AI tự thêm vẫn xuất hiện sau khi đã điều chỉnh prompt và quy tắc kiểm tra thì phải dừng sử dụng AI tạo nội dung tự động cho tình huống đó, chuyển sang template có kiểm soát.
- Nếu người dùng không cảm thấy hữu ích hoặc không muốn sử dụng công cụ thì cần quay lại kiểm chứng nhu cầu thực tế.
- Nếu không đảm bảo được an toàn dữ liệu cá nhân và dữ liệu doanh nghiệp thì không triển khai kết nối email thật; chỉ tiếp tục thử nghiệm với dữ liệu giả lập hoặc đã ẩn thông tin nhạy cảm.

---

## 9. Hạn chế và hướng tiếp theo

### 9.1. Hạn chế

- Quy mô và mẫu kiểm chứng còn hẹp: Do giới hạn thời gian của buổi lab, nhóm chỉ mới phỏng vấn sâu được 3 người và khảo sát nhanh 3 người trong lướp. Mặc dù có tín hiệu xác nhận lẫn cả phản bác thì mẫu này nhóm chủ yếu đại diện cho học sinh viên khối ngành công nghệ, nhóm cảm thấy chưa bao quát được các ngành nghề khác hoặc người đi làm lâu năm.
- Dữ liệu Baseline chủ yếu dựa trên tự theo dõi: Con số 10-20 phút/email khó và 30-45 phút/ngày mới được đo lương qua nhật ký cá nhân của từng thành viên trong nhóm, chưa có dữ liệu đo lường tự động như là extension theo dõi thời gian gõ phím, soạn thảo email.
- Mới nhìn từ 1 phía là người gửi: Nhóm mới chỉ phỏng vấn những người viết email mà chưa phỏng vấn được những người nhận email để đánh giá việc họ cảm thấy thế nào về một email được hỗ trợ bởi AI.
- Rào cản chính sách bảo mật của doanh nghiệp: Trong quá trình làm, nhóm chưa đánh giá được hết các quy định bảo mật htoong tin nội bộ của các công ty khi người dùng đưa ra ngữ cảnh công việc vào công cụ AI bên ngoài.

### 9.2. Hướng tiếp theo

- Triển khai Pilot 2 tuần ở phạm vi hẹp
- Thu thập dữ liệu định lương chuẩn xuác hơn
- Thêm khảo sát phản hồi từ người nhận
- Mở rộng các Candidate tiềm năng cho vòng sau

## 10. Tài liệu tham khảo

- Teresa Torres (2021). Continuous Discovery Habits: Discover Products that Create Customer Value and Business Value. Product Talk LLC. (Mô hình Opportunity Solution Tree - OST để phân định ranh giới giữa Outcome, Opportunity và Solution).
- Rob Fitzpatrick (2013). The Mom Test: How to talk to customers & learn if your business is a good idea when everyone is lying to you. (Phương pháp phỏng vấn kiểm chứng hành vi thực tế trong quá khứ thay vì hỏi ý kiến giả định).
- Ajay Agrawal, Joshua Gans, Avi Goldfarb (2018). Prediction Machines: The Simple Economics of Artificial Intelligence. Harvard Business Press. (Khung phân tích AI Canvas: Tách biệt Prediction của máy và Judgment của con người).
- Marty Cagan (2017). Inspired: How to Create Tech Products Customers Love. Silicon Valley Product Group / Wiley. (Mô hình đánh giá 4 rủi ro sản phẩm: Value, Usability, Feasibility, Viability).
- Google PAIR (People + AI Research). People + AI Guidebook. Truy cập tại: https://pair.withgoogle.com/
  (Nguyên tắc thiết kế Augment vs. Automate và phân tích rủi ro sai sót False Positive vs. False Negative).
- Microsoft Corporation. Microsoft Copilot for Outlook: AI Email Assistant Documentation. Truy cập tại: https://www.microsoft.com/vi-vn/microsoft-365/outlook/ai-email-assistant.
- Spike Now. Spike Email & Collaborative Workspace Documentation. Truy cập tại: https://www.spikenow.com/.
