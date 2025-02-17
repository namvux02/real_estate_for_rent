# Warehouse_for_rent
# Tổng quan
1. Tóm tắt
2. Dữ liệu 
3. Công cụ phân tích
4. Các bước thực hiện
5. Phân tích và báo cáo
6. Kết luận và khuyến nghị
7. Tài liệu tham khảo

# 1. Tóm tắt
Hỗ trợ cho việc đưa ra quyết định đầu tư vào thị trường bất động sản công nghiệp cho thuê ở Mỹ: bao gồm cho thuê nhà xưởng, nhà máy.
Tìm hiểu và nghiên cứu tình hình thị trường BĐS cho thuê tại thời điểm năm 2022. Đồng thời, ta biết được khoảng giá thuê ở mức bao nhiêu để phù hợp cho mục tiêu thu hút khách thuê và đảm bảo khoản đầu tư có thể sinh lời.

# 2. Dữ liệu
https://www.kaggle.com/datasets/snuzbrokh/warehouse-lease-data
- address: địa chỉ của kho
- buildingsize: kích thước của kho
- city: thành phố đặt kho
- listingdate: dữ liệu được xác minh vào ngày
- price: giá thuê
- proptype: lĩnh vực dùng cho kho
- spaceavailable: diện tích khoảng trống còn lại
- spaces: chỗ cho thuê còn lại
- state: bang
- subtype: kiểu kho
- utilities: tiện ích
- yearbuilt: năm xây
- yearRenovated: năm cải tạo
- propinfo: thông tin về kho
- ceilingheight: chiều cao trần
- lat, lon: tọa độ của kho trên bản đồ
- region: vùng
- division: miền nơi kho được xây
- spaceclass: phân loại cấp độ của kho 

# 3. Công cụ phân tích
- Python: xử lí và làm sạch dữ liệu
- Excel và PowerBI: trực quan hóa dữ liệu và tìm insight

# 4. Các bước thực hiện
- Thu thập và làm sạch dữ liệu: sử dụng dữ liệu trên kaggle và làm sạch dữ liệu bằng Python
- Trực quan hóa dữ liệu: sử dụng Excel và PowerBI để phân tích và tìm ra các insight từ dữ liệu
- Đưa ra kết luận và các khuyến nghị

# 5. Một vài phân tích và báo cáo
## Khu vực tiềm năng
![image](https://github.com/user-attachments/assets/2623270d-2536-4c14-bb01-6d8a8cb8140c)

GDP 2022 của 4 khu vực ở mức khá đồng đều, tuy nhiên khu vực South có sự nhỉnh hơn đôi chút so với các khu vực khác. Bên cạnh đó, khu vực phía Nam đang dần trở thành trung tâm Công Nghiệp của Mỹ và sẽ thu hút nhiều nhà đầu tư.

-> Đề xuất lựa chọn khu vực South để đầu tư

## Mật độ các kho tại cho thuê tại khu vực South ở từng bang
![image](https://github.com/user-attachments/assets/9f7cb743-cd0c-4b78-9dcf-9cf40062fbcb)

1. Số lượng bất động sản tập trung nhiều ở những bang có diện tích lớn như Texas, Florida, North Carolina. Các bang này đều là những bang có GDP cao ở Mỹ.

-> GDP cao cho thấy các bang này tập trung nhiều công ty và có nhiều tiềm năng để đầu tư, tuy nhiên do số lượng BĐS cao nên yếu tố cạnh tranh sẽ là lớn.

2. Xét về quy mô, số lượng kho nhỏ chiếm đa số ở các bang.

-> Tỷ trọng này phản ánh nhu cầu thực tế của thị trường đối với các kho có quy mô nhỏ. Các kho lớn và vừa chiếm tỷ trọng ít và chủ yếu đáp ứng nhu cầu lưu kho đối với một số loại hàng đặc thù cần diện tích lớn.
...

### Để biết thêm về các phân tích, hãy xem thêm tại đây: 
[Warehouse for rent - Final project.pdf](https://github.com/user-attachments/files/18827344/Warehouse.for.rent.-.Final.project.pdf)

# 6. Kết luận và kiến nghị
- Xem xét đầu tư ở các bang Tennessee, Virginia, Alabama, Mississippi, và tập trung ở phân khúc kho nhỏ (loại kho phổ biến). Tuy nhiên cần xét đến các yếu tố về điều kiện kinh tế, mức thu nhập, số lượng công ty ở các khu vực này ra quyết định.
- Giá cho thuê trung bình của kho nhỏ sẽ dao động trong khoảng từ 0.42 - 0.92.
- Loại kho lớn và trung bình, nếu đầu tư có thể sẽ tránh được cạnh tranh, tuy nhiên nếu nhu cầu thị trường không đáp ứng, cần xem xét đầu tư loại hình này.
- Đối với các bang khác:
1. Xem xét đầu tư ở các bang lớn do thị phần cạnh tranh cao. Có thể thay đổi mô hình của kho như làm kho lạnh, kho có hỗ trợ công nghệ quản lý kho thông minh
2. Cân nhắc mức giá để (i) đảm bảo tính cạnh tranh với các kho có cải tạo và đang có mức giá hấp dẫn và (ii) nằm trong kế hoạch ngân sách.
3. Mức giá thị trường BĐS ở các quy mô đều có xu hướng tăng theo năm xây dựng gần nhất. Ban Giám Đốc có thể tính toán để đưa ra mức giá phù hợp để cạnh tranh, thu hút khách hàng với tâm lý khách hàng sẽ thích mức giá tốt và chất lượng tòa nhà được đảm bảo.

# 7. Tài liệu tham khảo
- Dữ liệu GDP các bang của Mỹ trong năm 2022: https://en.wikipedia.org/wiki/List_of_U.S._states_and_territories_by_GDP
- Dữ liệu dân số Mỹ ở từng bang năm 2022: https://www.statsamerica.org/sip/rank_list.aspx?rank_label=pop1
- Tài liệu bổ sung cho đề xuất khu vực South: https://www.economist.com/united-states/2023/06/12/the-south-is-fast-becoming-americas-industrial-heartland




