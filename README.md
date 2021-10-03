# ISPMINICTF
## PHẦN I: WELCOME
### Bài 1: Dōnyū
Bạn sắp đặt chân vào thế giới mới. Hãy khám phá nó ...
[Donyu.txt](https://github.com/Peteraad/ISPMINICTF/files/7272836/Donyu.txt)

#### ***Cách giải:***
Bước 1: Tải file và mở ra, ta được flag: **ISPCLUB{900D_LUCK_B4BY}** 
![image](https://user-images.githubusercontent.com/90112096/135743295-0a1ace65-20d3-41df-b551-ed828d1cc590.png)

### Bài 2: Discord
Hành trình thu thập vô cùng nguy hiểm và khó lường. Hãy để gia tộc ISP giúp đỡ các bạn: https://discord.gg/B7xFmWXp5F

#### ***Cách giải:***
Bước 1: Join in vào gia tộc ISP, ta tìm được flag ở mục rules: **ISPCLUB {4r3_y0u_r34dy}**
![image](https://user-images.githubusercontent.com/90112096/135743369-7fb78ba5-312a-4d48-9400-2b860a9a7b2a.png)

## PHẦN II: WARM UP
### Bài 1: Isekai with truck-kun
Một nhãn thuật cấp S được biết đến với cái tên Amaterasu đã thất lạc cùng con mắt mangekyou sharingan của huyền thoại Itachi thông qua 1 đường hầm dị giới. AkatXienPan đang lùng lục cánh cổng dị giới đó. Nhưng theo nguồn tin từ đội anbu thì nó đã bị đóng lại từ lâu, cách duy nhất để xuyên không hiện tại đó là để Truck-kun tông và yên tâm là chúng ta đã sở hữu Rinnegan với luân hồi chuyển sinh. Hãy lên đường tìm kiếm nhãn thuật đi nào, biết đâu 1 cuộc phiêu lưu đang chờ đợi phía trước.
> nc 35.198.208.29 10005

#### ***Cách giải:***
Bước 1: Sử dụng lệnh netcat để kết nối với 35.198.208.29 10005: nc 35.198.208.29 10005.
Bước 2: Lần lượt chọn Adventurer->[Tên của bạn]->Fight->Fight Boss. Sau khi đánh bại được Boss ta nhận được flag: **ISPCLUB{h34L_15_p0w3R}**

![image](https://user-images.githubusercontent.com/90112096/135743610-a39b09f8-f5d8-45d2-85d6-d3cc5bc1bf99.png)

## PHẦN III: CRYPTO
### Bài 1: Gravity Falls Bill
Đã nhiều lần ăn Ramen tại tiệm Ramen thương hiệu ISP Ichizoku, Deku Haha và bạn đến hôm nay mới để ý thấy rằng trong những tờ hóa đơn thanh toán của tiệm đều có những ký hiệu kỳ lạ. Nghe đồn đây là ấn chú mà chủ tiệm đã khắc lên để nhận biết xem tờ hóa đơn có bị sửa đổi không. Deku Haha thầm nghĩ nếu sắp tới xin gia nhập ISP Ichizoku mà biết được nó và cho vào CV thì rất có ích. Hãy giải mã nó cùng Deku Haha để làm đẹp CV sắp tới của mình nhé!!!
![encrypt](https://user-images.githubusercontent.com/90112096/135743678-c26f9231-719a-4b42-b2ef-3570dd9848c3.png)

#### ***Cách giải:***
Bước 1: Tải file đề cho và mở ra, ta nhận thấy được đây là Gravity Falls Bill Cipher.
Bước 2: Sử dụng trang https://www.dcode.fr/gravity-falls-bill-cipher để giải mã đoạn mã đấy ta tìm được flag: **ISPCLUB{BJLL_CJPKER}**
![image](https://user-images.githubusercontent.com/90112096/135743786-be1bea37-366e-4b78-843f-f5f57227bab6.png)

### Bài 2: Base no Jutsu
Một bí thuật cơ sở bị trộn lẫn bởi Base Ichizoku để che giấu sự nhòm ngó của AkatXienPan!!!
[Baka_no_Jutsu (2).txt](https://github.com/Peteraad/ISPMINICTF/files/7272872/Baka_no_Jutsu.2.txt)

#### ***Cách giải:***
Bước 1: Tải file về ta được đoạn mã : SVNQQ0xVQns623473335f31735f6e30745fORVTI5C7MQYWMZRRMN2WY5D5
Bước 2: Ta thử decode đoạn mã dưới dạng base64 ta thu được:
![image](https://user-images.githubusercontent.com/90112096/135743876-96bc94b7-5ef9-45e3-9700-9955f7b89a9d.png)
Bước 3: Qua hình ta có thể thấy đoạn đầu đúng là dạng base 64, tuy nhiên đoạn sau là 623473335f31735f6e30745fORVTI5C7MQYWMZRRMN2WY5D5 không phải dạng base64. Nếu để ý ta thấy đoạn 623473335f31735f6e30745f là đoạn có dạng Hex. Để kiểm chứng ta thử decode nó qua trang https://www.convertstring.com/vi/EncodeDecode/HexDecode
![image](https://user-images.githubusercontent.com/90112096/135743915-65630b08-f94a-4369-9728-f8cee1ea1dad.png)

Bước 3: Vậy ta ghép lại được ISP{b4s3_1s_n0t_ tuy nhiên còn đoạn cuối ORVTI5C7MQYWMZRRMN2WY5D5 ta decode sang dạng base32 thì ta ra 
![image](https://user-images.githubusercontent.com/90112096/135743992-61741e94-ff04-4204-9925-e1c5193bc5fe.png)

Bước 4: Ghép 3 đoạn vừa tìm được lại ta có flag cần tìm **ISP{b4s3_1s_n0t_tk4t_d1ff1cult}**


