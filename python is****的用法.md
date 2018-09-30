# python is**** 的用法

## 1️⃣Python isalnum()方法
- Python isalnum() 方法检测字符串是否由字母和数字组成。

```
#!/usr/bin/python
# -*- coding: UTF-8 -*-
 
str = "this2009";  # 字符中没有空格
print str.isalnum();
 
str = "this is string example....wow!!!";
print str.isalnum();
############################
True
False
```
## 2️⃣Python isalpha()方法

- Python isalpha() 方法检测字符串是否只由字母组成。

```
#!/usr/bin/python

str = "this";  # No space & digit in this string
print str.isalpha();

str = "this is string example....wow!!!";
print str.isalpha();
############################
True
False
```

## 3️⃣Python isdecimal()方法

- Python isdecimal() 方法检查字符串是否只包含十进制字符。这种方法只存在于unicode对象。
- 注意:定义一个十进制字符串，只需要在字符串前添加 'u' 前缀即可。

```
#!/usr/bin/python


str = u"this2009";  
print str.isdecimal();

str = u"23443434";
print str.isdecimal();
############################
False
True
```

## 4️⃣Python isdigit()方法
- Python isdigit() 方法检测字符串是否只由数字组成。


```
#!/usr/bin/python

str = "123456";  # Only digit in this string
print str.isdigit();

str = "this is string example....wow!!!";
print str.isdigit();
############################
True
False
```

## 5️⃣Python islower()方法

- Python islower() 方法检测字符串是否由小写字母组成。

```
#!/usr/bin/python

str = "THIS is string example....wow!!!"; 
print str.islower();

str = "this is string example....wow!!!";
print str.islower();
############################
False
True
```

## 6️⃣Python isnumeric()方法
- Python isnumeric() 方法检测字符串是否只由数字组成。这种方法是只针对unicode对象。

- 注：定义一个字符串为Unicode，只需要在字符串前添加 'u' 前缀即可

```
#!/usr/bin/python

str = u"this2009";  
print str.isnumeric();

str = u"23443434";
print str.isnumeric();
############################
False
True
```

## 7️⃣Python isspace()方法

- Python isspace() 方法检测字符串是否只由空格组成。


```
#!/usr/bin/python

str = "       "; 
print str.isspace();

str = "This is string example....wow!!!";
print str.isspace();
############################
True
False
```

## 8️⃣Python istitle()方法
- Python istitle() 方法检测字符串中所有的单词拼写首字母是否为大写，且其他字母为小写。


```
#!/usr/bin/python


str = "This Is String Example...Wow!!!";
print str.istitle();

str = "This is string example....wow!!!";
print str.istitle();
############################
True
False
```

## 9️⃣Python isupper()方法

- Python isupper() 方法检测字符串中所有的字母是否都为大写。

```
#!/usr/bin/python

str = "THIS IS STRING EXAMPLE....WOW!!!"; 
print str.isupper();

str = "THIS is string example....wow!!!";
print str.isupper();
############################
True
False
```

## 1️⃣0️⃣Python isidentifier()方法
## 1️⃣1️⃣Python isprintable()方法



