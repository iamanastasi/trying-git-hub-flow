# trying-git-hub-flow
йоу!
import java.util.Scanner;
public class Main {
    static Scanner sc = new Scanner(System.in);
    static void myMethod(int i,int [] arr) {
        int a = sc.nextInt();
        if(i<arr.length) {
            System.out.print(a + " ");
            i++;
            myMethod(i, arr);
        }
        return 0 ;
    }
    public static void main(String[] args) {
        int n=sc.nextInt();
        int arr[] = new int[n];
        int i=0;
        myMethod(i, arr);
    }
}
