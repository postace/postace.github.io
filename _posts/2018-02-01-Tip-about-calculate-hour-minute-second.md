---
layout: post
title: A tip about calculate hours, minutes and seconds
---

Tình cờ làm cái challenge trên codewars và mình đã tìm ra lối viết code để tính giờ, phút, giây dễ dàng hơn:

Cho t là số giờ dạng float, tính số giờ, phút, giây nguyên từ số t này?

Có 2 cách:

Cách 1: Tính lần lượt số giờ nguyên, rồi phút nguyên và số giây nguyên

Cách 2: 
```javascript
  h = Math.floor(t);
  m = Math.floor(t * 60 % 60)
  s = Math.floor(t * 3600 % 60)
```
