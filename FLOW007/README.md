# Problem

**Problem URL:** [https://www.codechef.com/practice/course/logical-problems/DIFF800/problems/FLOW007?tab=statement](https://www.codechef.com/practice/course/logical-problems/DIFF800/problems/FLOW007?tab=statement)

## Solution

```java
import java.util.*;
import java.lang.*;
import java.io.*;

class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes herre
		Scanner sc = new Scanner(System.in);
		
		int t = sc.nextInt();
		
		while (t-->0){
		    int n = sc.nextInt();
		    int rev = 0;
		    while (n>0){
		       int rem = n%10;
		       rev = rev*10+rem;
		       n = n/10;
		    }
		    System.out.println(rev);
		}

	}
}
```
