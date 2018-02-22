---
layout: post
title: Series Lập trình đời sống: break, continue
# img: js-1.png # Add image post (optional)
tags: [easy-programming, tutorial] # add tag
---

# Dẫn nhập

A đang ngồi fix bug, bỗng dưng thấy có người B cần fix logic error, A nhảy vào giúp (A là người tốt mà). Rồi A nhận ra B code cả đống mà chẳng hiểu mình code cái gì, A đến phát điên lên vì bug của mình còn chưa fix xong lại còn phải gánh thêm bug giời ơi đất hỡi ở đâu rơi xuống :'(

Vì là người tốt nên A quyết định chỉ dẫn cho người đời biết thế nào là lập trình một cách đơn giản và dễ hiểu nhất, để những người sau không còn hỏi A vì những con bug vớ vẩn nữa.

# Nội dung

## Về `break`

Người ta biết được ý nghĩa của từ "break" trong tiếng Anh là "thoát ra", "đập vỡ". `break` trong lập trình cũng có ý nghĩa tương tự như vậy.

Ví dụ:

- Người môi giới bất động sản dẫn bạn đi xem nhà trên cả một khu phố dài. Bạn sẽ tìm xem có ngôi nhà nào ưng ý hay không.

```
for nhà in dãy_phố:
    if ưng_ý(nhà):
        break  # đã tìm được nhà ưng ý
        # bạn có thể gào to lên: "tôi lấy cái nhà này"
```

Nếu bạn không báo hiệu cho người môi giới biết bạn đã tìm được nhà ưng ý thì anh ta cứ dẫn bạn đi hết cả dãy nhà mà không cần quan tâm bạn đã tìm được nhà hay chưa. Khổ thế chứ lị.

- 
