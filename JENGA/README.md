# Problem

**Problem URL:** [https://www.codechef.com/practice/course/logical-problems/DIFF800/problems/JENGA](https://www.codechef.com/practice/course/logical-problems/DIFF800/problems/JENGA)

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
		    
		    if (n<=x){
		        if (x%n ==0) System.out.println("YES");
		        else System.out.println("NO");
		    }
		    else System.out.println("NO");
		}
	}
}
```
