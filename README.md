---
title: "#4 - University of California @Davis Data Manipulation in JavaScript"
author: "bbauska"
date last editted: "2/5/2024 8+am"
output: 
  markdown:
    with some style
---

<h2 align="center">Data Manipulation in JavaScript</h2>
<h6>Taught by William Mead, Lecturer</h6>
<br/>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~ readme.md of uc-davis-data-manipulation-in-js ~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~ 01. introduction to data manipulation in javascript (01) ~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image001.webp?raw=true"
  style="width:45%;"
  alt="Introduction to Data Manipulation in JavaScript by William Mead, 
    (lecturer, UC Davis)." />
</p>

<h3 align="center"> </h3>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 02. uc davis logo (01) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center" width="100%">
<img src="./images/image002.webp?raw=true"
  style="width:25%;"
  alt="UC Davis logo." />
</p>

<h2><a href="#table-of-contents">Table of Contents</a></h2>

## [**About**](#cha)
>### - [**About**](#cha-1)
>### - [**Source Code for Each Week**](#cha-2)
>### - [**Course Slides**](#cha-3)

## [**Course Information**](#chb)
>### * [**Syllabus**](#chb-1)
>### * [**Resources**](#chb-2)
>### * [** **](#chb-3)
>### * [** **](#chb-4)
>### * [** **](#chb-5)
>### * [** **](#chb-6)
>### * [** **](#chb-7)
>### * [** **](#chb-8)

## [**Week 1: Collecting &amp; Validating Data From Users**](#ch1)
>### 1.1 [**Introduction to HTML Forms**](#ch1-1)
>### 1.2 [**Adding a Label**](#ch1-2)
>### 1.3 [**Radio Button Input Types**](#ch1-3)
>### 1.4 [**Using the Checkboxes Input Types**](#ch1-4)
>### 1.5 [**Using Textarea Elements**](#ch1-5)
>### 1.6 [**Styling Your Form**](#ch1-6)
>### 1.7 [**Intro to Basics of Form Validation**](#ch1-7)
>### 1.8 [**Processing the Form**](#ch1-8)
>### 1.9 [**Backend Validation with PHP**](#ch1-9)
>### 1.10 [**Plain JavaScript Validation**](#ch1-10)
>### 1.11 [**jQuery Form Validation**](#ch1-11)
>### 1.12 [**jQuery Validator Plugin - Part 1**](#ch1-12)
>### 1.13 [**jQuery Validator Plugin - Part 2**](#ch1-13)
>### 1.14 [**Intro to Advanced Form Validation**](#ch1-14)
>### 1.15 [**Starting the Script**](#ch1-15)
>### 1.16 [**Checking the Phone Number**](#ch1-16)
>### 1.17 [**Adding Messages**](#ch1-17)
>### 1.18 [**Styling Your Form**](#ch1-18)

## [**Week 2: A Deeper Dive in JavaScript**](#ch2)
>### 2.1 [****](#ch2-1)
>### 2.2 [****](#ch2-2)
>### 2.3 [****](#ch2-3)
>### 2.4 [****](#ch2-4)
>### 2.5 [****](#ch2-5)
>### 2.6 [****](#ch2-6)
>### 2.7 [****](#ch2-7)
>### 2.8 [****](#ch2-8)
>### 2.9 [****](#ch2-9)

## [**Week 3: Seat Reservation Program**](#ch3)
>### 3.1 [**Intro to Creating the Seat**](#ch3-1)
>### 3.2 [**The Left Section**](#ch3-2)
>### 3.3 [**The Right Section**](#ch3-3)
>### 3.4 [**The Middle Section**](#ch3-4)
>### 3.5 [**Figuring Out Variables**](#ch3-5)
>### 3.6 [**Adding Switch Statements**](#ch3-6)
>### 3.7 [**Adding the Loop and HTML**](#ch3-7)
>### 3.8 [**Using an Arrow Function**](#ch3-8)
>### 3.9 [**The reservedSeats Object**](#ch3-9)
>### 3.10 [**Affecting the DOM**](#ch3-10)
>### 3.11 [**With IIFE Closure**](#ch3-11)
>### 3.12 [**Adding an Array**](#ch3-12)
>### 3.13 [**Two Pieces Needed**](#ch3-13)
>### 3.14 [**Getting the Seat ID**](#ch3-14)
>### 3.15 [**Getting the Index**](#ch3-15)
>### 3.16 [**Adding the If Statement**](#ch3-16)
>### 3.17 [**The Finished Function**](#ch3-17)
>### 3.18 [**Adding the Form HTML**](#ch3-18)
>### 3.19 [**Open and Close Form Event Handlers**](#ch3-19)
>### 3.20 [**manageConfirmForm Function**](#ch3-20)
>### 3.21 [**Updating the Else Statement**](#ch3-21)
>### 3.22 [**Fixing Bugs on the Form**](#ch3-22)
>### 3.23 [**Fixing More Bugs**](#ch3-23)
>### 3.24 [**Additional Condition Statements**](#ch3-24)
>### 3.25 [**Setting Up the Final Steps**](#ch3-25)
>### 3.26 [**Back to the Object**](#ch3-26)
>### 3.27 [**Adding Each Record**](#ch3-27)
>### 3.28 [**Clean Up**](#ch3-28)
>### 3.29 [**Final Fixes**](#ch3-29)

## [**Week 4: Working with Data Asynchronously in JavaScript**](#ch4)
>### 4.1 [****](#ch4-1)
>### 4.2 [****](#ch4-2)
>### 4.3 [****](#ch4-3)
>### 4.4 [****](#ch4-4)
>### 4.5 [****](#ch4-5)
>### 4.6 [****](#ch4-6)
>### 4.7 [****](#ch4-7)
>### 4.8 [****](#ch4-8)
>### 4.9 [****](#ch4-9)
>### 4.10 [****](#ch4-10)
>### 4.11 [****](#ch4-11)
>### 4.12 [****](#ch4-12)
>### 4.13 [****](#ch4-13)
>### 4.14 [****](#ch4-14)
>### 4.15 [****](#ch4-15)
>### 4.16 [****](#ch4-16)
>### 4.17 [****](#ch4-17)
>### 4.18 [****](#ch4-18)
>### 4.19 [****](#ch4-19)
>### 4.20 [****](#ch4-20)
>### 4.21 [****](#ch4-21)
>### 4.22 [****](#ch4-22)
>### 4.23 [****](#ch4-23)
>### 4.24 [****](#ch4-24)
>### 4.25 [****](#ch4-25)
>### 4.26 [****](#ch4-26)
>### 4.27 [****](#ch4-27)
>### 4.28 [****](#ch4-28)
>### 4.29 [****](#ch4-29)

<a href="https://github.com/bbauska/UC-Davis-Data-Manipulation-in-JS.git" target="_blank">
UC-Davis Data Manipulation in JavaScript - git</a>

<h3>Course Outline:</h3>

