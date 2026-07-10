---
name: user story3
about: Step by step guide.
title: ''
labels: ''
assignees: ''

---

As an admin
I need to update customer records
So that data stays current

Feature: Update Customer Account

Scenario: Update existing customer details
Given an existing customer account is available
When the admin updates the customer information
Then the account details should be saved successfully

Scenario: Invalid update attempt
Given an existing customer account is available
When the admin submits invalid data
Then the update should be rejected with an error
