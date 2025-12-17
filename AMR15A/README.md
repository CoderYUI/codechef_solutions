# Problem

**Problem URL:** [https://www.codechef.com/practice/course/logical-problems/DIFF800/problems/AMR15A](https://www.codechef.com/practice/course/logical-problems/DIFF800/problems/AMR15A)

## Solution

```java
import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// Taking the array input (maybe not in a optimized way)
		Scanner sc = new Scanner(System.in);
		int n = sc.nextInt();
		int arr[] = new int[n];
		for (int i=0; i<n; i++){
		    arr[i] = sc.nextInt();
		}
		
		// checking the inner elements of an array
		int lucky = 0, notLucky = 0;
		for (int nums:arr){
		    if (nums%2 ==0) lucky++;
		    else notLucky++;
		}
		
		// normal if else
		if (lucky>notLucky) System.out.println("READY FOR BATTLE");
		else System.out.println("NOT READY");

	}
}

// THIS IS OPTIMIZED ONE

/*public static void main (String[] args) throws java.lang.Exception
{
	Scanner sc = new Scanner(System.in);
	int n = sc.nextInt();
	int cnt = 0;
	for(int i=1; i<=n; i++) {
		int x;
		x = sc.nextInt();
		if( x % 2 == 0 ) {
			cnt ++;
		}
	}
	System.out.println( cnt > n - cnt ? "READY FOR BATTLE" : "NOT READY" );	
}*/
```
