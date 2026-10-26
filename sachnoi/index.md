---
title: Chính sách quyền riêng tư – Sách Nói Hay
---

# Chính sách quyền riêng tư của ứng dụng Sách Nói Hay

*Có hiệu lực từ ngày 27/10/2026.* [English version below](#privacy-policy-english).

Chính sách này giải thích ứng dụng Android **Sách Nói Hay** (mã ứng dụng `com.hadoso.sachnoi`)
do **HaDoSolution** phát triển (sau đây gọi là "chúng tôi") thu thập, sử dụng và chia sẻ dữ liệu
nào khi bạn dùng ứng dụng. Chính sách chỉ áp dụng cho ứng dụng này.

## 1. Tóm tắt

- Ứng dụng **không có tài khoản** và **không hỏi** tên, email hay số điện thoại của bạn.
- Lịch sử nghe, chỗ đang nghe dở, dấu trang và tốc độ phát **chỉ lưu trên máy của bạn**.
- Ứng dụng **có quảng cáo** do Start.io cung cấp. Start.io và Google Firebase thu một số dữ liệu
  thiết bị, như mã quảng cáo (Advertising ID), như mô tả ở mục 4.
- Chúng tôi **không bán** dữ liệu của bạn.

## 2. Dữ liệu lưu trên máy của bạn

Những dữ liệu sau được lưu trong bộ nhớ của ứng dụng trên máy bạn, **không gửi về máy chủ của
chúng tôi**:

- Danh sách sách đã nghe gần đây, chương và vị trí đang nghe dở, phần trăm đã nghe.
- Dấu trang và ghi chú bạn tự viết cho dấu trang.
- Tốc độ phát và các lựa chọn trong màn Cài đặt.
- Bản lưu danh mục và danh sách sách, để mở ứng dụng nhanh hơn.
- Mã truy cập (token) dùng để gọi máy chủ của ứng dụng.

Nếu bạn bật sao lưu của Android, hệ điều hành có thể đưa các dữ liệu trên (trừ mã truy cập) vào
bản sao lưu trong tài khoản Google của chính bạn. Gỡ ứng dụng hoặc chọn "Xoá dữ liệu" trong phần
cài đặt ứng dụng của Android sẽ xoá toàn bộ dữ liệu này.

## 3. Dữ liệu gửi tới máy chủ của chúng tôi

Để hiển thị và phát sách, ứng dụng kết nối tới máy chủ `api.code2smile.com` và máy chủ phát âm
thanh `static.code2smile.com` (đi qua mạng Cloudflare). Các yêu cầu này gồm:

- **Nội dung bạn xem:** danh mục, danh sách sách, chi tiết sách và các chương bạn mở.
- **Từ khoá tìm kiếm** bạn nhập vào ô tìm kiếm.
- **Yêu cầu sách mới:** tên sách, tác giả và người đọc mà bạn điền vào form "Yêu cầu sách mới".
  Form này không hỏi thông tin cá nhân.

Như mọi kết nối Internet, máy chủ nhận được **địa chỉ IP** của bạn và ghi nhật ký truy cập (thời
gian, đường dẫn, địa chỉ IP) để vận hành, chống lạm dụng và xử lý sự cố. Nhật ký chỉ được giữ
trong thời gian ngắn. Ứng dụng không gửi kèm tên, email hay danh bạ của bạn.

Mọi kết nối tới máy chủ đều được mã hoá bằng HTTPS. Đường dẫn âm thanh có chữ ký và hết hạn sau
một thời gian ngắn.

## 4. Dịch vụ của bên thứ ba

### 4.1. Quảng cáo: Start.io

Ứng dụng hiển thị quảng cáo banner và quảng cáo toàn màn hình của **Start.io**. Để chọn và đo
lường quảng cáo, thư viện Start.io có thể thu:

- Mã quảng cáo Android (Advertising ID), khi có.
- Địa chỉ IP và vị trí gần đúng suy ra từ địa chỉ IP. Ứng dụng **không xin quyền vị trí**, nên
  không có vị trí chính xác.
- Thông tin thiết bị (hãng, model, phiên bản Android, ngôn ngữ, nhà mạng) và tương tác với quảng
  cáo (lượt hiển thị, lượt bấm).
- Dữ liệu hiệu năng của thư viện, để Start.io sửa lỗi.

Ở những nơi pháp luật yêu cầu (ví dụ Liên minh châu Âu), Start.io hiện hộp thoại để bạn đồng ý
hoặc từ chối quảng cáo cá nhân hoá. Ứng dụng không tự đồng ý thay bạn. Cách Start.io xử lý dữ
liệu được mô tả trong [chính sách quyền riêng tư của Start.io](https://www.start.io/policy/privacy-policy/).

### 4.2. Phân tích và báo lỗi: Google Firebase

- **Firebase Analytics** thu mã phiên bản cài đặt (app-instance ID), mã quảng cáo Android, vị
  trí gần đúng suy ra từ IP và các sự kiện sử dụng (mở ứng dụng, màn hình đã xem, phiên dùng).
  Chúng tôi dùng chúng để biết tính năng nào được dùng và cải thiện ứng dụng.
- **Firebase Crashlytics** thu thông tin khi ứng dụng bị lỗi: nội dung lỗi, trạng thái ứng dụng
  lúc lỗi, thông tin thiết bị và một mã cài đặt ngẫu nhiên. Chúng tôi dùng chúng để sửa lỗi.

Google xử lý dữ liệu này theo [chính sách quyền riêng tư của Google](https://policies.google.com/privacy)
và [điều khoản về dữ liệu của Firebase](https://firebase.google.com/support/privacy).

## 5. Góp ý qua email

Khi bạn chọn "Góp ý" trong ứng dụng, ứng dụng mở ứng dụng email trên máy bạn và điền sẵn phiên
bản Android, phiên bản ứng dụng, hãng và model máy, để chúng tôi hỗ trợ dễ hơn. Bạn có thể xem và
xoá các thông tin này trước khi gửi. Email chỉ được gửi khi bạn bấm gửi. Chúng tôi dùng email đó
để trả lời bạn và không dùng vào mục đích khác.

## 6. Quyền trên thiết bị

| Quyền | Dùng để |
|---|---|
| Internet, trạng thái mạng | Tải danh sách sách và phát âm thanh |
| Thông báo, dịch vụ nền phát nhạc, giữ máy thức | Điều khiển phát từ thanh thông báo và tiếp tục phát khi tắt màn hình |
| Mã quảng cáo (`AD_ID`) và các quyền quảng cáo của Android | Quảng cáo và phân tích, như mục 4 |
| Chạy khi khởi động máy | Thư viện quảng cáo Start.io dùng để cập nhật cấu hình |

Ứng dụng không xin quyền vị trí, danh bạ, micro, máy ảnh hay quyền đọc ảnh và tệp trên máy.

## 7. Chia sẻ dữ liệu

- Chúng tôi **không bán** dữ liệu cá nhân.
- Dữ liệu chỉ được chia sẻ với các bên ở mục 4, đúng mục đích đã nêu.
- Chúng tôi có thể cung cấp dữ liệu khi cơ quan nhà nước có thẩm quyền yêu cầu theo quy định
  pháp luật.

## 8. Lựa chọn của bạn

- **Đặt lại hoặc xoá mã quảng cáo:** vào Cài đặt Android > Google > Quảng cáo (tên mục có thể
  khác tuỳ máy). Sau khi xoá, quảng cáo không còn được cá nhân hoá theo mã đó.
- **Xoá dữ liệu trên máy:** gỡ ứng dụng hoặc chọn "Xoá dữ liệu" trong phần cài đặt ứng dụng.
- **Yêu cầu khác về dữ liệu:** gửi email tới địa chỉ ở mục 11. Với dữ liệu do Start.io thu, bạn
  cũng có thể liên hệ trực tiếp Start.io qua support@start.io.

## 9. Trẻ em

Ứng dụng không dành cho trẻ em dưới 13 tuổi, và chúng tôi không cố ý thu dữ liệu của trẻ em. Nếu
bạn biết một trẻ em đã cung cấp dữ liệu cho chúng tôi, hãy liên hệ để chúng tôi xoá.

## 10. Thay đổi chính sách

Khi chính sách thay đổi, chúng tôi cập nhật trang này và ngày hiệu lực ở đầu trang. Những thay đổi
quan trọng sẽ được thông báo trong ghi chú phát hành của ứng dụng.

## 11. Liên hệ

HaDoSolution, email: **hadosolution@gmail.com**

---

<a id="privacy-policy-english"></a>

# Privacy Policy – Sách Nói Hay (English)

*Effective 27 October 2026.* This policy covers the Android app **Sách Nói Hay**
(`com.hadoso.sachnoi`), developed by **HaDoSolution**. This summary follows the Vietnamese
version above, which prevails if they differ.

- **No account.** The app does not ask for your name, email or phone number.
- **Kept on your device only:** listening history, playback position, bookmarks and notes,
  playback speed, settings, a cached catalogue, and an API access token. Android backup may
  include these (except the token) in your own Google account backup. Uninstalling or clearing
  the app's data removes them.
- **Sent to our servers** (`api.code2smile.com`, `static.code2smile.com` via Cloudflare, over
  HTTPS): what you browse and play, search terms, and book requests (title, author, narrator).
  Servers receive your IP address and keep short-lived access logs for operation and abuse
  prevention.
- **Advertising – Start.io:** banner and full-screen ads. The Start.io SDK may collect the Android
  Advertising ID, IP address and coarse location derived from it (the app requests no location
  permission), device information, ad interactions and SDK diagnostics. Where required by law,
  Start.io asks for your consent to personalised ads; the app never consents on your behalf. See
  the [Start.io privacy policy](https://www.start.io/policy/privacy-policy/).
- **Analytics and crash reporting – Google Firebase:** Analytics collects an app-instance ID,
  the Advertising ID, coarse location from IP and usage events; Crashlytics collects crash
  traces, app state, device information and a random installation ID. See the
  [Google Privacy Policy](https://policies.google.com/privacy).
- **Feedback email:** the app pre-fills your Android version, app version and device model in
  your own email app; you can edit it before sending.
- **We do not sell personal data.** Data is shared only with the providers above for the stated
  purposes, or when required by law.
- **Your choices:** reset or delete your Advertising ID in Android settings; clear the app's data;
  email us for other requests, or contact Start.io at support@start.io.
- **Children:** the app is not directed to children under 13.
- **Contact:** HaDoSolution, hadosolution@gmail.com
