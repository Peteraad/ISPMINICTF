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

Bước 4: Vậy ta ghép lại được ISP{b4s3_1s_n0t_ tuy nhiên còn đoạn cuối ORVTI5C7MQYWMZRRMN2WY5D5 ta decode sang dạng base32 thì ta ra 
![image](https://user-images.githubusercontent.com/90112096/135743992-61741e94-ff04-4204-9925-e1c5193bc5fe.png)

Bước 5: Ghép 3 đoạn vừa tìm được lại ta có flag cần tìm **ISP{b4s3_1s_n0t_tk4t_d1ff1cult}**

## PHẦN IV: PROGRAMMING
### Bài 1: Honest or Tricky
Tưởng shinobi thì không phải làm toán sao, đến bọn trẻ con còn làm tốt nữa là khác. Hãy thử xem liệu bạn có thể hoàn thành những bài toán sau trong thời gian cho phép ko nhé!
> nc 35.198.208.29 10002

#### ***Cách giải:***
Bước 1: Sử dụng câu lệnh netcat, kết nối với  35.198.208.29 10002: nc 35.198.208.29 10002

Bước 2: Giải liên tục 15 câu hỏi tính tổng 2 chữ số ta được flag: **ISPCLUB{m4th_f0R_dUmm13S!!!!!!!}**

![image](https://user-images.githubusercontent.com/90112096/135744201-f0553e66-4bc2-45fa-8f25-208ef37dd47b.png)

## PHẦN v: WEB 
###  Bài 1: Beginner
Một bài tập khởi động trước khi tham gia nhận nhiệm vụ ngày hôm nay!!!
> http://35.198.208.29:3202/

#### ***Cách giải:***
Bước 1 : Truy cập vào web và kiểm tra source code. Ta tìm được flag: **ISPCLUB{Not_the_first_time_huhh??} **

![image](https://user-images.githubusercontent.com/90112096/135745398-de8f79df-3986-49c1-b3ed-b49f1334e709.png)

### Bài 2: Deku's Bird
Chú chim quý của nhà Deku được cái đẹp nhưng lại không có não. Nhiều lần nó xổng ra nhưng đều đâm đầu vào tường rồi lăn ra ngất. Hôm nay nó đã xổng lồng và bay vào 1 hang động đầy thạch nhũ. Deku Haha đã dùng Quang độn thắp sáng cả cái hang này, bạn hãy dùng thuật điều khiển bóng để điều khiển con chim bay qua 222 chướng ngại vật để ra ngoài 1 cách an toàn nhé!!! http://134.209.97.157:5002/

#### ***Cách giải:***
Bước 1: Truy cập vào web, ta nhận thấy đây là trò chơi Flappy Bird huyền thoại. Tuy nhiên để mà chơi qua 222 điểm thì rất tốn thời gian cho nên ta vào mục Console kiểm tra xem có thuộc tính lưu điểm của đối tượng game không.

Bước 2: Ta tìm được game.score, có thể hiểu là điểm của mỗi lần chơi. Nhìn lại yêu cầu đề bài là cần bay qua 222 chướng ngại vật nên, ta gán game.score=222.
![image](https://user-images.githubusercontent.com/90112096/135745595-1e13a09c-1edb-4883-91ba-a294b6e8180c.png)

Bước 3: Đợi một lúc ta được flag: **ISPCLUB{4_G00D_PL4Y3R}**

![image](https://user-images.githubusercontent.com/90112096/135745609-857fa195-0a94-48ba-b806-a24ea5b627c4.png)

### Bài 3: Shinra Tensei
Hiruyzawa Kuhan đã lên kế hoạch phá hủy PTITgakure trong thời gian tới. Bạn có thể vượt thời gian để ngăn chặn kế hoạch của hắn không???
> http://18.118.154.214:5000/

#### ***Cách giải:***





## PHẦN VI: GENERAL SKILLS
### Bài 1: Start the new schoolyear
Một bài test nhanh cho các Genin!!

[exam.zip](https://github.com/Peteraad/ISPMINICTF/files/7272890/exam.zip)

#### ***Cách giải:***
Bước 1: Tải file về giải nến ta tìm có được thêm 3 file nén nhỏ và một file txt. Mở file txt ta đọc được 3 câu hỏi dành cho 3 cái pass của 3 file nén
![image](https://user-images.githubusercontent.com/90112096/135744268-ad9aaed2-7e06-46ce-b3ba-25352224cf3c.png)

Bước 2: Lần lượt trả lời các câu hỏi:
- Câu 1 : sudo
- Câu 2: cat
- Câu 3 : ls -a

Bước 3 : Sau khi giải nén ta được 3 file txt ghép lại ta được flag : **ISPCLUB{L1nux_1z_v3ry_c0nV3n1EnT}**

### Bài 2: Earth Hour
Hôm nay là ngày Trái Đất! ISP Ichizoku đại diện cho PTITgakure soạn thư gửi tới rất nhiều các quốc gia khác trên Thế giới. Trong thư không chỉ nói lên thông điệp của các nhẫn giả PTITgakure mà còn bao gồm các quốc gia nhận được thư. Hãy xem xem bạn có hiểu được thông điệp của bức thư không nhé!
[Messenger.txt](https://github.com/Peteraad/ISPMINICTF/files/7272893/Messenger.txt)

#### ***Cách giải:***
Bước 1: Tải về mở file lên ta thấy được một đoạn mã. Dựa theo đề bài ta có thể nhận ra (x,y) thật ra là tọa độ của các nước trên thế giới.

Bước 2: Sử dụng https://www.google.com/maps/ tìm các tọa độ và lấy chữ đầu của tên nước ta ghép lại và được flag: **ISPCLUB{OUREARTH}** 

### Bài 3: Sasuke’s Paw Encyclopedia
Dù cho đã kiếm đc cả dấu chân của vua mèo nhưng papasuke vẫn còn thiếu dấu chân duy nhất của con mèo ma thuật. Papasuke nói sẽ tặng cho bất kì ai kiếm được dấu chân mèo đó 1 ấn chú cấp S. Hãy tìm ra nó và mang về cho papasuke!!!
> nc 35.198.208.29 10001

#### ***Cách giải***
Bước 1: Sử dụng câu lệnh netcat, kết nối với 35.198.208.29 10001: nc 35.198.208.29 10001. Sau đó ta nhận được flag: **ISPCLUB{SO_WEIRD_CAT}**

![image](https://user-images.githubusercontent.com/90112096/135744462-11f691ea-8dad-4b43-a854-6c4268436f8d.png)

## PHẦN VII: MISC
### Bài 1: Faster!!!
Tên Hiruyzawa Kuhan là kẻ có thân thủ rất nhanh. Bạn cần luyện tập cho đôi mắt của mình bắt kịp tốc độ của hắn. Hãy xem bạn đã đủ nhanh để theo dõi hắn chưa
https://www.youtube.com/watch?v=95qVduCOWTc

#### ***Cách giải:***
Bước 1: Mở link youtube ra, ta nhận ra video này có phụ đề nên ta vào mục mở bản chép lời ra và ghép các từ đó lại ta được flag: **ISPCLUB{r1ck_r0ll_4g41n}

![image](https://user-images.githubusercontent.com/90112096/135744634-2739578e-280b-45fa-afd0-f14f9db049ca.png)

### Bài 2: First Generation
Trải qua nhiều thế hệ, biểu tượng của ISP Ichizoku đã được thay đổi rât nhiều nhưng biểu tượng thời sơ khai vẫn được cất giữ cẩn thận trong phòng truyền thống của gia tộc. Trên đó có 1 secret text . Chắc bạn sẽ tìm được nó nhanh thôi.

Flag form: ISPCLUB{SECRET_TEXT}

#### ***Cách giải:***
Bước 1: Đọc đề ta có thể nghĩ ngay đến page của ISP CLUB (https://www.facebook.com/ATTT.PTIT). Nói đến biểu tượng thì chỉ có thể là avatar, ta tìm avatar đầu tiên của câu lạc bộ và cũng là flag của bài : **ISPCLUB{CAPTURE_THE_FLAG}**
![image](https://user-images.githubusercontent.com/90112096/135744745-42660366-9a53-4633-976c-002796d9826b.png)

## PHẦN VIII: FORENSIC
### Bài 1: Covi no Dokumushi
Với cuốn bí thuật ăn cắp được từ Aburame Ichizoku, Hiruyzawa Kuhan đã sử dụng nó triệu hồi virus Covid tấn công PTITgakure. Ngày qua ngày số lượng ca nhiễm càng tăng lên đặt lên vai các y nhẫn giả một áp lực không hề nhẹ. Theo thống kê, ngày 22/9 số lượng người được chữa khỏi là nhiều nhất. Là genin cũng như là người dân trong làng, liệu bạn có nắm bắt được có bao nhiêu người được chữa khỏi ko???

> Flag : ISPCLUB{số lượng người}

#### ***Cách giải:***
Bước 1: Đọc đề sau đó ta tra cứu trên mạng và thu thập thông tin chính xác từ các web uy tín c https://moh.gov.vn/tin-lien-quan/-/asset_publisher/vjYyM7O9aWnX/content/ngay-22-9-co-11-527-ca-mac-covid-19-rieng-tp-hcm-va-binh-duong-a-ghi-nhan-hon-9-600-ca.
Bước 2: Vậy flag là : **ISPCLUB{11919}**

### Bài 2: Daichidoukaku
Tam Vĩ đang nổi điên. Chắc chắn là do Hiruyzawa Kuhan đã cho nó say thuốc. Trong lúc đợi các y nhẫn giả đến và chữa trị cho nó, bạn và hàng trăm genin gần đó có nhiệm vụ cùng nhau thi triển 1 nhẫn thuật để mặt đất rung chuyển và tách ra nhằm làm kìm chân Tam Vĩ, không để nó tiến vào trong làng.

![Supuritto_no_Jutsu](https://user-images.githubusercontent.com/90112096/135744921-8d01b8f7-8716-4aef-b466-aa16e415f3bf.gif)

#### ***Cách giải:***
Bước 1: Do bài chỉ là 1 file GIF nên ta nghĩ ngay đến cách phân rã file GIF bằng https://en.bloggif.com/gif-extract
![image](https://user-images.githubusercontent.com/90112096/135744974-7f9cb5b4-6697-438d-afb7-855269ec5f02.png)

Bước 2: Quét mã vạch mà ta tìm được trong đấy ta tìm được flag là : **ISPCLUB{5p1it_91f}**

![image](https://user-images.githubusercontent.com/90112096/135744995-78936db6-a43b-4124-9867-29dbb89853b7.png)

## PHẦN VIIII: RE
### Bài 1: Reverse no Jutsu
Có vẻ Deku Haha đã ăn cắp được một mảnh giấy cấm thuật. Nhưng vì quá ảo ma canada nên trong lúc luyện tập phong độn hắn lỡ cắt mảnh giấy thành nhiều phần và bị thổi bay đi. Bây giờ hắn đang khóc lóc và cầu xin bạn giúp tìm từng mảnh để ghép chúng lại. Hắn ta hứa sẽ trả công bạn hậu hĩnh. Bạn có sẵn lòng giúp hắn ko? ( Việc nhẹ lương cao tại sao không làm)

> https://pastebin.com/6wQC3nGi

#### ***Cách giải:***
Bước 1: Mở file cpp đề bài cho, đọc và ta thấy được thuật toán của chương trình: hàm check có tác dụng kiểm tra dãy string nhập vào có những kí tự trong dãy giống trong hàm check không. 

Bước 2: Thế nên ta chỉ cần khai báo hàm string và giữ nguyên phần có phép so sánh thành phép gán sau đó xuất ra màn hình thì ta tìm được flag của bài: **ISPCLUB{s3xY_n0_jnt5u_K4i_h4r3m}**
Code: https://pastebin.com/FcFSW3bG
