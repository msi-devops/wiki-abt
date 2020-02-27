Checklist:

- Para o MCC será preciso a implantação do GAMA e do MCC
  R: Não existe MCC sem o gerenciamento de acesso realizado pelo GAMA

- Criação das URLS na AWS, definição de IPs e de portas a serem utilizadas / redirecionadas
  R: Solicitar ao administrador de infra para que crie as URLS de forma padronizada. deverão ser criadas, inicialmente, duas URL´s.
     Uma para o gama e outra para o mcc:

     EX: https://gama.hml.martonis.net/ ou gama.jundiai.prodatamobility.com.br
         https://portal.mcc.hml.martonis.net ou portal.mcc.jundiai.prodatamobility.com.br


    

- Criação do banco de dados ORACLE do Gama
  R: Para a implantação do GAMA, é necessário um banco Oracle próprio, que por exemplo, armazena as URL´s do MCC e ABT.
     ![image.png](/.attachments/image-d8d4bd98-902e-422f-a963-e9175e77cea4.png)

- Inserção das URLs configuradas na AWS no GAMA - Oracle
  R: Configurar o banco do GAMA com as URl´s criadas na AWS pelo administrador de infra.
  EX: ![image.png](/.attachments/image-8ff9907f-a99e-4d05-a22e-bcf4fc4b2185.png)

- Ajuste do banco Oracle - Mercury para MCC (inserção de objetos)
  R: O MCC também utiliza-se da base de dados do Mercury pré-existente no projeto. Abrir atividade para o DBA para que execute esses scripts.
![image.png](/.attachments/image-fc75a271-8caa-4a7b-b7f0-37e7a529c8d7.png)

- Criação dos MongoDB para o Gama e MCC
   R: Deverão ser criados os banco de dados MongoDB e ajustados na publicação do projeto.
   Provavelmente todos utilizarão o Mongo Atlas.
   Abaixo, exemplo:
![image.png](/.attachments/image-89f96568-16f6-46b6-a476-dd2efed8398f.png)


- Ajuste das aplicações para o projeto, com as informações que foram geradas.
  R: Com as regras de negócios definidas pela equipe de coordenação, será preciso ajustar o parâmetros no Mercury e mongo DB.

   EX: Mercury![image.png](/.attachments/image-4a0964b8-9cc9-4f03-a421-6c5ce1ff3f99.png)
Mongo
![image.png](/.attachments/image-ad3604bc-eddb-4a80-98f2-5acd1103b289.png)
    

- Obtenção da Chave PEM
  R: A infraestrutura deverá fornecer a chave para acesso via ssh ai servidor na AWS.

- Clone do repositório para o AWS
  R: Enviar os arquivos do projeto para o servidor.

- Publicação dos módulos ja ajustados, com as informações do banco de dados Mercury e Oracle.

