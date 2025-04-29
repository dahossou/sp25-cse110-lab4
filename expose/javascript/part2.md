1. At line 12, it will print out 3 since that is the amount of prices that were given and then entered as declared in for loop.
2. At line 13, the output will be 150. Since discountedPrice is a var is it scoped and exists throughout the code.
3. At line 14, it will output 150. Initially, finalPrice was declared as a var so just like before, it is scoped.
4. Initially, we made discounted to be an empty list, so when adding in the values through the function we would get [50, 100, 150].
5. At line 12, we will get a reference error. The reason being is that we used let inside the loop so it only exists within the loop and we make the call outside the loop.
6. Similar to the previous question, at line 13 we will get a reference error. Since discountedPrice was establihsed with let inside the loop it only exists within it.
7. At line 14, we will get the value of 150. The reason being is that because we defined it using let outside the loop but still in the function so it works as intended.
8. The function will return [50,100,150] for a similar reaosn as prior. Since we stated it using a let outside the loop it is recongnized throughout the variable.
9. 

