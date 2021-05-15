# ReverseArrayInPlace

```java
class Solution {
    public int[] reverseArray(int[] arr) {
        int temp, iStart = 0, iEnd = arr.length - 1;
        while (iStart < iEnd) {
            temp = arr[iStart];
            arr[iStart] = arr[iEnd];
            arr[iEnd] = temp;
            iStart++;
            iEnd--;
        }
        return arr;
    }
 }
 ```
