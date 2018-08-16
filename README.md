# CalculatorMethod\import static java.lang.System.out;

public class CalculatorMethods
{
    public static int add(int a, int b) {
        return a + b;
    }

    public static int subtract(int a, int b) {
        return a - b;
    }

    public static int multiply(int a, int b) {
        return a * b;
    }

    public static float divide(int top, int bottom) {
        float answer = (float) top / (float) bottom;
        return answer;
    }

    public static void main(String [] args)
    {
        //First we call the add function.
        //It takes two input parameters which are 5 and 7 here.
        //The return value of add(), which is 12,
        //gets saved in the variable x.
        int x = add(5,7);

        //Then we print out the value of x in our print statement.
        System.out.println("5 plus 7 equals " +x);

        //Now we do the same kind of call, but in a single line,
        //without needing 'x' as a temporary variable in between.
        System.out.println("3 plus 5 equals " + add(3,5));
        System.out.println("1 plus 2 equals " + add( 1, 2));

        //The subtraction results are wrong
        //because the subtract() method is incomplete. Fixt It!
        System.out.println("9 minus 4 equals" + subtract(9,4));
        System.out.println("9 minus 3 equals" + subtract (9, 3));

        //The multiplication results are wrong
        //becaseu the mulitply() method is incomplete. Fix it!
        System.out.println("3 times 3 equals" + multiply(3, 3));
        System.out.println("2 times 4 equals" + multiply(2,4));

        //Now it's your turn! Create a divide() method and write some
        //print statements to test that it works right.
        float result = 0.0f;
        result = divide(20, 5);
        System.out.println("result is" + result);

    }
}
