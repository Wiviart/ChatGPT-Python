# Chatbot-ChatGPT-Python
Tạo chatbot với ChatGPT bằng Python

# Cách cài đặt
## Trên Linux
Bước 1: Cài đặt các package cần thiết
`sudo apt install git pip`

Bước 2: Cài đặt các package bổ sung
`sudo apt install nano xvfb chromium-driver`

## Trên Windows
Bước 1-2: Cài đặt python3 và chrome browser
![image](https://user-images.githubusercontent.com/69446798/217173869-47463743-da1b-4f58-9786-2dd2dca45476.png)

## Chung cho cả hai
Bước 3: Các bạn clone repo này về bằng lệnh: 
```git clone https://github.com/Wiviart/ChatGPT-Python.git```

Bước 4: Cài đặt các thư viện python cần thiết: 
`pip install -r requirements.txt`

Bước 5: Đăng nhập vào chat.openai.com, hỏi bất kỳ điều gì và chờ AI trả lời.

Bước 6: Bật F12 và vào tab `Application` > `Storage` > `Cookies` > Chọn mục đầu tiên và tìm token có tên là `__Secure-next-auth.session-token`. Sau đó copy mã token trong cột `Value`.
![image](https://user-images.githubusercontent.com/69446798/217171701-6453ee3b-0456-44f7-ac65-5befadb4e014.png)

Bước 7: Dán mã token đó vào biến session_token trong file pyChatbotGPT.py
![image](https://user-images.githubusercontent.com/69446798/217171751-2263d6bd-b38d-4a65-bb4e-f68cbd6ace4d.png)

Bước 8: Mở và copy Token ChatGPT vào ChatGPT.py (sử dụng nano hoặc các phần mềm edit khác)
`nano ChatGPT.py`

Bước 9: Chạy ChatGPT.py
`python3 ChatGPT.py`

![image](https://user-images.githubusercontent.com/69446798/217171816-025e84de-e979-47a1-bc9f-d9d5806f49e5.png)

Nếu thành công, cửa sổ ChatGPT sẽ mở ra từ trình duyệt Chrome.
![image](https://user-images.githubusercontent.com/69446798/217171841-7d186a76-4fd4-454a-9520-f15592e6e908.png)

Source: https://anonyviet.com/tu-tao-chatbot-chatgpt-bang-python-cho-rieng-minh/
