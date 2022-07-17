# 0x1B. C - Sorting algorithms & Big O

## Description

Tasks on .

What I learned from the tasks:

* What is the Big O notation, and how to evaluate the time complexity of an algorithm
* How to select the best sorting algorithm for a given input
* What is a stable sorting algorithm

---

## General Requirements
* Allowed editors: vi, vim and emacs.
* All files were created and compiled on Ubuntu 20.04.4 LTS using using gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89```
* Code checked with betty-style.pl and betty-doc.pl

---

# Tasks

These are all the tasks of this project, the ones that are completed link to the corresponding files.

### [0. Bubble sort](./0-bubble_sort.c)
* Write a function that sorts an array of integers in ascending order using the Bubble sort algorithm
	- Prototype: void bubble_sort(int *array, size_t size);
	- You’re expected to print the array after each time you swap two elements (See example below)

* Write in the file 0-O, the big O notations of the time complexity of the Bubble sort algorithm, with 1 notation per line:

	- in the best case
	- in the average case
	- in the worst case

### [1. Insertion sort](./1-insertion_sort_list.c)
* Write a function that sorts a doubly linked list of integers in ascending order using the Insertion sort algorithm

	- Prototype: void insertion_sort_list(listint_t **list);
	- You are not allowed to modify the integer n of a node. You have to swap the nodes themselves.
	- You’re expected to print the list after each time you swap two elements (See example below)

* Write in the file 1-O, the big O notations of the time complexity of the Insertion sort algorithm, with 1 notation per line:

	- in the best case
	- in the average case
	- in the worst case

### [2. Selection sort](./2-selection_sort.c)
* Write a function that sorts an array of integers in ascending order using the Selection sort algorithm

	- Prototype: void selection_sort(int *array, size_t size);
	- You’re expected to print the array after each time you swap two elements (See example below)
* Write in the file 2-O, the big O notations of the time complexity of the Selection sort algorithm, with 1 notation per line:

	- in the best case
	- in the average case
	- in the worst case

### [3. Quick sort](./3-quick_sort.c)
* Write a function that sorts an array of integers in ascending order using the Quick sort algorithm

	- Prototype: void quick_sort(int *array, size_t size);
	- You must implement the Lomuto partition scheme.
	- The pivot should always be the last element of the partition being sorted.
	- You’re expected to print the array after each time you swap two elements (See example below)
* Write in the file 3-O, the big O notations of the time complexity of the Quick sort algorithm, with 1 notation per line:

	- in the best case
	- in the average case
	- in the worst case




---

### Author
* **Dominic Samo** - (https://github.com/DominicSamoes)
