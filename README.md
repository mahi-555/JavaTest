#Code
import java.io.*;
import java.math.*;
import java.util.*;

public class Solution {

    public static void main(String[] args) {

        Scanner sc = new Scanner(System.in);

        BigInteger n = sc.nextBigInteger();

        if (n.isProbablePrime(10)) {
            System.out.println("prime");
        } else {
            System.out.println("not prime");
        }

        sc.close();
    }
}


<img width="1917" height="947" alt="Screenshot 2026-10-31 125607" src="https://github.com/user-attachments/assets/b4063bca-744d-4eb5-8238-cd8be1e52aba" />
