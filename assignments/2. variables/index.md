1. In code below "Mark" is a string.  What is name?
```js
var name = "Mark";
//name is a variable.
```

2. Find the error if any
```js
  var product cost = 3.45;
  //var product_cost = 3.45;  (No space between variables )
```

3. Write `Right or Wrong` next to the code below.

```js
  "Hello World"  //(Right)
  'Hello World"  //(Wrong)
  "Hello World'  //(wrong)
  'Hello World'  //(Right)
```

## Write `VALID` and `INVALID` infront of the variable name defined below
```js
var man;                  //(Right)
var 1girl;                //(wrong)
var woman3;               //(Right)
var -girl;                //(Wrong)
var blackDog;             //(Right)
var 42;                   //(Wrong)
var $42;                  //(Wrong)
var userName;             //(Right)
var x, y, z;              //(Right)
var x = 5, y = 6, z = 7;  //(Right)
var x = 5 + 10 + 2;       //(Right)
```

## Basic Operations

Mathematical Operations:

Solve this using mathematical operations. (+, -, *, / , etc)

```js
var amount = 2080;
// Define a new variable and store the value that is 80 less then the value of amount.
  var sub = amount - 80 ;
// Define a new variable and store the value that is 200 more then the value of amount.
  var add = amount + 200 ;
// Define a new variable and store the value that is 4 times the value of amount.
  var mul = amount * 4 ;
// Define a new variable and store the reminder when the value of amount is  divided by 21.
```
  var mod = amount % 21;

Logical Operation:

Solve this using logical operations. (<, >, &&, ||)

```js
var johnAge = 45;
var markAge = 35;

// Check who is older eithe John or Mark
// Check who is younger
// Check if their age is equal
  if(johnAge == markAge)
  {console.log("mark and john both age are same");}
  else{
        if(johnAge > markAge)
            {
              console.log("john is older");
              console.log("mark is younger");  
            }
        else
            {
              console.log("mark is older");
              console.log("john is younger");  
            }
      }
// Create a new variable and assign the age of john to new variable.
// Check if john is equal to or greater then mark.
// Check if john is less then or equal to mark.
var john_age = johnAge;
  if(john_age == markAge)
  {console.log("mark and john both are same age");}
  else{
        if(john_age > markAge)
            {
              console.log("john age is greater than mark");
            }
        else
            {
              console.log("john age is less than mark");  
            }
      }
    

// Calculate the average age of john and mark and assign to a new variable.
```
var avg_age = (johnAge + markAge)/2;