# Avaliação Sprint 4 - Programa de Bolsas Compass UOL / AWS e Univesp

Avaliação da quarta sprint do programa de bolsas Compass UOL para formação em machine learning para AWS.

***

## Execução (Código Fonte)

Criar uma API em Python com acesso a banco de dados para otimizar o acesso a outra API pública.

**Especificações**:

* Escolher uma API pública (https://any-api.com/, ou qualquer outra, e **deve ser diferente dos demais grupos**);
* Desenvolver uma função Python em AWS Lambda para:
  * disponibilizar uma API própria que consulta a API pública ou o banco de dados;
  * permitir a consulta ao histórico de consultas armazenado;
  * realizar os seguintes passos de consulta a partir da solicitação do usuário: 
    * consultar o banco de dados local;
    * se não contiver o que foi solicitado:
      * consultar a API pública;
      * armazenar os dados consultados no banco de dados local;
    * uma vez obtidos os dados, responder ao usuário;
* Configurar um AWS API Gateway para invocar as funções no Lambda;
* Armazenar as consultas em DynamoDB;
* O grupo pode ficar livre quanto a outros recursos AWS adicionais a este, que entendam como úteis à solução;
* Referência de como executar: [Tutorial: Using Lambda with API Gateway](https://docs.aws.amazon.com/lambda/latest/dg/services-apigateway-tutorial.html).



***

## O que será avaliado?

- Projeto em produção na AWS
- Arquivos de configuração utilizados
- Código Python desenvolvido
- Forma de publicação de códigos no git ao longo do desenvolvimento
- Organização geral do código fonte
  - Estrutura de pastas
  - Estrutura da lógica de negócio
  - Divisão de responsabilidades em arquivos/pastas distintos
  - Otimização do código fonte (evitar duplicações de código)
- Objetividade do README.md
- Modelo de organização da equipe para o desenvolvimento do projeto

***

## Entrega

- Aceitar o convite do repositório da sprint-4-pb-aws-univesp
- **O trabalho deve ser feito em grupos de três ou quatro pessoas**
  - Não repetir formação de grupos já criados em sprints anteriores
- Criar uma branch no repositório com o formato grupo-número (Exemplo: grupo-1)
- Subir o trabalho na branch com um README.md
  - documentar detalhes sobre como a avaliação foi desenvolvida
  - dificuldades conhecidas
  - como utilizar o sistema
  - 🔨 código fonte desenvolvido (Sugestão: pasta `src`)
- O prazo de entrega é até às 12h do dia 03/04/2023 no repositório do github ([https://github.com/Compass-pb-aws-2023-Univesp/sprint-4-pb-aws-univesp](https://github.com/Compass-pb-aws-2023-Univesp/sprint-4-pb-aws-univesp)).
