# viony-vexanium.com
algho test

These 2 arrays will make a sentence, what would it be?

arr1 = ['A', 'B', 'D', 'E', 'G', 'H', 'I', 'R', 'Q', 'O', 'N', 'K', 'S', 'T', 'U', 'V', 'Y']

arr2 = [32, 26, 37, 28, 27, 34, 31, 30, 41, 37, 25, 37, 33, 24, 27, 35, 34, 30, 36, 41, 24, 31, 26, 41, 33, 37, 40, 38, 41, 34, 30, 41, 40, 30, 24, 41, 39, 31, 31, 29, 28]

myResult:

i found that arr1 can make a sentence like " give her ride to grand street no ... "
and i put array 2 as number.

i using "looping type foreach" to use each of number in arr2.
Because arr2 have duplicate value, i rid it with $clear_array. This make the result more clean


___----- my alghom -----____

<?php

$arr1 = ['A', 'B', 'D', 'E', 'G', 'H', 'I', 'R', 'Q', 'O', 'N', 'K', 'S', 'T', 'U', 'V', 'Y'];

$arr2 = [32, 26, 37, 28, 27, 34, 31, 30, 41, 37, 25, 37, 33, 24, 27, 
35, 34, 30, 36, 41, 24, 31, 26, 41, 33, 37, 40, 38, 41, 34, 30, 41, 40, 30, 24, 41, 39, 31, 31, 29, 28];

$clear_array=array_unique($arr2);

foreach ($clear_array as $i){   

echo $arr1[4], $arr1[6], $arr1[15], $arr1[3]."&nbsp". $arr1[5], $arr1[3], $arr1[7]."&nbsp".$arr1[0]."&nbsp". $arr1[7], $arr1[6],
$arr1[2], $arr1[3]."&nbsp". $arr1[13], $arr1[9]."&nbsp".$arr1[4], $arr1[7], $arr1[0], $arr1[10], $arr1[2]."&nbsp". $arr1[12], $arr1[13],
$arr1[7], $arr1[3], $arr1[3],$arr1[13]."&nbsp".$arr1[10], $arr1[9]."."."&nbsp".$i."<br>";

}
?>


# i really sorry for late send. Jl. Karet was flooded. Welost electricity monday and tuesday.
thanks you for understand.
