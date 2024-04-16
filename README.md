👋public class Manuzokas {

    public static void main(String[] args) {
        Desenvolvedor eu = new Desenvolvedor();

        eu.setNome(🙋‍♀️: "Manuella");
        eu.setGenero("Feminino");
        eu.setFormacao(🎓:"Análise e Desenvolvimento de Sistemas no Instituto Federal do Rio Grande do Sul");
        eu.setHabilidades(💻:"Java, Programação Orientada a Objetos, Banco de Dados");
        eu.setAprendendo(📚:"Aprendendo atualmente Padrões de Projetos, Gerência de Projeto, Spring, Hibernate e JPA");
        eu.setBuscando(🔍:"Buscando uma oportunidade de estágio na área!");
        eu.setQualidades(⚡:"Comprometida com prazos, orientada a resultados, persistente ao encontro de soluções, adepta as necessidades, anseio constante por crescimento profissional e quaisquer oportunidades que agreguem conhecimento");
        eu.tempoDisponivel:(⏰:"Turno da manhã e turno da tarde (integral)");

        System.out.println(eu.apresentacao());
    }
}

class Desenvolvedor {

    private String nome;
    private String formacao;
    private String habilidades;
    private String aprendendo;
    private String genero;
    private String buscando;
    private String qualidades;
    private String tempoDisponivel;

    🛠️ // Insira aqui os métodos getters e setters

    public String apresentacao() {
        return "Olá, meu nome é " + nome + ".\n"
            + "Estou cursando " + formacao + ".\n"
            + "Minhas principais habilidades são: " + habilidades + ".\n"
            + "Atualmente, estou aprendendo " + aprendendo + ".\n"
            + "Minhas principais qualidades são: " + qualidades + ".\n"
            + "Meu tempo disponível para quaisquer oportunidades que aparecam: " + tempoDisponivel + ".\n"
            + "Estou animado para contribuir para projetos interessantes que agreguem bagagens!";
    }
}
