public class CountOddNumbers {
    public static void main(String[] args) {
        int count = 0;

        for (int i = 1; i <= 100; i++) {
            if (i % 2 != 0) { // Check if the number is odd
                count++;
            }
        }

        System.out.println("Total number of odd numbers between 1 and 100: " + count);
    }
}
# Total-number-of-odd-number-1-100
