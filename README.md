# java-practice notes
ECLIPSE - most widely used Integrated Dev Environment(IDE) for Java
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
