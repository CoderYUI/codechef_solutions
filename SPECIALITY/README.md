# Problem

**Problem URL:** [https://www.codechef.com/practice/course/basic-programming-concepts/DIFF500/problems/SPECIALITY](https://www.codechef.com/practice/course/basic-programming-concepts/DIFF500/problems/SPECIALITY)

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
		
		while (t--  > 0){
		    int x = sc.nextInt();
		    int y = sc.nextInt();
		    int z = sc.nextInt();
		    
		    if (Math.max(x,Math.max(y,z)) == x) System.out.println("Setter");
		    else if (Math.max(x,Math.max(y,z)) == y) System.out.println("Tester");
		    else System.out.println("Editorialist");
		}

	}
}
```
