# APSSDC
## HEADER 1
### HEADER 2
#### HEADER 3
##### HEADER 4
###### HEADER 5

*ITALIC 

**BOLD TEXT**

~~STRIKE TEXT~~

[LINK](adityatekkali.edu.in)

* IT
  * SECTION A
    * 01
    
1. IT
  1. SECTION-A
    
![alt](https://www.facebook.com/images/fb_icon_325x325.png)

:smile:

:innocent:

:yum:

:sunglasses:

:heart_eyes:

```java

public class Main {

  public static void main(String[] args) {

    int num = 29;
    boolean flag = false;
    for (int i = 2; i <= num / 2; ++i) {
      // condition for nonprime number
      if (num % i == 0) {
        flag = true;
        break;
      }
    }

    if (!flag)
      System.out.println(num + " is a prime number.");
    else
      System.out.println(num + " is not a prime number.");
  }
}
