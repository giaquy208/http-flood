# http-flood :3
- Using Golang(net/socket) to httpflood
- Please use command "ulimit -n 999999" before use this in linux
- 1 Threads = 1 connection, 100~300 connections can down a normal website in 10s(specially apache server 🤣🤣🤣)
- This is golang and threads are just goroutines so you set more higher threads like 1000-5000 is fine.
#
## THÔNG TIN
- HTTP Get Flood
- HTTP Post Flood
- Random url(http get flood)
- Self edit header(You can use "nil" to use default header)
- More powerful flood
- Improved threading control
- Auto get ip form domain(golang inbuilt function)
- More format for random url(http get flood)
- Fixed for 386 systems
#
## Cài đặt tiêu đề mặc định:
- Tác nhân người dùng ngẫu nhiên
- Dữ liệu ngẫu nhiên (http post flood)
- Tích lũy ngẫu nhiên
- Random Referer(only for http get flood)
#
## Tải xuống
- **Vui lòng tải xuống golang F * cking lúc đầu.**
- Sau đó:
 - 1: `git clone https://github.com/giaquy208/http-flood.git`
 - 2: `cd http-flood`
 - 3: `go httpflood.go`
- Định dạng tiêu đề.txt:
- 1 Accept: text/html 2 User-agent: Wget 3 Referer: http://google.com
- Hoặc bất kỳ thứ gì khác của tiêu đề http. Nếu bạn không biết gì về điều này, vui lòng chỉ sử dụng "nil" để sử dụng tiêu đề ngẫu nhiên mặc định.
#
## Cách sử dụng:
- `./httpflood  <url> <threads> <get/post> <seconds> <header.txt/nil>`
#
## ☞☜If you copy , Then Give me The Credits☞☜
