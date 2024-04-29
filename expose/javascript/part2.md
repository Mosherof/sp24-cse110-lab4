1. 3 because var means that the variable i will exist for the entirety. i is incremented everytime the forloop is run until it is no longer less than the length of prices. Since the length is 3, i stops at 3.
2. 150. Since discountedPrice is defined by var, it is will exist even outside the scope. The last value the discountedPrice was given was the last element of the list of prices (300) times 0.5 which is therefore 150.
3. 150. Since final price is defined by var, it will exist even oustide the scope. The last value found for finalPrice is given by rounding the discounted price so that it is given to the nearest cent. By similar logic, it stays the same.
4. [ 50, 100, 150 ]. We are inputting a list of three prices (100, 200, 300), and a discount rate of .5. The function goes through each price, and multplies it by 1 - the discount. Then, this number is stored into the discounted array object. Therefore the price of 100 becomes 50, the price of 200 becomes 100, and the price of 300 becomes 150.
5. An error is thrown becaue since i is assigned with "let", it only exists within the scope of the for loop, and line 12 is outside of this.
6. An error is thrown becaue since discountedPrice is assigned with "let", it only exists within the scope of the for loop, and line 13 is outside of this.
7. 150. finalPrice is last set by the last price in the list * (1- discount) and then rounded to the nearest cent. Since it was originally defined at the top, it is accessible to be logged into the console.
8. [ 50, 100, 150 ]. Similar logic to answer #4, but the main difference is that instead of using var to define most variables, using let means that they only exist within a scope of the code instead of throughout. However, since discounted is defined at the top, it is still reachable so can be returned as the correct value.
9. Error occurred because i has not been defined in this scope.
10. 3. The length is a contant value as the size of prices never changes. Because it is defined at the top of the function, it is accessible to be logged into the console. The list is put in as a parameter as [100, 200, 300] and has three items. This the length = 3.
11. [ 50, 100, 150 ]. It is able to be returned because it is defineed at the top of the function and is therefore in scope. While const means that the variable can't be reassigned, it is able to be manipulated and therefore allows values to be pushed in. The values also hold similar logic to that in answer #4.
12. Notations
    A. student.name
    B. student['Gsrad Year']
    C. student[greeting]
    D. student['Favorite Teacher'].name
    E. student.courseLoad[0]
13.
    A. '32' because they are concatenated like a string
    B. 1 because '-' only exists as a subtraction assignment so '3' is converted to 3
    C. 3 because null is converted to 0
    D. '3null' because null is converted to a string type
    E. 4 because true is converted to 1
    F. 0 because false is converted to 0 and null is converted to 0
    G. '3undefined' because undefined is converted to a string
    H. NaN because undefined has no numeric value and so it can't be subtracted from '3'
14.
    A. true because 1 can be converted to '1' and it comes before '2' in the ASCII table
    B. false because '12' starts with '1' which comes before '2' in the ASCII table and is therefore smaller
    C. true because '2' can be converted to 2.
    D. false because they have different types (number and string)
    E. false because false = 0 and 0 doesn't equal 2.
    F. true because 2 is not intuitively empty and thus, Boolean(2) is set to true.
15.  The "==" operator only checks if the left and right side are equal whereas the "===" operator is a strict equality check where the types must match as well. 
16.  Algorithm found at /part2-question16.js
17. [2, 4, 6]. Modify array itterates through each number in array. When it does this, it passes the number into the callback function which in this case is doSomething. doSomething returns the number doubled. This value is then pushed into newArr and newArr is returned. Thus the resulting result would be an array which doubles each number in the original array.
18. Algorithm found /part2-question18.js
19. The output should be the following:
    ```
    1
    4
    3
    2
    ```
    