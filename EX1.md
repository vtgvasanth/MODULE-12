# Ex.No:1

# Ex.Name: Write a CPP Program to get the elements of an Array which needs to be sorted using insertion sort.

## Date: 13/11/2025

## Aim:
To write a C++ program to get the elements of an array from the user and sort the array using Insertion Sort.

## Algorithm:
```
1. Start the program.
2. Read the number of elements `n`.
3. Read `n` elements into the array.
4. Perform insertion sort:

   * For each element from index 1 to n−1:

     * Store the current element as `key`.
     * Compare `key` with previous elements and shift them if greater.
     * Insert `key` in its correct sorted position.
5. Print the sorted array.
6. Stop the program.
```




## Program:
```cpp
void input(int arr[])
{
    for(int i=0;i<5;i++)
    cin>>arr[i];
    
}
```


## Output:
<img width="645" height="342" alt="image" src="https://github.com/user-attachments/assets/cca96e90-94c3-4e26-87a9-9a8dac60da4b" />



 ## Result:
The program successfully accepts array elements from the user and displays the array sorted using insertion sort.

