public class CallingMethodsInSameClass
{
	public static void main(String[] args) {
		printOne();
		printTwo();
	}

	public static void printOne() {
		System.out.println("This is Pavan");
	}

	public static void printTwo() {
		printOne();
		printOne();
	}
}
