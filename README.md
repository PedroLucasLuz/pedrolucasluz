```java
import Desenvolvedor from "PedroLucasluz";

public class SobreMim extends Desenvolvedor {
    private String nome = "Pedro Lucas Luz Costa";
    private String area = "Backend";
    private String objetivo = "Trabalhar em casa";
    private String linguagemQueOdeia = "Python";

    @Override
    public String toString() {
        return "Nome: " + nome + "\n" +
               "Área: " + area + "\n" +
               "Objetivo: " + objetivo + "\n" +
               "Linguagem que odeia: " + linguagemQueOdeia;
    }
}

public class Skills extends Desenvolvedor {
    private String[] marcacao = {"HTML", "CSS"};
    private String[] frontEnd = {"JavaScript", "TypeScript"};
    private String[] backEnd = {"Python", "Java", "Node.js"};
    private String[] frameworks = {"Tailwind CSS", "React", "Next.js", "Angular"};
    private String[] bancoDeDados = {"MySQL", "MongoDB", "PostgreSQL"};

    @Override
    public String toString() {
        return "Marcação: " + String.join(", ", marcacao) + "\n" +
               "Frontend: " + String.join(", ", frontEnd) + "\n" +
               "Backend: " + String.join(", ", backEnd) + "\n" +
               "Frameworks: " + String.join(", ", frameworks) + "\n" +
               "Banco de Dados: " + String.join(", ", bancoDeDados);
    }
}

public class Main {
    public static void main(String[] args) {
        SobreMim sobreMim = new SobreMim();
        Skills skills = new Skills();

        System.out.println(sobreMim.toString());
        System.out.println(skills.toString());
    }
}
```
