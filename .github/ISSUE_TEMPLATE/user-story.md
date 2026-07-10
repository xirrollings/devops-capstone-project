---
name: user story
about: this is a message to track the step by step progress of the project and what
  needs to get done.
title: devops-capstone project''
labels: ''
assignees: ''

---

As a customer
I need to create an account
So that I can use the service

Feature: Customer Account Creation

Scenario: Successfully create a customer account
Given the customer is on the registration page
When the customer enters valid account details and submits the form
Then a new customer account should be created successfully

Scenario: Missing required information
Given the customer is on the registration page
When the customer submits the form without required fields
Then an error message should be displayed
