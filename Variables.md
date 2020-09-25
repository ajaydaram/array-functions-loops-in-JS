# What are variables in Javascript ?

Variables are like **containers** or **bucket** that holds data for the later use.
The key word to create a container or bucket to hold data is **var**, **let** and **const**. The difference between each keywords can be discussed later.

## Example : 1
```
var name = "John Doe";
let age = 33;
const place = "Singapore";

console.log(name);
```
# conditions in Javascript ?

```
 if (condition is true ) {
 
    //run this code 
    
  }else if(condition is true) {
    
    // rrun this other code
  
  }else{
    //Default cool code
   }
```

 # Difference between **=** and **==** and ***===***
 
 ### 1. Assigning a value
  
In JavaScript "=" sign is used to assign values to the variable. We already discussed that the keyword *var* creates a memory location which is a container and this container is empty oe undefined. you assign a value with the *=*

```
 
 var name = "John Doe" 
 
 
```

### 2. Comparing two values 

In JavaScript **==** sign is used to compare two values. 

```
var name == "John Doe";  // This is wrong way of assigning a value, actually you are comparing name and John Doe wheter they two are equal.

```
### 3. strict comparision 

```  
  "John Doe age is " === "33";
  "John Doe age is " === 33; 
  
 

```
The value 33 is kept in between quatation. That means javascript understood it as a string. The strict opeator not only compare age is equal to 33, but also it compare which data type. Here the datatype are equal  and without the quotation mark the data type is not equal. 
