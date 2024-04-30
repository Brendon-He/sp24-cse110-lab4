1. Line 12 will only run once and print out "3" as it is run outside of the loop. At this point, i has reached the end of the loop and must be equal to the length of prices.
2. Line 13 will print out "150" as that is the last value discountedPrice was set to after all the loops.
3. Line 14 will print out "150" as that was also the last value finalPrice was set to.
4. This function will return "[ 50, 100, 150 ]" as while finalPrice and discountPrice were constantly being changed in the loop, each iteration was being added to the discounted array, so it was being saved.
5. The code will error as i is not in the same code block as the console statement.
6. The code will error as discountedPrice is not in the same code block as the console statement.
7. The code will output "150" as finalPrice was declared and initialized in the same code block, even though it was changed in a sub code block.
8. The code will still return "[ 50, 100, 150 ]" as the discounted array was declared, initialized, edited, and returned in the same code block or a sub code block.
9. The code will error because we are trying to access i in a different code block;
10. The code will output "3" as length is a constant value.
11. The code will return "[ 50, 100, 150 ]" as the values are still being created and pushed into the discounted array without error and the array is being returned.
12. 
    a. student.name
    b. student['Grad Year']
    c. student.greeting();
    d. student['Favorite Teacher'].name
    e. student.courseLoad[0]
13. 
    a.'32' was output because 3 is treated as a string, so addition will cause it to concatenate the 2 values together. 
    b.'1' was output because the - will cause js to try and convert '3' into a number before subtracting.
    c.'3' was output because null is treated as nothing, or 0.
    d.'3null' as they are concatenated together and both treated as strings, like a
    e.'4' is output because true is treated equal to 1. 
    f.'0' as both are treated as 0.
    g.'3undefined' as they are concatenated together, like a
    h.'Nan' as undefined is'NaN' and as such you can subtract NaN from 3.
14. 
    a.true as '2' is treated as 2 and then compared to 1.
    b.false as it compares 2 and 12 as strings, and thus lexigraphically, and 1<2.
    c. True as '2' is converted into 2.
    d.False as they of different data types.
    e.False as true would be translated into a 1.
    f. True as Boolean(2) is converted into a 1, or true.
15. == Will convert both sides into numbers and compare, will === will compare the data types as well and then check if they are the same.
16. Has its on js file
17. The output will be "[2,4,6]" as modifyArray will take in the array [1,2,3] and perform the function doSomething() on each value, beig doubling the value, before inserting in a new array in the same position it was in the old array.
18.  has its own js file
19. 1234