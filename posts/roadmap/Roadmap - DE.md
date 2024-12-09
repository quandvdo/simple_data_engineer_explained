---
title: Roadmap - DE
date: 2024-11-23
draft: false
quests: main-quest
tags:
  - DE_roadmap
  - DE
  - DataEngineering
featured_image: /imgs/roadmap-de.jpg
---
## Roadmap - DE

Mình đã nhận khá nhiều câu hỏi liên quan việc các kỹ năng 1 DE cần có và hướng phát triển của bản thân để fulfill khả năng cho DE.

1. Cần 1 ngôn ngữ lập trình : python/go/rust/C#/Java hoặc bất cứ ngôn ngữ nào cũng được. Mục đích là để bản thân hiểu được logic và application structure chạy như thế nào. Nếu bạn không có nền tảng này cũng không sao nhưng bù lại sẽ phải mất nhiều thời gian và công sức hơn để "hội nhập" với các tech stack của công ty bạn đang cần. 
	- Vd. Doanh nghiệp bạn đang sài airflow để làm main data orchestrate thì việc bạn phải biết python là điều hiển nhiên, vì nếu không thì không thể dựng dags/ data pipelines đc. Tuy nhiên nếu doanh nghiệp đang sài các tool visualize drag drop như nifi/data factory/magic thì bạn không cần nhất thiết phải biết. 
	- Nên tùy vào techstack doanh nghiệp mà bạn apply thì sẽ có yêu cầu phần này hay ko và thường sẽ được ghi rõ trong job description

3. Cần phải biết 1 cách xem data, có thể là SQL/numpy/pandas/ hoặc cơ bản nhất là excel. Phổ biến nhất vẫn là SQL và excel vì data đa số nằm ở dạng structured đâu đó trong doanh nghiệp. Nên việc mình nắm được cách xem data như thế nào, ở đâu cũng là quan trọng.

4. Hiểu được các tổ chức của data, bao gồm data types/ model / schema. Các bảng table có normalize hay denormalize không, primary/foreign key là gì, mô hình star schema ra sao. Khi nào apply đc Int32 và int64 , khi nào double khi nào float.

5. Hiểu các cách thức get data, ETL/ELT , data apis như thế nào. Khi nào scheduling với cron job/ hay timestamp etc...

6. Hiểu và biết cách sử dụng các DBT data build tool, với 1 số doanh nghiệp ko dùng cloud provider thì họ dùng các dbt nhỏ hơn như talend/ knime / pyetl... thì mình hiểu các sử dụng nó cũng là 1 lợi thế. Sau đó cái tool visualize như powerbi/ tableau/ crystal report hay chí ít là excel pivot/power query.

7. Các kỹ năng về softskill của các bạn :
	- Kỹ năng đọc, tiếng anh hay tiếng u gì cũng đc. Vì các bạn sẽ phải đọc rất nhiều, từ documentation của internal đến document của tool rồi các best practice khác mà các bạn có thể apply đc cho job hằng ngày.
	
	- Kỹ năng hiểu vấn đề và đơn giản hóa vấn đề. Nó sẽ bao gồm việc các bạn lắng nghe và có thể đưa ra cách giải quyết bớt cồng kềnh nhất.
	
	- Quan trọng nhất là kỹ năng truyền đạt, bạn có thể mô tả những thứ thuộc về technicals skill cho 1 người bình thường không có bất cứ background nào về tech thì là các bạn thành công. Hay các bạn có thể truyền tải đc thông tin ngắn gọn xúc tích cho các user khác mà không bị loãng thông tin. Cách làm slide cũng vậy đừng quăng 1 đống chữ wall of text lên thì chẳng ai đọc xong mà nhớ đc thông tin mình cần truyền đạt cả. Sắp xếp lại câu chữ, các ý chính dùng icon vẽ diagram abstract nhất có thể , hãy xem bất kỳ ai đọc slide/cv của mình là ng không biết gì, hoặc xem họ như học sinh lớp 5. Thì lúc mình truyền đạt, họ dễ follow và hiểu đc vấn đề của mình hơn.

7. Biết 1 tí về devops, git / cicd / branching pull request/ itsm hoặc 1 số cách promote tuqf dev =>qa=>prod. Data move như nào, test data ra sao...

8. Luôn học cái mới. Các công nghệ mới lúc nào cũng ngon vd apache iceberg/ delta io / cassandra ... apply những cái mới thì đời lúc nào cũng dễ thở.

Tóm tắt những ý chính của mình. Chúc các bạn thành công.

#DE #DE_roadmap