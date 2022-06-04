# My-examples
These are my code examples, all examples are written to the README file

## Java Script

### An example of a script looking for the area of a rectangle
```
const height = 40; <br>
const widt = 70; <br>
let square = height * widt; <br>
<br>
console.log(square);
```
### An example of a code with IF
```
const randomNumber = Math.floor(Math.random() * 100); 

if (randomNumber < 20){            
    console.log('randomNumber меньше 20'); 
} else if (randomNumber > 50) { <br>
    console.log('randomNumber больше 50'); 
} else{ 
    console.log('randomNumber больше 20, и меньше 50'); 
}
```
### The same example with using the Switch Case
```
const randomNumber1 = Math.floor(Math.random() * 100); 

switch(true){ 
    case (randomNumber1 < 20) : 
         console.log('randomNumber1 меньше 20'); 
         break; 
    case (randomNumber1 > 50) : 
        console.log('randomNumber больше 50'); 
        break; 
    default : 
    console.log('randomNumber1 больше 20, и меньше 50'); 
} 
```
### The example of FOR cycle
```
for(let i = 10; i <= 50; i++){
    if(i % 2 == 0){
        console.log(i);
    }
    
}
```

### The example of While cycle
```
let num = 21;

while(num <= 67){
num++;
if (num%2) console.log(num);
}
```
