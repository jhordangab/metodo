# Introdução a Análise Orientada a Objetos
## O que é análise orientada a objetos?

Análise orientada a objetos é uma abordagem técnica popular para análisar e projetar aplicações ou sistemas de software através da aplicação de conceitos de programação orientada a objetos, além da utilização de modelagem visual ao longo do ciclo de desenvolvimento para melhorar a comunicação entre interessados e a qualidade do produto em desenvolvimento.

Compreende a identificação de requisitos de engenharia de software e desenvolvimento de especificações de software em termos de modelos de objetos, onde cada representação de objeto pode possuir caracteristicas e comportamentos, além de ser relacionar e interagir com outros objetos para realizar as tarefas esperadas do sistema.


## Conceitos-chaves da análise orientada a objetos

Ao longo do amadurecimento do paradigma orientado a objetos diversas idéias e abordagens foram tentadas. Muitas delas foram descartadas, enquanto algumas se mantiveram e ajudaram a estabelecer as bases para a orientação a objetos. 

### Objetos

Objetos formam o conceito central da orientação a objetos, como o próprio nome sugere.
O projeto dos primeiros sistemas era centralizado em volta de processos, os quais eram suscetíveis a mudança, e quando essa mmudança acontecia, pouquissimos sistemas se mostravam 'reutilizáveis' e adaptáveis.
No paradigma orientado a objetos, um objeto é uma representação de um elemento concreto ou abstrato do mundo real que possui como caracteristicas principais:

* Uma identidade que distingue cada objeto particular de outros objetos no sistema.
* Estados que determinam as propriedades caracteristicas de um objeto, bem como os valores dessas propriedades ao longo da existência do objeto.
* Comportamentos que representam as atividades externamente visiveis realizadas por um objeto e um termos de mudanças de em seu estado.

A representação de um mesmo objeto do mundo real pode variar entre aplicações diferentes, porque de maneira geral, é desejável que um objeto represente apenas os caracteristicas e comportamentos tenham valor dentro das necessidades da aplicação em que ele é utilizado. Por exemplo, em um sistema de um estacionamento a placa de um veiculo pode ser um atributo importante, e que deveria estar presente nos objetos de carros do sistema. Por outro lado em um jogo de corrida talvez esse atributo seja desnecessário e por essa razão os objetos de carros deste sistema podem não possuir este atributo.

De forma analoga, no sistema do estacionamento provavelmente existe necessidade de representar o comportamento de acelar que os carros possuem, enquanto em um jogo esse comportamento pode ser crucial.

Um objeto também pode ser a representação de algo que possui uma existencia fisica no mundo real, como uma cadeira, ou a representação de algo que possui existencia conceitual, como o tempo.

### Classes

Classes podem ser entendidas como especificaçes para tipos de objetos. As caracteristicas e comportamentos de um objeto são descritas em classes, de forma que todo objeto é um membro de uma classe e criado a partir de uma classe. Chamamos a criação de objeto a partir de uma classe de instanciação e consequentemente dizemos que o objeto criado é uma instancia daquela classe.

Diversas instâncias podem ser criadas a partir de uma classe e todas as instâncias de uma classe (ou seja, todos os objetos criados a partir dela) possuem as caracteristicas e comportamentos definidos pela classe. Por exemplo, a partir de uma classe 'Cachorro' com os atributos 'tamanho', 'raça' e 'cor' e os comportamentos 'correr' e 'latir' podem ser criados quantos objetos 'Cachorro' desejarmos e todos eles possuirão um tamanho, uma raça e uma cor, além dos comportamentos de correr e latir. Apesar disso cada cachorro será um objeto diferente, com uma identidade diferente, além de poderem possuir estados diferentes (ou seja, um cachorro pode ter tamanho grande e cor cinza, enquanto outro cachorro pode ter tamanho pequeno e cor preta). Adicionalmente, os comportamentos dos objetos podem variar de acordo com seus estados (por exemplo, um cachorro com tamanho grande pode latir mais alto que um cachorro com o tamanho pequeno).



## Vantagens e Desvantagens

# Bases da Análise Orientada a Objetos
## Abstração
## Classes e Objetos
## Interfaces

# Relacionamentos
## Associações
## Herança
## Genericidade

# Linguagens Orientadas a Objetos e suas Caracteristicas
## Organização de classes
## Classes utilitárias
## Resoluçes em tempo de execução

# Padrões de Projeto
## O que são padrões de projeto?
## Principais padrões de projeto

# Análise
## Visão Geral
## Requisitos

# Projeto
## Projeto
## Implementação

# Modelagem
## UML
## Principais diagramas

# Referências
1. https://en.wikipedia.org/wiki/Object-oriented_analysis_and_design
2. https://www.tutorialspoint.com/object_oriented_analysis_design/ooad_object_oriented_analysis.htm
3. Object-Oriented Analysis, Design and Implementation: An Integrated Approach 2nd ed. 2015 Edition
