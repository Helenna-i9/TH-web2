# Bài 5: Bộ chọn thẻ, class và id

## 1. Yêu cầu

Dùng CSS ngoài, bộ chọn body, #tieude, .thongbao và .luuy.

## 2. Tệp bài làm

Mở bai5.html bằng trình duyệt. CSS nằm trong style.css, cùng thư mục HTML.

## 3. Thao tác và nhận xét

1. Đổi color của body chỉ ảnh hưởng chữ kế thừa màu từ body. Các phần tử có màu riêng như #tieude, .thongbao và .luuy giữ màu đã khai báo; trong nội dung mẫu, các khối chữ đều có màu riêng nên không đổi màu thấy được.

2. Đổi .thongbao sang green: cả 2 đoạn có class="thongbao" đổi sang xanh lá.

3. Thêm class="luuy" vào đoạn khác: đoạn đó đỏ và đậm. Nếu đoạn đã có class, thêm tên lớp vào danh sách, ví dụ class="thongbao luuy". Với thứ tự CSS hiện tại, .luuy quyết định màu đỏ, .thongbao vẫn cho cỡ chữ 18px.

4. Đổi #tieude sang text-align: left chỉ căn trái tiêu đề có id="tieude".

5. class được tái sử dụng trên nhiều phần tử; id phải duy nhất trong một tài liệu. Bộ chọn id có độ ưu tiên cao hơn class khi các điều kiện cascade khác tương đương.

## 4. Cách thử

Sửa một thuộc tính mỗi lần, lưu tệp, tải lại trình duyệt. Sau khi quan sát, khôi phục giá trị ban đầu trước khi thử mục tiếp theo.
