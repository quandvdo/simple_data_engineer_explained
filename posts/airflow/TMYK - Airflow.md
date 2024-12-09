---
title: The more you know series - Airflow
date: 2024-11-30
draft: false
quests: side-quest
tags:
	- airflow
	- orchestrator
	- sidequest
	- techstack
	- infras
---

![[tmyk-airflow.jpg]]
# DE nhập môn: Airflow

Hãy tưởng tượng mớ data khổng lồ bạn đang cần đẩy vào trong database, đủ các thể loại hình thù , kích cỡ và các thể loại process phía trước. Vậy để dễ hiểu bạn có thể hình dung đống data đó là những viên gạch xây nhà, nhiều viên gạch đủ màu và mục đích cuối cùng là mình xây dựng ngôi nhà vĩ đại. Nhưng việc sếp cả nghìn viên gạch như thế rất khó để theo dõi xem viên gạch nào nên được đặt ở đâu vào lúc nào! 🧐

Giới thiệu của anh Nô dữ liệu 3 đời cty sài Apache Airflow! Nói tóm tắm thì airflow nó là 1 tổ hợp nhiều chức năng giúp bạn tổ chức những viên gạch của mình (hoặc hoán dụ lại là việc xử lý mớ data hỗn độn ở trên) để mọi thứ luôn gọn gàng và ngăn nắp và có thể đo lường được.

## Hiểu airflow đơn giản nhất

1. **Xây toàn bộ căn nhà** : Quất từ móng, đến cột trụ, sàn, sà , tầng , lửng lác các thể loại... kể cả cất luôn cả nóc nhà.

2. **Airflow là 1 người làm công chuyên nghiệp** : Tools sẽ không bao giờ phàn nàn và biết chính xác thời điểm cần thêm viên gạch tiếp theo (hoặc chạy công việc / task tiếp theo) tự động mà không cần bạn phải nhấc tay lên! Tuy nhiên code dở hay code thiếu muối thì vẫn bị airflow chửi nhá !😊

3. **Lúc nào cũng sẵn sàng, trừ phi server down/ thiên tai/ hoả hạn/ hoặc thằng nào rút dây mạng server** : Chỉ cần bạn cần truy vấn, viên thứ 68 trong pallet số 14 bốc từ xe tải số 51A12345 ngày hôm qua nằm ở đâu thì airflow sẽ trả cho bạn kết quả chi tiết liền. viên đó nằm ở góc toilet, bên trên có xi măng, hoặc do a Nô nhân dữ liệu 3 đời kia đặt vào lúc 12 đêm... etc.

4. **Dễ khắc phục hậu quả... àh ko.. hệ quả**: vd viên gạch A nào đó bị bể nên trên bức tường nhà vĩ đại này có nguyên 1 cái lỗ nhìn xuyên qua bờ rào. với vài nút bấm thì airflow có thể remedy / retry/ thử chạy lại flow có viên gạch đó để vá ngay chỗ đó lại. Đồng thời track lại chỗ đó lủng bao nhiêu lần => để đưa ra dữ kiện (signal) làm sao sửa hoài vẫn lủng 👌

Airflow làm cho việc xử lý dữ liệu trở nên thú vị và dễ dàng, ngay cả khi bạn mới nhập môn! Nó giống như có một a Nô dữ liệu đời thứ 4 đi ám bạn bất kể đâu![🚀](https://static.xx.fbcdn.net/images/emoji.php/v9/tc6/1/16/1f680.png)


> Hãy cùng đợi và nghịch airflow trong các kỳ tới.


#DataEngineering#DE #ApacheAirflow#DễDàngChoNgườiMới 