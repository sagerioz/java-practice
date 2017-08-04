# java-practice notes
##ECLIPSE - most widely used Integrated Dev Environment(IDE) for Java
```
// comment
/* multi-line comments */
Import libraries:
import java.util.Scanner;
import java.util.*;

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
  static Scanner userinput = new Scanner(system.in);

  // this is a constructor example:
  public Animal(){
      numberOfAnimals++

      int sumOfNumbers = 5 + 1;
      System.out.println = ("5 + 1 = " + sumOfNumbers)
  }

  // this is how to execute the code above. This gets called first. You can run this on the command line:
  public static void main(String [] args){
      Animal theAnimal = new Animal()
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

```
