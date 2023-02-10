# Test1


import java.util.Scanner;


public class fibanocci {
    public static void main(String args[]){
    int a,b,n;
    a=0;b=1;
    Scanner sc = new Scanner(System.in);
    System.out.println("Enter the no. of elements of fibanocci series to be printed ");
    n = sc.nextInt();
    if (n==1){
    System.out.println(a);
    }else if(n == 2){
    System.out.println(a+" "+b);
    }else if(n>=3){
    System.out.print(a+" "+b+" ");
    for(int i=1; i<=n; i++){
        b=a+b;
        a=b-a;
        System.out.print(b+" ");
        
    }
    }
    }
}