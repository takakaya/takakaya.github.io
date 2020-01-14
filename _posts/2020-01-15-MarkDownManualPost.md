---
layout: page
title: Markdown trong viết blog
image: /img/markdown.png
topic: Security
---

*Markdown* là chuẩn viết tài liệu kỹ thuật trong phát triển phần mềm. Sử dụng trong viết những bài blog như này.

# Lịch sử của Markdown

Năm 2004, John Gruber là một designer, blogger chuyên viết về các sản phẩm của Apple đã nảy ra ý tưởng tạo ra một ngôn ngữ cho các tài liệu web với phương châm dễ viết, dễ đọc ở định dạng tự nhiên và có thể chuyển thành HTML.
Chính vì thế Markdown ra đời.

## ***Tiêu đề*** 

Các tiêu đề h1, h2, h3 cho đến h6 có thể viết bằng cách thêm số lượng ký tự \# tương ứng vào đầu dòng. Một ký tự \# tương đương với h1, 2 ký tự \# tương đương với h2, ... Tuy vậy, để viết một bài viết dễ đọc thì hiếm khi cần dùng đến quá 3 ký tự này.

## ***Bôi đậm và in nghiêng***

Kẹp một từ ở đầu và cuối bằng ký tự * để in nghiêng, 2 ký tự \*\* để bôi đậm, và 3 ký tự \*\*\* để vừa in nghiêng vừa bôi đậm. Sử dụng chữ gạch ngang bằng cách thêm \~ vào 2 đầu nội dung.

## ***Link***

Viết link trong markdown bằng cách cho alt text vào trong ngoặc vuông và link thật vào trong ngoặc đơn (). Ví dụ:
[TakaKaya](https://takakaya.github.io)

## ***Hình ảnh***

Chèn hình ảnh trong markdown bằng cách thêm ! vào kí tự đầu tiên, sau đó ghi alt text và link ảnh vào trong ngoặc vuông [] và ngoặc đơn ().
![Ảnh minh họa](https://drive.google.com/open?id=1BvOWbsy8XA_ebIHBh79_bD5vwUEVnogz)

## ***Định dạng danh sách***

Để định đạng một đoạn văn bản thành các gạch đầu dòng trong markdown, bạn dùng ký tự \* và một dấu cách ở mỗi ý và dùng thêm 2 dấu cách ở đằng trước nếu muốn lùi vào một level.

* Ruby
* PHP
  * Laravel
  * Symfony
  * Phalcon
* Python
  * Flask
    * Jinja2
    * WSGI1.0 
  * Django 

Nếu bạn muốn dùng số để đánh dấu thì viết số và một dấu chấm .

1. number one
2. number two
3. number three

## ***Trích dẫn***

Cách viết một trích dẫn giống hệt khi bạn vẫn trả lời bình luận hay dẫn chứng trong các diễn đàn: sử dụng ký tự >

> takakaya trang blog mới mở

## ***Mã code***

Có 2 loại code trong markdown là inline code (code nội dòng) và code block (Khối code riêng). Inline code được biểu diễn trong 2 dấu phẩy ngược.

`Đây là code nội dòng`

còn khối code dùng với cặp 3 ký tự phẩy ngược.

```Đây biểu diễn khối code```

## ***Vẽ bảng***

Vẽ bảng trong Markdown sẽ hơi khó nếu bạn chưa quen. Các cột được tách nhau bằng dấu ngăn thẳng đứng \| và header được tách với content bằng dấu gạch ngang \-.


| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

Ở dòng ngăn cách giữa header và content bạn sẽ thấy ký hiệu căn lề trái phải (cột 2 và cột 3) bằng dấu :.
