
    public class Debug {
    public static void main(String[] args) {

       
        int var1 = 4;
        if (var1 > 4){
            System.out.println("Var1 is greater than 4");
        } else if (var1 == 4) { // makes sure if the variable is 4 then there is an output for it
            System.out.println("Var1 is equal to 4 ");
        }else{
            System.out.println("Var1 is less than 4");
        }

        int var2 = 6;
        if (var2 == 5){
            System.out.println("Var2 is 5");
        } else if (var2 > 5){ 
            System.out.println("Var2 is greater than 5");
        } else { //all possabilitys are covered
            System.out.println("Var2 is less than 5");
        }

        int var3 = 5;
        if (var3 > 10){
            System.out.println("Var3 is greater than 10");
        } else if (var3 == 10) {
            System.out.println("Var3 is equal to 10);
        } else {
            System.out.println("Var3 is less than 10");
        }




        if ("Marist" == "marist"){   // qw are not entering the if stattement because the conditon is false
            //Marist doesnt = marist. so it will skip the if block and just run the else block.
            System.out.println("Marist college!");
        } else{
            System.out.println("Not marist college :(!");
        }


    }
}

    public static void main(String[] args) {

       
        int var1 = 4;
        if (var1 > 4){
            System.out.println("Var1 is greater than 4");
        } else if (var1 == 4) { // makes sure if the variable is 4 then there is an output for it
            System.out.println("Var1 is equal to 4 ");
        }else{
            System.out.println("Var1 is less than 4");
        }

        int var2 = 6;
        if (var2 == 5){
            System.out.println("Var2 is 5");
        } else if (var2 > 5){ 
            System.out.println("Var2 is greater than 5");
        } else { //all possabilitys are covered
            System.out.println("Var2 is less than 5");
        }

        int var3 = 5;
        if (var3 > 10){
            System.out.println("Var3 is greater than 10");
        } else if (var3 == 10) {
            System.out.println("Var3 is equal to 10);
        } else {
            System.out.println("Var3 is less than 10");
        }




        if ("Marist" == "marist"){   // qw are not entering the if stattement because the conditon is false
            //Marist doesnt = marist. so it will skip the if block and just run the else block.
            System.out.println("Marist college!");
        } else{
            System.out.println("Not marist college :(!");
        }


    }
}




// Name: Jade Spotts
// Major: CyberSecurity

import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in); // used to read whatever is typed

        int score = 0; // this varible will keep track of the score. started it at zero beacue well no points yet.
          

        System.out.print("Welcome to the Quiz All About Our Earth!!");
        System.out.print("guess all the right answers and win noteriety.");
        
        System.out.println("Question 1 : How many planets away from the Sun is Earth?");
        int planets = sc.nextInt(); // reads only an integer input from the user
        sc.nextLine(); // makes sure my next question doesnt get skipped by clearing the last imput 
        //checking the answer
        if (planets == 3)  { 
            System.out.println("You got it right!");
            score = score + 1; // increments the score by adding 1 to the previous score for every right answer
        } else { // if input wasnt 3 this blocks ran instead and because its being run after the score block was ran nothing happens to the scores value for the else statement.
            System.out.println("Incorrect, Earth is the 3rd planet from the Sun");
        }
    
        System.out.println("\nQuestion 2: What is the largest ocean on Earth?"); // \n i used /n because i was unable to get my code to run if the previous answer was correct. It would just skip the questions. So i looked up how to make the questions seperate / new which is what the \n does
        String ocean = sc.nextLine(); // reading users input and using sc.nextLine because its not an integer
        //checking the answer
        if ( ocean.equals("Pacific Ocean")) { //using comparing word for strings "equals"
            System.out.println("Correct, the pacific ocean is the largest");
            score = score + 1;
        } else {
            System.out.println("Wrong, the correct answer is the Pacific Ocean.");    
        }

        System.out.println("\nQuestion 3: Which layer of Earth do humans live on?");
        String layer = sc.nextLine(); // reading users input
        //checking answer
         if ( layer.equals("crust")) {
            System.out.println("Correct! Humans live on the Earth's crust.");
            score = score + 1;
        } else {
            System.out.println("Incorrect, the correct answer is the crust.");
        }
        
        System.out.println("\nYou scored " + score + " out of 3."); // calculates the final score from the accumulated correct statements (if)
    }
}

  //what i learned; I learned how to use if else statement to cjeck if a conditon is true or false and how to use multiple of them. 
  // i learned to make a how to track score/ an integer value whilest adding to it. 
  // how to use scanner to take the imput from uthe user using nextInt() = numbers and nextLine() = text  
