# Module2_VBA_Challenge
Module 2 VBA Challenge
**Overview of Project:**

_ **Refactoring** _: It is restructure (the source code of an application or piece of software) so as to improve operation without altering functionality.

This Project is all about Refactoring where we are trying to improve the performance of the original code.

Using this analysis we are trying to find out - total daily volume and yearly return for each stock without iterating though whole database again and again.

We have used arrays in the refactored code to store the values in arrays so that it is easy to modify so value and retrieving the value using array indexes.

**Results:**

The year 2017 performed very well as compared to the year 2018. The Returns are more in 2017 as compared in to 2018 year.

Stock – TERL did not perform in both the years.

Stock – DQ performed best in year 2017.

1. _Processing time for Original Code:_
  1. 2017: 5.73 seconds
  2. 2018: 5.40 seconds

1. _Processing time for Refactored Code:_

    1. 2017: 0.49 seconds
    2. 2018:0.49 seconds

![Refactored code run time for the year 2017](../Resources/VBA challenge\_Refactored\_2017.png)

![Refactored code run time for the year 2018](../Resources/VBA Challenge\_Refactored\_2018.png)

**Summary**

_Advantages and Disadvantages of refactoring code_

**ADVANTAGES:**

1. It improves the design of software.
2. It makes software easier to understand.
3. It helps finding bugs.
4. It helps programming faster.
5. It makes the code more efficient—by taking fewer steps, using less memory, or improving the logic of the code to make it easier for future users to read.

**DISADVANTAGES:**

1. It is hard to refactor the code when the application is big.
2. It&#39;s risky when developers do not understand what&#39;s all about
3. We have the same working code before and we just refactored it.
4. It is time consuming to refactor a code.
5. We may have no idea how much time it may take to complete the process. It may also land you into a situation where you have no idea where to go.
6. When refactoring code, we aren&#39;t adding new functionality

**Pros and Cons apply to refactoring the original VBA script** :

_Pros_:

-Execution time reduced.

_Cons_:

-Functionality remained same. Not much change in the functionality.

-We have fixed size arrays. Code can only accumulate data till 12 values. If there will be more stocks in the future then we have to change the arrays index also.

-It took time to understand the logic used to refactor the code.
