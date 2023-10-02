# Project 1: Living histories

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
Piggy is an expense tracker for users. Users get some insight about what their "piggy bank" is being spent on through a list breakdown of their expenses along with a chart breakdown of total expenses. Resources are also provided to the user to increase their financial literacy and budgetting habits.

## Living Histories Walkthrough Video
[Living Histories Walkthrough](https://youtu.be/nrF-XjUx4oI)

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
Completed, Not hosted.

This web app was created to be continually built upon by later researchers and residents of Kefalonia,Greece.

## Why Living Histories?
I created this app because of my personal affinity for finance. Being a recent graduate of both finance and accounting, I constantly think about the ways I am breaking out my daily, weekly, and monthly income. This app serves as a beginner's resource for those just now thinking about how finance plays into their lives and ways to improve financial habits.

## Contact
Created by [Caila Bridges](https://www.linkedin.com/feed/)
