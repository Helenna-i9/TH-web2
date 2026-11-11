# Bài 9: So sánh content-box và border-box

## 1. Yêu cầu

Kế thừa Bài 8; hai đoạn giống nhau có id contentBox và borderBox, width 500px, padding 20px, border đỏ 5px.

## 2. Tệp bài làm

Mở bai9.html bằng trình duyệt. CSS nằm trong style9.css, cùng thư mục HTML.

## 3. Thao tác và nhận xét

1. content-box: width chỉ tính phần nội dung; border-box: width đã gồm nội dung, padding và border. Tổng chiều rộng nêu dưới đây không tính margin.

2. contentBox = 500 + 20 × 2 + 5 × 2 = 550px. borderBox = 500px; phần nội dung = 500 − 40 − 10 = 450px.

3. Đổi contentBox sang border-box: hai hộp đều rộng tổng cộng 500px.

4. Khôi phục content-box rồi đổi padding chung lên 40px: contentBox rộng 590px; borderBox vẫn rộng 500px, phần nội dung còn 410px. Nếu chỉ sửa padding của contentBox, borderBox không thay đổi.

5. Với width: 80%, gọi chiều rộng khối chứa là W: contentBox rộng 0.8W + 50px, borderBox rộng 0.8W (giữ padding 20px). Các hộp thay đổi theo chiều rộng cửa sổ.

6. Thêm max-width: 700px khi đang dùng width: 80%: giới hạn phần content của content-box ở 700px, nên hộp có thể rộng tổng cộng 750px; với border-box, tổng chiều rộng tối đa là 700px. Nếu vẫn width: 500px thì max-width: 700px chưa làm thay đổi kích thước.

7. Bài giữ đúng width: 500px nên có thể tràn trên màn hình nhỏ; đây là ví dụ đo mô hình hộp, không tự co chiều rộng.

## 4. Cách thử

Sửa một thuộc tính mỗi lần, lưu tệp, tải lại trình duyệt. Sau khi quan sát, khôi phục giá trị ban đầu trước khi thử mục tiếp theo.
