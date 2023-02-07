# Chatbot-ChatGPT-Python
Tạo chatbot với ChatGPT bằng Python
# Cách cài đặt
Bước 1: Cài đặt các package cần thiết
`sudo apt install git pip xvfb chromium-driver`

Bước 2: Cài đặt các package bổ sung
`sudo apt install nano`

Bước 3: Các bạn clone repo này về bằng lệnh: 
`git clone https://github.com/Wiviart/ChatGPT-Python.git`

Bước 4: Cài đặt các thư viện python cần thiết: 
`pip install -r requirements.txt`

# Cách sử dụng
Bước 1: Đăng ký tài khoản ChatGPT. Các bạn có thể xem hướng dẫn đăng ký [tại đây](https://anonyviet.com/cach-tao-tai-khoan-chatgpt-o-viet-nam/)

Bước 2: Hỏi AI bất cứ thứ gì.

Bước 3: Bật F12 và vào tab Application > Storage > Cookies > Chọn mục đầu tiên và tìm token có tên là "__Secure-next-auth.session-token". Sau đó copy mã token trong cột Value.
![image](https://user-images.githubusercontent.com/69446798/217171701-6453ee3b-0456-44f7-ac65-5befadb4e014.png)

Bước 4: Dán mã token đó vào biến session_token trong file pyChatbotGPT.py
![image](https://user-images.githubusercontent.com/69446798/217171751-2263d6bd-b38d-4a65-bb4e-f68cbd6ace4d.png)

Bước 5: Chạy file bằng lệnh 
`python pyChatbotGPT.py`
![image](https://user-images.githubusercontent.com/69446798/217171816-025e84de-e979-47a1-bc9f-d9d5806f49e5.png)

Vậy là xong rồi đó. 
![image](https://user-images.githubusercontent.com/69446798/217171841-7d186a76-4fd4-454a-9520-f15592e6e908.png)

Ngoài ra các bạn cũng có thể đưa con bot này ra internet để bạn bè sử dụng bằng ngrok nhé.
