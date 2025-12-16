# Problem

**Problem URL:** [https://www.codechef.com/practice/course/logical-problems/DIFF800/problems/SUBSCRIBE_?tab=statement](https://www.codechef.com/practice/course/logical-problems/DIFF800/problems/SUBSCRIBE_?tab=statement)

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
	    
	    while (t--> 0) {
	        int x = sc.nextInt();
	        int y = sc.nextInt();
	        
	        int z = x/6;
	        if (x%6!=0) z++;
	        
	        System.out.println(z*y);
	        
	    }

	}
}
```
