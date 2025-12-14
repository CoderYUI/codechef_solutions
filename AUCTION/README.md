# Problem

**Problem URL:** [https://www.codechef.com/practice/course/basic-programming-concepts/DIFF500/problems/AUCTION](https://www.codechef.com/practice/course/basic-programming-concepts/DIFF500/problems/AUCTION)

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
		
		while (t-- > 0) {
		    int a = sc.nextInt();
		    int b = sc.nextInt();
		    int c = sc.nextInt();
		    
		    if (a>b){
		        if(a>c) System.out.println("Alice");
		        else System.out.println("Charlie");
		    } else if (b>c) {
		        if (b>a) System.out.println("Bob");
		        else System.out.println("Alice");
		    } else System.out.println("Charlie");
		}

	}
}
```
