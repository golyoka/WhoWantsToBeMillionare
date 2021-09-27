# WhoWantsToBeMillionare
Homework
public class WhoWantsToBeAMillionaireApp {

    public static void main(String[] args) {

        System.out.println("Welcome to my game you have 1 chance to find the right answer!");


        System.out.println("Who is named as the father of the light bulb?");
        System.out.println("A: Nikola Tesla");
        System.out.println("B: Marie Curie");
        System.out.println("C: Thomas Edison");
        System.out.println("D: Robert Oppenheimer");
        System.out.println();

        Scanner scanner = new Scanner (System.in);
        System.out.println("Please give your answer: ");

        String answer = scanner.nextLine();

scanner.close();
        if (answer == "a") {
            System.out.println("Winner");
        } else {
            System.out.println("Looser");
        }
