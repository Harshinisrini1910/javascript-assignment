# javascript-assignment

# 1.js
```
let age=30;
const name="Alice";
 name="bob";
 console.log(name)

```
# output
![Screenshot 2024-07-06 at 11 45 51 AM](https://github.com/Harshinisrini1910/javascript-assignment/assets/161415847/3a167701-cd82-46e0-b825-06fc1dae17ef)
# 2.js
```
const add=(a,b)=>{
    console.log(a+b) ;
}
add(9,11);


```

# output
![Screenshot 2024-07-06 at 11 46 10 AM](https://github.com/Harshinisrini1910/javascript-assignment/assets/161415847/59adce42-f3e8-403d-85ba-d2bd4d9cf4a7)

# 3.js
```
let name="Alice";
let age=30;
let txt=`Hello,${name} Your age is ${age}.`;
console.log(txt);

```

# output
![Screenshot 2024-07-06 at 11 46 31 AM](https://github.com/Harshinisrini1910/javascript-assignment/assets/161415847/7ad9b5db-535d-4d09-ba26-2e32d2c275cb)

# 4.js
```
const person={
    firstName: "Alice", 
    lastName: "Johnson"
}
const{firstName,lastName}=person;
console.log(firstName);
console.log(lastName)

```

# output
![Screenshot 2024-07-06 at 11 46 47 AM](https://github.com/Harshinisrini1910/javascript-assignment/assets/161415847/a46ad4ad-9df2-461c-bfd1-c915445c1615)

# 5.js
```
const numbers = [1, 2, 3, 4, 5];

const [first, second] = numbers;

console.log(first);  
console.log(second);

```

# output
![Screenshot 2024-07-06 at 11 47 05 AM](https://github.com/Harshinisrini1910/javascript-assignment/assets/161415847/df81892f-116f-475c-b417-cba4bc7349a4)

# 6.js
```
const arr1 = [1, 2, 3];
const arr2 = [4, 5, 6];

const combined = [...arr1, ...arr2];

console.log(combined);

```

# output
![Screenshot 2024-07-06 at 11 47 34 AM](https://github.com/Harshinisrini1910/javascript-assignment/assets/161415847/2634ae9b-e0a4-479a-8703-5e08a1a15e8f)

# 7.js
```
const sum = (...numbers) => numbers.reduce((acc, current) => acc + current, 0);

console.log(sum(1, 2, 3, 4, 5)); 
console.log(sum(50, 40));        
console.log(sum());

```

# output
![Screenshot 2024-07-06 at 11 47 48 AM](https://github.com/Harshinisrini1910/javascript-assignment/assets/161415847/fa2ba77f-ce7f-4f89-8d88-9e6d17ec66d3)

# 8.js
```
const greet = (name, greeting = "Hello") => `${greeting}, ${name}!`;

console.log(greet("Alice"));          
console.log(greet("Bob", "Hi"));      
console.log(greet("Charlie", "Hey"));

```
# output
![Screenshot 2024-07-06 at 11 48 01 AM](https://github.com/Harshinisrini1910/javascript-assignment/assets/161415847/856234b7-0503-4ecc-8e84-5d73e7541f08)

# 9.js
```

class Animal {
    constructor(name) {
      this.name = name;
    }
  }
  
  class Dog extends Animal {
    bark() {
      return `Woof! My name is ${this.name}`;
    }
  }
  
  const myDog = new Dog('Julie');
  console.log(myDog.bark());


```

# output
![Screenshot 2024-07-06 at 11 48 14 AM](https://github.com/Harshinisrini1910/javascript-assignment/assets/161415847/41ba147b-40ec-40d9-b08c-f9f941a58cd4)

# 10.js
```
const waitAndReturn = () => 
    new Promise(resolve => setTimeout(() => resolve("Done"), 2000));
  
  async function run() {
    const result = await waitAndReturn();
    console.log(result); 
  }
  
  run();

```
# output
![Screenshot 2024-07-06 at 11 48 30 AM](https://github.com/Harshinisrini1910/javascript-assignment/assets/161415847/6368f07a-c4ca-4c13-bdaf-c78f958fb683)
