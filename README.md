# Virtual Calculator

The calculator app is an app I made from Processing java, finished in 3 days and first programmed on Eclipse. 

7/19/2018
Release v.1.0.1
Calculator

The app consists of numbers, *, +, ^, %(modulus), -, =, and . (Working)
I have yet to add +/-, √, trigonometry, %(percent)
I also plan on making it easier, more efficient, and reduce the large amount of repeated code that there is already with the current method.
Finishing touches will include 
- making the colors and design more professional, higher quality,
- mouse hover making the button display change in some way

8/30/2018
Release v1.1.4
The Key Update

The Key Update introduces newly written code with regular expressions, key-based input for numbers and operations, and negatives! The calculator app is still in beta, so stay tuned for adding multiple operations at once and parenthesis! (())

8/28/2018
Release v1.1.2
The Regular Expression Update

The app calculations are now refactored to be called from a single method in the Operation class
This app uses regular expressions
	There are now negatives
	Resolved issue with text repeating
	When there are supposed to be errors, the program simply doesn't try to do the operation because the expression isn't valid
The less precision is still a problem even though the floats are not 
Overall, the app is much easier to code, use, and update

12/16/2018
Release v1.2.0
The Hover Update

New Operations! root, reciprocal, and x^2
Refactored GridSquare new instances, so now it is easier to lay out the calculator button texts in the 2-D array textToDisplay String[][]
The calculator looks more professional
The buttons now light up on mouse hover



