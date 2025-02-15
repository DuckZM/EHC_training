Tương tự git clone repo về
cat README.md thì thấy password bị ẩn

![alt text](writeup/anh/37.png)

Nhận thấy là file .md => thử git log thấy có commit là fix info leak
git show <id> để xem pass

![alt text](writeup/anh/38.png)