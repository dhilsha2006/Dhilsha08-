let name = "John Doe";
let age = 30;
let isAdmin = true;

console.log(name);
console.log(age);
console.log(isAdmin);

// Conditional Statements
let temperature = 25;

if (temperature > 30) {
  console.log("It's hot outside!");
} else if (temperature < 20) {
  console.log("It's cold outside!");
} else {
  console.log("It's nice outside!");
}

// Loops
for (let i = 0; i < 5; i++) {
  console.log(i);
}

let colors = ["red", "green", "blue"];

for (let color of colors) {
  console.log(color);
}

// Functions
function greet(name) {
  console.log(`Hello, ${name}!`);
}

greet("John Doe");

// Arrays and Objects
let numbers = [1, 2, 3, 4, 5];

console.log(numbers[0]); // 1

let person = {
  name: "John Doe",
  age: 30,
  isAdmin: true
};

console.log(person.name); // John Doe

// DOM Manipulation
document.getElementById("header").innerHTML = "New Header Text";

let button = document.getElementById("button");

button.addEventListener("click", function() {
  console.log("Button clicked!");
});
