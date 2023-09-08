# Học viết file readme.md
## **1.Tải tiện ích hỗ trợ**
- Ở bài này mình sử dụng VIM để mở và viết file dưới dạng hộp thoại lệnh
- Bình thường các bạn cứ tải Markdown All in One về để dùng, nó rất hữu ích
## **2. Giới thiệu một vài tính năng cơ bản**
- Dùng dấu # để tạo heading cho văn bản

### **2.1 FONTS**
- Nếu các bạn đã quen với latex thì khi sử dụng phần sẽ thấy cực kỳ dễ dàng
- Tiếp theo mình sẽ hướng dẫn cách dùng dấu \*\* ...\*\*để viết chữ in đâm và dùng \_ ... \_ hoặc \* ... \* để tạo chữ in nghiêng, **Ví dụ:** *Nghieng*. Để giữ lại ký tự đặc biệt thì dùng dấu \ đằng trước ký tự đặt biệt, tương tự như latex không khác gì cả.

### **2.2 Quatation**
- Sử dụng dấu \> để tạo **Quatation**
> **Ví dụ** đây là một ví dụ về Quatation (tạo vùng chú ý)
> Đây là một ví dụ khác.
- Dùng dấy \`...\` để nhấn mạnh chữ trong câu
Đây là `Ví dụ`

### **2.3 Tạo bảng**
|STT|Cột 1|Cột 2|Cột 3|
|---|-----|-----|-----|
|1|NCC|x|y|
|2|Footprint|ABC|DEF|

### **2.4 Code Block**
- Sử dụng viết thêm 1 đoạn code vào trong file dùng \`\`\`c để bắt đầu đoạn code và dùng \`\`` để kết thúc đoạn code
> Dưới đây là một `Ví dụ`
```c
#include <stdio.h>
void main
{
    printf("Hello World");
}
```
- Ngoài ra còn có thể thay các dấy trên bằng nút TAB
    Code block tạo bằng TAB

### **2.5 Gạch ngang kết thúc 1 phần nào đó**
- \-\-\- hoặc \*\*\* để kết thúc 1 phần, dưới đây là ví dụ:
---
***

### **2.6 Chèn link vào file**
- Để chèn link vào ta sử dụng cú pháp: 
>`[Tên link](Đường link đến chính)`
ví dụ: [Google](https://www.google.com.vn/)

### **2.7 Chèn ảnh**
- Để chèn ảnh cần ảnh và file README.md đặt cùng 1 folder.
Ví dụ:
![example](sky.png)

## **2.8 Biểu đồ**
- Dùng mermaid: [mermaid](http://mermaid.js.github.io/mermaid/#/) hoặc PlanUML

# **3. Import file**
- Dùng @import "file"

## **3.1 Math**
- Để viết công thức toán cao cấp cần đặt giữa 2 đầu \$
$\alpha$
$\varphi$
Ứng dụng công thức ở trên vào ví dụ sau:
$x^2$
$x^(n+1)$
$x_1$
***
Mũi tên: $\to$
Vô cùng: $\infty$
Phân số: $\frac[1][2]$
Căn thức: $\sqrt[n][k]$
***
Xem thêm phần toán học tại: <http://www.latex4techníc.com/>

