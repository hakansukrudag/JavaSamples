
import java.util.Scanner;

public class PalindromeNumber {
    public static void main(String[] args) {
        Scanner scan = new Scanner(System.in);
        System.out.println("Sayi giriniz : ");
        int num = scan.nextInt();
        
        isPalindrome(num);
    }

    public static void isPalindrome(int num){

        int originalNum, reversedNum, remainder;

        originalNum=num;
        reversedNum=0;

        while (num != 0)
        {
            remainder = num % 10;
            reversedNum = reversedNum * 10 + remainder;
            num /= 10;
        }

        // check if reversedNum and originalNum are equal
        if (originalNum == reversedNum)
        {
            System.out.println("true");
        }
        else
        {
            System.out.println("false");
        }
    }
}
