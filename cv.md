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
## Experience 

### Resent Projects:

#### Management event project, management events system, Finland
Three web-applications and one mobile application of project management for the creation and development of large scale events. 
##### Role: 
QA Engineer
##### Responsibilities: 
* Learning technical requirements
* Participate in different meetings with multinational QA team members to discuss the testing and problem solving process
* Communicating with the customers
* Writing test documentation: test cases, bug-reports
* Smoke testing
* Exploratory testing
* Functional testing
* Regression testing
* GUI testing
* API testing
* Cross-testing
* Cross-browser testing
* Cross-platform testing
* Mentoring trainees
* Team-lead duties: tasks assigning, QA team support and coordinating, checking following the flow, etc.

#### KindieDays, communication, Finland 
Application that helps teachers and parents communicate and collaborate in real-time. The Project is consist of four IOS and Android applications and 1 Web. 
##### Role: 
QA Engineer
##### Responsibilities: 
* Writing test documentation: test cases, bug-reports
* Smoke testing
* Exploratory testing
* Functional testing
* Regression testing
* GUI testing
* Cross-testing
* Cross-platform testing
* Reviewed test documentation of another QA team member

## Education 
* Belarusian State University, Geographic information system, 2014
* Continuous self-training 

## English 
* Pre-Intermediate