// PATTERNS

// # starpattern1
// Star pattern 4*4 , 5*5, 7*7 etc

public class Main
{
    static void writenumber(int num1){
        for(int i=1;i<=num1;i++){
	    for(int j=1;j<=num1;j++){
		System.out.print("* ");
	    }
	System.out.println();
	}    
     }
     public static void main(String[] args) {
      	writenumber(5);
    }
}

// # numberpattern1 (decrement)
// 1 2 3 4 
// 1 2 3
// 1 2
// 1
public class Main
{
	public static void main (String[] args) {
		int p=4;
		
		for(int i=p;i>=1;i--){
		    for(int j=1;j<=i;j++){
		        System.out.print(j+" ");
		    }
		    System.out.println();
		}
	}
}

// # numberpattern1 (decrement)
// 1 1 1 1
// 2 2 2
// 3 3
// 4
public class Main
{
	public static void main(String[] args) {
	int p=4;
        int a=1;
	    for(int i=p;i>=1;i--){
	        for(int j=1;j<=i;j++){
	            System.out.print(a+" ");    
	        }
	        a++;
	    System.out.println();
	    }
	}
}

// # numberpattern2 (increment)
// 1
// 1 2
// 1 2 3
// 1 2 3 4
public class Main
{
	public static void main(String[] args) {
		int d=4;
		
		for(int i=1;i<=d;i++){
		    for(int j=1;j<=i;j++){
		        System.out.print(j+" ");
		    }
		    System.out.println();
		}
	}
}

// # numberpattern3 (increment)
// 1
// 2 2
// 3 3 3
// 4 4 4 4
public class Main
{
	public static void main(String[] args) {
		int d=5;
		
		for(int i=1;i<=d;i++){
		    for(int j=1;j<=i;j++){
		        System.out.print(i+" ");
		    }
		    System.out.println();
		}
	}
}
