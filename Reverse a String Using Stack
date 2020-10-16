package strings;
import java.util.Scanner;
import java.util.Stack;

public class ReverseStringUsingStack {
	public static void main(String [] args) {
		Scanner s = new Scanner(System.in);
		String str = s.next();
		str = revString(str.toCharArray());
		System.out.println(str);
		s.close();
	}

	private static String revString(char[] str) {
		Stack<Character> stk = new Stack<>();
		for(int i=0; i<str.length; i++) {
			stk.push(str[i]);
		}
		for(int i=0; i<str.length; i++) {
			str[i]=stk.peek();
			stk.pop();
		}
		return String.valueOf(str);
	}
}
