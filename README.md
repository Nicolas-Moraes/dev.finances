# dev.finance$
- Esta aplicação foi feita pela equipe da Rocketseat durante o evento Maratona Discover em parceria com Mayk Brito.
- Sou iniciante na área da programação e pretendo atualizar a aplicação com novos conhecimentos adquiridos, visto que foi proposto como desafio aos participantes que desenvolvessem novas funcionalidades no projeto de forma livre.

## Últimas mudanças
### Correção de bug em   formatAmount(value) {
- Havia um bug onde alguns números inseridos em novas transações (como 0.56) retornavam um valor enorme na tabela das transações (como 56.000.000...). Isso ocorria quando adicionávamos um valor com ponto e não vírgula em uma nova transação pois era lido como uma string. 

-  Portanto, foi utilizado o *input[type=number]* para receber o campo em formato de número.

-  Então utilizamos *Math.round( )* para arredondar os números que foram passados como argumento.

## Ideias
- Mudar a cor do card de total caso esteja no negativo para vermelho;
- Adicionar múltiplas parcelas, onde cada uma tenha um mês de diferença da outra; 
- A dicionar um extrato para que seja baixado em formato .txt;
- Adicionar carteiras para diferentes usuários ou diferentes contas bancárias para um mesmo usuário;
- Adicionar temas ou apenas um modo noturno na aplicação;
- Adicionar um filtro de busca para transações. 
