import java.util.*;

public class Main {

  public static void main(String[] args) {

    Scanner sc = new Scanner(System.in);
    int n = sc.nextInt();
    int k = sc.nextInt();
    
    int temp=n;
    int count=0;
    while(temp>0){
        temp=temp/10;
        count++;
    }
    k=k%count;
    if(k<0){
        k=k+count;
    }
    int t = (int)Math.pow(10,k);
    
    int a=n%t;
    int b=n/t;
    
    int c = count -k;
    int d = (int)Math.pow(10,c);
    
    System.out.println(d*a+b);
  }
}
