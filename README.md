# 4ve5katlarinabolunme



import java.sql.SQLOutput;

import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner inp = new Scanner(System.in);
        int n,i=1,j=1;
        System.out.println("Bir Sayı Giriniz");
        n =inp.nextInt();

        for (j=1;j<=n;j*=5){
            if (j>i&&i<n){
                System.out.println(j);
                i*=4;
            }
            System.out.println(i);

        }

        }
    }
