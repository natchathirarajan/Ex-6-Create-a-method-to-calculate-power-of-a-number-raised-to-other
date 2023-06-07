# Ex-6-Create-a-method-to-calculate-power-of-a-number-raised-to-other

## AIM:
To write a java program to create a method to calculate power of a number raised to other.

## ALGORITHM: 
### Step 1:
Import the necessary packages.
### Step 2: 
Get the base and power values from the user.
### Step 3: 
Using recursive function, calculate the power value.
### Step 4:  
Print the result.
### Step 5: 
End the program.
## PROGRAM:
~~~
Name   : H.Syed Abdul Wasih
Reg No : 212221240057
~~~
~~~
import java.util.*;
public class Main {
    public static void main(String[] args) {
        Scanner s=new Scanner(System.in);
        int base, powerRaised;
        System.out.print("Enter the base value: ");
        base=s.nextInt();
        System.out.print("Enter the power value for raising the power of base: ");
        powerRaised=s.nextInt();
        int result = power(base, powerRaised);
        System.out.println("Result : "+base + "^" + powerRaised + "=" + result);
    }
    public static int power(int base, int powerRaised) {
        if (powerRaised != 0) {
         // recursive call to power()
            return (base * power(base, powerRaised - 1));
        }
        else {
            return 1;
        }
    }
}
~~~

## OUTPUT:

![exp6](https://github.com/abdulwasih2003/Ex-6-Create-a-method-to-calculate-power-of-a-number-raised-to-other/assets/91781810/50acd8a9-21c0-4d27-b525-5888447efc79)

## RESULT:
Thus the java program to create a method to calculate power of a number raised to other is successful.



