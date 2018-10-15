O teste existe para avaliar as características ou qualidades de algo e esse significado persiste em qualquer coisa que exista "test". 
A diferença é que no devops; engenharia de software o teste é feito em pequenas partes, de forma que todo conteúdo implementado é testado antes, dessa forma é possivel garantir a qualidade do trabalho final além de evitar problemas como atrasos e custos indevidos durante o projeto.

Eles fazem com que se torne válido todas as edições e garantir que tudo esteja dentro dos parametros solicitados.

Em testes, a Verificação é uma atividade, a qual envolve a análise de um sistema para certificar se este atende aos requisitos funcionais e não funcionais. Já a Validação, é a certificação de que o sistema atende as necessidades e expectativas do cliente. O processo de Validação e Verificação, não são processos separados e independentes.

Com a automação de testes, é possível evitar as atividades manuais e repetitivas e que sobrecarregam tanto o orçamento quanto o cronograma de uma empresa. Além disso, ainda há a possibilidade da criação de testes mais abrangentes, elaborados e que estejam de acordo com as funcionalidades e exigências de seus produtos. Entretanto, por mais bem preparada e capacitada que a sua gestão seja, imprevistos e problemas podem acontecer nesse percurso — e é por isso que os testes no DevOps devem ser implementados com o intuito de inserir a máxima eficiência em suas operações.

Dentro de testes, temos o Test case, que é um conjunto de condições e váriaveis que proporciona ao programador determinar se o sistema está trabalhando corretamente e se os requisitos estão sendo atendidos conforme o determinado. O processo de desenvolvimento de test cases também ajuda a encontrar problemas nos requisitos e no design da aplicação.

Os test cases agrupados e categorizados em conjuntos formam Test suit, que visando a atender de forma otimizada a necessidade do planejamento,a análise de um sistema e o seu desenvolvimento. São personalizáveis, podem englobar vários tipos de testes diferentes, de maneira que ajuda de forma aperfeiçoada o programador a executar e reportar o status da aplicação.

Além disso, existem vários tipos de testes, dentre os mais importantes, podemos listar:

Testes Unitários (Unit Test)
O teste unitário tem por objetivo testar a menor parte testável do sistema (unidade), em geral, um método.

Idealmente, o teste unitário é independente de outros testes, validando assim cada parte ou funcionalidade individualmente.

Para seguir um padrão legal do seu teste unitário, ele deve ser capaz de responder as seguintes perguntas:

O que eu estou testando?
O que o método deveria fazer?
Qual o seu atual retorno?
O que eu espero que retorne?
Se você conseguir olhar para o teste e responder tudo isso, seu teste é bastante válido e irá te ajudar bastante caso algo dê errado.

Teste de Sanidade (Smoke Test)
Esse é um teste pouco conhecido e pouco utilizado, mas que tem sua utilidade. Originado dos testes de hardware, ele serve para dizer somente se sua aplicação está respondendo corretamente ou não. Na área de web, ele seria basicamente o teste de retorno das rotas e nada mais que isso.

Teste de Integração (Integration Test)
Teste de integração é a fase do teste de software em que módulos são combinados e testados em grupo. Ela vem depois dos testes unitários, em que os módulos são testados individualmente, e vem antes dos testes de aceitação, em que o sistema completo é testado num ambiente que simula o ambiente de produção.

O teste de integração é alimentado pelos módulos previamente testados individualmente pelos testes unitários, agrupando-os assim em componentes, como estipulado no plano de teste, e resulta num sistema integrado e preparado para o teste de sistema.

Teste de Aceitação (Acceptance Test)
O teste de aceitação verifica se todo o projeto funciona de acordo com sua especificação, ele já é um teste final, que visa juntar todos os módulos e testá-los em conjunto já a uma interface gráfica. Esses testes visam aferir se algo na interface faça o sistema não funcionar ou que dificulte o acesso ao usuário, um exemplo seria se um input não estivesse aparecendo para que dados fossem inseridos.

Os testes podem ser divididos em Caixa Branca e Caixa Preta:

Teste Caixa Branca é um teste do tipo estrutural, que tem por viés uma perspectiva interna do software, no qual, o analista tem acesso à estrutura do software e também ao código fonte, o que possibilita uma análise mais específica e assertiva de cada parte ou função do produto, que pode ser analisada isoladamente com maior precisão a fim de verificar se o software está bem estruturado e funciona corretamente.

Já o Teste de Caixa Preta, também conhecido como teste funcional, tem como objetivo verificar se a implementação da aplicação foi feita como especificado, se ela desempenha os requisitos definidos e identificar as possíveis falhas funcionais que impossibilitem o funcionamento do software. Nesse tipo de teste o analista não tem acesso ao código fonte nem à estrutura do software.

A fim de organizar os testes, temos a Pirâmide de teste, que é uma ferramenta estratégica que existe para separar testes automatizados em três grandes blocos:  Na base encontramos os testes unitários em maior quantidade por conta de seu baixo custo de implementação e execução. Cada empresa define o seus testes Unitários.  Na camada intermediária, para testar as chamadas de serviços e APIs, encontramos os testes de integração, que atravessam a unidade do código fonte.  Por fim, no topo da pirâmide encontramos os testes end-to-end, que são de interface e aceitação; por serem em menor quantidade focando os fluxos principais do sistema e os feedbacks de interface, dado seu maior custo de desenvolvimento.

De acordo com a pirâmide de testes proposta pelo Google, temos a seguinte divisão para a execução de testes, seguindo a proporção 70/20/10, ou seja:

70% de testes unitários;
20% de testes de integração;
10% de testes de ponta a ponta.
Isso serve para tentar sempre evitar uma pirâmide invertida (focada em teste de ponta a ponta), ou em formato de ampulhta (foco em testes unitários e ponta a ponta, mas nenhum em integração).
