# postman
+ Mục đích:Báo cáo này nhằm mục đích tóm tắt kết quả của các bài kiểm thử được thực hiện trên trang web https://reqres.in/api/users?page=2 bằng công cụ Postman.
  ![image](https://github.com/21012064-BuiThiNgocHuyen/postman/assets/124747527/8f13f342-45c2-4f1e-b036-8be7f8e0422f)

+ Báo cáo này bao gồm các bài kiểm thử sau:
  Kiểm tra trạng thái HTTP
  Kiểm tra nội dung phản hồi
  Kiểm tra thời gian phản hồi
Yêu cầu: GET https://reqres.in/api/users?page=2
+ Kiểm tra trạng thái HTTP:
  Kết quả mong đợi: 200 OK
  Kết quả thực tế: 200 OK
->Kết luận: Yêu cầu thành công.
+ Kiểm tra nội dung phản hồi:
 1. Kết quả mong đợi: Phản hồi JSON chứa tên người dùng "Michael" có trong phần body.
  Kết quả thực tế: Phản hồi JSON chứa tên người dùng "Michael" có trong phần body.
 2. Kết quả mong đợi: Phản hồi JSON chứa value ="12" với thuộc tính "total"
  Kết quả thực tế:Phản hồi JSON chứa value ="12" với thuộc tính "total"
->Kết luận: Nội dung phản hồi chính xác.
+ Kiểm tra thời gian phản hồi:
  Thời gian phản hồi trung bình: 360 ms
->Kết luận: Thời gian phản hồi chấp nhận được.
+ Kết luận: Tất cả các bài kiểm thử đều thành công. Trang web https://reqres.in/api/users?page=2 hoạt động bình thường.
