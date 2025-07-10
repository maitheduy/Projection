
# Dự án Mô phỏng Phép chiếu (Projection)

Đây là repository chứa các mô phỏng HTML/JavaScript liên quan đến chủ đề phép chiếu trong không gian.

Trang chủ của dự án được đặt tại [https://maitheduy.github.io/Projection/](https://maitheduy.github.io/Projection/).

---

### Hướng dẫn cập nhật trang chủ khi có file mô phỏng mới

Trang chủ (`index.html`) được cập nhật thủ công để đảm bảo tính ổn định và tốc độ tải trang. Khi bạn có một file mô phỏng mới, hãy làm theo các bước sau để thêm nó vào trang chủ:

**Bước 1: Tải file mới lên**

*   Tải file `.html` mô phỏng mới của bạn vào thư mục `/data` trong repository này.

**Bước 2: Sửa file `index.html`**

*   Trong repository trên GitHub, tìm đến file `index.html` và nhấn vào biểu tượng cây bút chì (✏️ Edit this file) ở góc trên bên phải.

**Bước 3: Thêm dòng link mới**

*   Kéo xuống dưới và tìm đến khu vực có ghi chú `<!-- NƠI ĐỂ THÊM HOẶC SỬA CÁC LINK MÔ PHỎNG -->`.
*   Bạn sẽ thấy một danh sách các dòng có dạng `<a href="..." class="project-card">...</a>`.

**Bước 4: Sao chép, dán và sửa đổi**

*   **Sao chép (copy)** một dòng bất kỳ trong danh sách đó.
*   **Dán (paste)** nó vào một dòng mới.
*   **Chỉnh sửa** lại cho đúng với file mới của bạn theo mẫu:

    ```html
    <a href="data/TEN-FILE-CUA-BAN.html" class="project-card">TEN-HIEN-THI-BAN-MUON</a>
    ```

    *   `TEN-FILE-CUA-BAN.html`: là tên file chính xác bạn vừa tải lên thư mục `/data`.
    *   `TEN-HIEN-THI-BAN-MUON`: là chữ sẽ xuất hiện trong cái ô trên trang chủ.

**Ví dụ:**

Nếu bạn vừa tải lên file `HinhChieuVuongGoc.html`, bạn sẽ thêm dòng sau vào danh sách:

```html
<a href="data/HinhChieuVuongGoc.html" class="project-card">Hình Chiếu Vuông Góc</a>
```

**Bước 5: Lưu thay đổi**

*   Sau khi thêm xong, kéo xuống cuối trang và nhấn nút màu xanh "Commit changes".

Vậy là xong! Trang chủ sẽ được cập nhật với liên kết mới của bạn sau vài giây.
