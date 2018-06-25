# Ordlista
> Ordlista över vanligt förekommande begrepp och termer


| Begrepp   | Förklaring  |
| -------   | ----------- |
| argument  | De värden som skickas in till en funktion, värdena i funktionsanropet `add(5,5)` |
| parameter | De variabler som skapas och använd inuti funktionen, argumenten blir till parametrar, `a` och `b` i `function add(a,b){}` |
| scope     | Där du har tillträde till variabler. I JavaScript finns **function scope** samt **global scope**. _Global scope_ är hela javascript-filen medan _function scope_ skapas varje gång du deklarerar en funktion. Med `let`/`const` finns även **block scope**, [se tabell längre ned för jämförelse](#let-const-och-var) |
| hoisting  | När variabler skjuts upp och läggs längst upp i det aktuella scopet. Detta händer med [function declaration](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/function) vilket gör att funktionen kan kallas på innan den har blivit deklarerad |
| funktionsanrop | När du kallar på funktionen som du har deklarerat. Koden innanför funktionen kommer inte att köras förän du gör ett anrop. t.ex. `add(10, 10)` |

---

## `let`, `const` och `var`

| Keyword |	Scope	 | Hoisting | Can Be Reassigned | Can Be Redeclared |
|---|---|---|---|---|
|`var`|	Function scope	|Yes	|Yes	|Yes|
|`let`|	Block scope	|No	|Yes	|No |
|`const`|	Block scope	|No	|No	|No | 

[Källa](https://www.digitalocean.com/community/tutorials/understanding-variables-scope-hoisting-in-javascript)
