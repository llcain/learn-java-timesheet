# learn-java-timesheet



import java.util.Scanner;

public class App {

    public static void main(String args[]) {


        // initialize variables

        double totalHours;
        double hoursWorked;
        double dayOne, dayTwo, dayThree, dayFour, dayFive, daySix, daySeven, dayEight, dayNine, dayTen, dayEleven;
        double dayTwelve, dayThirteen, dayFourteen;
        double totalWeek1;
        double totalWeek2;

        Scanner Keyboard = new Scanner(System.in);

        //Display calculation to screen

        System.out.println("Enter number of hours worked for day one");
        dayOne = Keyboard.nextDouble();

        System.out.println("Enter number of hours worked for day two");
        dayTwo = Keyboard.nextDouble();

        System.out.println("Enter number of hours worked for day three");
        dayThree = Keyboard.nextDouble();

        System.out.println("Enter number of hours worked for day four");
        dayFour = Keyboard.nextDouble();

        System.out.println("Enter number of hours worked for day five");
        dayFive = Keyboard.nextDouble();

        System.out.println("Enter number of hours worked for day six");
        daySix = Keyboard.nextDouble();

        System.out.println("Enter number of hours worked for day seven");
        daySeven = Keyboard.nextDouble();


        totalWeek1 = dayOne + dayTwo + dayThree + dayFour + dayFive+ daySix + daySeven;
        System.out.println(totalWeek1);

        System.out.println("Enter number of hours worked for day eight");
        dayEight = Keyboard.nextDouble();

        System.out.println("Enter number of hours worked for day nine");
        dayNine = Keyboard.nextDouble();

        System.out.println("Enter number of hours worked for day ten");
        dayTen = Keyboard.nextDouble();

        System.out.println("Enter number of hours worked for day eleven");
        dayEleven = Keyboard.nextDouble();

        System.out.println("Enter number of hours worked for day twelve");
        dayTwelve = Keyboard.nextDouble();

        System.out.println("Enter number of hours worked for day thirteen");
        dayThirteen = Keyboard.nextDouble();

        System.out.println("Enter number of hours worked for day fourteen");
        dayFourteen = Keyboard.nextDouble();


        totalWeek2 = dayEight + dayNine + dayTen + dayEleven + dayTwelve +dayThirteen + dayFourteen;
        System.out.println( dayEight + dayNine + dayTen + dayEleven + dayTwelve +dayThirteen + dayFourteen );

        totalHours = totalWeek1 + totalWeek2;
        System.out.println(totalHours);
