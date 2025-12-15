# Problem

**Problem URL:** [http://codechef.com/practice/course/basic-programming-concepts/DIFF500/problems/TVDISC](http://codechef.com/practice/course/basic-programming-concepts/DIFF500/problems/TVDISC)

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
		    
		    int a = sc.nextInt();
		    int b = sc.nextInt();
		    int c = sc.nextInt();
		    int d = sc.nextInt();
		    
		    if (Math.min((a-c),(b-d))==(a-c) && 
		    Math.min((a-c),(b-d))==(b-d) ) System.out.println("Any");
		    else if (Math.min((a-c),(b-d))==(a-c)) System.out.println("First");
		    else System.out.println("Second");
		   
		    
		}

	}
}
```
