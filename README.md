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

Wichtige Begriffe
	•	Klasse → Bauplan für Objekte
	•	Objekt → Instanz einer Klasse
	•	Methode → Funktion innerhalb einer Klasse
	•	Eigenschaft → Daten eines Objekts
	•	constructor → Initialisierungsfunktion

⸻

Kurz gesagt

JavaScript-Klassen ermöglichen eine strukturierte und wiederverwendbare Organisation von Code.
