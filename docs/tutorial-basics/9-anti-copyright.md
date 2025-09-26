---
sidebar_position: 9
---

# Anti CR

Thêm filter cho **video dọc** -> **video ngang**

![Anti](/img/anti/anti-ui.png)

#### *Hình 1 - Giao diện tạo video rewrite*

## 1. Cắt video
### 1.1. Cắt nhỏ
    - Chương trình sẽ cắt video gốc thành các chuỗi video nhỏ dài **180s, 30s** liên tiếp nhau
    - Thời gian cắt này có thể chỉnh sửa ở phần cài đặt
    - click vào menu **Video** -> **Cắt nhỏ**
### 1.2. Edit filter
    - Opacity
        - Chỉnh sửa độ mờ của video gốc
    - Zoom
        - Tỉ lệ zoom
        - Vị trí zoom
    - Mask
        - Chọn loại mặt nạ: rectangle, circle triangle ...
        - Chọn kích thước
        - Chọn màu

## 2. Cài đặt chung

- Custom độ dài của video ngắn, dài
- Điều chỉnh hệ số zoom của layer nền

:::note
- Chương trình sẽ lấy chính video gốc làm layer nền
- Nếu chương trình chạy tốn nhiều RAM (Vào Task Manager để kiểm tra) <i class="fa-solid fa-arrow-right"></i> Hãy giảm hệ số zoom của layer nền
:::

## 3. Export video
    - Chọn sử dụng GPU hoặc không
    - ~~Tách vocal~~ (không khả dụng ở template này)

    ![Lyric](/img/common/export-video.png)

    **Hình 3 - Cửa sổ export video**

## 4. Ví dụ


<iframe width="560" height="315"
  src="https://www.youtube.com/embed/2Hs7mIcwHiY"
  title="YouTube video player"
  frameborder="0"
  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
  allowfullscreen>
</iframe>