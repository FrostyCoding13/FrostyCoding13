import java.util.*; //simple program for calculator in java
public class Calculator{
public static void main (String args[]){
System.out.println("Enter 1 for addition, 2 for subtraction, 3 for multiplication and 4 for Division");
Scanner sc = new Scanner(System.in);
int a = sc.nextInt();
double c;
if(a== 1) {Scanner d = new Scanner (System.in); 
    System.out.println("Enter first number");
    double e = d.nextInt();        
     System.out.println("Enter second number");
    double f = d.nextInt();
    c = e + f;
    System.out.println("Addition: "+c); 
            }
else if(a==2) { Scanner g = new Scanner (System.in); 
    System.out.println("Enter first number");
    double h = g.nextInt();        
     System.out.println("Enter second number");
    double i = g.nextInt();
    c = h - i;
    System.out.println("Subtraction : "+c); 
}
 if (a==3){Scanner j = new Scanner (System.in); 
    System.out.println("Enter first number");
    double k = j.nextInt();        
     System.out.println("Enter second number");
    double l = j.nextInt();
    c = k * l;
    System.out.println("Multiplication : "+c);} 
    
    else {Scanner m = new Scanner (System.in); 
    System.out.println("Enter first number");
    double n = m.nextInt();        
     System.out.println("Enter second number");
    double o = m.nextInt();
    c = n/o;
    System.out.println("Division : "+c);} 
}
}
