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

**BYOD (BRING YOUR OWN DEVICE) **(https://www.ibm.com/think/topics/byod#:~:text=BYOD%2C%20or%20bring%20your%20own,and%20perform%20their%20job%20duties.): Personal device 
- When and where people can use their personal device in company

**Whitelist/ Blacklist**
- Whitelist: privileged list of people.
- Blacklist: people cannot access it.

**CC/BCC (Carbon Copy/ Blind Carbon Copy)**
- Carbon Copy: send it to a lot of people, and everybody knows
- Blind Carbon Copy: send it to a lot of people, and nobody knows each other.

**High RAM performance server**
- RAM lên cao ở sophos endpoint -> see the Product Analysis to analyze the problems (because it describes possible scenarios that we may face)
- If it happens next time, contact the Sophos support team immediately
- https://support.sophos.com/support/s/article/KBA-000009704?language=en_US
- According to the Screenshots, Sophos was consuming 40 - 50 GB of memory (not expected, gradually increase).
- Can check what are running from the task management. 

**Peripheral device (thiết bị ngoại vi)**
- Thiết bị được kết nối bên ngoài máy tính với mục dích mở rộng chức năng hoặc cung cấp thêm tính năng bổ sung cho máy tính
- Connect through ports: USB, HDMI...
- Input: Keyboard, optical pen...
- Output: Headphones, head set, printer, speakers...
- Input + output: digital camera, CD/DVD...

**Clipboard**
- Bộ nhớ đệm tạm thời (save data when people cut, copy them)
- W + I -> Settings -> System -> Clipboard (on/ off)
- W + V -> Clipboard history

**Virtualization**
- Tạo ra phiên bản ảo của các tài nguyên như máy chủ, thiết bị lưu trữ, mạng, hệ điều hành

**Test log (https://www.browserstack.com/guide/what-is-test-log)**
- The process of documenting the details of the testing process, the test case execution result (kết quả thực hiện kiểm tra thử nghiệm), the environment configuration (môi trường cấu hình), the issues while testing (vấn đề khi thử nghiệm)

**DLP (Data Loss Prevention)**
- Chống mất dữ liệu

**Time-based one-time password (TOTP)**
- Mật mã tạm thời, sử dụng một lần được tạo phù hợp với thời gian hiện tại bằng một thuật toán để xác thực người dùng.

**Ubuntu**
- Operation System developed from Linux

**Byte**
- 1 bit = 0 or 1
- 1 byte (B) = 8 bits
- 1 kilobyte (KB) = 1024 Bytes
- 1 megabyte (MB) = 1024 Bytes
- 1 Gigabyte (GB) = 1024 Bytes
- tera, peta, exa, zetta, yotta...

**Cách bấm dây mạng đúng kỹ thuật** (https://vienthongxanh.vn/cach-bam-day-mang-sao-cho-chuan-va-chinh-xac/)
- Chuẩn A (T568A) và Chuẩn B (T568B)
- T568A: 1. TRẮNG-XANH LÁ 2. XANH LÁ 3. TRẮNG-CAM 4. XANH DƯƠNG 5. TRẮNG XANH DƯƠNG 6. CAM 7. TRẮNG NÂU 8. NÂU
- T568B: 1. TRẮNG-CAM 2. CAM 3. TRẮNG XANH LÁ 4. XANH DƯƠNG 5. TRẮNG XANH DƯƠNG 6. XANH LÁ 7. TRẮNG NÂU 8. NÂU  

![image](https://github.com/user-attachments/assets/c94ed791-71df-4956-a6cc-ac8eeaaa9d8a)

**Cáp thẳng, cáp chéo** 
Đầu nối RJ45 CÓ 2 tiêu chuẩn: T568A và T568B
- Straight-Through Cable Pinout (Cáp thẳng)
  - Cả hai đầu có cùng kiểU bấm. 
  - được sử dụng rộng rãi hơn.
- Cross-over cable (Cáp chéo)
  - Khác kiểu bấm 



 **Tại sao lại có sự khác biệt giữa cáp thẳng và cáp chéo? Liệu cùng loại có sử dụng cáp thẳng được không? và khác loại thì dùng cáp chéo được không?**
 - Trong mạng Ethernet, các dây không chỉ truyền và còn nhận tín hiệu (TX - RX)
 - Thiết bị end point thì thường truyền dữ liệu qua chân 1, 2 và nhận dữ liệu ở chân 3, 6.
 - Lý do tại sao lại thường truyền qua chân 1, 2 vì: Quy ước của chuẩn Ethernet cho 10BASE-T và 100BASE-TX (2 cặp dây = 4 dây, vì để giảm chi phí sản xuất cáp, nhưng từ Gigabit = Ethernet thì toàn bộ 8 dây đều được sử dụng để tăng tốc độ truyền dữ liệu) 
 - Thiết bị trung gian thì thường truyền dữ liệu qua chân 3,6 và nhận dữ liệu ở chân 1, 2.
 - -> Khi kết nối 2 thiết bị giống nhau bằng cáp thẳng, thì dữ liệu sẽ giống như cố nói chuyện nhưng không bên nào nghe -> phải dùng cáp chéo (và ngược lại)
 - Nhưng hiện tại đã có AUTO-MDIX (tự động nhận diện loại kết nối và hoán đổi tín hiệu TX/RX nếu cần)
 - Hiện tại thường dùng chuẩn B, không dùng chuẩn A.

**Cách tạo ra địa chỉ MAC address**
- Nhà sản xuất hỏi IEEE để họ cho nhà sản xuất một mã 3 byte độc quyền. (OUI = Organizationally unique identifier) -> IEE đồng ý đưa mã -> nhà sản xuất còn + thêm 3 mã mà họ chưa bao giờ sử dụng
![image](https://github.com/user-attachments/assets/8be4fc16-2e69-4071-b01a-9e5aaf3dc1dd)

**EoMPLS**
- EoMPLS: Multiprotocol Label Switching: công nghệ cho phép truyền tải Ethernet qua mạng MPLS
  
- MPLS: định tuyến dựa trên nhãn (label) để tăng tốc độ truyền dữ liệu
  - giữ nguyên gói tin và dán nhãn cho chúng, chuyển tiếp nhanh mà không cần phân tích IP Header mỗi lần.
  - EoMPLS: Gói tin Ethernet được đóng gói và truyền qua mạng MPLS như thể nào?
  - Ethernet gốc sẽ được đóng gói lại, đi xuyên qua mạng MPLS như một ống (tunnel), và khi đến đích thì mở ra như cũ
  - Ethernet gốc sẽ được đóng thêm (Inner label - transport label) 

MPLS sẽ xử lý lớp 3 - đảm bảo rằng IP Packet sẽ được giữ nguyên
EoMPLS sẽ xử lý lớp 2 - đảm bảo rằng cả IP, cả MAC sẽ được giữ nguyên. 

**Dây sạc Tai xi 65w**

LÀM CÁCH địa chỉ IP LẠI TỚI ĐƯỢC SUBNET KHÁC?

LÀM CÁCH NÀO MÀ bit lại ra đời và làm sao người ta nghĩ ra được cách chia dữ liệu thành từng gói nhỏ?


bandwidth

Các loại dây + phần cứng cơ bản

mật khẩu tamper

gói thầu là gì? 

màn hình 60Hz, 24Hz

- chị Tâm và anh Chung làm endpoint (Zecurion, OPSWAT...) + làm việc với khách + hãng để biết trao đổi và cấu hình cho khách. Mình sẽ đóng vai trò trung gian. (như case endpoint mà hôm nọ mình tham gia)
- Anh Đại và anh Thắng làm bên quản lý Sophos Firewall.
- thế còn anh Hiếu cái gì cũng làm 
- Anh Trường bảo làm kỹ thuật phải biết đọc log để còn phân tích và xử lý lỗi.
- Mấy anh mặc vest nói tiếng anh (có anh Thái) thì là product management (làm việc với hãng
- Anh Tuấn Anh thì làm Presale rùi.
- Chị Nhật Anh là kế toán?
- 08.04: mình được nhìn chị Tâm và anh Thắng ký phiếu nghiệm thu của nhà thầu

- license là gì? tại sao phải mua? agent là cái khỉ gì?
- 2 mũ 2: 2 squared


 - classful network???
 - bandwidth testing method


 
 
