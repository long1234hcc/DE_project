# Tên dự án: Dự án chatbot hỏi đáp cơ sở dữ liệu bán hàng
## Mục đích dự án: Tự động trả ra các kết quả thống kê về cơ sở dữ liệu bán hàng ngày (Sản phẩm nào bán chạy hôm nay?, Doanh số hàng ngày?,....)
## Mô tả dự án: 
1. Crawl data các dữ liệu của website ecom
2. Lưu trữ các file tại DataLake (Minio S3)
3. Chuyển đổi dữ liệu và đưa vào DataWarehouse (MySQL)
4. Xây dựng chatbot bằng Langchain và Google API key (Gemini-flask-1.5)
5. Query cơ sở dữ liệu để trả ra các kết quả thống kê

## Các bước vận hành dự án
1. Cài MySQL, MinioS3, Airflow bằng docker
2. Viết file docker-compose.yaml
3. Chạy airflow trên port localhost:8080
4. Đưa dự án vào folder dags trong folder chứa airflow
5. Quản lý dự án và chạy tự động trên giao diện của airflow


## Mở rộng dự án
Xây dựng tự động báo cáo bằng Power BI hoặc Tableu để lên báo cáo tự động hàng ngày

