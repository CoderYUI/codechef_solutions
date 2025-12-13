# Problem

**Problem URL:** [https://www.codechef.com/practice/course/basic-programming-concepts/DIFF500/problems/PRIZEPOOL](https://www.codechef.com/practice/course/basic-programming-concepts/DIFF500/problems/PRIZEPOOL)

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
		
		while(t-->0){
		    int x = sc.nextInt();
		    int y = sc.nextInt();
		    
		    int totalPrize = (x*10) + (y*90);
		    System.out.println(totalPrize);
		}

	}
}
```
