1. 3 since i represents the iterations from prices array and prices array has a length of 3. 
2. 150 since the discountedprice recorded last discounted price, which is 300*0.5=150. 
3. 150 since the final price record last discounted price. 
4. [50, 100, 150] since they are all var variable. for each input prices, it calculated discounted prices and push it to discounted array. Which returns [50, 100, 150].
5. error occured. since i(let) is scope variable, it only lives inside the for loop block.
6. error occured. since discountedPrice(let) is scope variable, it only lives inside the for loop block.
7. 150 since finalPrice live inside the function block, so it can be called.  
8. [50, 100, 150] discounted(let) lives inside whole function block.
9. error occured since i(let) is scope variable, it only lives inside the for loop block.
10. 3 since length(const) is already defined as prices array length in function block and never be modified. 
11. [50, 100, 150] since adding elements to discounted(const) array is not redeclaring or reasigning constant, so push is allowed and it returned array with three elements. 
12.  Given the above Object, write the notation for:  (These should be in your part2.md)
    1.  student.name 
    2.  student['Grad Year']
    3.  student.greeting(); 
    4.  student['Favorite Teacher'].name  
    5.  student.courseload[0]
13. Arithmetic
    1. ‘3’ + 2 output:32 since integers map to their exact string representation
    2. ‘3’ - 2 output:1 since the number is “read” from the string
    3. 3 + null output:3 since null maps to 0
    4. ‘3’ + null output:3null since null map to their exact string representation
    5. true + 3 output:4 since true maps to 1
    6. false + null output:0 since false maps to 0 and null maps to 0
    7. '3' + undefined output:3undedined since undefined map to their exact string representation
    8. '3' - undefined output:NaN since undefined maps to NaN when converted to integer
14. Comparison
    1.  ‘2’ > 1 output:true since string '2' becomes a number 2 and the first character of 1 strings is 1 is less than 2
    2.  ‘2’ < ‘12’ output:false since the first character of '12' strings is '1' is less than '2'
    3.  2 == ‘2’ output:true since type conversons make '2' becomes 2 in integer
    4.  2 === ‘2’ output:false since there is no type conversion and they are different types.
    5.  true == 2 output:false since true is converted to 1. 
    6.  true === Boolean(2) output:true since Boolean(2) outputs true. 
15.  === checks the equality without type conversion. == checks equality with type conversion. 
16. [2, 4, 6] since in the for loop, each element in the array is called with the dosomething function (which doubled the value) and new value is pushed to newArr. And newArr is returned by modifyArray.
17.  What is the output of the above code? (This should be in your part2.md)
    1
    4
    3
    2
