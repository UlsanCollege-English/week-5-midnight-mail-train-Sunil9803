[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/T6sJM4w6)

# Week 5 — Midnight Mail Train

## Summary
This assignment focuses on implementing a doubly linked list to manage train cars. It also includes working with strings and recursion to validate ticket codes, count labels, and clean messages. The goal is to understand data structures and recursive problem-solving.

## Approach
- Problem 1: Implemented a doubly linked list with functions to append a car, remove the last car, and return the list in reverse order.
- Problem 2: Checked if a ticket code is valid by verifying its prefix and ensuring it ends with exactly four digits.
- Problem 3: Used recursion to count how many times a target label appears in a list.
- Problem 4: Used recursion to remove all spaces from a given message.

## Complexity

- append_car:
  - Time: O(1) — adding at the end using tail pointer
  - Space: O(1) — no extra space used

- detach_last_car:
  - Time: O(1) — direct access to tail
  - Space: O(1)

- to_reverse_list:
  - Time: O(n) — traverses all nodes
  - Space: O(n) — stores result list

- is_valid_ticket_code:
  - Time: O(1) — fixed length check
  - Space: O(1)

- count_priority_labels (recursive):
  - Time: O(n) — checks each element
  - Space: O(n) — recursion stack

- clean_radio_message (recursive):
  - Time: O(n) — processes each character
  - Space: O(n) — recursion stack

## Edge-case checklist
- [x] empty train
- [x] one train car
- [x] invalid ticket code
- [x] empty label list
- [x] empty message
- [x] one-character or all-space message

## Assistance & Sources
- AI used? Yes
- What it helped with:
  - Understanding recursion logic
  - Structuring the doubly linked list methods
  - Writing clean and correct implementations
- Other sources used:
  - Class notes
  - Python documentation