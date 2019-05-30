class Rahul
{
int a,b,c;
void setdata(int x,int y)
{
a=x;
b=y;
}
}
class godella extends Rahul
{
void disp()
{
c=a+b;
System.out.println(c);
}
}
class main
{
    public static void main(String[] args)
    {
        int m;
     godella obj=new godella();
     obj.setdata(40,50);
     obj.disp();
    }
}
