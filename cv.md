# Irina Chistobaeva

## Contact Info
* +375 25 700 43 77
* Skype: rishachistobaeva
* chistobaevairina@gmail.com

## Summary
I am a QA Engineer with several years experience of working on different projects. My goal is to learn and practice front end technologies to get wide understanding of working web-applications and ability to automate my work in future.

## Skills

### QA and general skills:
- Various types of testing
- Creating test artifacts (test cases, test suites, check lists, bug-reports)
- Working with test management and bug tracking systems:
  - Targetprocess
  - Jira and Confluence
  - Zephyr
  - TestRail
  - Trello    
- Methodologies:
  - Scrum
  - Iterative and incremental development
- Planning and estimating 

### Technical skills:
- HTML/CSS
- JS basis
- Visual Studio Code
- Oracle and SQL
- Postman, Swagger, Fiddler

### Soft skills:
- Mentoring trainees
- Interviewing and assessment
- Lecturing

## Code example
```javascript

const PHONE_PRICE = 99.99;          //цена телефона
const ACCESSORY_PRICE = 9.99;       //цена аксессуара
const TAX = 0.09;                   //налог

let bill = prompt("Please tell me your bill:");
let amount = 0;

function taxRate(amount) {
    return amount * TAX;
}

function formatAmount(amount) {
    return "$" + amount.toFixed(2);
}

while (amount < bill) {
    amount = amount + PHONE_PRICE + ACCESSORY_PRICE;
    amount = amount + taxRate(amount);
    console.log(formatAmount(amount));
}

console.log('insufficient funds in the account');

```
