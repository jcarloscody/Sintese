# Padrões de Projeto

- **`POO:`** paradigma que tem um conceito que envolve pedaços de dados e que portam comportamentos e estes forma uma coleção de objetos e são construídos sob um plano, as classes.
- **`Classe:`** define a estrutura dos objetos.
- **`Hierarquia de Classes:`**
  - **subclasses** podem sobrescrever o comportamento que herdam das **superclasses**.

## Pilares POO

- **`Abstração:`** moldar objetos do programa com base nos objetos do mundo real. e a abstração disto se moldará apenas aos objetivos específicos.
- **`Encapsulamento:`** é tornar as coisas privadas, esconder estados e comportamentos de outros objetos e criar interfaces para acessa-los.
  - **Interfaces:** permite criar contratos de interação entre objetos.
- **`Herança:`** é a habilidade de construir novas classes em cima de classes já existentes.
  - possibilita **reutilizar** codigos.
- **`Polimorfismo:`** é a habilidade de rastrear a classe real de um objeto e chamar sua implementacao mesmo quando seu tipo real é desconhecido no contexto.


## Relações entre Objetos

- **`Dependência:`** Existe uma dependência entre duas classes se
algumas mudanças na definição de uma das classes pode resultar em modificações em outra classe.
  - é o mais básico e o mais fraco tipo de relações entre classes.
  - Você pode tornar a dependência
mais fraca se você fazer seu código ser dependente de interfaces ou classes abstratas ao invés de classes concretas.
  - **O ocorre quando usamos em tipos em assinaturas de metodos, quando instanciamos objetos atraves de chamadas do construtor.**
- **`Associação:`** um relacionamento no qual um objeto usa ou
interage com outro.
  - um tipo especializado de dependência.
  - Em geral, você usa uma associação para representar algo como
um campo em uma classe
- **`Agregação:`** é um tipo especializado de associação que representa relações individuais (one-to-many), multiplas(many-to-many), e totais (whole-part) entre multiplos objetos.
  - Geralmente, sob agregação, um objeto “tem” um conjunto de outros objetos e serve como um contêiner ou coleção. O componente pode existir sem o contêiner e pode ser ligado através de vários contêineres ao mesmo tempo.
- **`Composição:`** tipo especifico de agregação.
  - porém aqui o componente só pode existir como parte de um conteiner.


 - **`Dependência:`** Classe A pode ser afetada por mudanças na
classe B.
- **`Associação:`** Objeto A sabe sobre objeto B. Classe A depende de B.
- **`Agregação:`** Objeto A sabe sobre objeto B, e consiste de B. Classe A depende de B.
- **`Composição:`** Objeto A sabe sobre objeto B, consiste de B, e gerencia o ciclo de vida de B. Classe A depende de B.
- **`Implementação:`** Classe A define métodos declarados na interface B. objetos de A podem ser tratados como B. Classe A depende de B.
- **`Herança:`** Classe A herda a interface e implementação da classe
B mas pode estendê-la. Objets de A podem ser tratados como
B. Classe A depende de B.



# Introdução Aos Padrões
## O que é um padrão de projeto?

pag 30