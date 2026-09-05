# WinUltimak

Bộ tiện ích nhỏ gọn cho Windows, gom những thứ bạn hay phải làm thủ công vào một chỗ: chỉnh âm lượng, xem giờ, giảm chói màn hình lúc đêm, ném cửa sổ sang màn hình khác, và sắp xếp lại đám ứng dụng tự chạy khi bật máy.

WinUltimak chạy nền, nằm im dưới khay hệ thống, và chỉ xuất hiện khi bạn cần.

**Tải bản mới nhất:** [github.com/kienkmaster/WinUltimak-Release/releases/latest](https://github.com/kienkmaster/WinUltimak-Release/releases/latest)

---

## Mục lục

- [WinUltimak là gì](#winultimak-là-gì)
- [Các tiện ích](#các-tiện-ích)
- [Cài đặt chung](#cài-đặt-chung)
- [Yêu cầu hệ thống](#yêu-cầu-hệ-thống)
- [Tải về và chạy](#tải-về-và-chạy)
- [Kiểm tra file tải về](#kiểm-tra-file-tải-về)
- [Cấu hình được lưu ở đâu](#cấu-hình-được-lưu-ở-đâu)
- [Gỡ bỏ](#gỡ-bỏ)
- [Câu hỏi thường gặp](#câu-hỏi-thường-gặp)
- [Thư viện và thành phần bên thứ ba](#thư-viện-và-thành-phần-bên-thứ-ba)
- [Giấy phép](#giấy-phép)
- [Miễn trừ trách nhiệm](#miễn-trừ-trách-nhiệm)
- [Nhãn hiệu](#nhãn-hiệu)

---

## WinUltimak là gì

Windows có sẵn khá nhiều thứ, nhưng phần lớn nằm rải rác: âm lượng ở một góc, độ sáng ở nơi khác, danh sách ứng dụng khởi động thì chia làm mấy chỗ mà không chỗ nào nói cho bạn biết cái nào chạy trước cái nào. WinUltimak sinh ra để gom những việc vặt đó lại.

Toàn bộ ứng dụng chỉ là **một file `WinUltimak.exe` duy nhất**. Không cần cài đặt, không tạo entry trong Control Panel, không đụng vào thư mục hệ thống. Bạn chép nó vào đâu cũng chạy được, kể cả USB.

Mỗi tiện ích bên trong hoạt động độc lập. Bạn bật cái nào thì cái đó chạy; khi tắt, cửa sổ và tác vụ nền của tiện ích đó được dừng. Lần mở sau, WinUltimak tự khôi phục đúng những gì bạn đã bật.

Ứng dụng chỉ cho phép **một phiên bản chạy tại một thời điểm**. Nếu bạn lỡ bấm mở lần thứ hai, cửa sổ đang chạy sẽ hiện lên thay vì mở thêm một cái mới.

---

## Các tiện ích

### 1. Thanh âm lượng nổi (Window Volume Bar)

Một thanh âm lượng luôn nổi trên màn hình, kéo thả đặt ở đâu tùy bạn. Không cần rê chuột xuống khay hệ thống, không cần chờ popup của Windows hiện ra rồi tự tắt.

Thao tác:

| Thao tác | Kết quả |
|---|---|
| Cuộn chuột trên thanh | Tăng hoặc giảm âm lượng |
| `Ctrl` + cuộn | Phóng to hoặc thu nhỏ thanh |
| Giữ `Shift` | Xem mức trong suốt hiện tại |
| `Shift` + cuộn | Chỉnh mức trong suốt |

Thanh đọc trực tiếp mức âm lượng từ thiết bị phát mặc định của Windows, nên nếu bạn chỉnh âm lượng bằng phím trên bàn phím hay bằng thanh trượt của hệ thống, nó cũng cập nhật theo ngay lập tức. Đổi tai nghe hay loa giữa chừng cũng không cần khởi động lại.

Màu sắc, kiểu hiển thị và kích thước đều chỉnh được, và được nhớ lại cho lần sau.

### 2. Đồng hồ và lịch (Modern Date Clock)

Một đồng hồ nổi hiển thị giờ và ngày, đặt ở góc nào bạn thích. Hữu ích khi bạn hay làm việc toàn màn hình và thanh taskbar bị che mất.

Thao tác:

| Thao tác | Kết quả |
|---|---|
| `Ctrl` + cuộn | Phóng to hoặc thu nhỏ đồng hồ |
| Giữ `Shift` | Xem mức trong suốt hiện tại |
| `Shift` + cuộn | Chỉnh mức trong suốt |
| `Alt` + cuộn lên/xuống | Chuyển sang kiểu hiển thị kế tiếp hoặc trước đó |

Có nhiều kiểu hiển thị để chọn, từ dạng số bảy đoạn kiểu đồng hồ điện tử cho tới các kiểu chữ hiện đại hơn. Màu của từng thành phần (giờ, phút, ngày, viền) chỉnh riêng được.

### 3. Giảm sáng màn hình (Screen Dimmer)

Có những lúc màn hình đã kéo độ sáng xuống mức thấp nhất mà vẫn chói, nhất là khi làm việc buổi tối trong phòng tối. Tiện ích này phủ thêm một lớp giảm sáng lên trên, đưa màn hình xuống tối hơn mức phần cứng cho phép.

Mức giảm sáng đi theo các nấc **10%, 20%, 30%, 40%, 50%, 60%, 70% và 80%**. Bạn chọn những nấc mình thật sự dùng, rồi gán phím tắt toàn cục để nhảy qua lại giữa chúng mà không cần mở cửa sổ nào.

Kèm theo là một thanh hiển thị mức sáng nổi trên màn hình, để bạn biết mình đang ở nấc nào. Thanh này có thể tắt đi nếu thấy vướng.

Lưu ý: lớp giảm sáng nằm đè lên toàn bộ màn hình, nhưng không cản trở thao tác. Bạn vẫn click, gõ, kéo thả bình thường xuyên qua nó.

### 4. Dịch chuyển ứng dụng theo đa màn hình (Multi Monitor Mover)

Dành cho ai dùng từ hai màn hình trở lên. Thay vì kéo cửa sổ bằng chuột từ màn hình này sang màn hình kia, bạn bấm một phím tắt và cửa sổ đang làm việc nhảy sang màn hình bên cạnh, giữ nguyên trạng thái phóng to hay kích thước cũ.

Bạn có thể gán phím tắt riêng cho từng hướng, hoặc chỉ định thẳng một màn hình đích cụ thể. Danh sách màn hình được nhận diện theo thiết bị thật, nên khi bạn rút ra cắm vào hay đổi thứ tự màn hình trong Windows, cấu hình vẫn trỏ đúng chỗ.

### 5. Quản lý khởi động (Startup Manager)

Đây là phần "nặng ký" nhất của WinUltimak.

Windows lưu danh sách ứng dụng tự khởi động ở nhiều nơi khác nhau, và không nơi nào cho bạn quyết định thứ tự hay khoảng cách giữa chúng. Kết quả quen thuộc: vừa đăng nhập xong là mười mấy ứng dụng đồng loạt bung ra, máy đơ mất vài phút.

Startup Manager gom các cấu hình đó vào từng profile. Mỗi profile có thể mở một file, một thư mục hoặc thực thi Command Line bằng **Command Prompt** hay **Windows PowerShell 5.1**. Bạn có thể chọn một trong các cách xử lý sau:

- **Không đăng ký** — giữ profile và dữ liệu đã nhập nhưng gỡ các đăng ký startup thuộc profile khi bấm Save.
- **Khởi động theo bộ tiện ích** — WinUltimak mở file hoặc thư mục theo đúng thứ tự và độ trễ đã đặt.
- **Khởi động cùng Windows** — ghi cấu hình vào Registry Run của tài khoản hiện tại.
- **Tạo startup trong Start Menu** — tạo shortcut trong thư mục Startup của tài khoản hiện tại.
- **Tạo Task Scheduler khởi động** — tạo tác vụ Windows với action, tham số và thư mục `Start in` riêng. Command Line chỉ được đăng ký bằng chế độ này.

Với chế độ khởi động theo WinUltimak, mỗi profile có một khoảng chờ riêng, tính bằng mili giây, giây, phút hoặc giờ, tối đa một tiếng. Nhờ vậy bạn có thể xếp trình duyệt chạy trước, phần mềm đồng bộ đám mây chạy sau ba mươi giây, và các công cụ nặng để cuối cùng.

Task Scheduler cho phép chọn **Không điều kiện** để chỉ chạy thủ công, chạy theo lịch một lần/hằng ngày/hằng tuần/hằng tháng, chạy khi đăng nhập hoặc chạy khi Windows khởi động. Task có thể dùng account đang đăng nhập hoặc credential Windows; mật khẩu chỉ được chuyển cho Task Scheduler lúc Save và không được lưu trong `settings.json`.

Các chế độ thông thường hoạt động trong phạm vi tài khoản hiện tại và không cần quyền quản trị. Trigger **At startup** chạy từ lúc Windows khởi động nên WinUltimak sẽ yêu cầu xác nhận UAC và khởi động lại với quyền administrator để đăng ký.

---

## Cài đặt chung

Mở bằng biểu tượng khay hệ thống, chọn **Cài đặt**.

**Giao diện.** Bốn lựa chọn: *System*, *Light*, *Dark* và *Dark Gold*. Chọn *System* thì WinUltimak bám theo chế độ sáng/tối của Windows, và tự đổi ngay khi bạn đổi trong Settings của hệ điều hành mà không cần khởi động lại.

**Khởi động cùng Windows.** Bật lên thì WinUltimak tự chạy khi bạn đăng nhập. Mục này ghi vào khóa khởi động của riêng tài khoản bạn, không cần quyền quản trị.

**Luôn ẩn cửa sổ chính.** Bật lên thì mỗi lần mở, WinUltimak chỉ hiện biểu tượng dưới khay hệ thống chứ không bung cửa sổ ra. Phù hợp khi bạn đã cấu hình xong xuôi và chỉ muốn nó chạy nền.

**Khay hệ thống.** Click trái vào biểu tượng để mở cửa sổ chính. Click phải cho menu gồm *Mở WinUltimak*, *Cài đặt* và *Thoát*. Lối duy nhất để đóng hẳn ứng dụng là *Thoát* trong menu này — bấm nút đóng ở cửa sổ chính chỉ thu nó về khay.

---

## Yêu cầu hệ thống

| Hạng mục | Yêu cầu |
|---|---|
| Hệ điều hành | Windows 10 hoặc Windows 11, bản 64-bit |
| Kiến trúc | x64 |
| .NET Runtime | Không cần cài. Bản phát hành đã đóng gói sẵn mọi thứ bên trong |
| Quyền quản trị | Không cần trong sử dụng thông thường; trigger Task Scheduler `At startup` cần xác nhận UAC khi đăng ký |
| Dung lượng | Gói tải về khoảng 60 MB |

File thực thi lớn hơn mức thông thường vì nó mang theo toàn bộ nền tảng chạy bên trong. Đổi lại, bạn không phải cài thêm bất cứ thứ gì.

---

## Tải về và chạy

Tải bản phát hành chính thức mới nhất tại:

**➜ [github.com/kienkmaster/WinUltimak-Release/releases/latest](https://github.com/kienkmaster/WinUltimak-Release/releases/latest)**

Các bước:

1. Tải file `WinUltimak_v<phiên bản>.zip` cùng file `.sha256` đi kèm.
2. Giải nén ra một thư mục bạn định để lâu dài, ví dụ `D:\Tools\WinUltimak`. Tránh giải nén thẳng trong `Downloads` vì cấu hình sẽ nằm chung ở đó.
3. Chạy `WinUltimak.exe`.

Lần đầu chạy, Windows SmartScreen có thể hiện cảnh báo vì file chưa có chữ ký số thương mại. Bấm **More info** rồi **Run anyway** nếu bạn đã đối chiếu mã băm ở bước dưới.

Nâng cấp lên bản mới: thoát WinUltimak khỏi khay hệ thống, thay file `WinUltimak.exe` cũ bằng file mới, chạy lại. Cấu hình của bạn nằm ở file riêng nên vẫn còn nguyên.

---

## Kiểm tra file tải về

Mỗi bản phát hành đều đi kèm mã băm SHA-256 để bạn xác nhận file tải về đúng là file gốc, không bị sửa đổi trên đường truyền.

Mở PowerShell tại thư mục chứa file ZIP và chạy:

```powershell
$zip = Get-ChildItem -LiteralPath . -Filter 'WinUltimak_v*.zip' | Select-Object -First 1
Get-FileHash -Algorithm SHA256 -LiteralPath $zip.FullName
```

So chuỗi hiện ra với nội dung trong file `.sha256` đi kèm. Hai chuỗi phải trùng khớp hoàn toàn. Nếu lệch, đừng chạy file đó — hãy tải lại.

---

## Cấu hình được lưu ở đâu

WinUltimak lưu toàn bộ thiết lập vào file **`settings.json`**, đặt **ngay cạnh file `WinUltimak.exe`**.

Cách này có hai cái lợi: bạn chép cả thư mục sang máy khác là mang theo nguyên vẹn cấu hình, và khi muốn làm lại từ đầu thì chỉ cần xóa đúng một file.

Vì vậy hãy đặt WinUltimak ở thư mục mà tài khoản của bạn có quyền ghi. Để trong `C:\Program Files` sẽ khiến ứng dụng không lưu được cấu hình.

Các đăng ký sau nằm ngoài file này, do bản chất của chúng thuộc về hệ điều hành:

- Trạng thái **Khởi động cùng Windows** ghi tại `HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Run`.
- Các profile chạy qua Registry tạo value có tiền tố `WinUltimak_` trong cùng khóa Run của tài khoản hiện tại.
- Các shortcut do Startup Manager tạo nằm trong thư mục Startup của tài khoản hiện tại.
- Các task do Startup Manager tạo nằm trong Task Scheduler Library và mang metadata sở hữu của WinUltimak.

---

## Gỡ bỏ

Không có trình gỡ cài đặt, vì cũng không có trình cài đặt.

1. Mở WinUltimak, vào **Cài đặt**, tắt **Khởi động cùng Windows**.
2. Mở **Quản lý khởi động**, chọn **Không đăng ký** rồi Save cho từng profile để gỡ các đăng ký Registry, Start Menu, Task Scheduler và hàng đợi của WinUltimak.
3. Thoát ứng dụng từ menu khay hệ thống.
4. Xóa thư mục chứa `WinUltimak.exe` và `settings.json`.

Xong. Không còn dấu vết nào trong Registry hay thư mục hệ thống.

---

## Câu hỏi thường gặp

**WinUltimak có gửi dữ liệu đi đâu không?**
Không. Ứng dụng không kết nối mạng, không thu thập số liệu sử dụng, không tự kiểm tra cập nhật. Mọi thứ diễn ra trên máy bạn.

**Có cần chạy bằng quyền Administrator không?**
Không trong sử dụng thông thường. Khi bạn chọn trigger Task Scheduler **At startup**, WinUltimak sẽ yêu cầu xác nhận UAC vì Windows cần quyền administrator để đăng ký kiểu khởi động này.

**Tại sao file EXE nặng hơn 100 MB?**
Vì nó gói sẵn nền tảng chạy bên trong để bạn không phải cài thêm gì. Dung lượng trên đĩa lớn, nhưng bộ nhớ khi chạy thì vẫn nhẹ.

**Bật tiện ích rồi tắt đi có tốn tài nguyên không?**
Không. Khi bạn tắt một tiện ích, cửa sổ và các tài nguyên hệ thống nó giữ đều được giải phóng hoàn toàn.

**Giảm sáng màn hình có ảnh hưởng đến ảnh chụp màn hình hay chia sẻ màn hình không?**
Lớp giảm sáng là một lớp phủ trên desktop, nên tùy công cụ chụp mà nó có xuất hiện trong ảnh hay không. Nếu cần màu chuẩn để làm việc với hình ảnh, hãy tắt tiện ích này.

**Phím tắt bị trùng với ứng dụng khác thì sao?**
Khi WinUltimak không đăng ký được một tổ hợp phím vì ứng dụng khác đã giữ, nó sẽ báo ngay tại dòng cấu hình để bạn chọn tổ hợp khác.

---

## Thư viện và thành phần bên thứ ba

WinUltimak được viết bằng C# trên nền **.NET 9** với giao diện **WPF**, và cố ý giữ số lượng phụ thuộc ở mức tối thiểu.

### Gói phần mềm đi kèm trong bản phát hành

| Thành phần | Phiên bản | Nhà phát hành | Giấy phép |
|---|---|---|---|
| .NET Runtime & WPF | 9.0 | Microsoft | MIT |
| System.Drawing.Common | 9.0.5 | Microsoft | MIT |

Chỉ có vậy. Không có thư viện giao diện của bên thứ ba, không có framework MVVM ngoài, không có SDK quảng cáo hay phân tích hành vi nào được nhúng vào.

### Thành phần chỉ dùng khi phát triển

Hai gói dưới đây phục vụ việc kiểm thử tự động, **không** có mặt trong file phát hành tới người dùng:

| Thành phần | Phiên bản | Giấy phép |
|---|---|---|
| MSTest | 3.6.4 | MIT |
| Microsoft.NET.Test.Sdk | 17.12.0 | MIT |

### Giao diện lập trình có sẵn của Windows

Một số tính năng phải gọi trực tiếp xuống hệ điều hành. Đây là các thành phần sẵn có của Windows, không phải thư viện được đóng gói kèm:

| Thành phần | Dùng cho |
|---|---|
| `user32.dll` | Phím tắt toàn cục, quản lý cửa sổ, nhận diện màn hình |
| `gdi32.dll` | Vẽ và lấy màu điểm ảnh |
| `Magnification.dll` | Lớp phủ giảm sáng màn hình |
| Core Audio API | Đọc và điều chỉnh âm lượng thiết bị phát |
| Windows Shell | Đọc và ghi shortcut trong thư mục Startup |
| Windows Registry | Trạng thái khởi động cùng Windows và chế độ sáng/tối của hệ thống |

---

## Giấy phép

WinUltimak được phát hành theo **Giấy phép MIT**.

```
MIT License

Copyright (c) 2026 Kmaster Kien Nguyen
```

Nói gọn lại, giấy phép MIT cho phép bạn:

- Sử dụng phần mềm cho mục đích cá nhân hay thương mại, miễn phí.
- Sao chép và phân phối lại cho người khác.
- Chỉnh sửa và tạo ra phiên bản riêng của mình.

Với một điều kiện duy nhất: giữ lại thông báo bản quyền và nội dung giấy phép trong mọi bản sao hay phần đáng kể của phần mềm.

Nội dung đầy đủ nằm ở file [`LICENSE`](LICENSE) trong repository này, và cũng được đóng gói kèm trong mỗi bản phát hành.

---

## Miễn trừ trách nhiệm

Xin đọc kỹ phần này trước khi sử dụng.

WinUltimak được cung cấp **"nguyên trạng"** (*as is*), không kèm theo bất kỳ bảo đảm nào, dù là bảo đảm rõ ràng hay ngầm định. Điều này bao gồm nhưng không giới hạn ở các bảo đảm về khả năng thương mại, về sự phù hợp cho một mục đích cụ thể, và về việc không xâm phạm quyền của bên thứ ba.

Trong mọi trường hợp, **tác giả và người giữ bản quyền không chịu trách nhiệm** đối với bất kỳ khiếu nại, thiệt hại hay nghĩa vụ pháp lý nào phát sinh từ phần mềm hoặc từ việc sử dụng phần mềm.

Cụ thể hơn, người dùng cuối cần lưu ý:

**Bạn tự chịu rủi ro khi sử dụng.** Phần mềm này là một dự án cá nhân, không phải sản phẩm thương mại có đội ngũ hỗ trợ. Không có cam kết về thời gian phản hồi, về việc sửa lỗi, hay về việc tiếp tục phát triển.

**Về tính năng quản lý khởi động.** Startup Manager thay đổi cách các ứng dụng khác khởi động trên máy bạn. Cấu hình sai có thể khiến một phần mềm bạn đang cần không chạy lên đúng lúc, hoặc chạy sai thứ tự mong đợi. Hãy ghi lại cấu hình gốc trước khi thay đổi, và kiểm tra lại sau khi khởi động máy. Tác giả không chịu trách nhiệm cho công việc bị gián đoạn vì lý do này.

**Về tính năng giảm sáng màn hình.** Lớp phủ giảm sáng làm thay đổi màu sắc bạn nhìn thấy. Không dùng tính năng này khi đang làm việc đòi hỏi màu chính xác, như chỉnh ảnh, thiết kế in ấn hay kiểm tra màu sản phẩm. Việc nhìn màn hình quá tối trong thời gian dài cũng có thể gây mỏi mắt; hãy tự điều chỉnh cho phù hợp với mắt mình.

**Về trách nhiệm sao lưu.** Hãy tự sao lưu dữ liệu và cấu hình quan trọng của bạn. Phần mềm không tự sao lưu giúp bạn, và không có cơ chế khôi phục về trạng thái trước đó.

**Về môi trường doanh nghiệp.** Nếu máy tính của bạn do bộ phận công nghệ thông tin của cơ quan quản lý, hãy xin phép trước khi cài đặt và sử dụng. Một số chính sách bảo mật có thể cấm các phần mềm can thiệp vào cấu hình khởi động hoặc phím tắt toàn cục.

**Về việc tải phần mềm.** Chỉ tải WinUltimak từ trang phát hành chính thức được nêu trong tài liệu này, và luôn đối chiếu mã băm SHA-256 trước khi chạy. Tác giả không chịu trách nhiệm với các bản sao được phân phối lại từ nguồn khác.

Việc bạn tải về và sử dụng WinUltimak được xem là bạn đã đọc, hiểu và chấp nhận toàn bộ các điều khoản nêu trên.

---

## Nhãn hiệu

WinUltimak là một dự án độc lập. Dự án không có liên kết với, không được ủy quyền bởi, không được tài trợ bởi và không được chứng thực bởi Microsoft Corporation.

Microsoft và Windows là nhãn hiệu của nhóm công ty Microsoft. Mọi nhãn hiệu khác được nhắc đến thuộc về chủ sở hữu tương ứng của chúng.

---

<sub>WinUltimak · Bản phát hành: [github.com/kienkmaster/WinUltimak-Release](https://github.com/kienkmaster/WinUltimak-Release) · Giấy phép MIT · © 2026 Kmaster Kien Nguyen</sub>
