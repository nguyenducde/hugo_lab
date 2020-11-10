---
title: "Lab 1. Hiểu về DNS"
date: 2020-11-05T09:29:19+07:00

---
Câu 1: DNS là viết tắt của các chữ nào?
Domain Name System: Hệ thống tên miền hay Hệ thống phân giải (resolve) tên miền.
 

Câu 2: DNS dùng để làm gì?
DNS dùng để lưu trữ các tên miền (domain name), cung cấp dịch vụ chuyển đổi từ địa chỉ dạng chuỗi(domain name) sang dạng số (IP) và ngược lại.
 

Câu 3: Hãy truy cập 3 trang web mà không cần dùng tới tên miền (domain name)?



 

Câu 4: Tên miền cấp 1, cấp 2, cấp 3 là gì? cho ví dụ mỗi loại?
Tên miền cấp 1:
là tên miền quốc tế, dùng chung cho nhiều quốc gia, đại diện cho một lĩnh vực, ngành nghề hay khu vực địa lý vd: .com, .net, …
Tên miền cấp 2:

là tên miền quốc gia, thông thường mỗi quốc gia đều có tên miền riêng
vd: .vn, .cn
Tên miền cấp 3:

là kết hợp giữa tên miền cấp 2 và cấp 1.
vd: .com.vn, .edu.uk
 

Câu 5: Tên miền quốc tế là gì? cho 3 ví dụ?
– tên miền quốc tế: do Trung tâm quản lý tên miền quốc tế cấp

vd: .com, .net, .biz, .info, .org
 

Câu 6: Tên miền “nội địa” hay quốc gia là gì? cho 3 ví dụ?
tên miền “nội địa” do trung quản lý tên miền của mỗi quốc gia quản lý
vd: .vn, .com.vn, edu.vn
 

Câu 7: DNS server addresses trong cạc mạng máy tính dùng để làm gì? Tại sao lại có Preferred DNS server/Alternate DNS server?
Để thiết lập địa chỉ của máy phân giải tên miền. Một cái chính và một cái dự phòng.
 

Câu 8: Trong cạc mạng, không điền thông tin trong DNS server, có truy cập được trang web không? chứng minh?
Cạc mạng sẽ tự động chuyển sang chế độ lấy DNS server address tự động
Nếu cố tình gán một DNS server address không tồn tại thì không thể truy cập trang web
 

Câu 9: “8.8.8.8” là gì?
là DNS server address của google
 

Câu 10: Sau khi người dùng gõ vào trình duyệt https://www.w3schools.com/, gõ phím Enter.Viết lại quá trình một trình duyệt lấy trang web về?
Dựa vào thông tin DNS server address, gửi một gói tin để phân giải tên trang web sang IP
Gửi một gói tin yêu cầu nội dung trang web (index.html) tới Web server
Web server gửi nội dung trang web về cho máy client
Máy client thông dịch (biên dịch) mã nguồn của trang web (HTML, CSS, JavaScript) rồi hiển thị lên trình duyệt
Câu 11: Thử cấu hình DNS server: sửa tập tin hosts để khi người dùng truy cập trang tuoitre.vn, nội dung trình duyệt sẽ hiển thị thông báo lỗi “không thể truy cập được trang tuoitre.vn”

