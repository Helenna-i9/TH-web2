# Bài 11: Menu ngang với inline-block

## 1. Yêu cầu

Kế thừa Bài 10; liên kết inline-block, width 180px, border-box, padding 15px 10px, margin 0; nav padding 0.

## 2. Tệp bài làm

Mở bai11.html bằng trình duyệt. CSS nằm trong style11.css, cùng thư mục HTML.

## 3. Thao tác và nhận xét

1. inline: width không áp dụng cho liên kết văn bản thông thường, chiều ngang phụ thuộc nội dung và padding/border.

2. block: mỗi liên kết tạo hộp khối và bắt đầu trên dòng mới trong luồng bình thường, dù width chỉ là 180px.

3. inline-block: các mục có thể nằm cùng dòng và vẫn nhận width, padding đầy đủ.

4. Đổi width sang 220px: mục menu xuống dòng khi tổng chiều ngang vượt chỗ còn trống. Khoảng trắng giữa các thẻ inline-block cũng chiếm chỗ.

5. display: none trên liên kết Liên hệ: mục đó biến mất và không còn chiếm vị trí trong bố cục.

## 4. Cách thử

Sửa một thuộc tính mỗi lần, lưu tệp, tải lại trình duyệt. Sau khi quan sát, khôi phục giá trị ban đầu trước khi thử mục tiếp theo.
