# Total-number-of-odd-numbers
public class CountOddNumbers {
    public static void main(String[] args) {
        int count = 0;
        for (int i = 1; i <= 100; i++) {
            if (i % 2 != 0) {
                count++; // Increment the count for odd numbers
            }
        }
        System.out.println("The total number of odd numbers between 1 and 100 is: " + count);
    }
}

output-

The total number of odd numbers between 1 and 100 is: 50
