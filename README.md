# Demo running NLP AI

## Introduction
Đây là bản demo chạy NLP AI bằng Python, xử lý input đầu vào bằng keyBERT - trích xuất từ khóa và so sánh với tags được gắn trong database (không hoàn toàn chính xác, data này chỉ là raw phục vụ cho PoC, có thể còn thiếu sót). Output cho ra sẽ là gợi ý các món ăn, nhà hàng.

## Implement
Lưu ý keyBERT hiện tại không hỗ trợ cho phiên bản Python mới nhất Python 3.13. Thế nên để chạy được các file trên, khuyến khích nên cài máy ảo với Python 3.11 và đồng thời cài đặt các libraries cần thiết trong file **requirements.txt**:
- Cài đặt máy ảo trên VSCode:
+ Cài đặt Python 3.11: https://www.python.org/downloads/release/python-3119/
+ Cài đặt máy ảo:
``bash
py -3.11 -m venv .venv 
``
Rổi kích hoạt:
``bash
.\.venv\Scripts\Activate.ps1
``
Nếu thấy: **(.venv) PS D:\Data>**, là đã thành công.
Sau đó hãy cài các thư viện cần thiết sau:
``bash
pip install -r requirements.txt
``
Sau khi cài xong hết, chạy lệnh sau để chạy demo NLP AI:
*Chạy demo recom nhà hàng:
``bash
python recomRes.py
``
*Chạy demo recom đồ ăn thức uống:
``bash
python recomFood.py
``

## Notes
Bản demo này có thể còn nhiều thiếu sót và có khi có bug, mong mọi người thông cảm và đóng góp ý kiến cho mình nhé!
Email: hoangtrang555htm@gmail.com

## Author
HoangTrang
