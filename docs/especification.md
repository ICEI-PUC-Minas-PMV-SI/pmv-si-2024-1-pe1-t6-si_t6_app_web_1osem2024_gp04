# Especificações do Projeto

Definição do problema e ideia de solução a partir da perspectiva do usuário. É composta pela definição do  diagrama de personas, histórias de usuários, requisitos funcionais e não funcionais além das restrições do projeto.

Apresente uma visão geral do que será abordado nesta parte do documento, enumerando as técnicas e/ou ferramentas utilizadas para realizar a especificações do projeto.

Caso deseje atribuir uma imagem a sua persona, utilize o site https://thispersondoesnotexist.com/

## Personas

Pedro Paulo tem 26 anos, é arquiteto recém-formado e autônomo. Pensa em se desenvolver profissionalmente através de um mestrado fora do país, pois adora viajar, é solteiro e sempre quis fazer um intercâmbio. Está buscando uma agência que o ajude a encontrar universidades na Europa que aceitem alunos estrangeiros.

Enumere e detalhe as personas da sua solução. Para tanto, baseie-se tanto nos documentos disponibilizados na disciplina e/ou nos seguintes links:

> **Links Úteis**:
> - [Rock Content](https://rockcontent.com/blog/personas/)
> - [Hotmart](https://blog.hotmart.com/pt-br/como-criar-persona-negocio/)
> - [O que é persona?](https://resultadosdigitais.com.br/blog/persona-o-que-e/)
> - [Persona x Público-alvo](https://flammo.com.br/blog/persona-e-publico-alvo-qual-a-diferenca/)
> - [Mapa de Empatia](https://resultadosdigitais.com.br/blog/mapa-da-empatia/)
> - [Mapa de Stalkeholders](https://www.racecomunicacao.com.br/blog/como-fazer-o-mapeamento-de-stakeholders/)
>
Lembre-se que você deve ser enumerar e descrever precisamente e personalizada todos os clientes ideais que sua solução almeja.

## Histórias de Usuários

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Dono de pet         |achar alguém na minha região que cuide do meu pet enquanto viajo           |meu pet não ficar sozinho               |
|Dono de pet         |que o cuidador tenha avaliações de outros donos de pet           |ter confiança que meu pet está em boas mãos               |
|Dono de pet         |ver fotos do local onde meu pet ficará hospedado           |ter certeza que é um local adequado               |
|Dono de pet         |saber antecipadamente o valor total da estadia           |não ter surpresas financeiras               |
|Cuidador de pets         |que potenciais clientes da região me achem           |para ganhar dinheiro               |
|Cuidador de pet         |preciso saber os detalhes da estadia, como horarios que o pet se alimenta, remédios que toma, necessidades especiais e outras observações|Não aceitar um pet que eu nâo consiga cuidar|
|Dono de pet         |pagamento se pela plataforma           |garantir que não vou tomar calote               |

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade | 
|------|-----------------------------------------|----| 
|RF-001| A aplicação deve permitir que o usuário gerencie suas tarefas | ALTA |  
|RF-002| A aplicação deve permitir a emissão de um relatório de tarefas realizadas no mês   | MÉDIA | 
|RF-003| A aplicação deve permitir o cadastramento de cuidadores de pets | ALTA |  
|RF-004| O usuário pode realizar a pesquisa por localidades de cuidadores de pets   | MÉDIA | 
|RF-005| A aplicação deve permitir a ordenação por classificação de estrelas dos melhores cuidadores | ALTA |  
|RF-006| A aplicação deve permitir que os usuários façam comentários referente aos seus pets  | MÉDIA | 
|RF-007| A aplicação deve permitir que o usuário escolha o tipo de acomodação para o seu pet | ALTA |  
|RF-008| A aplicação deve permitir que o usuário escolha a quantidade de dias de hospedagem do pet   | MÉDIA | 
|RF-009| A aplicação de exibir uma lista de atividades para os pets | ALTA |  
|RF-010| A aplicação deve exibir uma lista com o tipo de rações disponíveis durante a hospedagem do pet   | MÉDIA | 
|RF-011| A aplicação deve permitir que o usuário selecione o se o pet será retirado na residência, ou se o cliente irá levá-lo | ALTA |  
|RF-012| A aplicação deve exibir o valor da retirada do pet no local indicado pelo usuário  | MÉDIA | 
|RF-013| A aplicação deve permitir o cadastramento dos pets | ALTA |  
|RF-014| A aplicação deve permitir o casdastramento do dono do pet   | MÉDIA | 
|RF-015| A aplicação deve exibir os valores da hospedagem do pet, com base no tipo de ração, acomodação, quantidade de dias etc | ALTA |  
|RF-016| A aplicação deve permitir que o usuário indique se as vacinas do pet estão em dia  | MÉDIA | 
|RF-017| A aplicação deve permitir que o usuário indique os tipos de vacinas tomadas pelo pet | ALTA |  
|RF-018| A aplicação não deve permitir que o usuário efetue o cadastro do pet sem indicar se o pet está com as vacinas em dia  | MÉDIA | 
|RF-019| O usuário deve cadastrar uma senha forte(letras, dígitos, caracteres especiais) com 8 dígitos | ALTA |  

### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| A aplicação deve ser responsiva | MÉDIA | 
|RNF-002| A aplicação deve processar requisições do usuário em no máximo 3s |  ALTA | 
|RNF-003| A aplicação pode ser acessado via webbrowser | MÉDIA | 
|RNF-004| O banco de dados deve ser atualizado automaticamente | ALTA | 
|RNF-005| A aplicação não pode ter um delay superior a 5 segundos para carregar as informações na tela | ALTA | 
|RNF-006| A aplicação deve ter modos de vizualizaçãoes personalizados |  BAIXA | 
|RNF-007| A aplicação deve permitir a mais de um tipo de ordenação | MÉDIA | 
|RNF-008| A aplicação deve possuir mais de um tipo de pesquisa |  ALTA | 
|RNF-009| A aplicação deve permitir a impressão/download comprovante de pagamento | MÉDIA | 
|RNF-010| A aplicação deve integrar-se com plataformas digitais de pagamento |  ALTA | 
|RNF-011| A aplicação precisa estar online 24hs por dia | MÉDIA | 
|RNF-012| A aplicação precisa ter uma interface amigável com o usuário |  ALTA | 


Com base nas Histórias de Usuário, enumere os requisitos da sua solução. Classifique esses requisitos em dois grupos:

- [Requisitos Funcionais
 (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
 correspondem a uma funcionalidade que deve estar presente na
  plataforma (ex: cadastro de usuário).
- [Requisitos Não Funcionais
  (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
  correspondem a uma característica técnica, seja de usabilidade,
  desempenho, confiabilidade, segurança ou outro (ex: suporte a
  dispositivos iOS e Android).
Lembre-se que cada requisito deve corresponder à uma e somente uma
característica alvo da sua solução. Além disso, certifique-se de que
todos os aspectos capturados nas Histórias de Usuário foram cobertos.

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |


Enumere as restrições à sua solução. Lembre-se de que as restrições geralmente limitam a solução candidata.

> **Links Úteis**:
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)
