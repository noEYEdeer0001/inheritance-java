public class Sameer   // Main class
{
    public static void main(String[] args)
    {
        C obj = new C();
        obj.sxm();   // from class A
        obj.sam();   // from class B
        obj.fn();    // from class C
    }
}
class A
{
    public void sxm()
    {
        System.out.println("Class A");
    }
}

class B extends A // Single inheritance
{
    public void sam()
    {
        System.out.println("Class B");
    }
}

class C extends B // Multilevel inheritance
{
    public void fn()
    {
        System.out.println("Class C");
    }
}

class K extends C // Hierarchical inheritance
{
    public void ff()
    {
        System.out.println("Class K");
    }
}

class M extends C // Hierarical inhertitance
{
    public void sds()
    {
        System.out.println("Class M");
    }
}

