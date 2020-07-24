# Kiểu dữ liệu Number trong javascript



Kiểu number đại diện cho cả 2 kiểu số nguyên và số thập phân (dấu phẩy động)

```
let n = 123;
n = 12.345;
```

Các thao tác cho giá trị thuộc kiểu number: + - * /

Bên cạnh giá trị number thông thường, còn có giá trị number đặc biệt (special numberic value):

* Infinity, -Infinity

```
alert( 1 / 0 ); // Infinity
alert( Infinity ); // Infinity
```

* NaN : đại diện cho một phép tính lỗi, là kết quả của phép toán **không chính xác** hoặc **không xác định**

```
alert( "not a number" / 2 ); // NaN
alert( "not a number" / 2 + 5 ); // NaN
```
