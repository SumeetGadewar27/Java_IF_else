# Java_IF_else

import java.io.*;
import java.math.*;
import java.security.*;
import java.text.*;
import java.util.*;
import java.util.concurrent.*;
import java.util.regex.*;

public class HackerRankSolution {



    private static final Scanner scanner = new Scanner(System.in);

    public static void main(String[] args) {
        int n = scanner.nextInt();
        String ans;
        scanner.skip("(\r\n|[\n\r\u2028\u2029\u0085])?");
        if(n%2==1){             //odd Condition 
              ans = "Weird";
            }
            else {
                if (n >= 2 && n <= 5) {     //even Condition Range 2-5
                    ans = "Not Weird";
                } else if (n >= 6 && n <= 20) {     //even Condition Range 2-5
                    ans = "Weird";  
                } else {
                    ans = "Not Weird";
                }
            
               //Complete the code
            }   
        System.out.println(ans);  
        scanner.close();
    }
}
