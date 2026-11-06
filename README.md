## Bài 3: Ứng dụng mô hình IPO trong xử lý lỗi Git

### 1. Báo cáo phân tích (IPO)

| Thành phần      | Nội dung                                                                                                                                                        |
| --------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Input (Đầu vào) | Ngữ cảnh: Đang sử dụng Git trên máy tính Windows nhưng không hiểu thông báo lỗi. Mã lỗi: `fatal: not a git repository (or any of the parent directories): .git` |
| Process (Xử lý) | AI phân tích mã lỗi, giải thích ý nghĩa, xác định nguyên nhân và đưa ra cách khắc phục phù hợp cho người mới học.                                               |
| Output (Đầu ra) | Bản dịch lỗi sang tiếng Việt và hướng dẫn 3 bước sửa lỗi cụ thể.                                                                                                |

### 2. Câu Prompt hoàn chỉnh

Sử dụng công thức: Ngữ cảnh → Mã lỗi → Yêu cầu.

Em là sinh viên năm nhất ngành Công nghệ thông tin, đang học cách sử dụng Git trên máy tính Windows nhưng chưa có nhiều kinh nghiệm.

Khi thực hiện lệnh Git, em nhận được thông báo lỗi sau:

`fatal: not a git repository (or any of the parent directories): .git`

Hãy giúp em:

1. Dịch thông báo lỗi trên sang tiếng Việt và giải thích ý nghĩa bằng ngôn ngữ đơn giản.
2. Cho biết nguyên nhân thường gặp gây ra lỗi này.
3. Hướng dẫn em 3 bước sửa lỗi cụ thể, từng bước một.
4. Đưa ra các lệnh cần nhập trong PowerShell và giải thích ngắn gọn từng lệnh.

Lưu ý: Hướng dẫn dành cho người mới học, dễ hiểu, không sử dụng kiến thức nâng cao.

### 3. Kết quả mong đợi từ AI

- Dịch lỗi: Git không tìm thấy thư mục quản lý Git (`.git`) trong thư mục hiện tại hoặc các thư mục cha.
- Nguyên nhân: Có thể em đang đứng sai thư mục, chưa di chuyển vào thư mục dự án hoặc chưa khởi tạo Git.

3 bước sửa lỗi:

1. Kiểm tra vị trí hiện tại bằng lệnh `pwd`.
2. Dùng lệnh `cd` để di chuyển vào đúng thư mục dự án.
3. Kiểm tra bằng lệnh `git status`. Nếu dự án chưa được khởi tạo Git thì mới sử dụng `git init`.

### 4. Kết luận

Mô hình IPO giúp em cung cấp thông tin đầu vào rõ ràng, giúp AI hiểu đúng vấn đề và đưa ra hướng dẫn sửa lỗi dễ hiểu, phù hợp với người mới học.
