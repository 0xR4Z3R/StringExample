# StringExample

public class StringExample{
	
	public static void main(String[] args)
	{
		String s1 = "String Example Program";
		int x = 111;
		String s2 = s1 + " " + x;
		String s3 = s2.substring(10,17);
		String s4 = " is fun";
		String s5 = s2 + s4;
		
		System.out.println("s1: " + s1);
		System.out.println("s2: " + s2);
		System.out.println("s3: " + s3);
		System.out.println("s4: " + s4);
		System.out.println("s5: " + s5);
		
		//showing effect of precedence
		
		x = 3;
		int y = 5;
		//sum up
		String s6 = x + y + " total";
		//multiply
		String s7 = "total " + x + y;
		//multiply
		String s8 = " " + x + y + "total";
		System.out.println("s6: " + s6);
		System.out.println("s7: " + s7);
		System.out.println("s8: " + s8);
		
		
	}
	
	//Output
  s1: String Example Program
s2: String Example Program 111
s3: mple Pr
s4:  is fun
s5: String Example Program 111 is fun
s6: 8 total
s7: total 35
s8:  35total
  
	
	
