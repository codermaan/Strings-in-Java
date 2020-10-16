import java.util.*;
import java.lang.*;
import java.io.*;
class Strings
 {
	public static void main (String[] args)
	 {
	    Scanner s = new Scanner(System.in);
	    int t = s.nextInt();
	    while(t-->0){
	        String a = s.next();
	        int n = a.length();
	        char ch[] = a.toCharArray();
	        char temp;
	        
	        for(int i=0, j=n-1; i<j; i++,j--){
	            temp = ch[i];
	            ch[i] = ch[j];
	            ch[j] = temp;
	        }
	        System.out.println(ch);
	    }
	 }
}
