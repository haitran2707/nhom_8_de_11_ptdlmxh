# Phân Tích Dữ Liệu Mạng Xã Hội của Facebook
# 📊 Five Step Facebook Report

Phân tích dữ liệu tương tác Facebook bằng Python với quy trình 5 bước:  
khám phá dữ liệu → làm sạch → phân tích nội dung → phân tích theo thời gian → dự đoán tương tác bằng Machine Learning.

---

# 🚀 Mục tiêu dự án

Notebook này giúp:

- Khám phá dữ liệu Facebook Page
- Làm sạch và chuẩn hóa dữ liệu
- Phân tích hiệu quả của từng loại nội dung
- Theo dõi xu hướng tương tác theo thời gian
- Trực quan hóa dữ liệu bằng biểu đồ
- Dự đoán mức độ tương tác bằng mô hình Random Forest

---

# 📂 Cấu trúc phân tích

## 🔹 Bước 0 — Khám phá dữ liệu

Kiểm tra:

- Kích thước dataset
- Danh sách cột
- Missing values
- Phân bố dữ liệu cơ bản

### Công thức sử dụng

\[
Mean = \frac{\sum x}{n}
\]

---

## 🔹 Bước 1 — Làm sạch dữ liệu

Thực hiện:

- Điền giá trị thiếu
- Chuẩn hóa kiểu datetime
- Loại bỏ dữ liệu trùng
- Tạo cột:

```python
Total_Engagement = Likes + Comments + Shares
```

---

## 🔹 Bước 2 — Phân tích hiệu quả nội dung

Phân tích 5 loại nội dung:

- Photo
- Video
- Status
- Link
- Live

### Công thức

```text
Engagement Rate = Total Interaction / Number of Posts
```

### Mục tiêu

- Xác định loại nội dung hiệu quả nhất
- So sánh mức độ tương tác trung bình

---

## 🔹 Bước 3 — Phân tích theo thời gian

- Gom nhóm theo tháng
- Theo dõi xu hướng tăng/giảm tương tác

### Công thức

```text
Growth Rate = (Current Month - Previous Month) / Previous Month × 100
```

---

## 🔹 Bước 4 — Trực quan hóa dữ liệu

Bao gồm các biểu đồ:

- Pie Chart
- Bar Chart
- Boxplot
- Time Series

### Thư viện sử dụng

- Matplotlib
- Seaborn
- mplcursors

---

## 🔹 Bước 5 — Dự đoán tương tác

Sử dụng mô hình:

```python
RandomForestRegressor
```

### Đánh giá bằng

- RMSE
- MAE
- R² Score

### Công thức

```text
RMSE = sqrt(mean((y - ŷ)^2))
MAE = mean(|y - ŷ|)
R² = 1 - SS_res / SS_tot
```

---

# 🛠️ Công nghệ sử dụng

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- mplcursors

---

# 📦 Cài đặt thư viện

```bash
pip install pandas numpy matplotlib seaborn scikit-learn mplcursors
```

---

# ▶️ Cách chạy project

## 1. Clone repository

```bash
git clone https://github.com/your-username/your-repo.git](https://github.com/haitran2707/nhom_8_de_11_ptdlmxh
```

## 2. Mở Jupyter Notebook

```bash
jupyter notebook
```

## 3. Chạy file notebook

```text
Five_Step_Facebook_Report.ipynb
```

---

# 📈 Kết quả đầu ra

Notebook tạo ra:

- Báo cáo phân tích Facebook
- Biểu đồ trực quan
- Dự đoán mức độ tương tác
- Đánh giá hiệu suất mô hình

---

# 📁 Dataset yêu cầu

Dataset cần chứa các cột như:

```text
Likes
Comments
Shares
Followers
Post Count
Photo Interactions
Video Interactions
Status Interactions
Link Interactions
Beginning Of Interval
```

---

# 🎯 Ứng dụng thực tế

Có thể dùng cho:

- Social Media Analytics
- Marketing Dashboard
- Facebook Content Strategy
- Machine Learning Practice
- Data Analysis Portfolio

---

# 👨‍💻 Tác giả

Trần Văn Huỳnh 
Trần Đỗ Minh Hải
