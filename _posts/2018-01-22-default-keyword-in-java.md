---
layout: post
title: Từ khóa default trong Java, debug on condition
---

# Bài học

Từ khóa default trong Java được dùng trong switch-case và cách dùng thứ hai là trong interface của Java 8.

Rút cục thì dùng default trong interface để làm gì?
Bình thường interface chỉ liệt kê các abstract method, các class implement interface đó cần implement lại danh sách các abstract method.

Để khắc phục điều này, Java 8 cho ta khái niệm default method, cho phép
interface có method được thực thi sẵn mà ko làm ảnh hưởng các class implement cái interface này.


# IntelliJ debugging condition

Mình thấy có lỗi null ở trong một request, muốn reproduce lại nhưng tập
kết quả khá nhiều. Đang loay hoay thì có anh đồng nghiệp hướng dẫn cách
đặt điều kiện cho break point, mình thấy cái tip này rất hữu ích.