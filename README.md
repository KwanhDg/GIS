# GIS
# Phân tích rủi ro ngập lụt đô thị TP. Hồ Chí Minh
Python GeoPandas Folium
# Tổng quan dự án
Dự án mô phỏng và đánh giá rủi ro ngập lụt cho 22 quận/huyện TP. Hồ Chí Minh dựa trên kịch bản nước dâng 2 m + vùng đệm 100 m quanh sông ngòi. Toàn bộ quy trình được thực hiện bằng Python + GIS, không cần phần mềm thương mại (ArcGIS/QGIS).
# Mục tiêu
Xác định % diện tích ngập và mức độ rủi ro (Cao / Trung bình / Thấp) từng quận
Tạo bản đồ tương tác hỗ trợ quy hoạch đô thị và ứng phó biến đổi khí hậu
## Cách chạy dự án
# 1. Tạo môi trường (khuyến nghị conda)
conda create -n flood_gis python=3.10
conda activate flood_gis
# 2. Cài đặt thư viện
pip install geopandas rasterio osmnx folium matplotlib numpy shapely
# 3. Mở và chạy lần lượt notebook
jupyter notebook ngap_lut_hcmc.ipynb

## Kết quả
<img width="1906" height="923" alt="image" src="https://github.com/user-attachments/assets/90c513d6-f20c-452c-83cb-2453d74925fc" />
