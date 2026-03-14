# java-test-0002-final-15325-sushant
Final Project Assignment - This repository contains the complete final project code and documentation.
public class Main {
    public static void main(String[] args) {
        final int TOTAL_ROWS = 5;

        for (int row = 1; row <= TOTAL_ROWS; row++) {

            
            for (int space = 1; space <= TOTAL_ROWS - row; space++) {
                System.out.print("  ");
            }

            
            for (int col = 1; col <= row; col++) {
                System.out.print(col + " ");
            }

          
            for (int col = row - 1; col >= 1; col--) {
                System.out.print(col);

                if (col > 1) {
                    System.out.print(" ");
                }
            }

            System.out.println();
        }
    }
}
