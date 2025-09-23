---
sidebar_position: 5
---

# Thuyết minh phim

Dịch và lồng tiếng phim từ ngôn ngữ này <i class="fa-solid fa-arrow-right"></i> ngôn ngữ khác

![Lyric](/img/thuyetminh/thuyet-minh.png)

#### *Hình 1 - Giao diện template thuyết minh phim*

## I. Dịch phim

### 1. Lấy lyric 
    - Tự động
        - Ở Menu **Lyric gốc** -> **Tạo tự động**. Thư viện sẽ tạo generate ra file `.srt` và tự động import vào project
    - Upload từ máy tính
        - Ở Menu **Lyric gốc** -> **Upload từ máy tính**
:::note    
Chương trình sẽ xóa bỏ 1 số dòng bị duplicate <i class="fa-solid fa-arrow-right"></i> tránh audio bị đè lên nhau
:::
### 2. Dịch
    - Dịch tự động: **Lyric dịch** -> **Dịch**
        - Chat GPT (Recommend)
        - Microsoft
    - Tải từ máy tính: **Lyric dịch** -> **Upload từ máy tính**
        
:::note    
Sau khi dịch, bạn cần review lại bản dịch để confirm lại
- Check lại ngôn ngữ bản dịch nếu bị dịch sai (Vào menu *Lyric dịch* <i class="fa-solid fa-arrow-right"></i> *So sánh*)
- Tìm kiếm và thay thế (Vào menu *Lyric dịch* <i class="fa-solid fa-arrow-right"></i> *Tìm kiếm và thay thế*)
:::

## II. Lồng tiếng

### 1. Tải audio 

    - Click vào item ở hình 1, ở trường **Chọn giọng TTK**, click vào ⋮ và áp dụng cho *tất cả* hoặc chọn *các item* tùy ý
    - Có thể chọn clone sau khi tạo audio
    - Menu **Audio** -> **Download Audio**
    - Tải audio: bạn có thể chọn tốc độ phù hợp với giọng nói ở phim để download

    ![download-audio](/img/common/download-audio.png)

    **Hình 2 - Cửa sổ download audio**

:::tip    
- Nếu tốc độ đọc của phim gốc nhanh, bạn cần chọn tốc độ cao khi download
- Ở phía dưới - trái <i class="fa-solid fa-arrow-right"></i> trạng thái phần trăm (%) số lượng item đã được dịch và số lượng item có audio
:::

### 2. Export video
- Chọn option xử lý audio (Ở phần *Cài đặt chung* trên hình 1)
    - Mặc định
    - Tự điều chỉnh tốc độ âm thanh
    - Cắt phần âm thanh bị đè
    - Kéo dãn video
    - Tự động kéo dãn video và âm thanh
    - Tự động điều chỉnh âm thanh
- Export
    - Chọn sử dụng GPU hoặc không
    - Tách vocal nếu muốn loại bỏ tiếng gốc của phim

![export-video](/img/common/export-video.png)

**Hình 3 - Cửa sổ export video**


## III. Ví dụ ngắn


<iframe width="560" height="315"
  src="https://www.youtube.com/embed/TYUVUn29FuY"
  title="YouTube video player"
  frameborder="0"
  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
  allowfullscreen>
</iframe>