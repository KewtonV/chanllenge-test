![](https://lh3.googleusercontent.com/-SjJCP2AntwI/XoYRxI-hBjI/AAAAAAAABA4/bFi0th7AKGgQFVIOB8L-GiWSZriYhI6MgCK8BGAsYHg/s0/2020-04-02.png)

## Tasks Concluídas

##### Calculadora
- A aplicação não deve ter nenhum tipo de controle de acesso; :ballot_box_with_check:
- A calculadora deverá ter as operações básicas (soma, subtração, multiplicação e divisão); :ballot_box_with_check:
- As operações devem ser realizadas através de um módulo nativo; :negative_squared_cross_mark:

##### Requisitos obrigatórios
- Ter componentes distintos e bem organizados (Ex: Display, Number, Operations, History, etc.);  :ballot_box_with_check:
- Histórico de operações (salve o histórico das operações no estado da aplicação);  :ballot_box_with_check:

##### Requisitos desejáveis (faz vai, vai ser um plus!)
- Realização das operações através de um método (ReactMethod) de um [módulo nativo](https://microsoft.github.io/react-native-windows/docs/native-modules) em C# ou C++; :star:  :negative_squared_cross_mark:
- Estilização dos componentes. Você pode usar algum framework para isso;  :ballot_box_with_check:
- Uso de hooks;  :ballot_box_with_check:
- Uso de componentes funcionais;  :ballot_box_with_check:
- A aplicação poderá ter um loading inicial, como um splash screen;  :ballot_box_with_check:
- Uso de Typescript (na criação do projeto, use um template em TS); :star:  :ballot_box_with_check:
- Uso de Redux para gerenciamento do estado da aplicação; :star:  :ballot_box_with_check:
- Testes unitários na camada JS usando Jest;  :negative_squared_cross_mark:
- Testes unitários na camada nativa;  :negative_squared_cross_mark:

## Comentários Sobre a Implementação do Desafio

#### Splash Screen
  Tentei utilizar o `@react-navigation/native` para colocar uma SplashScreen e depois chamar a Calculadora porém, tive um problema. Na [documentação](https://reactnavigation.org/docs/getting-started) oficial diz: *Note: If using this project with react-native-windows, omit react-native-gesture-handler.* mas, a lib `@react-navigation/native` tem como dependências `react-native-gesture-handler` mesmo omitindo-o na instalação. Então criei o 
  SplashScreen como um *Component*, sendo chamado na screen Home.

#### Commits
  Fiz vários `commit` com o prefixo *(número-da-versão) Tasks-mplementadas* dessa forma, você conseguirá ver cada
  etapa das implementações assim como as dificuldades e mudanças realizadas, pois foi construído tudo do zero.

#### Dificuldades No Perído de Implementação
  Iniciei o projeto na sexta-feira (29/01/2020) a noite e usei meus tempos livres e a madrugada do Sábado e Domingo para implementar pois estavamos em período de implantação de duas funcionalidades importantes no app
  que trabalho. 

  ## Instalação

  - Fazer um `git clone` na branch `development-kewton`.
  - Na pasta raiz do projeto rodar o comando `yarn` para instalar as dependências do *node_modules*.
  - Ainda na raiz do projeto rodar o comando `yarn windows` ou `npx react-native run-windows` para instalar as dependências do windows nativo.

  ## Imagens de Exemplos
  - na raiz do projeto existem duas imagens (`exemplo1` e `exemplo2`) de como o projeto ficou vosualmente.


  ## Agradecimento 
  Desde já agradeço a atenção do Caio e da Martina durante o processo.
  Abraços :grinning: 