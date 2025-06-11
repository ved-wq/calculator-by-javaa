# calculator-by-javaa
calculator  done by java programming ,in which we take the input from user and assign the symbols like addition, substraction, multiplication etc.  then we are using switch cases for the different calculations .




import java.util.*; 

public class simplecalculator   {

  public static void main(String args[]){
   Scanner sc = new Scanner(System.in);


   System.out.println("Enter first number (a): ");
   double a = sc.nextDouble();

   System.out.println("Enter second number (b): ");
   double b = sc.nextDouble();

   System.out.println("Choose operation:");
   System.out.println("1 : + (addition)");
   System.out.println("2 : - (substraction)");
   System.out.println("3 : * (multiplication)");
   System.out.println("4 : / (division)");
   System.out.println("5 : % (modulus of remainder)");

   System.out.println("Enter your choice (1-5): ");
   int choice = sc.nextInt();



   switch (choice) {
    case 1: 
        System.out.println("Result: " + (a+ b));
        break;

    case 2:
    System.out.println("Result: " + (a - b));
    break;

    case 3:
     System.out.println("Result: " + (a * b));
     break;

     case 4:
     if (b !=0)
      System.out.println("Result: " + (a / b));
      else 
       System.out.println("error: divisible by zero!");
       break;
       case 5:
       if (b !=0)
        System.out.println("Result: " + (a % b));
        else
         System.out.println("error: divisible by zero!");
         break;
         default:
         System.out.println("Invalid choice. Please enter a number  from 1 to 5.");

      
   }

   sc.close();

  }

}
  
   
   





   




  


   


  


    
