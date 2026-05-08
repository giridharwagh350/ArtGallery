## Art Gallery Management System 🎨 🖼️
 ### A web-based Art Gallery Management System developed using HTML, CSS, Bootstrap, PHP, and PostgreSQL Database.🌐
-------------------------------------------------------------------------------------------------------------------------------

## Description 📘

### What is an Art Gallery Management System?✨ 
<br>
An Art Gallery Management System is a digital platform 💻 designed to manage and showcase artworks 🖌️, artists 👩‍🎨👨‍🎨, and exhibitions 🏛️.
It provides:
An Admin Panel ⚙️ for managing gallery data.
A User Interface 👥 for exploring art collections.

## Project Scope 🎯
Art Galleries are a hub for culture and creativity 🌍.
This system:
📂 Stores and manages artworks, artists, and exhibitions.

🔍 Provides search & filter options for visitors.

🗄️ Uses PostgreSQL for secure data handling.

📊 Improves accessibility & efficiency through digitalization.

 ## Requirements 🖥️
  🌍 Web Browser (Chrome / Firefox / Edge).
  🐘 PostgreSQL Database (v13+ recommended).
  ⚡ PHP 8+ with pgsql or pdo_pgsql enabled.
  💾 500 MB Disk Space.
  🧠 4 GB RAM (or higher).

 ### Note: If you face issues, check PostgreSQL connection settings in php.ini.⚠️

 ## How to Run the Project? 🚀
This repository contains the Art Gallery Management System web app.
🛠️ Clone using Git
git clone https://github.com/giridharwagh350/Art-Gallery-Management-System

Or 📥 download the ZIP file from GitHub.

## Setup Steps 🔧
### Step 1: 🐘 Configure Database
Install PostgreSQL.
Create a DB named: art_gallery.
Import SQL file from /database folder.

### Step 2: ⚙️ Configure Project
Copy project to htdocs/ (XAMPP) or www/ (WAMP).
Edit config.php:

$host = "localhost";
$dbname = "art_gallery";
$user = "postgres";
$password = "your_password";

### Step 3: 🌐 Run Project
Start Apache/Nginx & PostgreSQL.
Visit:
http://localhost/Art-Gallery-Management-System

🎉 Done! Enjoy managing your gallery online.

## Screenshots 🖼️
### Home Page 🏠
![homepage](https://github.com/user-attachments/assets/ebd45982-b356-43c6-b115-b70e445d52c2)

### User Login 🔑
![admin](https://github.com/user-attachments/assets/bef13a8f-0696-4053-a002-7c2de55970b8)

### Admin Dashboard 📊 
![Dashbprd](https://github.com/user-attachments/assets/1db4a872-282b-46a4-9a28-17f0e310cd70)

### Manage Artists 👩‍🎨
![Manageartist](https://github.com/user-attachments/assets/dc2d155e-f032-4580-b129-ad3fede1b58f)

### Artwork Selling 💰 
![salling](https://github.com/user-attachments/assets/ec2bb420-4a66-4f59-b3ba-7003e7c01e1d)

## Features 🔑

👨‍💼 Admin Features: Add/Edit/Delete Artists, Artworks, Exhibitions, Customers.

👩‍🎨 User Features: Browse artworks, filter by category, view exhibitions.

🗄️ Database: PostgreSQL integration for secure storage.

## Credits 🙌

🎨 Frontend: HTML, CSS, Bootstrap.

⚙️ Backend: PHP.

🐘 Database: PostgreSQL.

🖼️ Assets: Open-source images & icons.

📚 Learning: Tutorials & community docs.


## MIT LICENSE 📜
MIT License  

Copyright (c) 2025  

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:  

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.  

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.














1. What is an algorithm?
An algorithm is a step-by-step procedure to solve a problem in a finite number of
steps.
2. What is time complexity?
Time complexity measures how the running time of an algorithm increases with
input size (n).
3. What is space complexity?
Space complexity is the amount of memory required by an algorithm.
4. What is greedy method?
Greedy method builds a solution step-by-step by choosing the best option at each
step.
5. What is dynamic programming?
It solves problems by breaking them into subproblems and storing results to avoid
repetition.
6. What is backtracking?
Backtracking tries all possible solutions and removes those that don’t satisfy
constraints.
7. What is divide and conquer?
It divides a problem into smaller subproblems, solves them, and combines results.
Selection Sort
8. What is Selection Sort?
It repeatedly selects the smallest element and places it in correct position.

9. Time complexity of Selection Sort?
Best/Worst/Average: O(n²)
Quick Sort
10. What is Quick Sort?
It is a divide-and-conquer algorithm using a pivot to partition array.
11. Time complexity of Quick Sort?
Best/Average: O(n log n), Worst: O(n²)
Heap Sort
12. What is Heap Sort?
It uses binary heap data structure to sort elements.
13. Time complexity of Heap Sort?
Always: O(n log n)
Merge Sort
14. What is Merge Sort?
It divides array into halves, sorts them, then merges.
15. Time complexity?
Always: O(n log n)
Prim’s Algorithm
16. What is Prim’s algorithm?
It finds Minimum Spanning Tree by growing tree step by step.

Kruskal’s Algorithm
17. What is Kruskal’s algorithm?
It builds MST by selecting edges in increasing order of weight.
Difference between Prim and Kruskal?
● Prim: grows from a node
● Kruskal: works on edges
Dijkstra’s Algorithm
18. What is Dijkstra’s algorithm?
It finds shortest path from a source node to all vertices.
19. Can it handle negative weights?
No
BFS and DFS
20. What is BFS?
Breadth First Search explores level by level using queue.
21. What is DFS?
Depth First Search explores deep paths using stack/recursion.
22. Time complexity of BFS/DFS?
O(V + E)
Topological Sorting
23. What is topological sort?

LCS
30. What is LCS?
Longest Common Subsequence between two strings.
Matrix Chain Multiplication
31. What is Matrix Chain Multiplication?
Find best way to multiply matrices with minimum operations.
Optimal BST
32. What is Optimal BST?
A binary search tree with minimum search cost.
Knapsack (0/1)
33. Difference between 0/1 and fractional knapsack?
● 0/1: items cannot be divided
● Fractional: items can be divided
34. What is MST?
Minimum Spanning Tree connects all vertices with minimum cost.
35. What is a graph?
A graph is a collection of vertices and edges.
36. What is DAG?
Directed Acyclic Graph (no cycles).
37. Which sorting is best?

Merge Sort / Quick Sort → O(n log n)
