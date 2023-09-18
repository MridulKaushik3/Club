//Club Code

class A{
    public void show(int i){
        System.out.println("value of i:"+i);
    }
}
class A extends B{
    public void show(int i, int j){
        System.out.println("value of i:"+i+"value of j:"+j);
    }
}
public class Ques{
    public static void main(String args[]){
        A obj = new A();
        B obj1 = new B();
        obj.show(23);
        obj1.show(23,52);
    }
}
