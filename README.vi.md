# Anime Origins Ultimate

**Ngôn ngữ:** [English](./README.md) | **Tiếng Việt**

[![Price](https://img.shields.io/badge/price-free-22c55e)](#miễn-phí--mã-nguồn-mở)
[![Source](https://img.shields.io/badge/source-open-3b82f6)](#miễn-phí--mã-nguồn-mở)
[![Language](https://img.shields.io/badge/language-Luau-00a2ff)](https://luau.org/)
[![License](https://img.shields.io/badge/license-MIT-f59e0b)](./LICENSE)

**Anime Origins Ultimate** là script Luau automation miễn phí và mã nguồn mở dành cho Anime Origins trên Roblox. Script gom auto lobby, macro trong game, auto rift/challenge, auto join, shop, summon, craft, webhook và quản lý config local vào một giao diện.

Script không có key system, không có paywall và không thu phí người dùng.

> Dự án do cộng đồng phát triển, không liên kết hoặc được chứng thực bởi Roblox hay nhà phát triển Anime Origins. Hãy tự chịu trách nhiệm khi sử dụng phần mềm bên thứ ba và tuân thủ điều khoản của nền tảng.

## Tính năng nổi bật

- Giao diện lobby và in-game cho Anime Origins Ultimate.
- Auto Join với lựa chọn mode, world, act, difficulty, artifact và priority chọn card.
- Macro In-Game: ghi, tối ưu, import, chạy lại, auto replay và auto restart infinite.
- Auto Quest, Auto Story, Auto Challenge và Auto Rift.
- Auto Claim các phần thưởng và hệ thống progression được hỗ trợ.
- Auto Craft, Auto Shop, Auto Summon và Auto Redeem Codes.
- Lưu timer Rift và Challenge giữa lobby/game session.
- Discord Webhook cho thông báo automation.
- Hỗ trợ Igris/Clash như parry, chest, book, frag và clash automation khi game hỗ trợ.
- Auto reconnect, giới hạn FPS, Anti-AFK, nút mobile và lưu/tải config local.

## Cài đặt

Chạy đoạn loader sau trong môi trường Luau tương thích khi đã vào game:

```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/Truyem/Anime-Origins/refs/heads/main/AnimeOriginsUltimate.lua"))()
```

## Yêu cầu

- Môi trường thực thi Luau hỗ trợ `loadstring` và `game:HttpGet`.
- HTTP request qua `request`, `http_request` hoặc `syn.request` cho webhook/API.
- File APIs như `readfile`, `writefile`, `isfile`, `isfolder` và `makefolder` để lưu config và timer.
- Một số tính năng nâng cao có thể cần `hookmetamethod`, `hookfunction`, `getconnections` và debug APIs.
- Kết nối mạng để tải thư viện UI và tài nguyên remote.

Khả năng tương thích phụ thuộc vào môi trường thực thi. Nếu thiếu API, một số tính năng có thể không hoạt động dù giao diện vẫn tải được.

## Sử dụng cơ bản

1. Chạy script trong Anime Origins.
2. Cấu hình tab lobby hoặc in-game đúng với tác vụ cần dùng.
3. Lưu thiết lập trong Configs sau khi setup.
4. Kiểm tra kỹ map, macro, webhook và auto leave trước khi AFK.
5. Dùng nút mobile hoặc hotkey đã cấu hình để mở lại giao diện khi cần.

Config và dữ liệu runtime được lưu trong thư mục `AnimeOrigins_<UserId>` thuộc workspace executor.

## File trong repository

- [`AnimeOriginsUltimate.lua`](./AnimeOriginsUltimate.lua): script automation chính cho Anime Origins.
- [`README.md`](./README.md): tài liệu tiếng Anh mặc định.
- [`LICENSE`](./LICENSE): MIT License.

## Miễn phí & Mã nguồn mở

Toàn bộ mã nguồn chính nằm trong [`AnimeOriginsUltimate.lua`](./AnimeOriginsUltimate.lua) và được công khai miễn phí để cộng đồng đọc, kiểm tra, cải tiến và đóng góp.

- Không mua bán hoặc trả phí để nhận script này.
- Không tin các bản reupload yêu cầu key hoặc thanh toán.
- Nên lấy phiên bản mới nhất trực tiếp từ repository GitHub chính thức.
- Khi chia sẻ hoặc fork, vui lòng giữ copyright notice và license notice.

Dự án được phát hành theo [MIT License](./LICENSE).

## Đóng góp

Pull request và báo lỗi đều được hoan nghênh.

1. Fork repository.
2. Tạo branch cho thay đổi của bạn.
3. Giữ thay đổi nhỏ, rõ ràng và không thêm code bị obfuscate.
4. Kiểm tra cú pháp Luau trước khi gửi pull request.
5. Mô tả hành vi đã thay đổi và cách bạn kiểm tra nó.

Không đăng webhook URL, token tài khoản hoặc dữ liệu cá nhân trong issue hoặc pull request.

## Credits

- **Truyem789**: tác giả Anime Origins Ultimate.
- [Fluent](https://github.com/dawid-scripts/Fluent): thư viện UI và addon config.
- Cộng đồng Anime Origins: kiểm thử, chia sẻ macro và phản hồi.

## Disclaimer

Phần mềm được cung cấp nguyên trạng và có thể ngừng hoạt động sau mỗi bản cập nhật game. Tác giả không chịu trách nhiệm cho mất dữ liệu, gián đoạn tài khoản hoặc hậu quả phát sinh từ việc sử dụng script.
