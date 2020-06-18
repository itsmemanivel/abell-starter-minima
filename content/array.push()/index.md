# {{meta.title}}



<img  style="width:100%;height:100%;" src="assets/undraw_moving_forward_lhhd.png" />

**Push()** function in array is used to append the data and mostly  it is used for  append the **string**.
Because are not treated as  array in normal.


## Methods

```js
//declare an empty array
var array=[];

//declare a string
var string1= "Hello! World";
var string2= "This is string";


//assing string to an array;
array = string1;

//invalid syntax, it will assing the value as string
console.log(array);  // array = "Hello! World"

array = string2;
console.log(array);  // array = "This is string"


//using push method
array.push(string1);


console.log(array); //array = ["Hello! World"]

array.push(string2);
console.log(array); //array = ["Hello! World", "This is string"]



```

## Effective

Make use this syntax  by replacing your old  string inserting methods  :-)  
