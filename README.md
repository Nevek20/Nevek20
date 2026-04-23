import java.util.Arrays;
import java.util.List;

class Desenvolvedor {
    public void apresentar() {
        System.out.println("Perfil carregado com sucesso.");
    }
}

class SobreMim extends Desenvolvedor {
    String nome = "Matheus Guida";
    String area = "Técnico de TI / Dev Back-end";
    
    List<String> contato = Arrays.asList(
        "linkedin.com/in/matheus-guid",
        "github.com/Nevek20"
    );

    String trabalho = "Projetos próprios / Freelance";
    String local = "Americana/SP";
}

class Skills extends Desenvolvedor {
    List<String> linguagens = Arrays.asList(
        "Java",
        "JavaScript",
        "PHP",
        "C#",
        "SQL"
    );

    List<String> bibliotecas = Arrays.asList(
        "Bootstrap",
        "jQuery"
    );

    List<String> frameworks = Arrays.asList(
        "Laravel",
        "Spring Boot"
    );
}

public class README {
    public static void main(String[] args) {

        SobreMim eu = new SobreMim();
        Skills tech = new Skills();

        eu.apresentar();

        System.out.println("Nome: " + eu.nome);
        System.out.println("Área: " + eu.area);
        System.out.println("Trabalho: " + eu.trabalho);
        System.out.println("Local: " + eu.local);
        System.out.println("Contato: " + eu.contato);

        System.out.println("\nLinguagens: " + tech.linguagens);
        System.out.println("Bibliotecas: " + tech.bibliotecas);
        System.out.println("Frameworks: " + tech.frameworks);
    }
}
