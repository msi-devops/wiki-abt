Checklist:

- Criação das URLS na AWS, definição de IPs e de portas a serem utilizadas / redirecionadas
  R: Solicitar ao administrador de infra para que crie as URLS de forma padronizada.
     EX: https://gama.hml.martonis.net/ ou gama.jundiai.prodatamobility.com.br

- Para o MCC será preciso a implantação do GAMA e do MCC
  R: Não existe MCC sem o gerenciamento de acesso realizado pelo GAMA

- Criação do banco de dados ORACLE do Gama
  R: Para a implantação do GAMA, é necessário um banco Oracle próprio, que por exemplo, armazena as URL´s do MCC e ABT

- Inserção das URLs configuradas na AWS no GAMA - Oracle
  R: Configurar o banco do GAMA com as URl´s criadas na AWS pelo administrador de infra.
  EX: ![image.png](/.attachments/image-8ff9907f-a99e-4d05-a22e-bcf4fc4b2185.png)

- Ajuste do banco Oracle - Mercury para MCC (inserção de objetos)
- Criação dos MongoDB para o Gama e MCC
- Ajuste das aplicações para o projeto, com as informações que forem geradas a cima
- Clone do repositório para o AWS
- Publicação dos módulos ja ajustados
- testes