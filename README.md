# Profit-Multiplier-v2

    import java.util.Scanner;

      public class Main {
       public static void main(String[] args) {

        Scanner scanner  = new Scanner(System.in);

        System.out.print("Enter the Initial Investment You wish to put into the Stock :$ ");
        double inlInvestment = scanner.nextDouble();

        System.out.print("What is the Monthly Growth Rate of the the Stock : ");
        double monthlyGrowthRate = scanner.nextDouble();

        
        for (int i = 1; i <= 10; i++) {
            inlInvestment = inlInvestment * monthlyGrowthRate;
            System.out.println("Month "+ i +"-> $" + inlInvestment);

        }


        scanner.close();
    }
    }
