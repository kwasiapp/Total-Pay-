# Total-Pay-
calculating total pay 

public class TotalPay {
    
    public static void main(String[] args) {
        // Declaration
        int iHrs;  
        double drate;
        double dTotalPay;
        
        // 1. Ask the suer to enter hours worked
        System.out.println("How many hours have you worked? for the week");
        // 2. Allow the user to enter the value
        Scanner keyboard = new Scanner (System.in);
        // 3. Store hours worked in memory
        iHrs = keyboard.nextInt();
        // 4. Ask the user to enter the rate 
        System.out.println("what is the rate of pay?");
        // 5. Allow the user to enter the value
        // 6. Store rate in memory
        drate = keyboard.nextDouble();
        // 7. Bring back values and calculate total pay 
        dTotalPay = iHrs * drate;
        // 8. Display total pay to owner
        System.out.println("The Total Pay is: \t"+dTotalPay);
        
    } // End of main
