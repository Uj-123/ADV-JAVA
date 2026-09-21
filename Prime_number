import java.util.Scanner;

public class PrimeList {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter number of elements: ");
        int n = sc.nextInt();

        System.out.println("Prime numbers are:");
        for (int i = 0; i < n; i++) {
            int num = sc.nextInt();
            boolean prime = true;

            if (num <= 1)
                prime = false;

            for (int j = 2; j <= num / 2; j++) {
                if (num % j == 0) {
                    prime = false;
                    break;
                }
            }

            if (prime)
                System.out.print(num + " ");
        }
    }
}
