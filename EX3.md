# Ex.No:3

# Ex.Name: Write the quickSort module of Quick Sort in CPP.

## Date: 13/11/2025

## Aim:
To write the quickSort module of the Quick Sort algorithm in C++ to sort an array using divide-and-conquer technique.

## Algorithm:
```
1. Choose a pivot element (usually the last element).
2. Partition the array such that:

   * Elements smaller than pivot come before it.
   * Elements greater than pivot come after it.
3. Recursively apply quickSort on the left sub-array.
4. Recursively apply quickSort on the right sub-array.
5. Stop when the sub-array has one or zero elements.
```




## Program:
```cpp
void quickSort(int array[], int low, int high) 
{
    if(low<high)
    {
        int pi=partition(array,low,high);
        quickSort(array,low,pi-1);
        quickSort(array,pi+1,high);
    }
    
}
```


## Output:
<img width="688" height="210" alt="image" src="https://github.com/user-attachments/assets/02b34c3b-f066-4288-864e-5babd005056e" />



## Result:
The quickSort module correctly sorts the array using the Quick Sort algorithm.
