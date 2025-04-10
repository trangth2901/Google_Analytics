# Google_Analytics_Big_Data

## Slide:
* https://www.canva.com/design/DAGZXmtmr2c/WgXVEmIiDYVh8z-d5my8OA/edit?ui=eyJEIjp7IlAiOnsiQiI6ZmFsc2V9fX0

## Mục tiêu kinh tế
* Dự đoán doanh thu của Google Merch Shop.
* Phân tích hành vi khách hàng. 
* Chăm sóc khách hàng mục tiêu

## Thành viên nhóm 
* A46350 Trần Huyền Trang
* A46483 Nguyễn Thị Thùy Trang
* A44314 Nguyễn Tuấn Anh

## Công nghệ sử dụng
* Ngôn ngữ lập trình: Python
* Mô hình: LightGBM

## Bộ dữ liệu sử dụng
Bộ dữ liệu "Google Analytics Customer Revenue Prediction" được cung cấp trong khuôn khổ cuộc thi trên Kaggle với mục đích dự đoán doanh thu của khách hàng dựa trên các dữ liệu hành vi của họ. Bộ dữ liệu bao gồm các thông tin về cách khách hàng tương tác với website Google Merch Shop. (https://www.kaggle.com/competitions/ga-customer-revenue-prediction/data).

## Kết quả và Đánh giá
Mô hình được đánh giá dựa trên chỉ số:
* RMSE ≈ 30$
* (Căn bậc hai của sai số bình phương trung bình. Đây là một thước đo phổ biến để đánh giá độ chính xác của mô hình dự đoán.)

## Kết luận
* Mô hình đang hoạt động ở mức độ khá tốt
* Kết hợp hai kĩ thuật mạnh mẽ:
* Label Encoding: giúp LightGBM dễ dàng tìm kiếm các mối quan hệ giữa các giá trị phân loại mà không phải thực hiện các phép toán phức tạp. 
* LightGBM: Xử lý nhanh chóng các dữ liệu lớn và có thể xử lý các đặc trưng phân loại hiệu quả. 
* Recall
* Precision
* F1-score
* Inference Time
* IoU (Intersection over Union) 
