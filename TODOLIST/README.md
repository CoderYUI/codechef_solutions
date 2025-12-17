# Problem

**Problem URL:** [https://www.codechef.com/practice/course/logical-problems/DIFF800/problems/TODOLIST?tab=statement](https://www.codechef.com/practice/course/logical-problems/DIFF800/problems/TODOLIST?tab=statement)

## Solution

```java
import java.util.*;
import java.lang.*;
import java.io.*;

/*class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
		Scanner sc = new Scanner(System.in);
		int t = sc.nextInt();
		
		while(t-- >0){
		    int n = sc.nextInt();
		    int arr[] = new int[n];
		    
		    for(int i=0; i<n; i++){
		        arr[i] = sc.nextInt();
		    }
		    int count = 0;
		    for (int nums : arr){
		        if (nums>=1000) count++;
		    }
		    System.out.println(count);
		}

	}
}
*/

//Optimised

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		Scanner sc = new Scanner(System.in);
		int t = sc.nextInt();
		while(t-- >0) {
		    int n = sc.nextInt();
		    int ans =0;
		    for(int i=0;i<n;i++) {
		        int x = sc.nextInt();
		        if (x>=1000) {
		            ans++;
		        }
		    }
		    System.out.println(ans);
		}
	}
}
```
