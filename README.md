# [Living histories](https://www.imaginarycountry.org/www_09/726/Index.html)

## Table of Contents
* [About](#about-living-histories)
* [Video](#living-histories-walkthrough-video)
* [Technologies](#technologies)
* [Code Examples](#code-examples)
* [Features](#living-histories-features)
* [Status](#status)
* [Why Living Histories](#why-living-histories)
* [Contact](#contact)

## About Living Histories
Living Histories is a multi-year multidisciplinary project spearheaded by Prof. Scott Townsend and based in Kefalonia (Κεφαλονια), the sixth largest Greek island. The focus of Living Histories is the documentation of the experiences, practices, values, and history of Kefalonia and its people. I and eight other students in the 2022 program cohort worked collaboratively to build and populate a website for all of the research done to date, including interviews, photography, cultural practices, and social values.

## Living Histories Walkthrough Video
[Living Histories Walkthrough Video](https://youtu.be/nrF-XjUx4oI)

## Technologies
JavaScript ES6

HTML5 / CSS3


## Code Examples

```
function persistExpense(user) {
    user.expenses.forEach(expense => {
        const divExpenses = document.getElementById("expense-list")
        const expenseListElement = document.createElement("p")
        expenseListElement.innerText = `${expense.item}: $ ${expense.amount}`
        divExpenses.append(expenseListElement)
        data = [{
            x: `${expense.item}, value: ${expense.amount}`
        }]
    })
}
```
```
function sumExpenses(user){
    expense_array = []
    user.expenses.map(expense => {
        (expense_array.push(expense.amount))
    })
    expenseSum = expense_array.reduce((total, amount) => total + amount);
    showTotalExpenses()
}
```
## Living Histories Features
* Interactive island map to access interviews from specific regions.
* Present and Visualize content in an organized manner.
* Provide oral histories and cultural practices for all generations. 


To-Do List:
* Add searching feature to quickly access selected interviews

## Status
Phase 1 completed (on-going)

This web app was created to be continually built upon by later researchers and residents of Kefalonia,Greece.

## Why Living Histories?
During my time in Kefalonia, I had the opportunity to be immersed within the island's culture, taste its traditional foods, and form relationships with it's people. It was a pleasure to be involved in building a web app that contained a manifestation of Kefalonia's hisotry and practices. I sharpened my technical skills with HTML, CSS and Javascript during its construction. I enhanced my ability to manage time, team collaboration and research content to bring the porject to completeion within the five week program.

## Contact
Created by [Caila Bridges](https://www.linkedin.com/feed/)
