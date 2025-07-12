```java
public class Desenvolvedor {
    public static void main(String[] args) {
        SobreMim sobreMim = new SobreMim();
        Skills skills = new Skills();

        System.out.println(SobreMim);
        System.out.println(Skills);
    }
}

class SobreMim {
    private String nome = "Pedro Lucas Luz Costa";
    private String area = "Backend";
    private String linguagemQueOdeia = "Python";
}

class Skills {
    private String[] marcacao = {"HTML", "CSS"};
    private String[] frontEnd = {"JavaScript"};
}

```
