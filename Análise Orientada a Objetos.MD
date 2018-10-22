# Introdução a Análise Orientada a Objetos
## O que é análise orientada a objetos?

Análise orientada a objetos é uma abordagem técnica popular para análisar e projetar aplicações ou sistemas de software através da aplicação de conceitos de programação orientada a objetos, além da utilização de modelagem visual ao longo do ciclo de desenvolvimento para melhorar a comunicação entre interessados e a qualidade do produto em desenvolvimento.

Compreende a identificação de requisitos de engenharia de software e desenvolvimento de especificações de software em termos de modelos de objetos, onde cada representação de objeto pode possuir caracteristicas e comportamentos, além de ser relacionar e interagir com outros objetos para realizar as tarefas esperadas do sistema.

# Bases da Análise Orientada a Objetos

Ao longo do amadurecimento do paradigma orientado a objetos diversas idéias e abordagens foram tentadas. Muitas delas foram descartadas, enquanto algumas se mantiveram e ajudaram a estabelecer as bases para a orientação a objetos. 
O foco principal na Orientação a Objetos são os objetos propriamente ditos, nos quais o sistema é constituido e na comunicação entre eles. Esses objetos, por sua vez, são categorizados em classes. Dessa forma, o principal processo da Análise Orientada à Objetos é a descoberta de classes para serem modeladas, não objetos.

## Conceitos-chaves da análise orientada a objetos

### Abstração

A abstração é um conceito essencial para identificarmos classes. O processo de abstrair consiste na seleção de alguns aspectos de domínio do problema a modelar, desconsiderando os irrelevantes para o nível de abstração em questão. Dessa forma, é indispensável utilizar da abstração é indispensável para abstrair objetos reais, pois no mundo real, quase tudo é complexo.


### Objetos

O projeto dos primeiros sistemas era centralizado em volta de processos e poucos desses sistemas se mostravam adaptáveis as mudanças externas quando elas aconteciam. Argumenta-se que um dos principais motivos para o grande número de fracassos (e cada vez maior) neste paradigma de desenvolvimento fosse o aumento da complexidade dos sistemas de software. Este aumento por sua vez resultante principalmente de dois fatores: 1) A evolução dos computadores levava a demanda por sistemas mais complexos e; 2) Os proprios sistemas se tornavam mais complexos conforme evoluiam.
O paradigma orientado a objetos surgiu e se popularizou com a proposta de simplificar a compreensão dos sistemas através da abstração do sistema como um conjunto de objetos trabalhando colaborativamente para a realização das tarefas esperadas do sistema.
 
No paradigma orientado a objetos, um objeto é uma representação de um elemento concreto ou abstrato do mundo real que possui como caracteristicas principais:

* Uma identidade que distingue cada objeto particular de outros objetos no sistema.
* Estados que determinam as propriedades caracteristicas de um objeto, bem como os valores dessas propriedades ao longo da existência do objeto.
* Comportamentos que representam as atividades externamente visiveis realizadas por um objeto e um termos de mudanças de em seu estado.

A representação de um mesmo objeto do mundo real pode variar entre aplicações diferentes, porque de maneira geral, é desejável que um objeto represente apenas os caracteristicas e comportamentos que tenham valor dentro das necessidades da aplicação em que ele é utilizado. Por exemplo, em um sistema de um estacionamento a placa de um veiculo pode ser um atributo importante, e que deveria estar presente nos objetos de carros do sistema. Por outro lado em um jogo de corrida talvez esse atributo seja desnecessário e por essa razão os objetos de carros deste sistema podem não possuir este atributo.

De forma analoga, em um sistema de estacionamento provavelmente não existe a necessidade de representar o comportamento de acelerar que os carros possuem, enquanto em um jogo de corrida esse comportamento normalmente é fundamental.

Um objeto também pode ser a representação de algo que possui uma existencia fisica no mundo real, como uma cadeira, ou a representação de algo que possui existencia conceitual, como o tempo.

### Classes

Classes podem ser entendidas como especificações para tipos de objetos. As caracteristicas e comportamentos de um objeto são descritas em classes, de forma que todo objeto é um membro de uma classe e criado a partir de uma classe. Chamamos a criação de um objeto a partir de uma classe de instanciação e consequentemente dizemos que o objeto criado é uma instancia da classe que o descreve.

Diversas instâncias podem ser criadas a partir de uma mesma classe e todas as instâncias de uma classe (ou seja, todos os objetos criados a partir dela) possuem as caracteristicas e comportamentos definidos pela classe. Por exemplo, a partir de uma classe 'Cachorro' com os atributos 'tamanho', 'raça' e 'cor' e os comportamentos 'correr' e 'latir' podem ser criados quantos objetos 'Cachorro' desejarmos e todos eles possuirão um tamanho, uma raça e uma cor, além dos comportamentos de correr e latir. Apesar disso cada cachorro será um objeto diferente, com uma identidade diferente, além de poderem possuir estados diferentes (ou seja, um cachorro pode ter tamanho grande e cor cinza, enquanto outro cachorro pode ter tamanho pequeno e cor preta). Adicionalmente, os comportamentos dos objetos podem variar de acordo com seus estados (por exemplo, um cachorro com tamanho grande pode latir mais alto que um cachorro com o tamanho pequeno).

### Herança

A herança é uma das principais e mais importantes características da Orientação à Objetos, onde é permitido o compartilhamento de atributos e métodos entre objetos que possuem o mesmo relacionamento hierárquico, organizando e otimizando o código construído.

Exemplo: 

A classe |Animal| possui os atributos |nome| e |quantidadeDePatas|

A classe |Cachorro| extende da classe |Animal|
A classe |Gato| extende da classe |Animal|

Portanto, |Cachorro| e |Gato| possuem os atributos |nome| e |quanidadeDePatas|

# Análise
O principal propósito da análise é determinar o que o sistema deve fazer em termos de soluções para um determinado conjunto ode problemas, sem determinar qual metodologia deve ser aplicada para isso. 
No caso da análise orientada a objetos, o objetivo é compreender e representar os problema a ser solucionado pelo sistema em termos de objetos. O resultado da análise orientada a objetos geralmente é um conjunto de modelos do sistema, representando-o como um agregado de objetos conceituais, com caracteristicas e comportamentos, que se relacionam para cumprir as tarefas esperadas do sistema.

## Requisitos
O objetivo principal de qualquer sistema de software é satisfazer um conjunto de necessidade declaradas ou implicitas dos indivíduos interessados nele. Este objetivo é evidentemente, muito genérico, e por essa razão é necessário um conjunto de atividades que possibilitem identificar quais são essas necessidades. Esse conjuntos de atividades é que chamamos de análise, e quando ela é realizada em termos de objetos, relacionamentos e responsabilidades a chamamos de análise orientada a objetos.

O resultado da análise é geralmente expresso em um ou mais documentos referidos tipicamente como "Especificação de Requisitos" ou "Requisitos do Sistema".

## Casos de Uso
Casos de uso são histórias escritas em formato de texto, amplamente utilizadas na análise orientada a objetos para descobrir e registrar requisitos. Eles influenciam muitos aspectos de um projeto e servem de entrada para diversos artefatos subsequentes no desenvolvimento de um sistema.
Um caso de uso descreve como um determinado ator interage com o sistema para realizar uma tarefa com algum objetivo, podendo ocorrer em diferentes cenários. Por exemplo, vender um item, cadastrar um cliente, emitir um relatório, etc...
Um ator é uma entidade como um pessoa, um sistema de computador ou uma organização que interage com o sistema com um determinado papel, comportamento ou objetivo. Por exemplo, um caixa de supermercado é o ator que interage com o sistema de vendas para realizar uma venda.
Um cenário é uma sequencia específica de ações e interações entre os atores e o sistema dentro de um caso de uso. Por exemplo, dentro de um caso de uso "realizar pagamento" podem existir diversos cenários como pagar com dinheiro, pagamento com cartão, pagamento a vista, pagamento a prazo, parcelamento, etc... Cada cenário pode exigir que o ator ou sistema se comporte de maneira diferente, mas o objetivo geral de todos os cenários está relacionado com o objetivo do caso de uso. Ou seja, embora um caso de uso possa ter diversos cenários, como é o caso do nosso cenário "realizar pagamento", todos eles estão envolvidos com o objetivo de tratar uma execução de pagamento.

Abaixo temos um exemplo de um caso de uso representado em formato resumido:

<b>Processar Venda</b>: Um cliente chega ao caixa com itens de venda. O caixa utiliza o sistema de vendas para registrar cada item de venda e sua quantidade. O sistema apresenta o total corrente e os detalhes de cada linha de item. O cliente insere as informações de pagamento, que o sistema valida e registra. O sistema atualiza o inventário. O cliente recebe um recibo do sistema e sai com o itens.

### Casos de Uso e Análise Orientada a Objetos
Casos de uso não são obrigatórios para realizar análise orientada a objetos, e, em termos gerais, um caso de uso não é considerado um modelo orientado a objetos. apesar disso, casos de uso podem ajudar bastante na análise orientada a objetos, pois através deles diversos objetos, relacionamentos e responsabilidades podem ser identificados.
Cada substantivo em um caso de uso é um candidato a um possivel objeto e cada verbo é um candidato a um comportamento de um ou mais objetos. Por exemplo: no casos de uso "processar venda" apresentado na seção anterior podemos identificar os substantivos "venda", "cliente", "caixa", "item de venda", "linha de item", "pagamento", "inventário" e "recibo". Todos estes substantivo são candidatos à uma classe de objetos e provavelmente a maioria deles de fato seria transformada em uma classe.
Também podemos identificar alguns comportamentos no mesmo caso de uso como "registrar item de venda", "apresentar total da venda", "detalhar linha de item", inserir informações de pagamento", "validar pagamento", "registrar pagamento", "atualizar inventário" e "gerar recibo". Novamente, todos esses comportamentos são candidatos à comportamentos de alguma classe, como por exemplo, o comportamento "atualizar inventário" pode ser escolhido como um comportamento da classe "inventário".
Casos de uso também ajudam a identificar atributos de objetos. Em nosso caso de uso de exemplo podemos ler "O caixa utiliza da item de venda e sua quantidade", e isso sugere que um item de venda possui um atributo quantidade.
Ainda é possivel identificar alguns relacionamentos entre os objetos utilizando casos de uso. Nosso caso de uso diz que o cliente chega ao caixa com os itens de venda, e isso pode indicar que exista algum relacionamento entre clientes e itens devenda.

## Modelo de Domínio
O modelo de domínio é o modelo mais importante e clássico da análise orientada a objetos. Ele ilustra os conceitos mais relevantes de um domínio. Além disso ele também serve como um fonte de inspiração para projetar alguns objetos de software e como entrada  para diversos outros arterafos no ciclo de desenvolvimento.
Um modelo de dominio é uma representação visual das classes conceituais (ou objetos do mundo real) em um domínio. Ele é composto basicamente de três elementos:
<li>Classes conceituais ou objetos do domínio <li>
<li>Associações entre as classes conceituais <li>
<li>Atributos das classes conceituais<li>
 
 ### Classes Conceituais
 Uma classe conceitual é uma coisa, conceito ou ideia que é relevante dentro do vocaboluário do domínio. Uma classe conceitural pode ser considerada em termos de seu simbolo, intenção e extensão. O Simbolo é a palavra ou imagem que representa a classe conceitual, em outras palavras o simbolo é o nome da classe conceitual. A intenção é a definição da classe conceitual, ou seja, é a explicação do que a classe representa dentro do domínio em que ela é empregada. A extensão por sua vez é o conjunto de exemplos onde a classes conceitual é aplicada.
 Por exemplo, considere a classe conceituaal para o evento de uma transação de compra e venda. Podemos escolher para nomear essa classe conceitual pelo simbolo **Venda**. A intenção de uma Venda pode ser definida como "representa o evento de transação de compra e venda". A extensão de Venda são todas os exemplos de vendas; ou seja, o conjunto de todas as instancias de venda.
 
 
 
 ### Modelo de Domínio Não é um Modelo de Objetos de Software
Apesar da semelhança entre modelos de dominio de diagramas de classes de software é importante compreender que um modelo de domínio ilustra apenas classes conceituais (ou seja, objetos, coisas ou conceitos relevantes no domínio do problema no "mundo real") e não objetos de software como classes de Java ou C#. Por esta razão elementos de software, como janelas de sistema, bancos de dados, responsabilidades ou métodos não são adequados para um modelo de domínio, exceto quando quando esses elementos façam parte do domínio modelado. 


# Modelagem
A modelagem pode ocorrer à partir de artefatos como: relatórios, documentos, textos, outros sistemas e qualquer outro artefato que faça parte do domínio do problema. O analista investiga estes artefatos e identifica o vocabulário relevante. Cada léxico deste vocabulário dá origem a uma classe conceitual no modelo de domínio. Para o processo de modelagem, é importante que exista um tipo de padronizador, para que uma modelagem possa ser mais universal e entendida mais facilmente. Nesse quesito, pode-se utilizar a UML.

## UML
A UML é uma notação padrão para diagramação amplamente utilizada para modelar soluções e sistemas orientados a objetos, que facilita a transmitir as idéias justamente por se tratar de uma notação padronizada, onde a grande maioria dos elementos utilizados possui um (ou alguns pouco) significado pré-estabelecido. Apesar disso é importante não confundir a habilidade de criar modelos UML com a habilidade de executar boas análises orientadas a objetos.
## Principais diagramas
### Diagrama de Casos de Uso
Esse diagrama documenta o que o sistema faz do ponto de vista do usuário. Em outras palavras, ele descreve as principais funcionalidades do sistema e a interação dessas funcionalidades com os usuários do mesmo sistema. Os diagramas de casos de uso são basicamente compostos por: ator, cenário, caso de uso e comunicação. Sendo o ator o usuário do sistema, o cenário uma sequência de eventos decorrentes de uma interação com o usuário, caso de uso uma tarefa ou funcionalidade e a comunicação o que liga o ator ao caso de uso.

### Diagrama de Classes
Representa uma coleção de classes e seus inter-relacionamentos. Uma classe, na UML (e na Orientação a Objetos também) possui três compartimentos, sendo para: Nome, Atributos e Operações. No diagrama podemos ter também relacionamentos de Associação, Agregação, Composição e Generalização (Herança).

### Diagrama de Objetos
Representa um retrato, em tempo de execução, dos objetos do software e seus inter-relacionamentos. O diagrama de objetos modela as instâncias das classes contidas no diagrama de classes, isto é, o diagrama de objetos mostra um conjunto de objetos e seus relacionamentos no tempo. Estes diagramas são importantes para construir os aspectos estáticos do sistema.


## Vantagens e Desvantagens

| Vantagem| Desvantagem |
| ------------- |:-------------:|
| Os princípios de encapsulamento fazem com que os dados não sejam alterados por outras partes do sistema. | Não é possível definir quais objetos irão definir um design otimizado. |
| A modularização provida pela AOO implica em uma redução da complexidade do software. | A funcionalidade restrita a objetos pode dificultar o desenvolvimento de sistemas que são intrinsecamente procedurais. |
| Facilita a manutenção e a melhoria de sistemas, inclusive aumentando para larga escala, diferentemente de um sistema desenvolvido com base em uma análise estruturada. | Sistemas consomem mais memória(heap) do que sistemas que utilizam o paradigma de programação estruturada. |
| Possibilidade de se desenvolver software em um nível de abstração mais elevado. | Dificuldade de aprendizado para desenvolvedores habituados a um modelo estrutural. |


# Referências
1. https://en.wikipedia.org/wiki/Object-oriented_analysis_and_design
2. https://www.tutorialspoint.com/object_oriented_analysis_design/ooad_object_oriented_analysis.htm
3. Object-Oriented Analysis, Design and Implementation: An Integrated Approach 2nd ed. 2015 Edition
4. https://docente.ifrn.edu.br/givanaldorocha/disciplinas/engenharia-de-software-licenciatura-em-informatica/analise-orientada-a-objetos
