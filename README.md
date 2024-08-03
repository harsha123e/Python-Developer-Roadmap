# Python-Developer-Roadmap
Complete roadmap along with notes to become a Python Developer

Credits - Roadmap framework from the [Propeers Python Developer Roadmap](https://www.propeers.in/roadmaps/6614a0932dc5903d99ab903c)

Notes generated using ChatGPT

# Table of Contents
- [Python-Developer-Roadmap](#python-developer-roadmap)
- [Python Basics](#python-basics)
  * [Introduction to Python - 6](#introduction-to-python---6)
    + [What is Python](#what-is-python)
    + [Basic Syntax](#basic-syntax)
    + [Keywords](#keywords)
    + [Comments](#comments)
    + [Input/Output Statements](#input-output-statements)
    + [Indentation](#indentation)
  * [Literals Variables and Datatypes - 4](#literals-variables-and-datatypes---4)
    + [Literals](#literals)
    + [Variables](#variables)
    + [Datatypes](#datatypes)
    + [Type Conversion and Type Casting](#type-conversion-and-type-casting)
  * [Operators - 8](#operators---8)
    + [What is Operator](#what-is-operator)
    + [Operator Precedence](#operator-precedence)
    + [Arithmetic Operators](#arithmetic-operators)
    + [Assignment Operators](#assignment-operators)
    + [Relational Operators](#relational-operators)
    + [Bitwise Operators](#bitwise-operators)
    + [Ternary Operators](#ternary-operators)
    + [Logical Operators](#logical-operators)
  * [Conditional Statements - 7](#conditional-statements---7)
    + [Decision Making Statements](#decision-making-statements)
    + [Implementation of Switch Case Statement](#implementation-of-switch-case-statement)
    + [Jump Statements](#jump-statements)
    + [Practice Problems](#practice-problems)
  * [Loops - 10](#loops---10)
    + [Loops and its Types](#loops-and-its-types)
    + [While Loop](#while-loop)
    + [For Loop](#for-loop)
    + [Nested Loop](#nested-loop)
    + [Iterators and Generators](#iterators-and-generators)
    + [Practice Problems](#practice-problems-1)
  * [Functions - 9](#functions---9)
    + [Functions in Python](#functions-in-python)
    + [Arguments in Python](#arguments-in-python)
    + [Built-in Functions](#built-in-functions)
    + [Lambda Function](#lambda-function)
    + [Higher Order Functions](#higher-order-functions)
    + [Decorators](#decorators)
    + [Recursion](#recursion)
    + [Practice Problems](#practice-problems-2)
- [Python Intermediate](#python-intermediate)
  * [List - 9](#list---9)
    + [What is List in Python](#what-is-list-in-python)
    + [List Operations](#list-operations)
    + [Membership Operators](#membership-operators)
    + [List Methods](#list-methods)
    + [List Comprehension](#list-comprehension)
    + [List Slicing](#list-slicing)
    + [Nested List](#nested-list)
    + [Sorting in List](#sorting-in-list)
    + [Sets in Python](#sets-in-python)
  * [List Practice Problems - 4](#list-practice-problems---4)
    + [Practice Problem 1 - Find the largest element in an array of size `n`.](#practice-problem-1---find-the-largest-element-in-an-array-of-size--n-)
    + [Practice Problem 2 - Given an array 'ARR' of integers and a position ‘M’, reverse the array from position ‘M+1’ onwards.](#practice-problem-2---given-an-array--arr--of-integers-and-a-position--m---reverse-the-array-from-position--m-1--onwards)
    + [Practice Problem 3 - Given an array 'arr' containing 'n' elements, rotate this array left once by shifting all elements to the left and moving the first element to the last position.](#practice-problem-3---given-an-array--arr--containing--n--elements--rotate-this-array-left-once-by-shifting-all-elements-to-the-left-and-moving-the-first-element-to-the-last-position)
    + [Practice Problem 4 - Given an array ‘a’ of ‘n’ non-negative integers, check whether the array is sorted in non-decreasing order. Return 1 if the array is sorted, else return 0.](#practice-problem-4---given-an-array--a--of--n--non-negative-integers--check-whether-the-array-is-sorted-in-non-decreasing-order-return-1-if-the-array-is-sorted--else-return-0)
  * [Tuple - 4](#tuple---4)
    + [What is Tuples in Python](#what-is-tuples-in-python)
    + [Difference between List and Tuples](#difference-between-list-and-tuples)
    + [Tuple Methods](#tuple-methods)
    + [Practice Problem 1 - Sorting Tuples](#practice-problem-1---sorting-tuples)
  * [Dictionary - 6](#dictionary---6)
    + [What is Dictionary in Python](#what-is-dictionary-in-python)
    + [Dictionary Methods](#dictionary-methods)
    + [Difference between List, Tuple, and Dictionary](#difference-between-list--tuple--and-dictionary)
    + [Sorting Dictionary](#sorting-dictionary)
    + [Dictionary Comprehension](#dictionary-comprehension)
    + [Practice Problem 1](#practice-problem-1)
  * [String - 7](#string---7)
    + [What is String in Python](#what-is-string-in-python)
    + [String Manipulation](#string-manipulation)
    + [F-String in Python](#f-string-in-python)
    + [Slicing in String](#slicing-in-string)
    + [Split in String](#split-in-string)
    + [Join in String](#join-in-string)
    + [String Methods](#string-methods)
  * [String Practice Problems - 3](#string-practice-problems---3)
    + [Practice Problem 1](#practice-problem-1-1)
    + [Practice Problem 2](#practice-problem-2)
    + [Practice Problem 3](#practice-problem-3)
  * [Linked List - 5](#linked-list---5)
    + [What is a Linked List in Python](#what-is-a-linked-list-in-python)
    + [Practice Problems](#practice-problems-3)
- [OOPS Concept](#oops-concept)
  * [Introduction to OOPS - 8](#introduction-to-oops---8)
    + [OOPS and Its Characteristics](#oops-and-its-characteristics)
    + [Features of OOPS](#features-of-oops)
    + [Application of OOPS](#application-of-oops)
    + [Aggregation and Composition](#aggregation-and-composition)
    + [Classes and Objects](#classes-and-objects)
    + [`__init__` and `self` Method in Python](#---init----and--self--method-in-python)
    + [Mutable and Immutable Objects in Python](#mutable-and-immutable-objects-in-python)
    + [Class Attributes and Instance Attributes](#class-attributes-and-instance-attributes)
  * [Encapsulation - 5](#encapsulation---5)
    + [What is Encapsulation](#what-is-encapsulation)
    + [Access Modifiers](#access-modifiers)
    + [Getter and Setter Methods](#getter-and-setter-methods)
    + [Property Decorators](#property-decorators)
    + [Class Method, Static Method, and Instance Method](#class-method--static-method--and-instance-method)
  * [Abstraction - 3](#abstraction---3)
    + [What is Abstraction](#what-is-abstraction)
    + [Abstract Classes](#abstract-classes)
    + [Interface](#interface)
  * [Inheritance - 5](#inheritance---5)
    + [What is Inheritance](#what-is-inheritance)
    + [Types of Inheritance](#types-of-inheritance)
    + [Constructor](#constructor)
    + [Super Method](#super-method)
    + [Dunder or Magic Methods](#dunder-or-magic-methods)
  * [Polymorphism - 5](#polymorphism---5)
    + [What is Polymorphism](#what-is-polymorphism)
    + [Method Overloading and Method Overriding](#method-overloading-and-method-overriding)
    + [Duck Typing](#duck-typing)
    + [Operator Overloading](#operator-overloading)
    + [Dynamic Typing](#dynamic-typing)
  * [Practice Problems - 4](#practice-problems---4)
    + [Practice Problem 1 - Rectangle](#practice-problem-1---rectangle)
    + [Practice Problem 2 - Car and RaceCar](#practice-problem-2---car-and-racecar)
    + [Practice Problem 3 - ComplexNumber](#practice-problem-3---complexnumber)
    + [Practice Problem 4 - Polynomial Multiplication](#practice-problem-4---polynomial-multiplication)
- [DSA in Python](#dsa-in-python)
  * [Arrays - 27](#arrays---27)
    + [Arrays in Python](#arrays-in-python)
    + [1. Second Largest Element](#1-second-largest-element)
    + [2. Rotate an Array by K](#2-rotate-an-array-by-k)
    + [3. Non-Decreasing Array](#3-non-decreasing-array)
    + [4. Equilibrium Index](#4-equilibrium-index)
    + [5. First Missing Positive](#5-first-missing-positive)
    + [6. Make Unique Array](#6-make-unique-array)
    + [7. Sum of Zeroes](#7-sum-of-zeroes)
    + [8. Matrix Symmetric](#8-matrix-symmetric)
    + [9. Pair Sum](#9-pair-sum)
    + [10. Bubble Sort](#10-bubble-sort)
    + [11. Selection Sort](#11-selection-sort)
    + [12. Insertion Sort](#12-insertion-sort)
    + [13. Intersection of Two Arrays](#13-intersection-of-two-arrays)
    + [14. Kadane’s Algorithm](#14-kadane-s-algorithm)
    + [15. Move Zeroes to End](#15-move-zeroes-to-end)
    + [16. Square Root](#16-square-root)
    + [17. Search in Rotated Sorted Array](#17-search-in-rotated-sorted-array)
    + [18. Move Negative Numbers to Start](#18-move-negative-numbers-to-start)
    + [19. Container with Most Water](#19-container-with-most-water)
    + [20. Longest Subarray Zero Sum](#20-longest-subarray-zero-sum)
    + [21. Dutch National Flag Algorithm](#21-dutch-national-flag-algorithm)
    + [22. Moore’s Voting Algorithm](#22-moore-s-voting-algorithm)
    + [23. Check Subsequence](#23-check-subsequence)
    + [24. Inplace Rotate Matrix 90 Degrees](#24-inplace-rotate-matrix-90-degrees)
    + [25. Set Matrix Zeroes](#25-set-matrix-zeroes)
    + [26. Count All Sub-arrays Having Sum Divisible by K](#26-count-all-sub-arrays-having-sum-divisible-by-k)
    + [27. Spiral Order](#27-spiral-order)
  * [Strings - 9](#strings---9)
    + [Strings in Python](#strings-in-python)
    + [1. Reverse String Word Wise](#1-reverse-string-word-wise)
    + [2. String Encoding](#2-string-encoding)
    + [3. Minimum Parenthesis](#3-minimum-parenthesis)
    + [4. Beautiful Strings](#4-beautiful-strings)
    + [5. Next Smallest Palindrome](#5-next-smallest-palindrome)
    + [6. First Non-Repeating Character in String](#6-first-non-repeating-character-in-string)
    + [7. Check Permutation](#7-check-permutation)
    + [8. Find Kth Character of Decrypted String](#8-find-kth-character-of-decrypted-string)
    + [9. Group Anagrams](#9-group-anagrams)
  * [Recursion - 6](#recursion---6)
    + [Recursion in Python](#recursion-in-python)
    + [1. Merge Sort](#1-merge-sort)
    + [2. Quick Sort](#2-quick-sort)
    + [3. Tower of Hanoi](#3-tower-of-hanoi)
    + [4. Find Kth Element](#4-find-kth-element)
    + [5. Family Structure](#5-family-structure)
    + [6. Binary String With No Consecutive 1s](#6-binary-string-with-no-consecutive-1s)
  * [Linked List - 10](#linked-list---10)
    + [Linked List in Python](#linked-list-in-python)
    + [1. Reverse A Linked List](#1-reverse-a-linked-list)
    + [2. Mid Point In Linked List](#2-mid-point-in-linked-list)
    + [3. Merge Sort](#3-merge-sort)
    + [4. Add Two Linked Lists](#4-add-two-linked-lists)
    + [5. Insertion Sort on Linked List](#5-insertion-sort-on-linked-list)
    + [6. Delete Kth Node from End](#6-delete-kth-node-from-end)
    + [7. Detect And Remove Cycle](#7-detect-and-remove-cycle)
    + [8. Swap Nodes In Pairs](#8-swap-nodes-in-pairs)
    + [9. Append Nodes](#9-append-nodes)
    + [10. Segregate Odd Even](#10-segregate-odd-even)
  * [Stacks & Queues - 10](#stacks---queues---10)
    + [Stacks and Queues in Python](#stacks-and-queues-in-python)
    + [1. Implement Stack Using Array](#1-implement-stack-using-array)
    + [2. Implement Stack Using Linked List](#2-implement-stack-using-linked-list)
    + [3. Implement Queue Using Array/Linked List](#3-implement-queue-using-array-linked-list)
    + [4. Implement Queue Using 2 Stacks](#4-implement-queue-using-2-stacks)
    + [5. Implement Stack Using 2 Queues](#5-implement-stack-using-2-queues)
    + [6. Min Stack](#6-min-stack)
    + [7. Next Greater Element](#7-next-greater-element)
    + [8. Stock Span Problem](#8-stock-span-problem)
    + [9. Reverse Queue](#9-reverse-queue)
    + [10. Valid Parentheses](#10-valid-parentheses)
  * [Binary Trees & BST - 16](#binary-trees---bst---16)
    + [Binary Trees and Binary Search Trees (BST) in Python](#binary-trees-and-binary-search-trees--bst--in-python)
    + [1. Diameter of Binary Tree](#1-diameter-of-binary-tree)
    + [2. Lowest Common Ancestor (LCA) of Binary Tree](#2-lowest-common-ancestor--lca--of-binary-tree)
    + [3. Level Order Traversal of Binary Tree](#3-level-order-traversal-of-binary-tree)
    + [4. Zigzag Order Traversal of Binary Tree](#4-zigzag-order-traversal-of-binary-tree)
    + [5. Left View of Binary Tree](#5-left-view-of-binary-tree)
    + [6. Top View of Binary Tree](#6-top-view-of-binary-tree)
    + [7. Construct Binary Tree From Inorder and Preorder](#7-construct-binary-tree-from-inorder-and-preorder)
    + [8. Vertical Order Traversal of Binary Tree](#8-vertical-order-traversal-of-binary-tree)
    + [9. Inorder Traversal of Binary Tree Using Stacks](#9-inorder-traversal-of-binary-tree-using-stacks)
    + [10. LCA of Two Nodes in BST](#10-lca-of-two-nodes-in-bst)
    + [11. BST Delete](#11-bst-delete)
    + [12. Check if Binary Tree is BST](#12-check-if-binary-tree-is-bst)
    + [13. Kth Smallest Element in BST](#13-kth-smallest-element-in-bst)
    + [14. Predecessor and Successor in BST](#14-predecessor-and-successor-in-bst)
    + [15. LCA of 3 Nodes](#15-lca-of-3-nodes)
    + [16. Pair Sum in BST](#16-pair-sum-in-bst)
  * [Priority Queues & Heaps - 7](#priority-queues---heaps---7)
    + [Priority Queues & Heaps in Python](#priority-queues---heaps-in-python)
    + [1. Implement Priority Queue](#1-implement-priority-queue)
    + [2. Convert Min Heap to Max Heap](#2-convert-min-heap-to-max-heap)
    + [3. Kth Smallest & Largest Element](#3-kth-smallest---largest-element)
    + [4. Kth Largest Sum Subarray](#4-kth-largest-sum-subarray)
    + [5. Merge K Sorted Arrays](#5-merge-k-sorted-arrays)
    + [6. Running Median](#6-running-median)
    + [7. Connect n Ropes with Minimum Cost](#7-connect-n-ropes-with-minimum-cost)
  * [Advanced Recursion & Backtracking - 8](#advanced-recursion---backtracking---8)
    + [Advanced Recursion & Backtracking in Python](#advanced-recursion---backtracking-in-python)
    + [1. N Queen Problem](#1-n-queen-problem)
    + [2. Sudoku Solver](#2-sudoku-solver)
    + [3. Rat in a Maze](#3-rat-in-a-maze)
    + [4. Letter Combinations Of Phone Number](#4-letter-combinations-of-phone-number)
    + [5. Subsequences of String](#5-subsequences-of-string)
    + [6. Combination Sum](#6-combination-sum)
    + [7. Print Permutations](#7-print-permutations)
    + [8. Restore IP Addresses](#8-restore-ip-addresses)
  * [Dynamic Programming - 15](#dynamic-programming---15)
    + [Dynamic Programming in Python](#dynamic-programming-in-python)
    + [1. Count Ways to Reach Nth Stair](#1-count-ways-to-reach-nth-stair)
    + [2. House Robber](#2-house-robber)
    + [3. Ways to Make Coin Change](#3-ways-to-make-coin-change)
    + [4. Rod Cutting Problem](#4-rod-cutting-problem)
    + [5. Minimum Jumps To Reach End](#5-minimum-jumps-to-reach-end)
    + [6. Minimum Steps to Reach Target by Knight](#6-minimum-steps-to-reach-target-by-knight)
    + [7. Longest Increasing Subsequence](#7-longest-increasing-subsequence)
    + [8. Longest Common Subsequence](#8-longest-common-subsequence)
    + [9. Edit Distance](#9-edit-distance)
    + [10. Interleaving Two Strings](#10-interleaving-two-strings)
    + [11. Minimum Deletions](#11-minimum-deletions)
    + [12. 0-1 Knapsack](#12-0-1-knapsack)
    + [13. Best Time to Buy and Sell Stock](#13-best-time-to-buy-and-sell-stock)
    + [14. Matrix Chain Multiplication](#14-matrix-chain-multiplication)
    + [15. Partition Equal Subset Sum](#15-partition-equal-subset-sum)
  * [Graphs - 13](#graphs---13)
    + [Graphs in Python](#graphs-in-python)
    + [1. Largest Island](#1-largest-island)
    + [2. Is Graph a Tree?](#2-is-graph-a-tree-)
    + [3. Snake & Ladder Problem](#3-snake---ladder-problem)
    + [4. Shortest Path in Binary Matrix](#4-shortest-path-in-binary-matrix)
    + [5. Dijkstra’s Algorithm](#5-dijkstra-s-algorithm)
    + [6. MST Using Prim’s Algorithm (With Priority Queue)](#6-mst-using-prim-s-algorithm--with-priority-queue-)
    + [7. MST Using Kruskal's Algorithm (With Disjoint Set Union)](#7-mst-using-kruskal-s-algorithm--with-disjoint-set-union-)
    + [8. Topological Sort](#8-topological-sort)
    + [9. M Coloring Problem](#9-m-coloring-problem)
    + [10. Detect Cycle in Directed Graph](#10-detect-cycle-in-directed-graph)
    + [11. Bipartite Check](#11-bipartite-check)
    + [12. Bellman-Ford Algorithm](#12-bellman-ford-algorithm)
    + [13. Floyd-Warshall Algorithm](#13-floyd-warshall-algorithm)
- [Advanced Python](#advanced-python)
  * [Modules and Packages - 9](#modules-and-packages---9)
    + [Module](#module)
    + [Packages](#packages)
    + [Importing Modules in Python](#importing-modules-in-python)
    + [Difference between Modules and Packages](#difference-between-modules-and-packages)
    + [Libraries](#libraries)
    + [Math Module](#math-module)
    + [Collection Module](#collection-module)
    + [Time Module](#time-module)
    + [OS Module](#os-module)
  * [Exception Handling - 9](#exception-handling---9)
    + [Exceptions and Errors](#exceptions-and-errors)
    + [What is Exception Handling](#what-is-exception-handling)
    + [Try and Except Statement](#try-and-except-statement)
    + [Built-in Exceptions](#built-in-exceptions)
    + [Raising Exception](#raising-exception)
    + [Multiple Exception Handling](#multiple-exception-handling)
    + [Handling TypeError Exception](#handling-typeerror-exception)
    + [Handling NameError Exception](#handling-nameerror-exception)
    + [AttributeError](#attributeerror)
  * [File Handling - 5](#file-handling---5)
    + [What is File Handling](#what-is-file-handling)
    + [Reading from File](#reading-from-file)
    + [Writing to File](#writing-to-file)
    + [Appending to File](#appending-to-file)
    + [File Modes](#file-modes)
  * [Multithreading - 6](#multithreading---6)
    + [What is Multithreading](#what-is-multithreading)
    + [Thread in Python](#thread-in-python)
    + [Creating New Thread](#creating-new-thread)
    + [Thread-Based Parallelism](#thread-based-parallelism)
    + [Handling Thread Exceptions](#handling-thread-exceptions)
    + [Socket Programming with Multithreading](#socket-programming-with-multithreading)
- [Python Libraries](#python-libraries)
  * [Package Manager in Python - 3](#package-manager-in-python---3)
    + [Libraries in Python](#libraries-in-python)
    + [PIP in Python](#pip-in-python)
    + [Import in Python](#import-in-python)
  * [Numpy - 13](#numpy---13)
    + [Installing Numpy](#installing-numpy)
    + [Basic Operations](#basic-operations)
    + [Numpy Datatypes](#numpy-datatypes)
    + [Numpy Array Creation](#numpy-array-creation)
    + [Slicing and Indexing in Numpy](#slicing-and-indexing-in-numpy)
    + [Numpy Reshape](#numpy-reshape)
    + [Numpy Iteration](#numpy-iteration)
    + [Numpy String Functions](#numpy-string-functions)
    + [Numpy Join](#numpy-join)
    + [Numpy Search](#numpy-search)
    + [Numpy Sort](#numpy-sort)
    + [Compare and Filter in Numpy](#compare-and-filter-in-numpy)
  * [Pandas - 10](#pandas---10)
    + [Importing Pandas](#importing-pandas)
    + [Difference between Numpy and Pandas](#difference-between-numpy-and-pandas)
    + [Pandas Profiling](#pandas-profiling)
    + [Pandas Series](#pandas-series)
    + [Pandas DataFrame](#pandas-dataframe)
    + [Read Excel with Pandas](#read-excel-with-pandas)
    + [Read JSON with Pandas](#read-json-with-pandas)
    + [Selecting, Extracting and Slicing DataFrames](#selecting--extracting-and-slicing-dataframes)
    + [Functions in Pandas](#functions-in-pandas)
    + [Data Cleaning using Pandas](#data-cleaning-using-pandas)
  * [Matplotlib - 6](#matplotlib---6)
    + [What is Matplotlib](#what-is-matplotlib)
    + [Ticks in Matplotlib](#ticks-in-matplotlib)
    + [Bar Plot](#bar-plot)
    + [Scatter Plot](#scatter-plot)
    + [Histogram Plot](#histogram-plot)
    + [Box and Whisker Plot](#box-and-whisker-plot)
  * [OpenCV - 17](#opencv---17)
    + [What is OpenCV](#what-is-opencv)
    + [Reading Image File](#reading-image-file)
    + [Display Image File](#display-image-file)
    + [Writing Image File](#writing-image-file)
    + [Image Read, Write and Display](#image-read--write-and-display)
    + [Feature Matching](#feature-matching)
    + [Color Filtering](#color-filtering)
    + [Color Spaces](#color-spaces)
    + [Cropping Image](#cropping-image)
    + [Bitwise Operations on Images](#bitwise-operations-on-images)
    + [Adaptive Thresholding](#adaptive-thresholding)
    + [Motion Estimation](#motion-estimation)
    + [Contours](#contours)
    + [Feature Detection with HAAR Cascade Classifier](#feature-detection-with-haar-cascade-classifier)
    + [Smoothing Images](#smoothing-images)
    + [Face Detection](#face-detection)
    + [Eyeball Tracking](#eyeball-tracking)
    + [Summary](#summary)
- [Flask](#flask)
  * [Fundamentals of Flask - 6](#fundamentals-of-flask---6)
    + [Introduction to Flask](#introduction-to-flask)
    + [Environment Setup and Creating First Application](#environment-setup-and-creating-first-application)
    + [Routing in Flask](#routing-in-flask)
    + [Variable Rules in Flask](#variable-rules-in-flask)
    + [URL Building in Flask](#url-building-in-flask)
    + [HTTP Methods in Flask](#http-methods-in-flask)
  * [Web Development with Flask - 9](#web-development-with-flask---9)
    + [Templates in Flask](#templates-in-flask)
    + [Static File Handling in Flask](#static-file-handling-in-flask)
    + [Request Object in Flask](#request-object-in-flask)
    + [JSON Response in Flask](#json-response-in-flask)
    + [Sending Form Data to Template in Flask](#sending-form-data-to-template-in-flask)
    + [Cookies in Flask](#cookies-in-flask)
    + [OAuth in Flask](#oauth-in-flask)
    + [Error Handling in Flask](#error-handling-in-flask)
    + [File Uploading in Flask](#file-uploading-in-flask)
  * [Advanced Flask Topics - 3](#advanced-flask-topics---3)
    + [Flask Mail](#flask-mail)
    + [Flask WTForms](#flask-wtforms)
    + [Flask Deployment](#flask-deployment)
- [Django](#django)
  * [Django Fundamentals - 5](#django-fundamentals---5)
    + [What is Django](#what-is-django)
    + [Basics of Django Framework](#basics-of-django-framework)
    + [Django Installation](#django-installation)
    + [Project Structure in Django](#project-structure-in-django)
    + [Django Admin Interface](#django-admin-interface)
  * [Django Frontend Development - 5](#django-frontend-development---5)
    + [Django Templates](#django-templates)
    + [Django Views](#django-views)
    + [Variables in Django](#variables-in-django)
    + [If-Else in Django](#if-else-in-django)
    + [Loop in Django](#loop-in-django)
  * [Django Backend Development - 10](#django-backend-development---10)
    + [Creating Django App](#creating-django-app)
    + [Django Redirect](#django-redirect)
    + [Django Forms](#django-forms)
    + [Creating Django Forms](#creating-django-forms)
    + [Django Form Fields](#django-form-fields)
    + [Django Formsets](#django-formsets)
    + [Django Models](#django-models)
    + [Django CRUD Operations](#django-crud-operations)
    + [Sessions in Django](#sessions-in-django)
    + [REST API](#rest-api)
- [Most Frequently Asked Coding Problems - 15](#most-frequently-asked-coding-problems---15)
    + [1. Reverse a 32-bit signed integer `N`](#1-reverse-a-32-bit-signed-integer--n-)
    + [2. Check if a number is a prime number](#2-check-if-a-number-is-a-prime-number)
    + [3. Generate the first `n` Fibonacci numbers using a generator function](#3-generate-the-first--n--fibonacci-numbers-using-a-generator-function)
    + [4. Find the largest of three given numbers `a`, `b`, and `c`](#4-find-the-largest-of-three-given-numbers--a----b---and--c-)
    + [5. Calculate the floor value of Simple Interest](#5-calculate-the-floor-value-of-simple-interest)
    + [6. Convert a binary string to its decimal equivalent](#6-convert-a-binary-string-to-its-decimal-equivalent)
    + [7. Check if a given year is a leap year](#7-check-if-a-given-year-is-a-leap-year)
    + [8. Calculate the factorial of a number](#8-calculate-the-factorial-of-a-number)
    + [9. Find all palindromic numbers from 1 to `N`](#9-find-all-palindromic-numbers-from-1-to--n-)
    + [10. Calculate the LCM (Least Common Multiple) of two numbers](#10-calculate-the-lcm--least-common-multiple--of-two-numbers)
    + [11. Print the first `N` rows of Pascal's Triangle](#11-print-the-first--n--rows-of-pascal-s-triangle)
    + [12. Reverse the array `arr` of size `n`](#12-reverse-the-array--arr--of-size--n-)
    + [13. Compute and return the transpose of a matrix `MAT`](#13-compute-and-return-the-transpose-of-a-matrix--mat-)
    + [14. Determine if a given integer `n` is an Armstrong number](#14-determine-if-a-given-integer--n--is-an-armstrong-number)
    + [15. Find the missing number in the range 1 to `n`](#15-find-the-missing-number-in-the-range-1-to--n-)
- [Interview Questions - 10](#interview-questions---10)

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>


# Python Basics

## Introduction to Python - 6

### What is Python

- **Python** is a high-level, interpreted, general-purpose programming language.
- Created by **Guido van Rossum** and first released in **1991**.
- Emphasizes code readability with its notable use of significant indentation.
- Widely used for web development, data analysis, artificial intelligence, scientific computing, and more.

### Basic Syntax

- Python uses **indentation** (whitespace) to define code blocks.
- No need for **curly braces** `{}` or **semicolon** `;` at the end of statements.
- Example:
    
    ```python
    if x > 0:
        print("Positive")
    else:
        print("Non-positive")
    ```
    

### Keywords

- Reserved words in Python that have a special meaning and cannot be used as identifiers.
- Examples include `False`, `None`, `True`, `and`, `or`, `not`, `if`, `else`, `elif`, `while`, `for`, `break`, `continue`, `return`, `import`, `from`, `as`, `class`, `def`, `pass`, `global`, `in`, `is`, `lambda`, `try`, `except`, `finally`, `raise`, `with`, `yield`, etc.
- Use `keyword` module to get a list of keywords:
    
    ```python
    import keyword
    print(keyword.kwlist)
    ```
    

### Comments

- Used to explain code and make it more readable.
- Single-line comments start with `#`:
    
    ```python
    # This is a single-line comment
    print("Hello, World!")  # This is an inline comment
    ```
    
- Multi-line comments can be done using triple quotes `'''` or `"""`:
    
    ```python
    """
    This is a
    multi-line comment
    """
    ```
    

### Input/Output Statements

- **Input**: Use `input()` to take input from the user:
    
    ```python
    name = input("Enter your name: ")
    print("Hello, " + name)
    ```
    
- **Output**: Use `print()` to display output:
    
    ```python
    print("Hello, World!")
    print("Hello, ", name)
    ```
    

### Indentation

- Indentation is crucial in Python; it defines the scope and grouping of code blocks.
- Typically, **4 spaces** per indentation level.
- Example:
    
    ```python
    def greet(name):
        if name:
            print(f"Hello, {name}")
        else:
            print("Hello, World!")
    ```
    

## Literals Variables and Datatypes - 4

### Literals

- **Literals** are constant values assigned to variables.
- Types of literals:
    - **String literals**: Enclosed in single, double, or triple quotes.
        
        ```python
        single_quote = 'Hello'
        double_quote = "World"
        triple_quote = '''Hello
        World'''
        
        ```
        
    - **Numeric literals**: Can be integers, floats, or complex numbers.
        
        ```python
        integer = 10
        float_num = 10.5
        complex_num = 3 + 5j
        
        ```
        
    - **Boolean literals**: `True` or `False`.
        
        ```python
        is_true = True
        is_false = False
        
        ```
        
    - **Special literals**: `None` represents the absence of value.
        
        ```python
        nothing = None
        
        ```
        

### Variables

- **Variables** are used to store data that can be modified later.
- Variable names must start with a letter or underscore, followed by letters, digits, or underscores.
- Python is **dynamically typed**: the type is inferred at runtime.
    
    ```python
    name = "Alice"
    age = 30
    height = 5.7
    is_student = False
    
    ```
    
- Variables can be reassigned to different data types.
    
    ```python
    x = 5
    x = "Hello"
    
    ```
    

### Datatypes

- Python supports several built-in data types:
    - **Numbers**: `int`, `float`, `complex`
        
        ```python
        a = 10       # int
        b = 10.5     # float
        c = 3 + 5j   # complex
        
        ```
        
    - **Sequences**: `str`, `list`, `tuple`
        
        ```python
        s = "Hello"            # str
        l = [1, 2, 3]          # list
        t = (1, 2, 3)          # tuple
        
        ```
        
    - **Mappings**: `dict`
        
        ```python
        d = {"name": "Alice", "age": 30}
        
        ```
        
    - **Sets**: `set`, `frozenset`
        
        ```python
        st = {1, 2, 3}         # set
        fs = frozenset([1, 2, 3])
        
        ```
        
    - **Boolean**: `bool`
        
        ```python
        b = True
        
        ```
        
    - **NoneType**: `None`
        
        ```python
        n = None
        
        ```
        

### Type Conversion and Type Casting

- **Type Conversion**: Implicit conversion done automatically by Python.
    
    ```python
    x = 10        # int
    y = 10.5      # float
    z = x + y     # y is implicitly converted to float
    
    ```
    
- **Type Casting**: Explicitly converting one data type to another using built-in functions.
    - **int()**: Converts to integer.
        
        ```python
        x = int(10.5)      # x will be 10
        
        ```
        
    - **float()**: Converts to float.
        
        ```python
        y = float(10)      # y will be 10.0
        
        ```
        
    - **str()**: Converts to string.
        
        ```python
        z = str(10)        # z will be '10'
        
        ```
        
    - **list()**: Converts to list.
        
        ```python
        l = list("abc")    # l will be ['a', 'b', 'c']
        
        ```
        
    - **tuple()**: Converts to tuple.
        
        ```python
        t = tuple([1, 2, 3])  # t will be (1, 2, 3)
        
        ```
        
    - **set()**: Converts to set.
        
        ```python
        s = set([1, 2, 3])    # s will be {1, 2, 3}
        ```
        

## Operators - 8

### What is Operator

- **Operators** are special symbols or keywords used to perform operations on variables and values.
- They can be classified into various types based on their functionality.

### Operator Precedence

- **Operator Precedence** defines the order in which operators are evaluated in expressions.
- Operators with higher precedence are evaluated before operators with lower precedence.
- Example of precedence (from highest to lowest):
    1. `*` (Exponentiation)
    2. ``, `/`, `//`, `%` (Multiplication, Division, Floor Division, Modulus)
    3. `+`, `` (Addition, Subtraction)
    4. `==`, `!=`, `>`, `<`, `>=`, `<=` (Comparison Operators)
    5. `not` (Logical NOT)
    6. `and` (Logical AND)
    7. `or` (Logical OR)
- Use parentheses `()` to override the default precedence.

### Arithmetic Operators

- Used to perform basic arithmetic operations.
    
    ```python
    x = 10
    y = 5
    
    addition = x + y        # 15
    subtraction = x - y     # 5
    multiplication = x * y  # 50
    division = x / y        # 2.0
    floor_div = x // y      # 2
    modulus = x % y         # 0
    exponent = x ** y       # 100000
    
    ```
    

### Assignment Operators

- Used to assign values to variables.
    
    ```python
    x = 10        # Assign 10 to x
    x += 5        # x = x + 5 -> 15
    x -= 3        # x = x - 3 -> 12
    x *= 2        # x = x * 2 -> 24
    x /= 4        # x = x / 4 -> 6.0
    x %= 5        # x = x % 5 -> 1.0
    x //= 2       # x = x // 2 -> 0.0
    x **= 3       # x = x ** 3 -> 0.0
    
    ```
    

### Relational Operators

- Used to compare two values. The result is a boolean value (`True` or `False`).
    
    ```python
    x = 10
    y = 5
    
    equal = x == y         # False
    not_equal = x != y     # True
    greater = x > y        # True
    less = x < y           # False
    greater_equal = x >= y # True
    less_equal = x <= y    # False
    
    ```
    

### Bitwise Operators

- Used to perform bit-level operations on integers.
    
    ```python
    x = 5        # 0b0101
    y = 3        # 0b0011
    
    and_op = x & y       # 0b0001 -> 1
    or_op = x | y        # 0b0111 -> 7
    xor_op = x ^ y       # 0b0110 -> 6
    not_op = ~x          # -(0b0101 + 1) -> -6
    left_shift = x << 1  # 0b1010 -> 10
    right_shift = x >> 1 # 0b0010 -> 2
    
    ```
    

### Ternary Operators

- Also known as conditional expressions, provide a shorthand way of writing `if-else` statements.
    
    ```python
    x = 10
    y = 20
    
    result = "x is greater" if x > y else "y is greater"
    print(result)  # y is greater
    
    ```
    

### Logical Operators

- Used to combine conditional statements.
    
    ```python
    x = True
    y = False
    
    and_op = x and y   # False
    or_op = x or y     # True
    not_op = not x     # False
    
    ```
    

## Conditional Statements - 7

### Decision Making Statements

- **Conditional statements** allow you to execute certain blocks of code based on conditions.
- Common statements:
    - **`if` statement**: Executes a block of code if the condition is `True`.
        
        ```python
        if condition:
            # Code to execute
        
        ```
        
    - **`if-else` statement**: Executes one block if the condition is `True`, and another block if it is `False`.
        
        ```python
        if condition:
            # Code to execute if True
        else:
            # Code to execute if False
        
        ```
        
    - **`if-elif-else` statement**: Checks multiple conditions.
        
        ```python
        if condition1:
            # Code to execute if condition1 is True
        elif condition2:
            # Code to execute if condition2 is True
        else:
            # Code to execute if no conditions are True
        
        ```
        

### Implementation of Switch Case Statement

- Python does not have a built-in `switch-case` statement like some other languages, but you can achieve similar functionality using a dictionary of functions or a series of `if-elif-else` statements.
- Example using dictionary:
    
    ```python
    def circle_area(r):
        import math
        return math.pi * r * r
    
    def rectangle_area(l, b):
        return l * b
    
    switch_case = {
        1: lambda r: circle_area(r),
        2: lambda l, b: rectangle_area(l, b)
    }
    
    choice = 1  # Example choice
    if choice in switch_case:
        result = switch_case   # Example radius for circle
    
    ```
    

### Jump Statements

- **Jump statements** alter the flow of control in loops and conditionals.
    - **`break`**: Exits the closest enclosing loop.
        
        ```python
        for i in range(10):
            if i == 5:
                break
        
        ```
        
    - **`continue`**: Skips the rest of the code inside the loop for the current iteration and proceeds to the next iteration.
        
        ```python
        for i in range(10):
            if i == 5:
                continue
            print(i)
        
        ```
        
    - **`pass`**: A placeholder that does nothing. Used when a statement is syntactically required but you do not want to execute any code.
        
        ```python
        for i in range(10):
            if i == 5:
                pass
        
        ```
        

### Practice Problems

**Practice Problem 1**

- **Problem**: Given two integers `a` and `b`, print "smaller" if `a` < `b`, "greater" if `a` > `b`, or "equal" if `a` == `b`.
    
    ```python
    a = int(input("Enter first number: "))
    b = int(input("Enter second number: "))
    
    if a < b:
        print("smaller")
    elif a > b:
        print("greater")
    else:
        print("equal")
    
    ```
    

**Practice Problem 2**

- **Problem**: Given a character, print `1` if it's an uppercase letter, `0` if it's a lowercase letter, or `1` if it's not a letter.
    
    ```python
    char = input("Enter a character: ")
    
    if char.isupper():
        print(1)
    elif char.islower():
        print(0)
    else:
        print(-1)
    
    ```
    

**Practice Problem 3**

- **Problem**: Given three numbers `a`, `b`, and `c`, print the largest among them.
    
    ```python
    a = int(input("Enter first number: "))
    b = int(input("Enter second number: "))
    c = int(input("Enter third number: "))
    
    if a >= b and a >= c:
        print(a)
    elif b >= a and b >= c:
        print(b)
    else:
        print(c)
    
    ```
    

**Practice Problem 4**

- **Problem**: Use a switch-case structure in Python to calculate and print the area based on choice `ch`: `1` for circle (π * r²) with radius `r`, or `2` for rectangle (l * b) with dimensions `l` and `b`.
    
    ```python
    import math
    
    def circle_area(r):
        return math.pi * r * r
    
    def rectangle_area(l, b):
        return l * b
    
    def calculate_area(choice, *args):
        switch_case = {
            1: lambda r: circle_area(r),
            2: lambda l, b: rectangle_area(l, b)
        }
        if choice in switch_case:
            return switch_case[choice](*args)
        else:
            return "Invalid choice"
    
    choice = int(input("Enter choice (1 for circle, 2 for rectangle): "))
    if choice == 1:
        radius = float(input("Enter radius: "))
        print("Area:", calculate_area(choice, radius))
    elif choice == 2:
        length = float(input("Enter length: "))
        breadth = float(input("Enter breadth: "))
        print("Area:", calculate_area(choice, length, breadth))
    else:
        print("Invalid choice")
    ```
    

## Loops - 10

### Loops and its Types

Loops are used to execute a block of code repeatedly. There are two primary types of loops in Python:

- **`for` loop**: Iterates over a sequence (like a list, tuple, or range) or other iterable objects.
    
    ```python
    for i in range(5):
        print(i)
    
    ```
    
- **`while` loop**: Repeats as long as a condition is `True`.
    
    ```python
    i = 0
    while i < 5:
        print(i)
        i += 1
    
    ```
    

### While Loop

- Executes a block of code as long as its condition remains `True`.
    
    ```python
    count = 0
    while count < 5:
        print(count)
        count += 1
    
    ```
    

### For Loop

- Iterates over a sequence (list, tuple, string) or a range of numbers.
    
    ```python
    for num in range(5):
        print(num)
    
    ```
    

### Nested Loop

- Loops within loops. The inner loop runs completely for each iteration of the outer loop.
    
    ```python
    for i in range(3):
        for j in range(2):
            print(i, j)
    
    ```
    

### Iterators and Generators

- **Iterators**: Objects that implement `__iter__()` and `__next__()` methods.
    
    ```python
    nums = [1, 2, 3]
    it = iter(nums)
    print(next(it))
    print(next(it))
    
    ```
    
- **Generators**: Functions that yield values one at a time using the `yield` keyword.
    
    ```python
    def count_up_to(max):
        count = 1
        while count <= max:
            yield count
            count += 1
    
    for num in count_up_to(3):
        print(num)
    
    ```
    

### Practice Problems

**Practice Problem 1**

- **Problem**: Given a number `N`, print the sum of all even numbers from 1 to `N`.
    
    ```python
    N = int(input("Enter N: "))
    total_sum = sum(i for i in range(2, N+1, 2))
    print("Sum of even numbers:", total_sum)
    
    ```
    

**Practice Problem 2**

- **Problem**: Given `Start` Fahrenheit value `S`, `End` Fahrenheit value `E`, and `Step` size `W`, convert all Fahrenheit values from `S` to `E` in steps of `W` into Celsius and print the results. Use the floor value for non-negative Celsius temperatures and the ceiling value for negative Celsius temperatures.
    
    ```python
    import math
    
    S = int(input("Enter Start Fahrenheit: "))
    E = int(input("Enter End Fahrenheit: "))
    W = int(input("Enter Step size: "))
    
    for f in range(S, E+1, W):
        celsius = (f - 32) * 5/9
        if celsius >= 0:
            celsius = math.floor(celsius)
        else:
            celsius = math.ceil(celsius)
        print(f"Fahrenheit {f} = Celsius {celsius}")
    
    ```
    

**Practice Problem 3**

- **Problem**: Compute x^n, x raised to the power n given integers `x` and `n`. Print the result. Assume 0^0 = 1.
    
    ```python
    x, n = map(int, input("Enter x and n separated by space: ").split())
    result = x ** n
    print(result)
    
    ```
    

**Practice Problem 4**

- **Problem**: Print a pattern for a given number of rows `N`:
    - For `N = 5`:
        
        ```
        1 2 3 4 5
        11 12 13 14 15
        21 22 23 24 25
        16 17 18 19 20
        6 7 8 9 10
        
        ```
        
    
    ```python
    N = int(input("Enter number of rows: "))
    num = 1
    for i in range(N):
        if i < N//2:
            for j in range(N):
                print(num, end=' ')
                num += 1
            print()
        else:
            num -= N
            for j in range(N):
                print(num, end=' ')
                num += 1
            num -= N - 1
            print()
    
    ```
    

**Practice Problem 5**

- **Problem**: Print a rectangle of height `M` and breadth `N` using the character * , with * only on the boundaries and spaces inside.
    - For input `2 2`:
        
        ```
        **
        **
        
        ```
        
    - For input `4 3`:
        
        ```
        ***
        * *
        * *
        ***
        
        ```
        
    
    ```python
    def print_rectangle(M, N):
        for i in range(M):
            if i == 0 or i == M-1:
                print('*' * N)
            else:
                print('*' + ' ' * (N-2) + '*')
    
    M, N = map(int, input("Enter height and breadth separated by space: ").split())
    print_rectangle(M, N)
    
    ```
    

## Functions - 9

### Functions in Python

Functions are blocks of reusable code that perform a specific task. They can take arguments, perform operations, and return a result.

- **Defining a Function**:
    
    ```python
    def function_name(parameters):
        # Code block
        return result
    
    ```
    
- **Calling a Function**:
    
    ```python
    function_name(arguments)
    ```
    

### Arguments in Python

Functions can accept arguments, which are values passed into the function.

- **Positional Arguments**: Values passed in a specific order.
    
    ```python
    def add(a, b):
        return a + b
    
    ```
    
- **Keyword Arguments**: Values passed using parameter names.
    
    ```python
    def greet(name, message):
        print(f"Hello {name}, {message}")
    
    greet(name="Alice", message="Welcome!")
    
    ```
    
- **Default Arguments**: Arguments with default values.
    
    ```python
    def greet(name, message="Welcome!"):
        print(f"Hello {name}, {message}")
    
    ```
    
- **Variable-Length Arguments**:
    - **`args`**: For non-keyword variable arguments.
        
        ```python
        def print_numbers(*args):
            for number in args:
                print(number)
        
        ```
        
    - **`*kwargs`**: For keyword variable arguments.
        
        ```python
        def print_info(**kwargs):
            for key, value in kwargs.items():
                print(f"{key}: {value}")
        
        ```
        

### Built-in Functions

Python provides several built-in functions, such as:

- **`len()`**: Returns the length of an object.
    
    ```python
    len("hello")  # Output: 5
    
    ```
    
- **`type()`**: Returns the type of an object.
    
    ```python
    type(5)  # Output: <class 'int'>
    
    ```
    
- **`range()`**: Generates a sequence of numbers.
    
    ```python
    for i in range(3):
        print(i)  # Output: 0 1 2
    
    ```
    
- **`sorted()`**: Returns a sorted list of elements.
    
    ```python
    sorted([3, 1, 2])  # Output: [1, 2, 3]
    
    ```
    

### Lambda Function

A lambda function is an anonymous function defined with the `lambda` keyword. It can have any number of arguments but only one expression.

- **Syntax**:
    
    ```python
    lambda arguments: expression
    
    ```
    
- **Example**:
    
    ```python
    add = lambda x, y: x + y
    print(add(2, 3))  # Output: 5
    
    ```
    

### Higher Order Functions

Functions that accept other functions as arguments or return them.

- **Example**: Using `map` to apply a function to each element in a list.
    
    ```python
    def square(x):
        return x * x
    
    numbers = [1, 2, 3, 4]
    squares = map(square, numbers)
    print(list(squares))  # Output: [1, 4, 9, 16]
    
    ```
    

### Decorators

Decorators are functions that modify the behavior of another function. They are applied using the `@` syntax.

- **Syntax**:
    
    ```python
    @decorator_function
    def function_to_decorate():
        pass
    
    ```
    
- **Example**:
    
    ```python
    def decorator(func):
        def wrapper():
            print("Something is happening before the function.")
            func()
            print("Something is happening after the function.")
        return wrapper
    
    @decorator
    def say_hello():
        print("Hello!")
    
    say_hello()
    
    ```
    

### Recursion

Recursion occurs when a function calls itself to solve a smaller instance of the same problem.

- **Example**: Calculating factorial using recursion.
    
    ```python
    def factorial(n):
        if n == 0:
            return 1
        else:
            return n * factorial(n - 1)
    
    ```
    

### Practice Problems

**Practice Problem 1**

- **Problem**: Print a star pattern for a given integer `N`. The pattern has `N` lines, where each line contains stars centered and padded with spaces.
    - For `N = 4`:
        
        ```
           *
          ***
         *****
        *******
        
        ```
        
    
    ```python
    def print_star_pattern(N):
        for i in range(N):
            stars = '*' * (2 * i + 1)
            print(stars.center(2 * N - 1))
    
    N = int(input("Enter the number of lines: "))
    print_star_pattern(N)
    
    ```
    

**Practice Problem 2**

- **Problem**: Check if a given string `S` is a palindrome by considering only alphabets and numbers. Ignore special characters, whitespaces, and treat the string as case insensitive.
    
    **Function Signature**:
    
    ```python
    def is_palindrome(S: str) -> str:
        pass
    
    ```
    
    - **Example Implementation**:
    
    ```python
    import re
    
    def is_palindrome(S: str) -> str:
        cleaned = re.sub(r'[^a-zA-Z0-9]', '', S).lower()
        return "Yes" if cleaned == cleaned[::-1] else "No"
    
    # Example usage:
    examples = ["N2 i&nJA?a& jnI2n", "A1b22Ba", "codingninjassajNiNgNidoc", "5?36@6?35", "aaBBa@"]
    results = [is_palindrome(ex) for ex in examples]
    print(results)  # Output: ['Yes', 'No', 'Yes', 'Yes', 'No']
    ```
    

# Python Intermediate

## List - 9

### What is List in Python

A list is a mutable, ordered collection of items that can be of different types. Lists are created using square brackets `[]`.

- **Syntax**:
    
    ```python
    my_list = [1, 2, 3, 'hello', 4.5]
    
    ```
    
- **Properties**:
    - **Mutable**: You can change elements.
    - **Ordered**: Elements maintain their order.
    - **Allow Duplicates**: Lists can have duplicate values.

### List Operations

Common operations you can perform on lists:

- **Accessing Elements**:
    
    ```python
    my_list = [10, 20, 30]
    print(my_list[1])  # Output: 20
    
    ```
    
- **Adding Elements**:
    
    ```python
    my_list.append(40)  # Adds 40 at the end
    my_list.insert(1, 15)  # Inserts 15 at index 1
    
    ```
    
- **Removing Elements**:
    
    ```python
    my_list.remove(20)  # Removes the first occurrence of 20
    del my_list[1]  # Removes the element at index 1
    
    ```
    
- **Updating Elements**:
    
    ```python
    my_list[1] = 25  # Updates the element at index 1
    
    ```
    
- **Clearing List**:
    
    ```python
    my_list.clear()  # Removes all elements
    
    ```
    

### Membership Operators

Check if an element is present in a list:

- **`in` Operator**:
    
    ```python
    my_list = [1, 2, 3]
    print(2 in my_list)  # Output: True
    
    ```
    
- **`not in` Operator**:
    
    ```python
    print(4 not in my_list)  # Output: True
    
    ```
    

### List Methods

Common methods available for lists:

- **`append()`**: Adds an element to the end.
    
    ```python
    my_list.append(5)
    
    ```
    
- **`extend()`**: Extends the list by appending elements from another iterable.
    
    ```python
    my_list.extend([6, 7])
    
    ```
    
- **`pop()`**: Removes and returns the element at the given position.
    
    ```python
    my_list.pop()  # Removes and returns the last element
    
    ```
    
- **`index()`**: Returns the index of the first occurrence of a value.
    
    ```python
    my_list.index(5)  # Output: index of 5
    
    ```
    
- **`count()`**: Returns the number of occurrences of a value.
    
    ```python
    my_list.count(2)  # Output: count of 2
    
    ```
    
- **`sort()`**: Sorts the list in ascending order (in-place).
    
    ```python
    my_list.sort()
    
    ```
    
- **`reverse()`**: Reverses the list (in-place).
    
    ```python
    my_list.reverse()
    
    ```
    

### List Comprehension

A concise way to create lists using a single line of code.

- **Syntax**:
    
    ```python
    [expression for item in iterable if condition]
    
    ```
    
- **Example**:
    
    ```python
    squares = [x**2 for x in range(5)]
    # Output: [0, 1, 4, 9, 16]
    
    ```
    

### List Slicing

Extract a portion of a list using slicing syntax.

- **Syntax**:
    
    ```python
    my_list[start:end:step]
    
    ```
    
- **Examples**:
    
    ```python
    my_list = [0, 1, 2, 3, 4, 5]
    print(my_list[1:4])  # Output: [1, 2, 3]
    print(my_list[:3])  # Output: [0, 1, 2]
    print(my_list[::2])  # Output: [0, 2, 4]
    
    ```
    

### Nested List

Lists within lists, creating a multi-dimensional array.

- **Syntax**:
    
    ```python
    nested_list = [[1, 2, 3], [4, 5, 6]]
    
    ```
    
- **Accessing Elements**:
    
    ```python
    print(nested_list[0][1])  # Output: 2
    
    ```
    

### Sorting in List

Sorting a list in ascending or descending order.

- **Using `sort()`**: Sorts the list in place.
    
    ```python
    my_list.sort()  # Ascending order
    my_list.sort(reverse=True)  # Descending order
    
    ```
    
- **Using `sorted()`**: Returns a new sorted list.
    
    ```python
    sorted_list = sorted(my_list)
    
    ```
    

### Sets in Python

Sets are collections of unique, unordered elements. They are useful for operations involving membership tests and set operations like union and intersection.

- **Creating a Set**:
    
    ```python
    my_set = {1, 2, 3, 4}
    
    ```
    
- **Operations**:
    - **Union**:
        
        ```python
        set1 | set2
        
        ```
        
    - **Intersection**:
        
        ```python
        set1 & set2
        
        ```
        
    - **Difference**:
        
        ```python
        set1 - set2
        
        ```
        
    - **Symmetric Difference**:
        
        ```python
        set1 ^ set2
        
        ```
        
- **Adding and Removing Elements**:
    
    ```python
    my_set.add(5)
    my_set.remove(2)
    
    ```
    

## List Practice Problems - 4

### Practice Problem 1 - Find the largest element in an array of size `n`.

**Problem Statement**:
Given an array of size `n`, find the largest element.

**Solution**:

1. Initialize a variable to store the maximum value.
2. Traverse through the array, comparing each element with the maximum value.
3. Update the maximum value if a larger element is found.
4. Return the maximum value.

**Code**:

```python
def find_largest(arr):
    if not arr:
        return None  # Return None if the array is empty

    max_value = arr[0]
    for num in arr:
        if num > max_value:
            max_value = num
    return max_value

# Example Usage
arr = [3, 1, 4, 1, 5, 9, 2, 6, 5, 3, 5]
print(find_largest(arr))  # Output: 9

```

### Practice Problem 2 - Given an array 'ARR' of integers and a position ‘M’, reverse the array from position ‘M+1’ onwards.

**Problem Statement**:
Given an array `ARR` of integers and a position `M`, reverse the elements of the array from position `M+1` to the end.

**Solution**:

1. Split the array into two parts: before and after `M`.
2. Reverse the part after `M`.
3. Concatenate the two parts.

**Code**:

```python
def reverse_from_position(arr, M):
    if M >= len(arr) - 1:
        return arr  # No need to reverse if M is the last position or beyond

    return arr[:M+1] + arr[M+1:][::-1]

# Example Usage
arr = [1, 2, 3, 4, 5, 6]
M = 2
print(reverse_from_position(arr, M))  # Output: [1, 2, 3, 6, 5, 4]

```

### Practice Problem 3 - Given an array 'arr' containing 'n' elements, rotate this array left once by shifting all elements to the left and moving the first element to the last position.

**Problem Statement**:
Given an array `arr` of `n` elements, rotate the array left once.

**Solution**:

1. Store the first element.
2. Shift all other elements to the left by one position.
3. Place the stored element at the end of the array.

**Code**:

```python
def rotate_left_once(arr):
    if not arr:
        return arr  # Return the array as is if it's empty

    first_element = arr.pop(0)
    arr.append(first_element)
    return arr

# Example Usage
arr = [1, 2, 3, 4, 5]
print(rotate_left_once(arr))  # Output: [2, 3, 4, 5, 1]

```

### Practice Problem 4 - Given an array ‘a’ of ‘n’ non-negative integers, check whether the array is sorted in non-decreasing order. Return 1 if the array is sorted, else return 0.

**Problem Statement**:
Check if an array is sorted in non-decreasing order.

**Solution**:

1. Traverse through the array and compare each element with the next element.
2. If any element is greater than the next, return 0.
3. If no such elements are found, return 1.

**Code**:

```python
def is_sorted(arr):
    for i in range(len(arr) - 1):
        if arr[i] > arr[i + 1]:
            return 0
    return 1

# Example Usage
arr = [1, 2, 2, 4, 5]
print(is_sorted(arr))  # Output: 1

arr = [1, 3, 2, 4, 5]
print(is_sorted(arr))  # Output: 0
```

## Tuple - 4

### What is Tuples in Python

- **Definition**: A tuple is an immutable sequence type in Python. It is similar to a list but cannot be modified after creation.
- **Syntax**: Tuples are created by placing comma-separated values within parentheses `()`.

**Example**:

```python
t = (1, 2, 3)

```

### Difference between List and Tuples

1. **Mutability**:
    - **List**: Mutable (can be modified after creation).
    - **Tuple**: Immutable (cannot be modified once created).
2. **Syntax**:
    - **List**: Created with square brackets `[]`.
    - **Tuple**: Created with parentheses `()`.
3. **Performance**:
    - **List**: Generally slower than tuples due to the overhead of mutation.
    - **Tuple**: Faster and more memory-efficient since they are immutable.
4. **Usage**:
    - **List**: Used when you need a sequence that may need to be changed.
    - **Tuple**: Used when you need a fixed sequence, often used as keys in dictionaries or elements of sets.

**Example**:

```python
# List
lst = [1, 2, 3]
lst[0] = 10  # Valid

# Tuple
tup = (1, 2, 3)
tup[0] = 10  # Invalid, raises TypeError

```

### Tuple Methods

- **`.count(value)`**: Returns the number of occurrences of a value.
- **`.index(value)`**: Returns the index of the first occurrence of a value.

**Example**:

```python
t = (1, 2, 2, 3)

# Count occurrences of 2
print(t.count(2))  # Output: 2

# Index of first occurrence of 2
print(t.index(2))  # Output: 1

```

### Practice Problem 1 - Sorting Tuples

**Problem Statement**:
Given an array of tuples `ARR` of length `N`, where all tuples have length `L`, sort the tuples in non-decreasing order based on their last element. If the last elements are equal, maintain their original order.

**Solution**:

1. Use Python’s `sorted()` function with a custom key.
2. The key should be the last element of each tuple.

**Code**:

```python
def sort_tuples_by_last_element(arr):
    return sorted(arr, key=lambda x: x[-1])

# Example Usage
arr = [(1, 2, 3), (4, 5, 2), (7, 8, 3), (10, 11, 2)]
sorted_arr = sort_tuples_by_last_element(arr)
print(sorted_arr)
# Output: [(4, 5, 2), (10, 11, 2), (1, 2, 3), (7, 8, 3)]

```

The provided solution maintains the original order of tuples with equal last elements by using Python’s stable sort algorithm.

## Dictionary - 6

### What is Dictionary in Python

- **Definition**: A dictionary is an unordered collection of key-value pairs. Each key must be unique, and the keys are immutable.
- **Syntax**: Dictionaries are created using curly braces `{}` with key-value pairs separated by colons.

**Example**:

```python
d = {"name": "Alice", "age": 25, "city": "New York"}

```

### Dictionary Methods

- **`.clear()`**: Removes all items from the dictionary.
- **`.copy()`**: Returns a shallow copy of the dictionary.
- **`.fromkeys(seq, value)`**: Creates a new dictionary with keys from `seq` and values set to `value`.
- **`.get(key, default)`**: Returns the value for the specified key, or `default` if the key does not exist.
- **`.items()`**: Returns a view object of dictionary's key-value pairs.
- **`.keys()`**: Returns a view object of dictionary's keys.
- **`.pop(key, default)`**: Removes the specified key and returns the corresponding value. If the key is not found, `default` is returned if provided.
- **`.popitem()`**: Removes and returns the last inserted key-value pair.
- **`.setdefault(key, default)`**: Returns the value of the key if it exists, otherwise inserts the key with `default` value.
- **`.update(other)`**: Updates the dictionary with key-value pairs from `other`, overwriting existing keys.
- **`.values()`**: Returns a view object of dictionary's values.

**Example**:

```python
d = {"name": "Alice", "age": 25}
print(d.get("name"))       # Output: Alice
print(d.keys())            # Output: dict_keys(['name', 'age'])
print(d.values())          # Output: dict_values(['Alice', 25])

```

### Difference between List, Tuple, and Dictionary

1. **List**:
    - **Syntax**: `[1, 2, 3]`
    - **Mutability**: Mutable
    - **Indexing**: Indexed by integers
    - **Use Case**: Ordered collections of items
2. **Tuple**:
    - **Syntax**: `(1, 2, 3)`
    - **Mutability**: Immutable
    - **Indexing**: Indexed by integers
    - **Use Case**: Fixed collections of items, often used as keys in dictionaries
3. **Dictionary**:
    - **Syntax**: `{"key1": "value1", "key2": "value2"}`
    - **Mutability**: Mutable
    - **Indexing**: Indexed by immutable keys (e.g., strings, numbers)
    - **Use Case**: Mapping of unique keys to values

### Sorting Dictionary

- Dictionaries themselves are unordered. To sort by keys or values, you need to convert the dictionary to a list of tuples.

**Example**:

```python
d = {"name": "Alice", "age": 25, "city": "New York"}

# Sort by keys
sorted_by_keys = dict(sorted(d.items()))
print(sorted_by_keys)  # Output: {'age': 25, 'city': 'New York', 'name': 'Alice'}

# Sort by values
sorted_by_values = dict(sorted(d.items(), key=lambda item: item[1]))
print(sorted_by_values)  # Output: {'name': 'Alice', 'age': 25, 'city': 'New York'}

```

### Dictionary Comprehension

- **Definition**: A concise way to create dictionaries using an expression within `{}`.

**Syntax**:

```python
{key_expr: value_expr for item in iterable}

```

**Example**:

```python
# Creating a dictionary of squares
squares = {x: x**2 for x in range(5)}
print(squares)  # Output: {0: 0, 1: 1, 2: 4, 3: 9, 4: 16}

```

### Practice Problem 1

**Problem Statement**:
Given an array of words `WORDS` and a string `ORDER` representing the alien alphabet order, check if the words are sorted lexicographically according to this alien language.

**Solution Approach**:

1. Create a dictionary that maps each character in `ORDER` to its position.
2. Convert each word into a list of its positions using the dictionary.
3. Check if the list of positions for each word is sorted.

**Code**:

```python
def is_sorted_lexicographically(words, order):
    order_dict = {char: index for index, char in enumerate(order)}

    def convert(word):
        return [order_dict[char] for char in word]

    for i in range(len(words) - 1):
        if convert(words[i]) > convert(words[i + 1]):
            return "NO"

    return "YES"

# Example Usage
words = ["word", "world", "row"]
order = "worldabcefghijkmnpqstuvxyz"
print(is_sorted_lexicographically(words, order))  # Output: NO

```

This code ensures that the words are checked according to the custom alphabetical order provided.

## String - 7

### What is String in Python

- **Definition**: A string is a sequence of characters enclosed in quotes. Python supports single quotes (`'`), double quotes (`"`), and triple quotes (`'''` or `"""`) for strings.
- **Syntax**:
    
    ```python
    single_quote = 'Hello'
    double_quote = "World"
    triple_quote = '''Python Strings'''
    
    ```
    

**Example**:

```python
string1 = 'Hello'
string2 = "World"
string3 = """Python Strings"""

```

### String Manipulation

- **Concatenation**: Combining two or more strings using `+`.
    
    ```python
    str1 = "Hello"
    str2 = "World"
    result = str1 + " " + str2  # Output: 'Hello World'
    
    ```
    
- **Repetition**: Repeating a string using ``.
    
    ```python
    str1 = "Hello"
    result = str1 * 3  # Output: 'HelloHelloHello'
    
    ```
    
- **Length**: Getting the length of a string using `len()`.
    
    ```python
    length = len("Hello")  # Output: 5
    
    ```
    

### F-String in Python

- **Definition**: Formatted string literals, or f-strings, allow for embedding expressions inside string literals using `{}`.
- **Syntax**: Prefix the string with `f` or `F`.

**Example**:

```python
name = "Alice"
age = 25
greeting = f"Hello, {name}. You are {age} years old."  # Output: 'Hello, Alice. You are 25 years old.'

```

### Slicing in String

- **Definition**: Extracting a part of a string using slice notation `[start:stop:step]`.
- **Syntax**:
    
    ```python
    string[start:stop:step]
    
    ```
    

**Examples**:

```python
text = "Python"
slice1 = text[1:4]   # Output: 'yth'
slice2 = text[:4]    # Output: 'Pyth'
slice3 = text[2:]    # Output: 'thon'
slice4 = text[::2]   # Output: 'Pto'

```

### Split in String

- **Definition**: Dividing a string into a list of substrings based on a delimiter using `.split()`.
- **Syntax**: `string.split(separator, maxsplit)`

**Example**:

```python
text = "apple,banana,cherry"
fruits = text.split(",")  # Output: ['apple', 'banana', 'cherry']

```

- **Without Separator**: Splits on any whitespace.
    
    ```python
    text = "Python is awesome"
    words = text.split()  # Output: ['Python', 'is', 'awesome']
    
    ```
    

### Join in String

- **Definition**: Concatenating a list of strings into a single string with a specified separator using `.join()`.
- **Syntax**: `separator.join(iterable)`

**Example**:

```python
fruits = ['apple', 'banana', 'cherry']
result = ", ".join(fruits)  # Output: 'apple, banana, cherry'

```

### String Methods

- **`.lower()`**: Converts all characters to lowercase.
    
    ```python
    text = "HELLO"
    lower_text = text.lower()  # Output: 'hello'
    
    ```
    
- **`.upper()`**: Converts all characters to uppercase.
    
    ```python
    text = "hello"
    upper_text = text.upper()  # Output: 'HELLO'
    
    ```
    
- **`.title()`**: Capitalizes the first letter of each word.
    
    ```python
    text = "hello world"
    title_text = text.title()  # Output: 'Hello World'
    
    ```
    
- **`.strip()`**: Removes leading and trailing whitespace.
    
    ```python
    text = "  hello  "
    stripped_text = text.strip()  # Output: 'hello'
    
    ```
    
- **`.replace(old, new)`**: Replaces occurrences of `old` with `new`.
    
    ```python
    text = "hello world"
    replaced_text = text.replace("world", "Python")  # Output: 'hello Python'
    
    ```
    
- **`.find(substring)`**: Finds the index of the first occurrence of `substring`.
    
    ```python
    text = "hello world"
    index = text.find("world")  # Output: 6
    
    ```
    
- **`.startswith(prefix)`**: Checks if the string starts with `prefix`.
    
    ```python
    text = "hello world"
    starts_with_hello = text.startswith("hello")  # Output: True
    
    ```
    
- **`.endswith(suffix)`**: Checks if the string ends with `suffix`.
    
    ```python
    text = "hello world"
    ends_with_world = text.endswith("world")  # Output: True
    
    ```
    

## String Practice Problems - 3

### Practice Problem 1

**Problem**: Reverse the words in a given string `str`, ensuring that there is only one space between words and no leading or trailing spaces.

**Solution**:

```python
def reverse_words(s: str) -> str:
    # Split the string into words
    words = s.split()
    # Reverse the list of words
    reversed_words = words[::-1]
    # Join the reversed words with a single space
    return ' '.join(reversed_words)

# Example
input_str = "Hello world from Python"
output_str = reverse_words(input_str)  # Output: "Python from world Hello"
print(output_str)

```

### Practice Problem 2

**Problem**: Convert the first letter of each word in a given string `STR` to uppercase, keeping other letters in their original case and ensuring that words are separated by a single space.

**Solution**:

```python
def capitalize_words(s: str) -> str:
    # Split the string into words
    words = s.split()
    # Capitalize the first letter of each word and join with a space
    capitalized_words = [word.capitalize() for word in words]
    return ' '.join(capitalized_words)

# Example
input_str = "hello world from python"
output_str = capitalize_words(input_str)  # Output: "Hello World From Python"
print(output_str)

```

### Practice Problem 3

**Problem**: Given a string `str` of even length, determine if the two substrings obtained by splitting the string in the middle contain an equal number of vowels.

**Solution**:

```python
def count_vowels(s: str) -> int:
    return sum(1 for char in s if char.lower() in 'aeiou')

def equal_vowel_substrings(s: str) -> bool:
    n = len(s)
    if n % 2 != 0:
        raise ValueError("String length must be even.")
    mid = n // 2
    left_substring = s[:mid]
    right_substring = s[mid:]
    return count_vowels(left_substring) == count_vowels(right_substring)

# Example
input_str = "abcdabcdef"
result = equal_vowel_substrings(input_str)  # Output: True
print(result)
```

## Linked List - 5

### What is a Linked List in Python

A linked list is a data structure consisting of nodes where each node contains a value and a reference (or link) to the next node in the sequence. Unlike arrays, linked lists do not store elements in contiguous memory locations. They are dynamically sized and allow efficient insertion and deletion of elements.

**Basic Structure**:

- **Node**: Contains `value` and `next` reference.
- **Head**: The first node in the linked list.
- **Tail**: The last node in the linked list (usually points to `None`).

**Node Class Definition**:

```python
class Node:
    def __init__(self, value=0, next=None):
        self.value = value
        self.next = next

```

### Practice Problems

**Practice Problem 1**: Given a singly linked list of `N` positive integers, insert a node with value `VAL` at position `POS`. Return the modified linked list.

**Solution**:

```python
class Node:
    def __init__(self, value=0, next=None):
        self.value = value
        self.next = next

def insert_at_position(head: Node, val: int, pos: int) -> Node:
    new_node = Node(val)
    if pos == 0:
        new_node.next = head
        return new_node

    current = head
    for _ in range(pos - 1):
        if current is None:
            raise IndexError("Position out of bounds")
        current = current.next

    new_node.next = current.next
    current.next = new_node
    return head

# Example
# Create a linked list 1 -> 2 -> 3
head = Node(1, Node(2, Node(3)))
# Insert 4 at position 1
new_head = insert_at_position(head, 4, 1)
# Result: 1 -> 4 -> 2 -> 3

```

**Practice Problem 2**: Given a singly linked list and a reference to a node to be deleted, remove that node from the list. The reference to the head of the list is not provided, and the node to be deleted is not the tail node.

**Solution**:

```python
def delete_node(node: Node) -> None:
    if node is None or node.next is None:
        raise ValueError("Node to delete is invalid or is the tail node")

    next_node = node.next
    node.value = next_node.value
    node.next = next_node.next

# Example
# Create a linked list 1 -> 2 -> 3 -> 4
head = Node(1, Node(2, Node(3, Node(4))))
node_to_delete = head.next.next  # Node with value 3
delete_node(node_to_delete)
# Result: 1 -> 2 -> 4

```

**Practice Problem 3**: Given a singly linked list and an integer value `K`, determine if there exists a node in the linked list with the value `K`. Return `1` if such a node exists, otherwise return `0`.

**Solution**:

```python
def find_value(head: Node, k: int) -> int:
    current = head
    while current:
        if current.value == k:
            return 1
        current = current.next
    return 0

# Example
# Create a linked list 1 -> 2 -> 3
head = Node(1, Node(2, Node(3)))
result = find_value(head, 2)  # Output: 1

```

**Practice Problem 4**: Given a linked list with a cycle, find and return the Nth node from the start of the cycle, counting from the cycle start towards the head. Return `None` if no such node exists.

**Solution**:

```python
def detect_cycle(head: Node) -> Node:
    slow = fast = head
    while fast and fast.next:
        slow = slow.next
        fast = fast.next.next
        if slow == fast:
            break
    else:
        return None

    # Find the start of the cycle
    slow = head
    while slow != fast:
        slow = slow.next
        fast = fast.next

    return slow

def find_nth_node_from_cycle_start(head: Node, n: int) -> Node:
    cycle_start = detect_cycle(head)
    if not cycle_start:
        return None

    current = cycle_start
    for _ in range(n):
        if not current.next:
            return None
        current = current.next
    return current

# Example
# Create a linked list with a cycle: 1 -> 2 -> 3 -> 4 -> 5 -> 2 (cycle starts at node with value 2)
head = Node(1, Node(2, Node(3, Node(4, Node(5)))))
head.next.next.next.next.next = head.next
result = find_nth_node_from_cycle_start(head, 2)  # Output: Node with value 4

```

# OOPS Concept

## Introduction to OOPS - 8

### OOPS and Its Characteristics

Object-Oriented Programming (OOPS) is a programming paradigm based on the concept of objects, which can contain data and methods. It aims to increase the modularity and reusability of code. The core characteristics of OOPS include:

1. **Encapsulation**: Bundling data (attributes) and methods (functions) into a single unit or class.
2. **Inheritance**: Mechanism to derive new classes from existing ones, inheriting attributes and methods.
3. **Polymorphism**: Ability to define methods in multiple forms, allowing objects to be treated as instances of their parent class.
4. **Abstraction**: Hiding complex implementation details and showing only the necessary features of an object.

### Features of OOPS

1. **Encapsulation**: Encapsulation is the process of wrapping data and methods into a single unit, typically a class. It restricts direct access to some of an object's components and can prevent the accidental modification of data.
2. **Inheritance**: Allows a new class (subclass) to inherit attributes and methods from an existing class (superclass). This promotes code reusability and can establish a hierarchical relationship.
3. **Polymorphism**: Refers to the ability to present the same interface for different data types. It can be achieved through method overriding (runtime polymorphism) and method overloading (compile-time polymorphism).
4. **Abstraction**: The concept of abstraction is to provide only essential information to the user and hide the implementation details. Abstract classes and interfaces are used to achieve abstraction.

### Application of OOPS

OOPS is widely used in software development to model real-world scenarios, manage complex codebases, and improve code maintenance and scalability. Common applications include:

- **Software Development**: Designing software systems that are modular and reusable.
- **Game Development**: Modeling game entities such as characters and items.
- **GUI Design**: Building graphical user interfaces with interactive components.
- **Simulation Systems**: Creating simulations of real-world processes or systems.

### Aggregation and Composition

Both are forms of association between classes but differ in terms of their relationship strength.

- **Aggregation**: Represents a "has-a" relationship where the child can exist independently of the parent. For example, a `Library` class that aggregates `Book` objects. If the `Library` is deleted, `Books` can still exist.
    
    ```python
    class Book:
        def __init__(self, title):
            self.title = title
    
    class Library:
        def __init__(self):
            self.books = []
    
        def add_book(self, book):
            self.books.append(book)
    
    ```
    
- **Composition**: Represents a stronger "has-a" relationship where the child cannot exist independently of the parent. For example, a `House` class that contains `Room` objects. If the `House` is deleted, `Rooms` are also deleted.
    
    ```python
    class Room:
        def __init__(self, name):
            self.name = name
    
    class House:
        def __init__(self):
            self.rooms = [Room("Living Room"), Room("Bedroom")]
    
    ```
    

### Classes and Objects

- **Class**: A blueprint for creating objects. It defines a set of attributes and methods that the objects created from the class can use.
    
    ```python
    class Dog:
        def __init__(self, name, age):
            self.name = name
            self.age = age
    
        def bark(self):
            return f"{self.name} barks!"
    
    ```
    
- **Object**: An instance of a class. It contains real data and can access the methods defined in the class.
    
    ```python
    my_dog = Dog("Buddy", 3)
    print(my_dog.bark())  # Output: Buddy barks!
    
    ```
    

### `__init__` and `self` Method in Python

- **`__init__` Method**: A special method called a constructor that initializes a new object's attributes when an instance is created.
    
    ```python
    class Person:
        def __init__(self, name, age):
            self.name = name
            self.age = age
    
    ```
    
- **`self`**: Refers to the instance of the class. It is used to access attributes and methods of the class within its methods.
    
    ```python
    def greet(self):
        return f"Hello, my name is {self.name}"
    
    ```
    

### Mutable and Immutable Objects in Python

- **Mutable Objects**: Objects whose state or value can be changed after they are created. Examples include lists, dictionaries, and sets.
    
    ```python
    my_list = [1, 2, 3]
    my_list.append(4)  # The list is modified
    
    ```
    
- **Immutable Objects**: Objects whose state or value cannot be changed once they are created. Examples include strings, tuples, and integers.
    
    ```python
    my_string = "hello"
    my_string = my_string.upper()  # Creates a new string
    
    ```
    

### Class Attributes and Instance Attributes

- **Class Attributes**: Attributes shared across all instances of a class. They are defined within the class but outside any methods.
    
    ```python
    class Car:
        wheels = 4  # Class attribute
    
    ```
    
- **Instance Attributes**: Attributes specific to each instance of a class. They are defined within the `__init__` method.
    
    ```python
    class Car:
        def __init__(self, color):
            self.color = color  # Instance attribute
    ```
    

## Encapsulation - 5

### What is Encapsulation

**Encapsulation** is one of the fundamental principles of Object-Oriented Programming (OOP). It involves bundling data (attributes) and methods (functions) that operate on the data into a single unit, typically a class. Encapsulation helps to:

- **Protect the integrity of the data**: By restricting direct access to some of the object's components.
- **Hide internal implementation**: Users interact with the object through a public interface, while the internal workings are hidden.
- **Improve maintainability**: Changes to the internal implementation can be made without affecting the external interface.

Example:

```python
class Car:
    def __init__(self, make, model):
        self.make = make
        self.__model = model  # Private attribute

    def get_model(self):
        return self.__model

    def set_model(self, model):
        self.__model = model

```

### Access Modifiers

Access modifiers in Python are used to control the visibility and accessibility of class attributes and methods. Python uses naming conventions rather than explicit access modifiers.

- **Public**: Attributes and methods that are accessible from outside the class.
    
    ```python
    class Car:
        def __init__(self, make):
            self.make = make  # Public attribute
    
    ```
    
- **Protected**: Attributes and methods that are intended to be accessed only within the class and its subclasses. Indicated by a single underscore `_`.
    
    ```python
    class Car:
        def __init__(self, make):
            self._make = make  # Protected attribute
    
    ```
    
- **Private**: Attributes and methods that are not accessible from outside the class. Indicated by a double underscore `__`.
    
    ```python
    class Car:
        def __init__(self, make):
            self.__make = make  # Private attribute
    
    ```
    

### Getter and Setter Methods

**Getter Methods**: Used to retrieve the value of a private attribute. They provide read-only access.

**Setter Methods**: Used to modify the value of a private attribute. They provide controlled write access.

Example:

```python
class Car:
    def __init__(self, make, model):
        self.__make = make
        self.__model = model

    def get_make(self):
        return self.__make

    def set_make(self, make):
        self.__make = make

    def get_model(self):
        return self.__model

    def set_model(self, model):
        self.__model = model

```

### Property Decorators

**Property Decorators** (`@property`) provide a way to define methods that act as attributes. They simplify the usage of getter and setter methods by allowing you to access them like attributes.

- **Getter Method**: Define a method that retrieves the value.
- **Setter Method**: Define a method that sets the value.
- **Deleter Method**: Optionally define a method to delete the attribute.

Example:

```python
class Car:
    def __init__(self, make, model):
        self.__make = make
        self.__model = model

    @property
    def make(self):
        return self.__make

    @make.setter
    def make(self, make):
        self.__make = make

    @property
    def model(self):
        return self.__model

    @model.setter
    def model(self, model):
        self.__model = model

```

### Class Method, Static Method, and Instance Method

- **Instance Method**: A method that operates on an instance of the class. It can access and modify instance attributes using `self`.
    
    ```python
    class Car:
        def __init__(self, make):
            self.make = make
    
        def display(self):
            print(self.make)
    
    ```
    
- **Class Method**: A method that operates on the class itself rather than an instance. It is defined using the `@classmethod` decorator and takes `cls` as the first parameter.
    
    ```python
    class Car:
        num_wheels = 4
    
        @classmethod
        def wheels(cls):
            return cls.num_wheels
    
    ```
    
- **Static Method**: A method that does not access or modify the class or instance. It is defined using the `@staticmethod` decorator and does not take `self` or `cls` as a parameter.
    
    ```python
    class Car:
        @staticmethod
        def is_motor_vehicle():
            return True
    ```
    

## Abstraction - 3

### What is Abstraction

**Abstraction** in object-oriented programming (OOP) is the concept of hiding complex implementation details and showing only the essential features of an object. It helps in focusing on what an object does instead of how it does it. Abstraction:

- **Simplifies complex systems**: By breaking them into more manageable parts.
- **Provides a clear interface**: Users interact with the object through a simplified and relevant interface.
- **Reduces code complexity**: By hiding implementation details and providing a simpler view of the object.

Example:

```python
from abc import ABC, abstractmethod

class Shape(ABC):
    @abstractmethod
    def area(self):
        pass

class Circle(Shape):
    def __init__(self, radius):
        self.radius = radius

    def area(self):
        return 3.14 * self.radius * self.radius

```

### Abstract Classes

**Abstract Classes** are classes that cannot be instantiated and are meant to be subclassed. They may contain one or more abstract methods. Abstract methods are defined in the abstract class but are meant to be implemented by subclasses. In Python, abstract classes are created using the `ABC` (Abstract Base Class) module and the `@abstractmethod` decorator.

- **Abstract Method**: A method declared in the abstract class with no implementation. Subclasses must provide an implementation for these methods.

Example:

```python
from abc import ABC, abstractmethod

class Animal(ABC):
    @abstractmethod
    def make_sound(self):
        pass

class Dog(Animal):
    def make_sound(self):
        return "Bark"

# animal = Animal()  # This will raise an error
dog = Dog()
print(dog.make_sound())  # Output: Bark

```

### Interface

**Interfaces** in Python are implemented using abstract classes. An interface defines a contract that classes must adhere to, specifying the methods that must be implemented but not their behavior. Unlike abstract classes, interfaces focus solely on the method signatures, not the data or state.

- **Interface Implementation**: A class that implements an interface must provide concrete implementations for all methods defined in the interface.

Python does not have a specific `interface` keyword like some other languages (e.g., Java). Instead, it uses abstract classes to achieve similar functionality.

Example:

```python
from abc import ABC, abstractmethod

class Printable(ABC):
    @abstractmethod
    def print(self):
        pass

class Document(Printable):
    def print(self):
        print("Printing document")

doc = Document()
doc.print()  # Output: Printing document
```

## Inheritance - 5

### What is Inheritance

**Inheritance** is an OOP concept that allows a class (child or subclass) to inherit properties and methods from another class (parent or superclass). It promotes code reuse and establishes a natural hierarchy between classes. The child class can add new features or override existing ones from the parent class.

Benefits:

- **Code Reusability**: Reuse existing code in a new class.
- **Extensibility**: Extend existing functionalities with new features.
- **Hierarchy**: Establish a natural relationship between classes.

Example:

```python
class Animal:
    def eat(self):
        print("This animal eats food.")

class Dog(Animal):
    def bark(self):
        print("Woof!")

dog = Dog()
dog.eat()  # Output: This animal eats food.
dog.bark()  # Output: Woof!

```

### Types of Inheritance

1. **Single Inheritance**: A class inherits from one superclass.
    
    ```python
    class Parent:
        pass
    
    class Child(Parent):
        pass
    
    ```
    
2. **Multiple Inheritance**: A class inherits from multiple superclasses.
    
    ```python
    class Father:
        pass
    
    class Mother:
        pass
    
    class Child(Father, Mother):
        pass
    
    ```
    
3. **Multilevel Inheritance**: A class inherits from another class which itself inherits from a superclass.
    
    ```python
    class Grandparent:
        pass
    
    class Parent(Grandparent):
        pass
    
    class Child(Parent):
        pass
    
    ```
    
4. **Hierarchical Inheritance**: Multiple classes inherit from a single superclass.
    
    ```python
    class Parent:
        pass
    
    class Child1(Parent):
        pass
    
    class Child2(Parent):
        pass
    
    ```
    
5. **Hybrid Inheritance**: A combination of two or more types of inheritance.
    
    ```python
    class A:
        pass
    
    class B(A):
        pass
    
    class C(A):
        pass
    
    class D(B, C):
        pass
    
    ```
    

### Constructor

**Constructors** are special methods used to initialize new objects. In Python, the `__init__` method is used as a constructor. When a child class inherits from a parent class, it can call the parent's constructor using `super()`.

Example:

```python
class Parent:
    def __init__(self):
        print("Parent Constructor")

class Child(Parent):
    def __init__(self):
        super().__init__()
        print("Child Constructor")

child = Child()
# Output:
# Parent Constructor
# Child Constructor

```

### Super Method

The `super()` method is used to call methods from the parent class. It allows the child class to access methods and properties from its parent class, often used within the child class's constructor to initialize inherited attributes.

Example:

```python
class Parent:
    def __init__(self):
        print("Parent Constructor")

    def show(self):
        print("Parent Method")

class Child(Parent):
    def __init__(self):
        super().__init__()
        print("Child Constructor")

    def show(self):
        super().show()
        print("Child Method")

child = Child()
child.show()
# Output:
# Parent Constructor
# Child Constructor
# Parent Method
# Child Method

```

### Dunder or Magic Methods

**Dunder (Double Underscore) Methods** are special methods with double underscores before and after their names. They allow customization of built-in operations. Common dunder methods include:

- `__init__`: Constructor method.
- `__str__`: Defines the string representation of an object.
- `__repr__`: Defines a formal string representation of an object.
- `__len__`: Returns the length of the object.
- `__add__`: Defines behavior for the addition operator (`+`).
- `__getitem__`: Defines behavior for indexing (`[]`).

Example:

```python
class Person:
    def __init__(self, name):
        self.name = name

    def __str__(self):
        return f"Person(name={self.name})"

    def __repr__(self):
        return f"Person('{self.name}')"

    def __len__(self):
        return len(self.name)

    def __add__(self, other):
        return self.name + " " + other.name

p1 = Person("Alice")
p2 = Person("Bob")

print(str(p1))  # Output: Person(name=Alice)
print(repr(p1))  # Output: Person('Alice')
print(len(p1))  # Output: 5
print(p1 + p2)  # Output: Alice Bob
```

## Polymorphism - 5

### What is Polymorphism

**Polymorphism** is an OOP concept that allows objects of different classes to be treated as objects of a common superclass. It means "many shapes" and refers to the ability of different objects to respond, each in their own way, to the same method call. Polymorphism enhances flexibility and maintainability by allowing the same interface to be used for different underlying data types.

Benefits:

- **Flexibility**: Write more generic and reusable code.
- **Maintainability**: Modify or extend code with minimal changes.
- **Readability**: Improve code clarity by using common interfaces.

Example:

```python
class Animal:
    def speak(self):
        pass

class Dog(Animal):
    def speak(self):
        return "Woof!"

class Cat(Animal):
    def speak(self):
        return "Meow!"

def make_animal_speak(animal):
    print(animal.speak())

dog = Dog()
cat = Cat()

make_animal_speak(dog)  # Output: Woof!
make_animal_speak(cat)  # Output: Meow!

```

### Method Overloading and Method Overriding

**Method Overloading**:
Method overloading allows a class to have more than one method with the same name but different parameters. Python does not support method overloading directly, but it can be implemented by default arguments or variable-length arguments.

Example:

```python
class Example:
    def greet(self, name=None):
        if name is not None:
            return f"Hello, {name}!"
        return "Hello!"

```

**Method Overriding**:
Method overriding allows a subclass to provide a specific implementation of a method that is already defined in its superclass. This is a way to achieve polymorphism.

Example:

```python
class Parent:
    def greet(self):
        return "Hello from Parent"

class Child(Parent):
    def greet(self):
        return "Hello from Child"

p = Parent()
c = Child()

print(p.greet())  # Output: Hello from Parent
print(c.greet())  # Output: Hello from Child

```

### Duck Typing

**Duck Typing** is a concept where the type or class of an object is determined by its behavior (methods and properties) rather than its explicit inheritance or implementation. The phrase "If it looks like a duck and quacks like a duck, it probably is a duck" summarizes this concept.

Example:

```python
class Bird:
    def fly(self):
        print("Bird flying")

class Airplane:
    def fly(self):
        print("Airplane flying")

def make_it_fly(thing):
    thing.fly()

bird = Bird()
airplane = Airplane()

make_it_fly(bird)      # Output: Bird flying
make_it_fly(airplane)  # Output: Airplane flying

```

### Operator Overloading

**Operator Overloading** allows the same operator to have different meanings based on the context or types of its operands. It is implemented by defining special methods (dunder methods) in a class.

Example:

```python
class Vector:
    def __init__(self, x, y):
        self.x = x
        self.y = y

    def __add__(self, other):
        return Vector(self.x + other.x, self.y + other.y)

    def __repr__(self):
        return f"Vector({self.x}, {self.y})"

v1 = Vector(1, 2)
v2 = Vector(3, 4)
v3 = v1 + v2

print(v3)  # Output: Vector(4, 6)

```

### Dynamic Typing

**Dynamic Typing** refers to the ability of a programming language to determine the type of a variable at runtime, rather than at compile time. This allows for more flexible and reusable code, as the type of an object can be checked and handled dynamically during execution.

Example:

```python
def add(a, b):
    return a + b

print(add(5, 10))       # Output: 15 (integers)
print(add("Hello, ", "World!"))  # Output: Hello, World! (strings)
```

## Practice Problems - 4

### Practice Problem 1 - Rectangle

Design a class `Rectangle` to compute and return the area of the rectangle.

```python
class Rectangle:
    def __init__(self, length: float, breadth: float):
        self.length = length
        self.breadth = breadth

    def getArea(self) -> float:
        return self.length * self.breadth

# Example usage:
rect = Rectangle(5, 3)
print("Area of Rectangle:", rect.getArea())

```

### Practice Problem 2 - Car and RaceCar

Design a `Car` class and a `RaceCar` class inheriting from `Car`.

```python
class Car:
    def __init__(self, noOfGear: int, color: str):
        self.noOfGear = noOfGear
        self.color = color

    def printCarInfo(self):
        print(f"Number of Gears: {self.noOfGear}")
        print(f"Color: {self.color}")

class RaceCar(Car):
    def __init__(self, noOfGear: int, color: str, maxSpeed: int):
        super().__init__(noOfGear, color)
        self.maxSpeed = maxSpeed

    def printRaceCarInfo(self):
        self.printCarInfo()
        print(f"Max Speed: {self.maxSpeed}")

# Example usage:
race_car = RaceCar(6, "Red", 200)
race_car.printRaceCarInfo()

```

### Practice Problem 3 - ComplexNumber

Create a `ComplexNumber` class with methods for addition, multiplication, and printing.

```python
class ComplexNumber:
    def __init__(self, R: int, I: int):
        self.R = R
        self.I = I

    def plus(self, C2):
        return ComplexNumber(self.R + C2.R, self.I + C2.I)

    def multiply(self, C2):
        real = self.R * C2.R - self.I * C2.I
        imag = self.R * C2.I + self.I * C2.R
        return ComplexNumber(real, imag)

    def print(self):
        if self.I >= 0:
            print(f"{self.R} + {self.I}i")
        else:
            print(f"{self.R} - {-self.I}i")

# Example usage:
c1 = ComplexNumber(1, 2)
c2 = ComplexNumber(3, 4)

result_add = c1.plus(c2)
result_mul = c1.multiply(c2)

print("Addition Result:")
result_add.print()

print("Multiplication Result:")
result_mul.print()

```

### Practice Problem 4 - Polynomial Multiplication

Multiply two polynomials given by their coefficients in arrays `A` and `B`.

```python
def multiply_polynomials(A, B):
    # Resultant polynomial degree
    m, n = len(A), len(B)
    result = [0] * (m + n - 1)

    for i in range(m):
        for j in range(n):
            result[i + j] += A[i] * B[j]

    return result

# Example usage:
A = [1, 2, 3]
B = [3, 2, 1]

result = multiply_polynomials(A, B)
print("Resultant Polynomial Coefficients:", result)

```

These solutions cover the creation and use of classes in Python, including inheritance, operator overloading, and polynomial operations.

# DSA in Python

## Arrays - 27

### Arrays in Python

**Introduction:**

Arrays are a fundamental data structure used to store a collection of elements, typically of the same data type. In Python, arrays are commonly implemented using lists, which provide dynamic sizing and can hold elements of different types. Arrays are essential for various operations, including sorting, searching, and manipulating data efficiently.

**Important Points:**

- **Fixed Size:** In traditional languages like C or Java, arrays have a fixed size once declared. In Python, lists are dynamic and can grow or shrink as needed.
- **Indexing:** Elements in an array (or list) are accessed via zero-based indexing.
- **Operations:** Common operations include traversal, insertion, deletion, searching, and sorting.
- **Time Complexity:** Operations on arrays often depend on the complexity of algorithms used, such as O(1) for access, O(n) for search and insertion, and O(n^2) for some sorting algorithms.

Arrays are the foundation for more complex data structures and algorithms, making understanding their basics crucial for tackling various problems in programming and data analysis.

### 1. Second Largest Element

```python
def second_largest(arr):
    first, second = float('-inf'), float('-inf')
    for num in arr:
        if num > first:
            first, second = num, first
        elif first > num > second:
            second = num
    return second if second != float('-inf') else None

```

**Example Usage:**

```python
arr = [10, 5, 8, 12]
print(second_largest(arr))  # Output: 10

```

### 2. Rotate an Array by K

```python
def rotate_array(arr, k):
    k %= len(arr)  # Handle cases where k > len(arr)
    return arr[-k:] + arr[:-k]

```

**Example Usage:**

```python
arr = [1, 2, 3, 4, 5]
print(rotate_array(arr, 2))  # Output: [4, 5, 1, 2, 3]

```

### 3. Non-Decreasing Array

```python
def check_non_decreasing(arr):
    modified = False
    for i in range(1, len(arr)):
        if arr[i] < arr[i - 1]:
            if modified:
                return False
            modified = True
            if i - 2 < 0 or arr[i] >= arr[i - 2]:
                arr[i - 1] = arr[i]
            else:
                arr[i] = arr[i - 1]
    return True

```

**Example Usage:**

```python
arr = [4, 2, 3]
print(check_non_decreasing(arr))  # Output: True

```

### 4. Equilibrium Index

```python
def equilibrium_index(arr):
    total_sum = sum(arr)
    left_sum = 0
    for i, num in enumerate(arr):
        if left_sum == (total_sum - left_sum - num):
            return i
        left_sum += num
    return -1

```

**Example Usage:**

```python
arr = [1, 2, 3, 4, 3, 2, 1]
print(equilibrium_index(arr))  # Output: 3

```

### 5. First Missing Positive

```python
def first_missing_positive(arr):
    arr = set(arr)
    i = 1
    while i in arr:
        i += 1
    return i

```

**Example Usage:**

```python
arr = [3, 4, -1, 1]
print(first_missing_positive(arr))  # Output: 2

```

### 6. Make Unique Array

```python
def make_unique(arr):
    return list(set(arr))

```

**Example Usage:**

```python
arr = [1, 2, 2, 3, 4, 4]
print(make_unique(arr))  # Output: [1, 2, 3, 4]

```

### 7. Sum of Zeroes

```python
def sum_of_zeroes(arr):
    return arr.count(0)

```

**Example Usage:**

```python
arr = [0, 1, 0, 3, 0]
print(sum_of_zeroes(arr))  # Output: 3

```

### 8. Matrix Symmetric

```python
def is_symmetric(matrix):
    return all(matrix[i][j] == matrix[j][i] for i in range(len(matrix)) for j in range(len(matrix[i])))

```

**Example Usage:**

```python
matrix = [[1, 2, 3], [2, 4, 5], [3, 5, 6]]
print(is_symmetric(matrix))  # Output: True

```

### 9. Pair Sum

```python
def pair_sum(arr, target):
    seen = set()
    pairs = set()
    for num in arr:
        complement = target - num
        if complement in seen:
            pairs.add((min(num, complement), max(num, complement)))
        seen.add(num)
    return list(pairs)

```

**Example Usage:**

```python
arr = [1, 2, 3, 4, 5]
print(pair_sum(arr, 6))  # Output: [(1, 5), (2, 4)]

```

### 10. Bubble Sort

```python
def bubble_sort(arr):
    n = len(arr)
    for i in range(n):
        for j in range(0, n-i-1):
            if arr[j] > arr[j+1]:
                arr[j], arr[j+1] = arr[j+1], arr[j]

```

**Example Usage:**

```python
arr = [64, 34, 25, 12, 22, 11, 90]
bubble_sort(arr)
print(arr)  # Output: [11, 12, 22, 25, 34, 64, 90]

```

### 11. Selection Sort

```python
def selection_sort(arr):
    for i in range(len(arr)):
        min_idx = i
        for j in range(i+1, len(arr)):
            if arr[j] < arr[min_idx]:
                min_idx = j
        arr[i], arr[min_idx] = arr[min_idx], arr[i]

```

**Example Usage:**

```python
arr = [64, 34, 25, 12, 22, 11, 90]
selection_sort(arr)
print(arr)  # Output: [11, 12, 22, 25, 34, 64, 90]

```

### 12. Insertion Sort

```python
def insertion_sort(arr):
    for i in range(1, len(arr)):
        key = arr[i]
        j = i - 1
        while j >= 0 and key < arr[j]:
            arr[j + 1] = arr[j]
            j -= 1
        arr[j + 1] = key

```

**Example Usage:**

```python
arr = [64, 34, 25, 12, 22, 11, 90]
insertion_sort(arr)
print(arr)  # Output: [11, 12, 22, 25, 34, 64, 90]

```

### 13. Intersection of Two Arrays

```python
def intersection(arr1, arr2):
    return list(set(arr1) & set(arr2))

```

**Example Usage:**

```python
arr1 = [1, 2, 2, 1]
arr2 = [2, 2]
print(intersection(arr1, arr2))  # Output: [2]

```

### 14. Kadane’s Algorithm

```python
def kadane(arr):
    max_current = max_global = arr[0]
    for num in arr[1:]:
        max_current = max(num, max_current + num)
        max_global = max(max_global, max_current)
    return max_global

```

**Example Usage:**

```python
arr = [1, -2, 3, -1, 2]
print(kadane(arr))  # Output: 4

```

### 15. Move Zeroes to End

```python
def move_zeroes(arr):
    non_zero_index = 0
    for i in range(len(arr)):
        if arr[i] != 0:
            arr[non_zero_index], arr[i] = arr[i], arr[non_zero_index]
            non_zero_index += 1

```

**Example Usage:**

```python
arr = [0, 1, 0, 3, 12]
move_zeroes(arr)
print(arr)  # Output: [1, 3, 12, 0, 0]

```

### 16. Square Root

```python
import math

def square_root(n):
    return math.sqrt(n)

```

**Example Usage:**

```python
print(square_root(16))  # Output: 4.0

```

### 17. Search in Rotated Sorted Array

```python
def search_rotated(arr, target):
    left, right = 0, len(arr) - 1
    while left <= right:
        mid = (left + right) // 2
        if arr[mid] == target:
            return mid
        if arr[left] <= arr[mid]:
            if arr[left] <= target < arr[mid]:
                right = mid - 1
            else:
                left = mid + 1
        else:
            if arr[mid] < target <= arr[right]:
                left = mid + 1
            else:
                right = mid - 1
    return -1

```

**Example Usage:**

```python
arr = [4, 5, 6, 7, 0, 1, 2]
print(search_rotated(arr, 0))  # Output: 4

```

### 18. Move Negative Numbers to Start

```python
def move_negatives(arr):
    left, right = 0, len(arr) - 1
    while left <= right:
        if arr[left] < 0:
            left += 1
        elif arr[right] >= 0:
            right -= 1
        else:
            arr[left], arr[right] = arr[right], arr[left]
            left += 1
            right -= 1

```

- *Example

Usage:**

```python
arr = [1, -2, 3, -4, 5]
move_negatives(arr)
print(arr)  # Output: [-4, -2, 3, 1, 5]

```

### 19. Container with Most Water

```python
def max_area(height):
    left, right = 0, len(height) - 1
    max_area = 0
    while left < right:
        width = right - left
        max_area = max(max_area, min(height[left], height[right]) * width)
        if height[left] < height[right]:
            left += 1
        else:
            right -= 1
    return max_area

```

**Example Usage:**

```python
height = [1, 8, 6, 2, 5, 4, 8, 3, 7]
print(max_area(height))  # Output: 49

```

### 20. Longest Subarray Zero Sum

```python
def longest_zero_sum_subarray(arr):
    sum_index_map = {0: -1}
    max_length, current_sum = 0, 0
    for i, num in enumerate(arr):
        current_sum += num
        if current_sum in sum_index_map:
            max_length = max(max_length, i - sum_index_map[current_sum])
        else:
            sum_index_map[current_sum] = i
    return max_length

```

**Example Usage:**

```python
arr = [1, -1, 3, -2, 2]
print(longest_zero_sum_subarray(arr))  # Output: 4

```

### 21. Dutch National Flag Algorithm

```python
def dutch_national_flag(arr):
    low, mid, high = 0, 0, len(arr) - 1
    while mid <= high:
        if arr[mid] == 0:
            arr[low], arr[mid] = arr[mid], arr[low]
            low += 1
            mid += 1
        elif arr[mid] == 1:
            mid += 1
        else:
            arr[mid], arr[high] = arr[high], arr[mid]
            high -= 1

```

**Example Usage:**

```python
arr = [1, 0, 2, 1, 0, 2]
dutch_national_flag(arr)
print(arr)  # Output: [0, 0, 1, 1, 2, 2]

```

### 22. Moore’s Voting Algorithm

```python
def moore_voting(arr):
    count, candidate = 0, None
    for num in arr:
        if count == 0:
            candidate = num
        count += (1 if num == candidate else -1)
    return candidate

```

**Example Usage:**

```python
arr = [3, 3, 4, 2, 4, 4, 2, 4, 4]
print(moore_voting(arr))  # Output: 4

```

### 23. Check Subsequence

```python
def is_subsequence(s, t):
    it = iter(t)
    return all(c in it for c in s)

```

**Example Usage:**

```python
s = "abc"
t = "ahbgdc"
print(is_subsequence(s, t))  # Output: True

```

### 24. Inplace Rotate Matrix 90 Degrees

```python
def rotate_matrix(matrix):
    n = len(matrix)
    for i in range(n):
        for j in range(i, n):
            matrix[i][j], matrix[j][i] = matrix[j][i], matrix[i][j]
    for row in matrix:
        row.reverse()

```

**Example Usage:**

```python
matrix = [
    [1, 2, 3],
    [4, 5, 6],
    [7, 8, 9]
]
rotate_matrix(matrix)
print(matrix)  # Output: [[7, 4, 1], [8, 5, 2], [9, 6, 3]]

```

### 25. Set Matrix Zeroes

```python
def set_matrix_zeroes(matrix):
    rows, cols = len(matrix), len(matrix[0])
    zero_rows, zero_cols = set(), set()
    for i in range(rows):
        for j in range(cols):
            if matrix[i][j] == 0:
                zero_rows.add(i)
                zero_cols.add(j)
    for row in zero_rows:
        for j in range(cols):
            matrix[row][j] = 0
    for col in zero_cols:
        for i in range(rows):
            matrix[i][col] = 0

```

**Example Usage:**

```python
matrix = [
    [1, 2, 3],
    [4, 0, 6],
    [7, 8, 9]
]
set_matrix_zeroes(matrix)
print(matrix)  # Output: [[1, 0, 3], [0, 0, 0], [7, 0, 9]]

```

### 26. Count All Sub-arrays Having Sum Divisible by K

```python
def count_subarrays_divisible_by_k(arr, k):
    count = 0
    sum_count = {0: 1}
    current_sum = 0
    for num in arr:
        current_sum += num
        mod = current_sum % k
        if mod < 0:
            mod += k
        count += sum_count.get(mod, 0)
        sum_count[mod] = sum_count.get(mod, 0) + 1
    return count

```

**Example Usage:**

```python
arr = [4, 5, 0, -2, -3, 1]
k = 5
print(count_subarrays_divisible_by_k(arr, k))  # Output: 7

```

### 27. Spiral Order

```python
def spiral_order(matrix):
    result = []
    while matrix:
        result += matrix[0]
        matrix = list(zip(*matrix[1:]))[::-1]
    return result

```

**Example Usage:**

```python
matrix = [
    [1, 2, 3],
    [4, 5, 6],
    [7, 8, 9]
]
print(spiral_order(matrix))  # Output: [1, 2, 3, 6, 9, 8, 7, 4, 5]
```

## Strings - 9

### Strings in Python

**Introduction:**

Strings are sequences of characters used to represent text. In Python, strings are immutable, meaning once created, they cannot be altered. Python provides a rich set of methods for manipulating and processing strings, making them versatile for various applications, from simple text processing to complex data handling.

**Important Points:**

- **Immutability:** Strings in Python cannot be modified after creation. Operations that alter a string return a new string.
- **Indexing:** Characters in a string are accessed via zero-based indexing, allowing for easy traversal and manipulation.
- **Common Operations:** Includes concatenation (`+`), repetition (``), slicing, and various string methods such as `.upper()`, `.lower()`, `.replace()`, `.find()`, and `.split()`.
- **String Formatting:** Python supports several ways to format strings, including f-strings (formatted string literals), `.format()`, and the older `%` operator.
- **Unicode Support:** Python strings are Unicode by default, allowing for international characters and symbols.

Understanding strings is essential for tasks involving text manipulation, data extraction, and formatting, making them a critical component in programming.

### 1. Reverse String Word Wise

```python
def reverse_string_word_wise(s):
    return ' '.join(s.split()[::-1])

```

**Example Usage:**

```python
s = "hello world"
print(reverse_string_word_wise(s))  # Output: "world hello"

```

### 2. String Encoding

```python
def encode_string(s):
    encoded = []
    count = 1
    for i in range(1, len(s)):
        if s[i] == s[i - 1]:
            count += 1
        else:
            encoded.append(s[i - 1] + str(count))
            count = 1
    encoded.append(s[-1] + str(count))
    return ''.join(encoded)

```

**Example Usage:**

```python
s = "aaabbc"
print(encode_string(s))  # Output: "a3b2c1"

```

### 3. Minimum Parenthesis

```python
def min_parentheses_to_balance(s):
    left, right = 0, 0
    for char in s:
        if char == '(':
            left += 1
        elif char == ')':
            if left > 0:
                left -= 1
            else:
                right += 1
    return left + right

```

**Example Usage:**

```python
s = "(()())("
print(min_parentheses_to_balance(s))  # Output: 2

```

### 4. Beautiful Strings

A beautiful string is a string with no two adjacent characters being the same. To make a string beautiful, we may need to change some characters. This function finds the minimum number of changes needed.

```python
def min_changes_to_beautiful(s):
    changes = 0
    for i in range(1, len(s)):
        if s[i] == s[i - 1]:
            changes += 1
    return changes

```

**Example Usage:**

```python
s = "aabb"
print(min_changes_to_beautiful(s))  # Output: 2

```

### 5. Next Smallest Palindrome

```python
def next_smallest_palindrome(s):
    s = list(s)
    n = len(s)
    def is_palindrome(s):
        return s == s[::-1]

    def find_next_palindrome(s):
        i = n // 2
        while i >= 0:
            if s[i] < '9':
                s[i] = s[i + 1] = chr(ord(s[i]) + 1)
                if is_palindrome(s):
                    return ''.join(s)
                else:
                    s[i] = s[i + 1] = '0'
            i -= 1
        return '1' + '0' * (n - 1) + '1'

    if is_palindrome(s):
        return find_next_palindrome(s)
    return ''

```

**Example Usage:**

```python
s = "12321"
print(next_smallest_palindrome(s))  # Output: "12421"

```

### 6. First Non-Repeating Character in String

```python
def first_non_repeating_char(s):
    from collections import Counter
    count = Counter(s)
    for char in s:
        if count[char] == 1:
            return char
    return None

```

**Example Usage:**

```python
s = "swiss"
print(first_non_repeating_char(s))  # Output: "w"

```

### 7. Check Permutation

```python
def check_permutation(s1, s2):
    return sorted(s1) == sorted(s2)

```

**Example Usage:**

```python
s1 = "listen"
s2 = "silent"
print(check_permutation(s1, s2))  # Output: True

```

### 8. Find Kth Character of Decrypted String

```python
def find_kth_char_of_decrypted(s, k):
    decoded_str = []
    i = 0
    while i < len(s):
        char = s[i]
        j = i + 1
        while j < len(s) and s[j].isdigit():
            j += 1
        count = int(s[i + 1:j]) if i + 1 < j else 1
        decoded_str.append(char * count)
        i = j
    return ''.join(decoded_str)[k - 1] if 0 <= k - 1 < len(''.join(decoded_str)) else None

```

**Example Usage:**

```python
s = "a2b3"
k = 4
print(find_kth_char_of_decrypted(s, k))  # Output: "b"

```

### 9. Group Anagrams

```python
def group_anagrams(words):
    from collections import defaultdict
    anagrams = defaultdict(list)
    for word in words:
        sorted_word = ''.join(sorted(word))
        anagrams[sorted_word].append(word)
    return list(anagrams.values())

```

**Example Usage:**

```python
words = ["eat", "tea", "tan", "ate", "nat", "bat"]
print(group_anagrams(words))  # Output: [['eat', 'tea', 'ate'], ['tan', 'nat'], ['bat']]
```

## Recursion - 6

### Recursion in Python

**Introduction:**

Recursion is a programming technique where a function calls itself to solve a problem. It is often used to break down complex problems into simpler sub-problems. Recursion is useful for problems that can be divided into similar sub-problems, such as tree traversals, dynamic programming, and combinatorial problems.

**Important Points:**

- **Base Case:** Every recursive function must have a base case, which defines when the recursion should stop. Without a base case, recursion can lead to infinite loops and stack overflow errors.
- **Recursive Case:** The part of the function that calls itself with modified parameters to move towards the base case.
- **Stack Memory:** Each recursive call adds a new frame to the call stack, which holds the function's local variables and state. Excessive recursion can lead to stack overflow.
- **Termination:** Ensure that the recursion progresses towards the base case to avoid infinite recursion.
- **Tail Recursion:** A special case of recursion where the recursive call is the last operation in the function. Some languages optimize tail recursion to avoid adding extra frames to the call stack.

Recursion simplifies complex problems by breaking them into smaller, more manageable problems, but it requires careful handling to ensure it terminates correctly and efficiently.

### 1. Merge Sort

```python
def merge_sort(arr):
    if len(arr) > 1:
        mid = len(arr) // 2
        left_half = arr[:mid]
        right_half = arr[mid:]

        merge_sort(left_half)
        merge_sort(right_half)

        i = j = k = 0

        while i < len(left_half) and j < len(right_half):
            if left_half[i] < right_half[j]:
                arr[k] = left_half[i]
                i += 1
            else:
                arr[k] = right_half[j]
                j += 1
            k += 1

        while i < len(left_half):
            arr[k] = left_half[i]
            i += 1
            k += 1

        while j < len(right_half):
            arr[k] = right_half[j]
            j += 1
            k += 1

    return arr

```

**Example Usage:**

```python
arr = [38, 27, 43, 3, 9, 82, 10]
print(merge_sort(arr))  # Output: [3, 9, 10, 27, 38, 43, 82]

```

### 2. Quick Sort

```python
def quick_sort(arr):
    def partition(low, high):
        pivot = arr[high]
        i = low - 1
        for j in range(low, high):
            if arr[j] <= pivot:
                i += 1
                arr[i], arr[j] = arr[j], arr[i]
        arr[i + 1], arr[high] = arr[high], arr[i + 1]
        return i + 1

    def sort_recursively(low, high):
        if low < high:
            pi = partition(low, high)
            sort_recursively(low, pi - 1)
            sort_recursively(pi + 1, high)

    sort_recursively(0, len(arr) - 1)
    return arr

```

**Example Usage:**

```python
arr = [10, 7, 8, 9, 1, 5]
print(quick_sort(arr))  # Output: [1, 5, 7, 8, 9, 10]

```

### 3. Tower of Hanoi

```python
def tower_of_hanoi(n, source, auxiliary, destination):
    if n == 1:
        print(f"Move disk 1 from {source} to {destination}")
        return
    tower_of_hanoi(n - 1, source, destination, auxiliary)
    print(f"Move disk {n} from {source} to {destination}")
    tower_of_hanoi(n - 1, auxiliary, source, destination)

```

**Example Usage:**

```python
tower_of_hanoi(3, 'A', 'B', 'C')

```

**Output:**

```
Move disk 1 from A to C
Move disk 2 from A to B
Move disk 1 from C to B
Move disk 3 from A to C
Move disk 1 from B to A
Move disk 2 from B to C
Move disk 1 from A to C

```

### 4. Find Kth Element

```python
def find_kth_element(arr, k):
    def partition(low, high):
        pivot = arr[high]
        i = low - 1
        for j in range(low, high):
            if arr[j] <= pivot:
                i += 1
                arr[i], arr[j] = arr[j], arr[i]
        arr[i + 1], arr[high] = arr[high], arr[i + 1]
        return i + 1

    def quick_select(low, high, k):
        if low < high:
            pi = partition(low, high)
            if pi == k:
                return arr[pi]
            elif pi < k:
                return quick_select(pi + 1, high, k)
            else:
                return quick_select(low, pi - 1, k)
        return arr[low]

    return quick_select(0, len(arr) - 1, k - 1)

```

**Example Usage:**

```python
arr = [12, 3, 5, 7, 19]
k = 2
print(find_kth_element(arr, k))  # Output: 5 (2nd smallest element)

```

### 5. Family Structure

This problem can be interpreted in various ways. Here's a general solution for a simple family tree representation where you define members and relationships:

```python
class FamilyMember:
    def __init__(self, name):
        self.name = name
        self.children = []

    def add_child(self, child):
        self.children.append(child)

    def display(self, level=0):
        print(' ' * level * 2 + self.name)
        for child in self.children:
            child.display(level + 1)

```

**Example Usage:**

```python
root = FamilyMember('Grandparent')
parent = FamilyMember('Parent')
child = FamilyMember('Child')

root.add_child(parent)
parent.add_child(child)

root.display()

```

**Output:**

```
Grandparent
  Parent
    Child

```

### 6. Binary String With No Consecutive 1s

```python
def count_binary_strings(n):
    def count_recursively(n, prev):
        if n == 0:
            return 1
        if prev == 1:
            return count_recursively(n - 1, 0)
        return count_recursively(n - 1, 0) + count_recursively(n - 1, 1)

    return count_recursively(n, 0) + count_recursively(n, 1)

```

**Example Usage:**

```python
n = 3
print(count_binary_strings(n))  # Output: 5 (Valid strings: "000", "001", "010", "100", "101")
```

## Linked List - 10

### Linked List in Python

**Introduction:**

A linked list is a linear data structure where each element, called a node, contains a reference (or link) to the next node in the sequence. Unlike arrays, linked lists do not require contiguous memory allocation and can efficiently handle dynamic data sizes. They are useful for scenarios where frequent insertions and deletions are needed.

**Important Points:**

- **Node Structure:** Each node in a linked list typically contains two components: data and a reference to the next node. In some variations, nodes can also have a reference to the previous node (doubly linked list).
- **Head Pointer:** The linked list is typically represented by a pointer (or reference) to the first node, called the head. If the list is empty, the head is set to `None`.
- **Types of Linked Lists:**
    - **Singly Linked List:** Each node has a reference to the next node only.
    - **Doubly Linked List:** Each node has references to both the next and previous nodes, allowing bidirectional traversal.
    - **Circular Linked List:** The last node points back to the first node, forming a circular structure.
- **Dynamic Size:** Unlike arrays, linked lists can grow and shrink dynamically without needing reallocation or resizing.
- **Efficiency:** Insertion and deletion operations are generally more efficient compared to arrays, as they involve only updating references without shifting elements.

Linked lists are ideal for applications where efficient insertion and deletion operations are crucial, but they require more memory per element due to additional references and may have slower access times compared to arrays.

### 1. Reverse A Linked List

```python
class ListNode:
    def __init__(self, val=0, next=None):
        self.val = val
        self.next = next

def reverse_list(head):
    prev = None
    current = head
    while current:
        next_node = current.next
        current.next = prev
        prev = current
        current = next_node
    return prev

```

**Example Usage:**

```python
# Helper function to create a linked list from a list
def create_linked_list(elements):
    head = ListNode(elements[0])
    current = head
    for elem in elements[1:]:
        current.next = ListNode(elem)
        current = current.next
    return head

# Example
head = create_linked_list([1, 2, 3, 4, 5])
reversed_head = reverse_list(head)
# Print reversed list
while reversed_head:
    print(reversed_head.val, end=" -> ")
    reversed_head = reversed_head.next
# Output: 5 -> 4 -> 3 -> 2 -> 1 ->

```

### 2. Mid Point In Linked List

```python
def find_middle(head):
    slow = fast = head
    while fast and fast.next:
        slow = slow.next
        fast = fast.next.next
    return slow

```

**Example Usage:**

```python
# Example usage (with a list of values)
head = create_linked_list([1, 2, 3, 4, 5])
mid = find_middle(head)
print(mid.val)  # Output: 3

```

### 3. Merge Sort

```python
def merge_sort(head):
    if not head or not head.next:
        return head

    def split(head):
        slow = fast = head
        while fast.next and fast.next.next:
            slow = slow.next
            fast = fast.next.next
        middle = slow.next
        slow.next = None
        return head, middle

    def merge(left, right):
        dummy = ListNode()
        current = dummy
        while left and right:
            if left.val < right.val:
                current.next = left
                left = left.next
            else:
                current.next = right
                right = right.next
            current = current.next
        if left:
            current.next = left
        if right:
            current.next = right
        return dummy.next

    left, right = split(head)
    left = merge_sort(left)
    right = merge_sort(right)
    return merge(left, right)

```

**Example Usage:**

```python
head = create_linked_list([4, 2, 1, 3])
sorted_head = merge_sort(head)
while sorted_head:
    print(sorted_head.val, end=" -> ")
    sorted_head = sorted_head.next
# Output: 1 -> 2 -> 3 -> 4 ->

```

### 4. Add Two Linked Lists

```python
def add_two_numbers(l1, l2):
    dummy = ListNode()
    current = dummy
    carry = 0

    while l1 or l2 or carry:
        val1 = l1.val if l1 else 0
        val2 = l2.val if l2 else 0
        carry, out = divmod(val1 + val2 + carry, 10)
        current.next = ListNode(out)
        current = current.next
        if l1:
            l1 = l1.next
        if l2:
            l2 = l2.next

    return dummy.next

```

**Example Usage:**

```python
l1 = create_linked_list([2, 4, 3])  # Represents 342
l2 = create_linked_list([5, 6, 4])  # Represents 465
result = add_two_numbers(l1, l2)
while result:
    print(result.val, end=" -> ")
    result = result.next
# Output: 7 -> 0 -> 8 -> (342 + 465 = 807)

```

### 5. Insertion Sort on Linked List

```python
def insertion_sort_list(head):
    dummy = ListNode(float('-inf'))
    current = head

    while current:
        prev = dummy
        while prev.next and prev.next.val < current.val:
            prev = prev.next
        next_node = current.next
        current.next = prev.next
        prev.next = current
        current = next_node

    return dummy.next

```

**Example Usage:**

```python
head = create_linked_list([4, 2, 1, 3])
sorted_head = insertion_sort_list(head)
while sorted_head:
    print(sorted_head.val, end=" -> ")
    sorted_head = sorted_head.next
# Output: 1 -> 2 -> 3 -> 4 ->

```

### 6. Delete Kth Node from End

```python
def delete_kth_from_end(head, k):
    dummy = ListNode(0)
    dummy.next = head
    slow = fast = dummy
    for _ in range(k + 1):
        fast = fast.next
    while fast:
        slow = slow.next
        fast = fast.next
    slow.next = slow.next.next
    return dummy.next

```

**Example Usage:**

```python
head = create_linked_list([1, 2, 3, 4, 5])
new_head = delete_kth_from_end(head, 2)
while new_head:
    print(new_head.val, end=" -> ")
    new_head = new_head.next
# Output: 1 -> 2 -> 3 -> 5 -> (Deleting 4th from end)

```

### 7. Detect And Remove Cycle

```python
def detect_and_remove_cycle(head):
    def has_cycle(head):
        slow = fast = head
        while fast and fast.next:
            slow = slow.next
            fast = fast.next.next
            if slow == fast:
                return True
        return False

    def remove_cycle(head):
        slow = fast = head
        while True:
            slow = slow.next
            fast = fast.next.next
            if slow == fast:
                break
        slow = head
        while slow != fast:
            slow = slow.next
            fast = fast.next
        # Find the start of the cycle and remove it
        while fast.next != slow:
            fast = fast.next
        fast.next = None

    if has_cycle(head):
        remove_cycle(head)
    return head

```

**Example Usage:**

```python
# Create a linked list with a cycle for demonstration
head = create_linked_list([1, 2, 3])
head.next.next.next = head.next  # Creating a cycle
head = detect_and_remove_cycle(head)
# The list should now be free of cycles

```

### 8. Swap Nodes In Pairs

```python
def swap_pairs(head):
    dummy = ListNode(0)
    dummy.next = head
    prev = dummy

    while head and head.next:
        first = head
        second = head.next
        prev.next = second
        first.next = second.next
        second.next = first
        prev = first
        head = first.next

    return dummy.next

```

**Example Usage:**

```python
head = create_linked_list([1, 2, 3, 4])
swapped_head = swap_pairs(head)
while swapped_head:
    print(swapped_head.val, end=" -> ")
    swapped_head = swapped_head.next
# Output: 2 -> 1 -> 4 -> 3 ->

```

### 9. Append Nodes

```python
def append_nodes(head, values):
    current = head
    while current.next:
        current = current.next
    for value in values:
        current.next = ListNode(value)
        current = current.next
    return head

```

**Example Usage:**

```python
head = create_linked_list([1, 2, 3])
head = append_nodes(head, [4, 5, 6])
while head:
    print(head.val, end=" -> ")
    head = head.next
# Output: 1 -> 2 -> 3 -> 4 -> 5 -> 6 ->

```

### 10. Segregate Odd Even

```python
def segregate_odd_even(head):
    odd_dummy = ListNode(0)
    even_dummy = ListNode(0)
    odd = odd_dummy
    even = even_dummy

    while head:
        if head.val % 2 == 0:
            even.next = head
            even = even.next
        else:
            odd.next = head
            odd = odd.next
        head = head.next

    odd.next = even_dummy.next
    even.next = None
    return odd_dummy.next

```

**Example Usage:**

```python
head = create_linked_list([1, 2, 3, 4, 5, 6])
segregated_head = segregate_odd_even(head)
while segregated_head:
    print(segregated_head.val, end=" -> ")
    segregated_head = segregated_head.next
# Output: 1 -> 3 -> 5 -> 2 -> 4 -> 6 ->
```

## Stacks & Queues - 10

### Stacks and Queues in Python

**Introduction:**

Stacks and queues are fundamental data structures used to manage data in specific ways. They differ in the order in which elements are added and removed.

**Stacks:**

- **Definition:** A stack is a Last In, First Out (LIFO) data structure. Elements are added (pushed) and removed (popped) from the same end, known as the top of the stack.
- **Operations:**
    - **Push:** Add an element to the top of the stack.
    - **Pop:** Remove and return the element from the top of the stack.
    - **Peek/Top:** Return the element at the top of the stack without removing it.
    - **isEmpty:** Check if the stack is empty.
- **Applications:** Used in scenarios like function call management (call stack), expression evaluation (e.g., postfix expressions), and undo mechanisms.

**Queues:**

- **Definition:** A queue is a First In, First Out (FIFO) data structure. Elements are added (enqueued) at the rear and removed (dequeued) from the front.
- **Operations:**
    - **Enqueue:** Add an element to the rear of the queue.
    - **Dequeue:** Remove and return the element from the front of the queue.
    - **Peek/Front:** Return the element at the front of the queue without removing it.
    - **isEmpty:** Check if the queue is empty.
- **Applications:** Used in scenarios like task scheduling (e.g., CPU scheduling), buffering (e.g., IO buffers), and breadth-first search (BFS) in graphs.

**Key Differences:**

- **Order of Processing:** Stacks process the most recently added element first, while queues process the oldest added element first.
- **Usage:** Stacks are ideal for tasks requiring reversal or last-accessed-first processing, while queues are suitable for tasks requiring first-come, first-served processing.

Both stacks and queues can be implemented using arrays or linked lists and are integral to various algorithms and systems.

### 1. Implement Stack Using Array

```python
class Stack:
    def __init__(self):
        self.stack = []

    def push(self, item):
        self.stack.append(item)

    def pop(self):
        if not self.is_empty():
            return self.stack.pop()
        raise IndexError("Pop from empty stack")

    def peek(self):
        if not self.is_empty():
            return self.stack[-1]
        raise IndexError("Peek from empty stack")

    def is_empty(self):
        return len(self.stack) == 0

    def size(self):
        return len(self.stack)

```

**Example Usage:**

```python
s = Stack()
s.push(1)
s.push(2)
print(s.pop())  # Output: 2
print(s.peek()) # Output: 1
print(s.size()) # Output: 1

```

### 2. Implement Stack Using Linked List

```python
class Node:
    def __init__(self, value):
        self.value = value
        self.next = None

class StackLinkedList:
    def __init__(self):
        self.top = None

    def push(self, item):
        new_node = Node(item)
        new_node.next = self.top
        self.top = new_node

    def pop(self):
        if not self.is_empty():
            value = self.top.value
            self.top = self.top.next
            return value
        raise IndexError("Pop from empty stack")

    def peek(self):
        if not self.is_empty():
            return self.top.value
        raise IndexError("Peek from empty stack")

    def is_empty(self):
        return self.top is None

```

**Example Usage:**

```python
s = StackLinkedList()
s.push(1)
s.push(2)
print(s.pop())  # Output: 2
print(s.peek()) # Output: 1

```

### 3. Implement Queue Using Array/Linked List

**Array Implementation:**

```python
class QueueArray:
    def __init__(self):
        self.queue = []

    def enqueue(self, item):
        self.queue.append(item)

    def dequeue(self):
        if not self.is_empty():
            return self.queue.pop(0)
        raise IndexError("Dequeue from empty queue")

    def is_empty(self):
        return len(self.queue) == 0

    def size(self):
        return len(self.queue)

```

**Linked List Implementation:**

```python
class Node:
    def __init__(self, value):
        self.value = value
        self.next = None

class QueueLinkedList:
    def __init__(self):
        self.front = self.rear = None

    def enqueue(self, item):
        new_node = Node(item)
        if self.rear is None:
            self.front = self.rear = new_node
            return
        self.rear.next = new_node
        self.rear = new_node

    def dequeue(self):
        if not self.is_empty():
            value = self.front.value
            self.front = self.front.next
            if self.front is None:
                self.rear = None
            return value
        raise IndexError("Dequeue from empty queue")

    def is_empty(self):
        return self.front is None

```

### 4. Implement Queue Using 2 Stacks

```python
class QueueUsingStacks:
    def __init__(self):
        self.stack1 = []
        self.stack2 = []

    def enqueue(self, item):
        self.stack1.append(item)

    def dequeue(self):
        if not self.stack2:
            while self.stack1:
                self.stack2.append(self.stack1.pop())
        if not self.stack2:
            raise IndexError("Dequeue from empty queue")
        return self.stack2.pop()

```

**Example Usage:**

```python
q = QueueUsingStacks()
q.enqueue(1)
q.enqueue(2)
print(q.dequeue())  # Output: 1

```

### 5. Implement Stack Using 2 Queues

```python
from collections import deque

class StackUsingQueues:
    def __init__(self):
        self.queue1 = deque()
        self.queue2 = deque()

    def push(self, item):
        self.queue1.append(item)

    def pop(self):
        if not self.queue1:
            raise IndexError("Pop from empty stack")
        while len(self.queue1) > 1:
            self.queue2.append(self.queue1.popleft())
        value = self.queue1.popleft()
        self.queue1, self.queue2 = self.queue2, self.queue1
        return value

    def peek(self):
        if not self.queue1:
            raise IndexError("Peek from empty stack")
        while len(self.queue1) > 1:
            self.queue2.append(self.queue1.popleft())
        value = self.queue1.popleft()
        self.queue2.append(value)
        self.queue1, self.queue2 = self.queue2, self.queue1
        return value

```

### 6. Min Stack

```python
class MinStack:
    def __init__(self):
        self.stack = []
        self.min_stack = []

    def push(self, item):
        self.stack.append(item)
        if not self.min_stack or item <= self.min_stack[-1]:
            self.min_stack.append(item)

    def pop(self):
        if not self.is_empty():
            item = self.stack.pop()
            if item == self.min_stack[-1]:
                self.min_stack.pop()
            return item
        raise IndexError("Pop from empty stack")

    def get_min(self):
        if not self.min_stack:
            raise IndexError("Get min from empty stack")
        return self.min_stack[-1]

    def is_empty(self):
        return not self.stack

```

**Example Usage:**

```python
s = MinStack()
s.push(1)
s.push(2)
s.push(-1)
print(s.get_min())  # Output: -1
print(s.pop())      # Output: -1
print(s.get_min())  # Output: 1

```

### 7. Next Greater Element

```python
def next_greater_element(nums):
    stack = []
    result = [-1] * len(nums)
    for i in range(len(nums)):
        while stack and nums[i] > nums[stack[-1]]:
            result[stack.pop()] = nums[i]
        stack.append(i)
    return result

```

**Example Usage:**

```python
nums = [4, 3, 2, 5, 7]
print(next_greater_element(nums))  # Output: [5, 5, 5, 7, -1]

```

### 8. Stock Span Problem

```python
def stock_span(prices):
    stack = []
    spans = []
    for price in prices:
        span = 1
        while stack and stack[-1][0] <= price:
            span += stack.pop()[1]
        spans.append(span)
        stack.append((price, span))
    return spans

```

**Example Usage:**

```python
prices = [100, 80, 60, 70, 60, 75, 85]
print(stock_span(prices))  # Output: [1, 1, 1, 2, 1, 4, 6]

```

### 9. Reverse Queue

```python
from collections import deque

def reverse_queue(queue):
    stack = []
    while queue:
        stack.append(queue.popleft())
    while stack:
        queue.append(stack.pop())
    return queue

```

**Example Usage:**

```python
q = deque([1, 2, 3, 4])
reversed_q = reverse_queue(q)
print(reversed_q)  # Output: deque([4, 3, 2, 1])

```

### 10. Valid Parentheses

```python
def valid_parentheses(s):
    stack = []
    mapping = {')': '(', '}': '{', ']': '['}
    for char in s:
        if char in mapping:
            top_element = stack.pop() if stack else '#'
            if mapping[char] != top_element:
                return False
        else:
            stack.append(char)
    return not stack

```

**Example Usage:**

```python
print(valid_parentheses("()[]{}"))  # Output: True
print(valid_parentheses("(]"))      # Output: False
```

## Binary Trees & BST - 16

### Binary Trees and Binary Search Trees (BST) in Python

**Introduction:**

**Binary Trees:**

- **Definition:** A binary tree is a hierarchical data structure where each node has at most two children, referred to as the left child and the right child.
- **Types:**
    - **Full Binary Tree:** Every node has either 0 or 2 children.
    - **Complete Binary Tree:** All levels are fully filled except possibly the last level, which is filled from left to right.
    - **Perfect Binary Tree:** All internal nodes have two children, and all leaf nodes are at the same level.
    - **Balanced Binary Tree:** The height of the left and right subtrees of any node differ by at most one.
- **Traversals:**
    - **Inorder (Left, Root, Right):** Visits nodes in ascending order for BSTs.
    - **Preorder (Root, Left, Right):** Useful for copying the tree.
    - **Postorder (Left, Right, Root):** Useful for deleting the tree.
    - **Level Order:** Visits nodes level by level.

**Binary Search Trees (BST):**

- **Definition:** A binary search tree is a binary tree where each node follows the property: all nodes in the left subtree are less than the root node, and all nodes in the right subtree are greater than the root node.
- **Operations:**
    - **Insertion:** Add a new node in its appropriate position to maintain BST properties.
    - **Deletion:** Remove a node while ensuring the tree remains a valid BST.
    - **Search:** Find a node with a given value efficiently due to the BST property.
    - **Find Minimum/Maximum:** Retrieve the smallest/largest value in the BST.
    - **Find Successor/Predecessor:** Retrieve the next or previous node in sorted order.
- **Applications:** Useful for efficient searching, insertion, and deletion operations. BSTs are used in various algorithms, including balanced variants like AVL Trees and Red-Black Trees for ensuring O(log n) operations.

**Key Differences:**

- **Structure:** All BSTs are binary trees, but not all binary trees are BSTs. A BST has a specific order property, while a binary tree does not.
- **Usage:** Binary trees are used in applications like expression parsing and hierarchical data representation, while BSTs are used for efficient data retrieval and dynamic sorting.

Both binary trees and BSTs are fundamental structures with numerous applications in computer science, particularly in algorithms involving hierarchical data.

### 1. Diameter of Binary Tree

The diameter of a binary tree is the length of the longest path between any two nodes in the tree.

```python
class TreeNode:
    def __init__(self, value=0, left=None, right=None):
        self.value = value
        self.left = left
        self.right = right

def diameter_of_binary_tree(root):
    def height(node):
        if not node:
            return 0
        left_height = height(node.left)
        right_height = height(node.right)
        diameter[0] = max(diameter[0], left_height + right_height)
        return 1 + max(left_height, right_height)

    diameter = [0]
    height(root)
    return diameter[0]

```

### 2. Lowest Common Ancestor (LCA) of Binary Tree

Find the lowest common ancestor of two nodes in a binary tree.

```python
def lowest_common_ancestor(root, p, q):
    if not root or root == p or root == q:
        return root

    left = lowest_common_ancestor(root.left, p, q)
    right = lowest_common_ancestor(root.right, p, q)

    if left and right:
        return root
    return left if left else right

```

### 3. Level Order Traversal of Binary Tree

Traverse a binary tree level by level.

```python
from collections import deque

def level_order_traversal(root):
    if not root:
        return []

    result = []
    queue = deque([root])

    while queue:
        level = []
        for _ in range(len(queue)):
            node = queue.popleft()
            level.append(node.value)
            if node.left:
                queue.append(node.left)
            if node.right:
                queue.append(node.right)
        result.append(level)

    return result

```

### 4. Zigzag Order Traversal of Binary Tree

Traverse a binary tree in zigzag level order.

```python
def zigzag_level_order(root):
    if not root:
        return []

    result = []
    queue = deque([root])
    level = 0

    while queue:
        level_size = len(queue)
        current_level = []

        for _ in range(level_size):
            node = queue.popleft()
            if level % 2 == 0:
                current_level.append(node.value)
            else:
                current_level.insert(0, node.value)
            if node.left:
                queue.append(node.left)
            if node.right:
                queue.append(node.right)

        result.append(current_level)
        level += 1

    return result

```

### 5. Left View of Binary Tree

Print the nodes visible from the left view of a binary tree.

```python
def left_view(root):
    def dfs(node, level):
        if not node:
            return
        if level == len(view):
            view.append(node.value)
        dfs(node.left, level + 1)
        dfs(node.right, level + 1)

    view = []
    dfs(root, 0)
    return view

```

### 6. Top View of Binary Tree

Print the top view of a binary tree.

```python
def top_view(root):
    if not root:
        return []

    result = []
    hd_map = {}
    queue = deque([(root, 0)])

    while queue:
        node, hd = queue.popleft()

        if hd not in hd_map:
            hd_map[hd] = node.value

        if node.left:
            queue.append((node.left, hd - 1))
        if node.right:
            queue.append((node.right, hd + 1))

    for hd in sorted(hd_map):
        result.append(hd_map[hd])

    return result

```

### 7. Construct Binary Tree From Inorder and Preorder

Construct a binary tree from inorder and preorder traversals.

```python
def build_tree(preorder, inorder):
    def build(pre_start, pre_end, in_start, in_end):
        if pre_start > pre_end or in_start > in_end:
            return None

        root_value = preorder[pre_start]
        root = TreeNode(root_value)
        in_root_index = inorder_index_map[root_value]
        left_size = in_root_index - in_start

        root.left = build(pre_start + 1, pre_start + left_size, in_start, in_root_index - 1)
        root.right = build(pre_start + left_size + 1, pre_end, in_root_index + 1, in_end)

        return root

    inorder_index_map = {value: index for index, value in enumerate(inorder)}
    return build(0, len(preorder) - 1, 0, len(inorder) - 1)

```

### 8. Vertical Order Traversal of Binary Tree

Print the vertical order of a binary tree.

```python
def vertical_order(root):
    if not root:
        return []

    from collections import defaultdict, deque

    result = defaultdict(list)
    queue = deque([(root, 0)])

    while queue:
        node, hd = queue.popleft()
        result[hd].append(node.value)

        if node.left:
            queue.append((node.left, hd - 1))
        if node.right:
            queue.append((node.right, hd + 1))

    return [result[key] for key in sorted(result.keys())]

```

### 9. Inorder Traversal of Binary Tree Using Stacks

Inorder traversal of a binary tree using stacks.

```python
def inorder_traversal(root):
    stack, result = [], []
    current = root

    while stack or current:
        while current:
            stack.append(current)
            current = current.left
        current = stack.pop()
        result.append(current.value)
        current = current.right

    return result

```

### 10. LCA of Two Nodes in BST

Find the LCA of two nodes in a Binary Search Tree (BST).

```python
def lca_bst(root, p, q):
    while root:
        if p.val < root.val and q.val < root.val:
            root = root.left
        elif p.val > root.val and q.val > root.val:
            root = root.right
        else:
            return root
    return None

```

### 11. BST Delete

Delete a node from a Binary Search Tree (BST).

```python
def delete_node(root, key):
    if not root:
        return None

    if key < root.value:
        root.left = delete_node(root.left, key)
    elif key > root.value:
        root.right = delete_node(root.right, key)
    else:
        if not root.left:
            return root.right
        elif not root.right:
            return root.left
        temp = min_value_node(root.right)
        root.value = temp.value
        root.right = delete_node(root.right, temp.value)

    return root

def min_value_node(node):
    current = node
    while current.left:
        current = current.left
    return current

```

### 12. Check if Binary Tree is BST

Check if a binary tree is a Binary Search Tree (BST).

```python
def is_bst(root, left=float('-inf'), right=float('inf')):
    if not root:
        return True

    if root.value <= left or root.value >= right:
        return False

    return (is_bst(root.left, left, root.value) and
            is_bst(root.right, root.value, right))

```

### 13. Kth Smallest Element in BST

Find the Kth smallest element in a Binary Search Tree (BST).

```python
def kth_smallest(root, k):
    def inorder(node):
        if node:
            yield from inorder(node.left)
            yield node.value
            yield from inorder(node.right)

    gen = inorder(root)
    for _ in range(k):
        kth_smallest = next(gen)

    return kth_smallest

```

### 14. Predecessor and Successor in BST

Find the predecessor and successor of a given node in a BST.

```python
def find_predecessor_and_successor(root, key):
    predecessor = successor = None

    def inorder(node):
        nonlocal predecessor, successor
        if node:
            inorder(node.left)
            if node.value < key:
                predecessor = node
            if node.value > key and (successor is None or node.value < successor.value):
                successor = node
            inorder(node.right)

    inorder(root)
    return predecessor, successor

```

### 15. LCA of 3 Nodes

Find the Lowest Common Ancestor (LCA) of three nodes in a binary tree.

```python
def lca_of_three(root, p, q, r):
    def lca_helper(node):
        if not node:
            return None
        if node == p or node == q or node == r:
            return node

        left = lca_helper(node.left)
        right = lca_helper(node.right)

        if left and right:
            return node
        return left if left else right

    return lca_helper(root)

```

### 16. Pair Sum in BST

Find pairs in a BST that sum up to a given target value.

```python
def find_pair_sum_bst(root, target):
    def inorder(node):
        if node:
            yield from inorder(node.left)
            yield node.value
            yield from inorder(node.right)

    values = set()
    for value in inorder(root):
        if target - value in values:
            return True
        values.add

(value)

    return False
```

## Priority Queues & Heaps - 7

### Priority Queues & Heaps in Python

**Introduction:**

**Priority Queues:**

- **Definition:** A priority queue is an abstract data type where each element is associated with a priority. Elements with higher priority are served before elements with lower priority.
- **Operations:**
    - **Insertion:** Add an element with a specified priority.
    - **Deletion:** Remove the element with the highest priority.
    - **Peek:** View the element with the highest priority without removing it.
- **Applications:** Used in algorithms like Dijkstra’s shortest path, Huffman coding, and scheduling tasks where certain tasks need to be executed before others.

**Heaps:**

- **Definition:** A heap is a specialized tree-based data structure that satisfies the heap property. In a min-heap, the parent node is less than or equal to its children, while in a max-heap, the parent node is greater than or equal to its children.
- **Types:**
    - **Min-Heap:** The root node has the minimum value, and every parent node is smaller than its children.
    - **Max-Heap:** The root node has the maximum value, and every parent node is larger than its children.
- **Operations:**
    - **Insertion:** Add a new element to the heap while maintaining the heap property. This usually involves adding the element at the end and then "bubbling up" to restore the heap property.
    - **Deletion:** Remove the root element (minimum in a min-heap, maximum in a max-heap), replace it with the last element, and then "heapify" to maintain the heap property.
    - **Peek:** Retrieve the root element without removing it.
- **Applications:** Heaps are used in implementing priority queues, heap sort, and algorithms like Dijkstra’s shortest path and Prim’s Minimum Spanning Tree.

**Key Differences:**

- **Priority Queues:** Abstract concept for managing elements with associated priorities. Can be implemented using heaps, but not limited to them.
- **Heaps:** Concrete data structures that maintain specific ordering properties (min-heap or max-heap). They provide efficient operations for priority queue operations.

**Example:**

In Python, the `heapq` module provides an implementation of a min-heap. It includes functions like `heappush` for insertion and `heappop` for deletion. For a max-heap, values can be negated or custom implementations can be used.

Heaps and priority queues are critical for efficiently managing and processing elements based on their priorities, making them useful in various computational problems and algorithms.

### 1. Implement Priority Queue

A priority queue is implemented using a heap. In Python, the `heapq` module can be used.

```python
import heapq

class PriorityQueue:
    def __init__(self):
        self.heap = []

    def push(self, item, priority):
        heapq.heappush(self.heap, (priority, item))

    def pop(self):
        return heapq.heappop(self.heap)[1]

    def is_empty(self):
        return len(self.heap) == 0

```

### 2. Convert Min Heap to Max Heap

To convert a min-heap to a max-heap, you can use a method where you convert the min-heap into a max-heap using the `heapq` module.

```python
import heapq

def convert_min_to_max_heap(min_heap):
    max_heap = [-x for x in min_heap]
    heapq.heapify(max_heap)
    return max_heap

# Example usage
min_heap = [1, 3, 5, 7, 9, 2, 4]
max_heap = convert_min_to_max_heap(min_heap)
print([-x for x in max_heap])  # To print max-heap as positive numbers

```

### 3. Kth Smallest & Largest Element

Find the Kth smallest and largest element in an array.

```python
import heapq

def kth_smallest(arr, k):
    return heapq.nsmallest(k, arr)[-1]

def kth_largest(arr, k):
    return heapq.nlargest(k, arr)[-1]

```

### 4. Kth Largest Sum Subarray

Find the Kth largest sum of any subarray.

```python
import heapq

def kth_largest_sum_subarray(arr, k):
    n = len(arr)
    sums = []
    for i in range(n):
        current_sum = 0
        for j in range(i, n):
            current_sum += arr[j]
            if len(sums) < k:
                heapq.heappush(sums, current_sum)
            else:
                heapq.heappushpop(sums, current_sum)
    return sums[0]

```

### 5. Merge K Sorted Arrays

Merge K sorted arrays into a single sorted array.

```python
import heapq

def merge_k_sorted_arrays(arrays):
    min_heap = []
    for i, array in enumerate(arrays):
        if array:
            heapq.heappush(min_heap, (array[0], i, 0))

    result = []
    while min_heap:
        value, array_idx, element_idx = heapq.heappop(min_heap)
        result.append(value)
        if element_idx + 1 < len(arrays[array_idx]):
            heapq.heappush(min_heap, (arrays[array_idx][element_idx + 1], array_idx, element_idx + 1))

    return result

```

### 6. Running Median

Find the running median of a list of numbers.

```python
import heapq

class RunningMedian:
    def __init__(self):
        self.min_heap = []
        self.max_heap = []

    def add_number(self, num):
        if len(self.max_heap) == 0 or num <= -self.max_heap[0]:
            heapq.heappush(self.max_heap, -num)
        else:
            heapq.heappush(self.min_heap, num)

        if len(self.max_heap) > len(self.min_heap) + 1:
            heapq.heappush(self.min_heap, -heapq.heappop(self.max_heap))
        elif len(self.min_heap) > len(self.max_heap):
            heapq.heappush(self.max_heap, -heapq.heappop(self.min_heap))

    def get_median(self):
        if len(self.max_heap) > len(self.min_heap):
            return -self.max_heap[0]
        return (-self.max_heap[0] + self.min_heap[0]) / 2

```

### 7. Connect n Ropes with Minimum Cost

Find the minimum cost to connect n ropes with minimum cost.

```python
import heapq

def connect_ropes(ropes):
    heapq.heapify(ropes)
    cost = 0
    while len(ropes) > 1:
        first = heapq.heappop(ropes)
        second = heapq.heappop(ropes)
        current_cost = first + second
        cost += current_cost
        heapq.heappush(ropes, current_cost)
    return cost
```

## Advanced Recursion & Backtracking - 8

### Advanced Recursion & Backtracking in Python

**Introduction:**

**Recursion:**

- **Definition:** Recursion is a programming technique where a function calls itself in order to solve a problem. It is useful for problems that can be divided into similar sub-problems.
- **Base Case and Recursive Case:**
    - **Base Case:** The condition under which the recursion stops, preventing infinite loops.
    - **Recursive Case:** The part where the function calls itself with modified parameters to approach the base case.
- **Applications:** Commonly used in algorithms such as tree traversals, generating permutations, and solving problems that can be broken down into smaller instances.

**Backtracking:**

- **Definition:** Backtracking is an algorithmic technique for finding all (or some) solutions to problems incrementally, by trying partial solutions and then abandoning them if they are not viable. It explores all potential solutions by building incrementally and backtracking when a solution path is not feasible.
- **Approach:**
    - **Choice:** Make a choice at each step and move to the next step.
    - **Constraint:** Ensure the choice meets problem constraints.
    - **Backtrack:** If the choice does not lead to a solution, undo the choice and try the next one.
- **Applications:** Used in problems like puzzles (e.g., Sudoku), pathfinding (e.g., maze solving), and combinatorial problems (e.g., N-Queens).

**Key Techniques:**

- **Combination Generation:** Generate all possible combinations or subsets of a set of elements.
- **Permutations:** Generate all possible arrangements of a set of elements.
- **Constraint Satisfaction:** Solve problems where solutions must satisfy specific constraints, such as placing N queens on a chessboard so that no two queens threaten each other.

**Examples:**

1. **N Queen Problem:**
    - **Problem:** Place N queens on an N×N chessboard so that no two queens attack each other.
    - **Approach:** Use backtracking to place queens one by one in different columns, checking for conflicts and backtracking when necessary.
2. **Sudoku Solver:**
    - **Problem:** Fill in a partially completed 9×9 Sudoku grid so that every row, column, and 3×3 sub-grid contains all digits from 1 to 9.
    - **Approach:** Use recursion and backtracking to fill cells, ensuring each move complies with Sudoku rules.
3. **Rat in a Maze:**
    - **Problem:** Find a path for a rat from the start to the destination in a maze.
    - **Approach:** Use recursive backtracking to explore all possible paths, marking cells as visited and backtracking when dead-ends are reached.

**Key Points:**

- **Efficiency:** While recursion and backtracking can solve complex problems, they may not always be the most efficient. It's important to consider optimization techniques to reduce unnecessary calculations.
- **Termination:** Properly define base cases and constraints to ensure termination and avoid infinite recursion.

Recursion and backtracking are powerful techniques that simplify complex problem-solving by breaking down problems into manageable sub-problems and systematically exploring potential solutions.

### 1. N Queen Problem

The N Queen problem involves placing N queens on an N x N chessboard so that no two queens attack each other.

```python
def solve_n_queens(n):
    def is_valid(board, row, col):
        for i in range(row):
            if board[i] == col or \\
               board[i] - i == col - row or \\
               board[i] + i == col + row:
                return False
        return True

    def solve(row):
        if row == n:
            result.append(board[:])
            return
        for col in range(n):
            if is_valid(board, row, col):
                board[row] = col
                solve(row + 1)
                board[row] = -1

    result = []
    board = [-1] * n
    solve(0)
    return result

# Example usage
print(solve_n_queens(4))

```

### 2. Sudoku Solver

Solve a Sudoku puzzle by filling in empty cells.

```python
def solve_sudoku(board):
    def is_valid(board, row, col, num):
        for i in range(9):
            if board[row][i] == num or board[i][col] == num:
                return False
        start_row, start_col = 3 * (row // 3), 3 * (col // 3)
        for i in range(start_row, start_row + 3):
            for j in range(start_col, start_col + 3):
                if board[i][j] == num:
                    return False
        return True

    def solve():
        for row in range(9):
            for col in range(9):
                if board[row][col] == 0:
                    for num in range(1, 10):
                        if is_valid(board, row, col, num):
                            board[row][col] = num
                            if solve():
                                return True
                            board[row][col] = 0
                    return False
        return True

    solve()
    return board

# Example usage
board = [
    [5, 3, 0, 0, 7, 0, 0, 0, 0],
    [6, 0, 0, 1, 9, 5, 0, 0, 0],
    [0, 9, 8, 0, 0, 0, 0, 6, 0],
    [8, 0, 0, 0, 6, 0, 0, 0, 3],
    [4, 0, 0, 8, 0, 3, 0, 0, 1],
    [7, 0, 0, 0, 2, 0, 0, 0, 6],
    [0, 6, 0, 0, 0, 0, 2, 8, 0],
    [0, 0, 0, 4, 1, 9, 0, 0, 5],
    [0, 0, 0, 0, 8, 0, 0, 7, 9]
]
print(solve_sudoku(board))

```

### 3. Rat in a Maze

Find a path for a rat to reach the destination in a maze.

```python
def rat_in_a_maze(maze):
    def is_valid(x, y):
        return 0 <= x < len(maze) and 0 <= y < len(maze[0]) and maze[x][y] == 1

    def solve(x, y):
        if x == len(maze) - 1 and y == len(maze[0]) - 1:
            path[x][y] = 1
            return True
        if is_valid(x, y):
            path[x][y] = 1
            if solve(x + 1, y) or solve(x, y + 1):
                return True
            path[x][y] = 0
        return False

    path = [[0] * len(maze[0]) for _ in range(len(maze))]
    solve(0, 0)
    return path

# Example usage
maze = [
    [1, 0, 0, 0],
    [1, 1, 0, 1],
    0, 1, 0, 0],
    [1, 1, 1, 1]
]
print(rat_in_a_maze(maze))

```

### 4. Letter Combinations Of Phone Number

Generate all possible letter combinations for a phone number.

```python
from typing import List

def letter_combinations(digits: str) -> List[str]:
    if not digits:
        return []

    digit_to_char = {
        '2': 'abc', '3': 'def', '4': 'ghi',
        '5': 'jkl', '6': 'mno', '7': 'pqrs',
        '8': 'tuv', '9': 'wxyz'
    }

    def backtrack(index, path):
        if index == len(digits):
            combinations.append("".join(path))
            return
        for char in digit_to_char[digits[index]]:
            path.append(char)
            backtrack(index + 1, path)
            path.pop()

    combinations = []
    backtrack(0, [])
    return combinations

# Example usage
print(letter_combinations("23"))

```

### 5. Subsequences of String

Generate all subsequences of a given string.

```python
def subsequences(s: str):
    result = []

    def backtrack(start, path):
        result.append("".join(path))
        for i in range(start, len(s)):
            path.append(s[i])
            backtrack(i + 1, path)
            path.pop()

    backtrack(0, [])
    return result

# Example usage
print(subsequences("abc"))

```

### 6. Combination Sum

Find all combinations of numbers that add up to a target sum.

```python
def combination_sum(candidates, target):
    def backtrack(start, path, target):
        if target == 0:
            result.append(path[:])
            return
        if target < 0:
            return
        for i in range(start, len(candidates)):
            path.append(candidates[i])
            backtrack(i, path, target - candidates[i])
            path.pop()

    result = []
    backtrack(0, [], target)
    return result

# Example usage
print(combination_sum([2, 3, 6, 7], 7))

```

### 7. Print Permutations

Print all permutations of a string.

```python
def permute(s: str):
    def backtrack(start):
        if start == len(s):
            result.append("".join(s))
            return
        for i in range(start, len(s)):
            s[start], s[i] = s[i], s[start]
            backtrack(start + 1)
            s[start], s[i] = s[i], s[start]

    result = []
    s = list(s)
    backtrack(0)
    return result

# Example usage
print(permute("abc"))

```

### 8. Restore IP Addresses

Restore valid IP addresses from a string.

```python
def restore_ip_addresses(s: str):
    def backtrack(start, path):
        if len(path) == 4:
            if start == len(s):
                result.append(".".join(path))
            return
        for i in range(1, 4):
            if start + i > len(s):
                break
            segment = s[start:start + i]
            if (i > 1 and segment[0] == '0') or int(segment) > 255:
                continue
            path.append(segment)
            backtrack(start + i, path)
            path.pop()

    result = []
    backtrack(0, [])
    return result

# Example usage
print(restore_ip_addresses("25525511135"))
```

## Dynamic Programming - 15

### Dynamic Programming in Python

**Introduction:**

Dynamic Programming (DP) is an optimization technique used to solve problems by breaking them down into simpler subproblems and storing the results of these subproblems to avoid redundant computations. It is particularly useful for problems with overlapping subproblems and optimal substructure.

**Key Concepts:**

- **Overlapping Subproblems:** Subproblems are solved multiple times within a problem. By storing the results of these subproblems, we avoid redundant calculations and improve efficiency.
- **Optimal Substructure:** An optimal solution to the problem can be constructed from optimal solutions of its subproblems. This property allows for the use of recursive relationships to build solutions.

**Approaches:**

1. **Top-Down Approach (Memoization):**
    - **Definition:** Solve the problem recursively and store the results of subproblems in a table (memoization) to avoid redundant calculations.
    - **Usage:** Implemented using recursion with a cache (e.g., Python dictionaries or lists) to store intermediate results.
2. **Bottom-Up Approach (Tabulation):**
    - **Definition:** Solve the problem iteratively by solving all possible subproblems and building up solutions to the main problem using a table (tabulation).
    - **Usage:** Implemented using loops to fill in a DP table with results from smaller subproblems, eventually leading to the solution of the main problem.

**Common Problems and Techniques:**

1. **Fibonacci Sequence:**
    - **Problem:** Find the Nth Fibonacci number.
    - **Approach:** Use a DP table to store the results of Fibonacci numbers to avoid redundant calculations.
2. **Knapsack Problem:**
    - **Problem:** Given items with weights and values, determine the maximum value that can be obtained in a knapsack of capacity W.
    - **Approach:** Use a DP table to store maximum values for each capacity and update values based on including or excluding items.
3. **Longest Common Subsequence (LCS):**
    - **Problem:** Find the longest subsequence common to two sequences.
    - **Approach:** Use a 2D DP table to store lengths of LCS for substrings of the sequences.
4. **Edit Distance:**
    - **Problem:** Compute the minimum number of operations required to convert one string into another (insertions, deletions, substitutions).
    - **Approach:** Use a 2D DP table to store the minimum number of operations for substrings of the two strings.
5. **Matrix Chain Multiplication:**
    - **Problem:** Determine the optimal order of matrix multiplications to minimize the number of scalar multiplications.
    - **Approach:** Use a 2D DP table to store the minimum cost of multiplying matrices.

**Key Techniques:**

- **State Representation:** Define the state of the problem using parameters that represent subproblems.
- **Transition:** Determine the transition between states based on the problem's recursive relationship.
- **Initialization:** Properly initialize the DP table with base cases.
- **Iteration vs. Recursion:** Choose between bottom-up (iterative) and top-down (recursive) approaches based on problem requirements and constraints.

**Advantages:**

- **Efficiency:** Reduces time complexity by avoiding redundant computations.
- **Optimal Solutions:** Ensures that the solution is optimal by considering all possible subproblem solutions.

Dynamic Programming is a powerful technique for solving optimization problems efficiently by leveraging previously computed results. It requires careful problem formulation and understanding of subproblem relationships.

### 1. Count Ways to Reach Nth Stair

Count the number of ways to reach the nth stair given that you can take either 1 step or 2 steps.

```python
def count_ways_to_reach_nth_stair(n):
    if n <= 1:
        return 1
    dp = [0] * (n + 1)
    dp[0], dp[1] = 1, 1
    for i in range(2, n + 1):
        dp[i] = dp[i - 1] + dp[i - 2]
    return dp[n]

# Example usage
print(count_ways_to_reach_nth_stair(5))

```

### 2. House Robber

Determine the maximum amount of money that can be robbed without robbing two adjacent houses.

```python
def house_robber(nums):
    if not nums:
        return 0
    n = len(nums)
    if n == 1:
        return nums[0]
    dp = [0] * n
    dp[0], dp[1] = nums[0], max(nums[0], nums[1])
    for i in range(2, n):
        dp[i] = max(dp[i - 1], dp[i - 2] + nums[i])
    return dp[-1]

# Example usage
print(house_robber([2, 7, 9, 3, 1]))

```

### 3. Ways to Make Coin Change

Find the number of ways to make a given amount using a list of coins.

```python
def coin_change_ways(coins, amount):
    dp = [0] * (amount + 1)
    dp[0] = 1
    for coin in coins:
        for x in range(coin, amount + 1):
            dp[x] += dp[x - coin]
    return dp[amount]

# Example usage
print(coin_change_ways([1, 2, 5], 5))

```

### 4. Rod Cutting Problem

Find the maximum revenue you can obtain by cutting up a rod and selling the pieces.

```python
def rod_cutting(prices):
    n = len(prices)
    dp = [0] * (n + 1)
    for i in range(1, n + 1):
        for j in range(i):
            dp[i] = max(dp[i], prices[j] + dp[i - j - 1])
    return dp[n]

# Example usage
print(rod_cutting([1, 5, 8, 9, 10, 17, 17, 20, 24, 30]))

```

### 5. Minimum Jumps To Reach End

Find the minimum number of jumps required to reach the end of the array.

```python
def min_jumps_to_reach_end(nums):
    if len(nums) <= 1:
        return 0
    jumps = 0
    current_end = 0
    farthest = 0
    for i in range(len(nums) - 1):
        farthest = max(farthest, i + nums[i])
        if i == current_end:
            jumps += 1
            current_end = farthest
    return jumps

# Example usage
print(min_jumps_to_reach_end([2, 3, 1, 1, 2, 4, 2, 0, 1, 1]))

```

### 6. Minimum Steps to Reach Target by Knight

Find the minimum number of moves required for a knight to reach a target position from a starting position on a chessboard.

```python
from collections import deque

def min_steps_knight(start, target):
    moves = [(2, 1), (1, 2), (-1, 2), (-2, 1), (-2, -1), (-1, -2), (1, -2), (2, -1)]
    queue = deque([(start[0], start[1, 0)])
    visited = set()
    visited.add(start)
    steps = 0
    while queue:
        for _ in range(len(queue)):
            x, y = queue.popleft()
            if (x, y) == target:
                return steps
            for move in moves:
                nx, ny = x + move[0], y + move[1]
                if 0 <= nx < 8 and 0 <= ny < 8 and (nx, ny) not in visited:
                    visited.add((nx, ny))
                    queue.append((nx, ny))
        steps += 1
    return -1

# Example usage
print(min_steps_knight((0, 0), (7, 7)))

```

### 7. Longest Increasing Subsequence

Find the length of the longest increasing subsequence in an array.

```python
def longest_increasing_subsequence(nums):
    if not nums:
        return 0
    dp = [1] * len(nums)
    for i in range(1, len(nums)):
        for j in range(i):
            if nums[i] > nums[j]:
                dp[i] = max(dp[i], dp[j] + 1)
    return max(dp)

# Example usage
print(longest_increasing_subsequence([10, 9, 2, 5, 3, 7, 101, 18]))

```

### 8. Longest Common Subsequence

Find the length of the longest common subsequence between two strings.

```python
def longest_common_subsequence(text1, text2):
    m, n = len(text1), len(text2)
    dp = [[0] * (n + 1) for _ in range(m + 1)]
    for i in range(1, m + 1):
        for j in range(1, n + 1):
            if text1[i - 1] == text2[j - 1]:
                dp[i][j] = dp[i - 1][j - 1] + 1
            else:
                dp[i][j] = max(dp[i - 1][j], dp[i][j - 1])
    return dp[m][n]

# Example usage
print(longest_common_subsequence("abcde", "ace"))

```

### 9. Edit Distance

Find the minimum number of operations required to convert one string into another.

```python
def edit_distance(word1, word2):
    m, n = len(word1), len(word2)
    dp = [[0] * (n + 1) for _ in range(m + 1)]
    for i in range(m + 1):
        for j in range(n + 1):
            if i == 0:
                dp[i][j] = j
            elif j == 0:
                dp[i][j] = i
            elif word1[i - 1] == word2[j - 1]:
                dp[i][j] = dp[i - 1][j - 1]
            else:
                dp[i][j] = 1 + min(dp[i - 1][j], dp[i][j - 1], dp[i - 1][j - 1])
    return dp[m][n]

# Example usage
print(edit_distance("intention", "execution"))

```

### 10. Interleaving Two Strings

Check if a string can be formed by interleaving two other strings.

```python
def is_interleave(s1, s2, s3):
    if len(s1) + len(s2) != len(s3):
        return False
    dp = [[False] * (len(s2) + 1) for _ in range(len(s1) + 1)]
    dp[0][0] = True
    for i in range(1, len(s1) + 1):
        dp[i][0] = dp[i - 1][0] and s1[i - 1] == s3[i - 1]
    for j in range(1, len(s2) + 1):
        dp[0][j] = dp[0][j - 1] and s2[j - 1] == s3[j - 1]
    for i in range(1, len(s1) + 1):
        for j in range(1, len(s2) + 1):
            dp[i][j] = (dp[i - 1][j] and s1[i - 1] == s3[i + j - 1]) or \\
                       (dp[i][j - 1] and s2[j - 1] == s3[i + j - 1])
    return dp[len(s1)][len(s2)]

# Example usage
print(is_interleave("aabcc", "dbbca", "aadbbcbcac"))

```

### 11. Minimum Deletions

Find the minimum number of deletions required to make a string a palindrome.

```python
def min_deletions_to_palindrome(s):
    def longest_palindromic_subsequence(s):
        n = len(s)
        dp = [[0] * n for _ in range(n)]
        for i in range(n):
            dp[i][i] = 1
        for cl in range(2, n + 1):
            for i in range(n - cl + 1):
                j = i + cl - 1
                if s[i] == s[j] and cl == 2:
                    dp[i][j] = 2
                elif s

[i] == s[j]:
                    dp[i][j] = dp[i + 1][j - 1] + 2
                else:
                    dp[i][j] = max(dp[i][j - 1], dp[i + 1][j])
        return dp[0][n - 1]

    return len(s) - longest_palindromic_subsequence(s)

# Example usage
print(min_deletions_to_palindrome("abcb"))

```

### 12. 0-1 Knapsack

Solve the knapsack problem where you can either include or exclude an item.

```python
def knapsack(weights, values, capacity):
    n = len(weights)
    dp = [0] * (capacity + 1)
    for i in range(n):
        for w in range(capacity, weights[i] - 1, -1):
            dp[w] = max(dp[w], dp[w - weights[i]] + values[i])
    return dp[capacity]

# Example usage
print(knapsack([1, 2, 3], [10, 15, 40], 6))

```

### 13. Best Time to Buy and Sell Stock

Find the maximum profit you can achieve from buying and selling a stock.

```python
def best_time_to_buy_and_sell_stock(prices):
    min_price = float('inf')
    max_profit = 0
    for price in prices:
        min_price = min(min_price, price)
        max_profit = max(max_profit, price - min_price)
    return max_profit

# Example usage
print(best_time_to_buy_and_sell_stock([7, 1, 5, 3, 6, 4]))

```

### 14. Matrix Chain Multiplication

Find the minimum cost to multiply a chain of matrices.

```python
def matrix_chain_multiplication(p):
    n = len(p) - 1
    dp = [[float('inf')] * n for _ in range(n)]
    for i in range(n):
        dp[i][i] = 0
    for length in range(2, n + 1):
        for i in range(n - length + 1):
            j = i + length - 1
            for k in range(i, j):
                dp[i][j] = min(dp[i][j], dp[i][k] + dp[k + 1][j] + p[i] * p[k + 1] * p[j + 1])
    return dp[0][n - 1]

# Example usage
print(matrix_chain_multiplication([10, 20, 30, 40, 30]))

```

### 15. Partition Equal Subset Sum

Determine if you can partition a set into two subsets with equal sum.

```python
def can_partition(nums):
    total = sum(nums)
    if total % 2 != 0:
        return False
    target = total // 2
    dp = [False] * (target + 1)
    dp[0] = True
    for num in nums:
        for j in range(target, num - 1, -1):
            dp[j] = dp[j] or dp[j - num]
    return dp[target]

# Example usage
print(can_partition([1, 5, 11, 5]))
```

## Graphs - 13

### Graphs in Python

**Introduction:**

Graphs are fundamental data structures used to represent relationships between entities. They consist of vertices (nodes) and edges (connections between nodes). Graphs are used in various applications, such as social networks, routing algorithms, and network analysis.

**Key Concepts:**

1. **Vertices (Nodes):** Represent the entities in the graph.
2. **Edges:** Represent the connections or relationships between vertices. Edges can be directed (one-way) or undirected (two-way).
3. **Weight:** Edges may have weights representing costs, distances, or other metrics.

**Types of Graphs:**

1. **Undirected Graphs:** Edges have no direction; the relationship is bidirectional.
2. **Directed Graphs (Digraphs):** Edges have direction; the relationship is one-way.
3. **Weighted Graphs:** Edges have weights or costs associated with them.
4. **Unweighted Graphs:** Edges have no weights; they represent simple connections.
5. **Cyclic Graphs:** Graphs that contain at least one cycle (a path that starts and ends at the same vertex).
6. **Acyclic Graphs:** Graphs with no cycles.

**Graph Representation:**

1. **Adjacency Matrix:**
    - **Definition:** A 2D array where the cell at (i, j) represents the presence (and weight) of an edge between vertices i and j.
    - **Usage:** Useful for dense graphs but can be memory-intensive.
2. **Adjacency List:**
    - **Definition:** An array of lists where each index represents a vertex, and the list at that index contains the adjacent vertices.
    - **Usage:** Efficient for sparse graphs and requires less memory compared to an adjacency matrix.

**Common Graph Algorithms:**

1. **Depth-First Search (DFS):**
    - **Definition:** A traversal algorithm that explores as far as possible along each branch before backtracking.
    - **Applications:** Pathfinding, topological sorting, cycle detection.
    - **Implementation:** Uses recursion or a stack.
2. **Breadth-First Search (BFS):**
    - **Definition:** A traversal algorithm that explores all neighbors of a vertex before moving to the next level of vertices.
    - **Applications:** Shortest path in unweighted graphs, level-order traversal, finding connected components.
    - **Implementation:** Uses a queue.
3. **Dijkstra’s Algorithm:**
    - **Definition:** Finds the shortest path from a source vertex to all other vertices in a weighted graph with non-negative weights.
    - **Applications:** Routing, network optimization.
    - **Implementation:** Uses a priority queue (min-heap).
4. **Kruskal’s Algorithm:**
    - **Definition:** Finds the Minimum Spanning Tree (MST) of a graph by adding edges in ascending order of weights and ensuring no cycles are formed.
    - **Applications:** Network design, clustering.
    - **Implementation:** Uses a Disjoint Set Union (DSU) data structure.
5. **Prim’s Algorithm:**
    - **Definition:** Another algorithm to find the Minimum Spanning Tree (MST) by expanding a growing spanning tree.
    - **Applications:** Network design, optimization problems.
    - **Implementation:** Uses a priority queue.
6. **Topological Sort:**
    - **Definition:** Orders vertices of a Directed Acyclic Graph (DAG) such that for every directed edge (u, v), vertex u comes before vertex v.
    - **Applications:** Task scheduling, course prerequisites.
    - **Implementation:** Uses DFS or Kahn’s Algorithm (BFS).
7. **Bellman-Ford Algorithm:**
    - **Definition:** Finds the shortest path from a source vertex to all other vertices in a graph, even with negative weights.
    - **Applications:** Detecting negative weight cycles, shortest path in graphs with negative weights.
8. **Floyd-Warshall Algorithm:**
    - **Definition:** Finds the shortest paths between all pairs of vertices in a graph.
    - **Applications:** Network analysis, finding shortest paths between multiple pairs of vertices.

**Graph Representation in Python:**

- **Adjacency Matrix:** Implemented using a 2D list or array.
- **Adjacency List:** Implemented using a dictionary of lists.

**Advantages:**

- **Versatility:** Can model various real-world problems.
- **Efficiency:** Algorithms like Dijkstra’s and Kruskal’s can solve complex problems efficiently.
- **Flexibility:** Can handle different types of graphs and edge weights.

Graphs are essential for solving problems involving relationships and paths. Understanding how to represent and manipulate graphs effectively is crucial for designing algorithms and solving real-world problems.

### 1. Largest Island

Find the area of the largest island in a grid where `1` represents land and `0` represents water.

```python
def largest_island(grid):
    def dfs(x, y):
        if 0 <= x < len(grid) and 0 <= y < len(grid[0]) and grid[x][y] == 1:
            grid[x][y] = 0
            area = 1
            for dx, dy in [(-1, 0), (1, 0), (0, -1), (0, 1)]:
                area += dfs(x + dx, y + dy)
            return area
        return 0

    max_area = 0
    for i in range(len(grid)):
        for j in range(len(grid[0])):
            if grid[i][j] == 1:
                max_area = max(max_area, dfs(i, j))
    return max_area

# Example usage
print(largest_island([[1, 0, 0, 0], [0, 1, 1, 0], [0, 1, 0, 0], [0, 0, 0, 1]]))

```

### 2. Is Graph a Tree?

Check if a given graph is a tree. A tree is a connected acyclic graph.

```python
def is_graph_a_tree(n, edges):
    from collections import defaultdict, deque

    def bfs(start):
        queue = deque([start])
        visited = set([start])
        while queue:
            node = queue.popleft()
            for neighbor in graph[node]:
                if neighbor not in visited:
                    visited.add(neighbor)
                    queue.append(neighbor)
        return visited

    graph = defaultdict(set)
    for u, v in edges:
        graph[u].add(v)
        graph[v].add(u)

    visited = bfs(0)

    if len(visited) != n:
        return False

    edge_count = sum(len(neighbors) for neighbors in graph.values()) // 2
    return edge_count == n - 1

# Example usage
print(is_graph_a_tree(5, [(0, 1), (1, 2), (2, 3), (3, 4)]))

```

### 3. Snake & Ladder Problem

Find the minimum number of dice throws required to reach the end of a board.

```python
from collections import deque

def snake_and_ladder(board):
    n = len(board)
    moves = [1, 2, 3, 4, 5, 6]
    visited = [False] * n
    queue = deque([(0, 0)])  # (position, distance)
    visited[0] = True

    while queue:
        position, distance = queue.popleft()
        if position == n - 1:
            return distance
        for move in moves:
            next_position = position + move
            if next_position < n:
                if board[next_position] != -1:
                    next_position = board[next_position]
                if not visited[next_position]:
                    visited[next_position] = True
                    queue.append((next_position, distance + 1))
    return -1

# Example usage
print(snake_and_ladder([-1, 4, -1, -1, -1, 2, -1, 8, -1, -1, 0]))

```

### 4. Shortest Path in Binary Matrix

Find the shortest path from the top-left to the bottom-right corner in a binary matrix.

```python
from collections import deque

def shortest_path_binary_matrix(grid):
    if grid[0][0] == 1 or grid[-1][-1] == 1:
        return -1

    n = len(grid)
    directions = [(-1, 0), (1, 0), (0, -1), (0, 1), (-1, -1), (-1, 1), (1, -1), (1, 1)]
    queue = deque([(0, 0, 1)])  # (x, y, distance)

    while queue:
        x, y, dist = queue.popleft()
        if x == n - 1 and y == n - 1:
            return dist
        for dx, dy in directions:
            nx, ny = x + dx, y + dy
            if 0 <= nx < n and 0 <= ny < n and grid[nx][ny] == 0:
                grid[nx][ny] = 1
                queue.append((nx, ny, dist + 1))
    return -1

# Example usage
print(shortest_path_binary_matrix([[0, 1, 0], [1, 0, 1], [0, 0, 0]]))

```

### 5. Dijkstra’s Algorithm

Find the shortest paths from a source node to all other nodes in a graph.

```python
import heapq

def dijkstra(graph, start):
    n = len(graph)
    distances = [float('inf')] * n
    distances[start] = 0
    min_heap = [(0, start)]

    while min_heap:
        current_distance, u = heapq.heappop(min_heap)
        if current_distance > distances[u]:
            continue
        for v, weight in graph[u]:
            distance = current_distance + weight
            if distance < distances[v]:
                distances[v] = distance
                heapq.heappush(min_heap, (distance, v))
    return distances

# Example usage
graph = {0: [(1, 4), (2, 1)], 1: [(2, 2), (3, 5)], 2: [(1, 2), (3, 8), (4, 10)], 3: [(4, 2)], 4: []}
print(dijkstra(graph, 0))

```

### 6. MST Using Prim’s Algorithm (With Priority Queue)

Find the Minimum Spanning Tree (MST) of a graph using Prim’s Algorithm.

```python
import heapq

def prim_mst(graph):
    n = len(graph)
    min_heap = [(0, 0)]  # (weight, node)
    visited = [False] * n
    mst_weight = 0
    edges_count = 0

    while min_heap:
        weight, u = heapq.heappop(min_heap)
        if visited[u]:
            continue
        visited[u] = True
        mst_weight += weight
        edges_count += 1
        if edges_count == n:
            break
        for v, edge_weight in graph[u]:
            if not visited[v]:
                heapq.heappush(min_heap, (edge_weight, v))

    return mst_weight

# Example usage
graph = {0: [(1, 4), (2, 1)], 1: [(0, 4), (2, 2), (3, 5)], 2: [(0, 1), (1, 2), (3, 8), (4, 10)], 3: [(1, 5), (2, 8), (4, 2)], 4: [(2, 10), (3, 2)]}
print(prim_mst(graph))

```

### 7. MST Using Kruskal's Algorithm (With Disjoint Set Union)

Find the Minimum Spanning Tree (MST) using Kruskal's Algorithm.

```python
def kruskal_mst(n, edges):
    parent = list(range(n))
    rank = [0] * n

    def find(x):
        if parent[x] != x:
            parent[x] = find(parent[x])
        return parent[x]

    def union(x, y):
        rootX, rootY = find(x), find(y)
        if rootX != rootY:
            if rank[rootX] > rank[rootY]:
                parent[rootY] = rootX
            elif rank[rootX] < rank[rootY]:
                parent[rootX] = rootY
            else:
                parent[rootY] = rootX
                rank[rootX] += 1

    edges.sort(key=lambda x: x[2])
    mst_weight = 0
    for u, v, weight in edges:
        if find(u) != find(v):
            union(u, v)
            mst_weight += weight

    return mst_weight

# Example usage
edges = [(0, 1, 4), (0, 2, 1), (1, 2, 2), (1, 3, 5), (2, 3, 8), (2, 4, 10), (3, 4, 2)]
print(kruskal_mst(5, edges))

```

### 8. Topological Sort

Perform a topological sort of a directed acyclic graph (DAG).

```python
from collections import deque, defaultdict

def topological_sort(n, edges):
    in_degree = [0] * n
    graph = defaultdict(list)

    for u, v in edges:
        graph[u].append(v)
        in_degree[v] += 1

    queue = deque([i for i in range(n) if in_degree[i] == 0])
    top_order = []

    while queue:
        u = queue.popleft()
        top_order.append(u)
        for v in graph[u]:
            in_degree[v] -= 1
            if in_degree[v] == 0:

                queue.append(v)

    return top_order if len(top_order) == n else []

# Example usage
print(topological_sort(6, [(5, 2), (5, 0), (4, 0), (4, 1), (2, 3), (3, 1)]))

```

### 9. M Coloring Problem

Determine if a graph can be colored with `m` colors such that no two adjacent nodes have the same color.

```python
def is_m_colorable(graph, m):
    def can_color(node, color):
        for neighbor in graph[node]:
            if colors[neighbor] == color:
                return False
        return True

    def graph_coloring(node):
        if node == len(graph):
            return True
        for color in range(1, m + 1):
            if can_color(node, color):
                colors[node] = color
                if graph_coloring(node + 1):
                    return True
                colors[node] = 0
        return False

    colors = [0] * len(graph)
    return graph_coloring(0)

# Example usage
graph = {0: [1, 2], 1: [0, 2], 2: [0, 1]}
print(is_m_colorable(graph, 3))

```

### 10. Detect Cycle in Directed Graph

Check if there is a cycle in a directed graph.

```python
def detect_cycle_in_directed_graph(n, edges):
    def dfs(node):
        if status[node] == 1:
            return True
        if status[node] == 2:
            return False
        status[node] = 1
        for neighbor in graph[node]:
            if dfs(neighbor):
                return True
        status[node] = 2
        return False

    graph = defaultdict(list)
    for u, v in edges:
        graph[u].append(v)

    status = [0] * n
    for node in range(n):
        if status[node] == 0 and dfs(node):
            return True
    return False

# Example usage
print(detect_cycle_in_directed_graph(4, [(0, 1), (1, 2), (2, 3), (3, 1)]))

```

### 11. Bipartite Check

Check if a graph is bipartite.

```python
def is_bipartite(graph):
    color = {}

    def bfs(start):
        queue = deque([start])
        color[start] = 0
        while queue:
            node = queue.popleft()
            for neighbor in graph[node]:
                if neighbor in color:
                    if color[neighbor] == color[node]:
                        return False
                else:
                    color[neighbor] = 1 - color[node]
                    queue.append(neighbor)
        return True

    for node in graph:
        if node not in color:
            if not bfs(node):
                return False
    return True

# Example usage
graph = {0: [1, 3], 1: [0, 2], 2: [1, 3], 3: [0, 2]}
print(is_bipartite(graph))

```

### 12. Bellman-Ford Algorithm

Find the shortest paths from a source node to all other nodes in a graph that may contain negative weights.

```python
def bellman_ford(n, edges, start):
    dist = [float('inf')] * n
    dist[start] = 0

    for _ in range(n - 1):
        for u, v, weight in edges:
            if dist[u] != float('inf') and dist[u] + weight < dist[v]:
                dist[v] = dist[u] + weight

    # Check for negative-weight cycles
    for u, v, weight in edges:
        if dist[u] != float('inf') and dist[u] + weight < dist[v]:
            return "Graph contains negative weight cycle"

    return dist

# Example usage
edges = [(0, 1, 4), (0, 2, 1), (1, 2, 2), (1, 3, 5), (2, 3, 8), (2, 4, 10), (3, 4, 2)]
print(bellman_ford(5, edges, 0))

```

### 13. Floyd-Warshall Algorithm

Find the shortest paths between all pairs of nodes in a graph.

```python
def floyd_warshall(n, edges):
    dist = [[float('inf')] * n for _ in range(n)]
    for i in range(n):
        dist[i][i] = 0

    for u, v, weight in edges:
        dist[u][v] = weight

    for k in range(n):
        for i in range(n):
            for j in range(n):
                dist[i][j] = min(dist[i][j], dist[i][k] + dist[k][j])

    return dist

# Example usage
edges = [(0, 1, 4), (0, 2, 1), (1, 2, 2), (1, 3, 5), (2, 3, 8), (2, 4, 10), (3, 4, 2)]
print(floyd_warshall(5, edges))
```

# Advanced Python

## Modules and Packages - 9

### Module

A **module** in Python is a file containing Python definitions and statements. Modules allow you to logically organize your Python code into different files and reuse them across multiple programs. Each Python file (.py) is considered a module, and you can import and use functions, classes, and variables defined in that module.

Example:

```python
# mymodule.py
def greet(name):
    return f"Hello, {name}!"

```

### Packages

A **package** is a way of organizing related modules into a directory hierarchy. A package is a directory containing a special `__init__.py` file and other modules or sub-packages. The `__init__.py` file can be empty or execute the package initialization code.

Example:

```
mypackage/
    __init__.py
    module1.py
    module2.py

```

To use a package:

```python
from mypackage import module1
from mypackage.module2 import function

```

### Importing Modules in Python

You can import modules using the `import` statement. You can import specific items from a module using the `from ... import ...` syntax.

Examples:

```python
import mymodule
print(mymodule.greet("Alice"))

from mymodule import greet
print(greet("Bob"))

import mymodule as mm
print(mm.greet("Charlie"))

```

### Difference between Modules and Packages

- **Module**: A single file containing Python code (e.g., `mymodule.py`).
- **Package**: A directory containing multiple modules and an `__init__.py` file to signify that it is a package (e.g., `mypackage/`).

### Libraries

A **library** is a collection of modules and packages. It provides reusable code and functionality that can be utilized by different programs. Libraries can be built-in or third-party. For example, the standard library includes modules like `math`, `os`, and `sys`.

### Math Module

The **math** module provides mathematical functions and constants.

Common functions:

- `math.sqrt(x)`: Returns the square root of `x`.
- `math.factorial(x)`: Returns the factorial of `x`.
- `math.pi`: Constant for the value of π.

Example:

```python
import math
print(math.sqrt(16))    # Output: 4.0
print(math.pi)          # Output: 3.141592653589793

```

### Collection Module

The **collections** module provides alternatives to built-in data types and additional data structures.

Common types:

- `collections.namedtuple()`: Factory function for creating tuple subclasses with named fields.
- `collections.deque()`: Double-ended queue for fast appends and pops from both ends.
- `collections.Counter()`: Counts hashable objects.

Example:

```python
from collections import namedtuple, deque, Counter

# namedtuple
Point = namedtuple('Point', ['x', 'y'])
p = Point(1, 2)
print(p.x, p.y)  # Output: 1 2

# deque
dq = deque([1, 2, 3])
dq.appendleft(0)
print(dq)  # Output: deque([0, 1, 2, 3])

# Counter
c = Counter('aabbcc')
print(c)  # Output: Counter({'a': 2, 'b': 2, 'c': 2})

```

### Time Module

The **time** module provides time-related functions.

Common functions:

- `time.time()`: Returns the current time in seconds since the epoch.
- `time.sleep(seconds)`: Delays execution for a given number of seconds.

Example:

```python
import time
print(time.time())       # Output: (current time in seconds since epoch)
time.sleep(1)            # Pauses execution for 1 second

```

### OS Module

The **os** module provides a way of using operating system-dependent functionality.

Common functions:

- `os.path.join(path, *paths)`: Join one or more path components.
- `os.listdir(path)`: List all entries in the given directory.
- `os.getenv(key, default=None)`: Get the value of an environment variable.

Example:

```python
import os

print(os.path.join('folder', 'file.txt'))  # Output: folder/file.txt
print(os.listdir('.'))                     # Output: List of files and directories in the current directory
print(os.getenv('HOME'))                   # Output: Path to the user's home directory
```

## Exception Handling - 9

### Exceptions and Errors

- **Errors**: Issues in code that prevent it from executing correctly. They include syntax errors (e.g., missing colons, wrong indentation) and runtime errors (e.g., division by zero).
- **Exceptions**: Special errors that can be caught and handled during runtime. They are typically raised when the code encounters a problem that it can’t handle naturally.

### What is Exception Handling

**Exception handling** is a programming construct that allows you to manage and respond to runtime errors, so the program can continue executing or fail gracefully. It involves using `try`, `except`, `else`, and `finally` blocks to manage exceptions.

### Try and Except Statement

The `try` block lets you test a block of code for errors. The `except` block lets you handle the error with a custom response.

Syntax:

```python
try:
    # Code that may raise an exception
    result = 10 / 0
except ZeroDivisionError:
    # Code to handle the exception
    print("Cannot divide by zero!")

```

### Built-in Exceptions

Python includes several built-in exceptions that cover common error conditions. Examples include:

- `ZeroDivisionError`: Raised when dividing by zero.
- `IndexError`: Raised when accessing an element out of range in a list.
- `KeyError`: Raised when accessing a dictionary with a non-existent key.
- `TypeError`: Raised when an operation is applied to an object of inappropriate type.

### Raising Exception

You can raise exceptions manually using the `raise` statement. This is useful when you want to signal that an error condition has occurred.

Syntax:

```python
def divide(x, y):
    if y == 0:
        raise ValueError("Cannot divide by zero.")
    return x / y

try:
    result = divide(10, 0)
except ValueError as e:
    print(e)  # Output: Cannot divide by zero.

```

### Multiple Exception Handling

You can handle multiple exceptions in a single `try` block by specifying multiple `except` blocks. Python will execute the first `except` block that matches the exception type.

Syntax:

```python
try:
    result = 10 / int(input("Enter a number: "))
except ZeroDivisionError:
    print("Cannot divide by zero!")
except ValueError:
    print("Invalid input. Please enter a number.")

```

### Handling TypeError Exception

The `TypeError` is raised when an operation or function is applied to an object of inappropriate type.

Example:

```python
try:
    result = "string" + 10
except TypeError:
    print("Cannot add a string and an integer!")

```

### Handling NameError Exception

The `NameError` is raised when a local or global name is not found.

Example:

```python
try:
    print(undefined_variable)
except NameError:
    print("Variable is not defined!")

```

### AttributeError

The `AttributeError` is raised when an invalid attribute reference is made. It indicates that an object does not possess the attribute you're trying to access.

Example:

```python
class MyClass:
    pass

obj = MyClass()
try:
    obj.some_method()
except AttributeError:
    print("Method does not exist on object!")
```

## File Handling - 5

### What is File Handling

**File handling** refers to the process of reading from and writing to files. It allows a program to interact with the file system, enabling the storage of data in files and retrieval of data from files.

### Reading from File

To read data from a file, you can use the `open()` function with the mode set to `'r'` (read mode). You can then use methods like `.read()`, `.readline()`, or `.readlines()` to access the file's contents.

**Example**:

```python
# Open file in read mode
with open('example.txt', 'r') as file:
    content = file.read()  # Read entire file
    print(content)

```

**Methods**:

- `.read()`: Reads the entire file content.
- `.readline()`: Reads a single line from the file.
- `.readlines()`: Reads all lines into a list.

### Writing to File

To write data to a file, use the `open()` function with the mode set to `'w'` (write mode). This will overwrite the existing file content or create a new file if it doesn’t exist.

**Example**:

```python
# Open file in write mode
with open('example.txt', 'w') as file:
    file.write("Hello, World!")  # Write data to file

```

**Note**: Using `'w'` mode will truncate the file to zero length if it already exists, so be cautious of overwriting important data.

### Appending to File

To add data to the end of a file without overwriting its existing content, use the `open()` function with the mode set to `'a'` (append mode).

**Example**:

```python
# Open file in append mode
with open('example.txt', 'a') as file:
    file.write("Appending a new line.\\n")  # Add data to the end of the file

```

### File Modes

Different modes for opening files in Python allow you to specify how you want to access the file:

- `'r'`: Read (default mode). Opens a file for reading only.
- `'w'`: Write. Opens a file for writing, truncating the file if it already exists.
- `'a'`: Append. Opens a file for appending, creating the file if it doesn’t exist.
- `'b'`: Binary. Used with other modes to handle binary files (e.g., `'rb'` or `'wb'`).
- `'x'`: Exclusive creation. Creates a new file, failing if the file already exists.

**Example**:

```python
# Open file in binary read mode
with open('example.bin', 'rb') as file:
    binary_data = file.read()  # Read binary data from file
```

## Multithreading - 6

### What is Multithreading

**Multithreading** is a technique where multiple threads run concurrently within a single process. Each thread operates independently, allowing tasks to be performed simultaneously, which can improve the efficiency of a program by utilizing CPU resources better.

### Thread in Python

In Python, threads are managed using the `threading` module. A thread is a separate flow of execution within a process, allowing multiple operations to run concurrently.

**Key Classes and Functions**:

- `threading.Thread`: A class that represents a thread.
- `threading.active_count()`: Returns the number of active threads.
- `threading.current_thread()`: Returns the current thread object.

**Example**:

```python
import threading

def print_numbers():
    for i in range(5):
        print(i)

# Create a new thread
thread = threading.Thread(target=print_numbers)
thread.start()  # Start the thread
thread.join()   # Wait for the thread to complete

```

### Creating New Thread

To create a new thread, you define a target function for the thread to execute. You then instantiate the `Thread` class with this target function and start the thread using the `.start()` method.

**Example**:

```python
import threading

def task():
    print("Thread is running")

# Instantiate a thread with the target function
thread = threading.Thread(target=task)
thread.start()  # Start the thread

```

### Thread-Based Parallelism

Thread-based parallelism allows different parts of a program to run in parallel, which can lead to more efficient execution, especially for I/O-bound tasks. However, Python’s Global Interpreter Lock (GIL) can limit the effectiveness of threads for CPU-bound tasks.

**Example**:

```python
import threading

def worker():
    print("Worker thread")

threads = []
for _ in range(5):
    thread = threading.Thread(target=worker)
    thread.start()
    threads.append(thread)

# Ensure all threads have completed
for thread in threads:
    thread.join()

```

### Handling Thread Exceptions

To handle exceptions in threads, you can use a try-except block within the thread’s target function. This ensures that exceptions are caught and managed appropriately without terminating the main program.

**Example**:

```python
import threading

def safe_task():
    try:
        # Code that might raise an exception
        raise ValueError("An error occurred")
    except Exception as e:
        print(f"Exception caught: {e}")

thread = threading.Thread(target=safe_task)
thread.start()
thread.join()

```

### Socket Programming with Multithreading

Multithreading can be used in socket programming to handle multiple client connections concurrently. Each client connection can be managed by a separate thread, allowing the server to process multiple requests simultaneously.

**Example**:

```python
import socket
import threading

def handle_client(client_socket):
    request = client_socket.recv(1024)
    print(f"Received: {request.decode()}")
    client_socket.send(b"ACK")
    client_socket.close()

server = socket.socket(socket.AF_INET, socket.SOCK_STREAM)
server.bind(('0.0.0.0', 9999))
server.listen(5)

print("Server listening...")
while True:
    client_sock, addr = server.accept()
    print(f"Accepted connection from {addr}")
    client_handler = threading.Thread(target=handle_client, args=(client_sock,))
    client_handler.start()
```

# Python Libraries

## Package Manager in Python - 3

### Libraries in Python

**Libraries** in Python are collections of modules that provide useful functions, classes, and variables to help perform specific tasks. They can be built-in, provided by the Python Standard Library, or third-party libraries available from various sources.

- **Standard Libraries**: Included with Python and provide core functionality (e.g., `math`, `datetime`, `json`).
- **Third-Party Libraries**: Developed by the community and can be installed via package managers (e.g., `requests`, `numpy`, `pandas`).

**Example**:

```python
import math

# Use the math library to calculate square root
print(math.sqrt(16))  # Output: 4.0

```

### PIP in Python

**PIP** (Python Package Installer) is the package management system used to install and manage Python packages from the Python Package Index (PyPI).

- **Install a Package**: `pip install package_name`
- **Upgrade a Package**: `pip install --upgrade package_name`
- **Uninstall a Package**: `pip uninstall package_name`
- **List Installed Packages**: `pip list`
- **Show Package Information**: `pip show package_name`

**Example**:

```
# Install the 'requests' package
pip install requests

# Check installed packages
pip list

# Upgrade 'requests' to the latest version
pip install --upgrade requests

```

### Import in Python

**Importing** is how you use functions, classes, and variables from other modules or libraries in your Python code. There are various ways to import:

- **Import the entire module**:
    
    ```python
    import math
    print(math.sqrt(25))  # Output: 5.0
    
    ```
    
- **Import specific functions or classes**:
    
    ```python
    from math import sqrt
    print(sqrt(25))  # Output: 5.0
    
    ```
    
- **Import with an alias**:
    
    ```python
    import numpy as np
    print(np.array([1, 2, 3]))
    
    ```
    
- **Import all names from a module** (not recommended for large modules):
    
    ```python
    from math import *
    print(sqrt(25))  # Output: 5.0
    ```
    

## Numpy - 13

### Installing Numpy

To use Numpy, you first need to install it. Numpy is a popular library for numerical computations in Python.

- **Installation**: Use pip to install Numpy.
    
    ```
    pip install numpy
    
    ```
    

### Basic Operations

Numpy supports a wide range of mathematical operations, including addition, subtraction, multiplication, and division, all performed element-wise.

**Example**:

```python
import numpy as np

a = np.array([1, 2, 3])
b = np.array([4, 5, 6])

# Basic operations
print(a + b)  # Output: [5 7 9]
print(a * b)  # Output: [ 4 10 18]

```

### Numpy Datatypes

Numpy arrays can hold elements of different data types such as integers, floats, and complex numbers. The `dtype` attribute is used to get the data type of the array.

**Example**:

```python
import numpy as np

arr = np.array([1, 2, 3], dtype=float)
print(arr.dtype)  # Output: float64

```

### Numpy Array Creation

Arrays can be created from lists or tuples, or by using built-in functions.

**Example**:

```python
import numpy as np

# From list
arr1 = np.array([1, 2, 3])

# From tuple
arr2 = np.array((4, 5, 6))

# Using built-in functions
zeros = np.zeros((3, 3))  # 3x3 matrix of zeros
ones = np.ones((2, 2))    # 2x2 matrix of ones

```

### Slicing and Indexing in Numpy

Numpy arrays support slicing and indexing similar to Python lists, but with additional functionality.

**Example**:

```python
import numpy as np

arr = np.array([1, 2, 3, 4, 5])

# Indexing
print(arr[2])  # Output: 3

# Slicing
print(arr[1:4])  # Output: [2 3 4]

```

### Numpy Reshape

You can change the shape of an array using the `reshape` method without changing the data.

**Example**:

```python
import numpy as np

arr = np.arange(12)
reshaped_arr = arr.reshape((3, 4))
print(reshaped_arr)

```

### Numpy Iteration

Numpy arrays can be iterated over using loops.

**Example**:

```python
import numpy as np

arr = np.array([1, 2, 3])

for element in arr:
    print(element)

```

### Numpy String Functions

Numpy provides functions for string operations on arrays.

**Example**:

```python
import numpy as np

arr = np.array(['apple', 'banana', 'cherry'])
print(np.char.upper(arr))  # Output: ['APPLE' 'BANANA' 'CHERRY']

```

### Numpy Join

Numpy’s `np.concatenate` or `np.vstack` can be used to join arrays.

**Example**:

```python
import numpy as np

arr1 = np.array([1, 2, 3])
arr2 = np.array([4, 5, 6])

joined_arr = np.concatenate((arr1, arr2))
print(joined_arr)  # Output: [1 2 3 4 5 6]

```

### Numpy Search

Numpy provides search functions like `np.where` to find indices where conditions are met.

**Example**:

```python
import numpy as np

arr = np.array([10, 20, 30, 40])
indices = np.where(arr > 20)
print(indices)  # Output: (array([2, 3]),)

```

### Numpy Sort

You can sort arrays using `np.sort` or sort in place with `sort` method.

**Example**:

```python
import numpy as np

arr = np.array([3, 1, 2])
sorted_arr = np.sort(arr)
print(sorted_arr)  # Output: [1 2 3]

```

### Compare and Filter in Numpy

Numpy arrays support comparison operations and filtering.

**Example**:

```python
import numpy as np

arr = np.array([1, 2, 3, 4, 5])

# Comparison
print(arr > 3)  # Output: [False False False  True  True]

# Filtering
filtered_arr = arr[arr > 3]
print(filtered_arr)  # Output: [4 5]
```

## Pandas - 10

### Importing Pandas

Pandas is a powerful data manipulation and analysis library in Python. It is commonly imported as `pd`.

**Example**:

```python
import pandas as pd

```

### Difference between Numpy and Pandas

- **Numpy**: Mainly used for numerical operations and array manipulation. It provides multidimensional arrays and mathematical functions.
- **Pandas**: Built on top of Numpy, it provides data structures like Series and DataFrame for data manipulation, including support for heterogeneous data types, and offers high-level functions for data analysis.

### Pandas Profiling

Pandas Profiling generates profile reports from a pandas DataFrame, giving a comprehensive overview of the data, including missing values, unique values, and statistical summaries.

**Installation**:

```
pip install pandas-profiling

```

**Example**:

```python
import pandas as pd
from pandas_profiling import ProfileReport

df = pd.read_csv('data.csv')
profile = ProfileReport(df)
profile.to_file("output.html")

```

### Pandas Series

A Series is a one-dimensional labeled array capable of holding any data type. It is similar to a column in a DataFrame.

**Example**:

```python
import pandas as pd

# Creating a Series
s = pd.Series([1, 2, 3, 4, 5], index=['a', 'b', 'c', 'd', 'e'])
print(s)

```

### Pandas DataFrame

A DataFrame is a two-dimensional labeled data structure with columns of potentially different types. It is similar to a table or spreadsheet.

**Example**:

```python
import pandas as pd

# Creating a DataFrame
data = {'Name': ['Alice', 'Bob', 'Charlie'], 'Age': [25, 30, 35]}
df = pd.DataFrame(data)
print(df)

```

### Read Excel with Pandas

Pandas can read Excel files into DataFrames using the `read_excel` function. You might need to install `openpyxl` or `xlrd` for this.

**Installation**:

```
pip install openpyxl

```

**Example**:

```python
import pandas as pd

df = pd.read_excel('file.xlsx', sheet_name='Sheet1')
print(df)

```

### Read JSON with Pandas

Pandas can read JSON data into DataFrames using the `read_json` function.

**Example**:

```python
import pandas as pd

df = pd.read_json('file.json')
print(df)

```

### Selecting, Extracting and Slicing DataFrames

- **Selecting Columns**: Use column names to select data.
- **Extracting Rows**: Use `iloc` or `loc` for row extraction.
- **Slicing**: Use `iloc` for integer-location based indexing or `loc` for label-based indexing.

**Example**:

```python
import pandas as pd

df = pd.DataFrame({'A': [1, 2, 3], 'B': [4, 5, 6]})

# Selecting a column
print(df['A'])

# Extracting a row
print(df.iloc[1])

# Slicing rows
print(df.iloc[0:2])

```

### Functions in Pandas

Pandas provides a wide range of functions for data manipulation, including aggregations, transformations, and statistical operations.

**Example**:

```python
import pandas as pd

df = pd.DataFrame({'A': [1, 2, 3, 4], 'B': [5, 6, 7, 8]})

# Aggregation
print(df.mean())  # Mean of each column

# Transformation
df['C'] = df['A'] + df['B']
print(df)

```

### Data Cleaning using Pandas

Pandas offers several methods for data cleaning, including handling missing values, removing duplicates, and converting data types.

**Example**:

```python
import pandas as pd

df = pd.DataFrame({'A': [1, 2, None, 4], 'B': [None, 2, 3, 4]})

# Handling missing values
df = df.fillna(0)  # Fill missing values with 0

# Removing duplicates
df = df.drop_duplicates()

print(df)
```

## Matplotlib - 6

### What is Matplotlib

Matplotlib is a comprehensive library for creating static, animated, and interactive visualizations in Python. It is widely used for plotting graphs and charts.

**Installation**:

```
pip install matplotlib

```

**Basic Usage**:

```python
import matplotlib.pyplot as plt

# Simple plot example
plt.plot([1, 2, 3, 4], [10, 20, 25, 30])
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.title('Simple Plot')
plt.show()

```

### Ticks in Matplotlib

Ticks are the markers on the axes of a plot that indicate data points. You can customize ticks using the `xticks()` and `yticks()` functions.

**Example**:

```python
import matplotlib.pyplot as plt

x = [1, 2, 3, 4]
y = [10, 20, 25, 30]

plt.plot(x, y)
plt.xticks([1, 2, 3, 4], ['A', 'B', 'C', 'D'])  # Custom X-axis labels
plt.yticks([10, 20, 30], ['Low', 'Medium', 'High'])  # Custom Y-axis labels
plt.show()

```

### Bar Plot

A bar plot is used to display categorical data with rectangular bars. The length of each bar represents the value of the category.

**Example**:

```python
import matplotlib.pyplot as plt

categories = ['A', 'B', 'C', 'D']
values = [10, 20, 15, 25]

plt.bar(categories, values)
plt.xlabel('Categories')
plt.ylabel('Values')
plt.title('Bar Plot')
plt.show()

```

### Scatter Plot

A scatter plot displays values for two variables using dots. It helps visualize the relationship between the variables.

**Example**:

```python
import matplotlib.pyplot as plt

x = [1, 2, 3, 4]
y = [10, 20, 15, 25]

plt.scatter(x, y)
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.title('Scatter Plot')
plt.show()

```

### Histogram Plot

A histogram shows the distribution of a dataset. It groups data into bins and displays the frequency of each bin.

**Example**:

```python
import matplotlib.pyplot as plt

data = [1, 2, 2, 3, 3, 3, 4, 4, 4, 4]

plt.hist(data, bins=4, edgecolor='black')
plt.xlabel('Value')
plt.ylabel('Frequency')
plt.title('Histogram Plot')
plt.show()

```

### Box and Whisker Plot

A box and whisker plot displays the distribution of a dataset based on quartiles. It shows the median, quartiles, and potential outliers.

**Example**:

```python
import matplotlib.pyplot as plt

data = [1, 2, 5, 6, 7, 8, 9, 10, 12, 15]

plt.boxplot(data)
plt.ylabel('Values')
plt.title('Box and Whisker Plot')
plt.show()
```

## OpenCV - 17

### What is OpenCV

OpenCV (Open Source Computer Vision Library) is an open-source library that contains a comprehensive set of tools for computer vision, machine learning, and image processing.

**Installation**:

```
pip install opencv-python

```

### Reading Image File

You can read an image file using `cv2.imread()`, which loads an image from a specified file.

**Example**:

```python
import cv2

image = cv2.imread('path/to/image.jpg')

```

### Display Image File

To display an image, use `cv2.imshow()`. This function opens a window to show the image.

**Example**:

```python
import cv2

image = cv2.imread('path/to/image.jpg')
cv2.imshow('Image Title', image)
cv2.waitKey(0)  # Wait for a key press
cv2.destroyAllWindows()  # Close all windows

```

### Writing Image File

To save an image to a file, use `cv2.imwrite()`. This function saves the image to the specified path.

**Example**:

```python
import cv2

image = cv2.imread('path/to/image.jpg')
cv2.imwrite('path/to/save_image.jpg', image)

```

### Image Read, Write and Display

Combining the above methods to read, display, and save an image:

**Example**:

```python
import cv2

image = cv2.imread('path/to/image.jpg')
cv2.imshow('Image Title', image)
cv2.waitKey(0)
cv2.imwrite('path/to/save_image.jpg', image)
cv2.destroyAllWindows()

```

### Feature Matching

Feature matching involves finding and matching keypoints between images. This can be done using feature detectors and descriptors like SIFT or ORB.

**Example**:

```python
import cv2

# Load images
img1 = cv2.imread('image1.jpg', 0)  # Query image
img2 = cv2.imread('image2.jpg', 0)  # Train image

# Initialize ORB detector
orb = cv2.ORB_create()

# Find keypoints and descriptors
kp1, des1 = orb.detectAndCompute(img1, None)
kp2, des2 = orb.detectAndCompute(img2, None)

# Match descriptors using BFMatcher
bf = cv2.BFMatcher(cv2.NORM_HAMMING, crossCheck=True)
matches = bf.match(des1, des2)

# Sort matches
matches = sorted(matches, key=lambda x: x.distance)

# Draw matches
img3 = cv2.drawMatches(img1, kp1, img2, kp2, matches[:10], None, flags=cv2.DrawMatchesFlags_NOT_DRAW_SINGLE_POINTS)
cv2.imshow('Feature Matches', img3)
cv2.waitKey(0)
cv2.destroyAllWindows()

```

### Color Filtering

Color filtering helps in isolating specific colors in an image.

**Example**:

```python
import cv2
import numpy as np

image = cv2.imread('path/to/image.jpg')
hsv = cv2.cvtColor(image, cv2.COLOR_BGR2HSV)

# Define color range for filtering
lower_bound = np.array([35, 100, 100])
upper_bound = np.array([85, 255, 255])

mask = cv2.inRange(hsv, lower_bound, upper_bound)
result = cv2.bitwise_and(image, image, mask=mask)

cv2.imshow('Filtered Image', result)
cv2.waitKey(0)
cv2.destroyAllWindows()

```

### Color Spaces

OpenCV supports multiple color spaces such as BGR, RGB, HSV, LAB.

**Example**:

```python
import cv2

image = cv2.imread('path/to/image.jpg')
hsv = cv2.cvtColor(image, cv2.COLOR_BGR2HSV)
lab = cv2.cvtColor(image, cv2.COLOR_BGR2LAB)

```

### Cropping Image

To crop an image, use array slicing.

**Example**:

```python
import cv2

image = cv2.imread('path/to/image.jpg')
cropped_image = image[50:200, 100:300]  # Crop from (50,100) to (200,300)

cv2.imshow('Cropped Image', cropped_image)
cv2.waitKey(0)
cv2.destroyAllWindows()

```

### Bitwise Operations on Images

Bitwise operations like AND, OR, NOT, and XOR can be used for image manipulation.

**Example**:

```python
import cv2
import numpy as np

image1 = cv2.imread('path/to/image1.jpg')
image2 = cv2.imread('path/to/image2.jpg')

# Perform bitwise AND
bitwise_and = cv2.bitwise_and(image1, image2)

cv2.imshow('Bitwise AND', bitwise_and)
cv2.waitKey(0)
cv2.destroyAllWindows()

```

### Adaptive Thresholding

Adaptive thresholding is useful for segmenting images with varying lighting conditions.

**Example**:

```python
import cv2

image = cv2.imread('path/to/image.jpg', 0)
thresh = cv2.adaptiveThreshold(image, 255, cv2.ADAPTIVE_THRESH_GAUSSIAN_C, cv2.THRESH_BINARY, 11, 2)

cv2.imshow('Adaptive Thresholding', thresh)
cv2.waitKey(0)
cv2.destroyAllWindows()

```

### Motion Estimation

Motion estimation can be used to detect and track movement in video frames.

**Example**:

```python
import cv2

cap = cv2.VideoCapture('video.mp4')

ret, frame1 = cap.read()
prvs = cv2.cvtColor(frame1, cv2.COLOR_BGR2GRAY)
hsv_mask = np.zeros_like(frame1)
hsv_mask[..., 1] = 255

while(cap.isOpened()):
    ret, frame2 = cap.read()
    if not ret:
        break

    next = cv2.cvtColor(frame2, cv2.COLOR_BGR2GRAY)
    flow = cv2.calcOpticalFlowFarneback(prvs, next, None, 0.5, 3, 15, 3, 5, 1.2, 0)
    magnitude, angle = cv2.cartToPolar(flow[..., 0], flow[..., 1])
    hsv_mask[..., 0] = angle * 180 / np.pi / 2
    hsv_mask[..., 2] = cv2.normalize(magnitude, None, 0, 255, cv2.NORM_MINMAX)
    rgb = cv2.cvtColor(hsv_mask, cv2.COLOR_HSV2BGR)

    cv2.imshow('Optical Flow', rgb)
    if cv2.waitKey(30) & 0xFF == 27:
        break

    prvs = next

cap.release()
cv2.destroyAllWindows()

```

### Contours

Contours are used to detect and outline shapes in an image.

**Example**:

```python
import cv2

image = cv2.imread('path/to/image.jpg', 0)
ret, thresh = cv2.threshold(image, 127, 255, cv2.THRESH_BINARY)
contours, _ = cv2.findContours(thresh, cv2.RETR_EXTERNAL, cv2.CHAIN_APPROX_SIMPLE)

cv2.drawContours(image, contours, -1, (0, 255, 0), 3)
cv2.imshow('Contours', image)
cv2.waitKey(0)
cv2.destroyAllWindows()

```

### Feature Detection with HAAR Cascade Classifier

HAAR Cascade classifiers are used for object detection such as faces.

**Example**:

```python
import cv2

face_cascade = cv2.CascadeClassifier(cv2.data.haarcascades + 'haarcascade_frontalface_default.xml')
image = cv2.imread('path/to/image.jpg')
gray = cv2.cvtColor(image, cv2.COLOR_BGR2GRAY)

faces = face_cascade.detectMultiScale(gray, 1.3, 5)

for (x, y, w, h) in faces:
    cv2.rectangle(image, (x, y), (x+w, y+h), (255, 0, 0), 2)

cv2.imshow('Face Detection', image)
cv2.waitKey(0)
cv2.destroyAllWindows()

```

### Smoothing Images

Smoothing (blurring) reduces noise and detail in an image.

**Example**:

```python
import cv2

image = cv2.imread('path/to/image.jpg')
blurred = cv2.GaussianBlur(image, (5, 5), 0)

cv2.imshow('Blurred Image', blurred)
cv2.waitKey(0)
cv2.destroyAllWindows()

```

### Face Detection

Face detection can be achieved using pre-trained models like HAAR cascades.

**Example**:

```python
import cv2

face_cascade = cv2.CascadeClassifier(cv2.data.haarcascades + 'haarcascade_frontalface_default.xml')
image = cv2.imread('path/to/image.jpg')
gray = cv2.cvtColor(image, cv2.COLOR_BGR2GRAY)

faces = face_cascade.detectMultiScale(gray, 1.3, 5)

for (x, y, w, h) in faces:
    cv2.rectangle(image, (x, y), (x+w, y+h), (255, 0, 0), 2)

cv2.imshow('Face Detection', image)
cv2.waitKey(0)
cv2.destroyAllWindows()
```

### Eyeball Tracking

Eyeball tracking involves detecting the eyes and tracking their movement. This typically starts with face detection and then focuses on eye detection.

**Example**:

```python
import cv2

# Load pre-trained classifiers
face_cascade = cv2.CascadeClassifier(cv2.data.haarcascades + 'haarcascade_frontalface_default.xml')
eye_cascade = cv2.CascadeClassifier(cv2.data.haarcascades + 'haarcascade_eye.xml')

# Load image
image = cv2.imread('path/to/image.jpg')
gray = cv2.cvtColor(image, cv2.COLOR_BGR2GRAY)

# Detect faces
faces = face_cascade.detectMultiScale(gray, 1.3, 5)

# Detect eyes within each face
for (x, y, w, h) in faces:
    roi_gray = gray[y:y+h, x:x+w]
    roi_color = image[y:y+h, x:x+w]
    eyes = eye_cascade.detectMultiScale(roi_gray)

    for (ex, ey, ew, eh) in eyes:
        cv2.rectangle(roi_color, (ex, ey), (ex+ew, ey+eh), (0, 255, 0), 2)

cv2.imshow('Eye Detection', image)
cv2.waitKey(0)
cv2.destroyAllWindows()

```

This example detects faces first and then detects eyes within each detected face, drawing rectangles around both.

### Summary

**OpenCV** is a powerful library for computer vision and image processing tasks. With its rich set of functions, you can perform a variety of operations from basic image reading and displaying to advanced tasks like feature detection and tracking.

# Flask

## Fundamentals of Flask - 6

### Introduction to Flask

- **Flask** is a lightweight web framework for Python used to build web applications.
- It's known for its simplicity and flexibility, allowing developers to use various extensions to enhance functionality.

### Environment Setup and Creating First Application

1. **Installation**:
    
    ```bash
    pip install Flask
    
    ```
    
2. **Creating Your First Flask App**:
    
    ```python
    from flask import Flask
    
    app = Flask(__name__)
    
    @app.route('/')
    def hello_world():
        return 'Hello, World!'
    
    if __name__ == '__main__':
        app.run(debug=True)
    
    ```
    
    - `app = Flask(__name__)` initializes the Flask application.
    - `@app.route('/')` defines the route for the home page.
    - `app.run(debug=True)` runs the app in debug mode for easier development.

### Routing in Flask

- **Routes** map URLs to functions.
- Example:
    
    ```python
    @app.route('/about')
    def about():
        return 'About Page'
    
    ```
    
- Use `@app.route('/path')` to specify the URL and link it to a function.

### Variable Rules in Flask

- **Variable Rules** allow dynamic URL segments.
- Example:
    
    ```python
    @app.route('/user/<username>')
    def show_user_profile(username):
        return f'User {username}'
    
    ```
    
- `<username>` is a variable part of the URL that will be passed to the function.

### URL Building in Flask

- **URL Building** generates URLs for a given endpoint.
- Use `url_for()` to dynamically generate URLs.
- Example:
    
    ```python
    from flask import url_for
    
    @app.route('/home')
    def home():
        return f'Home Page: {url_for("about")}'
    
    ```
    
- `url_for('about')` returns the URL for the `about` endpoint.

### HTTP Methods in Flask

- **HTTP Methods** (GET, POST, etc.) are used to interact with web routes.
- **GET**: Retrieve data.
- **POST**: Submit data.
- Example:
    
    ```python
    from flask import request
    
    @app.route('/login', methods=['POST'])
    def login():
        username = request.form['username']
        return f'Login for {username}'
    
    ```
    
- Use `methods=['POST']` to specify that the route accepts POST requests. Access form data via `request.form`.

## Web Development with Flask - 9

### Templates in Flask

- **Templates** are used to render dynamic HTML pages.
- Flask uses Jinja2 for templating.
- **Basic Usage**:
    - Create a folder named `templates`.
    - Store HTML files (e.g., `index.html`) in this folder.
    - Render templates in views:
        
        ```python
        from flask import render_template
        
        @app.route('/')
        def home():
            return render_template('index.html', title='Home Page')
        
        ```
        

### Static File Handling in Flask

- **Static Files** (CSS, JavaScript, images) are served from the `static` folder.
- Example folder structure:
    
    ```
    /static
        /css
            style.css
        /js
            script.js
    
    ```
    
- Access static files in templates:
    
    ```html
    <link rel="stylesheet" href="{{ url_for('static', filename='css/style.css') }}">
    <script src="{{ url_for('static', filename='js/script.js') }}"></script>
    
    ```
    

### Request Object in Flask

- **Request Object** provides data sent with the request.
- Access form data, query parameters, and more:
    
    ```python
    from flask import request
    
    @app.route('/submit', methods=['POST'])
    def submit():
        name = request.form['name']
        return f'Name: {name}'
    
    ```
    
- Use `request.args` for query parameters and `request.json` for JSON data.

### JSON Response in Flask

- **JSON Response** can be returned using `jsonify`.
- Example:
    
    ```python
    from flask import jsonify
    
    @app.route('/api/data')
    def get_data():
        data = {'key': 'value'}
        return jsonify(data)
    
    ```
    

### Sending Form Data to Template in Flask

- **Pass Form Data** from routes to templates.
- Example:
    
    ```python
    from flask import render_template, request
    
    @app.route('/form', methods=['GET', 'POST'])
    def form():
        if request.method == 'POST':
            name = request.form['name']
            return render_template('result.html', name=name)
        return render_template('form.html')
    
    ```
    

### Cookies in Flask

- **Cookies** are used to store data on the client side.
- Set and get cookies:
    
    ```python
    from flask import request, make_response
    
    @app.route('/set_cookie')
    def set_cookie():
        resp = make_response('Cookie Set')
        resp.set_cookie('username', 'FlaskUser')
        return resp
    
    @app.route('/get_cookie')
    def get_cookie():
        username = request.cookies.get('username')
        return f'Username: {username}'
    
    ```
    

### OAuth in Flask

- **OAuth** is used for authentication with third-party services.
- Use extensions like `Flask-OAuthlib` or `Authlib` for integration.
- Basic setup involves configuring the OAuth provider and handling callbacks.

### Error Handling in Flask

- **Error Handling** is managed using error handlers.
- Example:
    
    ```python
    @app.errorhandler(404)
    def page_not_found(e):
        return 'Page Not Found', 404
    
    ```
    
- Handle specific errors and customize responses.

### File Uploading in Flask

- **File Uploading** allows users to upload files to the server.
- Example:
    
    ```python
    from flask import request
    
    @app.route('/upload', methods=['POST'])
    def upload_file():
        if 'file' not in request.files:
            return 'No file part'
        file = request.files['file']
        if file.filename == '':
            return 'No selected file'
        file.save(f'./uploads/{file.filename}')
        return 'File Uploaded'
    ```
    

## Advanced Flask Topics - 3

### Flask Mail

- **Flask Mail** integrates email sending capabilities into Flask applications.
- **Setup**:
    - Install `Flask-Mail`: `pip install Flask-Mail`
    - Configure mail settings in `app.config`:
        
        ```python
        from flask_mail import Mail, Message
        
        app.config['MAIL_SERVER'] = 'smtp.example.com'
        app.config['MAIL_PORT'] = 587
        app.config['MAIL_USERNAME'] = 'your-email@example.com'
        app.config['MAIL_PASSWORD'] = 'your-password'
        app.config['MAIL_USE_TLS'] = True
        mail = Mail(app)
        
        ```
        
- **Send Email**:
    
    ```python
    @app.route('/send_email')
    def send_email():
        msg = Message('Hello', sender='your-email@example.com', recipients=['recipient@example.com'])
        msg.body = 'This is the email body'
        mail.send(msg)
        return 'Email sent!'
    
    ```
    

### Flask WTForms

- **Flask WTForms** is used for form handling and validation in Flask.
- **Setup**:
    - Install `Flask-WTF`: `pip install Flask-WTF`
    - Create a form class:
        
        ```python
        from flask_wtf import FlaskForm
        from wtforms import StringField, PasswordField, SubmitField
        from wtforms.validators import DataRequired
        
        class LoginForm(FlaskForm):
            username = StringField('Username', validators=[DataRequired()])
            password = PasswordField('Password', validators=[DataRequired()])
            submit = SubmitField('Login')
        
        ```
        
- **Render Form in Template**:
    
    ```python
    @app.route('/login', methods=['GET', 'POST'])
    def login():
        form = LoginForm()
        if form.validate_on_submit():
            return 'Form submitted!'
        return render_template('login.html', form=form)
    
    ```
    
    - In `login.html`:
        
        ```html
        <form method="POST" action="">
            {{ form.hidden_tag() }}
            {{ form.username.label }} {{ form.username() }}
            {{ form.password.label }} {{ form.password() }}
            {{ form.submit() }}
        </form>
        
        ```
        

### Flask Deployment

- **Flask Deployment** involves deploying Flask applications to production environments.
- **Common Deployment Options**:
    - **WSGI Servers**: Use servers like Gunicorn or uWSGI to serve the Flask app.
        
        ```bash
        gunicorn -w 4 app:app
        
        ```
        
    - **Platform-as-a-Service**: Deploy to platforms like Heroku, AWS Elastic Beanstalk, or Google Cloud Platform.
    - **Docker**: Containerize Flask applications using Docker for consistent deployment environments.
        - Create a `Dockerfile`:
            
            ```
            FROM python:3.9
            WORKDIR /app
            COPY requirements.txt requirements.txt
            RUN pip install -r requirements.txt
            COPY . .
            CMD ["gunicorn", "-w", "4", "app:app"]
            
            ```
            
        - Build and run:
            
            ```bash
            docker build -t my-flask-app .
            docker run -p 5000:5000 my-flask-app
            ```
            

# Django

## Django Fundamentals - 5

### What is Django

- **Django** is a high-level Python web framework that encourages rapid development and clean, pragmatic design.
- **Features**:
    - **MVC Architecture**: Follows the Model-View-Controller pattern.
    - **DRY Principle**: "Don't Repeat Yourself" - emphasizes code reusability and simplicity.
    - **Batteries-Included**: Comes with a lot of built-in features, like an admin interface, ORM, and authentication.
    - **Scalability**: Suitable for both small and large-scale applications.

### Basics of Django Framework

- **Components**:
    - **Models**: Define the data structure and interact with the database.
    - **Views**: Handle the business logic and return responses.
    - **Templates**: Define the HTML structure for rendering views.
    - **URLs**: Map URLs to views.
- **Request-Response Cycle**:
    1. **Request**: A user makes a request to the server.
    2. **URL Dispatcher**: Django maps the URL to a view.
    3. **View**: The view processes the request and interacts with models and templates.
    4. **Response**: The view returns a response, which is rendered by a template.

### Django Installation

- **Steps**:
    1. **Install Django**:
        
        ```bash
        pip install django
        
        ```
        
    2. **Verify Installation**:
        
        ```bash
        django-admin --version
        
        ```
        
    3. **Create a Django Project**:
        
        ```bash
        django-admin startproject myproject
        
        ```
        
    4. **Navigate to Project Directory**:
        
        ```bash
        cd myproject
        
        ```
        
    5. **Run Development Server**:
        
        ```bash
        python manage.py runserver
        
        ```
        
        - Access the development server at `http://127.0.0.1:8000/`.

### Project Structure in Django

- **Typical Structure**:
    
    ```
    myproject/
        manage.py
        myproject/
            __init__.py
            settings.py
            urls.py
            wsgi.py
        app1/
            __init__.py
            admin.py
            apps.py
            models.py
            tests.py
            views.py
    
    ```
    
- **Components**:
    - `manage.py`: Command-line utility for administrative tasks.
    - `settings.py`: Configuration settings for the project.
    - `urls.py`: URL declarations for the project.
    - `wsgi.py`: Entry point for WSGI-compatible web servers.
    - `app/`: Directory for each application, including models, views, and admin configuration.

### Django Admin Interface

- **Features**:
    - **Admin Interface**: A built-in interface for managing Django models.
    - **Automatic CRUD Operations**: Provides Create, Read, Update, and Delete operations for models.
- **Setup**:
    1. **Create Superuser**:
        
        ```bash
        python manage.py createsuperuser
        
        ```
        
        - Follow prompts to set up username, email, and password.
    2. **Access Admin Interface**:
        - Start the server and navigate to `http://127.0.0.1:8000/admin/`.
    3. **Register Models**:
        - In `admin.py` of an app, register your models:
            
            ```python
            from django.contrib import admin
            from .models import MyModel
            
            admin.site.register(MyModel)
            ```
            

## Django Frontend Development - 5

### Django Templates

- **Templates** are used to define the HTML structure for rendering views.
- **Template Syntax**:
    - **Variables**: `{{ variable_name }}`
    - **Filters**: `{{ variable_name|filter_name }}`
    - **Tags**: `{% tag_name %}`
- **Template Directory**:
    - By default, templates are placed in a `templates/` directory inside each app.
    - You can configure a global template directory in `settings.py` under `TEMPLATES` -> `DIRS`.

### Django Views

- **Views** handle the business logic and return responses.
- **View Types**:
    - **Function-Based Views (FBVs)**:
        
        ```python
        from django.http import HttpResponse
        
        def my_view(request):
            return HttpResponse("Hello, World!")
        
        ```
        
    - **Class-Based Views (CBVs)**:
        
        ```python
        from django.views.generic import TemplateView
        
        class MyView(TemplateView):
            template_name = "my_template.html"
        
        ```
        
- **Rendering Templates**:
    - **FBVs**:
        
        ```python
        from django.shortcuts import render
        
        def my_view(request):
            return render(request, 'my_template.html', {'key': 'value'})
        
        ```
        
    - **CBVs**:
        
        ```python
        from django.views.generic import TemplateView
        
        class MyView(TemplateView):
            template_name = "my_template.html"
            context_object_name = 'key'
        
        ```
        

### Variables in Django

- **Usage**:
    - Pass context variables from views to templates:
        
        ```python
        def my_view(request):
            context = {'variable_name': 'value'}
            return render(request, 'template.html', context)
        
        ```
        
    - **In Template**:
        
        ```html
        <p>{{ variable_name }}</p>
        
        ```
        
- **Context Processors**:
    - Allow you to add variables to all templates globally.
    - Define in `settings.py` under `TEMPLATES` -> `OPTIONS` -> `context_processors`.

### If-Else in Django

- **Template Tags**:
    - **If Tag**:
        
        ```html
        {% if condition %}
            <p>Condition is True</p>
        {% else %}
            <p>Condition is False</p>
        {% endif %}
        
        ```
        
    - **If-Else-If**:
        
        ```html
        {% if condition1 %}
            <p>Condition 1 is True</p>
        {% elif condition2 %}
            <p>Condition 2 is True</p>
        {% else %}
            <p>Neither condition is True</p>
        {% endif %}
        
        ```
        

### Loop in Django

- **For Tag**:
    - **Basic Loop**:
        
        ```html
        {% for item in list %}
            <p>{{ item }}</p>
        {% endfor %}
        
        ```
        
    - **Loop with Index**:
        
        ```html
        {% for item in list %}
            <p>{{ forloop.counter }}: {{ item }}</p>
        {% endfor %}
        
        ```
        
    - **Loop with Conditional**:
        
        ```html
        {% for item in list %}
            {% if item.condition %}
                <p>{{ item }}</p>
            {% endif %}
        {% endfor %}
        ```
        

## Django Backend Development - 10

### Creating Django App

- **Create an App**:
    - Use the `startapp` command to create a new app:
        
        ```bash
        python manage.py startapp app_name
        
        ```
        
- **Add to Project**:
    - Add the app to the `INSTALLED_APPS` list in `settings.py`:
        
        ```python
        INSTALLED_APPS = [
            'app_name',
            # other apps
        ]
        
        ```
        
- **App Structure**:
    - Includes files like `models.py`, `views.py`, `urls.py`, etc.

### Django Redirect

- **Redirect Views**:
    - Use `redirect()` to redirect to another view or URL:
        
        ```python
        from django.shortcuts import redirect
        
        def my_view(request):
            return redirect('url_name')
        
        ```
        
- **Named URLs**:
    - Define URLs with names in `urls.py` for easy referencing:
        
        ```python
        from django.urls import path
        
        urlpatterns = [
            path('some-url/', my_view, name='url_name'),
        ]
        
        ```
        

### Django Forms

- **Django Forms**:
    - Handle form data and validation.
    - Create forms by inheriting from `forms.Form` or `forms.ModelForm`.
    - **Form Example**:
        
        ```python
        from django import forms
        
        class MyForm(forms.Form):
            name = forms.CharField(max_length=100)
            age = forms.IntegerField()
        
        ```
        

### Creating Django Forms

- **Form Creation**:
    - Create a form in `forms.py` and use it in views:
        
        ```python
        from .forms import MyForm
        
        def my_view(request):
            form = MyForm()
            return render(request, 'template.html', {'form': form})
        
        ```
        
- **Form Handling**:
    - Handle form submission and validation in views:
        
        ```python
        if request.method == 'POST':
            form = MyForm(request.POST)
            if form.is_valid():
                # process data
        
        ```
        

### Django Form Fields

- **Common Field Types**:
    - **CharField**: Text input
    - **IntegerField**: Numeric input
    - **EmailField**: Email input
    - **DateField**: Date input
    - **ChoiceField**: Dropdown with choices
    - **BooleanField**: Checkbox
- **Example**:
    
    ```python
    class MyForm(forms.Form):
        email = forms.EmailField()
        age = forms.IntegerField()
        gender = forms.ChoiceField(choices=[('M', 'Male'), ('F', 'Female')])
    
    ```
    

### Django Formsets

- **Formsets**:
    - Manage multiple forms on a single page.
    - Use `formset_factory` to create a formset:
        
        ```python
        from django.forms import formset_factory
        
        MyFormSet = formset_factory(MyForm)
        
        ```
        
- **Usage in Views**:
    
    ```python
    def my_view(request):
        MyFormSet = formset_factory(MyForm)
        formset = MyFormSet()
        return render(request, 'template.html', {'formset': formset})
    
    ```
    

### Django Models

- **Models**:
    - Define data structure and ORM mapping in `models.py`:
        
        ```python
        from django.db import models
        
        class MyModel(models.Model):
            name = models.CharField(max_length=100)
            age = models.IntegerField()
        
        ```
        
- **Migration**:
    - Create and apply migrations to update the database schema:
        
        ```bash
        python manage.py makemigrations
        python manage.py migrate
        
        ```
        

### Django CRUD Operations

- **CRUD Operations**:
    - **Create**: Add new records
    - **Read**: Retrieve records
    - **Update**: Modify existing records
    - **Delete**: Remove records
- **Example Views**:
    - **Create**:
        
        ```python
        def create_view(request):
            if request.method == 'POST':
                form = MyModelForm(request.POST)
                if form.is_valid():
                    form.save()
                    return redirect('success_url')
            else:
                form = MyModelForm()
            return render(request, 'create_template.html', {'form': form})
        
        ```
        
    - **Read**:
        
        ```python
        def list_view(request):
            items = MyModel.objects.all()
            return render(request, 'list_template.html', {'items': items})
        
        ```
        

### Sessions in Django

- **Session Management**:
    - Use sessions to store user-specific data.
    - **Access Session Data**:
        
        ```python
        request.session['key'] = 'value'
        value = request.session.get('key', 'default')
        
        ```
        
- **Settings**:
    - Configure session settings in `settings.py` under `SESSION_ENGINE`.

### REST API

- **Django REST Framework (DRF)**:
    - **Install DRF**:
        
        ```bash
        pip install djangorestframework
        
        ```
        
    - **Configure**:
        - Add `'rest_framework'` to `INSTALLED_APPS` in `settings.py`.
    - **Create API Views**:
        
        ```python
        from rest_framework.views import APIView
        from rest_framework.response import Response
        from rest_framework import status
        
        class MyAPIView(APIView):
            def get(self, request):
                return Response({'message': 'Hello, World!'}, status=status.HTTP_200_OK)
        
        ```
        
    - **Serializers**:
        - Convert complex data types to native Python data types:
            
            ```python
            from rest_framework import serializers
            
            class MyModelSerializer(serializers.ModelSerializer):
                class Meta:
                    model = MyModel
                    fields = '__all__'
            ```
            

# Most Frequently Asked Coding Problems - 15

### 1. Reverse a 32-bit signed integer `N`

Reverse a 32-bit signed integer and return the reversed value, or `-1` if the result overflows.

```python
def reverse_integer(N):
    INT_MIN, INT_MAX = -2**31, 2**31 - 1
    reversed_int = 0
    sign = -1 if N < 0 else 1
    N = abs(N)

    while N != 0:
        pop = N % 10
        N //= 10
        if reversed_int > (INT_MAX - pop) // 10:
            return -1
        reversed_int = reversed_int * 10 + pop

    return sign * reversed_int

# Example usage
print(reverse_integer(123))    # Output: 321
print(reverse_integer(-123))   # Output: -321

```

### 2. Check if a number is a prime number

Check if a given number `n` is a prime number, returning "YES" if it is and "NO" otherwise.

```python
def is_prime(n):
    if n <= 1:
        return "NO"
    if n <= 3:
        return "YES"
    if n % 2 == 0 or n % 3 == 0:
        return "NO"
    i = 5
    while i * i <= n:
        if n % i == 0 or n % (i + 2) == 0:
            return "NO"
        i += 6
    return "YES"

# Example usage
print(is_prime(29))  # Output: YES
print(is_prime(10))  # Output: NO

```

### 3. Generate the first `n` Fibonacci numbers using a generator function

Generate the first `n` Fibonacci numbers using a generator function.

```python
def fibonacci_generator(n):
    a, b = 0, 1
    for _ in range(n):
        yield a
        a, b = b, a + b

# Example usage
print(list(fibonacci_generator(5)))  # Output: [0, 1, 1, 2, 3]

```

### 4. Find the largest of three given numbers `a`, `b`, and `c`

Find the largest of three given numbers `a`, `b`, and `c`.

```python
def find_largest(a, b, c):
    return max(a, b, c)

# Example usage
print(find_largest(3, 7, 5))  # Output: 7

```

### 5. Calculate the floor value of Simple Interest

Calculate the floor value of Simple Interest given principal, rate of interest, and time period.

```python
import math

def simple_interest(principal, rate, time):
    return math.floor((principal * rate * time) / 100)

# Example usage
print(simple_interest(1000, 5, 2))  # Output: 100

```

### 6. Convert a binary string to its decimal equivalent

Convert a binary string to its decimal equivalent.

```python
def binary_to_decimal(binary_str):
    return int(binary_str, 2)

# Example usage
print(binary_to_decimal("1101"))  # Output: 13

```

### 7. Check if a given year is a leap year

Check if a given year is a leap year.

```python
def is_leap_year(year):
    if year % 4 == 0:
        if year % 100 == 0:
            if year % 400 == 0:
                return True
            return False
        return True
    return False

# Example usage
print(is_leap_year(2020))  # Output: True
print(is_leap_year(1900))  # Output: False

```

### 8. Calculate the factorial of a number

Calculate the factorial of a number, with output 'Error' for negative inputs.

```python
import math

def factorial(n):
    if n < 0:
        return "Error"
    return math.factorial(n)

# Example usage
print(factorial(5))  # Output: 120
print(factorial(-1))  # Output: Error

```

### 9. Find all palindromic numbers from 1 to `N`

Find all palindromic numbers from 1 to `N`.

```python
def is_palindromic(num):
    return str(num) == str(num)[::-1]

def palindromic_numbers(N):
    return [num for num in range(1, N + 1) if is_palindromic(num)]

# Example usage
print(palindromic_numbers(100))  # Output: [1, 2, 3, 4, 5, 6, 7, 8, 9, 11, 22, 33, 44, 55, 66, 77, 88, 99]

```

### 10. Calculate the LCM (Least Common Multiple) of two numbers

Calculate the LCM (Least Common Multiple) of two numbers `X` and `Y`.

```python
import math

def lcm(x, y):
    return abs(x * y) // math.gcd(x, y)

# Example usage
print(lcm(12, 15))  # Output: 60

```

### 11. Print the first `N` rows of Pascal's Triangle

Print the first `N` rows of Pascal's Triangle.

```python
def generate_pascals_triangle(N):
    triangle = []
    for i in range(N):
        row = [1] * (i + 1)
        for j in range(1, i):
            row[j] = triangle[i - 1][j - 1] + triangle[i - 1][j]
        triangle.append(row)
    return triangle

# Example usage
for row in generate_pascals_triangle(5):
    print(row)

```

### 12. Reverse the array `arr` of size `n`

Reverse the array `arr` of size `n`.

```python
def reverse_array(arr):
    return arr[::-1]

# Example usage
print(reverse_array([1, 2, 3, 4, 5]))  # Output: [5, 4, 3, 2, 1]

```

### 13. Compute and return the transpose of a matrix `MAT`

Compute and return the transpose of a matrix `MAT`.

```python
def transpose_matrix(matrix):
    return list(map(list, zip(*matrix)))

# Example usage
print(transpose_matrix([[1, 2, 3], [4, 5, 6], [7, 8, 9]]))
# Output: [[1, 4, 7], [2, 5, 8], [3, 6, 9]]

```

### 14. Determine if a given integer `n` is an Armstrong number

Determine if a given integer `n` is an Armstrong number.

```python
def is_armstrong(n):
    digits = str(n)
    power = len(digits)
    return n == sum(int(digit) ** power for digit in digits)

# Example usage
print(is_armstrong(153))  # Output: True
print(is_armstrong(123))  # Output: False

```

### 15. Find the missing number in the range 1 to `n`

Given an array `a` of size `n-1` with elements in the range `1` to `n`, find the missing number.

```python
def find_missing_number(arr, n):
    return n * (n + 1) // 2 - sum(arr)

# Example usage
print(find_missing_number([1, 2, 4, 5, 6], 6))  # Output: 3

```

# Interview Questions - 10

[Python Set-1](https://www.naukri.com/code360/library/python-interview-questions)

[Python Set-2](https://www.javatpoint.com/python-interview-questions)

[Numpy Interview Questions](https://www.naukri.com/code360/library/numpy-interview-questions)

[Pandas Interview Questions](https://www.naukri.com/code360/library/pandas-interview-questions)

[Matplotlib Interview Questions](https://climbtheladder.com/matplotlib-interview-questions/)

[OpenCV Interview Questions](https://pythongeeks.org/opencv-interview-questions-with-answers/)

[Flask Interview Questions](https://www.softwaretestinghelp.com/flask-interview-questions-with-answers/)

[Django Interview Questions](https://www.codingninjas.com/blog/2021/09/10/top-30-basic-django-interview-questions-part-1/)
