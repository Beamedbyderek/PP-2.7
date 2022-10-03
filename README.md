# PP-2.7

/* 

10/2/2022

 Derek Durand

Converts F to C

*/ 

import java.util.Scanner;


public class PP27 {

    
    public static void main(String[] args) {
        
            Scanner sc = new Scanner(System.in);   // requests mile amount
            
            System.out.print("Enter Mile Amount: ");     
            float mileNumber = sc.nextFloat();
            
            System.out.print("Enter speed in MPH: ");
            float speed = sc.nextFloat();
            
            float timeSpent =  (float) (mileNumber/speed); // Converts into time
            
            System.out.print("This will take you " + timeSpent + " hours ");
            
       
    }
    
}
