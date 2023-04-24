# Cinema
Prova final do curso de ASP .NET

Desenvolver uma API Asp.Net Core para gerenciar vendas de ingressos para um pequeno cinema da cidade. 
Para suportar a venda precisamos criar alguns endpoints antes:

Criar e Atualizar Filmes para exibição (filme deve ter título, duração e sinopse)
Criar e Atualizar Sessões de exibição de um filme (Sessão deve ter dia, horario de inicio, quantidade de lugares, 
preço e filme a ser exibido)

Consultar Sessões passando um filtro por filme e dia
Uma vez os recursos devidamente cadastrados devemos disponiblizar um endpoint para relizar a venda de ingressos.
 O processo de venda de receber qual sessão escolhida e quantidade de ingressos desejados. Devemos tomar cuidado para garantir que a quantidade de lugares da sessão não seja ultrapassado.

Como requisitos não funcionais devemos atender:
-Logs das operações de negócio e erros
-Banco de dados Sql Server		
