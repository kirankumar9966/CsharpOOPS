using System;

abstract class test
{
 public abstract void m1();  
 public  void role(){
     Console.WriteLine("role method");
 }
}
class  test1 : test{
    public override void m1(){
        
        Console.WriteLine("child method is the 2nd program ");
    }
}
class mam{
    public static  void Main(string[] args) {
        test1 t=new test1();
        // Console.WriteLine ("Hello Mono World");
        t.role();
        t.m1();
        
    }
}