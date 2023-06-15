# code-challenge1

challenge 1: Student Grade Generator (Toy Problem)

//A> 79
//B-60 to 79
//C-49 to 59
//D-40 to 49
//E-less 40

let score = prompt("Enter the score: ");
score = Number(score);
let grade;
if (score >= 80) 
{grade = "A";} 
else if (score >= 60 && score <= 79) {
grade = "B";
} else if (score >= 50 && score <= 59) {
grade = "C";
} else if (score >= 40 && score <= 49) {
grade = "D";
} else {
grade = "E";
}

// Print the grade
console.log(`The grade is ${grade}.`);





challenge2:speed Detector (Toy Problem)

let speed = prompt("Enter the speed of the car: ");
const limit = 70;
const factor = 5;
if (speed <= limit) {
console.log("Ok");
} else {
let points = Math.floor((speed - limit) / factor);
console.log(`You have ${points} demerit points.`);
}



Challenge 3: Net Salary Calculator (Toy Problem)

const tax_rate =
const nhif_rate = 
const nssf_rate = 
let basic_salary = 
let benefits = 
basic_salary =
benefits =  
console.log()
console.log()
console.log()
console.log()
console.log()
