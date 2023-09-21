
- SAU KHI BUILD XONG IMAGE
- VÀO CODE Ở ĐÂU ĐÓ THÊM VÀO ĐOẠN CODE SAU ĐỂ KIỂM TRA:
```
<?php
echo xdebug_info();
?>
```
- Nó sẽ báo lỗi trên ide là không có hàm xdebug_info nhưng không quan tâm
- Lúc này khi refesh lại trình duyệt nó sẽ hiển thị ra thông tin về xdebug đã được cài đặt
- Trong đó để ý chỗ Step Debugger nếu nó là enabled là cài xdebug thành công

```
Feature	Enabled/Disabled	Docs
Coverage	✘ disabled	⊕
GC Stats	✘ disabled	⊕
Profiler	✘ disabled	⊕
Step Debugger	✔ enabled	⊕
Tracing	✘ disabled	⊕
```
