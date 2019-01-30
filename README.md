# quiz-7-corrections

6. An IndexOutOfBoundsException will be thrown in this case because the ArrayList doesn't have any values in it yet, so trying to get 0 wouldn't return anything because ArrayLists grow as you put values into them.

7. list.set(y, list.set(x, list.get(y)); would also work to swap x and y, because it gets y and sets it to x which then sets y to the x.

8. names.remove("Carlos"); & names.remove(2); would remove Carlos without disrupting the order because ArrayLists start at index 0, making Carlos index 2, and since the ArrayList has a String wrapper just opting to remove "Carlos" would work too.

10. This code would return Boston because it takes the elements of the String and adds it to the ArrayList that the value is then selected from.

11. As seen in question 8, using the remove method with index or value both automatically shift the array elements to preserve order.

(#12) I'm not sure where the middle answer came from that was marked wrong... but length is a property of an array whereas size is a function of the ArrayList class. Syntactically, this difference is shown by either the presence of absence of parenthesis.

13. numbers.forEach((number) -> System.out.println(number)); would also work to traverse through the array and print each value in the array as expressed by the lambda. 
