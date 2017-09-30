# Array-Tools :wrench:

|Current Working Status|
|:--------------------:|
| :white_check_mark:   |

These functions were created to speed up the process of making character arrays, growing them and shrinking them.
Each of these functions works in a specific way to make coding in C (or C++) faster when it comes to creating
character arrays.

## Included Functions and What they do

| Function Name | Description | Return |Params|
|:-------------:|:-----------:|:------:|:----:|
|makeCharArray()|Produces a character array of size 1 on heap (effectively just putting a single char in memory), ending it with a null-character|char pointer|None|
|makeCharArrayOfSize()|Produces a character array of a given size on the heap, ending it with a null character.|char pointer|(int)|
|pushbackChar()|This function takes in the *Address of* an array of characters *Pointer*, along with the character to be stored at the end of the array of characters. It then creats a completely new array of one size larger, storing the given character at the end, appending a null-character at the end.|char pointer|(char *double*-pointer, char)|
|popOffChar()|This functino takes in the *Address of* an array of characters *Pointer*, then removes the furthest right character, replaxing it with the null character as long as the given array size is > 0. If the array size becomes 0, the array will be cleared from memmory and a NULL is returned|char pointer|*double*-pointer|

