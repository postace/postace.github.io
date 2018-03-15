---
layout: post
title: Remote debugging
---

# Remote debugging with Spring, Maven, IntelliJ

Đôi khi sẽ có lúc bạn chạy spring app trên server dev, ko phải máy local của bạn và bạn muốn debug/log nó.
Dưới đây là step by step hướng dẫn bạn làm điều đó với IntelliJ:

- Trong IntelliJ chọn Run > Edit Configurations

- Chọn New Remote configuration. Mặc định IntelliJ sẽ bootstrap với những thông số sau:
   `-agentlib:jdwp=transport=dt_socket,server=y,suspend=n,address=5005`
   và tất nhiên là bạn không cần chỉnh sửa chúng.

- Trên dev server, chạy app bằng dòng lệnh sau:
    `mvn clean spring-boot:run -Drun:jvmArguments="-agentlib:jdwp=transport=dt_socket,server=y,suspend=n,address=5005"`

- All done, giờ chỉ việc bấm Debug trên giao diện IntelliJ là xong, có thể remote debug được rồi đó.
