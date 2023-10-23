Obs: os arquivos estão na brainch master, estou melhorando meus conhecimentos em Github.


====================================================== DESAFIO ======================================================

O desafio consiste em fazer um processo ETL, no vídeo explicativo foi mostrado o processo utilizando uma API, embora,
foi dada a liberdade para utilizar outras formas de trabalho.

===================================================== INTRODUÇÃO ====================================================

O PIX é um projeto de 2016 que foi implantado no Brasil no final de 2020, com o intuito de dar mais segurança, facilitar e agilizar transações bancárias, obteve uma ótima aceitação e adesão logo no primeiro trimestre de adoção. Nos anos seguinte, o PIX obteve um crescimento significativo, novas funcionalidades foram incorporadas ao sistema tornando mais seguro evitando assim práticas de roubo e furto que vinham ocorrendo. Atualmente o PIX é a principal forma de pagamento entre os brasileiros, sendo usado por pessoas e empresas, a cada dia se consolida e atinge números impressionantes.

====================================================== ETAPAS ======================================================

==== Coleta: os dados foram obtidos no site do Banco central de Brasil: https://olinda.bcb.gov.br/olinda/servico/Pix_DadosAbertos/versao/v1/aplicacao#!/recursos/TransacoesPixPorMunicipio#eyJmb3JtdWxhcmlvIjp7IiRmb3JtYXQiOiJqc29uIiwiJHRvcCI6MTAwLCJEYXRhQmFzZSI6IjIwMjMifSwicHJvcHJpZWRhZGVzIjpbMCwxLDIsMyw0LDUsNiw3LDgsOSwxMCwxMSwxMiwxMywxNF19 em formato JASON contendo informações sobre a utilização do PIX desde seu ano de implementação (2021 a 2023) até os ano de 2023.

=== Tratamento: O arquivo JASON foi importado para o Microsoft Excel, sendo utilizado o Power Query para fazer o tratamento inicial. Foram retiradas algumas colunas, acrescentadas outras, modificado o tipo algumas entre outras modificações pontuais.
Já no ambiente Microsoft Excel, foi construída uma tabela dinâmica que serviu de base para as análises realizadas.
Embora possua informações que podem gerar maiores e diversos tipos de análise, me ative ao crescimento da utilização do PIX por ano, por estado e por região do país.

=== Carregamento: Após tratamento no Power Query, o arquivo é automaticamente carregado em uma tabela, para melhorar o processo de análise, criei uma tabela dinâmica, dessa forma foi possível agrupar dados específicos como região, estados e anos analisados possibilitando observar com mais clareza o comportamento ascendente dos dados analisados.

=== Visualização (extra): Criei um Dashboard simples onde plotei alguns gráficos para ter uma melhor visualização das informações que consegui extrair dos dados.

====================================================== CONCLUSÕES ======================================================

* Após 1 ano de lançamento o PIX cresceu mais de 3.000%, dobrou no segundo ano e obteve um aumento de 12% no terceiro ano mostrando um período de consolidação.
* São Paulo lidera o número de transações seguido por Rio de janeiro e Minas Gerais
* Em 2022 o valor das transações CPF superou o de CNPJ, fato ocorrido no ano anterior em São Paulo. 
* A região Sudeste se destaca em número e valores de transações tendo por pivô o estado de São Paulo.

======================================================= EM BREVE =======================================================

O próximo passo será utilizar a base de dados para construir um relatório dinâmico no Microsoft Power BI, com isso será possível ter uma visualização mais interativa e dinâmica.

=========================================================================================================================

=== Melquisedeque Oliveira =========
 
