```
import java.math.BigDecimal;

public class Main {

    public static void main(String[] args) {

    BigDecimal regularbonus = new BigDecimal("0.3");
    BigDecimal specialbonus = new BigDecimal("0.6");
    BigDecimal total = regularbonus.add(specialbonus); // сложение
        
        System.out.println(total); }
        
}
```

Run code result:

![run result](/Users/Yana/precision/proposed code bd.png)