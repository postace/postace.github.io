---
layout: post
title: Một số bài học rút ra từ buổi Scrum Planning
---


# Bài học

Anh Hiển (Scrum Master) đã chỉ ra một số điều như sau mà team cũng
như bản thân mình gặp phải:

- Nên break out task thành testable small task
- QA là người đưa ra quyết định, Dev phải chạy theo :D
- Thay đổi cách tư duy, làm nhỏ nhưng mà phải ngon

Hi vọng với những thay đổi nhỏ nhỏ này, mình có thể khá hơn trong thời gian tới.


# Kỹ thuật

Hôm nay mình đã mất công tìm hiểu và config được checkstyle cho dự án
Stockbook ở công ty.
Đi kèm với plugin này là PMD, FindBugs, những recommended plugin cho Java.


Cuối giờ, mình định compare giữa việc dùng gson và dùng một thư viện khác
để serialize và deserialize object vào redis. Kết quả cuối cùng mình
nhận được là: `early optimization is the root of all evil`