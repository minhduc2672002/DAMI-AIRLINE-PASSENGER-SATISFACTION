# KHAI PHÁ DỮ LIỆU VỀ SỰ HÀI LÒNG CỦA HÀNH KHÁCH TRONG CHUYẾN BAY
## Sơ lược tập dữ liệu
Dữ liệu này do một tổ chức hàng không đưa ra. Tên thực tế của công ty không được đưa ra do nhiều mục đích khác nhau, đó là lý do tại sao có tên hãng hàng không không bị tiết lộ.
Tập dữ liệu bao gồm thông tin chi tiết về những khách hàng đã bay với họ. Phản hồi của khách hàng về các bối cảnh khác nhau và dữ liệu chuyến bay của họ đã được tổng hợp.
Mục đích chính của tập dữ liệu này là dự đoán liệu một khách hàng trong tương lai có hài lòng với dịch vụ của họ hay không khi cung cấp thông tin chi tiết về các giá trị tham số khác.
Ngoài ra, các hãng hàng không cũng cần biết khía cạnh nào của các dịch vụ do họ cung cấp phải được nhấn mạnh nhiều hơn để tạo ra nhiều khách hàng hài lòng hơn.
Gồm 129880 dòng  và 23 cột
- Gender: Giới tính của hành khách (Nữ, Nam)
- Customer_type: Loại khách hàng (Khách hàng trung thành, khách hàng không trung thành)
- Age: Tuổi thực của hành khách
- Type_of_travel: Mục đích chuyến bay của hành khách (Đi du lịch cá nhân, Đi công tác)
- Customer_class: Hạng du lịch trên máy bay của hành khách (hạng Thương gia, hạng Eco, hạng Eco Plus)
- Flight_distance: Khoảng cách bay của hành trình này
- Inflight_wifi_service: Mức độ hài lòng đối với dịch vụ wifi trên chuyến bay (0: Không áp dụng; 1-5)
- Departure_arrival_time_convenient: Mức độ hài lòng về Thời gian đi / đến thuận tiện
- Ease_of_online_booking: Mức độ hài lòng khi đặt phòng trực tuyến
- Gate_location: Mức độ hài lòng về vị trí cổng
- Food_and_drink: Mức độ hài lòng về Đồ ăn và thức uống
- Online_boarding: Mức độ hài lòng của nội trú trực tuyến
- Seat_comfort: Mức độ hài lòng về sự thoải mái của chỗ ngồi
- Inflight_entertainment: Mức độ hài lòng của giải trí trên chuyến bay
- Onboard_service: Mức độ hài lòng của dịch vụ trên chuyến bay
- Leg_room_service: Mức độ hài lòng của dịch vụ phòng chân
- Baggage_handling: Mức độ hài lòng của việc xếp dỡ hành lý
- Checkin_service: Mức độ hài lòng về dịch vụ nhận phòng
- Inflight_service: Mức độ hài lòng của dịch vụ trên chuyến bay
- Cleanliness: Mức độ hài lòng về Sạch sẽ
- Departure_delay_in_minutes: Bị hoãn vài phút khi khởi hành
- Arrival_delay_in_minutes: Bị Chậm Phút Khi Đến
- Satisfaction: Mức độ hài lòng của hãng hàng không (Hài lòng, trung tính hoặc không hài lòng)

## Trực quan hóa dữ liệu
Hài Lòng tổng quát


![360069485_619553773615878_1619825348283326697_n](https://github.com/minhduc2672002/DAMI-AIRLINE-PASSENGER-SATISFACTION/assets/133132824/2b3bb2eb-7515-44e8-9006-acf1370e4e14)


Ở các dịch vụ


![360612257_951352899504631_6463880016881468354_n](https://github.com/minhduc2672002/DAMI-AIRLINE-PASSENGER-SATISFACTION/assets/133132824/4d816327-3184-4b81-85ae-5f6416d7d48b)


Theo giới tính


![360190058_265464442751062_1164262809065245570_n](https://github.com/minhduc2672002/DAMI-AIRLINE-PASSENGER-SATISFACTION/assets/133132824/9067dfbc-5814-46f7-b789-c2660961be7d)


Suốt chuyến bay

![360271635_825685839023134_3624614955438116314_n](https://github.com/minhduc2672002/DAMI-AIRLINE-PASSENGER-SATISFACTION/assets/133132824/dd381adb-16c2-4bf0-8e1f-92bff53a035b)

Theo độ trễ

![361065009_232661645781234_6667782704338562116_n](https://github.com/minhduc2672002/DAMI-AIRLINE-PASSENGER-SATISFACTION/assets/133132824/8593f745-5809-437f-b2cf-c7b34bd4b69f)

## Khai phá dữ liệu sử dung Weka
* Sử dụng thuật toán cây quyết định J48
* Sử dụng thuật toán phân cụm K-mean
* Sử dụng luật kết hợp
  *Chi tiết xem ở file Report. Xin cảm ơn đã xem!*
