*Bản tiếng Việt trước, bản tiếng Anh ngay sau — English version below.*

# Chính sách quyền riêng tư của Lời Vọng Cổ

Có hiệu lực từ 28/10/2026. Cập nhật lần cuối ngày 28/10/2026.

Lời Vọng Cổ là ứng dụng tra cứu lời vọng cổ, cải lương xem được khi không có mạng, do
**HaDoSolution** phát hành trên Google Play. Chính sách này nói rõ app lưu gì trên máy bạn, gửi gì
ra ngoài, gửi cho ai, và bạn thay đổi điều đó bằng cách nào.

Chính sách áp dụng cho **phiên bản 3.0.0 trở đi**. Trong thời gian bản 3.0.0 được phát hành dần, một
số máy còn chạy phiên bản 2.6; chỗ nào phiên bản 2.6 làm khác, chính sách ghi rõ ở đó. Bạn xem
phiên bản đang dùng ở *Cài đặt → Thông tin ứng dụng → Phiên bản*.

## Tóm tắt

- App **không có tài khoản** và không bao giờ hỏi tên, email, số điện thoại hay bất kỳ thông tin
  nào để nhận ra bạn.
- Bài yêu thích, lịch sử xem, lịch sử tìm kiếm và cài đặt **nằm trên máy bạn**. Chúng tôi không có
  bản sao nào.
- App hiện **quảng cáo** của Google AdMob, gửi **số liệu sử dụng** cho Google Analytics for Firebase
  và **báo cáo sự cố** cho Firebase Crashlytics.
- Khi bạn **gửi yêu cầu bài hát**, nội dung bạn gõ được gửi về máy chủ của chúng tôi, kèm một mã
  ngẫu nhiên của lần cài để app báo cho bạn khi bài đã có (mục 5).
- App **tải dữ liệu bài hát mới** từ máy chủ của chúng tôi hoặc từ GitHub; việc tải không gửi gì về
  bạn (mục 6).
- Chúng tôi **không bán** dữ liệu của bạn cho ai.

## 1. Dữ liệu lưu trên máy bạn

App lưu trong bộ nhớ riêng của nó trên máy:

- bộ lời bài hát đi kèm app, và các bản dữ liệu mới app đã tải về (mục 6);
- bài bạn đánh dấu yêu thích, và các bài bạn đã mở cùng thời điểm mở;
- các từ khoá bạn đã tìm;
- các yêu cầu bài hát bạn đã gửi, trạng thái máy chủ báo về, và bước nào app đã báo cho bạn;
- cài đặt: cỡ chữ, số bài hiển thị, hiện hay ẩn nút yêu cầu bài hát, tự tải dữ liệu mới.

Những dữ liệu này không được gửi cho chúng tôi. Bạn xoá lịch sử tìm kiếm và lịch sử đã xem ở màn
*Cài đặt*. Muốn xoá hết, hãy gỡ app hoặc vào *Cài đặt Android → Ứng dụng → Lời Vọng Cổ → Bộ nhớ →
Xoá dữ liệu*.

**Sao lưu khi đổi máy.** Nếu bạn bật sao lưu của Android (*Cài đặt Android → Google → Sao lưu*),
Android tự sao lưu bài yêu thích, lịch sử, các yêu cầu bài hát đã gửi và cài đặt của app vào tài
khoản Google **của bạn**, và chép chúng sang máy mới khi bạn chuyển máy. Bản sao lưu do Google lưu
giữ theo cài đặt của bạn; chúng tôi không đọc được nó. Bộ lời bài hát không được sao lưu vì máy mới
tải lại cùng app.

*Phiên bản 2.6:* không dùng sao lưu của Android. Mục *Sao lưu* trong màn Cài đặt ghi danh sách bài
yêu thích ra một tệp ở thư mục gốc của bộ nhớ chung — nơi ứng dụng khác có quyền đọc bộ nhớ cũng
đọc được; tệp chỉ chứa danh sách bài. Từ Android 10 trở đi, Android không cho app ghi vào đó nữa,
nên mục này không còn tạo ra tệp nào.

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

**Nếu bạn ở Khu vực Kinh tế Châu Âu, Vương quốc Anh hoặc Thuỵ Sĩ**, lần đầu mở app sẽ hiện biểu mẫu
của Google để bạn đồng ý hoặc từ chối quảng cáo cá nhân hoá trước khi quảng cáo được tải. Bạn đổi
lựa chọn đó bất cứ lúc nào ở *Cài đặt → Quyền riêng tư quảng cáo*; lựa chọn cũng được chuyển cho
Google Analytics for Firebase (mục 3).

**Ở mọi nơi**, bạn có thể đặt lại hoặc xoá mã quảng cáo ở *Cài đặt Android → Google → Quảng cáo*
(tên mục khác nhau đôi chút giữa các máy); khi mã quảng cáo bị xoá, quảng cáo không còn được cá nhân
hoá theo mã đó.

*Phiên bản 2.6:* không có biểu mẫu đồng ý; cách đặt lại mã quảng cáo ở trên là cách tắt quảng cáo cá
nhân hoá.

## 3. Số liệu sử dụng và báo cáo sự cố — Google Analytics for Firebase, Firebase Crashlytics

**Số liệu sử dụng.** Để biết app được dùng thế nào, SDK Google Analytics for Firebase tự gửi cho
Google:

- mã cài đặt ngẫu nhiên (app-instance ID) mà Firebase tự tạo cho mỗi lần cài, và mã quảng cáo
  Android;
- vị trí gần đúng, do Google suy ra từ địa chỉ IP;
- các sự kiện tự động: lần đầu mở app, phiên sử dụng, màn hình đã mở, cập nhật app;
- một lần duy nhất sau khi nâng cấp lên 3.0.0: **số** bài yêu thích đã được chuyển sang bản mới — chỉ
  là con số, không có tên bài.

App không gửi tên bài bạn xem hay từ khoá bạn tìm. Các sự kiện này không chứa tên, email hay bất cứ
thứ gì nhận ra bạn. Chúng tôi chỉ xem chúng ở dạng tổng hợp.

*Phiên bản 2.6* gửi thêm: khi bạn mở một bài — tên bài, tên soạn giả và phiên bản app; khi một lần
tìm **không ra bài nào** và từ khoá dài từ 7 ký tự trở lên — từ khoá đó và phiên bản app. Phiên bản
2.6 cũng gửi **số đo hiệu năng** cho Firebase Performance Monitoring: thời gian khởi động và vẽ màn
hình, thời gian và kích thước các lần app gọi mạng (địa chỉ được gọi, mã phản hồi), thông tin thiết
bị (hãng, đời máy, phiên bản Android, loại kết nối) và một mã cài đặt ngẫu nhiên. Phiên bản 3.0.0
không còn Performance Monitoring.

**Báo cáo sự cố.** Khi app gặp lỗi và bị đóng đột ngột, SDK Firebase Crashlytics gửi cho Google một
báo cáo sự cố để chúng tôi tìm và sửa lỗi ấy. Báo cáo gồm:

- dấu vết lỗi (stack trace): đoạn code nào đang chạy lúc lỗi xảy ra;
- thông tin thiết bị: hãng và đời máy, phiên bản Android, bộ nhớ và dung lượng còn trống, hướng
  màn hình, máy đã root hay chưa;
- một mã cài đặt ngẫu nhiên mà Crashlytics tạo cho mỗi lần cài, để đếm bao nhiêu máy gặp cùng một
  lỗi.

Báo cáo không chứa bài yêu thích, từ khoá tìm kiếm hay bất cứ thứ gì bạn gõ.

## 4. Quyền trên máy

App xin quyền truy cập Internet và trạng thái mạng (để hiện quảng cáo, gửi yêu cầu bài hát và tải
dữ liệu bài hát mới), quyền rung (khi nhấn giữ một bài để lưu yêu thích), và quyền dùng mã quảng cáo
(cho mục 2). Thư viện chạy việc nền của Android thêm quyền giữ máy thức trong lúc một lần tải dữ liệu
đang chạy. App **không** xin quyền đọc bộ nhớ chung, quyền thông báo hay quyền đọc trạng thái điện
thoại, và không đọc số điện thoại, mã IMEI hay danh bạ của bạn.

*Phiên bản 2.6* xin thêm quyền ghi bộ nhớ chung cho mục sao lưu cũ ở mục 1.

## 5. Yêu cầu bài hát và góp ý

**Yêu cầu bài hát.** Khi bạn bấm *Gửi* ở màn Yêu cầu bài hát, app gửi về máy chủ của HaDoSolution
đúng những gì bạn điền — tên bài, tác giả, ca sĩ, thể loại, ghi chú — cùng tên và phiên bản app, qua
kết nối mã hoá HTTPS. Kèm theo là một **mã ngẫu nhiên app tạo cho mỗi lần cài**, chỉ dùng để tra
trạng thái các yêu cầu bạn đã gửi.

Khi bạn mở app, nếu còn yêu cầu đang được xử lý, app hỏi máy chủ theo mã đó (tối đa mỗi giờ một
lần) yêu cầu nào đã sang bước mới — đã tiếp nhận, đang soạn lời, đã có bài hay không thực hiện được
— rồi báo cho bạn ngay trong app. App **không** gửi thông báo đẩy và không xin quyền thông báo.

Mã này không chứa tên, email hay số điện thoại của bạn; gỡ rồi cài lại app là có mã mới (trừ khi
Android khôi phục bản sao lưu ở mục 1, khi đó máy mới dùng tiếp mã cũ để bạn vẫn theo dõi được yêu
cầu đã gửi). Máy chủ nhận thêm địa chỉ IP của bạn như mọi kết nối Internet. Chúng tôi dùng yêu cầu
để chọn bài bổ sung vào app và báo lại trong app khi bài đã có. Đừng ghi thông tin cá nhân vào ô
ghi chú.

**Góp ý qua email.** Mục góp ý mở ứng dụng email của bạn. Khi bạn gửi, chúng tôi nhận được địa chỉ
email và nội dung thư, và chỉ dùng chúng để trả lời bạn.

## 6. Tải dữ liệu bài hát mới

*Từ phiên bản 3.0.0.* Để có bài mới mà không phải chờ bản cập nhật trên Google Play, app kiểm tra
mỗi ngày một lần khi máy có Wi-Fi — hoặc khi bạn bấm *Cập nhật dữ liệu* trong Cài đặt — xem có bản
dữ liệu bài hát mới không, rồi tải về. Bạn tắt việc tự tải ở *Cài đặt → Tự động tải dữ liệu mới*.

Dữ liệu được tải từ máy chủ của HaDoSolution (`api.code2smile.com`), hoặc từ GitHub khi máy chủ của
chúng tôi không trả lời. Đây là các tệp tĩnh: app chỉ xin tệp, **không gửi mã nào về bạn**. Như mọi
kết nối Internet, máy chủ trả tệp — của chúng tôi, hoặc của GitHub, Inc. — nhận địa chỉ IP của máy
bạn; GitHub xử lý dữ liệu đó theo [Tuyên bố quyền riêng tư của
GitHub](https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement).
Dữ liệu tải về được ký số và kiểm tra trước khi dùng.

## 7. Chia sẻ dữ liệu

Dữ liệu ở mục 2 và 3 đi tới Google, bên cung cấp các dịch vụ ấy; với quảng cáo, Google có thể chia
sẻ tiếp dữ liệu ở mục 2 theo chính sách của Google đã dẫn ở đó. Yêu cầu bài hát và thư góp ý chỉ tới
chúng tôi. Ngoài địa chỉ IP mà GitHub nhận khi app tải dữ liệu (mục 6), chúng tôi không gửi dữ liệu
của bạn cho ai khác và không bán nó.

## 8. Bảo mật

Mọi dữ liệu mà các SDK của Google gửi đi, mọi yêu cầu bài hát và mọi lần tải dữ liệu bài hát đều đi
qua kết nối mã hoá.

## 9. Trẻ em

Lời Vọng Cổ không nhắm tới trẻ em dưới 13 tuổi. Chúng tôi không cố ý thu thập dữ liệu của trẻ dưới
13 tuổi.

## 10. Quyền của bạn

Vì app không có tài khoản, chúng tôi không có cách nào gắn dữ liệu ở mục 2 và 3 với một người cụ
thể, nên cũng không tra ra được dữ liệu của riêng bạn để xoá theo yêu cầu. Bạn vẫn kiểm soát được:
xoá lịch sử hoặc toàn bộ dữ liệu trên máy (mục 1), đặt lại mã quảng cáo (mục 2), tắt tự tải dữ liệu
(mục 6). Muốn xoá một yêu cầu bài hát hay thư góp ý đã gửi, hoặc có câu hỏi khác, hãy viết cho chúng
tôi theo địa chỉ ở mục 12.

## 11. Thay đổi chính sách

Khi chính sách này đổi, chúng tôi cập nhật trang này và ngày có hiệu lực ở đầu trang.

## 12. Liên hệ

HaDoSolution — hadosolution@gmail.com

---

# Lời Vọng Cổ Privacy Policy

Effective 28 October 2026. Last updated 28 October 2026.

Lời Vọng Cổ is an offline lyrics app for Vietnamese vọng cổ and cải lương opera songs, published on
Google Play by **HaDoSolution**. This policy explains what the app stores on your device, what it
sends out, who receives it, and how you can change that.

This policy covers **version 3.0.0 and later**. While version 3.0.0 is being rolled out, some devices
still run version 2.6; wherever version 2.6 behaves differently, the policy says so. You can see your
version under *Settings → App information → Version*.

## In short

- The app has **no accounts** and never asks for your name, email, phone number or anything else
  that identifies you.
- Your favourite songs, viewing history, search history and settings **stay on your device**. We
  keep no copy.
- The app shows **ads** from Google AdMob, sends **usage statistics** to Google Analytics for
  Firebase and **crash reports** to Firebase Crashlytics.
- When you **request a song**, what you type is sent to our server, with a random per-install code
  the app uses to tell you when the song is ready (section 5).
- The app **downloads new song data** from our server or from GitHub; downloading sends nothing about
  you (section 6).
- We **do not sell** your data to anyone.

## 1. Data stored on your device

The app keeps, in its own private storage on your device:

- the lyrics that ship with the app, and any newer song data it has downloaded (section 6);
- the songs you mark as favourites, and the songs you opened and when;
- the words you searched for;
- the song requests you sent, the status the server reported, and which step the app has already
  told you about;
- your settings: text size, number of songs shown, showing or hiding the song request button,
  downloading new data automatically.

None of this is sent to us. You can clear your search history and viewing history in the *Settings*
screen. To erase everything, uninstall the app or go to *Android Settings → Apps → Lời Vọng Cổ →
Storage → Clear data*.

**Backup when you change phones.** If you turn on Android backup (*Android Settings → Google →
Backup*), Android backs up the app's favourites, history, sent song requests and settings to **your**
Google account, and copies them to your new phone when you switch. Google keeps that backup according
to your settings; we cannot read it. The lyrics are not backed up, because the new phone downloads
them with the app.

*Version 2.6:* does not use Android backup. Its *Backup* option in the settings screen writes your
list of favourite songs to a file at the root of shared storage, where other apps allowed to read
storage can read it too; the file holds only the list of songs. From Android 10 onwards Android no
longer lets the app write there, so this option no longer creates any file.

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

**If you are in the European Economic Area, the United Kingdom or Switzerland**, the first time you
open the app it shows Google's form so you can accept or refuse personalised ads before any ad is
loaded. You can change that choice at any time in *Settings → Quyền riêng tư quảng cáo* (ad
privacy); it is also passed on to Google Analytics for Firebase (section 3).

**Everywhere**, you can reset or delete your advertising ID in *Android Settings → Google → Ads* (the
exact menu name varies slightly between devices); once it is deleted, ads are no longer personalised
by that ID.

*Version 2.6:* shows no consent form; resetting your advertising ID as above is how you turn off
personalised ads.

## 3. Usage statistics and crash reports — Google Analytics for Firebase, Firebase Crashlytics

**Usage statistics.** To learn how the app is used, the Google Analytics for Firebase SDK
automatically sends Google:

- a random app-instance ID that Firebase creates for each installation, and your Android
  advertising ID;
- your approximate location, which Google derives from your IP address;
- automatic events: first open, sessions, screens viewed, app updates;
- once, after upgrading to 3.0.0: the **number** of favourite songs carried over to the new version —
  a count only, with no song titles.

The app does not send the titles of songs you read or the words you search for. These events contain
no names, email addresses or anything that identifies you. We only look at them in aggregate.

*Version 2.6* also sends: when you open a song, its title, its lyricist and the app version; when a
search **finds no song** and the search text is at least 7 characters long, that text and the app
version. Version 2.6 also sends **performance measurements** to Firebase Performance Monitoring:
start-up and screen rendering times, the duration and size of the app's network requests (the
address called and the response code), device information (make, model, Android version, connection
type) and a random installation ID. Version 3.0.0 no longer uses Performance Monitoring.

**Crash reports.** When the app hits an error and closes unexpectedly, the Firebase Crashlytics SDK
sends Google a crash report so that we can find and fix the problem. The report contains:

- a stack trace: which part of the code was running when the error happened;
- device information: make and model, Android version, memory and free storage, screen
  orientation, and whether the device is rooted;
- a random installation ID that Crashlytics creates for each installation, used to count how many
  devices hit the same error.

The report contains no favourites, searches or anything you type.

## 4. Device permissions

The app asks for internet and network-state access (to show ads, send song requests and download new
song data), vibration (when you long-press a song to save it as a favourite), and access to the
advertising ID (for section 2). Android's background-work library adds permission to keep the device
awake while a data download is running. The app does **not** ask for shared-storage, notification or
phone-state access, and does not read your phone number, IMEI or contacts.

*Version 2.6* also asks for write access to shared storage, for the old backup in section 1.

## 5. Song requests and feedback

**Song requests.** When you tap *Send* on the song request screen, the app sends HaDoSolution's
server exactly what you filled in — title, composer, singer, genre, notes — together with the app
name and version, over an encrypted HTTPS connection. With it goes a **random code the app creates
once per install**, used only to look up the status of the requests you sent.

When you open the app and some requests are still being handled, the app asks the server for that
code (at most once an hour) which requests have moved on — accepted, lyrics being written, song
available, or not possible — and tells you inside the app. The app sends **no** push notifications
and does not ask for notification permission.

The code holds nothing about you — not your name, email or phone number — and reinstalling the app
creates a new one (unless Android restores the backup in section 1, in which case the new phone keeps
the old code so you can still follow your requests). Like any internet connection, the server also
sees your IP address. We use requests to choose which songs to add and to tell you in the app when a
song is available. Please do not put personal information in the notes field.

**Feedback by email.** The feedback option opens your email app. When you send a message we receive
your email address and the message, and we use them only to reply to you.

## 6. Downloading new song data

*From version 3.0.0.* So that new songs arrive without waiting for an update on Google Play, the app
checks once a day while the device is on Wi-Fi — or when you tap *Update data* in Settings — whether
a newer set of song data exists, and downloads it. You can turn automatic downloads off in *Settings
→ Download new data automatically*.

The data comes from HaDoSolution's server (`api.code2smile.com`), or from GitHub when our server does
not answer. These are static files: the app only asks for the file and **sends no code about you**.
Like any internet connection, the server delivering the file — ours, or GitHub, Inc.'s — sees your
device's IP address; GitHub handles it under the [GitHub General Privacy
Statement](https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement).
Downloaded data is digitally signed and checked before it is used.

## 7. Sharing

The data in sections 2 and 3 goes to Google, which provides those services; for ads, Google may
share the data in section 2 further under the Google policy linked there. Song requests and feedback
emails reach only us. Apart from the IP address GitHub sees when the app downloads data (section 6),
we send your data to no one else, and we do not sell it.

## 8. Security

All data sent by the Google SDKs, every song request and every song data download travel over
encrypted connections.

## 9. Children

Lời Vọng Cổ is not directed at children under 13. We do not knowingly collect data from children
under 13.

## 10. Your rights

Because the app has no accounts, we have no way to link the data in sections 2 and 3 to a particular
person, so we cannot look up your data to delete it on request. You stay in control: clear your
history or all data on your device (section 1), reset your advertising ID (section 2), and turn off
automatic downloads (section 6). To have a song request or feedback email deleted, or for any other
question, write to us at the address in section 12.

## 11. Changes to this policy

When this policy changes, we update this page and the effective date at the top.

## 12. Contact

HaDoSolution — hadosolution@gmail.com
