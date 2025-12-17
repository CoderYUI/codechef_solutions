# Problem

**Problem URL:** [https://www.codechef.com/practice/course/logical-problems/DIFF800/problems/SST](https://www.codechef.com/practice/course/logical-problems/DIFF800/problems/SST)

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
		int t= sc.nextInt();
		
		while (t-->0){
		    int x = sc.nextInt();
		    int y = sc.nextInt();
		    
		    if ((10*x)>(5*y)) System.out.println("First");
		    else if ((10*x)<(5*y)) System.out.println("Second");
		    else System.out.println("ANY");
		  
		}

	}
}
```
