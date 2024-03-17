## Personas

Ana tem 28 anos e é uma profissional de marketing em uma empresa internacional. Sua carreira exige que ela viaje pelo menos duas vezes ao mês para participar de reuniões, conferências e eventos em diferentes partes do país e do mundo. Ela tem um adorável labrador chamado Max. Quando Ana viaja, deixa Max em um hotel para cachorros, o qual nem sempre tem disponibilidade e é caro. Quando não há disponibilidade, Max fica sozinho e amigos vão à sua casa para colocar comida e água para ele. Ana gostaria de conhecer outras opções na região, mas precisa de mais informações e avaliações sobre outros locais.

Marcos tem 35 anos, tem um hotel para pets em sua cidade, gostaria de encontrar mais clientes em potencial, marcos atende principalmente cachorros em seu hotel.

Pedro tem 22 anos e é um estudante universitário que mora em um apartamento pequeno e não tem tempo suficiente para cuidar de um animal de estimação em tempo integral. No entanto, ele adora a companhia de pets e gostaria de poder hospedá-los em seu espaço durante as férias ou fins de semana prolongados para ganhar um dinheiro extra.

Sara tem 30 anos e é uma profissional ocupada que ama seus dois cachorros, mas com o ritmo agitado do trabalho, ela muitas vezes se sente culpada por deixá-los sozinhos em casa. Ela procura uma plataforma onde possa encontrar hospedeiros confiáveis para cuidar de seus pets enquanto ela está no escritório ou viajando a negócios.

Lúcia tem 65 e é uma pessoa apaixonada por animais, que dedicou sua vida a cuidar deles. Agora que está aposentada, ela tem muito tempo livre e gostaria de preencher esse tempo oferecendo hospedagem para pets em sua casa. Ela busca uma plataforma onde possa conectar-se com donos de animais que buscam um ambiente acolhedor e cuidadoso para seus pets durante suas ausências.



## Histórias de Usuários

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Dono de pet         |achar alguém na minha região que cuide do meu pet enquanto viajo           |meu pet não ficar sozinho               |
|Dono de pet         |que o cuidador tenha avaliações de outros donos de pet           |ter confiança que meu pet está em boas mãos               |
|Dono de pet         |ver fotos do local onde meu pet ficará hospedado           |ter certeza que é um local adequado               |
|Dono de pet         |saber antecipadamente o valor total da estadia           |não ter surpresas financeiras               |
|Cuidador de pets         |que potenciais clientes da região me achem           |para ganhar dinheiro               |
|Cuidador de pet         |preciso saber os detalhes da estadia, como horarios que o pet se alimenta, remédios que toma, necessidades especiais e outras observações|Não aceitar um pet que eu não consiga cuidar|
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
