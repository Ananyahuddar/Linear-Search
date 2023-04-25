# Linear-Search

Linear search in C to find whether a number is present in an array. If it's present, then at what location it occurs. It is also known as a sequential search. It is straightforward and works as follows: we compare each element with the element to search until we find it or the list ends. Linear search for multiple occurrences and using a function.

# Algorithm
1.Start with the main function.
2.Declare an integer array 'arr' and initialize it with values.
3.Declare an integer variable 'n' and assign the number of elements in the array 'arr'. Alternatively, you can calculate 'n' as: sizeof(arr) / sizeof(arr[0]).
4.Declare an integer variable 'target' and assign the value to be searched.
5.Call the 'linear_search' function with arguments: 'arr', 'n', and 'target'.
6.Inside the 'linear_search' function:
a. Declare an integer variable 'i' to use as a loop counter.
b. Loop through the array 'arr' from index 0 to 'n-1' using a 'for' loop.
i. Check if the element at the current index 'i' is equal to the target value.
ii. If yes, return the index 'i' as the result.
c. If the loop completes without finding the target value, return -1 as the result.
7.Back in the main function:
a. Store the result of the 'linear_search' function in an integer variable 'result'.
b. Check if 'result' is equal to -1.
i. If yes, print "Target value not found in the array."
ii. If no, print "Target value found at index: " followed by the value of 'result'.
8.End the main function.

![image](https://user-images.githubusercontent.com/125941580/234327045-da560118-b992-4591-b315-162b0d0727d1.png)

# Working of Linear search
Now, let's see the working of the linear search Algorithm.

To understand the working of linear search algorithm, let's take an unsorted array. It will be easy to understand the working of linear search with an example.

Let the elements of array are -

Linear Search Algorithm
Let the element to be searched is K = 41

Now, start from the first element and compare K with each element of the array.

Linear Search Algorithm
The value of K, i.e., 41, is not matched with the first element of the array. So, move to the next element. And follow the same process until the respective element is found.

Linear Search Algorithm
Now, the element to be searched is found. So algorithm will return the index of the element matched.
