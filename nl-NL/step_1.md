Vergelijkingsoperatoren in JavaScript worden gebruikt om twee waarden te vergelijken en een Booleaans resultaat te retourneren (`waar` of `onwaar`). Dit zijn enkele veelgebruikte vergelijkingsoperatoren:

### Gelijk (==)
Controleert of twee waarden gelijk zijn en converteert de gegevenstypen naar hetzelfde type als ze verschillend zijn.

--- code ---
---
language: js
filename: script.js
line_numbers: true
---
    var num1 = 5;
    var num2 = "5";
    console.log(num1 == num2); // Uitvoer: waar

--- /code ---

- In dit voorbeeld worden num1 en num2 als gelijk beschouwd, omdat de waarden hetzelfde zijn na conversie van het gegevenstype.

### Strikt gelijk (===)
Controleert of twee waarden gelijk zijn zonder ze te converteren naar hetzelfde gegevenstype. Er wordt ook gecontroleerd of de gegevenstypen hetzelfde zijn.

--- code ---
---
language: js
filename: script.js
line_numbers: true
---

    var num1 = 5;
    var num2 = "5";
    console.log(num1 == num2); // Uitvoer: onwaar

--- /code ---

- In dit voorbeeld zijn num1 en num2 niet strikt gelijk omdat hun gegevenstypen verschillend zijn

### Niet gelijk (!=)
Controleert of twee waarden niet gelijk zijn en converteert ze naar hetzelfde gegevenstype als ze verschillend zijn.

--- code ---
---
language: js
filename: script.js
line_numbers: true
---

    var num1 = 5;
    var num2 = "5";
    console.log(num1 != num2); // Uitvoer: onwaar

--- /code ---

- In dit voorbeeld zijn num1 en num2 gelijk nadat de gegevenstypen zijn geconverteerd. Het zal als 'onwaar' worden geretourneerd.

### Strikt niet gelijk (!==)
Controleert of twee waarden ongelijk zijn, zonder ze naar hetzelfde gegevenstype te converteren. Er wordt ook gecontroleerd of de gegevenstypen verschillend zijn.

--- code ---
---
language: js
filename: script.js
line_numbers: true
---

    var num1 = 5;
    var num2 = "5";
    console.log(num1 !== num2); // Uitvoer: waar

--- /code ---

- In dit voorbeeld hebben num1 en num2 verschillende gegevenstypen. Het zal dus als waar worden geretourneerd.

### Groter dan (>)
Controleert of de waarde aan de linkerkant groter is dan de waarde aan de rechterkant.

--- code ---
---
language: js
filename: script.js
line_numbers: true
---

    var num1 = 10;
    var num2 = 5;
    console.log(num1 > num2); // Uitvoer: waar

--- /code ---

- In dit voorbeeld is num1 groter dan num2 en wordt de waarde waar geretourneerd.

### Kleiner dan (<)
Controleert of de waarde aan de linkerkant kleiner is dan de waarde aan de rechterkant.

--- code ---
---
language: js
filename: script.js
line_numbers: true
---

    var num1 = 10;
    var num2 = 15;
    console.log(num1 < num2); // Uitvoer: waar

--- /code ---

- In dit voorbeeld is num1 kleiner dan num2 en wordt de waarde 'waar' geretourneerd.