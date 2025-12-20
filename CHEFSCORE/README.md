# Problem

**Problem URL:** [https://www.codechef.com/practice/course/logical-problems/DIFF800/problems/CHEFSCORE](https://www.codechef.com/practice/course/logical-problems/DIFF800/problems/CHEFSCORE)

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
		
		while (t-- >0){
		    int n = sc.nextInt();
		    int x = sc.nextInt();
		    int y = sc.nextInt();
		    
		    if (y%x == 0 ){
		        if (n*x >= y) System.out.println("yes");
		        else System.out.println("NO");
		    }
		    else System.out.println("NO");
		}

	}
}
```
