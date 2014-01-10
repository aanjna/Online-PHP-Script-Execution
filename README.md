Online-PHP-Script-Execution
===========================

Operater and data types in PHP script

<html>
<head>
<title>Online PHP Script Execution</title>
</head>
<body>
<?php
// File Description: PHP Operators Tutorial
 
////Arithmetic Operators
$value1 = 5;
$value1 = $value1 + 5;
echo "Addition Value: $value1 <br>";
 
// Modulus %
$value2 = 7;
$value2 = $value2 % 2;
echo "Modulus Value: $value2 <br>";
 
//Increment
$value3 = 5;
$value3++;
echo "Increment Value: $value3 <br>";
 
//Decrement
$value4 = 100;
$value4--;
echo "Decrement Value: $value4 <br>";
 
////Assignment Operators
$a = 6;
$b = 4;
$a = $b; 
echo "A now contains: $a";
 
$a += $b; // $a = $a + $b;
$a -= $b; // $a = $a - $b;
 
 
////Comparison Operators
$one = 1;
$two = 2;
 
//True or False
 
//Is Equal To ==
$one == $two; //return FALSE
$one == 1; //return TRUE
 
//Is Not Equal To !=, <>
$one != $two; //return TRUE
$one <> $two; //return TRUE
 
// Is Greater or Less Than >, <
$one > $two; // return FALSE
$one < $two; //return TRUE
 
// Is Greater or Less Than or Equal To >= , <=
$one >= $two; //return FALSE
$one <= $two; //return TRUE
 
////Logical Operators
 
// AND Operator &&
($one > 0 && $two > $one); // return true
// (true AND true) // return true
// (true && true) // return true
// (true && false) // return false
// (false && true) // return false
// (false && false) // return false
 
// OR Operator ||
($one < 0 || $two > $one); // return true
// (false || true) //return true
// (false || false) //return false
// (true || false) // return true
// (true || true) // true
 
// NOT Operator !
!($one == $two); //return TRUE
//!(true) //return FALSE
//!(false) //return TRUE
?>
</body>
</html>

