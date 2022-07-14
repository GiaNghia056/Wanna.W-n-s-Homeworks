# Stego-toolkit
Trong bài hướng dẫn cài bộ [stego-tookit](https://github.com/DominicBreuker/stego-toolkit) người ta hướng dẫn dùng docker container, nhưng mình chỉ chủ yếu dùng lệnh `sudo apt install` hoặc hướng dãn cài mỗi tool từ chính trang web ấy.
# Cài đặt và Demmo từng tool
Trước khi dùng `sudo apt íntall` thì hãy nhớ `sudo apt update` để chắc chắn rằng phiên bản `apt` đang là mới nhất.<br/>
Sau đó thì cài lần lượt từng tool.
Ở đây mình chỉ trình bày cách mình cài trên Máy ảo Kali và Windows10
## stegoVeritas
```
$ sudo -i
$ pip3 install stegoveritas
$ stegoveritas_install_deps
```
![image](https://user-images.githubusercontent.com/88471003/178874711-b37fa702-0768-42ca-aac6-8a680787b507.png)
## zsteg
```
$ gem install zsteg
```
![image](https://user-images.githubusercontent.com/88471003/178878011-342219c9-eaf9-4203-8063-2f0b8a90373b.png)
## stegdetect
Tải [package](http://old-releases.ubuntu.com/ubuntu/pool/universe/s/stegdetect/stegdetect_0.6-6_amd64.deb) này về và dùng lệnh
```
$ sudo dpkg -i stegdetect_0.6-6_amd64.deb
```
![image](https://user-images.githubusercontent.com/88471003/178884181-f1d38ae4-b8e9-4b98-a987-b4467c438ab1.png)
## stegbreak
