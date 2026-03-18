# oops-banner
UC5:

public class OOPSBannerAppUC5 {

    public static void main(String[] args) {

        System.out.println("OOPS Banner App - UC5\n");

        // UC5: Inline Array Initialization with String.join()
        String[] banner = {

            String.join("   ", " ***** ", " ***** ", " ***** ", " ***** "),
            String.join("   ", "*     *", "*     *", "*     *", "*      "),
            String.join("   ", "*     *", "*     *", "*     *", "*      "),
            String.join("   ", "*     *", "*     *", " ***** ", " ***** "),
            String.join("   ", "*     *", "*     *", "*      ", "      *"),
            String.join("   ", "*     *", "*     *", "*      ", "*     *"),
            String.join("   ", " ***** ", " ***** ", "*      ", " ***** ")

        };

        // Enhanced For Loop to print banner
        for (String line : banner) {
            System.out.println(line);
        }
    }
}