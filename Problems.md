HTTP Code (https://en.wikipedia.org/wiki/List_of_HTTP_status_codes)
- 1XX: Information Response
- 2XX: Successful
- 3XX: Re-direction
- 4XX: Client Error
  - 404: Not found
- 5XX: Server Error

Three-way handshake (https://vienthongxanh.vn/quy-trinh-bat-tay-3-buoc-tcp/?srsltid=AfmBOoqExV-gtV4acI7YWm5wjVPQe5BhojACu3moudGnPjWhiAcdWHy_)
1. Máy chủ A: khởi tạo kết nối bằng cách gửi gói tin TCP SYN đến máy chủ đích, có chứa số thứ tự ngẫu nhiên đánh dấu sự bắt đầu của dữ liệu
2. Máy chủ đích: nhận gói và phản hồi bằng số thứ tự của chính nó, phản hồi bao gồm số xác nhận, số thứ tự tăng lên. 
3. Máy chủ A: xác nhận bằng cách gửi số xác nhận, sô thứ tự của máy chủ tăng thêm 1

