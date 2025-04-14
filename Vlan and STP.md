**Material and topic**

**Chapter 8, chapter 9: VLAN và STP**
- Mạng LAN: VLAN, TRUNKING, DTP, VTP, STP
- Quản lý mạng: SNMP, NTP, NAT (static dynamic)
- Các giao thức mạng phổ biến ICMP, DHCP, HTTP/HTTPS, DNS, FTP, TCP/UDP

- Mạng LAN: VLAN, TRUNKING, DTP, VTP, STP (để sau cũng được)

**Chapter 8: Virtual LAN concepts**

LAN = ALL DEVICES IN THE SAME BROADCAST DOMAIN
- Tất cả các thiêt bị ở trong cùng 1 miền broadcast
- Vậy thì có nghĩa là: nếu sử dụng chế độ mặc định, thì một nhóc switch sẽ tự động hiểu rằng tất cả các cổng đều ở trong một miền broadcast. Để tạo ra 2 miền LAN broadcasr, chúng mình phải mua 2 cái switch riêng biệt

- ![image](https://github.com/user-attachments/assets/abdb9410-5c6d-4013-bca3-dc9d1300f739)

Nhưng mà bằng cách sử dụng 2 VLANs, 1 switch có thể hoàn thành nhiệm của của 2 switch. Với VLANs, một switch có thể cấu hình nhiều cổng vào một broadcast domain, tạo ra nhiều broadcast domain khác. Những broadcast domain đó gọi là "VIRTUAL LANS (VLAN)"

![image](https://github.com/user-attachments/assets/d69605de-5a2a-4e50-899f-3207084af675)

Trong hình 8.2, thì cô nhóc switch tạo ra 2 mạng LANs, bằng cách chia mỗi cổng trong switch thành những lối đến riêng biệt. 

OKE, vậy tại sao phải chia ra thành VLANs làm gì cho rắc rối?
- giảm CPU overhead (gánh nặng CPU) của mỗi thiết bị, làm tăng công suất của host, giảm số lượng thiết bị mà phải nhận khung broadcast
- giảm những rủi ro bảo mật bằng cách giảm số lượng host mà nhận copies frame
- cải thiện bảo mật cho máy chủ qua cái policy khác nhau trên mỗi VLAN
- tạo thêm nhiều cái thiết kế theo nhóm đa dạng theo từng phòng ban, nhóm
- giải quyết vấn đề nhanh hơn, bởi vì cái domain thất bại (k hiểu)
- giảm khối lượng công việc của STP (Spanning Tree Protocol) = giới hạn VLAN tới những kết nối LAN đơn.

Tạo ra Multiswitch VLANs với Trunking (đường truyền thân - cho phép nhiều VLAN truyền trên 1 liên kết vật lý giữa các thiết bị mạng như switch)
- Cấu hình VLANs trên 1 switch: cấu hình mỗi cổng để bảo VLAN number thuộc về cổng nào. Nhưng mà nếu có nhiều switches quá, thì phải xem thêm khái niệm về forward traffic giữa các switches. 
- sử dụng VLANs trong mạng mà có nhiều switch kết nối -> dùng VLAN trunking giữa các link -> sử dụng VLAN tagging (có nghĩa là cái switch sẽ thêm một header khác vào frame trước khi gửi tới trunk)
- cái đầu này là VLAN IDENTIFIER (VLAN ID).

![image](https://github.com/user-attachments/assets/382f922b-2574-42bd-805a-cd5f0ff76ba9)

Trong hình 8-3, có hai link nối giữa 2 switches, nhưng mà nếu cần tới 10-20 VLANs, thì cần 10-20 dây nối giữa các switch, và cần 10-20 cổng switch cho dây nối này. 

**VLAN TRUNKKING CONCEPTS**
- Tạo ra 1 liên kết giữa các thiết bị chuyển mạch mà hỗ trợ càng nhiều VLANs càng tốt
- 









