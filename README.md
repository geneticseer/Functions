Functions
=========

Passing objects into funtions
 
// In addition to making an array comprised of objects, functions can use objects as parameters.
// Functions can then take on the methods and properties of an object.

// Person constructor
function Person (name, age) {
  this.name = name;
  this.age = age;
  }
  
// Function with person arguments
var ageDifference = function (person1, person2) {
  return person1.age - person2.age;
  }
var jenn = new Person ("Jennifer", 45:
var james = new Person ("James", 65);
}

// Function provides difference in ages
var diff = ageDifference (jenn, billy) {
  return jenn.age - james.age;
    console.log("The difference in ages is " + ageDifference);
    }
    
// Function returns the oldest age
function Person (person1, person2) {
  if (age.person1 > age.person2) {
    console.log("The oldest person's age is " + age.person1 + "years old.");
    }
    else if (age.person2 > age.person1) {
        console.log("The oldest person's age is " + age.person2 + "years old.");
        }
    else (age.person1 == age.person2) {
      console.log("Both are the same age.");
      }
  }
