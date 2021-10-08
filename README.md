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

### Bài 3: Chuunin Exam
Kỳ thi Chunnin sắp đến gần, hãy chuẩn bị thật tốt để có thể học hỏi từ các Genin khác và có cơ hội được thăng cấp trở thành Chunnin đầu tiên trong thế hệ D21 làng PTIT!

> nc 35.198.208.29 2026

#### ***Cách giải:***
Bước 1: Kết nối với máy chủ thông qua câu lênh netcat : nc 35.198.208.29 2026
Bước 2: Ta sẽ giải 3 loại mật mã lần lượt theo thứ tự :
  1. Roman method of cryptography ( hay được biết tới là Caesar Cipher ):
>![image](https://user-images.githubusercontent.com/90112096/136212728-2166c707-3d54-4df1-bf03-bca077be6415.png)
  - Sử dụng trang web https://www.dcode.fr/caesar-cipher để decode mật mã ta tìm được messages : 
  >Developed around 100 BC, not until 9th-century, Caesar cipher was cracked with the discovery of frequency analysis.
  2. Ancient Greek technique ( hay được biết tới là Scytale Cipher ):
>![image](https://user-images.githubusercontent.com/90112096/136213288-e1d9b330-d103-47ca-88cc-8f6f3d3c5dbf.png)
  - Sử dụng trang web https://www.dcode.fr/scytale-cipher để decode mật mã ta tìm được messages:
  >Located_at_port_2026_encrypted_by_Scytale
  3.  Enigma M3
>![image](https://user-images.githubusercontent.com/90112096/136213988-c55122f4-a4fd-4517-bfad-b714cbdf45e5.png)
  - Sử dụng trang web https://cryptii.com/pipes/enigma-machine để decode mật mã ta tìm được messages:
  >enigmaisformilitarycommunication


**FLAG: ISPCLUB{s3cr3t_pr0t3ct0r}**
## PHẦN IV: PROGRAMMING
### Bài 1: Honest or Tricky
Tưởng shinobi thì không phải làm toán sao, đến bọn trẻ con còn làm tốt nữa là khác. Hãy thử xem liệu bạn có thể hoàn thành những bài toán sau trong thời gian cho phép ko nhé!
> nc 35.198.208.29 10002

#### ***Cách giải:***
Bước 1: Sử dụng câu lệnh netcat, kết nối với  35.198.208.29 10002: nc 35.198.208.29 10002

Bước 2: Giải liên tục 15 câu hỏi tính tổng 2 chữ số ta được flag: **ISPCLUB{m4th_f0R_dUmm13S!!!!!!!}**

![image](https://user-images.githubusercontent.com/90112096/135744201-f0553e66-4bc2-45fa-8f25-208ef37dd47b.png)

### Bài 2: Tricky or Honest
Tưởng shinobi thì không phải làm toán sao, đến bọn trẻ con còn làm tốt nữa là khác. Hãy thử xem liệu bạn có thể hoàn thành những bài toán sau trong thời gian cho phép ko nhé!
> nc 35.198.208.29 10003


#### ***Cách giải:***
Bước 1: Sử dụng câu lệnh netcat, kết nối với  35.198.208.29 10002: nc 35.198.208.29 10003

Bước 2: Do các phép tính giữa hay dãy số lớn bấm máy tính Casio bình thường sẽ không kịp thời gian 60s nên ta nghĩ đến hướng code socket.
 - Phân tích điều cần làm:
    + Ta cần chia câu hỏi thành hai dãy số riêng biệt để thực hiện các phép tính
    + Hiểu được thứ tự nhận được dữ liệu của máy chủ sau mỗi lần trả lời đúng 

Bước 3: Sau đó thực hiện code ta tìm được flag: **ISPCLUB{F45T_a5_71ghtN1n9!!!!}**

**CODE: https://pastebin.com/FHqWvEiu**
## PHẦN V: WEB 
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

### Bài 4: PHP no jutsu
Deku Haha tìm được một chiếc rương có chứa cuốn trục về một loại nhẫn thuật mới nhưng không tài nào tìm được mật khẩu để mở được rương. Haha đã đến nhờ bạn tìm mật khẩu giúp. Bạn có thể tìm được mật khẩu của rương kho báu giúp Haha không?

> http://35.198.208.29:3103/

#### ***Cách giải:***
Bước 1: Truy cập vào web và mở source code lên, ta thấy được 1 đoạn <!--hint.txt-->. Thử truy cập vào http://35.198.208.29:3103/hint.txt ta tìm được một đoạn code xét password đúng.
>![image](https://user-images.githubusercontent.com/90112096/136495686-f21094b5-7984-4c00-8b8e-72c3699c2d74.png)

Bước 2: Phân tích đoạn code, ta có thể thấy có đoạn  ***if (hash("md5", $_GET["password"]) == $_GET["password"])***, xem qua thì có thể thấy hơi vô lý vì làm sao một mã hash lại bằng chính nó được. Tuy nhiên đây là PHP và ngôn ngữ này có một đặc điểm gọi là Type Juggling ( Các bạn có thể nghiên cứu thêm qua https://bitly.com.vn/b1ny4p) 

Bước 3: Vậy ta có thể chọn một “Magic” Number / String	( 0e1137126905 ) trong bài viết trên và ta được flag : **ISPCLUB{php_1s_Suck}**

>![image](https://user-images.githubusercontent.com/90112096/136496132-cfffc6e9-9390-42a5-9bff-067a19d323fa.png)

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

### Bài 4: Himitsu No Ninmu
Bạn nhận được một nhiệm vụ tuyệt mật từ PTITgakuge: liên lạc với gián điệp của làng đang nằm vùng trong tổ chức AkatXienPan để thu thập thông tin tình báo. Dưới đây là bức mật thư đầu tiên của gián điệp đó. Hãy giải mã nó và tìm ra địa điểm trao đổi thông tin nhé!!!
> https://pastebin.com/9ESeD3UB

#### ***Cách giải***
Bước 1: Sau khi vào link đề cung cấp ta thấy một dãy số mà được tạo ra bởi Tupper's formula, nên ta sẽ decode đoạn mã đó qua trang 
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

### Bài 3: Sagasu no Jutsu
Vẫn chứng nào tật nấy, Deku Haha chưa thể sửa được tính vụng về và thói quen để đồ đạc lộn xộn của mình. Lại 1 lần nữa cậu ta để chung nhẫn cụ triệu hồi với cuốn bí thuật trong túi của mình. Và lại 1 lần nữa cậu ta vô tình kích hoạt nhẫn cụ đó, cả 1 đống cuốn trục trông chả khác gì cuốn bí thuật lại hiện ra. Dù rất là phiền phức nhưng bạn hãy một lần nữa giúp cậu ta nhé!!!
> https://bit.ly/3AWwaCT

#### ***Cách giải:***
Bước 1: Tải tệp về ta thấy có rất nhiều folder có cái có file txt có cái không. Nếu để truy cập từng cái thì rất lâu nên ta chỉ tìm những file đuôi .txt trong tệp ấy.

Bước 2: Xét từng file .txt ta tìm được flag sở file Secret : **ISPCLUB{5uck_4_l0n9_w4y}**

>![image](https://user-images.githubusercontent.com/90112096/136496789-22082801-61c2-4c4e-8284-79659fec7b9b.png)>

### Bài 4: Rasen...Deku
Trong gia tộc của Deku có 1 bức tranh nổi tiếng bền nhất trong PTITgakure, rơi bao nhiêu lần không vỡ. Deku Haha đã sử dụng bức tranh làm bia đỡ khi luyện tập và chắc cũng muốn kiểm tra độ bền của nó. Vì dùng Rasengan hơi mạnh nên bức tranh đã bị thành ra như này. Hãy giúp Deku Haha khôi phục nguyên vẹn bức tranh nhé!!!
>![Deku_cukcuk (2)](https://user-images.githubusercontent.com/90112096/136496865-089b6dc1-e9fa-4c13-a8b4-7159c6f050ea.png)

#### ***Cách giải:***
Bước 1: Nếu biết về Photoshop thì nhìn quá ta có thể thấy đây là hiệu ứng xoáy về tâm trong đó.

Bước 2: Vào photoshop và thực hiện **Filter->Distort->Twirl**, kéo thanh Angle lên 540 ta sẽ thấy được flag: **ISPCLUB{m4q3ky0u_sk4rjnq4n}**

>![image](https://user-images.githubusercontent.com/90112096/136497134-6743c9bc-1750-4740-900f-0889ac579c1e.png)

## PHẦN VIIII: RE
### Bài 1: Reverse no Jutsu
Có vẻ Deku Haha đã ăn cắp được một mảnh giấy cấm thuật. Nhưng vì quá ảo ma canada nên trong lúc luyện tập phong độn hắn lỡ cắt mảnh giấy thành nhiều phần và bị thổi bay đi. Bây giờ hắn đang khóc lóc và cầu xin bạn giúp tìm từng mảnh để ghép chúng lại. Hắn ta hứa sẽ trả công bạn hậu hĩnh. Bạn có sẵn lòng giúp hắn ko? ( Việc nhẹ lương cao tại sao không làm)

> https://pastebin.com/6wQC3nGi

#### ***Cách giải:***
Bước 1: Mở file cpp đề bài cho, đọc và ta thấy được thuật toán của chương trình: hàm check có tác dụng kiểm tra dãy string nhập vào có những kí tự trong dãy giống trong hàm check không. 

Bước 2: Thế nên ta chỉ cần khai báo hàm string và giữ nguyên phần có phép so sánh thành phép gán sau đó xuất ra màn hình thì ta tìm được flag của bài: **ISPCLUB{s3xY_n0_jnt5u_K4i_h4r3m}**

Code: https://pastebin.com/FcFSW3bG

### Bài 2: Kakureru
Bạn và Deku Haha đã tìm thấy một hang động, có lẽ đây là nơi ẩn nấp đã bị bỏ hoang của tổ chức AkatXienPan chăng? Trên hang chứa rất nhiều văn tự nhưng có lẽ chúng đã được viết ngược lại. Hãy giải mã nó để xem có thể tìm được manh mối gì của bọn chúng không nhé!
> [UDRL (3).zip](https://github.com/Peteraad/ISPMINICTF/files/7293908/UDRL.3.zip)

#### ***Cách giải:***
Bước 1: Tải file về vã mở file UDRL.py, đọc qua code ta sẽ có những yếu tố sau :
 - Flag đã được chuyển qua dãy nhị phân.
 - Flag đã được biến đổi qua các hàm up, down, right, left.

Bước 2: Đi sâu hơn, ta sẽ phân tích từng hàm: 
>Hàm up(x):
   - Đây là hàm convert Flag qua dãy nhị phân. Tuy nhiên số lượng phần tử của dãy nhị phân của mỗi kí tự sẽ là 8.

>Hàm down(x):
   - Đây là hàm có tác dụng khi gặp bit 1 sẽ đổi 0 và ngược lại trong dãy nhị phân.
   
>Hàm right(x):
   - Đây là hàm có thể nói là vô dụng vì nó giữ nguyên dãy nhị phân mà không gây biến đổi gì.

>Hàm left(x):
   - Đây là hàm đảo ngược dãy nhị phân từ dưới lên trên.

>Để kiểm chứng những điều vừa nói mình sẽ thử chạy và xuất ra từng hàm với **FLAG="I"** ( để dãy ngắn và dễ phân tích hơn ):
   ![image](https://user-images.githubusercontent.com/90112096/136208745-9e7b7b99-fa18-40e4-89b9-1c19650f86f6.png)

Bước 3: Sau khi hiểu rõ bản chất của đoạn code thì ta tiến hành viết chương trình giải mã ngược lại. 
> Ta cần :
   1. Đảo ngược chuỗi
   2. Loại bỏ phần tử cuối của dãy nhị phân mỗi lần tìm được vì chỉ dãy chỉ có 7 phần tử
   3. Sau đó ta convert nó qua ASCII bằng trang https://www.rapidtables.com/convert/number/binary-to-ascii.html
   
**CODE:** https://pastebin.com/yVHT8gMp

**FLAG:ISPCLUB{W3ll_c0m3_t0_r3vers!n9}**

    
Thanks for reading !
