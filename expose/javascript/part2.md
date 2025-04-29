1. At line 12, it will print out 3 since that is the amount of prices that were given and then entered as declared in for loop.
2. At line 13, the output will be 150. Since discountedPrice is a var is it scoped and exists throughout the code.
3. At line 14, it will output 150. Initially, finalPrice was declared as a var so just like before, it is scoped.
4. Initially, we made discounted to be an empty list, so when adding in the values through the function we would get [50, 100, 150].
5. At line 12, we will get a reference error. The reason being is that we used let inside the loop so it only exists within the loop and we make the call outside the loop.
6. Similar to the previous question, at line 13 we will get a reference error. Since discountedPrice was establihsed with let inside the loop it only exists within it.
7. At line 14, we will get the value of 150. The reason being is that because we defined it using let outside the loop but still in the function so it works as intended.
8. The function will return [50,100,150] for a similar reaosn as prior. Since we stated it using a let outside the loop it is recongnized throughout the variable.
9. At line 11 we will get another reference error since we defined i using let inside the for loop and so it is not recognized outside of it.
10. At line 12, we will get 3 because it was the fixed number of input we gave using const.
11. The function will return [50,100,150] because of each number thats input through the list and eventually multiplied by the discount and added to the list.
12.a) student.name b.) student["Grad Year"] c.) student.greeting() d.) student["Favorite Teacher"].name e.) student.courseLoad[0]
13. Arithmetic
13.a) '3' + 2 = '32'. This is because integers map to their string reperesentation.
13.b) '3' - 2 = 1. The "-" operator converts the string to its integer representation, so 3-2 = 1.
13.c) 3 + null = 3. null in integer form has the same value as 0, so 3 + 0 = 3.
13.d) '3' + null = '3null'. 3 is a string as such null is used as a string giving us the concatenation of '3null'.
13.e) true + 3 = 4. For booleans true has the value of 1, so 1 + 3 = 4.
13.f) false + null = 0. Since false takes on the value of 0 and null is 0, 0 + 0 = 0.
13.g) '3' + undefined = '3undefined'. 3 is a string, therefore undefined takes on as a string as leaves us with the concatenation of '3undefined'
13.h) '3' - undefined = NaN. We have the operator "-" meaning we mean to subtract 3 and undefined but since undefined is undefined we get NaN.
14. Comparison
14.a) '2' > 1 is true. '2' is seen as a string and the value of 2 is bigger than 1 so it evaluates to true.
14.b) '2' < '12' is false. Since they are both strings we do a string comparison and see that '2' is greater than '1' so it evalutes to false.
14.c) 2 == '2' is true. We are checking the value of the string and since its 2 and we're comparing it to 2, we know its true.
14.d) 2 === '2' is false. We are checking if they are the same value of the same type and one is a string and one isn't so it evaluates to false.
14.e) true == 2 is false. As a boolean true evaluates to 1, and 1 != 2 so it evaluates to false.
14.f) true === Boolean(2) is true. Since true is a boolean value and we are using a reference to the Boolean class, they are of the same type so it evaluates to true.
15. The == operator evluates whether or not the values are equal regardless of the primitive type used after conversion. The === operator evalutes whether or not the value and the type of the value are the exact same. 
16.) Done in javascript file.
17.) If the function is called with those parameters, modifyArray will return [2,4,6]. The reason being is that in the for loop after reading through the array, we push the callback function into a new array. The callback function multiplies each number in the array by 2 and returns it. So when we return newArr, we are left with each number multiplied by 2 in a new array.
18.) Done in javascript file.
