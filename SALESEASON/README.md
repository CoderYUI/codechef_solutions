# Problem

**Problem URL:** [https://www.codechef.com/practice/course/logical-problems/DIFF800/problems/SALESEASON](https://www.codechef.com/practice/course/logical-problems/DIFF800/problems/SALESEASON)

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
		    
		    if (x>5000) System.out.println(x-500);
		    else if (x<=5000 && x>1000) System.out.println(x-100);
		    else if (x<=1000 && x>100) System.out.println(x-25);
		    else System.out.println(x);
		}

	}
}
```
