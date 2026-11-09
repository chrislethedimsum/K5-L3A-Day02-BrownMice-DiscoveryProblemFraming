# Báo cáo cá nhân — MSSV_HoTen

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Phan Văn Diện
- MSSV:2A202603653
- Email trường (không bắt buộc, repo có thể để public):26ai.dienpv@vinuni.edu.vn
- Tên nhóm: BrowMice
- Link repo nhóm:https://github.com/chrislethedimsum/K5-L3A-Day02-BrownMice-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Lặp lại (tiếp nhận yêu cầu hỗ trợ)| Khi nhân viên gặp sự cố máy tính tôi muốn tiếp nhận yêu cầu nhanh chóng để xử lý kịp thời| IT support,nhân viên| yêu cầu gửi qua zalo,điện thoại, trực tiếp, dễ bị bỏ sót|
| 2 | Tốn thời gian (quản lý tài sản IT)| khi nhân viên hoặc bàn giao thiết bị tôi muốn biết lịch sử sử dụng và tình trạng thiết bị| IT support,nhân sự , quảnlý| Thông tin máy tính, máy in , màn hình đượclưu bằng excel hoặc ghi chép thủ công|
| 3 | Cần đọc tổng hợp nhiều thông tin (báo cáo công việc )| Khi quản lý cần đánh giá hiệu suất IT Support, tôi muốn có số liệu thống kê chính xác về sự cố và thời gian xử lý.| Trưởng phòng IT, IT Support| Phải tổng hợp Excel thủ công, khó thống kê số lượng ticket và thời gian xử lý.|
| 4 | Quản lý mạng| Khi mạng nội bộ hoặc Internet bị gián đoạn, tôi muốn xác định thiết bị hoặc khu vực gặp lỗi.| Toàn bộ nhân viên, IT Support| Người dùng báo mất mạng nhưng không xác định được lỗi nằm ở switch, router, access point hay máy trạm.|
| 5 | Phân loại sự cố| Khi nhận nhiều yêu cầu cùng lúc, tôi muốn phân loại theo mức độ ưu tiên để xử lý đúng thứ tự.| IT Support, các phòng ban| Sự cố nghiêm trọng đôi khi bị xử lý sau những yêu cầu ít quan trọng.|
| 6 | | | | |
| 7 | | | | |
| 8 | | | | |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

-

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | tiếp nhận yêu cầu hỗ trợ| vì thông tin đến chủ yếu từ zalo,cuộc gọi sms dẫn đến bị miss thông tin và không bảo mật| thói quen người dùng,zalo dễ sử dụng và phổ biến khi dùng ngoài công việc|
| 2 | quản lý tài sản IT| vì mất nhiều thời gian quản lý thông tin, tình trạng lịch sử sử dụng bàn giao tài sản băng file excel và biên bản giấy| vẫn đề này chủ yếu của team kế toán khi kiểm kê họ vẫn dùng cách cũ trên file excel đã quen|
| 3 | báo cáo công việc| vì tài liệu tổng hợp, thống kê và phân tích hiệu suất làm việc, tình trạng xử lýsựcốcủa bộ phận IT support| hiện tại đang có rất nhiều công cụ tổng hợp work flow,chưa chọn được công cụ hợp lý,đào tạo nhân viên sử dụng, chi phí bỏ ra|

### Problem Card #1

| Trường | Nội dung |  |
| --- | --- | --- |
| Job Story | Khi nhân viên gặp sự cố liên quan đến máy tính, máy in, mạng hoặc phần mềm, tôi muốn tiếp nhận và phân loại yêu cầu hỗ trợ một cách nhanh chóng để đảm bảo công việc của họ không bị gián đoạn. |  |
| Actor | IT support, nhân viên các phòng ban, trưởng bộ phân IT |  |
| Thời điểm / bối cảnh | Khi nhân viên gặp sự cố kỹ thuật trong giờ làm việc; khi nhiều phòng ban đồng thời gửi yêu cầu; khi có sự cố khẩn cấp liên quan đến hệ thống HIS, PACS hoặc mạng nội bộ. |  |
| Quy trình hiện tại (3–7 bước) | 1.Người dùng phát hiện sự cố 2.Liên hệ it support qua điện thoại , zalo, trực tiếp 3. IT support tiếp nhận và ghi nhận thông tin sự cố 4.IT support đánh giá mức độ nghiêm trọng và xác định nguyên nhân sơ bộ 5. tiến hành xử lý trực tiếp hoặc từ xa 6.xác nhận với người dùng và hoàn tất yêu cầu.7 tổng hợp thông tin sự cố vào excel hoặc ghi chép cá nhân |  |
| Bottleneck (bước nào, mất bao nhiêu phút) | yêu cầu phân tán ở nhiều kênh khác nhau (10p để user báo và gọi lại bằng nền tảng khác) không có cơ chế ưu tiên sự cố rõ ràng thông tin mô tả lỗi từ người dùng thường thiếu chi tiết |  |
| Impact (nếu không giải thì sao) | người dùng phải chờ đợi lâu,sự cố quan trọng không thể xử lý kịp thời, giảm năng suất làm việc của nhân viên và bộ phận IT |  |
| Success metric (baseline → target) | thời gian phản hồi trung bình,thời gian xử lý trung bình , tỷ lệ yêu cầu được xử lý đúng SLA,tỷ lệ yêu cầu bị bỏ sót,tỷ lệ xử lý thành công ngay từ đầu |  |
| Phương án không dùng AI | xây dựng hệ thống ticket bằng django, thiết lập mức độ ưu tiên và SLA,xây dựng dashboard theo dõi trạng thái ticket |  |
| Giả thuyết về AI (nếu có) | AI NLP có thể tự động phân loại yêu cầu dựa trên nội dung mô tả,LLM có thể trích xuất thiết bị, vị trí , triệu chứng và mức độ ảnh hưởng từ nội dung yêu cầu |  |
| Cảm nhận nhanh | Đây là vấn đề có tính thực tế cao, xuất hiện thường xuyên trong công việc IT Support. Có thể xây dựng MVP tương đối nhanh và thu thập dữ liệu thực tế để đánh giá hiệu quả. |  |

Quy trình nháp hiện tại:

```text

```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi cần kiểm tra, bàn giao, sửa chữa hoặc thu hồi thiết bị IT, tôi muốn tra cứu được đầy đủ thông tin và lịch sử sử dụng của từng thiết bị để quản lý tài sản chính xác và giảm thất thoát. |
| Actor | IT Support, quản trị viên IT, nhân viên sử dụng thiết bị, bộ phận hành chính và kế toán.|
| Thời điểm / bối cảnh | Khi nhân viên mới nhận việc; khi nhân viên chuyển phòng ban hoặc nghỉ việc; khi thiết bị bị hỏng, cần sửa chữa hoặc thay thế; khi kiểm kê tài sản định kỳ.|
| Quy trình hiện tại (3–7 bước) | 1. Tiếp nhận thông tin thiết bị mới 2.ghi nhận tên thiết bị, mã tài sản, serial number và cấu hình. 3. cập nhật thông tin thiết bị vào excel hoặc hệ thống quản lý 4.bàn giao thiết bị cho nhân viên và xác nhận người sử dụng. 5 cập nhật trạng thái khi thiết bị sửa chữa, thay thế hoặc điều chuyển. 6 kiểm kê tài sản định kỳ.7 đối chiếu dữ liệu thực tế với dữ liệu lưu trữ|
| Bottleneck (bước nào, mất bao nhiêu phút) | - dữ liệu thiết bị lưu trữ phân tán - thông tin bàn giao không được cập nhật kịp thời- khó theo dõi lịch sử sửa chữa và thay thế link kiện - khó xác định thiết bị nào đang được sử dụng, thiết bị nào đang dự phòng -kiểm kê thủ công mất nhiều thời gian|
| Impact (nếu không giải thì sao) | - có nguy cơ thất lạc hoặc thất thoát tài sản -khó xác định trách nhiệm quản lý thiết bị - tốn thời gian kiểm kê và đối chiếu -khó lập kế hoạch bảo trì , thay thế thiết bị -phát sinh chi phí sửa chữa và mua sắm không cần thiết|
| Success metric (baseline → target) | - tỷ lệ tài sản có thông tin đầy đủ -tỷ lệ sai lệch giữa dữ liệu và tài sản thực tế - thời gian trung bình để kiểm kê- tỷ lệ thiết bị có lịch sử bàn giao đầy đủ- tỷ lệ thiết bị đươc bảo trì đúng kế hoạch|
| Phương án không dùng AI | xây dựng hệ thống quản lý tài sản bằng django mysql - quản lý thông tin thiết bị theo mã tài sản và serial number- sử dụng qr code để tra cứu thông tin- quản lý lịch sử bàn giao, sửa chữa và bảo trì -xây dựng dashboard thống kê tài sản|
| Giả thuyết về AI (nếu có) | -AI có thể phân tích lịch sử sửa chữa để dự đoán thiết bị có nguy cơ hỏng hóc -machine learning có thể phân nhóm thiết bị theo mức độ sử dụng rủi ro -AI có thể phát hiện các bản ghi bất thường như thiết bị trùng serial, sai thông tin hoặc lịch sử bàn giao không hợp lý -AI có thể đề xuất thời điểm bảo trì dựa trên lịch sử sử dụng và sửa chữa|
| Cảm nhận nhanh | Vấn đề có tính ứng dụng lâu dài và phù hợp với môi trường doanh nghiệp, bệnh viện. Phần quản lý cơ bản không cần AI, nhưng dữ liệu lịch sử thiết bị có thể tạo nền tảng cho các bài toán dự đoán và phát hiện bất thường. |

Quy trình nháp hiện tại:

```text

```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi trưởng bộ phận IT yêu cầu báo cáo hiệu suất làm việc hoặc tình hình sự cố, tôi muốn tổng hợp dữ liệu nhanh chóng và chính xác để đánh giá khối lượng công việc, nhận diện vấn đề và đưa ra quyết định cải thiện hoạt động IT. |
| Actor | Nhân viên IT Support, trưởng nhóm IT, quản lý IT, ban lãnh đạo.|
| Thời điểm / bối cảnh | Cuối ngày, cuối tuần hoặc cuối tháng; khi quản lý yêu cầu báo cáo đột xuất; khi cần đánh giá hiệu suất nhân viên; khi cần xác định các loại sự cố xuất hiện thường xuyên.|
| Quy trình hiện tại (3–7 bước) | 1. thu thập thông tin từ nhật ký công việc , excel, ticket hoặc các kênh tiếp nhận sự cố 2.kiểm tra và chuẩn hóa dữ liệu 3. phân loại sự cố theo loại thiết bị , phòng ban và mức độ ưu tiên 4.tổng hợp số lượng yêu cầu và thời gian xử lý 5 tính toán các chỉ số hiệu suất 6.tạo bảng biểu, biểu đồ và báo cáo 7.gửi báo cáo cho quản lý|
| Bottleneck (bước nào, mất bao nhiêu phút) | - dữ liệu nằm ở nhiều nguồn khác nhau - phải tổng hợp excel thủ công-dễ xảy ra sai sots khi nhập liệu - khó xác định xu hướng sự cố - báo cáo chủ yếu mô tả những gì đa|
| Impact (nếu không giải thì sao) | - mất nhiều thời gian làm báo cáo - quản lý không có số liệu cập nhật kịp thời - khó đánh giá chính xác hiệu suất nhân viên - không nhận diện được các sự cố lặp lại - khó phân bố nhân lực và ngân sách IT hợp lý|
| Success metric (baseline → target) | - thời gian hoàn thành báo cáo -độ chính xác của dữ liệu báo cáo - tỷ lệ báo cáo được tự động hóa - thời gian xử lý sự cố trung bình theo từng loại - khả năng phát hiện xu hướng và sự cố lặp lại -độ chính xác của mô hình dự báo nếu triển khai AI|
| Phương án không dùng AI | -xây dựng dashboard bằng django , pandas và chart.js - tựđộng thu thập dữ liệu từ hệ thống ticket - chuẩn hóa và tính toán  KPI tự động - cung cấp báo cáo theo ngayf, tuần tháng. - xuất báo cáo excel/pdf|
| Giả thuyết về AI (nếu có) | -machine learning có thể dự báo số lượng ticket trong tương lai- time series forecasting có thể dự báo khối lượng công việc theo ngày hoặc tuần . Anomaly Detection có thể phát hiện sự gia tăng bất thường của một loại sự cố-LLM có thể tạo báo cáo bằng ngôn ngữ tự nhiên từ dữ liệu thống kế - AI có thể phân tích mối quan hệ giữa loại thiết bị , phòng ban và tần suất sự cố.|
| Cảm nhận nhanh | Đây là vấn đề có thể bắt đầu bằng dashboard thống kê, sau đó phát triển thành hệ thống dự báo, phát hiện bất thường và phân tích nguyên nhân sự cố. |

Quy trình nháp hiện tại:

```text

```

### Card muốn pitch nhất

- Card số: Tiếp nhận yêu cầu hỗ trợ IT
- Vì sao: Đây là vấn đề xuất hiện thường xuyên trong hoạt động IT Support. Yêu cầu đến từ nhiều kênh khác nhau khiến thông tin phân tán, khó theo dõi, dễ bỏ sót và không có cơ chế đánh giá mức độ ưu tiên rõ ràng. Giải pháp có khả năng áp dụng thực tế trong doanh nghiệp và môi trường bệnh viện.
- Câu hỏi muốn nhóm phản biện: Nếu nhân viên vẫn quen gửi yêu cầu qua Zalo hoặc gọi điện trực tiếp cho IT Support thay vì tạo ticket trên hệ thống, làm thế nào để đảm bảo tất cả sự cố đều được ghi nhận đầy đủ mà không làm tăng thao tác cho người dùng?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Chưa xác định rõ cách tiếp nhận yêu cầu khi người dùng tiếp tục sử dụng nhiều kênh khác nhau.| Có| Bổ sung phương án cho phép IT Support tạo ticket thay người dùng khi tiếp nhận yêu cầu qua điện thoại, Zalo hoặc trực tiếp.|

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | tôi đã pitch 1 problem nổi bật nhất trong 5 vấnđề nêu trên| Giúp nhóm hiểu rõ vấn đề yêu cầu hỗ trợ bị phân tán qua nhiều kênh và khó kiểm soát tiến độ.|
| Phản biện bài của bạn khác | tôi đã đặt câuhỏi:Nếu AI tạo ra email dựa trên những thông tin người dùng cung cấp, trong trường hợp email có nội dung nhạy cảm hoặc liên quan đến công việc nội bộ công ty, hệ thống sẽ xử lý và bảo vệ dữ liệu cá nhân cũng như dữ liệu doanh nghiệp như thế nào? | Giúp người đưa ra ý tưởng chú ý hơn đến bảo mật và quyền kiểm soát dữ liệu.|
| Nhận phản biện | Tôi tiếp nhận các câu hỏi phản biện về tính khả thi, khả năng người dùng thay đổi thói quen và cách xử lý yêu cầu từ nhiều kênh. | Nhận ra giải pháp không chỉ cần có chức năng tạo ticket mà còn phải giảm thao tác cho người dùng và đảm bảo không bỏ sót yêu cầu. |
| Gom cluster / cây OST | Tham gia nhóm các vấn đề theo chủ đề IT Support, quản lý tài sản, báo cáo công việc và vận hành hệ thống.| Giúp nhóm nhìn thấy mối liên hệ giữa các vấn đề và xác định những nhu cầu có thể phát triển thành giải pháp.|
| Chọn candidate problem | Tham gia đánh giá các Candidate dựa trên mức độ nghiêm trọng, tần suất xuất hiện và khả năng triển khai.| Giúp nhóm xác định vấn đề cần ưu tiên giải quyết thay vì lựa chọn giải pháp chỉ vì có công nghệ AI.|
| Kiểm chứng / research | Tìm hiểu quy trình tiếp nhận yêu cầu IT Support, hệ thống ticket, SLA và khả năng ứng dụng NLP/LLM trong phân loại sự cố.| Làm rõ phần nào có thể giải quyết bằng quy tắc thông thường và phần nào thực sự cần AI.|
| Quy trình nhóm | Tham gia phân tích quy trình từ lúc nhân viên báo sự cố đến khi IT Support xử lý và xác nhận hoàn thành.| Xác định các bước dễ phát sinh chậm trễ, đặc biệt là tiếp nhận, ghi nhận và phân loại yêu cầu.|
| Problem Statement | Tham gia xác định Actor, Bottleneck, Impact, Success Metric và Boundary cho bài toán của nhóm.| Giúp Problem Statement có phạm vi cụ thể, có chỉ số đánh giá và giới hạn rõ ràng cho AI.|
| Mức can thiệp AI | Phân tích và đề xuất Workflow kết hợp Rule-based và AI, trong đó AI hỗ trợ phân loại và trích xuất thông tin sự cố.| Tránh sử dụng Agent tự chủ khi chưa cần thiết; giữ quyền xác nhận mức ưu tiên và xử lý cho nhân viên IT.|
| Quyết định | Tham gia đánh giá Value, Usability, Feasibility và Viability để đề xuất triển khai thử nghiệm MVP.| Giúp nhóm xác định điều kiện cần kiểm chứng trước khi mở rộng hệ thống.|

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Không| Không| Không| Tự xác định các vấn đề xuất phát từ kinh nghiệm IT Support.|
| CP2 Problem Card | Không| Không| Không| Tự xây dựng 3 Problem Card dựa trên những vấn đề thực tế.|
| CP4 Research | Sử dụng AI để tìm hiểu mô hình IT Ticketing, SLA, NLP và ứng dụng LLM trong tiếp nhận sự cố.| Gợi ý các hướng nghiên cứu, phương pháp phân loại sự cố và các chỉ số đánh giá hiệu quả.| Một số đề xuất còn mang tính lý thuyết, chưa phản ánh đầy đủ quy trình thực tế tại doanh nghiệp và bệnh viện.| Chọn lọc các chức năng có khả năng triển khai thực tế, ưu tiên tiếp nhận ticket, phân loại sự cố và theo dõi SLA.|
| CP5 Quy trình | Sử dụng AI để phân tích và đề xuất quy trình tiếp nhận, phân loại, xử lý và đóng ticket.| Giúp phát hiện các bước có thể tự động hóa và xác định điểm cần nhân viên IT kiểm tra.| AI có thể bỏ qua tình huống người dùng báo lỗi qua điện thoại hoặc Zalo thay vì hệ thống.| Bổ sung cơ chế IT Support tạo ticket thay người dùng để tránh bỏ sót yêu cầu.|
| CP5–6 Problem Statement | Sử dụng AI để rà soát Actor, Bottleneck, Impact và Success Metric.| Giúp làm rõ phạm vi bài toán và đề xuất các chỉ số đo lường cụ thể.| Một số chỉ số chưa có dữ liệu baseline thực tế để xác nhận.| Chỉ giữ các chỉ số có thể thu thập được từ hệ thống ticket và yêu cầu đo baseline trước khi đánh giá.|
| CP6 Mức can thiệp / quyết định | Không| Không| Không| Tự đánh giá mức độ cần thiết của AI, rủi ro và khả năng triển khai để lựa chọn phương án phù hợp.|

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**
Tôi học được những vấn đề nỗi đau của các bạn trong nhóm 
**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**
Nhóm luôn tìm hiểu vấn đề trước khi đưa ra giải pháp 
**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**
Tôi không bị đổi ý phản biện của mình , sau những lần phản biện ý tưởng của tôi càng thêm chặt chẽ 
**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**
Kết quả kiểm chúng không làm tôi thay đổi quan điểm nhận định của mình  
**6.5. Điều khó nhất khi viết Problem Statement là gì?**
Điều khó nhất đối với tôi là xác định chính xác bottleneck và phân biệt giữa nguyên nhân gốc rễ với những biểu hiện của vấn đề. Ban đầu, tôi nhận thấy nhân viên gửi yêu cầu hỗ trợ IT qua nhiều kênh như Zalo, điện thoại, SMS hoặc trực tiếp, nhưng cần phân tích sâu hơn để xác định việc phân tán thông tin ảnh hưởng như thế nào đến thời gian phản hồi và xử lý sự cố. Ngoài ra, tôi cũng gặp khó khăn khi lựa chọn các chỉ số đo lường phù hợp để đánh giá mức độ cải thiện, chẳng hạn như thời gian phản hồi trung bình, thời gian xử lý và tỷ lệ bỏ sót yêu cầu. Tôi nhận ra rằng Problem Statement cần cụ thể, có thể đo lường và giới hạn rõ phạm vi, thay vì chỉ mô tả một vấn đề chung chung.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**
Nếu làm lại, tôi sẽ bổ sung thêm các luận điểm và luận cứ thực tế để chứng minh mức độ nghiêm trọng của vấn đề, thay vì chủ yếu dựa trên nhận định cá nhân. Tôi sẽ phản biện nhóm mạnh hơn ở việc xác định nguyên nhân gốc rễ, tính khả thi của giải pháp và vai trò thực sự của AI trong quy trình. Đặc biệt, tôi sẽ đặt câu hỏi liệu nhân viên có sẵn sàng thay đổi thói quen từ việc liên hệ IT qua Zalo, điện thoại sang sử dụng hệ thống ticket hay không. Tôi cũng sẽ yêu cầu nhóm làm rõ cách xử lý những yêu cầu vẫn đến từ các kênh bên ngoài hệ thống, tránh tình trạng triển khai phần mềm nhưng vẫn bỏ sót yêu cầu hỗ trợ. 

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

Vấn đề nhóm tôi lựa chọn là việc soạn thảo email mất thời gian, đặc biệt khi người dùng phải xác định nội dung, lựa chọn cách diễn đạt và điều chỉnh giọng văn sao cho phù hợp với người nhận và mục đích giao tiếp. Quy trình giải quyết bắt đầu từ việc người dùng cung cấp mục đích, nội dung chính và thông tin cần truyền đạt, sau đó AI hỗ trợ tạo bản nháp email để người dùng xem xét và chỉnh sửa. Các metric có thể sử dụng để đánh giá hiệu quả gồm thời gian hoàn thành một email, mức độ hài lòng của người dùng, số lần chỉnh sửa và chất lượng nội dung email. Boundary của giải pháp là tập trung vào việc hỗ trợ soạn thảo và cải thiện nội dung email, không tự ý gửi email hoặc thay người dùng đưa ra các quyết định quan trọng. AI sẽ can thiệp vào bước phân tích yêu cầu, đề xuất cấu trúc, tạo nội dung và điều chỉnh giọng văn theo ngữ cảnh. Người dùng vẫn cần kiểm tra tính chính xác, thông tin nhạy cảm và nội dung cuối cùng trước khi sử dụng. Từ đó, nhóm hướng đến xây dựng một giải pháp AI hỗ trợ soạn thảo email và đánh giá tính hiệu quả, khả thi cũng như mức độ hữu ích của giải pháp.

## 7. Tài liệu tham khảo

-
