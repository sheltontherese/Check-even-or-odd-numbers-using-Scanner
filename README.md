# Check-even-or-odd-numbers-using-Scanner
Check even or odd numbers using Scanner
public class KiemTraSoChanLe {
     public static void main(String[] args) {
         int n;
         Scanner scanner = new Scanner(System.in);
         System.out.println("enter number to check n:");
         n = scanner.nextInt();
         // execute the if else statement to check the condition
         if (n % 2 == 0) {
             System.out.println(n + " is even!");
         } else {
             System.out.println(n + " is odd");
         }
     }
}
