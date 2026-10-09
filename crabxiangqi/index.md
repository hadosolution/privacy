*Bản tiếng Việt trước, bản tiếng Anh ngay sau — English version below.*

# Chính sách quyền riêng tư của CrabXiangqi

Có hiệu lực từ 29/09/2026. Cập nhật lần cuối ngày 09/10/2026.

CrabXiangqi là game cờ tướng chơi offline cho Android, iPhone và iPad. Trên Google Play, app do
**HaDoSolution** phát hành; trên App Store, người bán là **Luan Vo**. Mỗi bên chịu trách nhiệm về dữ
liệu của bản app phát hành trên cửa hàng của mình; "chúng tôi" trong chính sách này là cả hai. Chính
sách này nói rõ app lưu gì trên máy bạn, gửi gì ra ngoài, gửi cho ai, và bạn thay đổi điều đó bằng
cách nào. Chỗ nào Android và iPhone/iPad khác nhau, chính sách ghi riêng từng bên.

## Tóm tắt

- App **không có tài khoản** và không bao giờ hỏi tên, email, số điện thoại hay bất kỳ thông tin
  nào để nhận ra bạn.
- Ván cờ, lịch sử ván và cài đặt **nằm trên máy bạn**. Chúng tôi không có bản sao nào.
- App hiện **một dải quảng cáo** của Google AdMob, gửi **số liệu sử dụng ẩn danh** cho Google
  Analytics for Firebase, và gửi **báo cáo sự cố** cho Firebase Crashlytics khi app bị lỗi. Ba dịch
  vụ này của Google là nơi duy nhất dữ liệu rời khỏi máy **tới một bên khác ngoài bạn**.
- Trên iPhone và iPad, app **chỉ dùng mã quảng cáo của Apple khi bạn cho phép** trong hộp thoại
  "theo dõi" của Apple (mục 2).
- Khi bạn **chơi hai máy qua Wi-Fi**, tên máy và nước đi đi thẳng sang máy của người chơi cùng, trong
  mạng Wi-Fi của hai bạn. Chúng không đi qua Internet và không tới chúng tôi (mục 5).
- Chúng tôi **không bán** dữ liệu của bạn cho ai.

## 1. Dữ liệu lưu trên máy bạn

App lưu trong bộ nhớ riêng của nó trên máy:

- cài đặt: ngôn ngữ, cấp độ máy, thời gian, âm thanh, bộ quân và các lựa chọn khác;
- ván đang đánh dở, để bạn chơi tiếp sau khi đóng app;
- lịch sử tối đa 50 ván đã chơi và bảng thống kê thắng thua;
- tiến độ bài học và cờ thế;
- ngày mở app lần đầu, dùng để không hiện quảng cáo trong mấy ngày đầu;
- tên máy bạn đặt cho việc chơi qua Wi-Fi, nếu bạn đã sửa nó.

Những dữ liệu này không được gửi cho chúng tôi.

- **Android:** nếu bạn bật sao lưu của Android, Android có thể sao lưu đúng tệp cài đặt ấy vào tài
  khoản Google của bạn để khôi phục khi đổi máy. Bản sao lưu do Google giữ theo [chính sách của
  Google](https://policies.google.com/privacy), và chúng tôi không đọc được nó. Muốn xoá hết, hãy gỡ
  app hoặc vào *Cài đặt Android → Ứng dụng → CrabXiangqi → Bộ nhớ → Xoá dữ liệu*.
- **iPhone và iPad:** dữ liệu ấy nằm trong bản sao lưu thiết bị nếu bạn sao lưu máy lên iCloud hoặc
  máy tính. Bản sao lưu do Apple hoặc máy tính của bạn giữ theo [chính sách của
  Apple](https://www.apple.com/legal/privacy/), và chúng tôi không đọc được nó. Muốn xoá hết, hãy gỡ
  app (giữ ngón tay trên biểu tượng → *Xoá ứng dụng*).

## 2. Quảng cáo — Google AdMob

App hiện một dải quảng cáo nhỏ trong ván cờ, không hiện quảng cáo chen giữa ván. Để hiện và đo
quảng cáo, SDK Google Mobile Ads **tự thu thập** và gửi cho Google:

- địa chỉ IP, có thể dùng để ước đoán vị trí chung (quốc gia, thành phố);
- trên Android: mã quảng cáo Android (Advertising ID) và mã App set ID;
- trên iPhone và iPad: mã quảng cáo của Apple (IDFA) **chỉ khi bạn cho phép theo dõi**, cùng các mã
  nhận dạng chỉ dùng được trong phạm vi app hoặc nhà phát triển (như IDFV);
- tương tác với app và với quảng cáo: mở app, chạm, lượt xem quảng cáo;
- thông tin chẩn đoán về hiệu năng của app và của SDK.

Google dùng các dữ liệu này để hiện quảng cáo, đo hiệu quả quảng cáo và chống gian lận. Cách Google
xử lý chúng nằm ở [Cách Google sử dụng thông tin từ các trang web hoặc ứng dụng sử dụng dịch vụ của
Google](https://policies.google.com/technologies/partner-sites).

**Hộp thoại "theo dõi" trên iPhone và iPad.** Lần đầu mở app, iOS hiện hộp thoại của Apple hỏi bạn
có cho phép app theo dõi hoạt động của bạn qua app và trang web của công ty khác hay không. Cho phép
thì SDK quảng cáo được đọc IDFA để chọn và đo quảng cáo; từ chối thì app không bao giờ nhận được IDFA,
và quảng cáo vẫn hiện nhưng không dựa trên mã ấy. App không xin quảng cáo nào trước khi bạn trả lời.

**Bạn có thể:**

- trên Android: đặt lại hoặc xoá mã quảng cáo ở *Cài đặt Android → Google → Quảng cáo* (tên mục
  khác nhau đôi chút giữa các máy);
- trên iPhone và iPad: đổi lựa chọn "theo dõi" bất cứ lúc nào ở *Cài đặt → Quyền riêng tư & Bảo mật
  → Theo dõi*;
- nếu bạn ở Khu vực Kinh tế Châu Âu, Vương quốc Anh hoặc Thuỵ Sĩ: app hỏi bạn đồng ý qua một biểu
  mẫu của Google — trên iPhone và iPad, biểu mẫu này hiện trước hộp thoại của Apple — và không xin
  quảng cáo nào trước khi bạn trả lời. Bạn đổi lựa chọn bất cứ lúc nào ở *Cài đặt → Quyền riêng tư*
  trong app. Không đồng ý cá nhân hoá thì quảng cáo không được cá nhân hoá.

## 3. Số liệu sử dụng — Google Analytics for Firebase

Để biết tính năng nào được dùng và chỗ nào quá khó, app gửi cho Google Analytics for Firebase:

- mã cài đặt ngẫu nhiên (app-instance ID) mà Firebase tự tạo cho mỗi lần cài, và — chỉ trên
  Android — mã quảng cáo Android. Bản iPhone và iPad không gửi IDFA cho Firebase;
- vị trí gần đúng, do Google suy ra từ địa chỉ IP đã được che bớt;
- màn hình đã mở và phiên sử dụng;
- các sự kiện trong game: bắt đầu và kết thúc một ván (chế độ chơi, cấp độ máy, thời gian, kết
  quả, số nước), dùng gợi ý, đi lại, hoàn thành một bài học, và đổi một cài đặt (tên cài đặt và
  giá trị mới).

Các sự kiện này không chứa nước đi, tên hay bất cứ thứ gì bạn nhập vào. Chúng tôi chỉ xem chúng ở
dạng tổng hợp. Ở Khu vực Kinh tế Châu Âu, Vương quốc Anh và Thuỵ Sĩ, lựa chọn của bạn trong biểu mẫu
ở mục 2 cũng quyết định Firebase được lưu những gì kể từ lúc đó. Biểu mẫu hiện ra sau khi app đã khởi
động, nên trước khi bạn trả lời, Firebase có thể đã ghi các sự kiện tự động của nó, như lần đầu mở
app (`first_open`) và một phiên sử dụng bắt đầu (`session_start`). Các sự kiện này chỉ mang các mã
nhận dạng và vị trí gần đúng nêu ở trên, không có gì về ván cờ của bạn.

## 4. Báo cáo sự cố — Firebase Crashlytics

Khi app gặp lỗi và bị đóng đột ngột, SDK Firebase Crashlytics gửi cho Google một báo cáo sự cố để
chúng tôi tìm và sửa lỗi ấy. Báo cáo gồm:

- dấu vết lỗi (stack trace): đoạn code nào đang chạy lúc lỗi xảy ra;
- trạng thái của app lúc đó, gồm màn hình đang mở và các sự kiện gần nhất ở mục 3;
- thông tin thiết bị: hãng và đời máy, phiên bản Android hoặc iOS, bộ nhớ và dung lượng còn trống,
  hướng màn hình, máy đã root (Android) hay jailbreak (iOS) hay chưa;
- một mã cài đặt ngẫu nhiên mà Crashlytics tạo cho mỗi lần cài, để đếm bao nhiêu máy gặp cùng một
  lỗi.

Báo cáo không chứa ván cờ, nước đi hay bất cứ thứ gì bạn nhập vào. Firebase chỉ dùng dữ liệu này để
cung cấp dịch vụ báo cáo sự cố. Báo cáo được gửi ở mọi nơi, kể cả châu Âu, vì nó chỉ dùng để sửa lỗi
của app; lựa chọn của bạn trong biểu mẫu ở mục 2 không ảnh hưởng tới nó.

## 5. Chia sẻ dữ liệu

Dữ liệu ở mục 2, 3 và 4 đi tới Google, bên cung cấp các dịch vụ ấy; với quảng cáo, Google có thể
chia sẻ tiếp dữ liệu ở mục 2 theo chính sách của Google đã dẫn ở đó. Chúng tôi không gửi dữ liệu
của bạn cho ai khác và không bán nó.

Trên iPhone và iPad, nếu bạn bật *Chia sẻ với nhà phát triển ứng dụng* trong cài đặt Phân tích của
iOS, Apple gửi cho chúng tôi báo cáo sự cố và số liệu sử dụng tổng hợp theo [chính sách của
Apple](https://www.apple.com/legal/privacy/). Bạn tắt nó ở *Cài đặt → Quyền riêng tư & Bảo mật →
Phân tích & Cải tiến*.

**Chơi hai máy qua Wi-Fi.** Chế độ này chỉ chạy khi bạn tự mở nó. Hai máy nói chuyện trực tiếp với
nhau trong mạng Wi-Fi chung, không qua máy chủ nào:

- khi bạn **tạo ván**, app quảng bá tên máy của bạn trong mạng Wi-Fi ấy để máy kia tìm thấy — mọi
  thiết bị trong cùng mạng đều có thể thấy tên này cho tới khi bạn rời màn tạo ván;
- trong ván, app gửi sang máy kia tên máy, số phiên bản app, nước đi, thời gian còn lại, lời cầu hoà
  và xin thua; màn chờ đối thủ hiện địa chỉ IP trong mạng nội bộ của máy bạn để người kia gõ vào.

Trên Android, tên máy mặc định lấy từ tên thiết bị trong cài đặt của máy — nếu tên ấy có tên thật
của bạn, hãy đổi nó trước khi chơi ở mạng Wi-Fi công cộng. Trên iPhone và iPad, tên mặc định chỉ là
"iPhone" hoặc "iPad", và iOS hỏi bạn cho phép app tìm thiết bị trong mạng nội bộ lần đầu bạn dùng chế
độ này; từ chối thì chế độ này không chạy, phần còn lại của app vẫn bình thường. Ở cả hai, bạn sửa
được tên ở màn tạo ván hay tìm ván. Ván
chơi qua Wi-Fi được lưu vào lịch sử trên máy bạn như mọi ván khác. Chúng tôi không nhận được bất kỳ
dữ liệu nào trong số này.

## 6. Bảo mật

Mọi dữ liệu mà các SDK của Google gửi đi đều được mã hoá trên đường truyền (TLS). Dữ liệu của chế độ
chơi qua Wi-Fi (mục 5) **không** được mã hoá: nó chỉ đi trong mạng nội bộ của bạn, nhưng thiết bị khác
trong cùng mạng về kỹ thuật có thể đọc được.

## 7. Trẻ em

CrabXiangqi dành cho người từ 13 tuổi trở lên và không nhắm tới trẻ em. Chúng tôi không cố ý thu
thập dữ liệu của trẻ dưới 13 tuổi.

## 8. Quyền của bạn

Vì app không có tài khoản, chúng tôi không có cách nào gắn dữ liệu ở mục 2, 3 và 4 với một người cụ
thể, và cũng không tra ra được dữ liệu của riêng bạn để xoá theo yêu cầu. Bạn vẫn kiểm soát được:
xoá dữ liệu trên máy (mục 1), đặt lại mã quảng cáo trên Android hoặc tắt "theo dõi" trên iPhone và
iPad (mục 2), và — ở châu Âu — đổi lựa chọn đồng ý trong app. Mọi câu hỏi khác, hãy viết cho chúng tôi theo địa chỉ ở mục 10.

## 9. Thay đổi chính sách

Khi chính sách này đổi, chúng tôi cập nhật trang này và ngày có hiệu lực ở đầu trang.

## 10. Liên hệ

- Bản trên Google Play: HaDoSolution — hadosolution@gmail.com
- Bản trên App Store: Luan Vo — hadosolution@gmail.com

---

# CrabXiangqi Privacy Policy

Effective 29 September 2026. Last updated 9 October 2026.

CrabXiangqi is an offline Xiangqi (Chinese chess) game for Android, iPhone and iPad. On Google Play
it is published by **HaDoSolution**; on the App Store the seller is **Luan Vo**. Each is responsible
for the data of the version sold in their store; "we" in this policy means both. This policy explains
what the app stores on your device, what it sends out, who receives it, and how you can change that.
Where Android and iPhone/iPad differ, the policy says so for each.

## In short

- The app has **no accounts** and never asks for your name, email, phone number or anything else
  that identifies you.
- Your games, game history and settings **stay on your device**. We keep no copy.
- The app shows **one banner ad** from Google AdMob, sends **anonymous usage statistics** to
  Google Analytics for Firebase, and sends a **crash report** to Firebase Crashlytics when the app
  fails. Those three Google services are the only places data leaves your device **for anyone other
  than you**.
- On iPhone and iPad, the app **uses Apple's advertising identifier only if you allow it** in Apple's
  tracking prompt (section 2).
- When you **play two devices over Wi-Fi**, your device name and your moves go straight to the other
  player's device, on your shared Wi-Fi. They never cross the internet and never reach us (section 5).
- We **do not sell** your data to anyone.

## 1. Data stored on your device

The app keeps, in its own private storage on your device:

- your settings: language, AI level, time limit, sound, piece set and other choices;
- an unfinished game, so you can resume it after closing the app;
- a history of up to 50 finished games, and your win/loss statistics;
- your progress through the lessons and puzzles;
- the date you first opened the app, used to show no ads during the first few days;
- the device name you set for playing over Wi-Fi, if you changed it.

None of this is sent to us.

- **Android:** if you turn on Android backup, Android may back up that settings file to your Google
  account so it can be restored on a new device. Google holds that backup under [Google's Privacy
  Policy](https://policies.google.com/privacy), and we cannot read it. To erase everything, uninstall
  the app or go to *Android Settings → Apps → CrabXiangqi → Storage → Clear data*.
- **iPhone and iPad:** this data is part of your device backup if you back up to iCloud or a
  computer. Apple or your computer holds that backup under [Apple's Privacy
  Policy](https://www.apple.com/legal/privacy/), and we cannot read it. To erase everything, delete
  the app (touch and hold its icon → *Delete App*).

## 2. Ads — Google AdMob

The app shows a small banner during a game and no ads that interrupt play. To serve and measure
those ads, the Google Mobile Ads SDK **automatically collects** and sends to Google:

- your IP address, which may be used to estimate your general location (country, city);
- on Android: your Android advertising ID and app set ID;
- on iPhone and iPad: Apple's advertising identifier (IDFA) **only if you allow tracking**, and
  identifiers limited to the app or developer (such as the IDFV);
- interactions with the app and with ads: app launches, taps, ad views;
- diagnostic information about the performance of the app and the SDK.

Google uses this data to serve ads, measure them and prevent fraud. How Google handles it is
described in [How Google uses information from sites or apps that use our
services](https://policies.google.com/technologies/partner-sites).

**Apple's tracking prompt on iPhone and iPad.** The first time you open the app, iOS shows Apple's
prompt asking whether the app may track your activity across other companies' apps and websites. If
you allow it, the ads SDK may read the IDFA to choose and measure ads; if you don't, the app never
receives the IDFA, and ads still appear without it. The app requests no ads until you answer.

**You can:**

- on Android: reset or delete your advertising ID in *Android Settings → Google → Ads* (the exact
  menu name varies slightly between devices);
- on iPhone and iPad: change your tracking choice at any time in *Settings → Privacy & Security →
  Tracking*;
- if you are in the European Economic Area, the United Kingdom or Switzerland: the app asks for
  your consent through a Google form — on iPhone and iPad, before Apple's prompt — and requests no
  ads at all until you answer. You can change your choice at any time under *Settings → Privacy* in
  the app. If you do not consent to personalisation, the ads you see are not personalised.

## 3. Usage statistics — Google Analytics for Firebase

To learn which features are used and where the game is too hard, the app sends Google Analytics
for Firebase:

- a random app-instance ID that Firebase creates for each installation, and — on Android only —
  your Android advertising ID. The iPhone and iPad version does not send the IDFA to Firebase;
- your approximate location, which Google derives from a masked IP address;
- which screens you open, and your sessions;
- in-game events: starting and finishing a game (mode, AI level, time limit, result, number of
  moves), using a hint, taking back a move, completing a lesson, and changing a setting (the
  setting's name and new value).

These events contain no moves, names or anything you type. We only look at them in aggregate. In
the European Economic Area, the United Kingdom and Switzerland, your choice in the form described
in section 2 also decides what Firebase may store from then on. The form appears once the app has
started, so before you answer it Firebase may already record its automatic events, such as the app
being opened for the first time (`first_open`) and the start of a session (`session_start`). Those
carry only the identifiers and approximate location listed above, and nothing about your games.

## 4. Crash reports — Firebase Crashlytics

When the app hits an error and closes unexpectedly, the Firebase Crashlytics SDK sends Google a
crash report so that we can find and fix the problem. The report contains:

- a stack trace: which part of the code was running when the error happened;
- the state of the app at that moment, including the open screen and the most recent events from
  section 3;
- device information: make and model, Android or iOS version, memory and free storage, screen
  orientation, and whether the device is rooted (Android) or jailbroken (iOS);
- a random installation ID that Crashlytics creates for each installation, used to count how many
  devices hit the same error.

The report contains no games, moves or anything you type. Firebase uses this data only to provide
its crash reporting service. Crash reports are sent everywhere, including Europe, because they are
used only to fix the app; your choice in the form described in section 2 does not affect them.

## 5. Sharing

The data in sections 2, 3 and 4 goes to Google, which provides those services; for ads, Google may
share the data in section 2 further under the Google policy linked there. We send your data to no
one else, and we do not sell it.

On iPhone and iPad, if you turn on *Share With App Developers* in the iOS Analytics settings, Apple
sends us crash reports and aggregated usage statistics under [Apple's Privacy
Policy](https://www.apple.com/legal/privacy/). You can turn it off in *Settings → Privacy & Security →
Analytics & Improvements*.

**Playing two devices over Wi-Fi.** This mode runs only when you open it. The two devices talk to each
other directly on your shared Wi-Fi, through no server:

- when you **create a game**, the app announces your device name on that Wi-Fi so the other device
  can find it — any device on the same network can see this name until you leave the create screen;
- during the game, the app sends the other device your device name, the app version, your moves, the
  time left, draw offers and resignations; the waiting screen shows your device's local IP address so
  the other player can type it in.

On Android, the default device name comes from your device's own settings — if it contains your real
name, change it before playing on public Wi-Fi. On iPhone and iPad, the default name is just "iPhone"
or "iPad", and iOS asks you to allow the app to find devices on your local network the first time you
use this mode; if you decline, this mode does not work and the rest of the app is unaffected. On
both, you can change the name on the create and find screens. A game played over Wi-Fi is saved to the history on your device like any other. We receive
none of this data.

## 6. Security

All data sent by the Google SDKs is encrypted in transit (TLS). Data from playing over Wi-Fi
(section 5) is **not** encrypted: it stays on your local network, but other devices on the same
network could technically read it.

## 7. Children

CrabXiangqi is intended for people aged 13 and over and is not directed at children. We do not
knowingly collect data from children under 13.

## 8. Your rights

Because the app has no accounts, we have no way to link the data in sections 2, 3 and 4 to a
particular person, so we cannot look up your data to delete it on request. You stay in control:
clear the data on your device (section 1), reset your advertising ID on Android or turn off tracking
on iPhone and iPad (section 2), and — in Europe — change your consent in the app. For any other question, write to us at the address in section 10.

## 9. Changes to this policy

When this policy changes, we update this page and the effective date at the top.

## 10. Contact

- Google Play version: HaDoSolution — hadosolution@gmail.com
- App Store version: Luan Vo — hadosolution@gmail.com
