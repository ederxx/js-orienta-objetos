Parabéns! Você concluiu o curso JavaScript: introdução a Orientação a Objetos! Ao longo deste treinamento nós conhecemos vários conceitos interessantes de orientação a objetos como o que são classes, o que são atributos e quais as vantagens de termos atributos privados ou estáticos, como criarmos métodos de acesso do tipo set e get (de modo a encapsularmos comportamentos dos atributos da classe), a funcionalidade dos construtores (que tornaram nosso código mais sucinto e legível) e assim por diante.

Também aprendemos a criar e utilizar métodos e como utilizar a composição de classes em nosso favor, utilizando tipos de referência (as próprias classes) para fazermos as operações que desejávamos. Isso culminou em casos como o método transferir(), que utiliza a linguagem do próprio negócio em sua operação,

transferir (valor, conta) {
    const valorSacado = this.sacar(valor);
    conta.depositar(valorSacado);

}COPIAR CÓDIGO
Aqui temos um nível de abstração mais alto, com uma lógica mais fácil de ser comunidacada às outras pessoas da equipe. Ainda existem diversos outros conteúdos de orientação a objetos para aprendermos, e trabalharemos com eles nos próximos cursos.
