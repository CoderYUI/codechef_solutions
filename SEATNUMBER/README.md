# Problem

**Problem URL:** [https://www.codechef.com/practice/course/logical-problems/DIFF800/problems/SEATNUMBER](https://www.codechef.com/practice/course/logical-problems/DIFF800/problems/SEATNUMBER)

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
		    
		    switch(n){
		        case 1 : case 2 : case 3 : case 4 : case 5 : case 6 : case 7 : case 8 : case 9 : case 10 :
		            System.out.println("Lower Double");
		            break;
		        
		        case 11 : case 12 : case 13 : case 14 : case 15 :
		            System.out.println("Lower Single");
		            break;
		            
		        case 16 : case 17 : case 18 : case 19 : case 20 : case 21 : case 22 : case 23 : case 24 : case 25 : 
		            System.out.println("Upper Double");
		            break;
		            
		        case 26 : case 27 : case 28 : case 29 : case 30 :
		            System.out.println("Upper Single");
		            break;
		            
		        default :
		        System.out.println();
		       
		    }
		}

	}
}
```
