Existem vários tipos de testes, dentre os mais importantes, podemos listar:

# Testes Unitários (Unit Test)

O teste unitário tem por objetivo testar a menor parte testável do sistema (unidade), em geral, um método.

Idealmente, o teste unitário é independente de outros testes, validando assim cada parte ou funcionalidade individualmente.

Para seguir um padrão legal do seu teste unitário, ele deve ser capaz de responder as seguintes perguntas:

- O que eu estou testando?
- O que o método deveria fazer?
- Qual o seu atual retorno?
- O que eu espero que retorne?

Se você conseguir olhar para o teste e responder tudo isso, seu teste é bastante válido e irá te ajudar bastante caso algo dê errado.

# Teste de Sanidade (Smoke Test)

Esse é um teste pouco conhecido e pouco utilizado, mas que tem sua utilidade. Originado dos testes de hardware, ele serve para dizer somente se sua aplicação está respondendo corretamente ou não. Na área de web, ele seria basicamente o teste de retorno das rotas e nada mais que isso.

# Teste de Integração (Integration Test)

Teste de integração é a fase do teste de software em que módulos são combinados e testados em grupo. Ela vem depois dos testes unitários, em que os módulos são testados individualmente, e vem antes dos testes de aceitação, em que o sistema completo é testado num ambiente que simula o ambiente de produção.

O teste de integração é alimentado pelos módulos previamente testados individualmente pelos testes unitários, agrupando-os assim em componentes, como estipulado no plano de teste, e resulta num sistema integrado e preparado para o teste de sistema.

# Teste de Aceitação (Acceptance Test)

O teste de aceitação verifica se todo o projeto funciona de acordo com sua especificação, ele já é um teste final, que visa juntar todos os módulos e testá-los em conjunto já a uma interface gráfica. Esses testes visam aferir se algo na interface faça o sistema não funcionar ou que dificulte o acesso ao usuário, um exemplo seria se um input não estivesse aparecendo para que dados fossem inseridos.

Filipe Gomes Furtado
RA 1800555
