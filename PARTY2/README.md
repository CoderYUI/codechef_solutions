# Problem

**Problem URL:** [https://www.codechef.com/practice/course/basic-programming-concepts/DIFF500/problems/PARTY2](https://www.codechef.com/practice/course/basic-programming-concepts/DIFF500/problems/PARTY2)

## Solution

```java
import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
		Scanner sc = new Scanner(System.in);
		int t = sc.nextInt();
		while (t-- > 0){
		    
		    int n = sc.nextInt();
		    int x = sc.nextInt();
		    int k = sc.nextInt();
		    
		    if ((n*x)<=k) System.out.println("YES");
		    else System.out.println("NO");
		}
	}
}
```
