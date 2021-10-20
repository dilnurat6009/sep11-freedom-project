# Entry 1
## Arrays
##### 10/19/2021

## Context/Basics
Over the past couple of weeks working on "arrays" has been interesting. It was tough to get a hand on it at first but over tasks, and assignments we did it became more clear. From my experience I can now say that an array is a variable that is used to store multiple values/data. With arrays you can make things like: grocery list, to do list, goals, bucket list, books to read, etc. With the function array we can personalize our list by adding, removing, and even changing our items. Writing javascript to make an array was definatly something different. Compared to my pervious learnings of HTML, CSS we did not use numbers or backets very much, but in this case it was very important because it was essential. 

## Arrays + Javascript
* All array lists are encloseed with brackets. Brackets are very important especially in when making arrays because brackets contain elements or variables.
``` JS
  var practice = prompt[1]
```

* There are some things that I needed to know/keep in mind when I made arrays. Inside arrays we use quotatoin marks or in other words known as strings/"". The function string is used to represent text.  
``` JS
  alert("hello")
```
The result of this code would be: hello

* To make a simple array the code would look like: 
``` JS
var dessert = ["tiramisu, ice-cream, cheesecake"];
```
As a result on our screen I would expect to see;
  tiramisu, ice-cream, cheesecake

* To point out something certain in my list, I would usually count starting from 1 and so forward. However, in javascript the numbers/index begins with 0. 
For example using the dessert example I have above, there are 3 things on the list (tiramisu, icecream, cheesecake). First on the list would generally be tiramisu and second icecream, etc. If I wanted to point out "Cheesecake" using javascript it would look something like:
 
 ``` JS
 var dessert = ["tiramisu, ice-cream, cheesecake"];
 var secondItem = dessert[2]
```

```
 Regular                                     Javascript
 1 tiramisu                                  0 tiramisu
 2 icecream      -------->                   1 icecream
 2 cheesecake                                2 cheesecake
 ```
 As a result the ouput would be cheesecake
 

## Direct Changes to the List

Example Data: 
``` JS
var practice = [4,7,9,18]
```
```
          Code      What does it do?                      Example                 Output
          push       adds to the end                  practice.push(12)           4,7,9,18,12   
          pop       removes data from the end         practice.pop()              4,7,9
          shift     removes data from beginning       practice.shift()            7,9,18
         unshift    adds to the beginning             practice.unshift(27)        27,4,7,9,18
 ```
 
 
 ## Struggles 
 The Grocery List parnter activity was something that was enjoyable but my partner and I definatly needed a push at certain moments. Specfically, Task #2 asked us to create a var that would delete the last item on the list by notifiying the user with whats being removed. To begin me and my partner Marisol did have an idea as to what had to be used. Because it was asking us to *remove from the end* that meant we had to use ```JS .pop ``` element. I remember trying is variation of code:
 ``` JS
 var lastItem = grocerylist.pop();
 alert("removing :")
```
Though this code was working to delete the last item on the list, it was not notifying the user of what was being removed, it simply just said removed and deleted the last item. We tried a couple of other things like adding brackets with numbers. However, when we wrote the index # of the item it simply did not make sense because the # would change frequently when adding or removing things from the list. We then asked William to check our work and advise us. He told us that in order for the name of the item to appear we had to specify the variable in the parenthesis. By writing down the variable in the parenthesis, that would tell Java to *remove lastItem*. This makes sense because I added another variable and sent the function to pop, therefore, thats the factor that actually removed. My final code eneded up looking like:
``` JS
var lastItem = groceryList.pop();
alert("Removing: " + lastItem)
```
[Next](entry02.md)

[Home](../README.md)
