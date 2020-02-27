Checklist de Ambiente de garagem e sua infraestrutura: 


- Configuração da APN list. 
  R: Qual será utilizada? Publica, privada própria ou privada Prodata?
    

- Ajuste das tasks de comunicação
  R: Para o funcionamento do MCC, será preciso que o arquivo PAR2 esteja subindo durantes as comunicações. 

- Instalação dos chips de dados nos validadores.
  R: Sem dados o MCC não funcionará.

- Versão de validador apropriada para utilização do MCC
  R: O Firmware deverá entregar de forma antecipada versão de validador própria do projeto e ajustada ao MCC.

- Cobertura da operadora para testes.
  R: Procurar utilizar as operadoras com melhor cobertura regional.

- Arquivo PAR2, que deve ser criado e ajustado no tasks (VW_EOD_DYNAMICPARAMETERS_2)
   R: Esse aquivo que deverá estar inserido na task de comunicação e que deverá ser gerado junto com o pacote de EOD.

- Ajuste deve ser realizado pela implantação e DBA (scripts)
  R: Ajustes relacionados ao EOD deverão ser ajustados pela equipe de implantação, solicitando atualização e inserção dessas configurações no banco de dados