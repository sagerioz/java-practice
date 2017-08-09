# java notes
##ECLIPSE - most widely used Integrated Dev Environment(IDE) for Java

###Java language is known to be flexible, scalable, and maintainable.


```
// comment
/* multi-line comments */
Import libraries:
import java.util.Scanner;
import java.util.*;

DATA TYPES:
char - short for character (ie in single quotes: 'G')
int - short for integer, whole pos or neg num
boolean - T or F

WHITESPACE:
Java will ignore whitespace in code

public class Animal {
  // the following is known as a field (or variable), aka attribute. Can start with a letter,$,_
  private String name;
  private int weight;
  private boolean hasOwner = false;
  private byte age;
  private uniqueID;
  private char favoriteChar;
  private double speed;
  private float height;

  protected static int numberOfAnimals;

  // this allows user input from the keyboard
  static Scanner userInput = new Scanner(system.in);

  // this is a constructor example:
  public Animal(){
      numberOfAnimals++

      int sumOfNumbers = 5 + 1;
      System.out.println = ("5 + 1 = " + sumOfNumbers)

      System.out.print("Enter the name: \n");

      /* more booleans like hasNextLine:
      hasNextInt,
      hasNextFloat,
      hasNextDouble,
      hasNextByte,
      nextInt,
      nextFloat,
      nextDouble...
      these make sure you are handling the right data types!
      */


      if(userInput.hasNextLine()){
        // if the user actually entered a string(hasNextLine)? If so, do this...
        this.setName(userInput.nextLine())
      }
  }

  // this is how to execute the code above. This gets called first. You can run this on the command line:
  public static void main(String [] args){
      Animal theAnimal = new Animal()
      // will print out 5 + 1 = 6
  }

  }

  // Cat is now a sub-class of type Animal; inheritance.
  public class Cat extends Animal(){

  }

more...
static: this number is shared by every Animal class that is created
public: available to anyone
final: constant an cannot be changed
private: accessed by other methods in the class and that's it. Good practice to use on all fields.
double: allows for decimals, i.e. (use uppercase letters) MYNUMBER = 1.1827;
string: string of characters
int: an integer
boolean: T/F
protected: only available within this code area; scope


/* RUN DIRECTLY IN TERMINAL:
Open Terminal.
Enter mkdir HelloWorld to create a new directory and cd HelloWorld to move into it.
Enter touch HelloWorld.java to create an empty Java file.
Now enter nano HelloWorld.java to edit the file.
In the Nano editor type out the following code:
public class HelloWorld {

   public static void main(String[] args) {

       System.out.println("Hello World!");

   }

}

Press Control-X then y and Return to save the file and exit Nano.
Now compile the program by entering javac HelloWorld.java in Terminal.
Enter java HelloWorld to run it.
You should see Hello World outputted into the Terminal.
*/
```
