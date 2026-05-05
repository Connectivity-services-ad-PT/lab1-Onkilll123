# Known Issues · Buổi 1

Ghi lại lỗi chưa xử lý được hoặc đã xử lý xong.

| STT | Lỗi gặp phải | Lệnh gây lỗi | Cách đã thử | Trạng thái |
|---:|---|---|---|---|
| 1 | Docker không nhận trong PowerShell mặc định | `docker --version` | Thêm Docker vào PATH: `C:\Program Files\Docker\Docker\resources\bin` | Đã xử lý |
| 2 | Git chưa có trong PATH | `git --version` | Cài Git qua winget, thêm `C:\Program Files\Git\cmd` vào PATH | Đã xử lý |
| 3 | Python phiên bản 3.9.13 (khuyến nghị 3.11.x) | `python --version` | Vẫn hoạt động bình thường, sẽ nâng cấp sau | Chấp nhận |
