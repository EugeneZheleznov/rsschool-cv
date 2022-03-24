# Evgenii Zheleznov

### Contacts:
**Phone.:** +7 999-204-51-09 
**Email:** zheleznov.evgeniy@mail.ru
**Telegram:** https://t.me/evgeniy_zheleznov


*********


My goal is to master - JS, React, Vue, NodeJS.
And also in the future to learn how to write programs on Phyton, Kotlin, create your own neural network and Data Science.


*********


### Навыки: 
- HTML, CSS (SCSS)
- GULP, Git
- JS Basics
- WordPress - I can create a template and connect the WooCommerce online store
- Bitrix, ModX, OpenCart, Joomla - only content edits, and minor edits in the template
- Graphic Editors: Adobe Photoshop / Illustrator 


*********


###Code example:


Implement and export a default function that counts the sum of all natural numbers less than n (the first argument) that are divisible by the numbers a or b (the second and third arguments) without remainder. n - can only be a natural number.


```
const isPrime = (n, a, b) => {
let result = 0;

for (let i = 1; i < n; i++) {
  if ((i % a === 0) || (i % b === 0)) {
    result = result + i;
  }
}
return result;
}

console.log(isPrime(10, 2, 4));
```