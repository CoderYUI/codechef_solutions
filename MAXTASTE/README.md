# Problem

**Problem URL:** [https://www.codechef.com/practice/course/logical-problems/DIFF800/problems/MAXTASTE?tab=statement](https://www.codechef.com/practice/course/logical-problems/DIFF800/problems/MAXTASTE?tab=statement)

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
		while(t-- > 0){
		    int a = sc.nextInt(), b = sc.nextInt(), c = sc.nextInt(), d = sc.nextInt();
		    
		    System.out.println(Math.max(a,b)+ Math.max(c,d));
		}

	}
}
```
