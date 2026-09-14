# INT3303, mô phỏng tương tác

Trang tĩnh dùng kèm bài giảng môn Mạng không dây, Trường Đại học Công nghệ, ĐHQGHN.

## Cách đưa lên GitHub Pages

Làm một lần, sau này chỉ cần kéo thả file mới.

1. Đăng nhập github.com, bấm dấu cộng góc trên bên phải, chọn **New repository**.
2. Đặt **Repository name** là `int3303`. Chọn **Public** (Pages miễn phí yêu cầu repo công khai).
   Không tick thêm README nào cả, vì thư mục này đã có sẵn.
3. Repo mới hiện ra một trang trống. Bấm **uploading an existing file**.
4. Kéo toàn bộ nội dung *bên trong* thư mục `int3303-pages` vào ô upload, gồm `index.html`,
   thư mục `buoi02`, và file `.nojekyll`. Lưu ý kéo phần bên trong, đừng kéo cả thư mục cha,
   nếu không đường dẫn sẽ thừa một cấp.
5. Bấm **Commit changes**.
6. Vào tab **Settings**, cột trái chọn **Pages**. Mục Source chọn **Deploy from a branch**,
   Branch chọn `main` và thư mục `/ (root)`. Bấm **Save**.
7. Đợi khoảng một tới hai phút. Link sẽ là:

   `https://<tên tài khoản github>.github.io/int3303/`

   Trang mô phỏng Faraday nằm ở:

   `https://<tên tài khoản github>.github.io/int3303/buoi02/tu-truong-bien-thien.html`

## Dán link vào slide

Dùng link ngắn ở mục lục (`.../int3303/`) cho slide mở đầu, và link thẳng tới từng trang
cho slide tương ứng. Link này không hết hạn, không cần đăng nhập, và thuộc quyền quản lý
của tài khoản GitHub chứ không phụ thuộc nền tảng nào khác.

Nếu muốn link ngắn hơn nữa thì đặt tên repo là `<tên tài khoản>.github.io`, khi đó địa chỉ
rút còn `https://<tên tài khoản>.github.io/buoi02/...`. Đổi lại, mỗi tài khoản chỉ có một
repo kiểu này, nên nó chiếm mất chỗ nếu sau này anh cần trang cá nhân riêng.

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
