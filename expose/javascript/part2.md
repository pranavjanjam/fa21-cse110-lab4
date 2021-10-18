1. Line 12 prints '3', which is the length of the array 'prices'. This is because the variable 'i' is used to iterate through the array, so with the for-loop, it starts at 0 and ends as the length of the array.
2. Line 13 prints '150' because for each value in the 'prices' array, the 'discountedPrice' value is set to the "price" multiplied by (1 - 'discount'). So, after the for-loop, 'discountedPrice' is set to the last price in the array multiplied by (1 - 'discount'). In this case, it is 300 * (1 - 0.5) = 150.
3. Line 14 prints '150' because 'finalPrice' is simply 'discountedPrice' multiplied by 100, rounded, then divided by 100. In this case, it is 150 * 100, rounded, which is 15000, then, divided by 100, which is 15000 / 100 = 150.
4. This function returns '[50, 100, 150]'. It is looping through the original 'prices' array, and for each price, it calculates the discounted price. It then pushes this to a new array called 'discounted'. After doing this for each price value, it returns the 'discounted' array. Since the original prices array is [100, 200, 300] and the discount is 0.5, then discounted prices array is [50, 100, 150].
5. The code causes an error, since 'i' is a let variable and declared within the for-loop. Therefore, 'i' is not accessible outside of the for-loop, since let variables are block-scope.
6. The code causes an error, since 'discountedPrice' is a let variable and declared within the for-loop. Therefore, 'discountedPrice' is not accessible outside of the for-loop, since let variables are block-scope.
7. Line 14 prints '150' because 'finalPrice' is simply 'discountedPrice' multiplied by 100, rounded, then divided by 100. In this case, it is 150 * 100, rounded, which is 15000, then, divided by 100, which is 15000 / 100 = 150. It is within the scope, since 'finalPrice' is declared within the function and line 14 is within the function.
8. This function returns '[50, 100, 150]'. It is looping through the original 'prices' array, and for each price, it calculates the discounted price. It then pushes this to a new array called 'discounted'. After doing this for each price value, it returns the 'discounted' array. Since the original prices array is [100, 200, 300] and the discount is 0.5, then discounted prices array is [50, 100, 150].
9. The code causes an error, since 'i' is a let variable and declared within the for-loop. Therefore, 'i' is not accessible outside of the for-loop, since let variables are block-scope.
10. Line 12 prints '3' because 'length' is initialized with the value of 'prices.length'. It is a const variable and the value is never changed. Since, the length of the 'prices' array is 3, the value of 'length' is 3.
11. This function returns '[50, 100, 150]'. It is looping through the original 'prices' array, and for each price, it calculates the discounted price. It then pushes this to a new array called 'discounted'. After doing this for each price value, it returns the 'discounted' array. Since the original prices array is [100, 200, 300] and the discount is 0.5, then discounted prices array is [50, 100, 150].
12. \
    a) student.name \
    b) student['Grad Year'] \
    c) student.greeting() \
    d) student['Favorite Teacher'].name \
    e) student.courseLoad[0]
13. \
    a) '32' because the integer 2 is converted into a string, and then string concatenation is executed. \
    b) 1 because the string '3' is converted into an integer, and then subtraction is executed. \
    c) 3 because null is being added to the integer 3, and in mathematical expression, null becomes equivalent to 0. \
    d) '3null' because null is being added to the string '3', so then null is converted to the string 'null', and string concatenation is executed. \
    e) 4 because true is being added to the integer 3, and in mathematical expression, true becomes equivalent to 1. \
    f) 0 because in mathematical expression, false and null both become equivalent to 0. \
    g) '3undefined' because undefined is being added to the string '3', so then undefined is converted to the string 'undefined', and string concatenation is executed. \
    h) NaN because in mathematical expression, undefined becomes NaN and cannot be added to an integer.
14. \
    a) True because in string/integer comparison, '2' becomes the integer 2. \
    b) False because in string comparison, the first characters are compared, and '2' > '1'. \
    c) True because in string/integer comparison, '2' becomes the integer 2. \
    d) False because === also compares types, and the two values are of different types. \
    e) False because in Boolean/integer comparison, true because the integer 1. \
    f) True because Boolean(2) is equivalent to true.
15. == and === are different because === checks for type equality, whereas == allows for type conversions.
16. Answer in part2-question16.js
17. The result is '[2, 4, 6]'. The 'modifyArray' function takes in an array 'array' and a function 'callback' as parameters. The function then initializes a new empty array called 'newArr'. Then, the function iterates through 'array' and performs the 'callback' function on each element of the array. It then pushes each modified element to 'newArr', and then returns 'newArr'. In this case, the 'callback' function ('doSomething') multiplies each element by 2. So, the [1, 2, 3] array becomes modified to [2, 4, 6].
18. Answer in part2-question18.js
19. The output is 1 4 3 2.