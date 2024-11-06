<p align="center" >
REPOSITORY NÀY ĐỂ LÀM BÀI TẬP NHÓM KỸ THUẬT LẬP TRÌNH
</p>

<p align="center">
NHÓM 2 - KTLT :wave: :wave:
</p>


__CÀI ĐẶT GIT__ 

- Git là công cụ giúp bạn quản lý mã nguồn và đẩy code từ máy tính của bạn lên GitHub.
  - __Tải Git cho Windows__ : [**TẢI TẠI ĐÂY**](https://git-scm.com/downloads/win)
  - __Tải Git cho macOS__ : [**TẢI TẠI ĐÂY**](https://git-scm.com/downloads/mac)
 
---

__CẤU HÌNH GIT__

- Để Git nhận diện tên và email của bạn, bạn cần cấu hình tài khoản Git.
- Sau khi tải GIT xong thì mở `GIT BASH` lên và ghi
``` bash
git config --global user.name "Tên đăng nhập của bạn"
```
  + Ví dụ : git config --global user.name suplongv



``` bash
git config --global user.email "email@domain.com"
```
  + Ví dụ : git config --global user.email email@domain.com

---

__ĐẨY CODE TỪ REPOSITORY VỀ MÁY TÍNH__

- Tạo 1 thư mục folder để chứa những code này (**LƯU Ý : PHẢI SỬ DỤNG VSCODE ĐỂ DỄ PUSH CODE LÊN GITHUB**

- Vào __Terminal__ của [__VISUAL STUDIO CODE__](https://code.visualstudio.com/) và gõ lệnh (__LƯU Ý : PHẢI TRONG CÁI THƯ MỤC FOLDER ĐÃ TẠO TRƯỚC ĐÓ MỚI MỞ TERMINAL__)

- THEO THỨ TỰ TÔI ĐÃ ĐỀ RA NHÉ !  
```bash
  git clone https://github.com/suplongv/group-2-ktlt.git

  cd group-2-ktlt

  git branch -M main
```

---

- Sau khi xong tất cả bước trên thì __CHỈ LÀ BƯỚC ĐƯA CODE VỀ MÁY__

__TRƯỚC KHI CODE THÌ PHẢI LƯU Ý PULL CODE VỀ MÁY TRƯỚC RỒI MỚI CODE__

```bash
  git pull
```
- Lệnh này sẽ giúp bạn cập nhật những thay đổi mới nhất từ các thành viên khác trong nhóm, tránh xung đột khi đẩy code lên.

---

__CODE__

- Sau khi code xong phần của mình thì cứ ghi lệnh như sau

``` bash
  git add .

  git commit -m "ĐÂY LÀ NỘI DUNG GHI CHÚ MÌNH ĐÃ VIẾT GÌ TRONG CODE"

  git push
```

- Khi bạn thực hiện lệnh `git push`, Git sẽ đẩy thay đổi của bạn lên GitHub. Nếu Git yêu cầu bạn phải thực hiện thêm một số bước (như cung cấp mật khẩu hoặc token), hãy làm theo hướng dẫn mà nó đưa ra.

---

__LƯU Ý QUAN TRỌNG :__

- __Luôn pull code mới nhất__ trước khi bắt đầu làm việc để tránh xung đột.
- __Không nên commit tất cả các thay đổi cùng lúc__. Nên commit thường xuyên với các thông điệp rõ ràng và dễ hiểu.
- Nếu gặp lỗi trong quá trình push, hãy đọc kỹ thông báo lỗi và làm theo hướng dẫn.

---

HẾT

__Cảm ơn bạn đã đọc hướng dẫn này! Hy vọng bạn sẽ thành công trong việc sử dụng Git và GitHub để làm việc nhóm. Chúc bạn có một ngày làm việc hiệu quả! 🚀__





