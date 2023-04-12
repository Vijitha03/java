# java
### star pyramid
import java.io.*;
public class pattern
{
    public static void printTriangle(int n)
    {
        for (int i=0; i<n; i++)
        {
            for (int j=n-i; j>1; j--)
            {
                System.out.print(" ");
            }
            for (int j=0; j<=i; j++ )
       {
                       System.out.print("* ");
            }
             System.out.println();
        }
    }

![image](https://user-images.githubusercontent.com/113349410/231493323-632e88b2-09b1-4725-98ad-169c4d557d73.png)
