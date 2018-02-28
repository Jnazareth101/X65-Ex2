# X-Team 65 Style Guide




We are all using similar style guides to prevent spaces vs tabs, using tabs primarily. Our goal is readablity and consistency.

## Naming conventions

We will name variables and methods based on what they do/ what they are, using comments if necessary. Keeping local variables and instantiated variables the same name, using this. to keep track of the variables.

### Examples
* interfaces
  * ```public interface TreeADT```
* classes
  * ```public class RBTree```
* exception types
  * ```public class DuplicateKeyException()```
* fields
  * ```private Treenode root```
* methods
  * ```public static void methodName();```
* parameters
  * ```public method(int descriptiveName, Integer descriptiveName)```
* local variables
  * ```int size = 0;```
* instance constants
  * ```public final int MAX_VALUE```
* class constants
  * ```public static final int MAX_SIZE = 0;```

## Commenting style for public and private members of a class or interface:

Primarily use // for commenting inside methods. We won't use a new line to begin the opening brace for a method. We will tab in spacing for methods/statements within classes. We won't be using terniary statements as much in our coding.

### Examples

* classes
```
/**
 * Description of the class, with useful information about implementation.
 * @author Group name
 */
 ```
* fields
```
/**Description of field*/
private Treenode root;
```
* constructors
```
/**
 * Description of what constructor does
 * @param Description of paramter
 */
 public ClassName() {
// in line comments
}
```
* methods
```javascript
/**
 * Method Header
 */
 public method() {
// in line comments
}
```
* coding style (brackets, horizontal, and vertical spacing) for:
  * if statements
  ```
  if(x > 0) {
          // Code
  }
  ```
  * switch statement
  ```
  switch(variable) {
      case 1: System.out.println("one");
          break;
      default: // statement
          break;
  ```
  * while loops
  ```
      while(condition) {
          // Statement
      }
  ```
  * for loops
  ```
  for(int i=0; i<100; i++) {
      // Statements
  }
  ```
  * enhanced for loops (for each loops)
  ```
  for(String s: stringArray) {
       System.out.println(s);
  }
  ```





### Signed by
* Julian Nazareth
* Theodore Montalbano
* Langston Nashold
* Michael Miranda
* Aditya Nese
