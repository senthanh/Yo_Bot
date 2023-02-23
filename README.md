<h1 align="center">
  <img alt="banner" src="header.jpg" />
  
  𝐇𝐞𝐥𝐥𝐨<img src="Hi.gif" width="30px">
</h1>

<p align="center">
  <em>
    Hi, Tôi là Dương Công Nam <img src="assets/gifs/Rocket.gif" width="18px"><br>
 YoBot <img src="Developer.gif" width="30px">  <b> là một dự án mang đến Messenger một trải nghiệm mới cho người dùng bằng cách xây dựng một hệ thống bot dành riêng cho messenger facebook. Dự án này được DCNam code xây dựng và duy trì.</b> <img src="Medal.gif" width="20px">&nbsp.
  </em>
</p>
  

<img align="right" width=300px alt="shinchan" src="shinchan.gif" />

<!-- INSTALLATION -->
## Installation

🔭Sau đây là các bước cơ bản để có thể cài đặt và vận hành.

### Yêu cầu

- Dung lượng của máy phải trống tầm 1-2gb.
- Cần một số phần mềm chỉnh sửa file, khuyến khích sử dụng [notepad++](https://notepad-plus-plus.org/downloads/) hoặc [sublime text 3](https://www.sublimetext.com/3)
- Cần hiểu biết sơ lược qua về node, javascript.
- Một tài khoản Facebook dùng để làm bot(Khuyến khích nên sử dụng acc đã bỏ hoặc không còn sử dụng để tránh mất acc hay acc bị khoá).
- Đối với:
    - Windows: Cần cài đặt windows-build-tools.
    - Linux: Cần cài đặt python3 hoặc python2.
    - Android Sử dụng termux để vận hành bot.

### 😄Cài Đặt😄

#### 💬Windows

1. Tải về [Nodejs](https://nodejs.org/en/) và [git](https://git-scm.com/) sau đó cài đặt
    1. Nếu bạn window 7 trở xuống và không thể cài đặt nodejs thì có thể tải file cài đặt nodejs [tại đây(win 64bit)](https://nodejs.org/download/release/v13.14.0/node-v13.14.0-x64.msi) hoặc [tại đây(win 32bit)](https://nodejs.org/download/release/v13.14.0/node-v13.14.0-x86.msi)

2. Cài đặt windows-build-tools:
    1. Mở powershell với quyền adminstrator thông qua startMenu
    2. Nhập 
     ```sh
     npm install windows-build-tools
     ```

3. Clone source code của bot
    1. chuột phải ở folder cần cài đặt source code nhấn vào git bash
    2. nhập
    ```sh
    git clone https://github.com/senthanh/yobot
    ``` 

4. Cài đặt các package cần thiết
    1. Mở cmd/terminal ở thư mục bot, LƯU Ý thư mục đó phải có file package.json
    2. Nhập
    ```sh
    npm install
    ```

5. Chỉnh sửa file config
    1. Mở file config.json thông qua notepad++ hoặc sublime text 3 đã cài đặt ở trên
    2. tùy chỉnh mail, password, tên bot, ...
    3. Sao lưu và đóng lại

6. Lấy cookie
   

7. Chạy bot và tận hưởng
    1. Nhập
    ```sh
      npm start
      ```
    2. Đợi source code load file và tận hưởng!

#### 💬Android

1. Sử dụng google play và tải termux

2. Mở termux và nhập
    ```sh
    termux-setup-storage && apt update && apt upgrade && pkg install curl -y && bash <(curl -s https://raw.githubusercontent.com/catalizcs/storage-data/master/install.sh)
    ```

3. Đợi mọi package, lib cài đặt thành công là có thể sử dụng

4. Lấy cookie
5. về cách sử dụng, edit, vận hành
      1. Để bật được file manager bạn chỉ cần nhập vào termux
      ```sh
      manager
      ```
      2. Để vận hành bot, bạn chỉ cần nhập vào termux
      ```sh
      cd ./yobot && npm start
      ```

#### 💬Linux/ubuntu

1. Cài đặt node và git bằng cách nhập vào terminal
    ```sh
    sudo apt-get install curl
    curl -sL https://deb.nodesource.com/setup_16.x | sudo -E bash -
    sudo apt-get install nodejs git sqlite3 -y
    sudo npm install -g npm
    ```

2. Clone source code của bot bằng cách nhập vào terminal
    ```sh
    git clone https://github.com/senthanh/yobot
    ```

3. Cài đặt các package cần thiết
    1. Mở cmd/terminal ở thư mục bot, LƯU Ý thư mục đó phải có file package.json
    2. Nhập
    ```sh
    npm install
    ``` 

4. Chỉnh sửa file config
    1. Mở file config.json thông qua notepad++ hoặc sublime text 3 đã cài đặt
    2. tùy chỉnh mail, password, tên bot, ...
    3. Sao lưu và đóng lại

5. Lấy cookie
6. Chạy bot và tận hưởng
    1. Nhập
    ```sh
      npm start
      ```
    2. Đợi source code load file và tận hưởng!


<!-- CONTRIBUTING -->
## 📥Contributing📥

Sự đóng góp của bạn sẽ khiến cho project ngày càng tốt hơn, các bước để bạn có thể đóng góp

1. Fork project này
2. Tạo một branch mới chứa tính năng của bạn (`git checkout -b feature/AmazingFeature`)
3. Commit những gì bạn muốn đóng góp (`git commit -m 'Add some AmazingFeature'`)
4. Đẩy branch chứa tính năng của bạn lên (`git push origin feature/AmazingFeature`)
5. Tạo một pull request mới và sự đóng góp của bạn đã sẵn sàng để có thể đóng góp!

<!-- CONTACT -->
## Contact

🌱Dương Công Nam - [Facebook](https://www.facebook.com/levy.nam.2k5)

🌱Sen THanh - [Facebook](https://www.facebook.com/profile.php?id=100014811933322)

<hr>
