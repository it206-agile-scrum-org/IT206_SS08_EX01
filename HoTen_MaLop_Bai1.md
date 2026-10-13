# Ước lượng Product Backlog cho nền tảng bán hàng qua livestream

## Nhiệm vụ 1: Kiểm tra dữ liệu

| Mã Story | Đủ rõ | Cần làm rõ | Thông tin/câu hỏi còn thiếu |
|---|---|---|---|
| LS01 | ☐ | ☒ | Khi đến giờ bắt đầu, phiên có cần tự chuyển sang trạng thái khác (ví dụ "Đang diễn ra") trong Story này không, hay chỉ cần hiển thị "Sắp diễn ra"? |
| LS03 | ☐ | ☒ | Nếu hai khách cùng đặt sản phẩm cuối cùng trong kho, hệ thống xử lý thế nào (đơn nào thành công, đơn còn lại nhận kết quả gì)? |

## Nhiệm vụ 2: Product Backlog đã ước lượng

| Mã Story | Mức ưu tiên | Kết quả phiếu | SP cuối cùng | Lý do ngắn |
|---|---|---|---|---|
| LS01 | 1 | 3 - 3 - 5 - 3 | 3 | Phiếu 5 SP chênh lệch do thông tin chưa rõ về xử lý trạng thái theo giờ; sau khi PO xác nhận chỉ cần trạng thái "Sắp diễn ra" thì phạm vi nhỏ lại. Độ phức tạp tương đương LS02 nên chốt 3 SP. |
| LS02 | 2 | 3 - 3 - 3 - 3 | 3 | Reference Story; các phiếu đã trùng nhau. |
| LS03 | 3 | 5 - 8 - 8 - 5 | 8 | Phiếu chênh lệch do đánh giá khác nhau về rủi ro đặt hàng đồng thời và quy tắc giảm/hoàn tồn. Story gồm nhiều luồng (tạo đơn, kiểm tra tồn, xác nhận, hủy) và có rủi ro tranh chấp tồn kho nên lớn hơn hẳn LS02, chốt 8 SP. |

## Nhiệm vụ 3: Vì sao "1 SP = 4 giờ" là sai

Story Point là thước đo tương đối về khối lượng, độ phức tạp và rủi ro của một Story so với Story tham chiếu, không phải thời gian. Cùng một Story có thể mất số giờ khác nhau tùy người làm và bối cảnh, nên quy đổi cố định sẽ sai và dễ biến ước lượng thành cam kết. Thay vào đó, nhóm dùng Velocity (tổng SP hoàn thành thực tế mỗi Sprint) để dự báo: nếu Velocity gần đây khoảng 20 SP thì Sprint tới nhóm chọn lượng việc trong khoảng đó, không cần đổi sang giờ.
