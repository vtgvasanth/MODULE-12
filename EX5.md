# Ex.No:5

# Ex.Name: Write the Greater than Module of Binary Search in CPP

## Date: 13/11/2025
## Aim:
To write the Greater-Than module of Binary Search in C++ that checks whether the middle element of the array is greater than the key element.

## Algorithm:
```
1. Start the function.
2. Receive the middle element `arr[mid]` and the search key.
3. Compare:

   * If `arr[mid] > key`, return `true`.
   * Otherwise return `false`.
4. End the function.
```




## Program:
```cpp
int GreaterThan(int a[], int mid, int search)
{
    if (a[mid]>search)
    {
        return 1;
    }
    else
    {
        return 0;
    }
    
}
```


## Output:
<img width="618" height="249" alt="image" src="https://github.com/user-attachments/assets/f23f8fb5-485d-41aa-9200-e68b5879919f" />



## Result:
The greaterThan module correctly checks whether the mid element of the array is greater than the key and helps guide the binary search process.
