# 1. Variable

1. Khởi tạo biến :

```php
// Struct :
$variableName = value;

// Eg :
$myName         = "Kieuvu";   // String Variable
$myLuckyNumber  = 39;         // Number Variable
$isMale         = true        // Boolean Variable
```

1. Xuất biến : 

```php
// Struct :
echo $variableName;

// Eg:
echo $myName . $myLuckyNumber . $isMale;           // Kieuvu39true
echo $myName ." ". $myLuckyNumber ." ". $isMale;   // Kieuvu 39 true
echo 'My name is '.$myName;                        // My name is Kieuvu 
```

1. Xác định kiểu dữ liệu : 

```php
// Struct :
gettype($varName);
var_dump($varName);
is_numberic($varName);
is_array($varName);
is_string($varName);
is_object($varName);

// Eg:
var_dump($myLuckyNumber);            // Boolean
echo gettype($myName);               // String
echo(is_numberic($myLuckyNumber));   // true "1"
echo(is_array($myName));             // false " "
```

1. Ép kiểu :

```php
// Struct :
settype($varName,"type");
(type)$varName;

// Eg:
$floatNum  = 1.2222;
$stringNum = 123asd;

echo settype($floatNum,"interger");   // 1
echo (int)$stringNum ;                // 123
```

1. Hằng số :

```php
// Struct :
define("constantName",value);

// Eg :
define("PI", 3.14);
echo PI;  // 3.14
```