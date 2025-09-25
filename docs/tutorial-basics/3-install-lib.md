---
sidebar_position: 3
---

# Cài đặt thư viện

Cài đặt thư viện để sử dụng đầy đủ tính năng của ứng dụng

## 1. Thư viện tạo lyric

Thư viện sẽ chuyển đổi *video, audio* <i class="fa-solid fa-arrow-right"></i> *text* dạng file `.srt` format

- Download
    - Download thư viện ở **[Lyric driver](https://drive.google.com/file/d/1fbsjYrpJGJD2tYhNZSyUsWi8jmZbSeDS/view)**
    - Giải nén file vừa download
- Cài đặt
    - Vào project bất kỳ, ở thành Menu tìm đến **Công cụ** -> **Nhận diện lyric**
    - Chọn đến file `lyric_.exe` ở thư mục vừa giải nén

![Lyric](/img/lib/lyric.png)

#### *Hình 1 - Giao diện thư viện get lyric*

## 2. Thư viện clone audio

- Download
    - Download thư viện ở **[clone driver](https://drive.google.com/file/d/1nNkbe6iX3K-JzWOKErvDmQYR5wABDBMM/view)**
    - Giải nén file vừa download
- Cài đặt
    - Vào project bất kỳ, ở thành Menu tìm đến **Công cụ** -> **Voice clone**
    - Chọn đến thư mục vừa giải nén
- Thêm các giọng clone
    - Tải các giọng clone ở dạng file `.zip` ở các link sau **[web](https://voice-models.com/)** hoặc **[model driver](https://drive.google.com/drive/folders/1ur5F2J7mP2g6AAdrJde96UPxywDLQOs7)**
    - Sau khi download xong, vào cửa sổ vừa mở (hình 2), nhấn **Thêm** và chọn đến các đường dẫn file vừa download
    - Chọn ngôn ngữ của giọng vừa download và sửa tên phù hợp để dễ dàng sử dụng

![VoiceClone](/img/lib/voice-clone.png)

#### *Hình 2 - Giao diện thư viện voice clone*

## 3. Thư viện tách vocal

- Cài đặt
    - Vào project bất kỳ hoặc ở của sổ lúc mới đăng nhập, ở thành Menu tìm đến **Công cụ** -> **Tách vocal**
    - Cửa sổ tách vocal hiện ra (hình 3), vào **Công cụ** -> **Cài đặt manual**
    - Chương trình sẽ ghi xuống 1 file `remove_vocal.bat` vào máy tính
    - Mở terminal tại thư mục, gõ tên `remove_vocal.bat` và Enter
    - Chạy ít nhất 1 lần cho đến khi báo thành công
    - Khởi động lại máy tính, tìm đến cửa sổ Tách Vocal. Ở phía dưới cửa sổ, có button ***Bắt đầu xử lý*** là đã cài đặt thành công

![RemoveVocal](/img/lib/remove-vocal.png)

#### *Hình 3 - Giao diện thư viện tách vocal*

:::tip[Mẹo]
- Bạn nên cài đặt thư viện trong ổ đĩa **SSD** để quá trình render được nhanh hơn
:::