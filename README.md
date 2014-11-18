#Regular Expression for Algerian Mobile Phone Numbers
# التعبير النمطي لارقال الجوال الجزائرية

##Mobile number format
#نمط رقم الجوال
     ^(00213|\+213|0)(5|6|7)[0-9]{8}$
    
##Javascript Example
##مثال جافا سكريبت

```javascript

var reg=  /^(00213|\+213|0)(5|6|7)[0-9]{8}$/

reg.test("021481515"); // false
reg.test("0770123456"); // true
reg.test("0550123456"); // true
reg.test("0440123456"); // false
reg.test("0660123456"); // true
reg.test("00213660123456"); // true
reg.test("+213660123456"); // true

```
