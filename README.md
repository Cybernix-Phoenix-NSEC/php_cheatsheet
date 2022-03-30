# php_cheatsheet
This repo contains the cheatsheet of PHP session


//Variable

<?php  
$str="hello string";  
$x=200;  
$y=44.6;  
echo "string is: $str <br/>";  
echo "integer is: $x <br/>";  
echo "float is: $y <br/>";  
?>  

<?php  
$x=5;  
$y=6;  
$z=$x+$y;  
echo $z;  
?>  

//PHP Variable: case sensitive

<?php  
$color="red";  
echo "My car is " . $color . "<br>";  
echo "My house is " . $COLOR . "<br>";  
echo "My boat is " . $coLOR . "<br>";  
?>  
<!-- PHP Variable: Rules -->

<?php  
$a="hello";//letter (valid)  
$_b="hello";//underscore (valid)  
  
echo "$a <br/> $_b";  
?>  

Operators	Additional Information	Associativity


[	array()	left
**	arithmetic	right
++ -- ~ (int) (float) (string) (array) (object) (bool) @	increment/decrement and types	right
instanceof	types	non-associative
!	logical (negation)	right
* / %	arithmetic	left
+ - .	arithmetic and string concatenation	left
<< >>	bitwise (shift)	left
< <= > >=	comparison	non-associative
== != === !== <>	comparison	non-associative
&	bitwise AND	left
^	bitwise XOR	left
|	bitwise OR	left
&&	logical AND	left
||	logical OR	left
?:	ternary	left

//Conditional Statement

<?php  
$num=12;  
if($num<100){  
echo "$num is less than 100";  
}  
?>  


<?php  
$num=12;  
if($num%2==0){  
echo "$num is even number";  
}else{  
echo "$num is odd number";  
}  
?>  




if (condition1){    
//code to be executed if condition1 is true    
} elseif (condition2){      
//code to be executed if condition2 is true    
} elseif (condition3){      
//code to be executed if condition3 is true    
....  
}  else{    
//code to be executed if all given conditions are false    
}    


<?php  
    $marks=69;      
    if ($marks<33){    
        echo "fail";    
    }    
    else if ($marks>=34 && $marks<50) {    
        echo "D grade";    
    }    
    else if ($marks>=50 && $marks<65) {    
       echo "C grade";   
    }    
    else if ($marks>=65 && $marks<80) {    
        echo "B grade";   
    }    
    else if ($marks>=80 && $marks<90) {    
        echo "A grade";    
    }  
    else if ($marks>=90 && $marks<100) {    
        echo "A+ grade";   
    }  
   else {    
        echo "Invalid input";    
    }    
?>  


//For Loop

for(initialization; condition; increment/decrement){  
//code to be executed  
}  


<?php    
for($n=1;$n<=10;$n++){    
echo "$n<br/>";    
}    
?>  

//Functions
function functionname(){  
//code to be executed  
}  

<?php  
function sayHello(){  
echo "Hello PHP Function";  
}  
sayHello();//calling function  
?>  



<?php  
function sayHello($name){  
echo "Hello $name<br/>";  
}  
sayHello("Sonoo");  
sayHello("Vimal");  
sayHello("John");  
?>  

//Arrays

$season=array("summer","winter","spring","autumn");  

OR

$season[0]="summer";  
$season[1]="winter";  
$season[2]="spring";  
$season[3]="autumn";  


<?php  
$season[0]="summer";  
$season[1]="winter";  
$season[2]="spring";  
$season[3]="autumn";  
echo "Season are: $season[0], $season[1], $season[2] and $season[3]";  
?>  

