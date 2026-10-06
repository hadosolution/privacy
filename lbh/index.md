*Bản tiếng Việt trước, bản tiếng Anh ngay sau — English version below.*

# Chính sách quyền riêng tư của Lời Bài Hát

Có hiệu lực từ 06/10/2026. Cập nhật lần cuối ngày 06/10/2026.

Lời Bài Hát là ứng dụng tra cứu lời bài hát Việt Nam xem được khi không có mạng, do
**HaDoSolution** phát hành trên Google Play. Chính sách này nói rõ app lưu gì trên máy bạn, gửi gì
ra ngoài, gửi cho ai, và bạn thay đổi điều đó bằng cách nào.

## Tóm tắt

- App **không có tài khoản** và không bao giờ hỏi tên, email, số điện thoại hay bất kỳ thông tin
  nào để nhận ra bạn.
- Bài yêu thích, lịch sử tìm kiếm và cài đặt **nằm trên máy bạn**. Chúng tôi không có bản sao nào.
- App hiện **quảng cáo** của Google AdMob, gửi **số liệu sử dụng** cho Google Analytics for
  Firebase và **báo cáo sự cố** cho Firebase Crashlytics.
- Khi bạn **gửi yêu cầu bài hát**, nội dung bạn gõ được gửi về máy chủ của chúng tôi (mục 5).
- Chúng tôi **không bán** dữ liệu của bạn cho ai.

## 1. Dữ liệu lưu trên máy bạn

App lưu trong bộ nhớ riêng của nó trên máy:

- bộ lời bài hát đi kèm app;
- bài bạn đánh dấu yêu thích và các bài bạn đã xem;
- các từ khoá bạn đã tìm;
- cài đặt: cỡ chữ, số bài hiển thị, hiện hay ẩn nút yêu cầu bài hát.

Những dữ liệu này không được gửi cho chúng tôi. Muốn xoá hết, hãy gỡ app hoặc vào *Cài đặt Android →
Ứng dụng → Lời Bài Hát → Bộ nhớ → Xoá dữ liệu*.

**Sao lưu ra thẻ nhớ.** Nếu bạn bấm *Sao lưu* trong màn Cài đặt, app ghi danh sách bài yêu thích
ra một tệp ở thư mục gốc của bộ nhớ chung. Tệp này nằm ngoài bộ nhớ riêng của app, nên ứng dụng khác
có quyền đọc bộ nhớ cũng đọc được nó; nó chỉ chứa danh sách bài, không có gì về bạn. Từ Android 10
trở đi, Android không cho app ghi vào đó nữa, nên mục này không còn tạo ra tệp nào.

## 2. Quảng cáo — Google AdMob

App hiện một dải quảng cáo ở cuối danh sách bài và màn xem lời, và một quảng cáo toàn màn hình
trước khi mở màn *Yêu cầu bài hát*. Để hiện và đo quảng cáo, SDK Google Mobile Ads **tự thu thập**
và gửi cho Google:

- địa chỉ IP, có thể dùng để ước đoán vị trí chung (quốc gia, thành phố);
- mã quảng cáo Android (Advertising ID) và mã App set ID;
- tương tác với app và với quảng cáo: mở app, chạm, lượt xem quảng cáo;
- thông tin chẩn đoán về hiệu năng của app và của SDK.

Google dùng các dữ liệu này để hiện quảng cáo, đo hiệu quả quảng cáo và chống gian lận. Cách Google
xử lý chúng nằm ở [Cách Google sử dụng thông tin từ các trang web hoặc ứng dụng sử dụng dịch vụ của
Google](https://policies.google.com/technologies/partner-sites).

**Bạn có thể** đặt lại hoặc xoá mã quảng cáo ở *Cài đặt Android → Google → Quảng cáo* (tên mục khác
nhau đôi chút giữa các máy); khi mã quảng cáo bị xoá, quảng cáo không còn được cá nhân hoá theo mã
đó. Phiên bản hiện tại của app chưa có biểu mẫu xin đồng ý dành cho người dùng ở Khu vực Kinh tế
Châu Âu, Vương quốc Anh và Thuỵ Sĩ; nếu bạn ở đó, cách trên là cách để tắt quảng cáo cá nhân hoá.

## 3. Số liệu sử dụng — Google Analytics for Firebase

Để biết app được dùng thế nào, SDK Google Analytics for Firebase tự gửi cho Google:

- mã cài đặt ngẫu nhiên (app-instance ID) mà Firebase tự tạo cho mỗi lần cài, và mã quảng cáo
  Android;
- vị trí gần đúng, do Google suy ra từ địa chỉ IP;
- các sự kiện tự động: lần đầu mở app, phiên sử dụng, màn hình đã mở, cập nhật app.

App không gửi thêm sự kiện riêng nào: không có tên bài bạn xem hay từ khoá bạn tìm. Các sự kiện này
không chứa tên, email hay bất cứ thứ gì nhận ra bạn. Chúng tôi chỉ xem chúng ở dạng
tổng hợp.

## 4. Báo cáo sự cố — Firebase Crashlytics

Khi app gặp lỗi và bị đóng đột ngột, SDK Firebase Crashlytics gửi cho Google một báo cáo sự cố để
chúng tôi tìm và sửa lỗi ấy. Báo cáo gồm:

- dấu vết lỗi (stack trace): đoạn code nào đang chạy lúc lỗi xảy ra;
- thông tin thiết bị: hãng và đời máy, phiên bản Android, bộ nhớ và dung lượng còn trống, hướng
  màn hình, máy đã root hay chưa;
- một mã cài đặt ngẫu nhiên mà Crashlytics tạo cho mỗi lần cài, để đếm bao nhiêu máy gặp cùng một
  lỗi.

Báo cáo không chứa bài yêu thích, từ khoá tìm kiếm hay bất cứ thứ gì bạn gõ.

## 5. Yêu cầu bài hát và góp ý

**Yêu cầu bài hát.** Khi bạn bấm *Gửi* ở màn Yêu cầu bài hát, app gửi về máy chủ của HaDoSolution
đúng những gì bạn điền — tên bài, tác giả, ca sĩ, ghi chú — cùng tên app, qua kết nối mã
hoá HTTPS. Máy chủ nhận thêm địa chỉ IP của bạn như mọi kết nối Internet. Chúng tôi dùng yêu cầu chỉ
để chọn bài bổ sung vào app, và không gắn nó với người nào. Đừng ghi thông tin cá nhân vào ô ghi chú.

**Góp ý qua email.** Mục góp ý mở ứng dụng email của bạn. Khi bạn gửi, chúng tôi nhận được địa chỉ
email và nội dung thư, và chỉ dùng chúng để trả lời bạn.

## 6. Chia sẻ dữ liệu

Dữ liệu ở mục 2, 3 và 4 đi tới Google, bên cung cấp các dịch vụ ấy; với quảng cáo, Google có thể
chia sẻ tiếp dữ liệu ở mục 2 theo chính sách của Google đã dẫn ở đó. Yêu cầu bài hát và thư góp ý
chỉ tới chúng tôi. Chúng tôi không gửi dữ liệu của bạn cho ai khác và không bán nó.

## 7. Quyền trên máy

App xin quyền truy cập Internet và trạng thái mạng (để hiện quảng cáo và gửi yêu cầu bài hát), quyền
rung (khi nhấn giữ một bài để lưu yêu thích), và quyền đọc và ghi bộ nhớ chung (cho mục sao lưu ở mục 1).
Bản cài đặt còn khai quyền đọc trạng thái điện thoại từ các phiên bản cũ; app **không** đọc số điện
thoại, mã IMEI hay danh bạ của bạn.

## 8. Bảo mật

Mọi dữ liệu mà các SDK của Google gửi đi, và mọi yêu cầu bài hát, đều được mã hoá trên đường truyền.

## 9. Trẻ em

Lời Bài Hát không nhắm tới trẻ em dưới 13 tuổi. Chúng tôi không cố ý thu thập dữ liệu của trẻ dưới
13 tuổi.

## 10. Quyền của bạn

Vì app không có tài khoản, chúng tôi không có cách nào gắn dữ liệu ở mục 2, 3 và 4 với một người
cụ thể, nên cũng không tra ra được dữ liệu của riêng bạn để xoá theo yêu cầu. Bạn vẫn kiểm soát
được: xoá dữ liệu trên máy (mục 1) và đặt lại mã quảng cáo (mục 2). Muốn xoá một yêu cầu bài hát hay
thư góp ý đã gửi, hoặc có câu hỏi khác, hãy viết cho chúng tôi theo địa chỉ ở mục 12.

## 11. Thay đổi chính sách

Khi chính sách này đổi, chúng tôi cập nhật trang này và ngày có hiệu lực ở đầu trang.

## 12. Liên hệ

HaDoSolution — hadosolution@gmail.com

---

# Lời Bài Hát Privacy Policy

Effective 6 October 2026. Last updated 6 October 2026.

Lời Bài Hát is an offline lyrics app for Vietnamese songs, published on Google Play by **HaDoSolution**. This policy explains what the app stores on your device, what it
sends out, who receives it, and how you can change that.

## In short

- The app has **no accounts** and never asks for your name, email, phone number or anything else
  that identifies you.
- Your favourite songs, search history and settings **stay on your device**. We keep no copy.
- The app shows **ads** from Google AdMob, sends **usage statistics** to Google Analytics for
  Firebase and **crash reports** to Firebase Crashlytics.
- When you **request a song**, what you type is sent to our server (section 5).
- We **do not sell** your data to anyone.

## 1. Data stored on your device

The app keeps, in its own private storage on your device:

- the lyrics that ship with the app;
- the songs you mark as favourites and the songs you have viewed;
- the words you searched for;
- your settings: text size, number of songs shown, showing or hiding the song request button.

None of this is sent to us. To erase everything, uninstall the app or go to *Android Settings →
Apps → Lời Bài Hát → Storage → Clear data*.

**Backup to the SD card.** If you tap *Backup* in the settings screen, the app writes your list of
favourite songs to a file at the root of shared storage. That file lives outside the app's private
storage, so other apps allowed to read storage can read it too; it holds only the list of songs and
nothing about you. From Android 10 onwards Android no longer lets the app write there, so this option
no longer creates any file.

## 2. Ads — Google AdMob

The app shows a banner at the bottom of the song lists and the lyrics screen, and one full-screen ad
before the *Request a song* screen opens. To serve and measure those ads, the Google Mobile Ads SDK
**automatically collects** and sends to Google:

- your IP address, which may be used to estimate your general location (country, city);
- your Android advertising ID and app set ID;
- interactions with the app and with ads: app launches, taps, ad views;
- diagnostic information about the performance of the app and the SDK.

Google uses this data to serve ads, measure them and prevent fraud. How Google handles it is
described in [How Google uses information from sites or apps that use our
services](https://policies.google.com/technologies/partner-sites).

**You can** reset or delete your advertising ID in *Android Settings → Google → Ads* (the exact menu
name varies slightly between devices); once it is deleted, ads are no longer personalised by that
ID. The current version of the app does not yet show a consent form for users in the European
Economic Area, the United Kingdom and Switzerland; if you are there, the setting above is how you
turn off personalised ads.

## 3. Usage statistics — Google Analytics for Firebase

To learn how the app is used, the Google Analytics for Firebase SDK automatically sends Google:

- a random app-instance ID that Firebase creates for each installation, and your Android
  advertising ID;
- your approximate location, which Google derives from your IP address;
- automatic events: first launch, sessions, screens opened, app updates.

The app sends no events of its own: not the songs you read, not the words you search for. These
events contain no names, email addresses or anything that identifies you. We only look at them
in aggregate.

## 4. Crash reports — Firebase Crashlytics

When the app hits an error and closes unexpectedly, the Firebase Crashlytics SDK sends Google a
crash report so that we can find and fix the problem. The report contains:

- a stack trace: which part of the code was running when the error happened;
- device information: make and model, Android version, memory and free storage, screen
  orientation, and whether the device is rooted;
- a random installation ID that Crashlytics creates for each installation, used to count how many
  devices hit the same error.

The report contains no favourites, searches or anything you type.

## 5. Song requests and feedback

**Song requests.** When you tap *Send* on the song request screen, the app sends HaDoSolution's
server exactly what you filled in — title, composer, singer, notes — together with the app
name, over an encrypted HTTPS connection. Like any internet connection, the server also sees your IP
address. We use requests only to choose which songs to add, and we do not link them to any person.
Please do not put personal information in the notes field.

**Feedback by email.** The feedback option opens your email app. When you send a message we receive
your email address and the message, and we use them only to reply to you.

## 6. Sharing

The data in sections 2, 3 and 4 goes to Google, which provides those services; for ads, Google
may share the data in section 2 further under the Google policy linked there. Song requests and
feedback emails reach only us. We send your data to no one else, and we do not sell it.

## 7. Device permissions

The app asks for internet and network-state access (to show ads and send song requests), vibration
(when you long-press a song to save it as a favourite), and read and write access to shared storage (for
the backup in section 1). The installed app also still declares a phone-state permission from older
versions; the app does **not** read your phone number, IMEI or contacts.

## 8. Security

All data sent by the Google SDKs, and every song request, is encrypted in transit.

## 9. Children

Lời Bài Hát is not directed at children under 13. We do not knowingly collect data from children
under 13.

## 10. Your rights

Because the app has no accounts, we have no way to link the data in sections 2, 3 and 4 to a
particular person, so we cannot look up your data to delete it on request. You stay in control:
clear the data on your device (section 1) and reset your advertising ID (section 2). To have a song
request or feedback email deleted, or for any other question, write to us at the address in
section 12.

## 11. Changes to this policy

When this policy changes, we update this page and the effective date at the top.

## 12. Contact

HaDoSolution — hadosolution@gmail.com
