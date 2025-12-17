# Problem

**Problem URL:** [https://www.codechef.com/practice/course/logical-problems/DIFF800/problems/MINPIZZA?tab=Submissions](https://www.codechef.com/practice/course/logical-problems/DIFF800/problems/MINPIZZA?tab=Submissions)

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
		int arr[] = new int[3];
  		
		while (t-- > 0){
		    int x = sc.nextInt();
		    int y = sc.nextInt();
		    
		    if ((x*y)%4 ==0) System.out.println(((x*y)/4));
		    else System.out.println((x*y/4)+1);
		}

	}
}
```
