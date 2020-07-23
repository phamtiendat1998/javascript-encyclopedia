# Biến và kiểu dữ liệu

##### Biến

```
var yourVariable; // Khai báo viến bằng từ khóa var
yourVariable = 0; // Gán giá trị cho biến
var youVariable = 0; // Vừa khai báo vừa gán giá trị
```

##### Kiểu dữ liệu

Javascript là một ngôn ngữ có kiểu động. Chúng ta không cần khai báo kiểu dữ liệu. Kiểu dữ liệu sẽ được hình thành khi mã được thực thi

Theo tiêu chuẩn ECMAScript mới nhất xác định có 9 kiểu:

* 7 kiểu sơ khai (primitive):
  * Undefined
  * Null
  * Boolean
  * Number
  * String
  * Symbol (Chỉ có từ tiêu chuẩn ECMAScript 6)
  * Bigint
* Object
* Function (Kiểu phi dữ liệu)

Chúng ta có thể xác định kiểu dữ liệu bằng toán tử **typeof**

```
console.log(typeof 6);
// Output: "number"
console.log(typeof 'your');
// Output: "string"
```

Tham khảo:

[https://developer.mozilla.org/vi/docs/Web/JavaScript/Data_structures](https://)
