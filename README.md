class A
{
	int a;
	A()
	{
		System.out.println("Im default constructor");
	}
	A(int a)
	{
		this();
		this.a=a;
		System.out.println("value of a is: "+a);
		this.show();
	}
	void show()
	{
		System.out.println("Im called using this but not using object");
	}
	
}
class Jala 
{
	public static void main(String[] args){ 
			 A a = new A(5);
	}
}
