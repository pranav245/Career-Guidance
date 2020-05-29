# Career-Guidance

In this project user will enter the marks of different subjects and then we are predicting their stream in which he/she can start their carrer using fuzzy inference system.

## Fuzzy Logic

The term fuzzy refers to things which are not clear or are vague. In the real world many times we encounter a situation when we can’t determine whether the state is true or false, their fuzzy logic provides a very valuable flexibility for reasoning. In this way, we can consider the inaccuracies and uncertainties of any situation.

In boolean system truth value, 1.0 represents absolute truth value and 0.0 represents absolute false value. But in the fuzzy system, there is no logic for absolute truth and absolute false value. But in fuzzy logic, there is intermediate value too present which is partially true and partially false.


![fuzzy-logic_1](https://user-images.githubusercontent.com/42700950/68443217-4be4ed00-01f9-11ea-8d4f-dcdd6f629041.png)

## ARCHITECTURE

Its Architecture contains four parts :

##### 1) RULE BASE : 
It contains the set of rules and the IF-THEN conditions provided by the experts to govern the decision making system, on the basis of linguistic information. Recent developments in fuzzy theory offer several effective methods for the design and tuning of fuzzy controllers. Most of these developments reduce the number of fuzzy rules.

##### 2) FUZZIFICATION :
It is used to convert inputs i.e. crisp numbers into fuzzy sets. Crisp inputs are basically the exact inputs measured by sensors and passed into the control system for processing, such as temperature, pressure, rpm’s, etc.

##### 3) INFERENCE ENGINE :
It determines the matching degree of the current fuzzy input with respect to each rule and decides which rules are to be fired according to the input field. Next, the fired rules are combined to form the control actions.

##### 4) DEFUZZIFICATION :
It is used to convert the fuzzy sets obtained by inference engine into a crisp value. There are several defuzzification methods available and the best suited one is used with a specific expert system to reduce the error.

![fuzzylogic_architecture](https://user-images.githubusercontent.com/42700950/68443662-a3378d00-01fa-11ea-9390-a4a8aeddcf90.png)

## Membership function

A graph that defines how each point in the input space is mapped to membership value between 0 and 1. Input space is often referred as the universe of discourse or universal set (u), which contain all the possible elements of concern in each particular application.
There are largely three types of fuzzifiers:

Singleton fuzzifier
Gaussian fuzzifier
Trapezoidal or triangular fuzzifier

##### These are all the concepts that are used in this project so before moving to code make sure you have gone to them atleast once.



## Step by Step approach for creating the Model

##### Step 1
Importing all necessary modules
 
##### Step 2
We decide our input subject and make function.
(Antecedent Function)

##### Step 3
Divede our input antecedent in different different categories
on the basis of defined range that is if it is between 70 to 100 then it is excellent

##### Step 4
Add proffesion and make function. 
(Consequent Function)

##### Step 5
We divide our consequent variable into different categories using automf function.

##### Step 6
Made rules and using Control system function merge all the rules.

##### Step 7
Using ControlSystemSimulation Function we simulate the rules.

##### Step 8
Making of GUI using django.


