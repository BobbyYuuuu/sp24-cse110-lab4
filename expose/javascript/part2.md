1. 3 will be printed because i was declared as a var in line 6, so i is accessable outside of the scope. Then i is incremented 3 times because the length of the prices array that is passed in as the parameter is 3, so i = 3 after the loop.
2. 150 will be printed by line 13 the discountedPrice stores the last calculation result in the loop because it is updated every loop. Hence it would be 300 * (1-0.5) which is 150. The discountedPrice is also accessable outside of the scope because it is declared by var.
3. 150 will be printed by line 14 because finalPrice basically will store the same value as discountedPrice if the discountedPrice is a integer. Then finalPrice was declared as a var in the beginning at line 4, hence it is accessible outside of the scope, so it stores the same value as discountedPrice and will print out 150.
4. The function will return an array [50, 100, 150] because essentiall the function will take in the price array and multiply it by the discount parameter. In this case it is [100, 200, 300] and discount is 0.5. Hence it will multiply each of the integers in the array by 0.5, and push it into the discounted array, which results in [50, 100, 150], and then this array will be returned by the function.
5. It will return an error because i is defined by let in the loop, hence it is not accessible outside of its scope and we can't access it outside of the for loop, and it will return an error when we try to print it.
6. Same reason as number 5, because discountedPrice is declared with let, we are not able to access it outside of the scope, so that means it is only accessable inside the for loop but not outside.
7. 150 will be printed out by line 14 because although it was declared with let, it was declared outside of the for loop and inside the same scope as line 14. That means line 14 can access the finalPrice variable. Then it goes through the same process as question 3 and stores the most recent calculated finalPrice value inside the for loop, which is 150 in this case.
8. The function will return the array [50, 100, 150] with the same reason as question 4. Although this time variables are declared by let instead of var, but all the variables are used inside the block scope that it is in, hence it will not cause an error and just perform the same calculation as the one in question 4 and the push them into the discounted array and gets returned.
9. It will run in to an error because in line 6, we declared i by let, that means it will not be accessable outside its scope, which after the for loop, we are not able to access it anymore, so it will cause an error.
10. It will print out 3 because length is declared as a const variable with the length of the input prices array, in this case it is 3. After the declaration, we did not make any changes to the length variable, hence it will remain as 3. Although it is declared as a const varaible, it is declared inside the same scope as the console.log() function, so we will not have an error trying to print the length variable out.
11. It will return the array [50, 100, 150], although the discounted array is declared by const, it is in the same scope as all the other parts of the function, hence there will be no problem pushing element into this array. The function itself follows the same process as question 4 and 8, it does a calculation based on the input ([100, 200, 300], 0.5), multiplying each of the element in the input array by the 1 - discount input. Hence at the end, discounted will be [50, 100, 150] and then get returned by the function.
12. a. student.name 
    b. student['Grad Year'] 
    c. student.greeting() 
    d. student['Favorite Teacer'].name 
    e. student.courseLoad[0] 
13. a. it outputs '32' because javascript converts the 2 into '2', then '3'+'2' will be a string addition which equals to '32' 
    b. it outputs 1 because javascript converts the '3' into integer 3, and then 3-2 would be integer subtraction which equals to 1 
    c. it outputs 3 because null is mapped into 0 in javascript, hence 3 + 0 would just be equal to 3 
    d. it outputs '3null' because javascript converts null into 'null', then '3'+'null' would be a string addition equal to '3null' 
    e. it outputs 4 because true is mapped into 1 in javascript, hence 3 + 1 would be equal to 4 
    f. it outputs 0 because false is mapped to 0 in javascrip since it is boolean, and null would also mapp into 0 in javascript, so 0+0=0
    g. it outputs '3undefined' because javascript converts undefined into 'undefined', hence '3'+'undefined' = '3undefined' by javascript type conversion
    h. it outputs NaN because '3' is a string, and undefined is just undefined, hence we are doing math operation on two non-integer element, which results in Not-a-Number
14. a. it outputs true because '2' is converted into 2 by javascript conver, and integer 2 is greater than 1, which returns true
    b. it outputs false because it compares '2' with '12', and by string order alphabetically, it compares '2' with '1', in which '2' is greater than '1', hence '2' < '12' returns false
    c. it outputs true because '2' is converted into 2 by javascript, hence 2==2 is true
    d. it outputs false because === means that it has to be equal value and equal type, but since 2 is an integer and '2' is a string, hence '2'===2 outputs false
    e. it outputs false because true is mapped to the integer 1, and 1 != 2, hence it outputs false
    d. it outputs true because Boolean(2) = true if it is passed in any value excpet for values like 0 and false, hence true === true would output true since they are equal type and equal value.
15. == checks for equal value, but the == would perform type conversion. On the other hand, === checks for equal value but does not perform tyoe convserion. For example, 2=='2' is true but 2==='2' is false because this first one is true only if type conversion was performed
17. The result would be the array [2,4,6] because we are allowed to use a function as a parameter, then in the modifyArray function, we pass in the original array as an parameter, which is [1,2,3], then we declared a const empty array. Then inside the for loop, what it does is that it applys the doSomething function to each elements inside the parameter array, in this case, it multiplies the element by 2 and then push it into the declared array. Hence we will have 1*2, 2*2, 3*2, which is 2,4,6 pushed into the array, finally this array will be returned.
19. 1

    4
    
    3
    
    2
