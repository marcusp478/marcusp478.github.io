---
layout: project
type: project
image: img/database.png
title: "Bank Database Application"
date: 2022-04-23
published: true
labels:
  - C
  - C++
  - Unix
summary: "A project I made for my ICS 212 class that grants its user access to bank records from a database."
---

ICS 212 at the University of Hawaii at Manoa covered both the C and C++ programming languages throughout the course. For this reason there are two iterations of the project that are each written in one of the aforementioned languages. Despite their differences, both functioned similarly and were both compiled and ran on Unix. In addition, both used linked lists in order to store the records in memory, which would eventually be transferred into a text file that served as our database.

The goal of this assignment was to allow the user to do the following: 1) add new bank records, 2) delete already existing records, 3) view all existing records in order of their account numbers, 4) or view one specific record via account number (or multiple if they share the same number). Each of these options had their own respective functions that would either iterate through the linked list or append/remove linked nodes. Apart from these functionalities, I also included both a read and write function. When the program executes, all records (if any) that are in the database are added to the linked list. Once the user decides to terminate the program, all remaining records are added to the text file in numerical order so they can be read and transferred to a linked list the next time the executable starts up.
