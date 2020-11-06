---
title: "Lab 4. Hiểu về web server"
date: 2020-11-05T09:33:19+07:00
draft: true
---
I. Web server là gì?
“Web server” có thể là phần cứng hoặc phần mềm, hoặc cả hai.

Ở khía cạnh phần cứng:

1 web server như là một máy tính lưu trữ các file của 1 website (html, css, js) và có thể phân phát chúng tới thiết bị người dùng (end-user).
Nó kết nối mạng internet và có thể truy cập thông qua tên miền nào đó.
Ở khía cạnh phần mềm:

1 web server bao gồm một số phần để điều khiển cách người sử dụng web truy cập tới các file được lưu trữ trên một HTTP server(máy chủ HTTP).
Một HTTP server là một phần mềm hiểu được các URL (các địa chỉ web) và HTTP (giao thức trình duyệt để xem các trang web).
 

II. Mô hình hoạt động

Ở mức cơ bản nhất, bất cứ khi nào một trình duyệt cần một file được lưu trữ trên một web server, trình duyệt request (yêu cầu) file đó thông qua HTTP.
Khi một request tới đúng web server (phần cứng), HTTP server (phần mềm) gửi tài liệu được yêu cầu trở lại, cũng thông qua HTTP.
 

III. Tổng Kết
Để xuất bản 1 website cần phải tạo 1 static website or dynamic website.

static website:

bao gồm 1 máy tính với 1 HTTP server (phần mềm)
gọi là static bởi vì server gửi các file nguyên vẹn (html, css, js) tới trình duyệt.
dynamic website:

bao gồm một static web server cộng với một application server và một database
gọi là dynamic bởi vì application server cập nhật các file được lưu trữ trước khi gửi chúng tới tình duyệt của bạn thông qua HTTP server.

