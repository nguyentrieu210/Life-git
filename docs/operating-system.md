# Hệ điều hành cá nhân 🌿

Cập nhật: 2026-10-01

## Stable mode

`mode: stable`

Mục tiêu không phải lúc nào cũng là thắng ngay. Mục tiêu là **giữ hệ thống sống đủ lâu để còn cơ hội merge**.

### Nguyên tắc

- Không cưỡng cầu.
- Không bỏ cuộc.
- Không reset cả hệ thống chỉ vì một nhánh lỗi.
- Đóng một PR không đồng nghĩa bỏ mục tiêu.
- Chưa có dữ liệu mới thì không tự viết thêm kết luận.

## Mô hình cơ hội

```text
Opportunity arrives
        ↓
      Review
        ↓
       Fit?
     ↙     ↘
   No       Yes
   ↓         ↓
Close PR   Evaluate
             ↓
          Worth it?
          ↙     ↘
        No       Yes
        ↓         ↓
     Decline     Merge
```

## Quy tắc khi một “kèo” không ra bài

Không làm:

```text
Không phản hồi
→ lo lắng
→ ép tiến độ
→ tự hạ tiêu chuẩn
→ phụ thuộc vào một kèo
```

Thay vào đó:

```text
Không phản hồi
→ ghi nhận là thiếu dữ liệu
→ đặt mốc review
→ giữ pipeline
→ tìm thêm nhánh
→ đóng khi đủ bằng chứng
```

## Tư duy tài nguyên

Nguồn lực hữu hạn:
- thời gian;
- tiền;
- sức;
- sự chú ý;
- uy tín;
- cơ hội.

Vì vậy không “roll” một cơ hội quá lâu chỉ vì đã đầu tư thời gian vào nó.

Đây là nguyên tắc chi phí chìm:
> Đã bỏ công không phải là lý do đủ để tiếp tục.

## Tư duy ERP

Mọi vấn đề lớn nên tách thành:

### Đầu vào
Có dữ liệu gì? Thiếu gì?

### Quy trình
Ai làm? Khi nào? Theo điều kiện nào?

### Chứng từ / trạng thái
Đang ở bước nào?

### Kiểm soát
Có điểm kiểm tra nào?

### Ngoại lệ
Nếu kế hoạch hỏng thì có kịch bản nào?

### Đầu ra
Kết quả đo bằng gì?

## Tư duy Git

- `main`: mục tiêu dài hạn và trạng thái sống.
- branch: một hướng thử nghiệm.
- commit: một thay đổi có thể ghi nhận.
- PR: một cơ hội đang được xem xét.
- merge: cơ hội trở thành một phần của hệ thống.
- close: dừng một hướng không còn phù hợp.
- rollback: quay lại một phiên bản cách làm cũ khi chiến lược mới không tốt.
- không `git reset --hard` cả cuộc đời.

## Tư duy TFT

- Không roll vô hạn.
- Có bài thì chơi.
- Không có bài thì giữ tiền.
- Quan sát shop.
- Có biến động thì xoay comp.
- Một kèo fail chỉ là một ván / một branch, không phải game over.

## Khi cảm thấy “mọi thứ không ổn”

Câu hỏi đầu tiên không phải:
> “Tao thất bại à?”

Mà là:
> “Đây là lỗi dữ liệu, lỗi chiến lược, lỗi lựa chọn môi trường, hay chỉ là một chu kỳ chưa có đầu ra?”

Sau đó tách:
1. Sự kiện đã xảy ra.
2. Điều chưa biết.
3. Giả định đang tự thêm vào.
4. Hành động nhỏ nhất có thể kiểm chứng giả định đó.

## Tiêu chuẩn ra quyết định

Một quyết định tốt không nhất thiết là quyết định tạo kết quả ngay.

Nó phải:
- giảm rủi ro;
- tạo thêm dữ liệu;
- giữ quyền lựa chọn;
- không đốt quá nhiều tài nguyên;
- và không khóa tương lai một cách không cần thiết.

## Câu lệnh tinh thần

```text
panic: disabled
force_push: disabled
job_pipeline: open
life_status: running
```

feat: formalize stable operating system · 2026-10-01
