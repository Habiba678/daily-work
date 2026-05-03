## daily-work

Ich übe hier regelmäßig JavaScript.
Dieses Repository nutze ich, um die Grundlagen Schritt für Schritt zu lernen.

---

### Tag 1 – Variablen

```js
let name = "Max";
let age = 25;

let city = "Hamburg";
let country = "Deutschland";

let isStudent = true;
let score = 100;



### Tag 2 – Datentypen
// Datentypen beschreiben, welche Art von Wert gespeichert wird

let username = "Julia";   // String
let age = 30;             // Number

let city = "Berlin";      // String
let price = 19.99;        // Number

let isOnline = true;      // Boolean
let hasAccess = false;    // Boolean



### Tag 3 – Bedingungen und Schleifen
// Bedingungen und Schleifen steuern den Ablauf im Code

let age = 18;

if (age >= 18) {
  console.log("Volljährig");
} else {
  console.log("Minderjährig");
}

let numbers = [1, 2, 3, 4, 5];

for (let i = 0; i < numbers.length; i++) {
  console.log(numbers[i]);
}





Klassen in JavaScript

JavaScript-Klassen dienen der Strukturierung von Code.
Sie ermöglichen die Definition von Objekten sowie deren Eigenschaften und Methoden.

⸻

Beispiel

class User {
constructor(name) {
this.name = name;
}

greet() {
console.log(Hallo, ich bin ${this.name});
}
}

const user1 = new User(“Janna”);
user1.greet();

⸻

Erklärung
	•	class User
Definiert eine Klasse mit dem Namen „User“.
	•	constructor(name)
Wird beim Erstellen eines Objekts automatisch ausgeführt.
	•	this.name = name
Weist dem Objekt eine Eigenschaft zu.
	•	greet()
Definiert eine Methode innerhalb der Klasse.
	•	new User(“Janna”)
Erzeugt eine Instanz der Klasse.

⸻







/* COUNTER PROGRAM 

const descreaseBnt = document.getElementById("decreaseBtn");
const resetBnt = document.getElementById("resetBtn");
const increaseBtn = document.getElementById("increaseBtn");
const countLabel = document.getElementById("countLabel");
let count = 0;

increaseBtn.onclick = function(){
    count++;
    countLabel.textContent = count;
}

descreaseBnt.onclick = function(){
    count--;
    countLabel.textContent = count;
}


resetBnt.onclick = function(){
    count = 0;
    countLabel.textContent = count; 
}*/


// Math = built-in object that provides a collection 
// of properties and mathos

//let x = 3;
let y = 2;
let z = 1;

//z = Math.round(x);
//z = Math.floor(x);
//z = Math.ceil(x);
//z = Math.trunc(x);
//z = Math.paw(x;
//z = Math.log(x);
//z = Math.sin(x);
//z = Math.cos(x);
//z = Math.tan(x);
//z = Math.abs(x);
//z = Math.sign(x);
//let max = Math.max(x, y, z);
//let min = Math.min(x, y, z);
//console.log(min);


// RANDOM NUMBER GENERATOR

//const min = 50;
//const max = 100;

//console.log(randomNum);

//const myButton = document.getElementById("myButton");
//const label1 = document.getElementById("label1");
//const label2 = document.getElementById("label2");
//const label3 = document.getElementById("label3");

//const min = 1;
//const max = 6;
//let randomNum1;
//let randomNum2;
//let randomNum3;

//myButton.onclick = function(){
    //randomNum1 = Math.floor(Math.random () * max) + min;
    //randomNum2 = Math.floor(Math.random () * max) + min;
    //randomNum3 = Math.floor(Math.random () * max) + min;
    //label1.textContent = randomNum1;
    //label2.textContent = randomNum2;
    //label3.textContent = randomNum3;
//}

//IF STATEMENTS = if a condition is true, execute some code
//                  if not , do something else


//let age = 13; 

//if (age >= 18){
    //console.log("You are old enough to enter this site");
//}
//else{
    //console.log("You must be 18+ enter this site")
//}

/* const myText = document.getElementById("myText");
const mySubmit = document.getElementById("mySubmit");
const resultElement = document.getElementById("resultElement");
let age;


mySubmit.onclick = function(){

   age = myText.value;
   age = Number(age)

   if(age >= 100){
       resultElement.textContent = `You are TOO OLD to enter this site`;
   }
   else if(age == 0){
        resultElement.textContent = `You can't enter. You were just born`;
   }

   else if(age >= 18){
        resultElement.textContent = `You are old enough to enter this site`;
   }

   else if(age < 0){
        resultElement.textContent = `You age can't be below 0`;
   }

   else{
       resultElement.textContent = `You must be 18+ to enter this site`;
   }

}*/


/*const myCheckBox = document.getElementById("myCheckBox");
const visaBtn = document.getElementById("visaBtn");
const masterCarBtn = document.getElementById("masterCarBtn");
const payPalBtn = document.getElementById("payPalBtn");
const mySubmit = document.getElementById("mySubmit");
const subResult = document.getElementById("subResult");
const paymentResult = document.getElementById("paymentResult");

mySubmit.onclick = function(){
    if(myCheckBox.checked){
        subResult.textContent = `You are subscribed`;
    }
    else{
        subResult.textContent = `You are NOT subscribed`;
    }

    if(visaBtn.checked){
        paymentResult.textContent = `You are paying with Visa`;

    }
    else if(masterCarBtn.checked) {
        paymentResult.textContent = `You are paying with MasterCard`;

    }
    else if(payPalBtn.checked){
        paymentResult.textContent = `You are paying with PayPal`;

    }
    else {
        paymentResult.textContent = `You must select a payment type`;

    }


}*/














Wichtige Begriffe
	•	Klasse → Bauplan für Objekte
	•	Objekt → Instanz einer Klasse
	•	Methode → Funktion innerhalb einer Klasse
	•	Eigenschaft → Daten eines Objekts
	•	constructor → Initialisierungsfunktion

⸻

Kurz gesagt

JavaScript-Klassen ermöglichen eine strukturierte und wiederverwendbare Organisation von Code.
