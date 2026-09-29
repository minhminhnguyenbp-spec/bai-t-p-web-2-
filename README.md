# PhoneZone — Bản đầy đủ chức năng giao diện

Website tĩnh bằng **HTML5 + CSS3**, không sử dụng JavaScript/backend.  
Bản này giữ bộ 8 trang chính trước đó và **bổ sung 3 trang chức năng** (`account.html`, `cart.html`, `orders.html`) lấy ý tưởng từ bộ file tham khảo người dùng cung cấp.

## Cấu trúc

- `index.html` — Trang chủ, Hero/Banner, trust strip, danh mục, sản phẩm nổi bật
- `products.html` — 8 sản phẩm, bộ lọc/sắp xếp mô phỏng, mobile filter
- `categories.html` — Danh mục theo thương hiệu và nhu cầu
- `promotions.html` — Khuyến mãi và quy trình nhận ưu đãi
- `details.html` — Chi tiết 8 sản phẩm, gallery, dung lượng, số lượng, thêm giỏ
- `blog.html` — Tin tức / tư vấn có ghi nguồn
- `about.html` — Giới thiệu
- `contact.html` — Trung tâm hỗ trợ + form
- `account.html` — Đăng nhập / đăng ký mô phỏng
- `cart.html` — Giỏ hàng mô phỏng
- `orders.html` — Theo dõi đơn hàng mô phỏng
- `style.css` — CSS chung + Responsive
- `images/` — Logo, banner và ảnh dự phòng cục bộ
- `README.md`

> Yêu cầu đề bài là **ít nhất 08 trang HTML**, nên việc có 11 trang vẫn đúng yêu cầu.

## Chức năng giao diện đã tích hợp

- Header + logo
- Navigation liên kết giữa các trang
- Thanh tìm kiếm có chọn danh mục
- Tài khoản / Đơn hàng / Giỏ hàng
- Hero/Banner
- Trust strip
- Section / Grid / Card / Button / Footer
- Danh mục theo hãng và nhu cầu
- Bộ lọc sản phẩm, sắp xếp, mobile filter (mô phỏng)
- Thẻ sản phẩm có đánh giá, giá cũ, giá mới, giao hàng, thêm giỏ
- Chi tiết sản phẩm có gallery, chọn dung lượng, số lượng, thêm giỏ
- Khuyến mãi
- Giỏ hàng
- Theo dõi đơn hàng
- Form đăng nhập / đăng ký
- Form liên hệ
- Breadcrumb
- Ghi nguồn ảnh / thông tin tham khảo
- Responsive Desktop / Tablet / Mobile

## Lưu ý

Do yêu cầu kỹ thuật chỉ dùng HTML5 và CSS3:
- tìm kiếm,
- lọc/sắp xếp,
- đăng nhập/đăng ký,
- giỏ hàng,
- đặt hàng

được **mô phỏng giao diện**, không có xử lý dữ liệu thật.

## Nguồn thông tin và hình ảnh sản phẩm

1. iPhone 16 Pro Max — Apple Support  
   https://support.apple.com/vi-vn/121032

2. Samsung Galaxy S25 Ultra — Samsung  
   https://www.samsung.com/vn/smartphones/galaxy-s25-ultra/

3. Xiaomi 15 — Xiaomi  
   https://www.mi.com/vn/product/xiaomi-15/specs/

4. OPPO Find X8 Pro — OPPO  
   https://www.oppo.com/vn/smartphones/series-find-x/find-x8-pro/specs/

5. Vivo V50 — vivo  
   https://www.vivo.com/en/products/picture/v50

6. Realme 14 Pro 5G — realme  
   https://www.realme.com/global/realme-14-pro-5g/specs

7. HONOR 400 — HONOR  
   https://www.honor.com/vn/phones/honor-400/

8. iPhone 16 — Apple Support  
   https://support.apple.com/vi-vn/121029

## Nguồn bài viết

- Vietnamnet Công nghệ: https://vietnamnet.vn/cong-nghe
- Sforum: https://cellphones.com.vn/sforum
- Sforum Tin công nghệ: https://cellphones.com.vn/sforum/tin-cong-nghe

## Responsive

- Desktop: nhiều cột, sidebar lọc.
- Tablet: grid giảm số cột, chi tiết sản phẩm chuyển 1 cột.
- Mobile: 1 cột, filter desktop ẩn và dùng khối lọc mobile, Header/Nav thu gọn, ảnh dùng `object-fit` để không méo.

## GitHub Pages

Đưa toàn bộ file và thư mục `images/` lên root repository.  
Đảm bảo `index.html` nằm ở cấp ngoài cùng, sau đó vào:

`Settings → Pages → Deploy from a branch → main / root`


> Ảnh hiển thị ở các khu vực sản phẩm được lấy trực tiếp từ các trang/chủ thể chính thức của Apple, Samsung, Xiaomi, OPPO, vivo, realme và HONOR; thư mục `images/` vẫn được giữ nguyên để không thay đổi cấu trúc dự án.
