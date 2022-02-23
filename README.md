# Sales_Reporting_Analysis.

Báo cáo và phân tích dữ liệu bán hàng, trả lời các câu hỏi liên quan đến doanh thu doanh nghiệp.

# Question:
1. what was the best month for sales?
  How much was earned that month?
2. What city has the best sales?
3. What time should we display ads to maximize the likelihood of customer's buying product?
4. What products are most often sold together?
5. What product sold the most?
  Why do you think it sold the most?

# Data attributes - Thuộc tính của dữ liệu.
- Order ID - Mã giao dịch
- Product - Sản phẩm
- Quantity Orderd - Số lượng mua
- Price Each - Giá một đơn vị sản phẩm
- Order Date - Ngày mua hàng
- Purchase Address - Địa điểm cửa hàng

# Exploratory Data Analysis. 

- Phân tích dữ liệu khám phá ( EDA- Exploratory Data Analysis) là một tiếp cận: tóm
tắt các đặc điểm chính của dữ liệu.
- Là một phương pháp phân tích dữ liệu chủ yếu sử dụng các kỹ thuật về biểu đồ, hình vẽ.

    - Hiểu dữ liệu,
    - Lấy ngữ cảnh liên quan đến dữ liệu
    - Hiểu các biến và quan hệ giữa các biến
    - Hình thành các giải thuyết có thể hữu ích cho việc xây dựng các mô hình dự
    báo

Task 1: Set up enviroment and Load data
  - Install and import necessary packages
  - Display the table format of the dataset we wanted to explore
  
Task 2: Clean and Preprocess data
  - Clean data:
    - Remove unnecessary rows/column, fill-in or remove missing values
  - Data
    - Merging or Appending data to add more attributes or objects
    - Calculate new columns based on exsting atttributes
    
Task 3: Report
  - Report and Visualize what happend with the business through the data

# Libraries

pandas: - Đây là thư viện giúp xử lý dữ liệu dạng bảng.
        - Một bảng dữ liệu trong pandas được gọi là DataFrame.
        - Từng cột trong Pandas sẽ có tên gọi là Series.

Matplotlib: là một thư viện vẽ đồ thị rất mạnh mẽ hữu ích, cung cấp giao diện như MATLAB nhưng thay vào đó, nó sử dụng Python và nó là nguồn mở. 