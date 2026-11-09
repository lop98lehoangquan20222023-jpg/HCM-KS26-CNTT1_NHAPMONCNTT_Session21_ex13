# Phần 1:
1. Vì chứa nhiều từ cảm thán và từ xưng hô nên google trả ra nhiều kết quả không liên quan
2. bốc tách 3 lỗi:
- Tên phần mềm / Hệ điều hành: Node.js / npm / Windows 11

- Mã lỗi: 'npm' is not recognized as an internal or external command, operable program or batch file.

- Thao tác đang làm: Gõ lệnh kiểm tra npm -v trong Terminal của VS Code sau khi cài đặt.
3. **3 câu truy vấn Google**
- Giới hạn trong StackOverflow (site:):
    - site:stackoverflow.com "npm" "not recognized" windows 
- Dùng ngoặc kép cho lỗi nguyên văn (" ");
    - "'npm' is not recognized as an internal or external command" nodejs
- Loại trừ các bài viết cũ không liên quan (-):
   - npm not recognized windows path -windows-xp -windows-7
# Phần 2 – Thẩm định StackOverflow:
1. So sánh Câu trả lời A và B:

- Câu trả lời A: Có tích xanh (Accepted Answer), +186 votes, mới đăng 2 năm trước.

- Câu trả lời B: Không có tích xanh, chỉ có +2 votes, đăng 9 năm trước, chứa tag cũ .
2. Kết luận lựa chọn:

Em chọn áp dụng Câu trả lời A.

Vì sao câu trả lời B là "bẫy": Vì nó hướng dẫn cài lại driver cho Windows XP — hệ điều hành đã quá cũ và không liên quan đến Windows 11, nếu làm theo sẽ làm hỏng máy hoặc mất thời gian vô ích.
3. Quy trình 30 Giây Đọc lướt:

Nhìn lướt Tags xem có đúng công nghệ không ->Nhảy thẳng đến câu trả lời có tích xanh (Accepted Answer) hoặc Upvotes cao nhất -> Đọc nhanh phần code/giải pháp ngắn gọn.
# Phần 4 – Viết Bug Report chuẩn để nhờ hỗ trợ
1. Tin nhắn kiểu "Tin nhắn Kém":

"Thầy ơi máy em bị lỗi gõ npm không chạy được cứu em với!"

2. Tin nhắn chuẩn theo Bug Reporting Framework 4 bước:

|Mảnh ghép|Nội dung trong tin nhắn của bạn|
|:---:|:---:|
|Context|Đang cài đặt Node.js trên máy tính Windows 11 mới để làm bài tập lập trình web, mở Terminal trong VS Code.|
|Expected|Khi gõ lệnh npm -v, Terminal phải hiển thị số phiên bản hiện tại của npm.|
|Actual|Terminal báo lỗi không nhận diện được lệnh.|
|Log & Screenshot|'npm' is not recognized as an internal or external command, operable program or batch file. (Kèm ảnh chụp màn hình Terminal)
