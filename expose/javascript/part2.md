12A. student.name;
12B. student['Grad Year'];
12C. student.greeting();
12D. student['Favorite Teacher'].name;
12E. student.courseLoad[0];

13A. 32 - When we use the + operator in javascript, if the first number is a string, the result is concatenated.
13B. 31 - When we use the - operator in javascript and if the first number is a string, then it automatically converts the string to a number and performs the subtraction
13C. 3 - This is because javascript treats null as 0
13D. 3null - Since '3' is a string, the result is concatenated
13E. 4 - The boolean 'true' is converted to a 1
13F. 0 - False and null are both treated as numeric values of 0
13G. 3undefined - Since '3' is a string, the result is concatenated
13H. Nan (not a number) - Since we are using subtract with a string, javascript tries to convert both operands into numbers

14A. true - javascript converts the string '2' to the number 2, and then compares it to 1
14B. false - When comparing strings, javascript uses lexicographical order
14C. true - Here, javascript performs type conversion. It converts the string '2' to the number 2
14D. false - The '===' comparison checks both value and type without converting them, and they are of different types
14E. false - for this comparison, true is converted to 1, and 1 does not equal 2.
14F. true - The Boolean(2) converts 2 to true, because in javascript any non-zero number is truthy


15.  '==' compares two values for equality after performing type conversion if needed. if the values being compared are not of the same type, javascript tries to convert them into a common type before making the comparison. '==='  operator compares both the value and the type, meaning if the values being compared have different types, the comparison will immediately return false.

17. The function goes as follows:

    modifyArray is called with [1,2,3] as the array and doSomething as the callback function
    The newArr array is initialized as an empty array
    The for loop starts. On each iteration, the current array element is passed to the doSomething function
    The doSomething function takes the input number, multiplies it by 2, and returns the result
    The result is pushed onto newArr
    After the loop finishes, newArr contains the doubled values of the original array

Hence, the final array returned by modifyArray is [2, 4, 6].

19. The output is:
    1
    4
    3
    2






