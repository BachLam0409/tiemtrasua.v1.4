# Trà sữa Tẹt Phượng (v27)

Game chạy thẳng trên trình duyệt, tối ưu cho Samsung (Android) và iPhone (kể cả 13 Pro Max).
Tất cả file nằm cùng một cấp, không cần thư mục.

## Danh sách file (tải lên cùng một chỗ, ở gốc repo)
- `index.html` : game
- `manifest.webmanifest` : để cài ra màn hình chính
- `sw.js` : chơi offline
- `icon-180.png`, `icon-192.png`, `icon-512.png`, `icon-512-maskable.png` : biểu tượng

## Đưa lên GitHub Pages
1. Tạo repo mới (Public) trên github.com.
2. Bấm **Add file → Upload files**, kéo thả toàn bộ file trên (không kéo thư mục), rồi **Commit changes**.
3. Vào **Settings → Pages → Build and deployment**: Source chọn **Deploy from a branch**, Branch chọn **main** và thư mục **/(root)**, bấm **Save**.
4. Đợi 1–2 phút, mở link `https://<tên-github>.github.io/<tên-repo>/` trên điện thoại.

## Cài ra màn hình chính
- **Samsung / Android (Chrome hoặc Samsung Internet):** bấm menu ⋮ → **Thêm vào màn hình chính** / **Cài đặt ứng dụng**.
- **iPhone (bắt buộc dùng Safari):** bấm nút **Chia sẻ** → **Thêm vào MH chính**.

## Lưu ý
- Tiến trình lưu trong trình duyệt của từng máy. Trên iPhone, Safari có thể xóa dữ liệu của trang web lâu không dùng, nên hãy cài ra màn hình chính và thỉnh thoảng vào tab **Sao lưu** để xuất file.
- Khi cập nhật game: ghi đè `index.html` và đổi `VERSION` trong `sw.js` (ví dụ `ttp-v27-2`) để điện thoại nhận bản mới.
- Chơi dọc màn hình. Nếu xoay ngang, game sẽ nhắc xoay lại.

## Có gì mới ở v27
- Vốn khởi điểm 520.000đ; ngày 1 có tối thiểu 25 khách, tăng dần theo ngày (tối đa gấp đôi sau khoảng 30 ngày).
- Tiền thuê ưu đãi 40.000đ/ngày trong 7 ngày đầu, 55.000đ trong 7 ngày kế, sau đó 70.000đ.
- Chống phá sản sớm: trong 10 ngày đầu, cuối ngày còn dưới 60.000đ thì gia đình cho mượn không lãi (tối đa 2 lần, trả dần 20 ngày).
- Ngày bán dài hơn khoảng 27%, hàng chờ thêm 1 chỗ, khách kiên nhẫn hơn những ngày đầu.
- Nhạc nền nhỏ hơn, hiệu ứng âm thanh rõ hơn trên loa điện thoại.
