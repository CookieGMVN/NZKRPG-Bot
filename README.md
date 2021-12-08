# NZKRPG-Bot
Xin chào! Đầu tiên, xin chúc mừng bạn đã mò được tới cái Project này 👏

Vậy thì, cái gì đây? Ừ thì do chán con [NezukoBot](https://nezukobot.xyz/) nên thằng CookieGMVN lại đi làm con bot khác và đặt tên là NZKRPG vì hết ý tưởng đặt tên.
## Giới thiệu
NZKRPG là 1 con RPG Discord bot, được code bằng [NodeJS](https://nodejs.org/) và thư viện [Discord.js](https://discord.js.org/) và một số thư viện khác được liệt kê trong file package-lock.json

NZKRPG sử dụng 100% tiếng Việt và điều đặc biệt là NZKRPG là một con Bot mã nguồn mở, dựa theo Apache License 2.0. Để xem thêm chi tiết về những gì bạn ĐƯỢC và KHÔNG ĐƯỢC làm, vui lòng xem file [LICENSE](https://github.com/CookieGMVN/NZKRPG-Bot/blob/main/LICENSE).
## Cách sử dụng
Trước khi sử dụng, vui lòng lưu ý rằng, NZKRPG sử dụng Cơ sở dữ liệu MariaDB và Quick.DB nên bạn hãy cân nhắc về việc cài đặt chúng.

Cách cài đặt:
1. Clone/Fork Repo này về, cd đến folder bạn chứa.
2. Truy cập [Discord Developer Portal](https://discord.com/developers), tạo một Project + Bot mới
3. Lấy token của Bot, đi tới thư mục data và đổi tên file auth.ini.example thành auth.ini, cho Token Bot và tài khoản MySQL của Bot vào.
4. Tiến hành chạy lệnh `npm ci` để cài đặt các thư viện cần thiết
5. Sau khi xong, chạy lệnh `npm setup-db` để cài đặt và setup CSDL.
6. Cuối cùng, chạy lệnh `npm start` để bắt đầu chạy Bot.

Oh-yeah! Bạn đã chạy được Bot rồi đó! 👏
