# mua-sam-thong-minh

Ứng dụng quản lý mua sắm thông minh - Smart Shopping Management

## Mô tả

Repository này lưu trữ thông tin các sản phẩm mua sắm từ các nền tảng thương mại điện tử.

## Dữ liệu

Thông tin mua sắm được lưu trong file `shopping-list.json` với cấu trúc:

- `id`: ID sản phẩm trong danh sách
- `product_name`: Tên sản phẩm
- `url`: Đường dẫn đến sản phẩm
- `platform`: Nền tảng (Shopee, Lazada, Tiki, ...)
- `shop_id`: ID cửa hàng
- `item_id`: ID sản phẩm trên nền tảng
- `category`: Danh mục sản phẩm
- `added_date`: Ngày thêm vào danh sách
- `status`: Trạng thái (saved, purchased, ...)