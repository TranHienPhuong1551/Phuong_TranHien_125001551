
# NHẬT KÝ PROMPT ENGINEERING (VIBE CODING LOG)

- **Họ và tên:** Trần Hiền Phương
- **MSSV:** [125001551]
- **Tên đề tài Website:** PC Gaming Store
- **Công cụ AI đã sử dụng:** ChatGPT

## 1. Yêu cầu ban đầu (System/Initial Prompt)

> Hãy xây dựng website giới thiệu và bán linh kiện máy tính,
> gaming gear bằng HTML, CSS và JavaScript.
> Website cần có giao diện hiện đại, tông màu đen và xanh lá,
> bố cục responsive, phù hợp với cửa hàng gaming.
> Sử dụng Semantic HTML5, CSS Variables, Flexbox hoặc Grid.
> Tích hợp Animate.css và AOS để tạo hiệu ứng chuyển động.
> Viết mã nguồn rõ ràng, chia thành các file riêng biệt.

## 2. Quá trình tinh chỉnh và giải quyết sự cố

### Lần 1: Dựng khung Semantic HTML và CSS Variables

- **Prompt đã dùng:**
  Hãy tạo cấu trúc HTML5 sử dụng header, nav, main,
  section, article và footer. Hạn chế sử dụng div
  không cần thiết. Khai báo CSS Variables trong :root
  để quản lý màu sắc, font chữ và khoảng cách.

- **Kết quả AI tạo ra:**
  Website có thanh điều hướng, phần giới thiệu, danh sách
  sản phẩm, dịch vụ, liên hệ và chân trang.

- **Nhận xét và tinh chỉnh của SV:**
  Kiểm tra ý nghĩa các thẻ HTML, bổ sung alt cho hình ảnh
  và chia nội dung thành các section rõ ràng.
  Sử dụng biến CSS để giao diện nhất quán hơn.

### Lần 2: Thiết kế giao diện bằng CSS

- **Prompt đã dùng:**
  Hãy thiết kế giao diện theo phong cách gaming hiện đại,
  sử dụng nền tối, màu xanh lá làm màu nhấn, CSS Grid
  cho danh sách sản phẩm và Flexbox cho thanh điều hướng.
  Bổ sung hiệu ứng hover, focus và responsive.

- **Kết quả AI tạo ra:**
  Giao diện có các thẻ sản phẩm, nút kêu gọi hành động,
  bố cục cân đối và màu sắc đồng bộ.

- **Nhận xét và tinh chỉnh của SV:**
  Điều chỉnh kích thước chữ, khoảng cách giữa các phần
  và bố cục trên màn hình nhỏ để dễ sử dụng hơn.

### Lần 3: Tích hợp Animate.css và AOS

- **Prompt đã dùng:**
  Hãy tích hợp Animate.css cho phần giới thiệu chính.
  Sử dụng AOS cho các thẻ dịch vụ và sản phẩm khi
  người dùng cuộn trang. Khởi tạo AOS bằng JavaScript.

- **Kết quả AI tạo ra:**
  Phần giới thiệu có hiệu ứng xuất hiện và các nội dung
  phía dưới có hiệu ứng khi cuộn trang.

- **Nhận xét và tinh chỉnh của SV:**
  Giới hạn thời gian hiệu ứng để tránh gây rối mắt.
  Thiết lập once: true để các phần tử không liên tục
  chạy lại hiệu ứng khi cuộn lên xuống.

### Lần 4: Kiểm tra và sửa lỗi

- **Prompt đã dùng:**
  Hãy kiểm tra website trên máy tính và điện thoại.
  Sửa lỗi menu trên điện thoại, kiểm tra đường dẫn CSS,
  JavaScript và cách khởi tạo AOS.

- **Kết quả AI tạo ra:**
  Bổ sung menu responsive, điều chỉnh bố cục trên màn
  hình nhỏ và hoàn thiện các hiệu ứng tương tác.

- **Thách thức gặp phải:**
  Nếu AOS không hoạt động, nguyên nhân có thể là thư viện
  chưa tải được, đường dẫn CDN lỗi hoặc thiếu AOS.init().
  Menu điện thoại cũng cần JavaScript để mở và đóng.

- **Cách sửa prompt (Debug prompt):**
  Kiểm tra thứ tự tải thư viện AOS và file script.js.
  Đảm bảo AOS.init() được gọi sau khi thư viện tải xong.
  Kiểm tra tên class active và các đường dẫn file.

## 3. Đánh giá cá nhân về quá trình Vibe Coding

- **AI đã giúp tiết kiệm thời gian ở phần nào nhất?**

  AI giúp tôi tạo nhanh cấu trúc HTML, bố cục CSS,
  thiết kế thẻ sản phẩm và tích hợp thư viện hiệu ứng.
  Nhờ đó, tôi có thêm thời gian kiểm tra và điều chỉnh
  giao diện theo yêu cầu đề bài.

- **Bài học rút ra khi đặt câu hỏi cho AI:**

  Tôi nhận thấy prompt cần nêu rõ mục tiêu, cấu trúc,
  công nghệ và kết quả mong muốn. Khi gặp lỗi, cần mô tả
  chính xác biểu hiện lỗi và yêu cầu AI kiểm tra từng phần.
  Sau khi nhận mã nguồn, sinh viên vẫn phải tự chạy thử,
  đọc mã và kiểm tra kết quả.
