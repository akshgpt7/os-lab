# OS LAB ASSIGNMENT 1

### Aksh Gupta
### 19104005
### B-11

GitHub profile link: https://github.com/akshgpt7
Repo: https://github.com/akshgpt7/os-lab/

Code:

```java
import java.util.*;
class firstassignment{
  public static void main(String arg[]){
    Scanner x = new Scanner(System.in);
    System.out.println("Enter number of elements-");
    int n = x.nextInt();
    int a[] = new int [n];
    for(int i = 0; i < n; i++){
      a[i] = x.nextInt();
     }
    Arrays.sort(a);
    System.out.println("Sorted array-");
    for(int j = 0; j < n; j++){
     System.out.print(a[i]+" ");
    }
  }
}
```
