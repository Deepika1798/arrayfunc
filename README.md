# arrayfunc
import java.util.Scanner;
public class arrayfunc
{
    public static void main(String[] args)
    {
        int n,t,r=1,i,r1=1,result; 
        Scanner sc=new Scanner(System.in);
        int a[]=new int[10];
        System.out.println("enter the size of the array");
        n=sc.nextInt();
        System.out.println("enter the numbers");
        for(i=0;i<n;i++)
     {
        a[i]=sc.nextInt();
    }
    System.out.println("enter the value of which you want output");
    t=sc.nextInt();
    
    for(i=t+1;i<n;i++)
        {
            r*=a[i];
        }
        for(i=t-1;i>=0;i--)
        {
            r1*=a[i];
        }
        result=r*r1;
        
    System.out.println("the result"+result);
}

}
            
    
  
