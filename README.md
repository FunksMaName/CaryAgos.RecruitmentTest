# CaryAgos Bank Engineer Recruitment Test

Thank you for opting to take our Engineering technical test. The tests consists of two parts: 

* [A coding test](#coding-test)
* [Some technical questions](#technical-questions)

## Coding Test
CaryAgos Bank has a snapshot database which holds point of sale transaction records of its customers for the year **2017** and **2018**. Each transaction record contains the following details

* User identifier
* Transaction date
* Transaction description
* Transaction amount 
* Transaction currency denomination
* The Transaction location category (Restaurant, Shopping, e.t.c.) Identifier

A separate table exists which links the transaction location category Id where a transaction occurred to the most applicable category Id. There are currently 6 defined categories in the system

* 1010 – Restaurant
* 1020 – Groceries
* 1030 – Shopping
* 1040 – Transport
* 1050 – Cash
* 1060 – Transfers

The task is to create an application that accepts a transaction ***start date*** and ***end date*** as a parameter. The application should then display the following information about each transaction that falls within the search criteria

* Date and time
* Category Name
* Amount
* User Id

## Guidelines and Platform of choice
We expect you to complete the solution using .NET Framework using C# and SQL Server

## Task requirements
* Please complete the user story below
* Your code should ideally compile and run in one step
* You **should** include tests

## User stories
As an administrator running the application

I can view a list of transactions that fall within a selected date range

So that I know exactly how many transactions occurred over the selected period

## Acceptance Criteria
Transaction date, category name, amount and user id are displayed

# Problems?
Feel free to contact us or your recruitment agent if you would like us to clarify anything.
