Les opérateurs de comparaison en JavaScript sont utilisés pour comparer deux valeurs et renvoyer un résultat booléen (soit« vrai » soit « faux »). Voici quelques opérateurs de comparaison courants :

### Égal à (==)
Vérifie si deux valeurs sont égales et les convertit vers le même type de données si elles sont différentes.

--- code ---
---
language: js
filename: script.js
line_numbers: true
---
    var num1 = 5;
    var num2 = "5";
    console.log(num1 == num2); // Résultat : vrai

--- /code ---

- Dans cet exemple, les valeurs num1 et num2 sont considérées comme égales, car elles sont identiques après la conversion du type de données.

### Strictement égal à (===)
Vérifie si deux valeurs sont égales sans les convertir vers le même type de données. Vérifie également si les types de données sont les mêmes.

--- code ---
---
language: js
filename: script.js
line_numbers: true
---

    var num1 = 5;
    var num2 = "5";
    console.log(num1 === num2); // Résultat : faux

--- /code ---

- Dans cet exemple, les valeurs num1 et num2 ne sont pas strictement égales, car leurs types de données sont différents

### Pas égal à (!=)
Vérifie si deux valeurs ne sont pas égales et les convertit vers le même type de données si elles sont différentes.

--- code ---
---
language: js
filename: script.js
line_numbers: true
---

    var num1 = 5;
    var num2 = "5";
    console.log(num1 != num2); // Résultat : faux

--- /code ---

- Dans cet exemple, les valeurs num1 et num2 sont égales après la conversion des types de données. Le résultat est « faux ».

### Strictement pas égal à (!==)
Vérifie si deux valeurs ne sont pas égales, sans les convertir vers le même type de données. Vérifie également si les types de données sont différents.

--- code ---
---
language: js
filename: script.js
line_numbers: true
---

    var num1 = 5;
    var num2 = "5";
    console.log(num1 !== num2); // Résultat : vrai

--- /code ---

- Dans cet exemple, les valeurs num1 et num2 ont des types de données différents. Le résultat est donc « vrai ».

### Supérieur à  (>)
Vérifie si la valeur de gauche est supérieure à la valeur de droite.

--- code ---
---
language: js
filename: script.js
line_numbers: true
---

    var num1 = 10;
    var num2 = 5;
    console.log(num1 > num2); // Résultat : vrai

--- /code ---

- Dans cet exemple, la valeur num1 est supérieure à la valeur num2, le résultat est donc « vrai ».

### Inférieur à (<)
Vérifie si la valeur de gauche est inférieure à la valeur de droite.

--- code ---
---
language: js
filename: script.js
line_numbers: true
---

    var num1 = 10;
    var num2 = 15;
    console.log(num1 < num2); // Résultat : vrai

--- /code ---

- Dans cet exemple, la valeur num1 est inférieure à la valeur num2, le résultat est donc « vrai ».