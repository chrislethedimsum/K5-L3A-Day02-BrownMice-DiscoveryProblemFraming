# Báo cáo cá nhân — MSSV_HoTen

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Phan Văn Diện
- MSSV:2A202603653
- Email trường (không bắt buộc, repo có thể để public):26ai.dienpv@vinuni.edu.vn
- Tên nhóm: BrowMice
- Link repo nhóm:

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
| Impact (nếu không giải thì sao) | |
| Success metric (baseline → target) | |
| Phương án không dùng AI | |
| Giả thuyết về AI (nếu có) | |
| Cảm nhận nhanh | Đây là vấn đề có thể bắt đầu bằng dashboard thống kê, sau đó phát triển thành hệ thống dự báo, phát hiện bất thường và phân tích nguyên nhân sự cố. |

Quy trình nháp hiện tại:

```text

```

### Card muốn pitch nhất

- Card số:
- Vì sao:
- Câu hỏi muốn nhóm phản biện:

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| | | |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | | |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: | |
| Nhận phản biện | Câu hỏi tôi nhận được: | Tôi đã sửa gì: |
| Gom cluster / cây OST | | |
| Chọn candidate problem | | |
| Kiểm chứng / research | | |
| Quy trình nhóm | | |
| Problem Statement | | |
| Mức can thiệp AI | | |
| Quyết định | | |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | | | | |
| CP2 Problem Card | | | | |
| CP4 Research | | | | |
| CP5 Quy trình | | | | |
| CP5–6 Problem Statement | | | | |
| CP6 Mức can thiệp / quyết định | | | | |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

---

## 7. Tài liệu tham khảo

-
