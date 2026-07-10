---
name: user story2
about: step into the user story
title: ''
labels: ''
assignees: ''

---

As a customer
I need to view my account
So that I can verify my information

Feature: View Customer Account

Scenario: View an existing customer account
Given a customer account exists
When the customer requests their account details
Then the account information should be displayed

Scenario: Account does not exist
Given no customer account exists for the provided ID
When the customer searches for the account
Then a not found message should be returned
