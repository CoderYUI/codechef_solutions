# Problem

**Problem URL:** [https://www.codechef.com/practice/course/logical-problems/DIFF800/problems/MONOPOLY2?tab=solution](https://www.codechef.com/practice/course/logical-problems/DIFF800/problems/MONOPOLY2?tab=solution)

## Solution

```java
import java.util.*;
import java.lang.*;
import java.io.*;


//My asuumption

/*class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
		Scanner sc = new Scanner(System.in);
		int arr[] = new int[4];
		int t = sc.nextInt();
		while(t-- >0){
		    arr[0] = sc.nextInt();
		    arr[1] = sc.nextInt();
		    arr[2] = sc.nextInt();
		    arr[3] = sc.nextInt();
		    
		    Arrays.sort(arr);
		    int sum = arr[0] + arr[1] + arr[2];
		    if (sum < arr[3] ) System.out.println("YES");
		    else System.out.println("NO");
		    
		}

	}
}*/

// Optimised
class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
		Scanner sc = new Scanner(System.in);
	
		int t = sc.nextInt();
		while(t-- >0){
		   int a = sc.nextInt();
		   int b = sc.nextInt();
		   int c = sc.nextInt();
		   int d = sc.nextInt();
		   
		   if (a> b+c+d) System.out.println("YES");
		   else if (b> a+c+d) System.out.println("YES");
		   else if (c>a+b+d) System.out.println("YES");
		   else if (d>a+b+c) System.out.println("YES");
		   else System.out.println("NO");
		    
		}

	}
}
```
