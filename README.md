# Junit5JupiterMaven

## 1. A primeira parte descreveremos jUnit5 

Atualmente em meu trabalho vejo a crescente busca por qualidade nas entregas das Releases,
porem o que ainda vejo e testes sendo feitos me modo manual, não penso que seja desnecessario pois 
ainda e relevante, mas estamos trabalhando com tecnologia e penso que e necessario a utilizarmos para redução de tempo 
e melhoria dos processos. <br/>
E lendo um artigo interessante no mediun sobre o assunto, decidi criar varios artigos levando em consideração ferramentas de testes em Java, 
muitos me perguntaram, por que em Java, a resposta e simples e a que mais uso e gosto, não quero entrar aqui em discussoes qual linguagem e 
a melhor mesmo sabendo que e Java (Seria minha resposta). <br/>
 
Muitos dizem que o teste é uma das disciplinas que separa os desenvolvedores fortes dos fracos e os profissionais dos amadores, penso
que seja um diferencial e que sim, melhora e muito as qualidades dos codigos, outra técnica seria codigo limpo(famoso clean code) e S.O.L.ID, assuntoS para
quem sabe um novo artigo. <br/>
 
Não se trata de seguir Test Driven Development (TDD), Behavior Driven Development (BDD) ou qualquer outra metodologia de teste, 
mas saber o mínimo necessario para se escrever um código para testar adequadamente o seu código automaticamente (Para muitos isto e complexo). <br/>

Muitos desenvolvedores Java escrevem testes de unidade e testes de integração que são executados automaticamente durante o tempo de construção, 
em muitas vezes e cobrado uma porcentagem de teste que gira em torno de 80% a 100% do seu código, porem tambem a discussoes sobre e que e necessario
ser testado, porem não e o foco aqui neste momento. <br/>

A unica coisa que digo e o que e visto os teste de automação estão crescendo exponencialmente, devido a cobrança dos clientes e conscientização das 
equipes que viram nos teste uma forma de melhorar a qualidade da entrega e a decrescimo de retrabalho em bugs encontrados nos teste das equipes de testes manuaias,
ou de teste de aceitação por parte do cliente.  <br/>

Ao me deparar com os desafios de teste notei que muitas ferramentas no que podem te ajudar cada uma tem suas premissas e qualidades e e sempre bom apreender novas 
ferramentas , pois no futuro podemos tomar a decisão de qual e mais produtiva ou atende com perfeição ou o mais efetiva na solução do problema exposto.  <br/>

Este Artigo esta devidido em partes onde abordarei sobre e se baseia em um artigo escrito por javinpaul (10+ Test Automation Libraries for Java Developers) 
na plataforma medium e aconselho que leiam o mesmo e uma leitura rapida e que pode dar ao leitor deste artigo uma visão da abordagem deste artigo, pois irei trabalhar cada
ferramenta descrita por ele e os codigos estarão disponivel em meu github (https://github.com/weder96) 


01 . Junit
https://medium.com/@mari_azevedo/qualidade-e-junit-introduzindo-automatiza%C3%A7%C3%A3o-de-testes-unit%C3%A1rios-do-seu-software-java-no-dia-a-dia-849611de5574

O que é o jUnit ?
Segundo o site(http://junit.wikidot.com/), 
JUnit é um Framework open-source utilizado para facilitar o desenvolvimento de códigos em Java verificando se os resultados gerados pelos métodos são os esperados. Caso não sejam, o JUnit exibe os possíveis erros que estão ocorrendo nos métodos. Essa verificação é chamada de teste unitário ou teste de unidade.

Ao validar esse Afirmação nos deparamos com outra questão.

Mas o que são testes unitários?

Um teste unitário simplesmente o teste da menor parte testável de um programa.
Se você programa em uma linguagem que suporte paradígma funcional por exemplo, a menor parte testável  
então será uma função. No caso de orientação a objetos seria o teste de um método de seu objeto.

no site da jUnit a versão na data deste artigo e a versão 5, (https://junit.org/junit5/docs/current/user-guide/).

O que é o JUnit 5?

Sendo o mesmo um É um framework open-source para construção de testes automatizados em Java, hospedado no
https://github.com/junit-team/junit5/ sendo formado das versões anteriores do JUnit, 
o JUnit 5 é composto por vários módulos diferentes de três subprojetos diferentes.

JUnit 5 = (JUnit Platform + JUnit Jupiter + JUnit Vintage)


A Plataforma JUnit serve como base para o lançamento de estruturas de teste na JVM. 
Ele também define a API TestEngine para desenvolver uma estrutura de teste executada na plataforma. 
Além disso, a plataforma fornece um Console Launcher para iniciar a plataforma a partir da linha de comando e um Runner baseado no JUnit 4 para executar qualquer 
TestEngine na plataforma em um ambiente baseado no JUnit 4. 
O suporte de primeira nivel para a plataforma JUnit também existe em IDEs populares (
IntelliJ IDEA, 
Eclipse, 
NetBeans e
Visual Studio Code) e ferramentas de construção (Gradle, Maven e Ant).

JUnit Jupiter é a combinação do novo modelo de programação e modelo de extensão para escrever testes e extensões no JUnit 5. 
O subprojeto Jupiter fornece um TestEngine para executar testes baseados em Jupiter na plataforma.

O JUnit Vintage fornece um TestEngine para executar testes baseados no JUnit 3 e JUnit 4 na plataforma.

O jUnit requer Java 8 ou superior para executar, Entretanto os códigos que foram compilado com versões anteriores do JDK pode ser testado devido a modo suporte a versão anteriores.


### Relevant Articles:
- [10+ Test Automation Libraries for Java Developers] (https://medium.com/javarevisited/10-test-automation-libraries-for-java-developers-e40cb61dcd49)
- [A Guide to JUnit 5 Extensions](https://www.baeldung.com/junit-5-extensions)
- [Inject Parameters into JUnit Jupiter Unit Tests](https://www.baeldung.com/junit-5-parameters)
- [Mockito and JUnit 5 – Using ExtendWith](https://www.baeldung.com/mockito-junit-5-extension)
- [The Order of Tests in JUnit](https://www.baeldung.com/junit-5-test-order)
- [Running JUnit Tests Programmatically, from a Java Application](https://www.baeldung.com/junit-tests-run-programmatically-from-java)
- [Testing an Abstract Class With JUnit](https://www.baeldung.com/junit-test-abstract-class)
- [Guide to Dynamic Tests in JUnit 5](https://www.baeldung.com/junit5-dynamic-tests)
- [Determine the Execution Time of JUnit Tests](https://www.baeldung.com/junit-test-execution-time)
- [@BeforeAll and @AfterAll in Non-Static Methods](https://www.baeldung.com/java-beforeall-afterall-non-static)
- [The java.lang.NoClassDefFoundError in JUnit](https://www.baeldung.com/junit-noclassdeffounderror)

