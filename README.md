# INT3303, mô phỏng tương tác

Trang tĩnh dùng kèm bài giảng môn Mạng không dây, Trường Đại học Công nghệ, ĐHQGHN.

Repo: https://github.com/tkvmai/int3303-pages

## Địa chỉ công khai

- Mục lục: https://tkvmai.github.io/int3303-pages/

Mọi mô phỏng đều có thẻ trong mục lục, nên chỉ cần dán địa chỉ mục lục cho sinh viên.
Slide thì trỏ thẳng vào từng trang theo đường dẫn trong mục Cấu trúc dưới đây.

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
index.html                                 mục lục, là trang sinh viên vào đầu tiên
.nojekyll                                  tắt bộ xử lý Jekyll, phục vụ file y nguyên

buoi02/song-va-ba-thuoc-tinh.html          sáu mô phỏng về sóng, dùng ở Tiết 1
buoi02/tu-truong-bien-thien.html           cảm ứng Faraday, có núm vặn tương tác
buoi02/dien-truong-bien-thien.html         chiều ngược lại của cặp phương trình
buoi02/dung-yen-chay-deu-dao-dong.html     ba trạng thái của điện tích
buoi02/vet-gay-cua-duong-suc.html          dựng sóng theo cách của Thomson và Purcell
buoi02/chenh-lech-giua-hai-cho.html        chênh lệch theo không gian và biến thiên theo thời gian
buoi02/vi-sao-song-tu-lan-ra-xa.html       vì sao sóng tự duy trì khi đi xa
buoi02/ba-cach-bien-doi-song-mang.html     ASK, FSK, PSK trên cùng một dãy bit, dùng ở Tiết 2
buoi02/chom-sao-va-mat-phang-iq.html       chòm sao BPSK, QPSK, 4-ASK, 16-QAM, dùng ở Tiết 3

lab/index.html                             mục lục riêng cho các bài thực hành
lab/tu-day-bit-toi-tin-hieu-dieu-che.html  Phần 1, dãy bit thành NRZ rồi thành OOK, BPSK, BFSK
lab/pho-bien-do-va-bang-thong.html         Phần 2, phổ biên độ và phép đo băng thông búp chính
lab/dieu-che-16-qam.html                   Phần 3, bốn bit thành một điểm trên chòm sao
lab/ghep-kenh-theo-tan-so.html             Phần 4, ba kênh 16-QAM ghép trên một đường truyền
```

Mỗi file HTML là một trang độc lập, đã nhúng sẵn toàn bộ CSS và JavaScript bên trong,
không gọi ra mạng ngoài. Nhờ vậy mở được cả khi không có Internet, và không hỏng khi
một thư viện bên thứ ba nào đó ngừng hoạt động.

## Bản gốc

Thư mục này là bản sao để xuất bản. Bản làm việc nằm ở thư mục cha `Bo slide 15 buoi`,
với tên tiếng Việt đầy đủ dạng `Demo Buoi 02 Tiet 2 - ...`. Khi sửa bản làm việc thì chép
đè sang đây rồi mới đẩy lên.

Hai bản phải khớp nhau. Nếu chỉ sửa một bên thì slide và trang công bố sẽ nói khác nhau,
và đó là loại sai khó phát hiện nhất vì không có cổng kiểm nào bắt được.
