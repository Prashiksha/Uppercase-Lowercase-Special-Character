// Uppercase-Lowercase-Special-Character
import java.util.Scanner;
class Assign
{
 public static void main(String args[])
{
 Scanner inp = new Scanner(System.in);
 char ch;
 ch = inp.next().charAt(0);

 if (Character.isUpperCase(ch))
   System.out.println("Uppercase");
 else
     {
       if(Character.isLowerCase(ch))
         System.out.println("lowercase");
 else
   System.out.println("special char");
}
}
}
