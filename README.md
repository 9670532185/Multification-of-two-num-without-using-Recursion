# Multification-of-two-num-without-using-Recursion
public class ABC {
    public static int mul(int a,int b)
    {
        if(b==0)
        {
            return 0;
        }
        return a+mul(a,b-1);

    }
public static void main(String[] args)
{
    int a=3,b=5;
    System.out.println(mul(a,b));

}

}
    

