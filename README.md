<h1>Atividades Colaborativa</h1>
<p>Integrantes:</p>
<ul>
    <li>Antonio Lacerda</li>
    <li>Eduardo Denis</li>
</ul>
<h2>Atividade 01</h2>

<p>Responda as seguintes questões propostas do livro Batista & Moraes (2013), página 23, questões de 1 a 8.</p>

<h3>Q1 - Explique qual a função da Máquina Virtual Java (JVM).</h3>
<p>R: A Máquina Virtual Java, também conhecida como JVM é responsável por executar programas Java. A sua função principal é interpretar o conjunto de códigos chamado de bytecode que é gerado pelo compulador Java e após isto, traduzi-lo em um código onde qualquer máquina consiga executa-lo, ou seja, qualquer sistema operacional hospedeiro. É a partir das JVMs que os programas desenvolvidos em Java podem ser executados em diferentes plataformas sem a necessidade de recompilar o seu código fonte. Ademais, as JVMs também tem potencial de gerenciar memória utilizada, alocar e desalocar objetos, além de fornecer outras funcionalidades importantes.</p>

<h3>Q2 - Qual a diferença entre JRE e JDK?</h3>
<p>R: O JRE é o "Ambiente de execução Java". Nele contém a Máquina Virtual Java (JVM) e as bibliotecas necessárias para que um usuário comum execute aplicações Java. <br>Já o JDK é o "Kit de desenvolvimento Java". Nele contém tudo o que está disponível no JRE além de ferramentas que o desenvolvedor utiliza, como por exemplo o javac (compilador) e o javadoc (gerador de documentação).</p>

<h3>Q3 - Crie um programa Java que imprima o seguinte texto "Terminei a primeira aula com um programa Java!"</h3>
<p>R: link do repositório: </p>
 
<h3>Q4 - Compile um programa desenvolvido no exercício anterior. A seguir apague o arquivo .class gerado e tente executar o programa. O que aconteceu?</h3>
<p>R: Após compilar o programa e apagar o arquivo .class, ao tentar executar o programa, foi exibido no terminal um erro informando que não foi possível encontrar ou carregar a classe principal do arquivo java indicado. A mensagem específica foi: "Could not find or load main class PrimeiroPrograma"</p>

<h3>Q5 - Mude o nome do método "main" para "start", compile e execute. O que aconteceu?</h3>
<p>R: Ao substituir o método main pelo método start, o arquivo compilou normalmente, criando um arquivo PrimeiroPrograma.class, contudo, quando executado, o terminal exibiu uma mensagem de erro informando que, o método main não foi encontrado dentro da classe PrimeiroPrograma e indicou que a mesma fosse definida. O terminal deu uma segunda opção que é de utilizar uma extensão. A mensagem original foi: "Main method not found in class PrimeiroPrograma, please define the main method as: public static void main(String[] args) or a JavaFX application class must extend javafx.application.Application".</p>

<h3>Q6 - Crie um programa Java para imprimir duas linhas de texto usando duas linhas de código "System.out", onde aparecerá o seu nome na primeira linha e na segunda linha aparecerá o time para o qual você torce.</h3>
<p>R:
<code>
public class SegundoPrograma {
    public static void main(String[] args) {
        System.out.println("Antonio Lacerda");
        System.out.println("Flamengo");
        System.out.println("Eduardo Denis");
        System.out.println("Corinthians");
    }
}
</code>
</p>

<h3>Q7 - Experimente escrever todo o programa anterior em maiúsculo, compile e execute. O que aconteceu?</h3>
<p>R: O código não chegou a ser compilado e foram listados erros para cada linha de comando. <br\> A mensagem mostrada foi: SegundoPrograma.java:1: error: class, interface, enum, or record expected. </p>

<h3>Q8 - Experimente salvar o arquivo com um nome diferente do nome da classe, compile e execute. O que aconteceu?</h3>
<p>R: O código novamente não foi compilado. A mensagem mostrada foi: NomeDiferente.java:1: error: class SegundoPrograma is public, should be declared in a file named SegundoPrograma.java</p>
