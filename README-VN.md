# Unichain BOT
BOT Click: [UNICHAIN](https://docs.unichain.org/docs)

## Tính năng:

* Gửi token ETH đến các địa chỉ được tạo ngẫu nhiên trên Unichain Testnet.

## Module:

- Python 3.7 trở lên
- `pip` (trình cài đặt gói Python)

## Cài đặt
1. **Sao chép kho lưu trữ này:**
- Mở cmd hoặc Shell, sau đó chạy lệnh:
```sh
git clone https://github.com/thog9/Unichain-testnet.git
```
```sh
cd Unichain-testnet
```
2. **Cài đặt Module:**
- Mở cmd hoặc Shell, sau đó chạy lệnh:
```sh
pip install -r requirements.txt
```
3. **Config:**
- Mở tệp `private_keys.json` và đảm bảo thay thế `private_key` bằng khóa riêng hợp lệ của bạn.:
```sh
private_key = "PRIVATE_KEY_HERE"
```
4. **Chạy:**
- Mở cmd hoặc Shell, sau đó chạy lệnh:
```sh
python bot.py
```