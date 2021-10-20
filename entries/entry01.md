# Entry 1
## Arrays
##### 10/19/2021

## Context/Basics
### Over the past couple of weeks working on "arrays" has been interesting. It was tough to get a hand on it at first but over tasks, and assignments we did it became more clear. From my experience I can now say that an array is a variable that is used to store multiple values/data. With arrays you can make things like: grocery list, to do list, goals, bucket list, books to read, etc. With the function array we can personalize our list by adding, removing, and even changing our items. Writing javascript to make an array was definatly something different. Compared to my pervious learnings of HTML, CSS we did not use numbers or backets very much, but in this case it was very important because it was essential. 

## Arrays + Javascript

### All array lists are encloseed with brackets. Brackets are very important especially in when making arrays because brackets contain elements or variables.
  #### var practice = prompt[1]

### There are some things that I needed to know/keep in mind when I made arrays. Inside arrays we use quotatoin marks or in other words known as strings/"". the function string is used to represent text.  
  #### alert("hello")
### The result of this code would be: hello

### To make a simple array the code would look like: 
  #### var dessert = ["tiramisu, ice-cream, cheesecake"];
### As a result on our screen I would expect to see;
  ### tiramisu, ice-cream, cheesecake

### To point out something certain in my list, I would usually count starting from 1 and so forward. However, in javascript the numbers/index begins with 0. 
### For example using the dessert example I have above, there are 3 things on the list (tiramisu, icecream, cheesecake). First on the list would generally be tiramisu and second icecream, etc. If I wanted to point out "Cheesecake" using javascript it would look something like:
 #### var dessert = ["tiramisu, ice-cream, cheesecake"];
 #### var secondItem = dessert[2]

### Regular                                     Javascript
#### 1 tiramisu                                  0 tiramisu
#### 2 icecream      -------->                   1 icecream
#### 2 cheesecake                                2 cheesecake
 ### As a result the ouput would be cheesecake
 

## Direct Changes to the List

### Example Data: 
### var practice = [4,7,9,18]

###       Code      What does it do?                      Example                 Output
          push       adds to the end                  practice.push(12)           4,7,9,18,12   
          pop       removes data from the end         practice.pop()              4,7,9
          shift     removes data from beginning       practice.shift()            7,9,18
         unshift    adds to the beginning             practice.unshift(27)        27,4,7,9,18
 
 ## Struggles 
 

[Next](entry02.md)

[Home](../README.md)
