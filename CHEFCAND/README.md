# Problem

**Problem URL:** [https://www.codechef.com/practice/course/logical-problems/DIFF800/problems/CHEFCAND?tab=hints](https://www.codechef.com/practice/course/logical-problems/DIFF800/problems/CHEFCAND?tab=hints)

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
		    int n = sc.nextInt();
		    int x = sc.nextInt();
		    int candiesToBuy =0;
		    if (n>x) candiesToBuy = n-x;
		    if (candiesToBuy%4 == 0) System.out.println(candiesToBuy/4);
		    else System.out.println(candiesToBuy/4 + 1);
		    
		    
		}
		

	}
}
```
