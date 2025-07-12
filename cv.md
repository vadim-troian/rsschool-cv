# Vadym Troian

Junior Frontend Developer

## Table of contents

- [Contact information](#contact-information)
- [About Myself](#about-myself) 
- [Skills](#skills)
- [[Code example]](#code-example)
- [Education](#education)
- [Languages](#languages)

---

### Contact information

- **Location:** Kyiv, Ukraine
- **Discort:** vadym troian (@vadim-troian)
- **E-mail:** vadymtroiyan@gmail.com
- **[Telegram](https://web.telegram.org/):** @Vadim_Viktorovich_39
- **GitHub:** [vadim-troian](https://github.com/vadim-troian)

---

### About Myself 

I am a reliable and responsible person with experience as an accountant. I love to study and master new things. Now I am aiming to work as a web developer.

---

### Skills

- HTML, CSS
- JavaScript Basics
- Git, GitHub

---

### Code example

Solution for Palindrome Checker from freecodecamp.org : *A palindrome is a word or sentence that's spelled the same way both forward and backward, ignoring punctuation, case, and spacing. Return `true` if the given string is a palindrome. Otherwise, return `false`.* 

> ***Note:** You'll need to remove **all non-alphanumeric characters** (punctuation, spaces and symbols) and turn everything into the same case (lower or upper case) in order to check for palindromes.*

```js
function palindrome(str) {

   str = str.toLowerCase().replace(/[\W_]/g, '');
   for (let i = 0, len = str.length - 1; i < len / 2; i++) {
      if (str[i] !== str[len - i]) {
         return false;
      }
   }
   return true;
}

palindrome("eye");
```

---

### Education

- **University:** Kharkiv National University of Economics

- **Courses:**

  - Freecodecamp Course "Responsive Web Design" (completed)

  - Freecodecamp Course "Legacy JavaScript Algorithms and Data Structures" (completed)

  - RS Schools Course "JS/FE Pre-School 2025Q2" (in progress)

---

### Languages

- English - Pre-Intermediate
- Russian - Native
- Ukrainian - Advanced