---
name: user story4
about: A peak into the project gudelines
title: ''
labels: ''
assignees: ''

---

As an admin
I need to delete customer accounts
So obsolete records can be removed

Feature: Delete Customer Account

Scenario: Delete an existing customer account
Given a customer account exists
When the admin deletes the account
Then the account should be removed successfully

Scenario: Delete a non-existent account
Given the customer account does not exist
When the admin attempts deletion
Then a not found error should be returned
