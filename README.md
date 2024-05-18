```java
public class Desenvolvedor {
    public static void main(String[] args) {
        SobreMim sobreMim = new SobreMim();
        Skills skills = new Skills();

        System.out.println(sobreMim);
        System.out.println(skills);
    }
}

class SobreMim {
    private String nome = "Pedro Lucas Luz Costa";
    private String area = "Backend";
    private String objetivo = "Trabalhar em casa";
    private String linguagemQueOdeia = "Python";
}

class Skills {
    private String[] marcacao = {"HTML", "CSS"};
    private String[] frontEnd = {"JavaScript", "TypeScript"};
    private String[] backEnd = {"Python", "Java", "Node.js"};
    private String[] frameworks = {"Tailwind CSS", "React", "Next.js", "Angular"};
    private String[] bancoDeDados = {"MySQL", "MongoDB", "PostgreSQL"};
}

```
