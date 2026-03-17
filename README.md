abstract class Main6{
    abstract void show();
    abstract void show1();
}
class Demo extends Main6{
    void show(){
        System.out.println("This is show method");
    }
    void show1(){
        System.out.println("This is show1 method");
    }
}
public class Abstraction {
  public static void main(String[] args){
      Demo d=new Demo();
      d.show();
      d.show1();
  }
}
