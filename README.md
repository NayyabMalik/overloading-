# overloading-
I'm doing program through java in oop
/**
 *
 * @author student
 */
public class Sum {
   
    
   static int sum( int a,int b){
        return a+b;
    }
   static int sum(int a,int b,int c){
        return a+b+c;
    }

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        
    int x= sum(4,5);
    int y=sum(4,5,6);
    System.out.println("sum of two preimeters="+x);
    System.out.println("sum of three perimeters="+y);
