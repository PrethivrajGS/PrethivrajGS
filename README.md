import java.util.Scanner;
import java.lang.*;
class area
{
    static int cal(int a,int b)
    {
        return a*b;
    }
    static float cal(float a)
    {
        return 2.0f*a;
    }
    static double cal(double x,double y,double z)
    {
        return x*y*z;
    }
}
class Main
{
    public static void main(String[] arg)
    {
        System.out.println(area.cal(20,4));
        System.out.println(area.cal(43.0f)); 
        System.out.println(area.cal(5.0,6.2,6.4)); 
    }
}
