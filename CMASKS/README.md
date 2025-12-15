# Problem

**Problem URL:** [https://www.codechef.com/practice/course/basic-programming-concepts/DIFF500/problems/CMASKS](https://www.codechef.com/practice/course/basic-programming-concepts/DIFF500/problems/CMASKS)

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
		
		while (t--> 0){
		    int x = sc.nextInt();
		    int y = sc.nextInt();
		    
		    if (Math.min((x*100),(y*10))==x) System.out.println("Cloth");
		    else if (Math.min((x*100),(y*10))< (y*10)) System.out.println("Disposable");
		    else System.out.println("Cloth");
		    
		   
		}

	}
}
```
