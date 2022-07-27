import java.io.*;
import java.util.*;

public class Solution {
            private static Scanner sc;
    public static void main(String[] args) {
        /* Enter your code here. Read input from STDIN. Print output to STDOUT. Your class should be named Solution. */
       int side, i, j;
        sc = new Scanner(System.in);
        
        
        side = sc.nextInt();    
            
        for(i = 1; i <= side; i++)
        {
            for(j = 1; j <= side; j++)
            {
                System.out.print("*"+" "); 
            }
            System.out.print("\n"); 
        }    
    }
}
