# Stego-toolkit
Trong bài hướng dẫn cài bộ [stego-tookit](https://github.com/DominicBreuker/stego-toolkit) người ta hướng dẫn dùng docker container, nhưng mình chỉ chủ yếu dùng lệnh `sudo apt install` hoặc hướng dãn cài mỗi tool từ chính trang web ấy.
# Cài đặt và Demo từng tool
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
## AudioStego
```
$ sudo apt-get install libboost-all-dev
$ git clone https://github.com/danielcardeenas/AudioStego.git
$ cd AudioStego
$ mkdir build
$ cd build
$ cmake ..
$ make 
```
Sau đó một file tên `hideme` được tạo ra.<br/>
![image](https://user-images.githubusercontent.com/88471003/178886870-2ca74a88-8107-47b4-bb3b-1b51c1e3c963.png)
## jphide/jpseek
```
$ wget -O /usr/bin/jphide https://github.com/mmayfield1/SSAK/raw/master/programs/64/jphide
$ chmod +x /usr/bin/jphide

$ wget -O /usr/bin/jpseek https://github.com/mmayfield1/SSAK/raw/master/programs/64/jpseek
$ chmod +x /usr/bin/jpseek
```
## jsteg
```
$ wget -O /usr/bin/jsteg https://github.com/lukechampine/jsteg/releases/download/v0.1.0/jsteg-linux-amd64
$ chmod +x /usr/bin/jsteg
```
![image](https://user-images.githubusercontent.com/88471003/178890980-90b2617e-f76d-49e5-a8cd-b89871fdd927.png)
## mp3stego
## openstego
## outguess
```
$ wget -O /usr/bin/outguess-0.13 https://github.com/mmayfield1/SSAK/raw/master/programs/64/outguess_0.13
$ chmod +x /usr/bin/outguess-0.13
```
![image](https://user-images.githubusercontent.com/88471003/178929739-8d5833fd-2c37-4442-a764-5fd7bc357f2b.png)
## stegano
Chạy file [này](https://github.com/DominicBreuker/stego-toolkit/blob/master/install/stegano.sh) để cài
![image](https://user-images.githubusercontent.com/88471003/178932861-8bf78727-31a1-4c3a-990d-f76c174db19d.png)
## Steghide
```
$ sudo apt install steghide
```
![image](https://user-images.githubusercontent.com/88471003/178936491-ef0365b2-ee99-48f0-b984-29741bf4d8dd.png)
## cloackedpixel
Chạy file [này](https://github.com/DominicBreuker/stego-toolkit/blob/master/install/cloaked_pixel.sh) để cài<br/>
![image](https://user-images.githubusercontent.com/88471003/178941946-ee67a2f3-4184-40ab-b743-e08c190e7f0e.png)
## LSBSteg
Clone [repo](https://github.com/RobinDavid/LSB-Steganography) này về và chạy file `LSBSteg.py` bên trong<br/>
## f5
## stegpy 
```
$ pip3 install stegpy
```
![image](https://user-images.githubusercontent.com/88471003/178953121-ef0fc982-08c6-4cc8-9a1d-145d162b593d.png)
## Steg
Cài ở [đây](https://www.fabionet.org/)<br/>
![image](https://user-images.githubusercontent.com/88471003/178963027-5a9bd38b-fd2d-490f-a50e-6fea9fb1de56.png)
![image](https://user-images.githubusercontent.com/88471003/178963140-41516ae0-1b84-46ae-9f8b-a0210a78efbc.png)
![image](https://user-images.githubusercontent.com/88471003/178963307-9be5f9f2-8c33-4ba8-ae32-ee5d70c7a4d6.png)
![image](https://user-images.githubusercontent.com/88471003/178963438-de28c3a6-8b94-403d-838b-ffc2c48a6801.png)
## Steganabara
Cài ở [đây](https://github.com/zardus/ctf-tools/blob/master/steganabara/install)<br/>
![image](https://user-images.githubusercontent.com/88471003/178965107-677a2c22-fb54-49bd-8d59-bf1451704621.png)
![image](https://user-images.githubusercontent.com/88471003/178964954-c9d38d55-f145-4ce1-960a-64143ae9fc49.png)
## Stegsolve
Chạy file [này](https://github.com/zardus/ctf-tools/blob/master/stegsolve/install) để cài<br/>
Tải file [này](https://drive.google.com/file/d/1T1tIOw6Z79J2125BYZe4esL8o5fdGpS-/view) để chạy thử<br/>
![image](https://user-images.githubusercontent.com/88471003/178965777-566400ac-8039-48ec-81c3-5b51e6292060.png)
![image](https://user-images.githubusercontent.com/88471003/178966442-100c83f4-2ba1-41a4-ba3b-54870cd9f418.png)
![image](https://user-images.githubusercontent.com/88471003/178966645-1a1e4d8c-9578-4ba8-b5d7-070c083babe1.png)
## Sonic Visualizer
Cài ở [đây](https://www.sonicvisualiser.org/)<br/>
Tải file [này](https://drive.google.com/file/d/1m5EvwE17OrJ6N8LZTcdefnFS0sWaG7a6/view) để chạy thử<br/>
![image](https://user-images.githubusercontent.com/88471003/178968119-1ee6dc97-27b2-4f79-b723-569ca20b48b1.png)
![image](https://user-images.githubusercontent.com/88471003/178968185-8bb17111-1bba-4a0a-aa94-3981ece040af.png)
## Stegosuite
```
$ sudo apt install stegosuite
```
![image](https://user-images.githubusercontent.com/88471003/178968558-cf4b5851-9bac-42b7-9ea0-015006270489.png)
![image](https://user-images.githubusercontent.com/88471003/178969723-6d26230e-9274-4d39-b62d-a5379f4a2026.png)
![image](https://user-images.githubusercontent.com/88471003/178969355-5619d78f-4eaf-4358-95df-efc3526aacc6.png)
![image](https://user-images.githubusercontent.com/88471003/178969584-7fdd8b6c-db4c-4790-9f26-d8a1cf5b4aeb.png)
## openpuff
Chạy file [này](https://github.com/DominicBreuker/stego-toolkit/blob/master/install/openpuff.sh) để cài<br/>
![image](https://user-images.githubusercontent.com/88471003/178969991-0c636058-3f4f-4821-8ac7-fbcc3e898a22.png)
![image](https://user-images.githubusercontent.com/88471003/178971443-648d4c48-d252-43ec-bfa6-433fc99cb7bb.png)
![image](https://user-images.githubusercontent.com/88471003/178972095-b3da4524-e2ac-4ad8-9649-7ddf6ee780b0.png)
## DeepSound
Cài ở [đây](http://jpinsoft.net/deepsound)<br/>
![image](https://user-images.githubusercontent.com/88471003/178973124-a89f608c-19dd-4a7d-8212-70a470072927.png)
![image](https://user-images.githubusercontent.com/88471003/178973362-e7a1e6cb-b074-45f6-927e-72dd0a07e04d.png)
## cloacked-pixel
                                                                         _oo0oo_
                                                                        o8888888o
                                                                        88" . "88
                                                                        (| -_- |)
                                                                        0\  =  /0
                                                                      ___/`---'\___
                                                                    .' \\|     |// '.
                                                                   / \\|||  :  |||// \
                                                                  / _||||| -:- |||||- \
                                                                 |   | \\\  -  /// |   |
                                                                 | \_|  ''\---/''  |_/ |
                                                                 \  .-\__  '-'  ___/-. /
                                                               ___'. .'  /--.--\  `. .'___
                                                            ."" '<  `.___\_<|>_/___.' >' "".
                                                           | | :  `- \`.;`\ _ /`;.`/ - ` : | |
                                                           \  \ `_.   \_ __\ /__ _/   .-` /  /                                                  
                                                       =====`-.____`.___ \_____/___.-`___.-'=====
                                                                         `=---='
                                                                   THANKS FOR READING
