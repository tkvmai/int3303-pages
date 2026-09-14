# INT3303, mô phỏng tương tác

Trang tĩnh dùng kèm bài giảng môn Mạng không dây, Trường Đại học Công nghệ, ĐHQGHN.

Repo: https://github.com/tkvmai/int3303-pages

## Địa chỉ công khai

- Mục lục: https://tkvmai.github.io/int3303-pages/
- Cảm ứng Faraday: https://tkvmai.github.io/int3303-pages/buoi02/tu-truong-bien-thien.html
- Sóng và ba thuộc tính: https://tkvmai.github.io/int3303-pages/buoi02/song-va-ba-thuoc-tinh.html

Link không hết hạn, không cần đăng nhập, thuộc quyền quản lý của tài khoản GitHub.

## Bật GitHub Pages

Chỉ làm một lần. Vào https://github.com/tkvmai/int3303-pages/settings/pages, mục Source
chọn **Deploy from a branch**, Branch chọn `main` và thư mục `/ (root)`, bấm **Save**.
Đợi một tới hai phút. Repo phải để **Public** thì Pages mới chạy ở gói miễn phí.

Nếu sau này muốn địa chỉ ngắn hơn thì đổi tên repo thành `tkvmai.github.io`, khi đó
địa chỉ rút còn `https://tkvmai.github.io/buoi02/...`. Đổi lại, mỗi tài khoản chỉ có một
repo kiểu này, nên nó chiếm mất chỗ nếu sau này cần trang cá nhân riêng. Đổi tên repo
cũng làm hỏng mọi link đã dán vào slide, nên cân nhắc trước khi phát tài liệu cho sinh viên.

## Cập nhật về sau

Vào repo, mở đúng file, bấm biểu tượng bút chì để sửa, hoặc dùng **Add file > Upload files**
để ghi đè bản mới. Trang web tự cập nhật sau khoảng một phút.

## Cấu trúc

```
index.html                              mục lục, là trang sinh viên vào đầu tiên
buoi02/tu-truong-bien-thien.html        cảm ứng Faraday, có núm vặn tương tác
buoi02/song-va-ba-thuoc-tinh.html       sáu mô phỏng về sóng
.nojekyll                               tắt bộ xử lý Jekyll, phục vụ file y nguyên
```

Mỗi file HTML là một trang độc lập, đã nhúng sẵn toàn bộ CSS và JavaScript bên trong,
không gọi ra mạng ngoài. Nhờ vậy mở được cả khi không có Internet, và không hỏng khi
một thư viện bên thứ ba nào đó ngừng hoạt động.

## Bản gốc

Thư mục này là bản sao để xuất bản. Bản làm việc nằm cùng cấp, trong
`Bo slide 15 buoi`, với tên tiếng Việt đầy đủ. Khi sửa bản làm việc thì nhớ chép đè
sang đây rồi mới upload.
